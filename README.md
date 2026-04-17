# homebrew-humbl

A personal [Homebrew tap](https://docs.brew.sh/Taps) for CLIs I publish,
starting with [`humblskills`](https://github.com/jjfantini/humblSKILLS).

## Install a formula

```sh
brew install jjfantini/humbl/humblskills
```

The tap is added implicitly on first install. To update formulas:

```sh
brew upgrade jjfantini/humbl/humblskills
```

## How it works

Each formula in [`Formula/`](Formula) is a Ruby file describing how to
fetch a pre-built binary from that project's GitHub Releases. Formulas
are updated automatically by GoReleaser on every release of the upstream
project — this repo is a destination, not a source tree.

## Formulas here

| Formula        | Source                                                             |
| -------------- | ------------------------------------------------------------------ |
| `humblskills`  | [jjfantini/humblSKILLS](https://github.com/jjfantini/humblSKILLS)  |
