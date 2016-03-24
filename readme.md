# npm-name-cli [![Build Status](https://travis-ci.org/sindresorhus/npm-name-cli.svg?branch=master)](https://travis-ci.org/sindresorhus/npm-name-cli)

> Check whether a package name is available on npm

![](screenshot.png)


## Install

```
$ npm install --global npm-name-cli
```


## Usage

```
$ npm-name --help

  Usage
    $ npm-name <name>

  Examples
    $ npm-name chalk
    ✖ chalk is unavailable
    $ npm-name unicorn-cake
    ✔ unicorn-cake is available

  Exits with code 0 when the name is available or 2 when taken
```


## Related

- [npm-name](https://github.com/sindresorhus/npm-name) - API for this module


## License

MIT © [Sindre Sorhus](https://sindresorhus.com)