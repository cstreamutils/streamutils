Stream Utils
============

## Tools
* [rep](#rep) - search and replace
* [del](#del) - search and delete
* [red](#red) - stream reader
* [upr](#upr) - stream to upper case
* [lwr](#lwr) - stream to lower case
* [prepend](#prepend) - prepend to stream 
* [append](#append) - append to stream 

## Universal flags
* `-n` - line number:`12` or line number range:`7,19`
* `-v` - verbose
* `-i` - inplace file edit
* `-c` - color output

### rep
> search and replace  

* `-z` - invert search regex
* `-w` - wrap matching `"before:after"`
 * `::` to escape `:`
* `-p` - prepend matching string
* `-a` - append matching string

### del
> search and delete  

* `-z` - invert search regex
* `-e` - empty lines

### red
> stream reader  

* `-l` - print line numbers
* `-e` - dont print empty lines
* `-c` - use vim color syntax-highlight

### upr
> stream to upper case  

* `-l` - apply to line (use with -n)

### lwr
> stream to lower case  

* `-l` - apply to line (use with -n)

### prepend
> prepend to stream  

* `-l` - prepend to line (use with -n)

### append
> append to stream  

* `-l` - append to line (use with -n)
