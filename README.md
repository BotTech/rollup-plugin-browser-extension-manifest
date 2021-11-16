# @bottechnz/rollup-plugin-browser-extension-manifest

🍣 A Rollup plugin that processes browser extension manifests.

## Why?

There is another plugin [rollup-plugin-chrome-extension] which does this too however it doesn't work the way I wanted.

This particular plugin is solely responsible for taking the `manifest.json` entry point and replacing it with the entry
points from within that file. It also updates the `manifest.json` with other information such as the version so that
this only needs to be maintained in the `package.json` file.

## Requirements

TODO

## Install

Using npm:

```console
pnpm install @bottechnz/rollup-plugin-browser-extension-manifest --save-dev
```

## Usage

TODO

## Options

TODO

[rollup-plugin-chrome-extension]: https://github.com/extend-chrome/rollup-plugin-chrome-extension
