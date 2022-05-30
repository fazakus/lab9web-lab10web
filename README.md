# lab9web-lab10web
Nama : Faza Ardan Kusuma<br>
NIM : 312010001<br>
Kelas : TI 20 B1<br>
<hr>

## Praktikum 9

Praktikum 9 ada pada foldre <b>lab9web</b>.<br>
Disini saya akan membuat PHP modular sesuai dengan instruksi Praktikum 9.<br>

## Membuat Header
Pertama - tama saya membuat file dengan nama header.php dengan syntax berikut :<br>
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contoh Modularisasi</title>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.3.1/dist/css/bootstrap.min.css" integrity="sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T" crossorigin="anonymous">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.1.1/css/all.min.css" integrity="sha512-KfkfwYDsLkIlwQp6LFnl8zNdLGxu9YAA1QvwINks4PhcElQSvqcyVLLD9aMhXd13uQjoXtEKNosOWaZqXgel0g==" crossorigin="anonymous" referrerpolicy="no-referrer" />
</head>
<body>
    <div class="container-fluid">
        <div class="row">
            <nav class="navbar navbar-expand-lg navbar-light bg-primary font-weight-bold">
                <div class="container-fluid">
                    <a class="navbar-brand" href="#">Navbar</a>
                    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                        <span class="navbar-toggler-icon"></span>
                    </button>
                    <div class="collapse navbar-collapse" id="navbarNav">
                        <ul class="navbar-nav">
                            <li class="nav-item">
                                <a class="nav-link active" aria-current="page" href="#">Home</a>
                            </li>
                            <li class="nav-item">
                                <a class="nav-link" href="#">Tentang</a>
                            </li>
                            <li class="nav-item">
                                <a class="nav-link" href="#">Kontak</a>
                            </li>
                        </ul>
                    </div>
                </div>
            </nav>
        </div>
        <div class="row">
        </div>
        <header>
            <h1>Modularisasi Menggunakan Require</h1>
        </header>
    </div>
</body>
</html>
```

Berikut tampilannya :<br>
![header](/lab9web/Pic/navbar.png)

## Membuat Footer
Setelah membuat header, maka saya akan membuat Footernya. Saya membuat file baru dengan nama footer.php dengan syntax berikut :<br>
```
<div class="row">
        <div class="col col-sm-12">
            <div class="font-weight-bold bg-primary mb-1">
                <div class="card-body text-center">
                    Faza Ardan Kusuma - 312010001 - TI.20.B.1 <br>
                    &copy; 2022 - Universitas Pelita Bangsa
                </div>
            </div>
        </div>
    </div>
```

Tampilan dari footer tersebut sebagai berikut :<br>
![footer](/lab9web/Pic/footer.png)<br>

## Home Page
Disini saya mencoba membuat Home Page dengan mengambil header dan footer yang sudah dibuat sebelumnya dengan syntax berikut :<br>
```
<?php
require('header.php');
?>

<div class="container-fluid">
    <h2>Homepage</h2>
    <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Cumque, labore recusandae laboriosam temporibus aut maiores aperiam libero dolores facere voluptates, corrupti saepe et, provident nemo voluptas praesentium quae hic. Temporibus.</p>
</div>

<?php require('footer.php'); ?>
```
Hasilnya : <br>
![homepage](/lab9web/Pic/home.png)<br>

## About Page
Setelah home page, disini saya mencoba sekali lagi dengan membuat about page dengan syntax yang sama.
```
<?php
require('header.php');
?>

<div class="container-fluid">
    <h2>About page</h2>
    <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Distinctio quas vero eveniet non. Aut, accusantium minima quo iure possimus vel labore quas dicta. Adipisci fuga aperiam laborum eaque doloribus molestiae.</p>
</div>

<?php require('footer.php'); ?>
```

Hasilnya : <br>
![about](/lab9web/Pic/about.png)<br>

## Implementasi
Disini saya akan mengimplementasikan cara tersebut kedalam hasil praktikum sebelumnya.<br>
Di dalam halaman index, tambah dan ubah sudah saya implementasikan, berikut tampilannya :<br>

### Index
![Implementasi1](/lab9web/Pic/implementasi.png)<br>

### Tambah Data
![Implementasi2](/lab9web/Pic/implementasi2.png)<br>

### Ubah Data
![Implementasi3](/lab9web/Pic/implementasi3.png)<br>

## Praktikum 10
Untuk Praktikum 10 berada pada folder <b>lab10web</b>.