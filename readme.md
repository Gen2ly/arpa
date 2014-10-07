### Description

`arpa` is a wrapper script encompassing many common package-manager related tasks - the purpose intended is to help the user remember how to implement those tasks.

### Usage

```bash
arpa [option] [*package] - a generic package tasks wrapper script
  -e, --explicit - install a package as explicit
  -g, --get      - get/download package upgrade(s)    : -G get pkg upgrades all
  -i, --install  - install a package                  : -I install as dependency
  -l, --list     - list package files                 : -L list pkgs installed
  -o, --owns     - owning package of a file
  -q, --query    - query for an installed package     : -Q query w/ description
  -r, --remove   - remove a pkg and its deps          : -R force, no argue orphs
  -s, --search   - search for a package               : -S search w/ description
  -u, --upgrade  - upgrade system                     : -U upgrade AUR
  -y, --sync     - sync package db
```

### ToDo

* Possibly to add gepopt(s) to allow defining multiple tasks.
