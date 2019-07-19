Untuk bisa masuk dan menjalankan installer MacOS, diperlukan setting pada Clover yang sesuai dengan device yang dipakai. Fungsinya agar installer MacOS mengenali device baik itu PC/Laptop yang dipakai, beserta semua atributnya. Seperti device ID nya, BIOS, versi, dan lain-lain. Saat ini tidak perlu susah untuk membuatnya. Tinggal ambil saja salah satu yang sesuai dengan device kita di repo om Rehabman :

[https://github.com/RehabMan/OS-X-Clover-Laptop-Config](https://github.com/RehabMan/OS-X-Clover-Laptop-Config)

Misal pada Asus X45C yang memakai processor Intel Core i3-2350M atau Sandy Bridge yang dikenal dengan generasi ke-2. Maka memakai config.plist untuk Intel HD 3000.

Untuk mempercepat proses masuk ke installer MacOS dan mempermudah melakukan tracing bila terjadi error atau trouble, maka cari baris ini pada config.plist yang telah di download dari repo om Rehabman :  

<string>kext-dev-mode=1 dart=0 slide=0 nv_disable=1 -cdfon -igfxnohdmi</string>

Dan ganti baris tersebut dengan :  

<string>kext-dev-mode=1 dart=0 slide=0 nv_disable=1 -cdfon -igfxnohdmi -f -v -no_compat_check</string>

Fungsinya untuk : 
* -v atau verbose, untuk menampilkan log installasi, warning atau error message akan ditampilkan di sini.
* -f atau force, untuk melewati semua opsi yang memerlukan respon, misal pertanyaan untuk Y/N, dll.
* -no_compat_check, untuk menghindari pengecekan kompatibilitas yang tidak diperlukan.

Copas saja file config.plist untuk me-replace config.plist di dalam folder EFI/Clover/.
