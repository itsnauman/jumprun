`$ jumprun_`
=============

A unix command-line tool for running scripts from any directory in terminal, It allows you to do it from any directory buy making shortcuts. At the current moment `Perl 5`, `Ruby` and `Python` interpreters are supported.

### Platform:

This tool is strictly for UNIX based OS.

### Installation:

It can be installed using PyPi, `$ pip install jumprun`.

### Dependencies:
This tool makes use of `docopt` and `termcolor`

### Usage:
* Add a python shortcut with, `$ jr add NAME file.py`
* Run the script from any dir in terminal using, `$ jr NAME`
* Refresh the entire db with, `$ jr rm --all`
* Delete a specfic shortcut with, `$ jr rm NAME`
* Rename a shortcut with, `$ jr rename OLDNAME NEWNAME`
* List all shortcuts with `$ jr show`
* `$ jr --help` for more details

### Tests:
For running the unittests, `$ python test_jumprun.py` 

### TODO:
* Add support for shell scripts 

### License:
`Jumprun` is distributed under MIT license, see `LICENSE` for more details.
