# sain

Git less, Small, Simple AUR helper. (Install only)

> Warning: Using AUR package is at your own risk.

## Require

- bash
- coreutil
- curl
- grep
- pacman

## Install

```shell
# zplug
zplug 'nxhlt/sain', as:command, use:sain

# curl
curl https://raw.githubusercontent.com/nxhlt/sain/main/sain > sain
chmod +x sain

```

## Usage

```
./sain [aur-packages...]
```

## Motivation

I heard we can download *Plaintext PKGBUILD* from AUR with curl.  
So I created for embedded/container environment.
