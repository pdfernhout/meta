# dojo-meta

This repository contains information regarding Dojo 2 that crosses package boundries.

## Guidelines and Style Guide

There are several documents that are relevent for contributing to Dojo 2.

* [Contributing Guidelines](CONTRIBUTING.md) - Guidelines for contributing code (or documentation) to Dojo 2
* [Style Guide](STYLE.md) - The style guide for Dojo 2.
* [tslint.json](tslint.json) - The configuration file [tslint](http://palantir.github.io/tslint/) that is used to validate Dojo 2 code against

## Packages

There are several packages that makeup the Dojo 2 platform:

* [`dojo/core`](https://github.com/dojo/core) - The foundational code of the Dojo 2 platform
* [`dojo/loader`](https://github.com/dojo/loader) - A TypeScript based AMD loader
* [`dojo/dom`](https://github.com/dojo/dom) - A set of API for manipulating the DOM
* [`dojo/parser`](https://github.com/dojo/parser) - A HTML document parser for instantiating objects declaratively
* [`dojo/compose`](https://github.com/dojo/compose) - A mixin/trait based composition library
* [`dojo/actions`](https://github.com/dojo/actions) - A command like library for Dojo 2 applications
* [`dojo/i18n`](https://github.com/dojo/i18n) - A set of internationalization tooling
* [`dojo/routing`](https://github.com/dojo/routing) - A routing service to build web applications with
* [`dojo/crypto`](https://github.com/dojo/crypto) - A set of libraries to deal with cryptography
* `dojo/widgets` - A set of rich UI elements

### Support Pakcages

There are a couple packages which are designed to support the Dojo 2 platform:

* [dojo/dojo2-package-template](https://github.com/dojo/dojo2-package-template) - The standard template for Dojo 2 packages, including build and packaging templates
* [dojo/grunt-dojo2](https://github.com/dojo/grunt-dojo2) - A set of Grunt tasks for use with Dojo 2 packages.

### Status

The following tables contain status information for the packages:

|Package|CI Status|Code Coverage|npm       |Stage|
|-------|---------|-------------|----------|-----|
|[dojo/core](https://github.com/dojo/core)|[![Build Status](https://travis-ci.org/dojo/core.svg?branch=master)](https://travis-ci.org/dojo/core)|[![codecov.io](http://codecov.io/github/dojo/core/coverage.svg?branch=master)](http://codecov.io/github/dojo/core?branch=master)|[![npm version](https://badge.fury.io/js/dojo-core.svg)](http://badge.fury.io/js/dojo-core)|Alpha|
|[dojo/loader](https://github.com/dojo/loader)|[![Build Status](https://travis-ci.org/dojo/loader.svg?branch=master)](https://travis-ci.org/dojo/loader)|[![codecov.io](http://codecov.io/github/dojo/loader/coverage.svg?branch=master)](http://codecov.io/github/dojo/loader?branch=master)|[![npm version](https://badge.fury.io/js/dojo-loader.svg)](http://badge.fury.io/js/dojo-loader)|Beta|
|[dojo/dom](https://github.com/dojo/dom)|[![Build Status](https://travis-ci.org/dojo/dom.svg?branch=master)](https://travis-ci.org/dojo/dom)|[![codecov.io](http://codecov.io/github/dojo/dom/coverage.svg?branch=master)](http://codecov.io/github/dojo/dom?branch=master)| |*Alpha*|
|[dojo/compose](https://github.com/dojo/compose)|[![Build Status](https://travis-ci.org/dojo/compose.svg?branch=master)](https://travis-ci.org/dojo/compose)|[![codecov.io](http://codecov.io/github/dojo/compose/coverage.svg?branch=master)](http://codecov.io/github/dojo/compose?branch=master)|[![npm version](https://badge.fury.io/js/dojo-compose.svg)](http://badge.fury.io/js/dojo-compose)|Alpha|
|[dojo/parser](https://github.com/dojo/parser)|[![Build Status](https://travis-ci.org/dojo/parser.svg?branch=master)](https://travis-ci.org/dojo/parser)|[![codecov.io](http://codecov.io/github/dojo/parser/coverage.svg?branch=master)](http://codecov.io/github/dojo/parser?branch=master)| |Prototype|
|[dojo/actions](https://github.com/dojo/actions)|[![Build Status](https://travis-ci.org/dojo/actions.svg?branch=master)](https://travis-ci.org/dojo/actions)|[![codecov.io](http://codecov.io/github/dojo/actions/coverage.svg?branch=master)](http://codecov.io/github/dojo/actions?branch=master)| |Prototype|
|[dojo/i18n](https://github.com/dojo/i18n)|[![Build Status](https://travis-ci.org/dojo/i18n.svg?branch=master)](https://travis-ci.org/dojo/i18n)|[![codecov.io](http://codecov.io/github/dojo/i18n/coverage.svg?branch=master)](http://codecov.io/github/dojo/i18n?branch=master)| |*Prototype*|
|[dojo/routing](https://github.com/dojo/routing)|[![Build Status](https://travis-ci.org/dojo/routing.svg?branch=master)](https://travis-ci.org/dojo/routing)|[![codecov.io](http://codecov.io/github/dojo/routing/coverage.svg?branch=master)](http://codecov.io/github/dojo/routing?branch=master)| |Proposal|
|[dojo/crypto](https://github.com/dojo/crypto)|[![Build Status](https://travis-ci.org/dojo/crypto.svg?branch=master)](https://travis-ci.org/dojo/crypto)|[![codecov.io](http://codecov.io/github/dojo/crypto/coverage.svg?branch=master)](http://codecov.io/github/dojo/crypto?branch=master)| |Proposal|
|dojo/app-factory| | | |*Proposal*|
|dojo/widgets| | | |*Proposal*|
|[dojo/grunt-dojo2](https://github.com/dojo/grunt-dojo2/)|[![Build Status](https://travis-ci.org/dojo/grunt-dojo2.svg?branch=master)](https://travis-ci.org/dojo/grunt-dojo2)|[![codecov.io](http://codecov.io/github/dojo/grunt-dojo2/coverage.svg?branch=master)](http://codecov.io/github/dojo/grunt-dojo2?branch=master)|[![npm version](https://badge.fury.io/js/grunt-dojo2.svg)](http://badge.fury.io/js/grunt-dojo2)|Alpha|
