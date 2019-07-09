# gulp-pug-boilerplate

## 開発環境

### Install

```
$ git clone https://github.com/gurunavi-creators/gulp-pug-boilerplate.git
$ cd gulp-pug-boilerplate
$ yarn
```

### Node Version

```
v10.15.1
```

### Package

- [package.json](https://github.com/gurunavi-creators/gulp-pug-boilerplate/package.json)

### Development

```
$ yarn dev
```
（Clean & Build & watch）

### Build

```
$ yarn build
```
（html & js & css & img）

### Clean

```
$ yarn clean
```

## eslint-config-gnavi

[![License](http://img.shields.io/npm/l/eslint-config-gnavi.svg?style=flat-square)](https://github.com/gurunavi-creators/eslint-config-gnavi)

> [ESLint](http://eslint.org/) shareable config for Gnavi UI

## Develop Directory Structure

```
src/
  └ html/
    └ pug/
      └ data/
      └ include/
        └ common/
        └ core/
      └ layout/
      └ pages/
    └ scss/
      └ module/
      └ lib/
    └ script/
      └ common/
      └ lib/

↓ After Compilation

public/
  └ pages/
  └ css/
    └ lib/
  └ js/
    └ lib/
```
