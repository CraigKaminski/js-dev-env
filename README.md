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
* [HTTP Call Library](#http-call-library)
* [Mock HTTP](#mock-http)
* [Steps for Mocking HTTP](#steps-for-mocking-http)
* [Error Logging](#error-logging)

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

## HTTP Call Library
* Node
  * http
  * request
* Browser
  * XMLHttpRequest
  * jQuery
  * Framework-based
  * *Fetch*
    * [window.fetch polyfill](https://github.com/github/fetch)
    * [isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch)
* Node & Browser
  * [isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch)
  * xhr
  * SuperAgent
  * Axios

Use [Polyfill.io](https://polyfill.io/v2/docs/) to inly include polyfills to browsers that need it.

## Mock HTTP
* Nock
* Static JSON
* Create development webserver
  * api-mock
  * *JSON server*
  * *JSON Schema faker*
  * Browsersync
  * Express

## Steps for Mocking HTTP
  1. Declare you schema
    * JSON Schema Faker
  2. Generate Random Data
    * faker.js
    * chance.js
    * randexp.js
  3. Server Data via API
    * JSON Server

## Error Logging
  * TrackJS
  * Sentry
  * New Relic
  * Raygun