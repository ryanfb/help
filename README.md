# help

A simple bash script for getting command help. It will loop through checking the following for available help with a command, exiting after the first available one:

* [`tldr`](https://github.com/tldr-pages/tldr)
* [`cheat`](https://github.com/cheat/cheat)
* [`eg`](https://github.com/srsudar/eg)
* [`bro`](http://bropages.org/)
* `man`
* `command --help`

Usage:

    help command

Install:

    curl -o /usr/local/bin/help https://raw.githubusercontent.com/ryanfb/help/master/help && chmod a+x /usr/local/bin/help

Or, y'know, whatever makes you comfortable.
