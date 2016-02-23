# Bab 7 Membuat Palet Warna

Palet warna adalah sekumpulan jenis kelompok warna yang biasa digunakan pada Inkscape. Pada gambar berikut, palet warna ditunjukkan dalam area berwarna merah.

![palet-1](/img/palet-1.png)

Untuk mengganti palet warna lainnya, pengguna dapat mengakses tombol **<** seperti gambar berikut.

![palet-2](/img/palet-2.png)

Kemudian akan muncul jenis palet warna lainnya.

![palet-3](/img/palet-3.png)

Format berkas palet warna berekstensi .gpl. Dalam sistem operasi GNU/Linux, berkas-berkas palet ini ada dalam direktori `/usr/share/inkscape/palletes`, sementara itu dalam sistem operasi Windows ada dalam direktori `Program Files/Inkscape/share/palletes`.

![palet-4](/img/palet-4.png)

Buka salah satu berkas diatas, misal `Tango-Pallete.gpl`. Isi berkas tersebut seperti berikut.

![palet-5](/img/palet-5.png)

Isi berkas .gpl (palet warna) adalah seperti gambar diatas, yaitu menggunakan kode warna RGB. Misalnya untuk warna Butter 1 memiliki kode warna R=252, G=233, B=79. Sementara itu untuk warna Butter 2 memiliki kode warna R=237, G=212, B=0, dst. Untuk membuat berkas palet warna baru, cara paling mudah adalah dengan menyalin isi berkas diatas kemudian mengganti sesuai warna yang Anda kehendaki.

Sebagai contoh, kita akan membuat palet warna flat seperti http://flatuicolors.com/. Buat dokumen baru dengan editor teks kesayangan Anda, salin salah satu isi berkas .gpl diatas, kemudian ganti kode warna yang ada dengan warna pada http://flatuicolors.com/. Jangan lupa untuk memberi nama pada tiap warna yang dibuat.

![palet-6](/img/palet-6.png)

Untuk menyalin kode warna dibutuhkan aplikasi *color selector*, misalnya Gcolor2 pada GNU/Linux. Cara penggunaannya cukup mudah, hanya mengarahkan tombol *eyedropper* pada warna yang ingin diketahui kode warnanya. Pada gambar berikut, Gcolor2 mengambil kode warna Turquoise yang memiliki kode warna R=26, G=188, B=156. Salinlah kode warna tersebut pada teks editor yang berisi berkas palet warna yang akan kita buat.

![palet-7](/img/palet-7.png)

Setelah selesai menyalin semua warna pada http://flatuicolors.com/, isi berkas palet warna yang akan kita buat akan seperti berikut isinya.

![palet-8](/img/palet-8.png)

Simpan dokumen diatas dengan nama, misal `FlatUI.gpl`. Kemudian salin berkas tersebut dalam direktori `/usr/share/inkscape/palletes` untuk sistem operasi GNU/Linux (Anda membutuhkan akses root) dan direktori `Program Files/Inkscape/share/palletes` untuk sistem operasi Windows. Setelah selesai, buka kembali Inkscape Anda dan ganti palet dengan menekan tombol **<** seperti pada penjelsan awal. Palet baru buatan Anda akan muncul dan siap digunakan. 

![palet-9](/img/palet-9.png)

Palet ini juga dapat diunduh di https://github.com/cho2/flatui-palette.
