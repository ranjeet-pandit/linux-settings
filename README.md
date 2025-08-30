# 🚀 My Developer Dotfiles

This repo contains my **personalized terminal setup** for productivity and aesthetics on Linux (Ubuntu/Pop!_OS).  
It includes **Zsh**, **Starship prompt**, useful plugins, and synced configs.

---

## ⚡ Features
- **Zsh** with aliases and plugins
- **Starship prompt** with:
  - Git branch & status
  - Node.js, Java, Python versions
  - Docker & Kubernetes context
  - Memory usage, battery, and command duration
  - Current time in **12-hour AM/PM**
- **TLDR** for quick command references
- **Dotfiles Git-managed** for portability

---

## 📦 Installation

### 1. Install Zsh
```bash
sudo apt install zsh -y
chsh -s $(which zsh)

sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
Enable them by editing ~/.zshrc:
2. Install Starship Prompt
curl -sS https://starship.rs/install.sh | sh


Add to bottom of ~/.zshrc:

eval "$(starship init zsh)"
plugins=(git zsh-autosuggestions zsh-syntax-highlighting)
# Useful plugins
git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions




Also for working with External Monitor chnage to Wayland from default x11 and also make the permanent fix by editing wayland to tru in custom.config
git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting

curl -sS https://starship.rs/install.sh | sh

