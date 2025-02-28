# Fonts

All open-source fonts I've collected for personal use, except **San Francisco Fonts**.

## To Install Manually on Linux

```bash
mkdir -p ~/.local/share/
git clone --depth=1 https://github.com/dpi0/fonts $HOME/.local/share/
```

## San Francisco

- **SF Pro Display** and **SF Pro Text**: <https://github.com/sahibjotsaggu/San-Francisco-Pro-Fonts>
- **LigaSFMono Nerd Font**: <https://github.com/shaunsingh/SFMono-Nerd-Font-Ligaturized>

## Inter & Merriweather

- **Inter**:
  - <https://fonts.google.com/specimen/Inter>
  - <https://github.com/rsms/inter>
  - <https://rsms.me/inter/>
- **Merriweather**:
  - <https://fonts.google.com/specimen/Merriweather>
  - <https://fonts.adobe.com/fonts/merriweather>

## Nerd Fonts

<https://www.nerdfonts.com/font-downloads>  
<https://github.com/ryanoasis/nerd-fonts/tree/master/patched-fonts/JetBrainsMono#tldr>

### TL;DR

- Pick your font family:
  - If you are limited to monospaced fonts (because of your terminal, etc.), pick a font with `Nerd Font Mono` (or `NFM`).
  - If you want to have bigger icons (usually around 1.5 normal letters wide), pick a font without `Mono`, i.e., `Nerd Font` (or `NF`). Most terminals support this, but YMMV.
  - If you work in a proportional context (GUI elements, editing presentations, etc.), pick a font with `Nerd Font Propo` (or `NFP`).

The following Nerd Fonts can easily be installed via `pacman` on Arch. If not, download and install manually.

- **JetBrainsMono Nerd Font**:
  - <https://www.programmingfonts.org/#jetbrainsmono>
  - <https://github.com/ryanoasis/nerd-fonts/tree/master/patched-fonts/JetBrainsMono>
  - Install:
    ```bash
    sudo pacman -S ttf-jetbrains-mono-nerd
    ```
- **FiraMono Nerd Font** _(not FiraCode)_:
  - <https://www.programmingfonts.org/#fira>
  - <https://github.com/ryanoasis/nerd-fonts/tree/master/patched-fonts/FiraMono>
  - Install:
    ```bash
    sudo pacman -S otf-firamono-nerd
    ```
- **CommitMono Nerd Font**:
  - <https://www.programmingfonts.org/#commit-mono>
  - <https://github.com/ryanoasis/nerd-fonts/tree/master/patched-fonts/CommitMono>
- **Monaspace Nerd Font**:
  - <https://monaspace.githubnext.com/>
  - <https://github.com/ryanoasis/nerd-fonts/tree/master/patched-fonts/Monaspace>
  - Install:
    ```bash
    sudo pacman -S otf-monaspace-nerd
    ```
