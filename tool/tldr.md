# tldr
- https://tldr.sh/

## Install
```bash
$ npm install -g tldr
$ tldr --update
```

## Usage
```bash
$ tldr
Usage: tldr command [options]

Simplified and community-driven man pages

Options:
  -v, --version            Display version
  -l, --list               List all commands for the chosen platform in the cache
  -a, --list-all           List all commands in the cache
  -1, --single-column      List single command per line (use with options -l or -a)
  -r, --random             Show a random command
  -e, --random-example     Show a random example
  -f, --render [file]      Render a specific markdown [file]
  -m, --markdown           Output in markdown format
  -p, --platform [type]    Override the current platform [android, darwin, freebsd, linux, macos, netbsd, openbsd,
                           osx, sunos, win32, windows]
  --android                Override the platform with android
  --darwin                 Override the platform with darwin
  --freebsd                Override the platform with freebsd
  --linux                  Override the platform with linux
  --macos                  Override the platform with macos
  --netbsd                 Override the platform with netbsd
  --openbsd                Override the platform with openbsd
  --osx                    Override the platform with osx
  --sunos                  Override the platform with sunos
  --win32                  Override the platform with win32
  --windows                Override the platform with windows
  -t, --theme [theme]      Color theme (simple, base16, ocean)
  -s, --search [keywords]  Search pages using keywords
  -u, --update             Update the local cache
  -c, --clear-cache        Clear the local cache
  -h, --help               Show this help message

  Examples:

    $ tldr tar
    $ tldr du --platform=linux
    $ tldr --search "create symbolic link to file"
    $ tldr --list
    $ tldr --list-all
    $ tldr --random
    $ tldr --random-example

  To control the cache:

    $ tldr --update
    $ tldr --clear-cache

  To render a local file (for testing):

    $ tldr --render /path/to/file.md
```

```bash
$ tldr --list-all
!, $, %, ,, ., 2to3, 7z, 7za, 7zr, LICENSE, [, [[, ], ]], ^, a2disconf, a2dismod, a2dissite, a2enconf, a2enmod, a2ensite, a2ping, a2query, aa, aa-audit, aa-cleanprof, aa-complain, aa-decode, aa-disable,
...
```

```bash
$ tldr whoami

  whoami

  Print the username associated with the current effective user ID.
  More information: https://www.gnu.org/software/coreutils/manual/html_node/whoami-invocation.html.

  - Display currently logged username:
    whoami

  - Display the username after a change in the user ID:
    sudo whoami
```
