# Dockerfile
FROM mcr.microsoft.com/devcontainers/jekyll

# Install wget if not already installed
RUN apt-get update && apt-get install -y wget

# Download .zshrc from remote address

USER vscode
RUN wget https://raw.githubusercontent.com/Riverscapes/environment/master/nar-ys.zsh-theme -O ~/.oh-my-zsh/custom/themes/nar-ys.zsh-theme
RUN wget https://raw.githubusercontent.com/Riverscapes/environment/master/.aliases -O ~/.aliases
RUN wget https://raw.githubusercontent.com/Riverscapes/environment/master/.zshrc -O ~/.zshrc

