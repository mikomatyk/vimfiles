# Vimfiles

Optional configuration files for Vim, ready to download as a ZIP file.

This repository complements my primary [vimrc][00] repository, which dynamically
generates optional components using Bash scripts. Here, you will find
pre-packaged those optional Vim configuration files and plugins, designed for
environments with network restrictions that prevent the use of `git clone` or
`curl` commands, rendering the installation scripts from the primary repository
unusable. Instead of relying on dynamic script-based installation, this
repository provides all necessary files in a ready-to-use format.

Additionally, the _retrobox_ color scheme is included, tailored for older
versions of Vim that don't support it natively.

## Setup

Whenever possible, start by cloning [vimrc][00] and running its Bash scripts
directly. If network restrictions prevent this, follow these steps:

1. Download both [vimrc][00] and this repository as ZIP files through your web
   browser.
2. Extract the ZIP files into the Vim configuration directory:
   - On Windows: `~/vimfiles`
   - On Linux: `~/.vim`

## Author

Unless explicitly stated otherwise, I am not the author of the files presented
here and do not claim any copyright over them. Any other content in this
repository that may be a subject to licensing was prepared and unlicensed by
[Mikołaj Bartnicki][98]; please read [UNLICENSE][99] file for details.

[00]:https://github.com/mikomatyk/vimrc
[98]:mailto:mikolaj@bartnicki.org
[99]:UNLICENSE
