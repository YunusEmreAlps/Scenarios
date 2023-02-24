# Bandit Level 21

---

## Level Goal

There is a setuid binary in the homedirectory that does the following: it makes a connection to localhost on the port you specify as a commandline argument. It then reads a line of text from the connection and compares it to the password in the previous level (bandit20). If the password is correct, it will transmit the password for the next level (bandit21).

NOTE: Try connecting to your own network daemon to see if it works as you think

``` {.sh}
  - Host: bandit.labs.overthewire.org
  - Port: 2220
```

### Commands you may need to solve this level

``` {.sh}
  ssh, nc, cat, bash, screen, tmux, Unix ‘job control’ (bg, fg, jobs, &, CTRL-Z, …)
```

![Bandit Level 21](https://cdn.bulutbilisimciler.com/public/images/bandit/Bandit21.png)
