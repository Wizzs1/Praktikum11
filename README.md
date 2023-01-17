Nama  :Wisnu Ikhwansyah Saputra

NIM   :312210305

Kelas : TI 22.A3

---

# Praktikum 11

<img width="908" alt="pip1" src="https://user-images.githubusercontent.com/110619093/212939722-66461a54-5208-40f8-a2b3-7c148d70fdcd.png">

- !pip install request
  
  digunakan untuk menginstall package requests di python. Package requests digunakan untuk melakukan HTTP request dari python.
  
  <img width="901" alt="pip2" src="https://user-images.githubusercontent.com/110619093/212940063-60e2a0b8-6b1a-4514-b915-e0277167fbc0.png">

- !pip install pandas

  digunakan untuk menginstall package pandas di python. Package pandas digunakan untuk memanipulasi data dalam bentuk tabel (dataframe) dan digunakan untuk data analysis. Fungsi dari package pandas sangat luas, seperti melakukan operasi pada data, mengimport dan mengeksport data dari berbagai format, dan lainnya
  
  <img width="918" alt="pip3" src="https://user-images.githubusercontent.com/110619093/212940413-4a8b8b1e-a238-4bd6-844a-ef34aa62fc5a.png">

- !pip install BeautifulSoup4 

  digunakan untuk menginstall package BeautifulSoup4 di python, Package BeautifulSoup4 digunakan untuk parsing dan mengelola data dari HTML atau XML.
  
<img width="919" alt="import" src="https://user-images.githubusercontent.com/110619093/212940780-2c961462-37e5-4b73-9fde-5662f94895e2.png">

- import pandas as pd

  digunakan untuk mengimport library pandas dan menyebutnya sebagai pd. Library pandas digunakan untuk memanipulasi data dalam bentuk tabel (dataframe) dan digunakan untuk data analysis.
  
- from bs4 import BeautifulSoup

  digunakan untuk mengimport class BeautifulSoup dari package BeautifulSoup4. Class BeautifulSoup digunakan untuk mengelola dan mengolah data dari HTML atau XML.

## Penjelasan
mengambil data lowongan kerja dari situs web Glints. Dengan menggunakan library Python 'requests', kodingan mengirim permintaan GET ke URL "https://glints.com/id/lowongan-kerja" yang merupakan halaman web yang berisi informasi lowongan kerja. Kemudian, dengan menggunakan library 'BeautifulSoup', kodingan menganalisis konten halaman web yang didapat dari permintaan GET tersebut dengan menggunakan parser HTML.

Selanjutnya, kodingan mencari semua elemen HTML dengan atribut 'div' dan 'id' yang sesuai, yaitu '__next'. Kemudian, dari elemen-elemen tersebut, kodingan mengekstrak informasi pekerjaan, lokasi, dan nama perusahaan dengan mencari elemen yang memiliki atribut 'class' yang sesuai. Informasi yang diambil kemudian disimpan dalam sebuah list yang sesuai.

Setelah itu, kodingan menggunakan library pandas untuk membuat dataframe dari list yang didapat dan menyimpannya dalam variabel 'df'. Kemudian kodingan mencetak dataframe tersebut, sehingga kita dapat melihat informasi lowongan kerja yang diambil dari situs web Glints.
