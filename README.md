# tmartinson.com

Personal site. Interactive terminal UI hosted on Firebase.

## Commands

| Command | Description |
|---|---|
| `whoami` | Who is this guy |
| `links` | Where to find me |
| `ls` | List directory |
| `cat <file>` | Read a file (`about.txt`, `contact.txt`) |
| `echo <text>` | Echo text |
| `date` | Current date/time |
| `uname` | System info |
| `uptime` | System uptime |
| `ps` | Running processes |
| `top` | Process monitor |
| `fortune` | Words of wisdom |
| `cowsay <text>` | Important message |
| `sudo <cmd>` | Attempt privilege escalation |
| `rm -rf /` | Do not run this |
| `vim` | You will regret this |
| `matrix` | Fullscreen matrix rain (Ctrl+C to exit) |
| `man <cmd>` | Read the manual |
| `history` | Command history |
| `pwd` | Current directory |
| `clear` | Clear terminal |

## Shortcuts

| Shortcut | Action |
|---|---|
| `Tab` | Autocomplete command or filename |
| `↑ / ↓` | Navigate command history |
| `Ctrl+L` | Clear terminal |
| `Ctrl+C` | Interrupt / cancel |

## Deploy

Pushes to `master` auto-deploy to Firebase Hosting via GitHub Actions.

To deploy manually:
```bash
firebase deploy --only hosting
```
