# trash

## Introduction

Delete and recover files, print the size and contents of the trash can, and
more.

## Usage

### Delete files

```
trash -d file1 file2 ...
```

### Recover a file

```
trash -r file
```

### Print size

```
trash -s
```

### List contents

```
trash -l
```

### Print location of trash can

```
trash -L
```

### Empty trash can

```
trash --empty
```

## Install

To install the trash can, run the following command:
```
trash --install
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

To uninstall the trash can, run the following command:
```
trash --uninstall
```

This will remove the trash can directory and all of its contents.
