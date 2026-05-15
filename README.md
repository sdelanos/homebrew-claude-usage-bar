# homebrew-claude-usage-bar

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

Homebrew cask for [Claude Usage Bar](https://github.com/sdelanos/claude-usage-bar)
— a macOS menu-bar app that shows your Claude API rate-limit usage at a
glance.

## Install

```sh
brew tap sdelanos/claude-usage-bar
brew install --cask claude-usage-bar
open -a "ClaudeUsageBar"
```

## What this repo is for

Just the cask formula. Source, issues, releases, and docs live in the
[main repo](https://github.com/sdelanos/claude-usage-bar). The cask
formula here is bumped by the maintainer after each release; see the
main repo's [`RELEASING.md`](https://github.com/sdelanos/claude-usage-bar/blob/main/RELEASING.md)
for the loop.

## First-run setup

The cask installs a prebuilt `.app`. After launching, click the
menu-bar icon and follow the **Set up authentication** card — one paste
of `claude setup-token` and you're done. Full docs in the
[main README](https://github.com/sdelanos/claude-usage-bar#first-run-setup-30-seconds).

## License

MIT. See [LICENSE](LICENSE).
