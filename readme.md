
# Utility shell scripts

**Note :** Scripts are developed under the amazing `[Cygwin](http://www.cygwin.com/)` for Windows but are compatible for all shell interpreters.

The `Cygwin` or `Unix` flags mean that the script is compatible under those plateform.

## util/colors.sh

__Compatibility :__ `Cygwin` `Unix`

A set of color variables to use in your scripts.

```shell
# Text color
black="\033[30m"
red="\033[31m"
green="\033[32m"
yellow="\033[33m"
blue="\033[34m"
magenta="\033[35m"
cyan="\033[36m"
white="\033[37m"

# Background color
_black="\033[40m"
_red="\033[41m"
_green="\033[42m"
_yellow="\033[43m"
_blue="\033[44m"
_magenta="\033[45m"
_cyan="\033[46m"
_white="\033[47m"

# Reset all
_def_="\033[00m"
```
