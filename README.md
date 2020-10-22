# git-select

Displays a menu where you can select a branch to checkout.

# Installation

Simply copy the ```git-select``` file in a directory included in your ```$PATH```. For example:

```sh
$ sudo - su
# cp git-select /usr/local/bin
```

# Usage

To use the command execute the following command in the working directory you want to clean up:

```sh
$ git select
```

Initially the current branch is pre-highlighted. Navigate to the desired branch using cursor keys and hit Enter to check out. To abort hit Escape or choose Cancel.

# Dependencies

This shell script depends on the following programs (besides git itself):

* dialog (https://invisible-island.net/dialog/)
* sed, awk

