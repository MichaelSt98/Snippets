# Bash/Shell

**sh** or *Shell Command languag* is a programming language described by the 
[POSIX standard](https://pubs.opengroup.org/onlinepubs/009695399/utilities/xcu_chap02.html).
Therefore **sh** is a specification and not a implementation!

Many implementations are available:
* bash
* ksh88
* dash
* ...

## Shebang line

The implementation is chosen using the *shebang* line, thus the very first line of the script:

```
#!/bin/sh
```
uses **sh** (and whatever points to that)

```
#!bin/bash
```
uses **bin/bash** if available (and fail with error message if not)

```
`#!bin/dash
```
uses **bin/dasg** and so forth...

# Content

## Scripts

* *make_doc* generate a documentation using doxygen

