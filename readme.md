
# semistandard-format
  This is a fork of [standard-format](https://github.com/maxogden/standard-format) same concept but with semicolons.

## Installation

  Install with npm

    $ npm install -g semistandard-format

## Example Usage

  Output all formatted javascript in a directory and subdirectories to stdout

    $ semistandard-format

  Format all javascript files, overwriting them into standard format

    $ semistandard-format -w

  Format javascript over stdin

    $ semistandard-format < file.js > formatted-file.js

  Format and overwrite specific files

    $ semistandard-format -w file1.js file2.js

### Editor plugins

  - Atom: [linter-js-standard](https://github.com/ricardofbarros/linter-js-standard)
