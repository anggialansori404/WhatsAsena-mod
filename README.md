<div align="center">
  <img src="https://i.hizliresim.com/6Bbj7i.jpg" width="200" height="200">
  <h1>🐺 WhatsAsena</h1>
  <h3>Remod by @elzeXD</h3>
</div>
<p align="center">
    WhatsAsena project - Makes it easy and fun to use Whatsapp. Also first userbot for Whatsapp.
    <br>
        <a href="https://t.me/elzeXD"> My Telegram</a> |
        <a href="https://elzeXD.github.io">My Website</a> |
        <a href="https://t.me/WHATSASENA">Telegram Channel</a> |
        <a href="https://t.me/AsenaSupport">Telegram Group</a> |
    <br>
</p>

----
![Docker Pulls](https://img.shields.io/docker/pulls/fusuf/whatsasena?style=flat-square) ![Docker Image Size (latest by date)](https://img.shields.io/docker/image-size/fusuf/whatsasena?style=flat-square)

## 📢 Guide
> [Untuk bantuan dan dukungan silahkan kunjungi channel Telegram kami.](https://t.me/AsenaSupport)

> [Cara Pasang](https://github.com/Quiec/WhatsAsena/wiki)

> [Video Guide](https://www.youtube.com/watch?v=029KmetlKPU)

> [Bantu Translate via Crowdin](https://crowdin.com/project/whatsasena)

## 🔎 What is WhatsAsena?
**WhatsAsena,** is a WhatsApp helper bot written by [Yusuf Usta](https://github.com/Quiec). Does not log into your account It is written on WhatsApp Web API.

### Cara Instal
## A. String Session

**WAJIB 2 HAPE!**
1. Buka Termux di HP pembantu, ketik ini berurutan, tunggu selesai command yang satu baru lanjut yang lain
```apt update
apt install nodejs --fix-missing
pkg install git
git clone https://github.com/Quiec/WhatsAsena
cd WhatsAsena
npm install @adiwajshing/baileys
npm install chalk
node qr.js
```

Atau cara cepat ketik:
```bash <(curl -L https://t.ly/qYqy)```

2. Ikuti instruksinya, masukin no WA, 0 ganti +62
3. Cek kode verifikasi di HP utama, lalu masukin kode verifikasi di Termux
4. **HARUS CEPAT!!! Soalnya nanti kodenya ganti-ganti cepet banget** Balik ke HP yang WAnya mau dipasang bot, buka Pengaturan -> WA Web, lalu scan QR code yang di Termux.
*Bila perlu, dari awal HP udah harus siap di menu WA Web.*
5. Setelah scan nanti ada kode di Termux, nah copy itu kode mulai dari `ASENA ;;;` sampai kodenya habis, simpan di notes bila perlu


## B. Install Bot
1. Klik tombol dibawah ini:

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/elzeXD/WhatsAsena)
2. *Kalo gapunya akun heroku, buat dulu, kalo udah punya, rekomendasi di akun baru karena ini rakus makan dyno dan lu pada juga bakal sering make*
3. Isi `ASENA_SESSIONS` dengan kode dari Termux tadi
4. Kalo mau bahasa indo, di `LANGUAGE` isi ID
5. Tunggu prosesnya sekesai, Manage App, nyalain dyno, dan silahkan tonton log, kalo berhasil selamat anda punya bot!

## F.A.Q
Beberapa pertanyaan yang sering diajukan:
### Ini aman kan? Lo pada bisa baca pesan gw trus mata2in gw kan, ngaku lo!
Ini open source, semua orang bisa analisis kodenya, tidak ada kode untuk mata-matain orang. **Kani tidak bisa mengakses akun anda, btw sori nih bos, lagian lo siape? Orang penting ae bukan.**

### Serius? Tapi kata temenku, kalo ada notifikasi WhatsApp Web itu tandanya WA ku disadap/dibobol?
Kalo lu pada masih menganut itu, yaudah gausah instal, yaelah ribet amat.
Misal WAmu beneran disadap, buka **Whatsapp> Titik 3> Whatsapp Web> Nah kan ada daftar komputer tuh, keluarin aja semua, tapi yang ada tulisan Baileys jangan, karena itu botnya.**
*Tapi kalo udah terlanjur, yaudah balik lagi ke atas, nyari string session, trus atur lagi di Heroku.*

### Mantul banget ini, tapi bayar ga?
**Gak dan gak bakal.** Tapi kalo mau donasi langsung ke pembuatnya aja via [Telegram](https://t.me/fusuf) .
Kalau mau ke saya juga boleh, via [Saweria](https://saweria.co/elzeXD)

### • What does Asena mean?
[Asena](https://tr.wikipedia.org/wiki/Asena), comes from Turkish mythology. According to Turkish mythology, Asena is a she-wolf that plays an important role.

### ⚠️ Warning! 
```
Due to Userbot; Your WhatsApp account may be banned.
This is an open source project, you are responsible for everything you do. 
Absolutely, Asena executives do not accept responsibility.
By establishing the Asena, you are deemed to have accepted these responsibilities.
```

## Credit

[![Yusuf Usta](https://github.com/quiec.png?size=100)](https://quiec.tech) | [![Alperen Ç](https://github.com/xacnio.png?size=100)](https://github.com/xacnio)
---|---
[Yusuf Usta](https://t.me/fusuf) | [Alperen Ç](https://t.me/xacnio)
Base, Development, Idea, Modules |  Bug Fixes, Modules
Saya cuma remodder.

## Thanks To
- [@adiwajshing](https://github.com/adiwajshing) for coded [Baileys](https://github.com/adiwajshing/Baileys) 
- [@itacirgabral](https://github.com/itacirgabral) for helps
- `Ikarus#7808 (Discord)` for helps
- Translators

## License
This project is protected by `GNU General Public Licence v3.0` license.

### Disclaimer
`WhatsApp` name, its variations and the logo are registered trademarks of Facebook. We have nothing to do with the registered trademark
