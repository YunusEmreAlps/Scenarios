# ![Bandit Level 21](https://github.com/YunusEmreAlps/Scenarios/blob/master/ctf-bandit/assets/Bandit21.png?raw=true)

---

## Seviye Hedefi

Ana dizinde aşağıdakileri yapan bir setuid ikili dosyası vardır: komut satırı bağımsız değişkeni olarak belirttiğiniz bağlantı noktasında localhost ile bağlantı kurar. Daha sonra bağlantıdan bir metin satırı okur ve bunu bir önceki seviyedeki (bandit20) şifreyle karşılaştırır. Şifre doğru ise bir sonraki seviye (bandit21) için şifreyi iletecektir.

NOT: Düşündüğünüz gibi çalışıp çalışmadığını görmek için kendi ağ arka plan programınıza bağlanmayı deneyin.

``` {.sh}
  - Host: bandit.labs.overthewire.org
  - Port: 2220
```

### Bu seviyeyi çözmek için ihtiyaç duyabileceğiniz komutlar

``` {.sh}
  ssh, nc, cat, bash, screen, tmux, Unix ‘job control’ (bg, fg, jobs, &, CTRL-Z, …)
```
