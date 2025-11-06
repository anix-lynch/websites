# 🌐 My Websites & Portfolios

This repository contains git submodules pointing to my important website repositories.

## 📂 Websites

| Website | Repository | Description |
|---------|------------|-------------|
| [anix-lynch.github.io](https://anix-lynch.github.io) | [anix-lynch.github.io](./anix-lynch.github.io/) | Main portfolio website (GitHub Pages) |
| [gozeroshot.dev](https://gozeroshot.dev) | [gozeroshot.dev](./gozeroshot.dev/) | Business website for AI/data engineering services |
| [anixlynch.github.io](https://anixlynch.github.io) | [anixlynch.github.io](./anixlynch.github.io/) | Older portfolio for audio AI work (GitHub Pages) |

## 🔍 Quick Access

To work on any website:
```bash
# Clone this repo with submodules
git clone --recursive https://github.com/anix-lynch/websites.git
cd websites

# Work on a specific website
cd anix-lynch.github.io
# Make changes...
git add .
git commit -m "Update portfolio"
git push
```

## 🔄 Update All

To update all website repositories:
```bash
git submodule update --remote --recursive
```

---

*These are my source of truth repositories for my online presence*
