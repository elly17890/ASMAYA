<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <title>Asrama Yamo</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<!-- NAVBAR -->
<header>
    <h1>Asrama Yamo</h1>
    <nav>
        <a href="#">Beranda</a>
        <a href="#penghuni">Penghuni</a>
        <a href="#daftar">Daftar</a>
    </nav>
</header>

<!-- HERO -->
<section class="hero">
    <h2>Selamat Datang di Asrama Yamo</h2>
    <p>Nyaman • Aman • Modern</p>
    <button onclick="scrollToForm()">Daftar Sekarang</button>
</section>

<!-- DATA PENGHUNI -->
<section id="penghuni" class="container">
    <h2>Data Penghuni</h2>
    <table id="tabelPenghuni">
        <tr>
            <th>Nama</th>
            <th>Kamar</th>
        </tr>
        <tr>
            <td>Eliyon</td>
            <td>A1</td>
        </tr>
    </table>
</section>

<!-- FORM -->
<section id="daftar" class="container">
    <h2>Pendaftaran Asrama</h2>
    <form id="formDaftar">
        <input type="text" id="nama" placeholder="Masukkan Nama" required>
        <input type="text" id="kamar" placeholder="Nomor Kamar" required>
        <button type="submit">Daftar</button>
    </form>
</section>

<footer>
    <p>© 2026 Asrama Yamo</p>
</footer>

<script src="script.js"></script>
</body>
</html>
