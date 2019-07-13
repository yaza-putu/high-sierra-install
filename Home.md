![My Asus X45C Hackintosh](https://raw.githubusercontent.com/ipang-dwi/efi-high-sierra/master/ss/0.png)
Welcome to the efi-high-sierra wiki! Craft a perfect Hackintosh for daily used.
> masih dalam proses penulisan yak, jadi bila ada yang belum lengkap atau sempurna, harap dimaklumi.. meskipun untuk membangun Hackintosh PC/Laptop, namun akan disarankan memakai tools dan kext yang free dan opensource..

Repo ini dibuat untuk memudahkan bagi yang ingin mempelajari dan mencoba menginstall Mac OS High Sierra pada PC atau Laptop non Apple. BIsa juga diterapkan pada versi sebelum, maupun sesudahnya, semua langkah-langkahnya sama. Hanya perlu penyesuaian kextnya saja.

* Pastikan PC/Laptop kamu memenuhi [Minimum Requirements](https://github.com/ipang-dwi/efi-high-sierra/wiki/Minimum-Requirements). Pada repo ini, dipergunakan media laptop Asus X45C.
* Download installer MacOS yang sudah include clover bootloader di [sini](https://files.zhih.me/macOS/). Dan buat bootable USB dengan flashdisk minimal 8GB, dengan menggunakan [Transmac](https://www.acutesystems.com/scrtm.htm). Caranya baca [di sini](https://github.com/ipang-dwi/efi-high-sierra/wiki/Cara-create-bootable-installer-MacOS-dengan-Transmac).
* Replace isi dari partisi EFI dengan file release EFI dari repo ini. Untuk laptop/PC lain langsung skip aja langkah selanjutnya.
* Untuk mempercepat proses installasi <a href="https://github.com/ipang-dwi/efi-high-sierra/wiki/Essential-Kext" target="blank">lakukan ini</a>.
* Disable secure boot pada BIOS/UEFI, dan boot dari USB.
* Lakukan proses installasi pada PC/Laptop.
* Saat installasi pastikan untuk tidak terkoneksi dengan internet, dan tidak perlu setup jaringan, baik LAN maupun WAN.
* Saat create user baru, masukkan password 1 karakter saja. Fungsinya agar saat butuh installasi kext atau app, atau akses lain yang memerlukan password, tidak ribet ketik panjang-panjang. Tapi setelah setup selesai, bisa diganti password sepanjang-panjangnya.
* Install DPCI Manager, silahkan install satu-satu kext yang dibutuhkan sesuai dengan vendor dan type hardware yang kamu pakai, serach kextnya di Google, atau bisa tanya di grup FB Forum Hackintosh Indonesia.
* Untuk mengaktifkan Wifi Atheros AR9485 <a href="https://github.com/ipang-dwi/efi-high-sierra/wiki/Mengaktifkan-Wifi-Atheros-AR9485-di-MacOS-High-Sierra-10.13.6---FullSpeed" target="blank">lakukan ini</a>.
* Terbiasa memakai Windows atau Linux, <a href="https://github.com/ipang-dwi/efi-high-sierra/wiki/Nyamankan-diri-di-MacOS" target="blank">lakukan ini</a> agar kalian nyaman di MacOS.

> Happy Hackintoshing... :)