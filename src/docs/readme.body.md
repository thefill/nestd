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
