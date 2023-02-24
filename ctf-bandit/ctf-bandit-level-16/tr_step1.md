# ![Bandit Level 16](https://github.com/YunusEmreAlps/Scenarios/blob/master/ctf-bandit/assets/Bandit16.png?raw=true)

---

## Seviye Hedefi

Bir sonraki seviyenin şifresi, geçerli seviyenin şifresini SSL şifrelemesi kullanılarak *localhost'ta 30001 numaralı bağlantı* noktasına göndererek alınabilir.

**Faydalı not: "HEARTBEATING" ve "Read R BLOCK" alıyor musunuz? -ign_eof kullanın ve kılavuz sayfasındaki "BAĞLANTILI KOMUTLAR" bölümünü okuyun. 'R' ve 'Q'nun yanında, 'B' komutu da o komutun bu versiyonunda çalışır...**

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
  - Wikipedia'da Güvenli Yuva Katmanı/Aktarım Katmanı Güvenliği
  - OpenSSL Yemek Kitabı - OpenSSL ile Test Etme
```
