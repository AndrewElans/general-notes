# general-notes

## macos sequoia 
### zsh terminal `man` command returnes `Unknown locale, assuming C`
#### Fix
- open .zshrc in editor
  -  location -> `/Users/ae`
- add
```terminal
export LANG="en_US.UTF-8"
export LC_CTYPE="en_US.UTF-8"
```
- from [here](https://apple.stackexchange.com/a/463210)
