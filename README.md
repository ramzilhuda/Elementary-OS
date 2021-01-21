# Tentang Elementary-OS

Elementary OS merupakan sebuah distro linux berbasiskan Ubuntu. Distro ini menggunakan desktop manager-nya sendiri yang bernama Pantheon. Rilis versi stabil pertama dari elementary OS adalah "Jupiter", diluncurkan pada Maret 2011 dan berbasis Ubuntu 10.10. Sejak Oktober 2012, versi ini tidak lagi didukung dan berarti juga tidak lagi bisa diunduh di situs resmi elementary OS. 
Elementary OS tersedia dengan bebas biaya (tersedia pilihan untuk menyumbang kepada tim pengembang) melalui pengunduhan berkas iso, BitTorrent maupun Live CD/USB yang mengizinkan pengguna untuk dapat mencobanya tanpa perlu melakukan pemasangan pada harddisk. Installer-nya adalah Ubiquity yang merupakan installer standar untuk Ubuntu dan kebanyakan Sistem Operasi turunannya.

Panduan : 
1. Lisensi
https://github.com/ramzilhuda/Elementary-OS/blob/main/LICENSE
2. Kontribusi
https://github.com/ramzilhuda/Elementary-OS/blob/main/CONTRIBUTING.md
3. kode etik
https://github.com/ramzilhuda/Elementary-OS/blob/main/kode-etik.md

# Sistem Rekomendasi 
1. Prosesor Intel i3 or compatible dual-core 64-bit processor
2. 4 GB (RAM)
3. Hardisk 15 GB untuk penyimpanan
4. Akses Internet
5 VGA dengan grafik 1024×768 display

#Kelebihan Elemntary OS
Secara performa dirasa jauh lebih cepat dibanding dengan Ubuntu. Hal itu mungkin disebabkan oleh jenis DE (Desktop Environment) yang digunakan dimana Ubuntu menggunakan Unity sedangkan eOS menggunakan Pantheon yang memang lebih ringan. 
Selain itu dapat dilihat juga dari system requirement-nya, dimana jika dibandingkan dengan Ubuntu yang recommended Ram-nya 2GB. Dari segi customize-nya juga sudah mumpuni dimana kita dapat mengutak-atik sesuai keinginan kita.
Uniknya di eOS ini ada fitur notifikasi dimana jika semisal kita menjalankan perintah di Terminal maka jika sudah selesai perintah itu dieksekusi akan muncul notofikasi di pojok kanan atas. Fitur ini belum tersedia di beberapa distro Linux termasuk Ubuntu.

#Kekurangan Elemntary OS
Selain kelebihan dan keunikan diatas beberapa kekurangan masih bisa ditemukan di eOS. Memang eOS adalah distro yang tergolong ringan dan cepat namun bukan yang tercepat karena masih ada beberapa distro yang lebih ringan dibandingkan dengan eOS misal saja Lubuntu yang juga berbasis Ubuntu yang diperuntukkan untuk perangkat-perangkat lama. Selain itu masih sering ditemukan bug berupa freeze yang kadang terjadi tetapi biasanya ini terjadi saat seseorang salah atau memaksakan suatu customize pada eOS.

Elementary OS ini juga termasuk distro yang jarang sekali merilis versi terbarunya dan juga dukungan atau forum yang membahas eOS juga tidak sebanyak Ubuntu.

# Panduan Instalasi Elementary-OS
1. Download ISO Elementary-OS sesuai dengan sistem operasi yang kamu gunakan di https://elementary.io/ bagi kamu yang ingin berdonasi silahkan isi sesuai dengan keinginan teman - teman bagi yang ingin downloa secara free silahkan isi donasi dengan $0
![elementaryos2](https://user-images.githubusercontent.com/60292040/105368015-a66a3d80-5c33-11eb-968d-9ca2115f7af7.jpg)
2. Bagi teman - teman yang menginstal ISO elementary-OS melalui flashdisk silahkan download aplikasi rufus di : https://rufus.ie/
![Screenshot_20](https://user-images.githubusercontent.com/60292040/105372882-a882cb00-5c38-11eb-925f-5301d3388599.jpg)
3. Cara membuat ISO elementary-OS menggunakan flashdisk menggunakan aplikasi rufus dapat melihat video ini : https://www.youtube.com/watch?v=n7hCNSgncMI
4. Boot bios first boot ke flashdisk yang sudah kita buatkan ISO Elementary-OS.
![Screenshot_3](https://user-images.githubusercontent.com/60292040/105370866-9c960980-5c36-11eb-85b9-7d319e156415.jpg)
5. Selanjutkan kita akan diberikan pilihan untuk jenis keyboard. Untuk langkah ini, bisa langsung di-next saja karena Indonesia sudah terbiasa menggunakan kibor standar English US
![Screenshot_4](https://user-images.githubusercontent.com/60292040/105371566-4f666780-5c37-11eb-8d9c-289480ce54b8.jpg)
6. Di sini ada dua opsi, keduanya tidak wajib dicentang. Anda bebas apakah ingin mencentang keduanya atau tidak. Akan jika anda memiliki koneksi internet yang cepat dan kuota, saya sarankan keduanya dicentang
![Screenshot_5](https://user-images.githubusercontent.com/60292040/105371397-2ba32180-5c37-11eb-90f1-c787732f518b.jpg)
7. Ada dua tipe instalasi. Yang pertama Erase disk and Install Ubuntu. Ini akan membersihkan semua harddisk anda. Membuat ulang partisi tabel. Lalu akan diisi dengan fresh instalasi Ubuntu.
![Screenshot_6](https://user-images.githubusercontent.com/60292040/105371401-2cd44e80-5c37-11eb-8733-e4d02dde7303.jpg)
8. Pilihan yang kedua adalah: Something else. Ini dipilih ketika kita ingin mengatur partisi hard drive kita sendiri. Akan tetapi kita sendiri juga yang akan bertanggung jawab jika ada hal-hal yang tidak diiginkan semisal semua partisi hard-drive terhapus.
![Screenshot_7](https://user-images.githubusercontent.com/60292040/105371403-2d6ce500-5c37-11eb-84df-965e7adca8c0.jpg)
9. Di dalam contoh kali ini, saya menggunakan hard-drive virtual berukuran 2.2TB.
Buat Tabel Partisi Baru Jika Belum Ada
Di dalam contoh ini, hard-drive benar-benar kosongan seperti baru. Sehingga tidak ada tabel partisinya dan kita harus membuatnya terlebih dahulu.
![Screenshot_8](https://user-images.githubusercontent.com/60292040/105371406-2e057b80-5c37-11eb-8200-a7d0ebeb1355.jpg)
10. Klik Continue untuk mengonfirmasi pembuatan tabel partisi baru.
![Screenshot_9](https://user-images.githubusercontent.com/60292040/105371410-2e9e1200-5c37-11eb-8691-793e29aa34c4.jpg)
11. Setelah tabel partisi baru terbuat, anda akan melihat hasilnya kira-kira seperti ini.
![Screenshot_10](https://user-images.githubusercontent.com/60292040/105371413-2f36a880-5c37-11eb-91fb-a194461ee6c4.jpg)
12. Di sini saya mencontohkan membuat partisi utama sebesar 500GB.
![Screenshot_11](https://user-images.githubusercontent.com/60292040/105371415-2fcf3f00-5c37-11eb-8824-041766f5bbdb.jpg)
13. Setelah partisi sistem selesai dibuat. Ulangi lagi langkah tersebut untuk membuat partisi swap. Ubah bagian use as sesuai dengan kebutuhan.
Berikut penampakan setelah 3 partisi selesai saya tambahkan
![Screenshot_12](https://user-images.githubusercontent.com/60292040/105371417-2fcf3f00-5c37-11eb-816d-69cbfa19b08a.jpg)
14. Setelah selesai membuat partisi. Klik tombol Install Now. Lalu anda akan dimintai konfirmasi apakah benar-benar yakin untuk melanjutkan dan paham konsekuensinya. Langsung klik Continue saja.
![Screenshot_13](https://user-images.githubusercontent.com/60292040/105371419-3067d580-5c37-11eb-8d18-b25521206963.jpg)
![Screenshot_14](https://user-images.githubusercontent.com/60292040/105371420-31006c00-5c37-11eb-9562-828ca924cc44.jpg)
15. Jika anda terhubung dengan Internet, harusnya sistem akan mendeteksi secara otomatis timezone anda. Akan tetapi jika ternyata ada kesalahan, anda bisa mengaturnya secara manual.
![Screenshot_15](https://user-images.githubusercontent.com/60292040/105371422-31990280-5c37-11eb-9d1b-df859f2abd02.jpg)
16. Langkah selanjutnya adalah melengkapi data-data. Mulai dari data Nama PC, Nama pengguna, password. Dan sebagainya. Setelah selesai silakan klik tombol Continue.
17. Setelahnya anda akan disuguhkan jendela yang menunjukkan progress instalasi. Anda bisa mulai menyeduh kopi anda dan menunggu.
![Screenshot_16](https://user-images.githubusercontent.com/60292040/105371429-32319900-5c37-11eb-8d52-f71542c0c86c.jpg)
18. Setelah beberapa menit, anda akan diminta untuk mereboot mesin. Ini artinya proses instalasi telah selesai dengan sukses.
![Screenshot_17](https://user-images.githubusercontent.com/60292040/105371432-32ca2f80-5c37-11eb-88a9-285316472de4.jpg)
19. Agar PC tidak kembali booting melalui media installer Elementary OS, anda harus melepaskannya terlebih dahulu. Jika menggunakan USB maka dicabut, dan jika menggunakan DVD maka di-eject.
![Screenshot_18](https://user-images.githubusercontent.com/60292040/105371435-32ca2f80-5c37-11eb-9f9b-ee800cb6e91d.jpg)
![Screenshot_19](https://user-images.githubusercontent.com/60292040/105371437-3362c600-5c37-11eb-802d-b627db5384c1.jpg)

#


