# ![Bandit Level 24](https://github.com/YunusEmreAlps/Scenarios/blob/master/ctf-bandit/assets/Bandit24.png?raw=true)

---

## Seviye Hedefi

Bir program, zamana dayalı iş planlayıcı olan *cron*'dan düzenli aralıklarla otomatik olarak çalışıyor. Yapılandırma için */etc/cron.d/* dosyasına bakın ve hangi komutun yürütülmekte olduğunu görün.

*NOT*: Bu seviye, kendi ilk kabuk betiğinizi oluşturmanızı gerektirir. Bu çok büyük bir adım ve bu seviyeyi geçtiğinizde kendinizle gurur duymalısınız!

*NOT 2*: Shell komut dosyanızın çalıştırıldıktan sonra kaldırıldığını unutmayın, bu nedenle bir kopyasını saklamak isteyebilirsiniz…

``` {.sh}
  - Host: bandit.labs.overthewire.org
  - Port: 2220
```

### Bu seviyeyi çözmek için ihtiyaç duyabileceğiniz komutlar

``` {.sh}
  cron, crontab, crontab(5) (use “man 5 crontab” to access this)
```
