# Colours

> A (fetch?) tool to display the colours of your terminal emulator written in bash

# Requirements

- Bash -- https://www.gnu.org/software/bash/

# Installation

## Manual

```bash
sudo install -Dm755 colours /usr/local/bin
```

## Packages

- Linux
  - Gentoo linux: [app-misc/colours::dinolay](https://ari-web.xyz/gentooatom/app-misc/colours)

# Customisation

Set the `T` environment variable to customise the sample text, it's `gYw` by default,
for example:

```bash
T=':)' colours
```
