# ![Bandit Level 22](https://github.com/YunusEmreAlps/Scenarios/blob/master/ctf-bandit/assets/Bandit22.png?raw=true)

---

## Seviye Hedefi

Bir program, zamana dayalı iş planlayıcı olan *cron*'dan düzenli aralıklarla otomatik olarak çalışıyor. Yapılandırma için */etc/cron.d/* dosyasına bakın ve hangi komutun yürütülmekte olduğunu görün.

``` {.sh}
  - Host: bandit.labs.overthewire.org
  - Port: 2220
```

### Bu seviyeyi çözmek için ihtiyaç duyabileceğiniz komutlar

``` {.sh}
  cron, crontab, crontab(5) (use “man 5 crontab” to access this)
```
