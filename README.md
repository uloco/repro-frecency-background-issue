# Reproduction Repository

Regarding issue https://github.com/nvim-telescope/telescope-frecency.nvim/issues/210

## How to reproduce

* Copy this config in your nvim config folder
* Use a light terminal background
* Start neovim and let it install everything etc.
* Default dark theme is loade altough neovim should detect the terminal theme background as light not as dark.
* Remove frecency as a dependency from the lazy list and restart nvim
* neovim successfully detects background as light.

I testet this in iTerm2 on MacOS but I don't think it is a terminal or OS related issue, since other plugins work fine.
