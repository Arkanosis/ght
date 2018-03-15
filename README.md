# ght [![Version](https://img.shields.io/badge/version-v0.2.0--dev-orange.svg)](https://semver.org/spec/v2.0.0.html) [![License](http://img.shields.io/badge/license-ISC-blue.svg)](/LICENSE)

**ght** is a command-line re-implementation of GitHub's timelines.

## Installation

Copy the `ght` script wherever you want.

## Configuration

You can create a `.ghtrc` configuration file in your `$HOME` directory.

Example configuration file:

```sh
COMMAND=others # by default, uses --help without command
SELF=Arkanosis # by default, uses $USER as GitHub handle
```

## Usage

```console
Usage: ght mine
       ght others
       ght -h | --help
       ght --version

Commands:
    mine        Show one's activity
    others      Show activity of others

Options:
    -h, --help  Show this screen.
    --version   Show version.
```

## Contributing and reporting bugs

Contributions are welcome through [GitHub pull requests](https://github.com/Arkanosis/ght/pulls).

Please report bugs and feature requests on [GitHub issues](https://github.com/Arkanosis/ght/issues).

## License

ght is copyright (C) 2018 Jérémie Roquet <jroquet@arkanosis.net> and licensed under the ISC license.
