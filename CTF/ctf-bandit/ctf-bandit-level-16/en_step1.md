# Bandit Level 16

---

## Level Goal

The password for the next level can be retrieved by submitting the password of the current level to *port 30001 on localhost* using SSL encryption.

*Helpful note: Getting “HEARTBEATING” and “Read R BLOCK”? Use -ign_eof and read the “CONNECTED COMMANDS” section in the manpage. Next to ‘R’ and ‘Q’, the ‘B’ command also works in this version of that command…*

``` {.sh}
  - Host: bandit.labs.overthewire.org
  - Port: 2220
```

### Commands you may need to solve this level

``` {.sh}
  ssh, telnet, nc, openssl, s_client, nmap
```

### Helpful Reading Material

``` {.sh}
  - Secure Socket Layer/Transport Layer Security on Wikipedia
  - OpenSSL Cookbook - Testing with OpenSSL
```

![Bandit Level 16](https://cdn.bulutbilisimciler.com/public/images/bandit/Bandit16.png)
