# Hacking Tools Usage CheatSheet
This is the CheatSheet for Pentester, Ethical Hacker, Bug Hunter and CTF Player so they Can Quickly use these commands.

## Information Gathering

### Nmap

```bash
namp -sC -sV -vv -O  -oN result.txt 10.10.10.3 
```
| flag | Usage |
|-------|-------|
| -sC    | Default Scripts Scan |
| -sV   | getting service and version info |
| -O    | Operating System Detection |
| -vv   | Double verbose, Shows detail info |
| -oN   | Getting Text based Results |  

### Feroxbuster


