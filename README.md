# general-notes

## macos sequoia 
### zsh terminal `man` command returnes `Unknown locale, assuming C`
#### Fix
- open .zshrc in editor
  -  location -> `/Users/ae`
- add
```bash
export LANG="en_US.UTF-8"
export LC_CTYPE="en_US.UTF-8"
```
```batch
export LANG="en_US.UTF-8"
export LC_CTYPE="en_US.UTF-8"
```
```powershell
export LANG="en_US.UTF-8"
export LC_CTYPE="en_US.UTF-8"
```
- from [here](https://apple.stackexchange.com/a/463210)
- man manual [tldr.sh](https://tldr.sh)
