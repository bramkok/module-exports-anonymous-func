# module-exports-functions

> Test anonymous and named functions with `module.exports`

## Install

```
$ yarn global add module-exports-functions
```

## Usage

```
$ module-exports-functions --help

  Usage: index [options]

  Options:

    -V, --version    output the version number
    -n, --named      throw error inside a named function
    -a, --anonymous  throw error inside an anonymous function
    -h, --help       output usage information
```
## FAQ

### What's the value of this project?

This is a demo project to test behavior of anonymous and named functions
when exported with `module.exports`. Running the cli will offer the user
to choose either anonymous or named functions and an Error object will be
thrown.

### Ehhh, but why build a fully fledged project around it?

To test [eslint-config-bramkok](https://github.com/bramkok/eslint-config-bramkok)
and to create blueprint for JavaScript/Node projects. When finished it can be
made into a boilerplate and be used with [`boil`](https://github.com/bramkok/boil).

## License

MIT © [Bram Kok](https://bramkok.com)
