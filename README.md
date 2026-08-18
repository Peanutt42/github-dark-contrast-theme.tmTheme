# github-dark-contrast-theme.tmTheme

.tmTheme of GitHub Dark Contrast Theme ([github-dark-contrast-theme.nvim](https://github.com/Peanutt42/github-dark-contrast-theme.nvim) neovim theme)
to be used for bat and delta.

## How to install in bat/delta

(installing as a bat theme will automatically make the theme available in delta)

```bash
mkdir -p "$(bat --config-dir)/themes"
cd "$(bat --config-dir)/themes"

# copy the ./GitHub Dark Contrast.tmTheme file into this ./themes dir
# you can also just download the single file instead of cloning this repo
cp "/path/to/this/repo/GitHub Dark Contrast.tmTheme" .

bat cache --build
```

The theme should then be available as "GitHub Dark Contrast" when running `bat --list-themes`

<br>

To install the delta "feature" named "github-dark-contrast" that uses this tmTheme, \
look at [github-dark-contrast-theme.delta](https://github.com/Peanutt42/github-dark-contrast-theme.delta).
