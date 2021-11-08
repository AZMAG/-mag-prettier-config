![](http://geo.azmag.gov/maps/readonaz/app/resources/img/maglogo_black.png)

# mag-prettier-config

![npm](https://img.shields.io/npm/v/prettier-config)
[![Semver](http://img.shields.io/SemVer/2.0.0.png)](https://shields.io/)
[![MIT licensed](https://img.shields.io/badge/license-MIT-blue.svg)](https://opensource.org/licenses/MIT)

This repo is a Maricopa Association of Governments (MAG) [Prettier](https://prettier.io) config for use in project files.

## Usage

**Install**:

```bash
$ npm install --save-dev mag-prettier-config
```

or

```bash
$ yarn add --save-dev mag-prettier-config
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

### version | 1.0.2

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
