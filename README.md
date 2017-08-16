# js-dev-env
JavaScript Development Environment
# Table of Contents
* [Editors](#editors)
* [Editor Configuration](#editor-configuration)
* [Package Management](#package-management)
* [When to Run Security Check](#when-to-run-security-check)
* [Development Webservers](#development-webservers)
* [Sharing Work-in-progress](#sharing-work-in-progress)
* [Automation](#automation)
* [Transpiling](#transpiling)
* [Module Formats](#module-formats)
* [Bundler](#bundler)
* [linter](#linter)

## Editors
* Atom
* WebStorm
* Brackets
* *VSCode*

## Editor Configuration
[EditorConfig](http://editorconfig.org/) allows you to define a consistent coding
style across multiple editors. Some editors come with built-in support for
EditorConfig while many others have plugins.

## Package Management
* Bower
* *npm*
* JSPM
* Jam
* volo

## Package Security
* retire.js
* *Node Security Platform*

## When to Run Security Check
* Manually - Easy to forget
* npm install - May be issue later
* production build - Expensive to change
* pull request - Expensive to change
* *npm start - Slows start slightly*

## Development Webservers
* http-server
* live-server
* *Express*
* budo
* Webpack dev server
* Browsersync

## Sharing Work-in-progress
* localtunnel
* ngrog
* Surge
* now

## Automation
* Grunt
* Gulp
* *npm Scripts*

## Transpiling
* *Babel*
* TypeScript
* Elm

## Module Formats
* IIFE
```javascript
(function() {
  //my code here
})();
```
* AMD
```javascript
define(['jq'], function(jq) {});
```
* CommonJS
```javascript
var jquery = require('jquery');
```
* ES6 Module
```javascript
import jQuery from 'jquery';
```

## Bundler
* RequireJS
* Browserify
* *Webpack*
* Rollup
* JSPM

## Linter
* JSLint
* JSHint
* *ESLint*