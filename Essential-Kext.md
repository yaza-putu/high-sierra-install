Untuk mempercepat installasi lakukan hal ini. Delete semua file kext yang tidak diperlukan, dan hanya sisakan 4 kext di gambar. Kenapa?? Jawabannya karena pada saat installasi, termasuk pada saat recovery, kext yang tidak tepat akan berpotensi menghambat proses boot. Pada beberapa kasus malah bisa membuat proses boot terhenti. Karena itu om Rehabman menyarankan hanya memakai essential kext, atau hanya kext penting saja, untuk proses boot.

<img src="https://raw.githubusercontent.com/ipang-dwi/efi-high-sierra/master/ss/es.png"/>

Fungsi kext tersebut :
- ApplePS2SmartTouchpad : mengaktifkan touchpad laptop
- FakeSMC : simulator SMC agar PC/Laptop tidak dideteksi sebagai PC/Laptop Non Apple
- Lilu : almost AIO plugin kext, ke depannya semua kext penting akan menyatu dengan Lilu
- WhatEverGreen : patch graphic card Intel/AMD/NVIDIA

> Happy hackintoshing..