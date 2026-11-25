# c-toolchain

Generated files, don't edit. Each publish replaces this branch.

The C compiler used by the course pages on https://riad.run/learn/,
served at https://riad.run/c-toolchain/. It's [YoWASP clang](https://yowasp.org/)
(Clang/LLD compiled to WebAssembly, from the `@yowasp/clang` npm package),
with the header and library archive trimmed to C for wasm32-wasip1 and the
.wasm/.tar files gzipped. The build scripts live in the blog's source repo
(scripts/build-toolchain.mjs, scripts/publish-toolchain.sh).

LLVM is under the Apache License 2.0 with LLVM Exceptions; see
https://llvm.org/LICENSE.txt.
