<h1>
   <p align="center">
     <a href="https://ghostty.org/"><img src="https://ghostty-debian.github.io/blob/main/ghostty-logo.png" alt="Ghostty Logo" width="128" style="margin-right: 20px"></a>
     <a href="https://www.debian.org/"><img src="https://ghostty-debian.github.io/blob/main/debian-logo.png" alt="Debian Logo" width="104" style="margin-left: 20px"></a>
     <br>Ghostty for Debian 
   </p>
</h1>

<p align="center">
   Unofficial repository for ghostty Debian packages
</p>
<p align="center">
 👻 Ghostty is a fast, feature-rich, and cross-platform terminal emulator that uses platform-native UI and GPU acceleration.
</p>

# Ghostty for Debian

This repository contains _unofficial_ Debian packages (.deb) for [Ghostty](https://ghostty.org) hosted at [apt](https://ghostty-debian.github.io/apt)

Packages are build in the [build-pipeline](https://github.com/ghostty-debian/build-pipeline)

Currently supported debian distros are:
- Bookworm
- Trixie
- Sid

This is an unofficial community project to provide a package that's easy to
install on Debian. If you're looking for the Ghostty source code, see
[ghostty-org/ghostty](https://github.com/ghostty-org/ghostty).

## Install/Update

```sh
curl -sS https://ghostty-debian.github.io/3B9335DF576D3D58059C6AA50B56A1A69762E9FF.asc | sudo gpg --dearmor --yes -o /etc/apt/trusted.gpg.d/ghostty-debian.gpg
echo "deb https://ghostty-debian.github.io/apt $(lsb_release -sc 2>/dev/null) main" | sudo tee /etc/apt/sources.list.d/ghostty-debian.list
```

## Disclaimer

- This repo is not open for issues related to ghostty. This repo is only for _unofficial_ Debian packaging.
