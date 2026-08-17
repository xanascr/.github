<p align="center">
  <h1 align="center">XanaScript</h1>
  <p align="center">A typed programming language with Portuguese syntax, an optimizing compiler, a built-in ORM, and native WebAssembly support.</p>
  <p align="center">
    <a href="https://www.npmjs.com/package/xanascript"><img src="https://img.shields.io/npm/v/xanascript.svg?style=flat&color=%23f58b8e" alt="npm"></a>
    <a href="https://github.com/xanascr/xs/blob/main/LICENSE"><img src="https://img.shields.io/github/license/xanascr/xs?style=flat&color=%23f58b8e" alt="License"></a>
    <a href="https://github.com/xanascr/xs/releases"><img src="https://img.shields.io/github/v/release/xanascr/xs?style=flat&color=%23f58b8e" alt="Release"></a>
    <a href="https://xanascript.xyz"><img src="https://img.shields.io/badge/website-xanascript.xyz-%23f58b8e?style=flat" alt="Website"></a>
  </p>
</p>

XanaScript is a strong-typed programming language with Portuguese keywords, built for readability and speed. It ships with an optimizing compiler that targets JavaScript and WebAssembly, a bytecode VM, a built-in ORM, compile-time macros, LSP and DAP support, and zero runtime dependencies.

## Quick Start

```xs
DB Usuario {
  nome: eh-palavra,
  idade: eh-numero,
  ativo: vdd?
}

resolve main() {
  cria repo = Usuario.bota-ai({ nome: "Ana", idade: 25, ativo: verdadeiro })
  grita-ae("Welcome, " + repo.nome + "!")
}
```

```bash
npm install -g xanascript
xana run app.xs
```

Requires Node.js 18+.

## Features

- **Typed** - strong static typing with inference (`xana check`)
- **Portuguese syntax** - keywords in Portuguese for accessibility
- **Optimizing compiler** - JavaScript and WebAssembly output
- **Bytecode VM** - stack-based VM for fast execution
- **Built-in ORM** - JSON-backed CRUD with validation
- **Package manager** - `xana install`, `xana publish`
- **LSP support** - IDE integration with diagnostics and autocomplete
- **DAP support** - debugging with breakpoints, step and variables
- **Macros** - compile-time code generation
- **Test runner** - native test framework (`xana test`)
- **Zero dependencies** - no runtime dependencies

## CLI

```
xana run <file>          Run .xs (AST interpreter)          [roda]
xana vm <file>           Run .xs (bytecode VM)              [roda --vm]
xana check <file>        Type-check without executing       [verifica]
xana fmt <file>          Format code                        [ajeita]
xana build <file>        Generate JavaScript                [monta]
xana build --wasm <file> WebAssembly output
xana test [dir]          Run tests (*test*.xs)              [teste]
xana lsp                 Language Server Protocol           [fala-com-ide]
xana repl                Interactive REPL                   [bate-papo]
```

Every command has a Portuguese alias (shown in `[brackets]`); both forms work.

## Repositories

| Repository | Description |
|------------|-------------|
| [xs](https://github.com/xanascr/xs) | Core language - compiler, CLI, VM, wasm |
| [xs-vscode](https://github.com/xanascr/xs-vscode) | Official VS Code extension |
| [xs-site](https://github.com/xanascr/xs-site) | Official website |
| [xs-examples](https://github.com/xanascr/xs-examples) | Code examples |
| [xs-ideias](https://github.com/xanascr/xs-ideias) | Packages and projects built with XanaScript |

## Documentation

- [Getting Started](https://github.com/xanascr/xs/blob/main/docs/getting-started.md)
- [Syntax Reference](https://github.com/xanascr/xs/blob/main/docs/syntax.md)
- [Type System](https://github.com/xanascr/xs/blob/main/docs/types.md)
- [Standard Library](https://github.com/xanascr/xs/blob/main/docs/stdlib.md)
- [ORM](https://github.com/xanascr/xs/blob/main/docs/orm.md)
- [CLI Reference](https://github.com/xanascr/xs/blob/main/docs/cli.md)
- [Examples](https://github.com/xanascr/xs/blob/main/docs/examples.md)

## Links

- Website: [xanascript.xyz](https://xanascript.xyz)
- npm: [xanascript](https://www.npmjs.com/package/xanascript)
- Releases: [github.com/xanascr/xs/releases](https://github.com/xanascr/xs/releases)