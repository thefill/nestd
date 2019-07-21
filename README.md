[//]: # (Readme partial used by an default readme page)

# Nestd

Recursive file operations toolkit.

[//]: # (Readme partial used by an default readme page)

[![Codacy quality](https://api.codacy.com/project/badge/Grade/b5f8bff3dbbe4abc8f581547fe8b57bb)](https://www.codacy.com/app/fifofil/nestd?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=thefill/nestd&amp;utm_campaign=Badge_Grade)
[![Coverage](https://api.codacy.com/project/badge/Coverage/b5f8bff3dbbe4abc8f581547fe8b57bb)](https://www.codacy.com/app/fifofil/nestd?utm_source=github.com&utm_medium=referral&utm_content=thefill/nestd&utm_campaign=Badge_Coverage)
[![Greenkeeper badge](https://badges.greenkeeper.io/thefill/nestd.svg)](https://greenkeeper.io/)
[![CricleCi badge](https://circleci.com/gh/thefill/nestd/tree/master.svg?style=shield)](https://circleci.com/gh/thefill/nestd)

![npm version](https://img.shields.io/npm/v/nestd.svg)
[![Open issues](https://img.shields.io/github/issues-raw/thefill/nestd.svg)](https://github.com/thefill/nestd/issues)
![Types: TypeScript](https://img.shields.io/npm/types/nestd.svg)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

[//]: # (Readme partial used by an default readme page)

## Main features

*   recursive file operations
*   Typescript types included
*   exposes esm/cjs modules
*   always 100% test coverage

## Guide

*   [Installation](#installation "Installation")
*   [Basic usage](#basicusage "Basic usage")
*   [API documentation](#documentation "Documentation")

## Installation

<pre>npm install --save nestd</pre>

or

<pre>yarn add nestd</pre>

or

<pre>pnpm --save nestd</pre>

## Basic usage

Nestd main method replaces provided string or regex match with another text.

### Replace string or regex match with another string in all files below path

<pre>const Nestd = require('nestd@.0.3').Nestd;
const nestd = new Nestd();

function async run(){
    await nestd.replace('some-text', 'path');
}
run();</pre>

[//]: # (Readme partial used by an markdown readme page)

## Documentation

Full API documentation for this package can be found [here](https://thefill.github.io/nestd "API documentations for the package")
