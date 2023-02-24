# ![Bandit Level 6](https://github.com/YunusEmreAlps/Scenarios/blob/master/CTF/ctf-bandit/Bandit%20Assets/Bandit6.png?raw=true)

---

## Seviye Hedefi

Bir sonraki seviyenin şifresi, *inhere* dizini altındaki bir dosyada saklanır ve aşağıdaki özelliklerin tümüne sahiptir::

``` {.sh}
  - insan tarafından okunabilir(human-readable)
  - 1033 bayt boyutunda(1033 bytes in size)
  - çalıştırılamaz(not executable)
```

``` {.sh}
  - Host: bandit.labs.overthewire.org
  - Port: 2220
```

### Bu seviyeyi çözmek için ihtiyaç duyabileceğiniz komutlar

``` {.sh}
  ls , cd , cat , file , du , find
```
