![](http://geo.azmag.gov/maps/readonaz/app/resources/img/maglogo_black.png)

# mag-prettier-config

![GitHub release (latest SemVer)](https://img.shields.io/github/v/release/AZMAG/mag-prettier-config?&logo=github&style=flat-square)
![GitHub Release Date](https://img.shields.io/github/release-date/AZMAG/mag-prettier-config?&logo=github&style=flat-square)
![GitHub last commit](https://img.shields.io/github/last-commit/AZMAG/mag-prettier-config?&logo=github&style=flat-square)
![GitHub issues](https://img.shields.io/github/issues-raw/AZMAG/mag-prettier-config?&logo=github&style=flat-square)
![Libraries.io dependency status for GitHub repo](https://img.shields.io/librariesio/github/AZMAG/mag-prettier-config?style=flat-square)
![npm](https://img.shields.io/npm/v/mag-prettier-config?color=crimson&logo=npm&style=flat-square)
![semver](https://img.shields.io/badge/semver-2.0.0-blue?style=flat-square)
[![GitHub license](https://img.shields.io/github/license/AZMAG/mag-prettier-config?style=flat-square)](https://github.com/AZMAG/mag-prettier-config/blob/main/LICENSE)

This is Maricopa Association of Governments (MAG) shareable [Prettier](https://prettier.io) config for use in project files. This module defines standard [Prettier](https://prettier.io) rules for code formatting to help format the code in all of our projects.

## :key: Keywords

`config` `prettier` `prettier-config` `prettierrc` `prettierconfig` `code-style` `style-guide` `mag`

## :gear: Installation

Install this Prettier config together with its peer dependencies:

#### Install with npm

```bash
$ npm i mag-prettier-config --save-dev
```

<details><summary>Install with <code>yarn</code></summary><p>

```bash
$ yarn add mag-prettier-config --dev
```

</p></details>

### Peer Dependencies

Peer dependencies need to be installed in order to make it work properly.

- Prettier is an opinionated code formatter.

  #### Install with npm

  ```bash
  $ npm i prettier --save-dev
  ```

  <details><summary>Install with <code>yarn</code></summary><p>

  ```bash
  $ yarn add prettier --dev
  ```

  </p></details>

- eslint-config-prettier turns off all rules that are unnecessary or might conflict with [Prettier](https://prettier.io)

  #### Install with npm

  ```bash
  $ npm i eslint-config-prettier --save-dev
  ```

  <details><summary>Install with <code>yarn</code></summary><p>

  ```bash
  $ yarn add eslint-config-prettier --dev
  ```

  </p></details>

## Usage

Once you have installed the module and its peer dependencies you will need to add this reference to your `package.json`

```
{
  "prettier": "mag-prettier-config",
  "eslintConfig": {
      "extends": ["prettier"]
    },
}
```

Previously, rules had been defined directly in a `.prettierrc `or `package.json`

Any previous `.prettierrc` should be removed in favor of the shared config.

## Options

Prettier ships with a handful of format options.

[Prettier Options](https://prettier.io/docs/en/options.html)

## Current Options

`{ "$schema": "http://json.schemastore.org/prettierrc", "printWidth": 100, "tabWidth": 2, "useTabs": false, "singleQuote": false, "trailingComma": "all", "endOfLine": "lf", "semi": false, "bracketSameLine": true, "bracketSpacing": true, "htmlWhitespaceSensitivity": "css", "arrowParens": "always" }`

<details><summary>**Prettier rules**</summary><p>

This project defines the following settings in the file.

| Rule                                                                                                | Value\*    |
| --------------------------------------------------------------------------------------------------- | ---------- |
| [`printWidth`](https://prettier.io/docs/en/options.html#print-width)                                | **`100`**  |
| [`tabWidth`](https://prettier.io/docs/en/options.html#tab-width)                                    | `2`        |
| [`useTabs`](https://prettier.io/docs/en/options.html#tabs)                                          | `false`    |
| [`singleQuote`](https://prettier.io/docs/en/options.html#quotes)                                    | `false`    |
| [`trailingComma`](https://prettier.io/docs/en/options.html#trailing-commas)                         | **`all`**  |
| [`endOfLine`](https://prettier.io/docs/en/options.html#end-of-line)                                 | `lf`       |
| [`semi`](https://prettier.io/docs/en/options.html#semicolons)                                       | `false`    |
| [`bracketSameLine`](https://prettier.io/docs/en/options.html#jsx-brackets)                          | **`true`** |
| [`bracketSpacing`](https://prettier.io/docs/en/options.html#bracket-spacing)                        | `true`     |
| [`htmlWhitespaceSensitivity`](https://prettier.io/docs/en/options.html#html-whitespace-sensitivity) | `css`      |
| [`arrowParens`](https://prettier.io/docs/en/options.html#arrow-parens)                              | `always`   |

\* Values in **bold** differ from the Prettier defaults.

</p></details>

If you change any options, it’s recommended to do it via the [configuration file](https://github.com/AZMAG/mag-prettier-config/blob/main/index.json).

## Version

### version | 1.1.0

- #### Updated | 2021-11-30
- #### Created | 2021-11-08

Releases will be numbered with the following format:

**`<major>.<minor>.<patch>`**

And constructed with the following guidelines:

1. **MAJOR** version when you make incompatible API changes **bumps the major** resets minor and patch
2. **MINOR** version when you add functionality in a backwards-compatible manner **bumps the minor** resets patch
3. **PATCH** version when you make backwards-compatible bug fixes and misc changes **bumps only the patch**

## Technologies

A list of technologies used within the project:

<a href="https://prettier.io/" title="Prettier"><img src="https://github.com/get-icon/geticon/raw/master/icons/prettier.svg" alt="Prettier" width="31px" height="31px"></a>
<a href="https://eslint.org/" title="ESLint"><img src="https://github.com/get-icon/geticon/raw/master/icons/eslint.svg" alt="ESLint" width="31px" height="31px"></a>
<a href="https://www.npmjs.com/" title="npm"><img src="https://github.com/get-icon/geticon/raw/master/icons/npm.svg" alt="npm" width="31px" height="31px"></a>
<a href="https://code.visualstudio.com/" title="vscode"><img src="https://github.com/get-icon/geticon/raw/master/icons/visual-studio-code.svg" alt="vscode" width="31px" height="31px"></a>

## :star: Credits

`Maricopa Association of Governments (MAG) and the MAG member agencies`

## :zap: Disclaimer

- [DISCLAIMER](DISCLAIMER.md)

## :warning: Licensing

Copyright 2021 Maricopa Association of Governments (MAG)

This project is licensed under the MIT license.

[![GitHub license](https://img.shields.io/github/license/AZMAG/mag-prettier-config?style=flat-square)](https://github.com/AZMAG/mag-prettier-config/blob/main/LICENSE)

[(Back to top)](#mag-prettier-config)
