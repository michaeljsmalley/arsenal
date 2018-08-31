## What's `arsenal` about?

This is a place where I maintain the inventory of all of the tools, utilities, and even gimmicky binaries I've stumbled upon and used to some extent over the years. Like most things I put up on [my GitHub](https://github.com/michaeljsmalley) or [the blog](www.smalleycreative.com), it serves two purposes:

* Personal benefit: It's nice keeping all of the tools I've come across in an organized place it here so I don't need to remember it
* Community benefit: It's nice sharing this mess with humanity. 😀

I primarily use MacOS at work, and Arch Linux at home, so installation instructions for those platforms are documented here, but most of these tools are available on other platforms.

### CLI Tools

* **`htop`**: A better `top` (https://github.com/hishamhm/htop)
    * Installation
        * MacOS: `brew install htop`
        * Arch: `pacman -Sy htop`

* **`ag`**: The Silver Searcher (https://github.com/ggreer/the_silver_searcher)
    * Installation
        * MacOS: `brew install ag`

* **`yay`**: AUR client for Arch Linux (https://github.com/Jguer/yay)
    * Installation
        * Arch:
            ```bash
            git clone https://aur.archlinux.org/yay.git
            cd yay
            makepkg -si
            ```

* **`inxi`**: System information utility (https://github.com/smxi/inxi)

* **`bat`**: Better than `cat` (https://github.com/sharkdp/bat)
    * Installation
        * MacOS: `brew install bat`
        * Arch: `pacman -Sy bat`

* **`prettyping`**: `ping` with a text-based response graph (https://github.com/denilsonsa/prettyping)
    * Installation
        * MacOS: `brew install prettyping`

* **`jq`**: JSON processor (https://stedolan.github.io/jq/)
    * Installation
        * MacOS: `brew install jq`
        * Arch: `pacman -Sy jq`

* **`tldr`**: Simple and community driven `man` pages (https://tldr.sh/)
    * Installation
        * MacOS (Note: Requires `npm`, and `-g` means it installs globally): `npm install -g tldr`

### GUI Tools

* **Bear**: Markdown-based note taking app for MacOS (http://www.bear-writer.com/)

### Novelties

* 
