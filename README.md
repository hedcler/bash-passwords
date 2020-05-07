# bash-passwords
Prevent to show your passwords notes when your screen is shared with others.

!! It's only for MacOS at this moment.

## Installation

Download this [repository as zip](https://github.com/hedcler/bash-passwords/archive/master.zip) and extract it. Save the file `.getpwd` and directory `dotfiles` in your home path.

After that you need to add this import script in your `~/.bashrc` or `~/.bash-profile`:

```
if [ -f "${HOME}/.getpwd" ]; then
    . $HOME/.getpwd
fi
```

## Usage

`~ $ getpwd` will list all keys configured on your `~/dotfiles/.passwords`
`~ $ getpwd <key>` will copy the key value to clipboard. using `pbcopy`

## Support for Linux

You can contribute for this project and add linux suport. :D
