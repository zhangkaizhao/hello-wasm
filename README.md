# Rust to wasm

This is the code snippets of [Compiling from Rust to WebAssembly] without publishing to NPM registry.

[Compiling from Rust to WebAssembly]: https://developer.mozilla.org/docs/WebAssembly/Rust_to_wasm

Try running:

1. Building the package

Building the package to `pkg` sub-directory:

```sh
wasm-pack build --scope mynpmusername
```

2. Serving the site

```sh
cd site/
npm install
npm run serve
```
