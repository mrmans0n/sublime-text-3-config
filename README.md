sublime-text-3-config
=====================

Taking inspiration of some devs that did this in the past, I'm doing it too. Because adapting settings between four different computers is a mess.

## Install

Quit Sublime Text 3.

    $ rm -rf ~/Library/Application \Support/Sublime\ Text\ 3
    $ git clone https://github.com/mrmans0n/sublime-text-3-config.git ~/Library/Application\ Support/Sublime\ Text\ 3

Open Sublime Text 3.

You may need to [manually install Package Control](https://sublime.wbond.net/installation).

## Keeping it up to date

You should add then this line to your .bash_profile, .zshrc or any other similar script. 

`cd "Library/Application Support/Sublime Text 3/";git pull;cd`
