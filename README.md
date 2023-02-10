# Tugas Praktikum 13
# Pertemuan15

<b>Nama : Baihaqi Asa'ari Lubis</b>

<b>NIM : 312210720</b>

<b>Prodi : Teknik Informatika</b>

<b>Mata Kuliah : Bahasa Pemrograman</b>

# PIP

* PIP merupakan package manager untuk mengelola package dan modul pada python.
* Dengan menggunakan PIP, kita dapat menggunakan library yang tersedia bebas dari directory package library python.
* Untuk dapat menggunakan PIP, perlu diinstall terlebih dahulu, silahkan kunjungi tautan berikut untuk proses instalasinya : https://pypi.org/project/pip/

## Perintah Dasar PIP :

* pip --version -> menampilkan versi PIP yang terinstall.
* pip install nama_package -> menginstall package.
* pip uninstall nama_package -> menghapus package.
* pip list -> untuk menampilkan daftar package yang terinstall.

## Web Scraping Menggunakan Python

### Introducing

* Data Scraping adalah suatu teknik dalam mengumpulkan data dari berbagai sumber data.
* Salah satunya adalah dari website, sehingga lebih dikenal dengan Web Scraping.
* Secara Umum ada dua teknik dalam Web Scraping yaitu Manual (copy paste), dan Otomatis (dengan software/tools).

### Teknik Web Scraping :

* Menyalin data secara manual
* Menggunakan regular expression
* Parsing data HTML
* Menggunakan DOM
* Menggunakan XPath
* Menggunakan Google Sheet

### Tools yang digunakan :

* Python
* Request
* BeautifulSoup
* Google Colab

### Python

1. Kujungi tautan berikut untuk proses instalasinya : https://www.python.org/

3. Selanjutnya buka Command Promt lalu ketik python untuk melihat versi python

![gambar 2](img/2.png)

#### Request

* Requests merupakan library HTTP untuk proses mengirim dan mengambil data menggunakan protokol HTTP.
* Untuk menginstallnya menggunakan perintah pip, seperti pada gambar di bawah ini :

![gambar 3](img/3.png)

#### BeautifulSoup

* BeautifulSoup merupakan library yang digunakan untuk proses web scraping halaman HTML dan XML.
* Untuk menginstallnya menggunakan perintah pip, seperti pada gambar di bawah ini :

![gambar 4](img/4.png)

#### Pandas

* Pandas adalah library open source pada Python yang sering digunakan untuk memproses data yang meliputi pembersihan data, manipulasi data, hingga melakukan analisis data. Ketika melakukan suatu analisis, kita tidak bisa menggunakan data mentah.
* Penggunaan Pandas umumnya disingkat menjadi pd. Format penulisan saat akan memanggil library Pandas adalah import pandas as pd. Ingat untuk selalu import library yang akan digunakan terlebih dahulu.
* Untuk menginstallnya menggunakan perintah pip, seperti pada gambar di bawah ini :

![gambar 5](img/5.png)

* Untuk melihat daftar package yang telah terinstall gunakan perintah pip list

![gambar 6](img/6.png)

#### Google Colab

1. Kunjungi tautan berikut untuk membuat project baru : https://colab.research.google.com/
2. Kemudian klik File
3. Kemudian buat Notebook Baru
4. Beri nama proyeknya, untuk tampilannya seperti pada gambar di bawah ini :

![gambar 7](img/7.png)

5. Kemudian Import Library yang telah kita install sebelumnya, untuk tampilannya seperti gambar di bawah ini :

![gambar 8](img/8.png)

6. Kemudian ketik program yang akan di jalankan (Studi Kasus 1: Jadwal Sholat (URL:https://jadwalsholat.org/jadwal-sholat/monthly.php))

![gambar 9](img/9.png)

7. Untuk tampilan lengkapnya sebagai berikut :

![gambar 10](img/10.png)

8. Jika sudah benar dan berhasildi RUN maka akan menghasilkan output seperti gambar di bawah ini :

![gambar 11](img/11.png)
