# File sharing obatbatuk

  </a>
  <a href="https://t.me/virtualmeresahkan1">
    <img src="https://github.com/ibrasptra791/PyrogramGenStr/blob/main/resources/madebycodex-badge.svg" width="250">
  </a><br>
  <a href="https://t.me/virtualmeresahkan0">
    &nbsp;<img src="https://img.shields.io/badge/channel%20%F0%9D%95%8F%20virtual-Channel-blue?style=flat-square&logo=telegram" width="130" height="18">&nbsp;
  </a>
  <a href="https://t.me/virtualmeresahkan">
    &nbsp;<img src="https://img.shields.io/badge/gruop%20%F0%9D%95%8F%20virtual-Group-blue?style=flat-square&logo=telegram" width="130" height="18">&nbsp;
  </a>  
</p>


Telegram Bot untuk menyimpan Posting dan Dokumen dan dapat Diakses melalui Tautan Khusus.
Saya Kira Ini Akan Bermanfaat Bagi Banyak Orang.....😇.

### Features
- Dapat Custom Full
- Message Awal:sambutan & Forcesub yang bisa dicustom.
- Lebih dari satu Posting dalam Satu Link (batch).
- Dapat di-deploy di heroku secara langsung.

### Setup

- Tambahkan bot ke Channel Database dengan semua izin admin
- Tambahkan bot ke Channel ForceSub tambahkan bot sebagai ADMIN
- Tambahkan bot ke Group ForceSub tambahkan bot sebagai ADMIN

##
### Installation
#### Deploy on Heroku
[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/jandijanda/kon2)</br>

#### Deploy in your VPS
````bash
git clone https://github.com/jandijanda/kon2
cd FileSharing-Restu
pip3 install -r requirements.txt
# <Create config.py appropriately>
python3 main.py
````

### Admin Commands

```
/start - mulai bot atau dapatkan postingan

/batch - buat link untuk lebih dari satu posting

/genlink - buat link untuk satu posting

/users - lihat statistik pengguna bot

/broadcast - menyiarkan/broadcast pesan apa pun ke pengguna bot

/ping - untuk mengecek bot
```

### Variables

* `API_HASH` Dapatkan API HASH di web my.telegram.org.
* `API_ID` Dapatkan APP ID di web my.telegram.org
* `TG_BOT_TOKEN` Dapatkan dari t.me/BotFather
* `OWNER` Masukan Username Telegram untuk Owner BOT
* `OWNER_ID` Masukan User ID Telegram untuk Owner BOT
* `CHANNEL_ID` Masukan ID Channel Untuk [Channel Database] contoh:- -100xxxxxxxx
* `ADMINS` Masukan User ID untuk mendapatkan hak Admin BOT [Hanya dapat membuat link]
* `START_MESSAGE` Opsional: Pesan /start memulai awalan ke bot, Gunakan parsemode HTML 
* `FORCE_SUB_MESSAGE` Opsional: Pesan Paksa Subscribe bot, Gunakan Format parsemode HTML
* `FORCE_SUB_CHANNEL` Masukan ID dari Channel Untuk Wajib Subscribenya
* `FORCE_SUB_GROUP` Masukan ID dari Group Untuk Wajib Subscribenya

### Extra Variables

* `CUSTOM_CAPTION` letakkan teks teks Kustom Anda jika Anda ingin Mengatur Teks Kustom, Anda dapat menggunakan HTML dan <a href='https://github.com/jandijanda/kon2/blob/main/README.md#custom_caption'>fillings</a> untuk pemformatan (hanya untuk dokumen)
* `DISABLE_CHANNEL_BUTTON` Masukan True untuk Nonaktifkan Tombol Berbagi Saluran, Default jika False

### Fillings
#### START_MESSAGE | FORCE_SUB_MESSAGE

* `{first}` - User first name
* `{last}` - User last name
* `{id}` - User ID
* `{mention}` - Mention the user
* `{username}` - Username

#### CUSTOM_CAPTION

* `{filename}` - file name of the Document
* `{previouscaption}` - Original Caption


## Support   
Bergabunglah di [Group Telegram ](https://www.telegram.dog/virtualmeresahkan0) Untuk Dukungan/Bantuan dan untuk info Update bot.   
   
Laporkan Bug, Berikan Permintaan Fitur Di sana.
### Credits

- Thanks To Dan For His Awsome [Libary](https://github.com/pyrogram/pyrogram)
- Thanks To [CodeXBotz](https://github.com/CodeXBotz/File-Sharing-Bot)
- Our Support Group Members

### Licence
[![GNU GPLv3 Image](https://www.gnu.org/graphics/gplv3-127x51.png)](http://www.gnu.org/licenses/gpl-3.0.en.html)  

[FILE-SHARING-BOT](https://github.com/jandijanda/kon2) is Free Software: You can use, study share and improve it at your
will. Specifically you can redistribute and/or modify it under the terms of the
[GNU General Public License](https://www.gnu.org/licenses/gpl.html) as
published by the Free Software Foundationither version 3 of the License, or
(at your option) any later version. 

##

   **Berikan Bintang Repo ini jika Anda menyukainya ⭐⭐⭐⭐⭐**

