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
* [Testing Framework](#testing-framework)
* [Assertion Library](#assertion-library)
* [Helper Library](#helper-library)
* [Where to Run Tests](#where-to-run-tests)
* [Continuous Integration](#continuous-integration)

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

## Testing Framework
* *Mocha*
* Jasmine
* Tape
* QUnit
* AVA
* Jest

## Assertion Library
* *Chai*

## Helper Library
* *JSDom*
* *Cheerio*

## Where to Run Tests
* Browser
  * Karma
  * Testem
* Headless Browser
  * PhantomJS
* In-memory DOM
  * *JSDOM*

## Continuous Integration
* *Travis*
* Appveyor
* Jenkins
* CircleCI
* Semaphore
* SnapCI