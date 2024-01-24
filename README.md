# rh

**rh** searches for a string with [ripgrep], then opens the selected match in [helix].

This code is derived from [this Hacker News post].

[helix]: https://github.com/helix-editor/helix
[ripgrep]: https://github.com/BurntSushi/ripgrep
[this hacker news post]: https://news.ycombinator.com/item?id=38474106

## Install

**rh** is distributed as a Zsh plugin.
Install it as you install your other Zsh plugins.

## Use

All arguments are passed without modification to `ripgrep`:

```sh
rh <search string>
```
