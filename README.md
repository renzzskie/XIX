1.1 JUDUL

XIX

1.2 LATAR BELAKANG 

Project merupakan salah satu bagian akhir dari keseluruhan rangkaian kegiatan 
praktikum Algoritma dan Pemrograman Dasar tahun 2025. Pelaksanaan praktikum harus 
diselesaikan dengan membuat suatu projek aplikasi dengan mengimplementasikan semua 
modul yang dimulai dari modul I sampai dengan modul VI menggunakan bahasa 
pemrograman C++. Perencanaan project pembuatan aplikasi dibutuhkan beberapa macam 
ide yang mudah dipahami dan mudah untuk disusun bentuk dari kodenya menggunakan 
bahasa pemrograman C++ yang mencakup semua aspek dalam modul I sampai dengan 
modul VI.
Ide XIX yaitu ide yang disepakati bersama untuk dijadikan sebuah aplikasi 
setelah ditinjau beberapa pertimbangan yang nantinya bisa dipastikan bahwa aplikasi sistem 
manajemen tersebut mencakup semua materi dari modul I sampai dengan modul VI 
berdasarkan praktikum Algoritma dan Pemrograman Dasar yang telah dilaksanakan. 
Game XIX adalah sebuah game atau program yang diciptakan dan dikembangkan 
menggunakan bahasa pemrogramana C++. XIX ini memiliki banyak fitur di 
dalamanya yang sehingga bertujuan untuk mengimplementasikan atau mengaplikasikan 
materi-materi yang telah diperoleh dari modul I sampai dengan modul VI pada praktikum 
Algoritma dan Pemrograman Dasar tahun 2025. 

1.3 DESKRIPSI PROGRAM 

Program XIX ini merupakan game yang dirancang untuk menyediakan dua jenis 
permainan interaktif, yaitu Tebak Angka (BOOM) dan GTRA (Kuis Teka-Teki), serta fitur 
administrasi untuk mengelola soal kuis pada game GTRA. Saat memulai program, pengguna 
dihadapkan pada menu utama dengan tiga opsi yaitu BOOM, GTRA, dan EXIT. 
Jika memilih BOOM, pengguna akan diarahkkan ke menu permainan tebak angka yang 
menawarkan 2 mode, yaitu single player atau multiplayer. Pada mode single player, 
pengguna memasukkan nama dan menebak angka acak antara 1 sampai 100. Tebakan yang 
benar akan mempersempit rentang, sedangkan tebakan yang mengenai angka boom 
menyebabkan kekalahan. Pada mode multiplayer, 2-5 pemain bergiliran menebak angka 
dengan aturan serupa, dan pemain yang menebak angka boom kalah. Setelah permainan 
selesai, pengguna dapat memilih untuk bermain lagi atau kembali ke menu sebelumnya. 
Jika memilih GTRA, pengguna akan diarahkan ke menu permainan kuis teka-teki yang 
terdapat 3 opsi main, menu admin dan keluar. Jika memilih main pengguna diminta 
memasukkan nama dan memilih tingkat kesulitan kuis yaitu easy, normal, dan hard. Permain 
menjawab dengan aturan “Petunjuk Cara Pengerjaan!!! Jika jawaban adalah satu kata tulis 
awalan dengan huruf kapital, Jika lebih gunakan Kapital Each Word, Jika singkatan gunakan 
CAPSLOCK dan kamu memiliki 3 kesempatan salah, kamu bebas memilih level soal, poin 
tiap level berbeda”. Permainan berakhir jika semua soal dijawab atau nyawa habis, dan 
pengguna dapat memilih untuk bermain lagi atau kembali ke menu utama. 
Untuk bagian menu admin, pengguna dapat mengakses melalui username dan password 
yang sudah ditetapkan, menu admin mencakup opsi untuk menambah soal baru (easy, 
normal atau hard), melihat riwayat pemain yang menampilkan nama, skor, dan nyawa 
pemain, atau kembali ke menu utama. Admin dapat mengelola soal dengan memasukkan 
pertanyaan, jawaban, dan poin. Setiap pengguna dapat memilih opsi keluar untuk 
mengakhiri program sepenuhnya. 

1.4 ALGORITMA 

1. Mulai Program. 
2. Program akan menampilkan menu awal yaitu pemilihan BOOM, GTRA dan exit. 
3. Jika user memilih exit maka program selesai. 
4. Jika user memilih BOOM maka program akan menampilkan menu BOOM yaitu 
singleplayer, multiplayer, dan kembali. 
5. Jika user memilih singleplayer maka system akan secara acak memilih angka kemudian  
user akan diminta memasukkan nama dan bermain sendiri, user akan menebak angka 
dari 1 sampai 100, akan di update setelah memilih, jika berhasil menebak angka itu user 
akan kalah, tetapi jika user berhasil menghindari angka itu dan mendekati angka itu 
maka user menang. 
6. Jika user memilih multiplayer maka sistem akan secara acak memilih angka kemudian  
user akan diminta memasukkan berapa orang yang akan main antara 2 sampai 5 orang 
kemudian memasukkan nama orang orangnya, user akan menebak angka dari 1 sampai 
100, akan di update setelah memilih, jika salah satu berhasil menebak angka itu user 
akan kalah, tetapi jika user berhasil menghindari angka itu dan mendekati angka itu 
maka user menang. 
7. Jika user memilih kembali maka akan kembali ke menu awal. 
8. Jika user memilih GTRA maka program akan menampilkan menu GTRA yaitu mulai 
main, menu admin, dan kembali. 
9. Jika user memilih mulai main maka akan disuruh untuk memasukkan nama terlebih 
dahulu, jika nama sudah digunakan maka disuruh untuk menambahkan berupa karakter 
atau tanda. Kemudian menampilkan 3 level soal yaitu easy, medium dan hard, untuk 
setiap level memiliki poin yang berbeda dan setiap user memiliki 3 nyawa, setelah 
memilih level user diminta menjawab semua soal yang terdapat pada level tersebut, jika 
salah menjawab akan mengurangi nyawa 1 dan setelah selesai menjawab semua soal 
ditanya apakah mau main lagi atau tidak, jika iya maka kembali ke menu 3 level.  
10. Jika user memilih menu admin, akan diminta memasukkan username dan password, jika 
benar akan dibawa ke dalam menu admin yang terdapat opsi untuk menambah soal baru 
(easy, medium atau hard), melihat riwayat pemain, dan kembali untuk ke menu utama. 
Jika memilih menambah soal baru akan diminta memasukkan pertanyaan, jawaban, dan 
poin, jika memilih melihat riwayat akan ditampilkan nama, skor, dan nyawa dari 
pemain.
