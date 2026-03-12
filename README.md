<h3 align="center">
    rust-pack
</h3>
<h6 align="center">
    <a href="#about">about</a>
    ·
    <a href="#install">install</a>
    ·
    <a href="#dev">contribute</a>
</h6>
<div align="center">

![GitHub](https://img.shields.io/github/license/abczyx2006/rust-pack?color=A3BE8C&style=flat-square)
![Installs](https://vsmarketplacebadges.dev/installs-short/abczyx2006.main-pack.svg?&logo=visualstudiocode&color=A3BE8C)
![Version](https://vsmarketplacebadges.dev/version-short/abczyx2006.main-pack.svg?&logo=visualstudiocode&color=A3BE8C&label=version)

</div>

### about

- rust-pack is a monorepo for 6 extension packs.
  - main
    - extension pack of all the extensions given below.

  - rust
    - extensions for [`rust-lang`](https://rust-lang.org)
  - nodejs
    - extension for [`js`](https://nodejs.org/en) / [`ts`](https://www.typescriptlang.org/)
  - svelte
    - extensions for [`svelte`](https://svelte.dev)
  - python
    - extensions for [`python`](https://www.python.org)
  - vscode
    - extensions for general purpose use on [`vscode`](vscode:)

<br />

### install

1. press: <kbd>Ctrl + P</kbd>

2. type `ext install abczyx2006.main-pack`

3. press <kbd>Enter</kbd>

### contribute

- suggest extensions to add in the form of issues

- create pull request for adding extensions

- file-structure

```
🗀 rust-pack
├── 🗀 main
│   ├── 🗀 assets
│   │   └── 🖻 icon.png
│   ├── 🖹 LICENSE
│   ├── 🗎 package.json
│   └── ▼ README.md
│   └── 🗋 .vscodeignore
├── 🗀 nodejs
│   ├── 🗀 assets
│   │   └── 🖻 icon.png
│   ├── 🖹 LICENSE
│   ├── 🗎 package.json
│   └── ▼ README.md
│   └── 🗋 .vscodeignore
├── 🗀 python
│   ├── 🗀 assets
│   │   └── 🖻 icon.png
│   ├── 🖹 LICENSE
│   ├── 🗎 package.json
│   └── ▼ README.md
│   └── 🗋 .vscodeignore
├── ▼ README.md
├── 🗀 rust
│   ├── 🗀 assets
│   │   └── 🖻 icon.png
│   ├── 🖹 LICENSE
│   ├── 🗎 package.json
│   └── ▼ README.md
│   └── 🗋 .vscodeignore
├── 🗀 svelte
│   ├── 🗀 assets
│   │   └── 🖻 icon.png
│   ├── 🖹 LICENSE
│   ├── 🗎 package.json
│   └── ▼ README.md
│   └── 🗋 .vscodeignore
└── 🗀 vscode
│   ├── 🗀 assets
│   │   └── 🖻 icon.png
    ├── 🖹 LICENSE
    ├── 🗎 package.json
    └── ▼ README.md
    └── 🗋 .vscodeignore
```
