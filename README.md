# PineconeMC-Linux

The fork of [PineconeMC](https://elyprismlauncher.github.io/) with integrated support for Ely.by accounts (Earlier ElyPrismLauncher)

<div align="center"> 

![PineconeMC](PineconeMC.svg)

</div>

> [!IMPORTANT]
> Works only on SteamDeck, Arch Linux and Arch-based distributions (SteamOS, CachyOS, EndeavourOS, Manjaro, Garuda, Artix and etc)

## Manual Installation

> [!NOTE]
> Make sure you have the base-devel and git installed, if not so install it by running in the terminal:
>
> ```
> sudo pacman -S --needed base-devel git
> ```

Then install the PineconeMC by running in the terminal:

```
git clone https://github.com/Esconine/PineconeMC-Linux && cd PineconeMC-Linux && makepkg -si
```

## Uninstallation

If you want to uninstall the PineconeMC and all its dependencies run in the terminal:

```
sudo pacman -Rns pineconemc-bin pineconemc-bin-debug && rm -rf ~/PineconeMC-Linux
```
