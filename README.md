# topotal/homebrew-tap

Homebrew tap for CLIs published by [Topotal](https://topotal.com/).

## Usage

```sh
brew install topotal/tap/<name>
```

Or tap once and install by name:

```sh
brew tap topotal/tap
brew install <name>
```

The available CLIs are the casks in [`Casks/`](Casks).

## Maintenance

The casks are generated and pushed by each CLI's release workflow with
[GoReleaser](https://goreleaser.com/). Do not edit them by hand; change the CLI's
`.goreleaser.yaml` instead.
