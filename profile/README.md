# MLF

A functional language with MLF polymorphism, a self-hosted compiler, and native package tools.

The compiler infers eMLF programs, elaborates them to independently checked xMLF, and emits LLVM for native execution. The language includes algebraic data types, type classes, modules, and `do` notation.

## Toolchain

- **`emlf`** — the compiler and interpreter, written in MLF.
- **`mlfpkg`** — the native package manager, written in MLF, with local dependencies, separate module compilation, interface files, and build caching.
- **Libraries and examples** — the standard prelude, IO support, games, and Benchmarks Game workloads.

The compiler, runtime, package manager, libraries, and tests are developed together in [mlf-lang/mlf](https://github.com/mlf-lang/mlf), currently a private repository.

## Community

Use [discussions](https://github.com/mlf-lang/.github/discussions) for language ideas and ecosystem questions.

MLF is in active development. The package manager currently resolves local dependencies; a public package registry is future work.
