# Lab6Web
## Tugas Pemrograman web - Pertemuan Ke 7

<hr>

Nama    : Rudi Hartono

NIM     : 312010027

Kelas   : TI.20.B1


*Pada kesempatan kali ini (Perkuliahan Pemrograman Web Pertemuan 7), mahasiswa ditugaskan untuk membuat sebuah layout seperti pada Pertemuan 5 lalu, tetapi membuat dengan menggunakan Twitter Bootstrap. Dimana Website tersebut bisa menjadi responsive atau mengikuti semua device yang dipakai oleh user.*

## Membuat Header dan Hero

<hr>

*Pertama-tama kita akan membuat halaman baru dengan nama "index.html" di mana dalam sebuah file tersebut sudah dimasukan file Bootstrap & Javascript yang ada.*

*Source code yang saya masukan pada file "index.html" seperti berikut ini:*

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>

    <link rel="stylesheet" href="bootstrap.css">
    <script type="text/javascript" src="bootstrap.bundle.js"></script>
</head>
<body>

    <div class="container" style="box-shadow: 0 0 1em #cccccc">
        <div class="row">
            <header>
                <h1>Layout Sederhana</h1>
            </header>
        </div>
        <div class="row">
            <nav class="navbar navbar-collapse navbar-expand navbar-dark bg-primary">
                <div class="container-fluid">
                    <div class="collapse navbar-collapse">
                        <ul class="navbar-nav" style="font-size: 14px; font-weight: bold;">
                            <li class="nav-item" style="padding-right: 15px;">
                                <a class="nav-link active" href="#">Home</a>
                            </li>
                            <li class="nav-item" style="padding-right: 15px;">
                                <a class="nav-item">
                                    <a href="#" class="nav-link">Artikel</a>
                                </a>
                            </li>
                            <li class="nav-item" style="padding-right: 15px;">
                                <a class="nav-item">
                                    <a href="#" class="nav-link">About</a>
                                </a>
                            </li>
                            <li class="nav-item" style="padding-right: 15px;">
                                <a class="nav-item">
                                    <a href="#" class="nav-link">Contact</a>
                                </a>
                            </li>
                        </ul>
                    </div>
                </div>
            </nav>
        </div>
        <div class="row">
            <section id="hero">
                <h1>Hello World !</h1>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Veniam pariatur necessitatibus excepturi cupiditate aliquam sapiente inventore eius ducimus alias. In quod sint libero quis, ipsam qui similique quos, dolorum exercitationem quae veritatis. Aspernatur officiis unde minus itaque maiores iure, omnis voluptate veritatis dolor, exercitationem adipisci voluptatum, repellat recusandae ea placeat!</p>
                <a class="btn btn-primary" type="button"><b>Learn More >></b></a>
            </section>
        </div>
    </div>
    
</body>
</html>