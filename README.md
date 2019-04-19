# commitlint-config

[shareable config](https://conventional-changelog.github.io/commitlint/#/concepts-shareable-config)
for [commitlint](https://conventional-changelog.github.io/commitlint/)

<!-- status badges -->
[![Build Status][ci-badge]][ci-link]

## Usage

<!-- consumer badges -->
[![npm][npm-badge]][npm-link]
[![MIT license][license-badge]][license-link]

This config extends [commitlint-config-travi](https://github.com/travi/commitlint-config-travi)

### Installation

```sh
$ npm install @form8ion/commitlint-config --save-dev
```

### Define the config for your project

```sh
$ echo "module.exports = {extends: ['@form8ion']};" > .commitlintrc.js
```

### Define the npm script for [husky](https://github.com/typicode/husky)

```json
{
  "scripts": {
    "commitmsg": "commitlint -e"
  }
}
```

## Contributing

<!-- contribution badges -->
[![Conventional Commits][commit-convention-badge]][commit-convention-link]
[![Commitizen friendly][commitizen-badge]][commitizen-link]
[![semantic-release][semantic-release-badge]][semantic-release-link]
[![PRs Welcome][PRs-badge]][PRs-link]

### Dependencies

```sh
$ nvm install
$ npm install
```

### Verification

```sh
$ npm test
```

[npm-link]: https://www.npmjs.com/package/@form8ion/commitlint-config
[npm-badge]: https://img.shields.io/npm/v/@form8ion/commitlint-config.svg
[license-link]: LICENSE
[license-badge]: https://img.shields.io/github/license/form8ion/commitlint-config.svg
[ci-link]: https://travis-ci.com/form8ion/commitlint-config
[ci-badge]: https://img.shields.io/travis/com/form8ion/commitlint-config/master.svg
[commit-convention-link]: https://conventionalcommits.org
[commit-convention-badge]: https://img.shields.io/badge/Conventional%20Commits-1.0.0-yellow.svg
[commitizen-link]: http://commitizen.github.io/cz-cli/
[commitizen-badge]: https://img.shields.io/badge/commitizen-friendly-brightgreen.svg
[semantic-release-link]: https://github.com/semantic-release/semantic-release
[semantic-release-badge]: https://img.shields.io/badge/%20%20%F0%9F%93%A6%F0%9F%9A%80-semantic--release-e10079.svg
[PRs-link]: http://makeapullrequest.com
[PRs-badge]: https://img.shields.io/badge/PRs-welcome-brightgreen.svg
