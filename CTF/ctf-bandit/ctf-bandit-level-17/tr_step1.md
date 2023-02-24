# ![Bandit Level 17](https://github.com/YunusEmreAlps/Scenarios/blob/master/CTF/ctf-bandit/Bandit%20Assets/Bandit17.png?raw=true)

---

## Seviye Hedefi

Bir sonraki seviye için kimlik bilgileri, geçerli seviyenin şifresini *localhost'ta 31000 ila 32000 aralığındaki bir bağlantı noktasına göndererek alınabilir*. İlk olarak, bu bağlantı noktalarından hangilerinin onları dinleyen bir sunucuya sahip olduğunu bulun. Ardından, bunlardan hangilerinin SSL konuşup hangilerinin konuşmadığını öğrenin. Sonraki kimlik bilgilerini verecek yalnızca 1 sunucu var, diğerleri ona ne gönderirseniz onu size geri gönderecek.

``` {.sh}
  - Host: bandit.labs.overthewire.org
  - Port: 2220
```

### Bu seviyeyi çözmek için ihtiyaç duyabileceğiniz komutlar

``` {.sh}
  ssh, telnet, nc, openssl, s_client, nmap
```

### Yararlı Okuma Materyali

``` {.sh}
  - Port scanner
```
