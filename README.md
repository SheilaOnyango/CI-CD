# null_or_empty

[![Node CI](https://github.com/SheilaOnyango/CI-CD/actions/workflows/whatever.yml/badge.svg)](https://github.com/SheilaOnyango/CI-CD/actions/workflows/whatever.yml)

A simple Node.js package that checks, if a given string is null or empty.

## Usage

First, install the package using npm:

    npm install @SheilaOnyango/CI-CD --save

Then, require the package and use it like so:

    var isNullOrEmpty = require('@SheilaOnyango/CI-CD');

    console.log(isNullOrEmpty("")); // true
    console.log(isNullOrEmpty(null)); // true
    console.log(isNullOrEmpty(undefined)); // true

    console.log(isNullOrEmpty("Hello World")); // false

## License

MIT
