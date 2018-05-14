## Description
(a) Data Scraping
Data scraping  adalah teknik yang digunakan untuk mengambil isi sebuah halaman secara spesifik, misalnya link gambar, isi berita atau sejenisnya. Pada tugas ini akan mengambil data dari halaman web

(b) topik yang dipilih serta alasan pemilihannya
Topik yang ingin dibahas adalah Proyek Strategis Nasional Indonesia
Alasannya : Era Jokowi saat ini sangat genjar terhadap perumbuhan ekonomi yang didukung dari pelaksanaan proyek yang ada
Sehingga proyek ini menarik untuk di analisis untuk melihat kinerja dari setiap proyek dan persebaran dari setiap proyek dan menjadi 
tolak ukur apakah proyek ini sesuai dengan yang diharapkan atau tidak.

(c) tahapan-tahapan yang dilakukan dalam mengerjakan tugas Data Scraping beserta tools yang digunakan
Tahapannya : 
Dalam pengerjaan tugas 1 ini , saya menggunakan bahasa pemrograman python dan editornya menggunakan notepad++ serta OS yang saya gunakan adalah windows :)
Saya melakukan download dan install terhadap python ini dan melakukan environment untuk menjalankan python
Saya baru pertama menggunakan python sehingga saya perlu pembelajaran / tutuorial melewati youtube dan stackoverflow, Saya langsung mencari webscrapping dengan python sekaligus belajar menggunakan python
Dalam melakukan convert file csv ke Json saya menggunakan converter https://www.csvjson.com/csv2json sehingga file csv langsung tergerarte otomatis ke Json. Sekian tools yang saya gunakan . TOOLS UTAMA : LAPTOP DAN INTERNET CONNECTION :)

(d) penjelasan mengenai library lain yang dieksplorasi
Menggunakan library urllib agar dapat melakukan request ke web server
BeautifulSoup untuk mengambil data html dan XML files
Pandas adalah sebuah paket library yang dapat menyediakan struktur data dengan cepat , fleksibel

(f)  ide pemanfaatan data dan/atau informasi baru yang bisa di diperoleh dari data hasil scraping
Informasi baru yang dapat diperoleh :
- Dapat mengetahui jumlah proyek yang ada
- Dapat mengetahui persebaran setiap proyek yang ada
- Dapat mengetahui persebaran sektor proyek yang ada
- Dapat mengetahui nilai proyek yang ada 
- Dapat melakukan analisis terhadap suatu daerah yang harusnya dapat berpotensi adanya proyek
- Dapat melakukan analisis apakah proyek prioritas itu memang harus di dahulukan
- Pada proyek prioritas dapa menjadi benchmark terhadapa proyek lain dan dapat dilihat apakah proyek tersebut nilai investasi nya sesuai atau tidak
- Menganalisis sektor proyek dari setiap daerah tersebut apa sudah cocok dengan potensi di daerah tersebut
- Dan masih banyak lagi 
(: 
:)


## Specification

1. Lakukan data scraping dari sebuah laman web untuk memeroleh data atau informasi tertentu TANPA MENGGUNAKAN API.

2. Daftarkan judul topik yang akan dijadikan bahan data scraping pada spreadsheet berikut: http://bit.ly/TopikDataScraping. Usahakan agar tidak ada peserta dengan topik yang sama. Akses edit ke spreadsheet akan ditutup tanggal 10 Mei 2018 pukul 20.00 WIB. Tugas sudah dapat mulai dikerjakan sejak tanggal 5 Mei 2018.

3. Dalam mengerjakan tugas 1, calon warga basdat terlebih dahulu melakukan fork project github pada link berikut: https://github.com/wargabasdat/Seleksi-2018/Tugas1. Sebelum batas waktu pengumpulan berakhir, calon warga basdat harus sudah melakukan pull request dengan nama TUGAS_SELEKSI_1_[NIM]

4. Pada repository tersebut, calon warga basdat harus mengumpulkan file script dan json hasil data scraping. Repository terdiri dari folder src dan data dimana folder src berisi file script/kode yang WELL DOCUMENTED dan CLEAN CODE sedangkan folder data berisi file json hasil scraper.

5. Peserta juga diminta untuk membuat Makefile sesuai template yang disediakan, sehingga program dengan mudah di-build, di-run, dan di-clean.

6. Deadline pengumpulan tugas adalah 15 Mei 2018 Pukul 23.59.

7. Tugas 1 akan didemokan oleh masing-masing calon warga basdat pada tanggal 16 Mei 2016.

8. Demo tugas mencakup keseluruhan proses data scraping hingga memeroleh data sesuai dengan yang dikumpulkan pada Tugas 1.

9. Hasil data scraping ini nantinya akan digunakan sebagai bahan tugas analisis dan visualisasi data.

10. Sebagai referensi untuk mengenal data scraping, asisten menyediakan dokumen "Short Guidance To Data Scraping" yang dapat diakses pada link berikut: bit.ly/DataScrapingGuidance

11. Tambahkan juga gitignore pada file atau folder yang tidak perlu di upload, NB : BINARY TIDAK DIUPLOAD

12. JSON harus dinormalisasi dan harus di-preprocessing. Preprocessing contohnya : Cleaning, Parsing, Transformation, dan lain-lain.

## How to use
#A. Daftar Proyek
1. Buka folder src 
2. Buka Folder DaftarProyek
3. Klik DaftarProyek.py
4. Membuka editors kemudian copy DaftarProyek ke editor
5. Save as di direktori bebas
6. Membuka cmd 
7. cd direktory
8. Run --> py DaftarProyek.py

########*ALTERNATIF*##########
1. Buka folder src
2. Buka file dengan editor
3. Menggunakan python shell
4. Press F5
5. File di run 
##############################

##Datanya
1. Format data csv
2. Membuka website https://www.csvjson.com/csv2json ### :)
3. DaftarProyek.csv convert ke Json
4. Copy File Json ke editor
5. Edit file apabila ada yang unidentified character maka di hapus dengan ctr+f kemudian karakter tersebut di replace dengan character lain
6. Save as ke folder data - DaftarProyek
:)

#B. Proyek Prioritas
1. Buka folder src
2. Buka folder ProyekPrioritas
3. Pilih folder proyek yang ada
4. Membuka file dengan editor
5. Save as di direktori bebas
6. Membuka cmd
7. cd direktori
8. Run --> py fileproyek.py

########*ALTERNATIF*##########
1. Buka folder src
2. Buka file dengan editor
3. Menggunakan python shell
4. Press F5
5. File di run 
##############################

##Datanya
1. Format data csv
2. Membuka website https://www.csvjson.com/csv2json ### :)
3. DaftarProyek.csv convert ke Json
4. Copy File Json ke editor
5. Edit file apabila ada yang unidentified character maka di hapus dengan ctr+f kemudian karakter tersebut di replace dengan character lain
6. Save as ke folder data - ProyekPrioritas :)

## JSON Structure
Pada DaftarProyek menggunakan : An Object
Pada ProyekPrioritas menggunakan : An Array

## Screenshot program 
![alt text](https://github.com/aldomatthew/Seleksi-2018/blob/master/Tugas1/screenshots/DaftarProyek/DP_1.png)
![alt text](https://github.com/aldomatthew/Seleksi-2018/blob/master/Tugas1/screenshots/DaftarProyek/DP_2.png)
![alt text](https://github.com/aldomatthew/Seleksi-2018/blob/master/Tugas1/screenshots/DaftarProyek/DP_3.png)
![alt text](https://github.com/aldomatthew/Seleksi-2018/blob/master/Tugas1/screenshots/DaftarProyek/DP_4.png)
![alt text](https://github.com/aldomatthew/Seleksi-2018/blob/master/Tugas1/screenshots/DaftarProyek/DP_5.png)
![alt text](https://github.com/aldomatthew/Seleksi-2018/blob/master/Tugas1/screenshots/DaftarProyek/DP_6.png)
![alt text](https://github.com/aldomatthew/Seleksi-2018/blob/master/Tugas1/screenshots/DaftarProyek/DP_7.png)
## Reference (Library used, etc)
Pandas
BeutifulSoup 4
urllib
csv

- Author:Ronaldo Matthew R (18216007) / STI
