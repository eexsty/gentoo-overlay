# Gentoo Overlay

A simple overlay I made just for managing packages easily for things I use daily.

## Installation

**Replace `doas` with `sudo` if you're using sudo.**
```bash
doas emerge -av app-eselect/eselect-repository
doas eselect repository add eexsty git https://github.com/eexsty/gentoo-overlay
doas emerge --sync eexsty
```

## Included packages

* [`x11-misc/picom-animations`](https://github.com/dccsillag/picom)
* [`sys-auth/polkit-dumb-agent`](https://github.com/sandsmark/polkit-dumb-agent)

