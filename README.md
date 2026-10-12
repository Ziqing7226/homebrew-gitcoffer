# Homebrew tap for GitCoffer

[GitCoffer](https://github.com/Ziqing7226/GitCoffer) — an encrypted git
remote that lives on your own disk: `git push` into a passphrase-protected
vault on a USB drive or second disk, with stock git and VSCode.

```sh
brew tap Ziqing7226/gitcoffer
brew install Ziqing7226/gitcoffer/gitcoffer
```

The formula builds the two binaries (`gitcoffer`, `git-remote-coffer`)
from the tagged source archive; git finds the helper through `PATH`.
