# 1. Membuat instaler dan install mac os high sierra
high-sierra-install
Tutorial install high sierra by bang ipang

follow link ini untuk melihat tutorial lengkapnya..
https://github.com/ipang-dwi/efi-high-sierra/wiki

EFI file ada di repo ini

note : set nvidia enable (pc ini memakai vga nvidia 710)
# 2. Setelah Berhasil install mac, selanjutnya install clover di hdd/ssd, kebetulan pc ini bootnya legacy(bios legacy)
<p>configurasi clovernya seperti di bawah ini :</p>
<p>saya memakai clover versi 4895</p>
<img src="https://res.cloudinary.com/dk0053zbe/image/upload/v1579847837/git%20hub%20install%20high%20sieera/Screen_Shot_2020-01-24_at_14.32.44_hwtx90.png"/>
<img src="https://res.cloudinary.com/dk0053zbe/image/upload/v1579849039/git%20hub%20install%20high%20sieera/Screen_Shot_2020-01-24_at_14.56.33_ounhvs.png"/>
<img src="https://res.cloudinary.com/dk0053zbe/image/upload/v1579847836/git%20hub%20install%20high%20sieera/Screen_Shot_2020-01-24_at_14.33.06_nn17a0.png"/>
<img src="https://res.cloudinary.com/dk0053zbe/image/upload/v1579847837/git%20hub%20install%20high%20sieera/Screen_Shot_2020-01-24_at_14.33.12_yil42w.png"/>
<img src="https://res.cloudinary.com/dk0053zbe/image/upload/v1579847837/git%20hub%20install%20high%20sieera/Screen_Shot_2020-01-24_at_14.33.48_jtxqq1.png"/>
di tahap ini install clover berhasil dipasang di bios legacy, selanjutnya mereplace efi yg ada di installer flashdisk.
<p>caranya moun efi hdd tempat anda menginstall mac osnya, lalu hapus semua isi file Efinya dan paste file EFInya, file EFI ada di repo ini</p>
preview config clover untuk komputer ini
<p>Set audio nya, ini memakai ALC 662, dan support di layout id = 12, dan di propertienya set 12</p>
<img src="https://res.cloudinary.com/dk0053zbe/image/upload/v1579849644/git%20hub%20install%20high%20sieera/Screen_Shot_2020-01-24_at_15.06.15_ar451a.png"/>
<img src="https://res.cloudinary.com/dk0053zbe/image/upload/v1579849781/git%20hub%20install%20high%20sieera/Screen_Shot_2020-01-24_at_15.08.51_ck3klp.png"/>
<img src="https://res.cloudinary.com/dk0053zbe/image/upload/v1579849783/git%20hub%20install%20high%20sieera/Screen_Shot_2020-01-24_at_15.08.06_o7f06u.png"/>
