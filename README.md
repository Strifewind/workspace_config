
# dotfiles & templates

This repository contains reusable configuration templates and starter files that I commonly copy into new environments and projects.

Each type of configuration lives in its own directory to keep things organized and easy to reference.

## Contents
bash/
└── .bashrc
vim/
└── .vimrc
make/
└── Makefile
git/
└── .gitignore

### bash/
Sample `.bashrc` with aliases, environment settings, and shell quality-of-life improvements.

### vim/
A `.vimrc` focused on sane defaults and lightweight editing general development.

### make/
A generic `Makefile` template suitable for small school and personal projects, including:
- build rules
- test targets
- valgrind helpers
- tarball creation

### git/
Common `.gitignore` patterns for projects and editor artifacts.

## Usage

These files are intended to be **copied**, not symlinked.

Example:
```sh
cp make/Makefile my-project/
cp git/.gitignore my-project/

