# Unfield's Homebrew tap

```sh
brew tap unfield/tap
brew trust unfield/tap     # newer Homebrew versions require this for third-party taps
brew install --cask reclaim
```

This installs [Reclaim](https://github.com/Unfield/Reclaim), a free, open-source disk cleanup app for macOS, along with its `reclaim` command-line tool.

The cask in `Casks/` is updated automatically by Reclaim's release workflow.
