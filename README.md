## Profil
| # | Biodata |
| -------- | --- |
| **Nama** | Alingga Reandito |
| **NIM** | 312010276 |
| **Kelas** | TI.20.A.2 |
| **Mata Kuliah** | Pemrograman Web |

## PERTEMUAN 11

## LAB 9 WEB

Dipertemuan kali ini kita akan mempelajari **php modular** 

## LANGKAH - LANGKAH PRAKTIKUM

## 1). MENJALANKAN XAMPP SERVER
![img](img/xamp_server.png)

**PENJELASAN**

Menjalankan xampp server localhost

## 2).BUAT FOLDER BARU DENGAN NAMA **lab9_php_modular** 
![img](img/php_modular.png)

**PENJELASAN**

Kemudian jalanlan pada localhost server dengan mengakses URL: http://localhost/Lab9Web/lab9_php_modular/
![img](img/local_server.png)

## 3). BUAT FILE BARU DENGAN NAMA **header.php**
![img](img/header.png)

**PENJELASAN**

Buat header seperti contoh di atas
 
 **code header**
 ```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Contoh Modularisasi</title>
    <link href="style.css" rel="stylesheet" type="text/stylesheet" media="screen" />
</head>
<body>
    <div class="container">
        <header>
            <h1>Modularisasi Menggunakan Require</h1>
        </header>
        <nav>
            <a href="home.php">Home</a>
            <a href="about.php">Tentang</a>
            <a href="kontak.php">Kontak</a>
        </nav>
 ```

## 4). BUAT FILE BARU DENGAN NAMA **footer.php**
![img](img/footer.png)

**PENJELASAN**

Buat **footer.php** dan code nya

**code footer**
```html
<footer>
            <p>&copy; 2022, Informatika, Universitas Pelita Bangsa</p>
        </footer>
    </div>
</body>
</html>
```

## 5). BUAT FILE BARU DENGAN NAMA **home.php**
![img](img/home.png)

**PENJELASAN**

Buat **home.php** dan code nya

**code home**
```php
<?php require('header.php'); ?>

<div class="content">
    <h2>Ini Halaman Home</h2>
    <p>Ini adalah bagian content dari halaman.</p>
</div>

<?php require('footer.php'); ?>
```

## 6). BUAT FILE BARU DENGAN NAMA **about.php**
![img](img/about.png)

**PENJELASAN**

Buat **about.php** dan code nya

**code about**
```php
<?php require('header.php'); ?>

<div class="content">
    <h2>Ini Halaman About</h2>
    <p>Ini adalah bagian content dari halaman.</p>
</div>

<?php require('footer.php'); ?>
```

## 7). TAMPILAN DIBROWSER NYA

* Tampilan **home** page pada browser yang menggunakan modular ***header*** dan ***footer***
![img](img/tampilan_home.png)

* Tampilan **about** page pada browser yang menggunakan modular ***header*** dan ***footer***
![img](img/tampilan_about.png)

--------------------------------------------------------------------------------

## PERTANYAAN DAN TUGAS

* Implementasikan konsep modularisasi pada kode program **praktikum 8** tentang database, sehingga setiap halamannya template tampilan yang sama.

## 1) BUAT FOLDER BARU **lab9_tugas**

**PENJELASAN**

Buat file baru atau salin file pada **praktikum 8** lalu implementasikan dengan menambahkan modular **header** dan **footer**

## HASIL

* Tampilan pada bagian **Home** 
![img](img/page_home.png)


* Tampilan pada bagian **Tambah Barang**
![img](img/page_tmbah_barang.png)


* Tampilan pada bagian **Ubah Barang**
![img](img/page_ubah_barang.png)

