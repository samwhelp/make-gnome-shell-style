

# Home

| Link | GitHub |
| ---- | ------ |
| [make-gnome-shell-style](https://samwhelp.github.io/make-gnome-shell-style/) | [GitHub](https://github.com/samwhelp/make-gnome-shell-style) |




## Subject

* [Usage](#usage)
* [Option](#option)
* [Link](#link)




## Usage


### Quick Start

> How to download [make-gnome-shell-style.sh](https://github.com/samwhelp/make-gnome-shell-style/blob/main/make-gnome-shell-style.sh) and run [it](https://raw.githubusercontent.com/samwhelp/make-gnome-shell-style/refs/heads/main/make-gnome-shell-style.sh).


* run

``` sh
bash <(curl -L https://raw.githubusercontent.com/samwhelp/make-gnome-shell-style/refs/heads/main/make-gnome-shell-style.sh)
```


* or run

``` sh
bash <(wget -q https://raw.githubusercontent.com/samwhelp/make-gnome-shell-style/refs/heads/main/make-gnome-shell-style.sh -O - )
```


* or run

``` sh
bash -c "$(curl -fsSL https://raw.githubusercontent.com/samwhelp/make-gnome-shell-style/refs/heads/main/make-gnome-shell-style.sh || wget -q https://raw.githubusercontent.com/samwhelp/make-gnome-shell-style/refs/heads/main/make-gnome-shell-style.sh -O - )"
```


* or run

``` sh
bash -c "$(wget -q https://raw.githubusercontent.com/samwhelp/make-gnome-shell-style/refs/heads/main/make-gnome-shell-style.sh -O - || curl -fsSL https://raw.githubusercontent.com/samwhelp/make-gnome-shell-style/refs/heads/main/make-gnome-shell-style.sh)"
```


### Basic

> default

``` sh
./make-gnome-shell-style.sh
```


> Option: [REF_MASTER_DISTRO](#option--ref_master_distro)

* execute local script

``` sh
REF_MASTER_DISTRO=archlinux ./make-gnome-shell-style.sh
```

* execute remote script

``` sh
REF_MASTER_DISTRO=archlinux bash <(curl -L https://raw.githubusercontent.com/samwhelp/make-gnome-shell-style/refs/heads/main/make-gnome-shell-style.sh)
```


> Option: [REF_MASTER_STYLE](#option--ref_master_style)

* execute local script

``` sh
REF_MASTER_STYLE=vimix ./make-gnome-shell-style.sh
```

* execute remote script

``` sh
REF_MASTER_STYLE=vimix bash <(curl -L https://raw.githubusercontent.com/samwhelp/make-gnome-shell-style/refs/heads/main/make-gnome-shell-style.sh)
```




## Option


### Option / REF_MASTER_DISTRO

| REF_MASTER_DISTRO   |
| ------------------- |
| `debian` (default)  |
| `ubuntu`            |
| `fedora`            |
| `archlinux`         |
| `voidlinux`         |

> We can use `REF_MASTER_DISTRO=any` to skip the step of installing required packages.


### Option / REF_MASTER_STYLE

| REF_MASTER_STYLE    |
| ------------------- |
| `jasper` (default)  |
| `graphite`          |
| `fluent`            |
| `colloid`           |
| `vimix`             |
| `orchis`            |
| `layan`             |
| `lavanda`           |
| `qogir`             |




## Link

| Link | GitHub |
| ---- | ------ |
| [Gnome Shell Adjustment](https://samwhelp.github.io/gnome-shell-adjustment/) | [GitHub](https://github.com/samwhelp/gnome-shell-adjustment) |
| [gnome-shell-enhance](https://samwhelp.github.io/gnome-shell-enhance/) | [GitHub](https://github.com/samwhelp/gnome-shell-enhance) |




## Related Projects

| Link | GitHub |
| ---- | ------ |
| [make-xfce-style](https://samwhelp.github.io/make-xfce-style/) | [GitHub](https://github.com/samwhelp/make-xfce-style) |


| Link |
| ---- |
| [demo-style-select](https://github.com/samwhelp/note-about-menu-applet/tree/gh-pages/_demo/prototype/menu-applet/demo-application/demo-style-select) |
| make-gnome-shell-layout-wincity / [make-gnome-shell-style](https://github.com/samwhelp/make-gnome-shell-layout-wincity/tree/main/part/make-gnome-shell-style) |
| make-gnome-shell-layout-maccity / [make-gnome-shell-style](https://github.com/samwhelp/make-gnome-shell-layout-maccity/tree/main/part/make-gnome-shell-style) |


| Link | GitHub |
| ---- | ------ |
| [deb-recipe](https://samwhelp.github.io/deb-recipe/) | [GitHub](https://github.com/samwhelp/deb-recipe) |
| [deb-coffee](https://samwhelp.github.io/deb-coffee/) | [GitHub](https://github.com/samwhelp/deb-coffee) |




## Samwhelp

* [GitHub](https://github.com/samwhelp)
