# tslint-config-ultra

This is a tslint plugin ([https://palantir.github.io/tslint/](tslint)) with my personal coding style.
Extends from tslint:recommended with some minor changes, tabs and no semicolons.

## Why tabs

Because it's the only way. I used to indent my code with 2 spaces (4 are just too much! :P), but using tabs is just the right way. Period. When using tabs, one indentation level equals one character. And everyone can decide how a tab is displayed.

Github sadly displays tab as 8 spaces, which looks kinda ugly. However, there are dozens of plugins which fix that with a single click. The same applies to editors like nano where you can simply set the tabsize in your settings.

Usage:

```sh
npm i tslint tslint-config-ultra -D
# or
yarn add tslint tslint-config-ultra --dev
```

Then, add the following snippet to your tslint.json:

`"extends": "ultra"`

Yay!
