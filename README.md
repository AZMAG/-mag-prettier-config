![](http://geo.azmag.gov/maps/readonaz/app/resources/img/maglogo_black.png)

# mag-prettier-config

![GitHub release (latest SemVer)](https://img.shields.io/github/v/release/AZMAG/mag-prettier-config)
![GitHub tag (latest SemVer)](https://img.shields.io/github/v/tag/AZMAG/mag-prettier-config)
[![npm version](https://badge.fury.io/js/mag-prettier-config.svg)](https://badge.fury.io/js/mag-prettier-config)
[![GitHub issues](https://img.shields.io/github/issues/AZMAG/mag-prettier-config)](https://github.com/AZMAG/mag-prettier-config/issues)
[![GitHub license](https://img.shields.io/github/license/AZMAG/mag-prettier-config)](https://github.com/AZMAG/mag-prettier-config/blob/main/LICENSE)

This repo is a Maricopa Association of Governments (MAG) [Prettier](https://prettier.io) config for use in project files.

## Usage

**Install**:

```bash
$ npm i mag-prettier-config --save-dev
```

or

```bash
$ yarn add mag-prettier-config --dev
```

**Edit**:

Once you have installed the module you will need to add this reference to your `package.json`

```jsonc
{
  // ...
  "prettier": "mag-prettier-config"
}
```

## Options

Prettier ships with a handful of format options.

[Prettier Options](https://prettier.io/docs/en/options.html)

If you change any options, it’s recommended to do it via the [configuration file](https://github.com/AZMAG/mag-prettier-config/blob/main/index.json).

## Version

### version | 1.0.3

- #### Updated | 2021-11-08
- #### Created | 2021-11-08

Releases will be numbered with the following format:

**`<major>.<minor>.<patch>`**

And constructed with the following guidelines:

1. **MAJOR** version when you make incompatible API changes **bumps the major** resets minor and patch
2. **MINOR** version when you add functionality in a backwards-compatible manner **bumps the minor** resets patch
3. **PATCH** version when you make backwards-compatible bug fixes and misc changes **bumps only the patch**

## Credits

`Maricopa Association of Governments (MAG) and the MAG member agencies`

## Licensing

Copyright 2021 Maricopa Association of Governments (MAG)

Code released under the MIT license.

- [LICENSE](LICENSE)

[(Back to top)](#azmagprettier-config)
