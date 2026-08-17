<h1 align="center">XanaScript</h1>

<p align="center">
  <strong>Programe em Português. Rode em WebAssembly. Performance de verdade.</strong>
</p>

<p align="center">
  <a href="https://www.npmjs.com/package/xanascript"><img src="https://img.shields.io/npm/v/xanascript?color=6a0dad&label=npm&logo=npm" alt="npm" /></a>
  <a href="https://github.com/xanascr/xs/blob/main/LICENSE"><img src="https://img.shields.io/github/license/xanascr/xs?color=6a0dad" alt="License" /></a>
  <a href="https://github.com/xanascr/xs/releases"><img src="https://img.shields.io/github/v/release/xanascr/xs?color=6a0dad&label=release" alt="Release" /></a>
  <img src="https://img.shields.io/badge/node-%3E%3D18-6a0dad" alt="Node 18+" />
</p>

---

## O que é?

Uma linguagem de programação **fortemente tipada** com sintaxe em **português**, compilador otimizador
(JavaScript + WebAssembly + Bytecode VM), ORM embutido, macros de tempo de compilação, LSP, DAP
(debugger) e **zero dependências em runtime**.

```xs
DB Usuario {
  nome: eh-palavra,
  idade: eh-numero,
  ativo: vdd?
}

resolve main() {
  cria repo = Usuario.bota-ai({ nome: "Ana", idade: 25, ativo: verdadeiro })
  grita-ae("Bem-vinda, " + repo.nome + "!")
}
```

## ✨ Features

| | |
|---|---|
| 🇧🇷 **Sintaxe em português** | `cria`, `se-pah`, `repete-na-moral`, `resolve`, `grita-ae`... |
| ⚡ **3 backends** | Interpreter, Bytecode VM e WebAssembly (binário direto) |
| 🔍 **Type checker** | Inferência estática com `xana check` |
| 🗄️ **ORM embutido** | CRUD + validação + persistência em `.db/` |
| 🧩 **Macros** | Expansão em tempo de compilação |
| 🛠️ **LSP + DAP** | Autocomplete, hover e debugger no VS Code |
| 📦 **Package manager** | `xs pkg` com registry próprio |
| 🧪 **Test runner** | `crush` integrado, `test --watch` |
| 🚫 **Zero deps** | Sem dependências em runtime |

## 🚀 Começa já

```bash
npm install -g xanascript

# roda direto
xs run app.xs

# compila pra WebAssembly
xs build --wasm app.xs

# checa os tipos
xs check app.xs

# roda os testes
xs test

# formato e difusão
xs fmt
```

## 📦 Repositórios

| Repositório | Descrição |
|---|---|
| [**xs**](https://github.com/xanascr/xs) | ⭐ Núcleo da linguagem — compilador, CLI, VM, wasm |
| [**xs-vscode**](https://github.com/xanascr/xs-vscode) | Extensão oficial pro VS Code (syntax, LSP, debug) |
| [**xs-site**](https://github.com/xanascr/xs-site) | Site oficial da linguagem |
| [**xs-examples**](https://github.com/xanascr/xs-examples) | Exemplos prontos pra aprender |
| [**xs-ideias**](https://github.com/xanascr/xs-ideias) | Lista de pacotes e projetos feitos com XanaScript |

## 🌐 Links

- [Site](https://xanascript.xyz)
- [Docs](https://github.com/xanascr/xs/tree/main/docs)
- [npm](https://www.npmjs.com/package/xanascript)
- [Binários](https://github.com/xanascr/xs/releases)

---

<p align="center">
  <sub>Feito com 💜 — programe do seu jeito.</sub>
</p>