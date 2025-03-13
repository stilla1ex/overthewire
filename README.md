<h3 align="center">overthewire wargames</h3>

---
### Bandit Level 0  - First, we need to ssh to the overthewire

**Level Goal**  
The password for the next level is stored in a file called `readme` located in the home directory. Use this password to log into `bandit1` using SSH.  

Whenever you find a password for a level, use SSH (on port `2220`) to log into that level and continue the game.  

**Commands you may need to solve this level:**  
```bash
  ls, cd, cat, file, du, find
```

**Type the following commands**
```bash
  ssh bandit0@bandit.labs.overthewire.org -p 2220
```
***password***
```bash
  bandit0
```
