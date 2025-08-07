# 🛠️ New Mac Setup Guide (with Homebrew & Dotfiles)

This guide helps you set up a new macOS machine using this repo's Homebrew configuration and dotfiles.

---

## 🚀 1. Prerequisites

On the new machine, install Homebrew:

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

---

## 📦 2. Setup

1. **Download the Brewfile** and navigate to the directory containing it

2. **Install all packages** using Homebrew Bundle:
   ```bash
   brew bundle --file=./Brewfile
   ```

---

## ✅ 3. Final Steps

1. **Restart your terminal** to apply all changes

2. **Run any post-install scripts** (if included in this repo)

3. **Log into services** such as:
    - Git configuration
    - GitHub CLI authentication
    - Other development tools

4. **Configure SSH keys** for secure repository access

---

## 📝 Notes

- Make sure you have an active internet connection during setup
- The installation process may take several minutes depending on the number of packages
- Some applications may require additional configuration after installation