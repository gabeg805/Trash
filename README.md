# DEL

## What is it?

Delete files to, recover files from, and print size of the trash can.

## Installation

Installing the trash can simply involves creating the trash directory. To do so, run:
```
$ del --install
```

This will create the trash directory *${HOME}/.local/share/trash*. If this is
not where you want it installed, in the script, edit the line:
```
...
TRASHDIR="${HOME}/.local/share/trash"
...
```

Which appears in the first few lines of the script.

## Uninstall

To uninstall the trash can, run the command:
```
$ del --uninstall
```

This will remove the trash can directory and all of its contents.
