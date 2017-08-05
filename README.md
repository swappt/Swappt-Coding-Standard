# Swappt Coding Standard
Coding standards for Swappt

## Outline
* Any main function or function that is executed first should be placed at the bottom of the file.
* Code should be broken into files on a per-class basis.
* Code should always be indented appropriately, unless exceptions apply
* Nested `IF` statements should generally be avoided, paeticularly when the same could be achieved with an `AND`
* Fractions should be presented in their simplest forms or converted to decimals
* Tabs should never be used. Indent to 2 spaces (a 'soft-tab')
* Constants should be done in all UPPER CASE
* Classes should be Capitalized
* camelCase is preferred over underscore_seperators for variables of 2 or more words

## Python
* Imports should be written at the top of the files
* Imports no longer used should be removed
* Don't import things you don't need. use `IMPORT FROM` and the dot separator.
* Files should be lower case
* The file you execute should be named `main.py`
* Any utilities that don't get run but assist in production should be placed in a `utils` folder.
* File paths in the code must use a `/`
* Imports should be grouped by the module they are coming from
* Excepts should directly state the type of exception they are catching
* Anything that isn't a string should be coerced using `str()` and not the comma `,` syntax
