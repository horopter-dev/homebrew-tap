# Horopter Homebrew tap

Homebrew casks for [Horopter](https://docs.horopter.dev/)'s command-line tools, published by
each [horopter release](https://github.com/horopter-dev/horopter/releases).

## Install

```bash
brew install horopter-dev/tap/horo
brew install horopter-dev/tap/horoctl
```

Installing by the fully qualified name taps the repository and trusts only that cask, which
Homebrew requires of a third-party tap ([Tap Trust](https://docs.brew.sh/Tap-Trust)).

## Casks

| Cask | Description |
| --- | --- |
| `horo` | Records changes and reads them back |
| `horoctl` | Manages Horopter tenants and credentials and applies migrations |

The casks in `Casks/` are written by GoReleaser on every horopter release. Don't edit them by
hand: the next release overwrites them.
