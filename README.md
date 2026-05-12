# frankenpress/homebrew-tap

Homebrew tap for the FrankenPress CLI tools.

## Install

```bash
brew install frankenpress/tap/fp
```

## What lives here

Formulas are auto-published by [`frankenpress/fp`](https://github.com/frankenpress/fp)'s
goreleaser pipeline on every `vX.Y.Z` tag. The tap is the canonical
install path for `fp` on macOS + Linux.

## Manual install (no tap)

If you'd rather not add the tap:

```bash
brew install frankenpress/tap/fp --no-tap  # or download a binary from
                                            # github.com/frankenpress/fp/releases
```

## Companion repos

- [`fp`](https://github.com/frankenpress/fp) — the CLI itself
- [`runtime`](https://github.com/frankenpress/runtime) — base container image
- [`mu-plugin`](https://github.com/frankenpress/mu-plugin)
- [`site-template`](https://github.com/frankenpress/site-template)
- [`charts`](https://github.com/frankenpress/charts)
- [`docs`](https://github.com/frankenpress/docs)
