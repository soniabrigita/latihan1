<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Quiz 1 - HTML5</title>
</head>
<body>

    <!-- Header -->
    <header>
        <h1>Selamat Datang</h1>
        <p>Belajar elemen semantik HTML5</p>
        <nav>
            <a href="#tentang">Tentang</a> |
            <a href="#kursus">Kursus</a> |
            <a href="#kontak">Kontak</a>
        </nav>
    </header>

    <!-- Section Tentang -->
    <section id="tentang">
        <h2>Tentang Halaman Ini</h2>
        <p>Ini merupakan section untuk menu Tentang</p>
    </section>

    <!-- Section Daftar Kursus -->
    <section id="kursus">
        <h2>Daftar Kursus</h2>
        <table border="1">
            <tr>
                <th>No</th>
                <th>Nama Kursus</th>
                <th>Durasi</th>
            </tr>
            <tr>
                <td>1</td>
                <td>Dasar HTML & CSS</td>
                <td>4 Minggu</td>
            </tr>
            <tr>
                <td>2</td>
                <td>JavaScript Fundamental</td>
                <td>4 Minggu</td>
            </tr>
        </table>
    </section>

    <!-- Section Kontak -->
    <section id="kontak">
        <h2>Hubungi Kami</h2>
        <form>
            <label for="nama">Nama:</label>
            <input type="text" id="nama" name="nama"><br><br>
            
            <label for="email">Email:</label>
            <input type="email" id="email" name="email"><br><br>
            
            <label for="pesan">Pesan:</label><br>
            <textarea id="pesan" name="pesan" rows="4" cols="30"></textarea><br><br>
            
            <button type="submit">Kirim</button>
        </form>
    </section>

    <!-- Footer -->
    <footer>
        <p>&copy; 2025 oleh ……..</p>
    </footer>

</body>
</html>
