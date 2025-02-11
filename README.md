# Litarvan's LightDM WebKit2 theme

## The Difference between [Litarvan repo](https://github.com/Litarvan/lightdm-webkit-theme-litarvan) is the following:
- When 6 characters have been introduced as the password, lightdm will try to use it automatically to log in, aka, no need to press the enter key on your keyboard.

[![Arch Release](https://img.shields.io/badge/arch-3.2.0-blue.svg?style=flat-square)](https://www.archlinux.org/packages/community/any/lightdm-webkit-theme-litarvan/) &nbsp;[![Latest Release](https://img.shields.io/github/release/Litarvan/lightdm-webkit-theme-litarvan.svg?style=flat-square&label=github)](https://github.com/Litarvan/lightdm-webkit-theme-litarvan/releases) &nbsp;![Github downloads](https://img.shields.io/github/downloads/Litarvan/lightdm-webkit-theme-litarvan/total.svg?style=flat-square)

**=> Screenshots below**

# [Live testing (3.2.0)](https://litarvan.github.io/lightdm-webkit-theme-litarvan/)

# Customize release
Backgrounds can be added in `/usr/share/backgrounds` and chosen in the Theming view (bottom right corner of the Setup view).

Customize the OS logo within `/usr/share/lightdm-webkit/themes/litarvan/img/os.xxxxxxxx.png`

# Installation

## Arch Linux (3.2.0)

```
pacman -S --needed lightdm-webkit2-greeter lightdm-webkit-theme-litarvan
```

* If not already done, edit `/etc/lightdm/lightdm.conf` and set `greeter-session=lightdm-webkit2-greeter` .
* Then edit `/etc/lightdm/lightdm-webkit2-greeter.conf` and set `theme` or `webkit-theme` to `litarvan` .

## Manual (3.2.0)

* Install lightdm-webkit2-greeter using your dependency manager if not already done
* Download and unzip the [tar file](https://github.com/Litarvan/lightdm-webkit-theme-litarvan/releases) in `/usr/share/lightdm-webkit/themes/litarvan/`
* Edit `/etc/lightdm/lightdm-webkit2-greeter.conf` and set `theme` to `litarvan`.

# Building (latest features in development, future 3.3.0)

```
$ ./build.sh
```

Will generate a lightdm-webkit-theme-litarvan-3.2.0.tar.gz in the current folder.

# Screenshots

![Setup screenshot](https://litarvan.github.io/lightdm-webkit-theme-litarvan/setup_view.png)

![Splash screenshot](https://litarvan.github.io/lightdm-webkit-theme-litarvan/splash_view.png)

![Login screnshot](https://litarvan.github.io/lightdm-webkit-theme-litarvan/login_view.png)

![Desktops screenshot](https://litarvan.github.io/lightdm-webkit-theme-litarvan/desktops_view.png)

![Theming screenshot](https://litarvan.github.io/lightdm-webkit-theme-litarvan/theming_view.png)
