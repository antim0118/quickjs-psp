# ⚡️ QuickJS - A mighty JavaScript engine

## Overview

QuickJS is a small and embeddable JavaScript engine. It aims to support the latest
[ECMAScript] specification.

This project is a _fork_ of the [original QuickJS project] by Fabrice Bellard and Charlie Gordon, after it went dormant, with the intent of reigniting its development.

## Getting started

Head over to the [project website] for instructions on how to get started and more
documentation.

## Building for PSP

Type in console:

```bash
mkdir build
cd build
psp-cmake ..
make
```

Then check for `libqjs.a` and `libqjs-libc.a` files in `build/` folder.

## Download build
1. Go to [Actions tab](https://github.com/antim0118/quickjs-psp/actions?query=workflow%3Abuild).
2. Open latest build.
3. Download `libs` artifact in *Artifacts*.

## Authors

[@bnoordhuis], [@saghul], and many more [contributors].

[ECMAScript]: https://tc39.es/ecma262/
[original QuickJS project]: https://bellard.org/quickjs
[@bnoordhuis]: https://github.com/bnoordhuis
[@saghul]: https://github.com/saghul
[contributors]: https://github.com/quickjs-ng/quickjs/graphs/contributors
[project website]: https://quickjs-ng.github.io/quickjs/
