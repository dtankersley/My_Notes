[linux]

# Linux Commands Cheat Sheet

## File Operations

| Command | What it does |
| ------- | ------------ |
| `find . -name "*.md" -mtime -7` | Find .md files modified in last 7 days |
| `du -sh */` | Show folder sizes in current directory |
| `rsync -avz src/ dest/` | Sync files with progress (resumable) |
| `chmod 755 script.sh` | Make a script executable |
| `ln -s /path/to/target linkname` | Create a symbolic link |

## Monitoring & Logs

| Command                   | What it does                      |
| ------------------------- | --------------------------------- |
| `tail -f /var/log/syslog` | Follow log output in real-time    |
| `htop`                    | Interactive process viewer        |
| `df -h`                   | Disk space usage (human-readable) |
| `free -h`                 | Memory usage                      |
| `ss -tulnp`               | Show listening ports              |
|                           |                                   |

## Text Processing

| Command | What it does |
| ------- | ------------ |
| `grep -r "pattern" .` | Search for text recursively |
| `awk '{print $1}' file.txt` | Print first column |
| `sed -i 's/old/new/g' file.txt` | Find and replace in file |
| `wc -l file.txt` | Count lines |
| `sort file.txt \| uniq -c \| sort -rn` | Count unique occurrences |

## Notes

- Use `rsync` over `cp` for large transfers — it can resume
- `tldr <command>` gives simplified examples (install with `npm i -g tldr`)
