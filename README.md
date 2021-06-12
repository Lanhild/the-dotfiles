<p align="center">
  <a name="top" href="#octocat-hello-newcomer-enjoy-your-visit-">
     <img alt="the-dotfiles@Lanhild" height="60%" width="100%" src="https://i.ibb.co/1zdvVd3/icon.png"/>
  </a>
</p>

##  
### :octocat: Hello newcomer! Enjoy your visit! <img alt="" align="right" src="https://badges.pufler.dev/visits/Lanhild/the-dotfiles?style=flat-square&label=&color=fa74b2&logo=GitHub&logoColor=white&labelColor=373e4d"/>

This main repository contains sub-repositories, with each of them having the configurations files to install the dotfiles inside them.

Don't hesitate to open an issue if there is a need to!

## Sections
1. [Details](#here-are-some-details-about-my-setup)
2. [Changelogs](#changelogs)
3. [Dependencies](#dependencies)
4. [Automatic Installation](#automatic-method)
5. [Manual Installation](#manual-method)
6. [Special Notes](#notes)

## Here are some details about my setup
### Components
> Basic components installed on most of my setups

- **Window Manager**               • [bspwm](https://github.com/baskerville/bspwm) and [i3-gaps]() :art: <kbd>tiling</kbd>
- **Shell**                        • [zsh](https://www.gnu.org/software/bash/) :shell: 
- **Terminal**                     • [kitty](https://sw.kovidgoyal.net/kitty/) <kbd>>_</kbd>
- **Compositor**                   • [picom](https://github.com/ibhagwan/picom) :shaved_ice: blurred windows and rounded corners! <kbd>fork
</kbd>

### Applications
> List of the applications used on my setups.

- **Status Bar**                   • [polybar](https://github.com/polybar/polybar) fully configurable modules!
- **Notifications Daemon**         • [dunst](https://github.com/dunst-project/dunst) infinite configuration possibilities!
- **Application Launcher**         • [rofi](https://github.com/davatorium/rofi)
- **File Manager**                 • [ranger](https://github.com/ranger/ranger) :bookmark: blazingly fast!
- **Music Player**                 • [mpd](https://www.musicpd.org/) + [ncmpcpp](https://github.com/ncmpcpp/ncmpcpp) <kbd>music</kbd>
- **CLI Text Editor**              • [neovim](https://neovim.io/) <kbd>good product</kbd>

---
## Changelogs <img alt="" align="right" src="https://img.shields.io/github/repo-size/Lanhild/the-dotfiles?style=flat-square&label=.files&color=cf8ef4&labelColor=282828"/>

Updates about the recent changes on the repository. See the [commits history](https://github.com/Lanhild/the-dotfiles/commits/main) for the older changes. 

<details>
  <summary><strong>v0.9</strong> <kbd>latest</kbd></summary>
  
  **Major Update**:
  - Added the first files
  - Added the README
  
  For the rest, see the [commits history](https://github.com/Lanhild/the-dotfiles/commits/main). You can also check out my [website](https://lanhild.github.io/portfolio).
  
</details>

<details>
  <summary><strong>v1.0</strong> <kbd>coming soon!</kbd></summary>

  **Major Update**:
  - Will add the complete installation scripts
  - Will add/update the README of each sub-repository to provide more information

  For the rest, see the [commits history](https://github.com/Lanhild/the-dotfiles/commits/main). You can also check out my [website](https://lanhild.github.io/portfolio).

</details>

# Dependencies
List of the dependencies for the setups. See this [wiki section]() for more extensive information about the dependencies packages and their usage.

|---|---|---|
|rofi
|

# Installation
##
## Automatic Method
**Recommended way to install**

You can install any of the setups you'd wish to by simply using the installation script provided in this main repository. If you do not wish to use the script for any reason, you can always install everything manually

##
## Manual Method
> The packages listed below aren't hard dependencies; they are packages I judged necessary to the well-functionning of the setups.
>   
> **Warning!**  
> They do have as mandatory packages `sudo`, `bash` and `coreutils`
>
> The commands below need to be run as `sudo` or `doas`.

> **Warning!**  
> - You may prefer to use `polkit-gnome` over `lxsession`/`lxpolkit`, because, currently the `lxsession` package in Gentoo/Linux is no good(literal dependencies hell).
  
<details>
  <summary><strong>Arch-based dependencies</strong> <kbd>pacman</kbd></summary>

```sh
pacman -S git mpd ncmpcpp 
```

</details>

##  
### Installation (dotfiles) 
  
  > **Depending on what you wish to have/not have, you can omit some directories**

##
## Notes
---
<details>
<summary><strong>Small note to developers</strong></summary>
You can modify the content of the installation scripts in various ways. Though, make sure to follow the comments in them and also make sure that you know what you do while modifying, as the majority of the scripts are very sensitive to modfications, and they can break easily.
</details>


- Special thanks to **[r/unixporn](https://www.reddit.com/r/unixporn/).**
- **All the great artists out there who make wonderful wallpapers and icons.**
