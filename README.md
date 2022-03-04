# git-select

Displays a dialog from where you can select a branch to checkout or copy its name.

# Installation

Simply copy the ```git-select``` file in a directory included in your ```$PATH```. For example:

```sh
$ sudo - su
# cp git-select /usr/local/bin
```

# Usage

To use the command execute the following command in the working directory in which you wish to switch branches:

```sh
$ git select
```

Initially the current branch is pre-selected. Navigate to the desired branch using arrow keys and choose "Check out" to check it out. If you need to copy the branch name into the clipboard instead, then choose "Copy name". To close the dialog without any action hit Escape or choose "Cancel".

# Dependencies

This shell script depends on the following programs (besides git itself):

* dialog (https://invisible-island.net/dialog/)
* sed, awk, pbcopy

