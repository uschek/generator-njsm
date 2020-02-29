# generator-njsm [![Build Status](https://travis-ci.org/uschek/generator-njsm.svg?branch=master)](https://travis-ci.org/uschek/generator-njsm)

> Scaffold out a node module

Optionally with a [CLI](http://en.wikipedia.org/wiki/Command-line_interface).


## Install

```
$ npm install --global yo generator-njsm
```


## Usage

With [yo](https://github.com/yeoman/yo):

```
$ yo njsm
```

There are multiple command-line options available:

```
$ yo njsm --help

  Usage:
    yo njsm [options]

  Options:
    --help          # Print the generator's options and usage
    --skip-cache    # Do not remember prompt answers                      Default: false
    --skip-install  # Do not automatically install dependencies           Default: false
    --org           # Publish to a GitHub organization account
    --cli           # Add a CLI
    --coverage      # Add code coverage with nyc
    --codecov       # Upload coverage to codecov.io (implies --coverage)
```

The `--org` option takes a string value (i.e. `--org=avajs`). All others are boolean flags and can be negated with the `no` prefix (i.e. `--no-codecov`). You will be prompted for any options not passed on the command-line.


## Tip

Use [chalk](https://github.com/sindresorhus/chalk) if you want colors in your CLI.


## Credits

This module is identical to [generator-nm](https://github.com/sindresorhus/generator-nm) by [Sindre Sorhus](http://sindresorhus.com), but with spaces instead of tabs. Thank you for building these [awesome modules](https://www.npmjs.com/~sindresorhus), Sindre!
