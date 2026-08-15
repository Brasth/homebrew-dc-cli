# homebrew-dc-cli

Homebrew tap for [dc-cli](https://dc.brasth.com).

```bash
brew tap Brasth/dc-cli
brew install dc-cli
```

Needs Docker (Colima or Desktop). Official `@devcontainers/cli` is separate (`npm i -g @devcontainers/cli`).

Formula is copied from `Brasth/dc-cli` `packaging/homebrew/dc-cli.rb`. After a new `v*` release, update version + sha256 with `scripts/print-release-shas.sh`.
