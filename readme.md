# 2022

> My personal preferences for Development and Tech Expectations in 2022.


## Defaults

> Default Settings and Practises for Development, Languages, Frameworks and Projects.

### General

* IP = IPv6 otherwise use IPv4
* Websites: mobile first (if analytics don't tell otherwise)
* no pointless Blockchains (or event SSI)
* no Bitcoin, Ethereum or other crypto currencies
* no fucking scam NFTs
* no IE support (but there are now many old mobile Chromiums and Safaris)


### Local Machine

* still macOS (even though NixOS is still tempting)
* Docker still kinda sucks (from M1) on it (compared to linux)
  * alternatives are hard due to ARM
  * but nix solves a lot
* nix as main package-manager
* nix-darwin (for OS defaults)
* nix home-manager
* rest Homebrew casks
* iterm2
* fish
* starship

### Editor

1. neovim
  * todo: migrate to full lua code and use neovim-lsp all in (with treesitter, telescope, neogit etc)
  * Also with a nice native VimR
2. Sublime Text
  With Version 4 it got a huge upgrade (and D.A. also still uses and loves it)
3. DataSpell
4. VS Code (just to play around and explore and for Codespaces etc)


### JavaScript

#### Package Manager

* NPM is still ok
* pnpm and yarn still seem a bit superiour
* yarn has a nice cli (whereas pnpm is harder to type)
* pnpm can do everything (workspaces, overrides, even node versions)
* volta (instead of nvm or manual homebrew linking) love it so far!
  * although pnpm support is missing (and general development/releases seem slowed down)
  * upgrade is still weird though

#### JS/Node Projects

* Typescript by default (esbuild, babel and ts-node)
* Use more Deno for personal projects (so far very cool)
* Favour npm scripts over gulp/grunt
* Gulp is still alright (and used in typescript or vscode)
* zx might be a good addition
* Vite is love (with esbuild and rollup)
* webpack is still ok
* Use SWC over Babel for everything (except if the minified code is still too large)
* Use Parcel for quick or small projects
* Node v17
* Node v16 if LTS is required
* Vue 3 (with Composition API, setup hook)
* preact / React
* petite-vue
* Move to vitest (from jest)
* Use more Tailwind/WindiCSS where possible


### Static pages

* 11ty
* Hugo
* Sphinx


### Server

* Uberspace is still nice
* HetzerCloud is awesome (still no NixOS images)
  * but the cli is good and Terraform
* if possible: use more nix instead of ansible


### Elixir

* Version 1.13


### Rails

* Version 7


### LaTeX

* Overleaf is still fine for most!


## Hopes and wishes

* Rome(tools) will be released
  and pretty much speed up pretty js, linting js and run tests (hopefully with good IDE support)
* GitLab and GitHub will support (displaying etc) key signing with SSH keys
* Node Corepack will be stable
* Bitcoin-Bros disappear into void


## How it's going


### Surprises


