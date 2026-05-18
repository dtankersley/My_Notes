Useful Tools# Useful Linux Tools

## CLI Tools Worth Installing

**htop** — Interactive process viewer, much better than `top`
```
sudo apt install htop
```

**bat** — `cat` with syntax highlighting and line numbers
```
sudo apt install bat
```

**fzf** — Fuzzy finder for files and command history. Press `Ctrl+R` after installing for magic.
```
sudo apt install fzf
```


**ripgrep (rg)** — Blazing fast recursive search, better than `grep -r`
```
sudo apt install ripgrep
```

## Useful Aliases

Add these to `~/.bashrc` or `~/.zshrc`:

```bash
alias ll='ls -alh'
alias gs='git status'
alias gd='git diff'
alias dc='docker compose'
alias cls='clear'
```

## Notes

- After editing `.bashrc`, run `source ~/.bashrc` to apply changes
- Most of these tools are available through `apt` on Ubuntu/Debian
