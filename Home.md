[![FIRSTPLATO](https://www.firstplato.com/img/logo.png)](https://www.firstplato.com)

Welcome to the efi-high-sierra wiki! Craft a perfect Hackintosh for daily used.

![My Asus X45C Hackintosh](https://raw.githubusercontent.com/ipang-dwi/efi-high-sierra/master/ss/0.png)

> masih dalam proses penulisan yak, jadi bila ada yang belum lengkap atau sempurna, harap dimaklumi.. meskipun untuk membangun Hackintosh PC/Laptop, namun akan disarankan memakai tools dan kext yang free dan opensource..

Repo ini dibuat untuk memudahkan bagi yang ingin mempelajari dan mencoba menginstall Mac OS High Sierra pada PC/Laptop non Apple. Bisa juga diterapkan pada versi sebelum, maupun sesudahnya, semua langkah-langkahnya sama. Hanya perlu penyesuaian kextnya saja.

**Pra Install**
* Pastikan PC/Laptop kamu memenuhi [Minimum Requirements](https://github.com/ipang-dwi/efi-high-sierra/wiki/Minimum-Requirements). Pada repo ini, dipergunakan media laptop Asus X45C.
* Download installer MacOS yang sudah include clover bootloader di [sini](https://files.zhih.me/macOS/). Dan buat bootable USB dengan flashdisk minimal 8GB, dengan menggunakan [Transmac](https://www.acutesystems.com/scrtm.htm). Caranya baca [di sini](https://github.com/ipang-dwi/efi-high-sierra/wiki/Cara-create-bootable-installer-MacOS-dengan-Transmac).
* Replace isi dari partisi EFI dengan file release EFI dari repo ini. Untuk laptop/PC lain langsung skip saja langkah selanjutnya.
* Untuk mempercepat proses installasi <a href="https://github.com/ipang-dwi/efi-high-sierra/wiki/Essential-Kext" target="blank">lakukan ini</a>.
* Disable secure boot pada BIOS/UEFI, dan boot dari USB.

**Install**
* Lakukan proses installasi pada PC/Laptop.
* Karena versi yang dipakai ini adalah versi 10.13.6, maka secara otomatis format yang dipakai untuk partisinya adalah APFS. Meski pada saat installasi, kamu memilih jenis partisi HFS+, tetap akan diformat APFS oleh installernya. 
* Saat installasi pastikan untuk tidak terkoneksi dengan internet, dan tidak perlu setup jaringan, baik LAN maupun WAN.
* Saat create user baru, masukkan password 1 karakter saja. Fungsinya agar saat butuh installasi kext atau app, atau akses lain yang memerlukan password, tidak ribet ketik panjang-panjang. Tapi setelah setup selesai, bisa diganti password sepanjang-panjangnya.
* Jika ada message warning atau error, atau terhenti di tengah jalan ketika installasi, silahkan post masalahnya di grup FB Forum Hackintosh Indonesia.

**Pasca Install**
* Setelah proses installasi selesai, saatnya menginstall semua kext yang diperlukan.
* Install DPCI Manager, untuk mengetahui semua detail setiap hardware yang kamu pakai.
* Silahkan install satu-satu kext yang dibutuhkan sesuai dengan vendor dan type hardware yang kamu pakai, search kextnya di Google, atau bisa juga tanya di grup FB Forum Hackintosh Indonesia.
* Kext apa saja yang dipakai di Asus X45C bisa dilihat [di sini](https://github.com/ipang-dwi/efi-high-sierra/wiki/Kext-Asus-X45C---High-Sierra).
* Untuk mengaktifkan Wifi Atheros AR9485 pada Asus X45C <a href="https://github.com/ipang-dwi/efi-high-sierra/wiki/Mengaktifkan-Wifi-Atheros-AR9485-di-MacOS-High-Sierra-10.13.6---FullSpeed" target="blank">lakukan ini</a>.
* Untuk mengaktifkan Backlight atau setting brightness [lakukan ini](https://github.com/ipang-dwi/efi-high-sierra/wiki/Mengaktifkan-Backlight-atau-setting-brightness).
* Terbiasa memakai Windows atau Linux, <a href="https://github.com/ipang-dwi/efi-high-sierra/wiki/Nyamankan-diri-di-MacOS" target="blank">lakukan ini</a> agar kalian nyaman di MacOS.

[![FIRSTPLATO](https://www.firstplato.com/img/logo.png)](https://www.firstplato.com)

> Happy Hackintoshing... :)