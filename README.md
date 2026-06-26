# Hostinger Homebrew Tap

Homebrew formulae for Hostinger's command-line tools.

## Install the Hostinger API CLI

```sh
brew install hostinger/tap/hapi
```

Or tap first, then install:

```sh
brew tap hostinger/tap
brew install hapi
```

Upgrade to the latest release:

```sh
brew upgrade hapi
```

Shell tab-completion (bash/zsh/fish) is installed automatically.

## How this tap is maintained

Formulae in [`Formula/`](Formula/) are published automatically by
[GoReleaser](https://goreleaser.com/) on every release of
[`hostinger/api-cli`](https://github.com/hostinger/api-cli). They are not edited by
hand — do not commit manual changes to `Formula/hapi.rb`; they will be overwritten on
the next release.
