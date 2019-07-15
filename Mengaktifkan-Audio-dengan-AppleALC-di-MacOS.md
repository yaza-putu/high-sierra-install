Setelah menginstall MacOS, untuk mendapatkan performa Audio sesuai dengan driver bawaan Apple, perlu dipergunakan Kext AppleALC. Kext ini akan menjembatani dan menjadikan Laptop/PC bisa dideteksi dan mempergunakan driver audio bawaan Apple dengan sempurna.

* Buka App Clover Configurator dan mount partisi EFI
* Load config.plist dari partisi EFI
* Pilih section Devices
* Pada Audio, centang pilihan ResetHDA dan di kolom inject, ketikkan angka layout-id yang mau dipakai. Layout-id yang didukung oleh AppleALC selengkapnya bisa dilihat [di sini](https://github.com/acidanthera/AppleALC/wiki/Supported-codecs). Contoh layout-id yang dipakai pada Asus X45C.

![AppleALC Asus X45C](https://raw.githubusercontent.com/ipang-dwi/efi-high-sierra/master/ss/audio.png)

* Jangn lupa pada bagian bawahnya, pilih properties, pilih devices, cari di Properties Key yang ada label layout-id. Hapus tanda # di depannya. Dan Properties Value, isi dengan layout-id yang dipakai.