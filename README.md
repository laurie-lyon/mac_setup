# Setting up a new Mac Book
## Bare Bones Basic Necessity
First, we need to set up the MacOS package manager, `brew`.
Instructions for installing `brew` can be found [here](www.brew.sh).

```shell
% /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

This bit of code is necessary to tell the OS where `brew` lives.
```shell
(echo; echo 'eval "$(/opt/homebrew/bin/brew shellenv)"') >> /Users/laurielyon/.zprofile
eval "$(/opt/homebrew/bin/brew shellenv)"
```

## Installing command line ammenities
We're going install a slew of handy shit:
```shell
% brew install htop \
  git \
  openssh \
  tmux \
  docker \
  visual-studio-code \
  tree
```

## Installing Rstudio via Docker/Rocker
  - in progress

## Commands to know
  - `cmd` + `,` to open settings
  - `htop` to look at ongoing processes
  - `ssh` allows you to control computers remotely
  - `git`
  - `which` identifies the path of a certain software/tool
  - `tree` displays a tree of folders/subfolders

## Software
Virtual Environments
  - conda
  - docker

IDE (Integrated Development Environment)
  - VSCode
  - RStudio

Version Control
  - git

Languages
  - R
    - Tidyverse
  - Python
  - bash

Brew Packages:
  - git
  - htop

# TO DO:
  - Complete documentation for docker B.S.
  - Complete documentation for vscode + micromamba setup.
