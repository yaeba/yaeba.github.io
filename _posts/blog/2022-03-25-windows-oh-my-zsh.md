---
title: "Install Oh My Zsh on Windows Git BASH"
excerpt: "Download, install, configure Z shell (Zsh) and Oh My Zsh on Windows Git BASH"
classes: wide
tags:
  - terminal
---

## Useful links

- [Git for Windows + Git BASH](https://gitforwindows.org/){:target="\_blank"}
- [Chocolatey](https://chocolatey.org/install#individual){:target="\_blank"}
- [GNU Make (Chocolatey)](https://community.chocolatey.org/packages/make){:target="\_blank"}
- [Oh My Zsh](https://github.com/ohmyzsh/ohmyzsh){:target="\_blank"}
- [MSYS2 Zsh](https://packages.msys2.org/package/zsh){:target="\_blank"}
- [Zstandard](https://packages.msys2.org/package/zsh){:target="\_blank"}

## Before you start

1. Download and install [Git for Windows + Git BASH](https://gitforwindows.org/)
2. Install [Chocolatey](https://chocolatey.org/install#individual)
3. Install [GNU Make (Chocolatey)](https://community.chocolatey.org/packages/make), eg `choco install make`

## Install Zsh

Run `Git BASH` as administrator and execute the following

1. Download the `zsh` package
  ```bash
  curl -sL https://mirror.msys2.org/msys/x86_64/zsh-5.8-5-x86_64.pkg.tar.zst -o zsh.tar.zst
  ```

2. Clone the `zstd` repo to use it for decompression
  ```bash
  git clone https://github.com/facebook/zstd.git
  ```

3. Build `zstd` and untar + decompress the `zsh` package
  ```bash
  CC=gcc make -C zstd
  mkdir zsh && tar --use-compress-program=zstd/zstd.exe -xvf zsh.tar.zst -C zsh
  ```

4. Merge the `zsh` content to Git BASH directory
  ```bash
  cp -R zsh/etc /
  cp -R zsh/usr /
  ```

5. Set up `zsh`
  ```bash
  touch ~/.zshrc
  echo "test -t && exec zsh" >> ~/.bashrc
  ```

6. Clean up and test zsh
  ```bash
  rm -rf zsh zsh.tar.zst zstd
  zsh --version
  ```

## Set up Oh My Zsh

At this point you have `zsh` installed, next just set up Oh My Zsh the way you like.

```bash
## install oh my zsh
sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"

## install plugins etc
```
