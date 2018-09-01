---
toc: true
---

## What's `arsenal` about?

This is a place where I maintain the inventory of all of the tools, utilities, and even gimmicky binaries I've stumbled upon and used to some extent over the years. Like most things I put up on [my GitHub](https://github.com/michaeljsmalley) or [the blog](www.smalleycreative.com), it serves two purposes:

* Personal benefit: It's nice keeping all of the tools I've come across in an organized place it here so I don't need to remember it
* Community benefit: It's nice sharing this mess with humanity. 😀

I primarily use MacOS at work, and Arch Linux at home, so installation instructions for those platforms are documented here, but most of these tools are available on other platforms.

### CLI Tools

* **[htop](https://github.com/hishamhm/htop)**: A better `top`.
    * Installation
        * MacOS: 
            ```bash
            brew install htop
            ```
        * Arch: 
            ```bash
            pacman -S --noconfirm htop
            ```

* **[ag](https://github.com/ggreer/the_silver_searcher)**: The Silver Searcher.
    * Installation
        * MacOS:
            ```bash
            brew install ag
            ```

* **[yay](https://github.com/Jguer/yay)**: AUR client for Arch Linux.
    * Installation
        * Arch:
            ```bash
            git clone https://aur.archlinux.org/yay.git
            cd yay
            makepkg -si
            ```

* **[inxi](https://github.com/smxi/inxi)**: System information utility.

* **[bat](https://github.com/sharkdp/bat)**: Better than `cat` 
    * Installation
        * MacOS:
            ```bash
            brew install bat
            ```
        * Arch:
            ```bash
            pacman -S --noconfirm bat
            ```

* **[prettyping](https://github.com/denilsonsa/prettyping)**: `ping` with a text-based response graph.
    * Installation
        * MacOS:
            ```bash
            brew install prettyping
            ```

* **[jq](https://stedolan.github.io/jq/)**: JSON processor.
    * Installation
        * MacOS:
            ```bash
            brew install jq
            ```
        * Arch:
            ```bash
            pacman -S --noconfirm jq
            ```

* **[tldr](https://tldr.sh/)**: Simple and community driven `man` pages.
    * Installation
        * MacOS (Note: Requires `npm`, and `-g` means it installs globally):
            ```bash
            npm install -g tldr
            ```

* **[neofetch](https://github.com/dylanaraps/neofetch)**: System information utility.
    * Installation
        * MacOS:
            ```bash
            brew install neofetch
            ```
        * Arch:
            ```bash
            pacman -S --noconfirm neofetch
            ```

### GUI Tools

* **[Bear](http://www.bear-writer.com/)**: Markdown-based note taking app for MacOS

### Novelties

* 
