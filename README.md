with_bg
=======

Lets you run a command with a specified background color. Only works with iterm2.

`with_bg R G B command arguments`

R, G, and B are integers from 0 - 255.

ex: a red/yellow background so you know if you're on prod or staging
```bash
alias emp-staging="with_bg 48 48 07 EMPIRE_API_URL=https://empire.classchirp.com emp"
alias emp-prod="with_bg 64 16 16 EMPIRE_API_URL=https://empire.remind.com emp"
```
