# hl: syntax highlighting on the command line

The `hl` command is a very simple command that merely takes an
regular expression argument and highlights any lines that come from
stdin.  Similar to `grep --color`, but outputs every line and provides
fine control over color choices using the `-c` flag.

## Example Usage

* `hl Swap /proc/meminfo`
* `history | hl -c blue grep`

...

## Similar to grep

* `history | grep --color 'grep|$'` 

## Screen Shot

TBD

# Author

Wes Hardaker
