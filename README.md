<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Quiz 1 - HTML5</title>
</head>
<body>

    
    <header>
        <h1>Selamat Datang</h1>
        <p>Belajar elemen semantik HTML5</p>
        <nav>
            <a href="#tentang">Tentang</a> |
            <a href="#kursus">Kursus</a> |
            <a href="#kontak">Kontak</a>
        </nav>
    </header>

   
    <section id="tentang">
        <h2>Tentang Halaman Ini</h2>
        <p>Ini merupakan section untuk menu Tentang</p>
    </section>

  
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
<footer>
    <section id="kontak">
        <h2>Hubungi Kami</h2>
        <form>
          <label>Nama: <input type="text" /></label><br />
          <label>Email: <input type="email" /></label><br />
          <label>Pesan: <textarea></textarea></label><br />
          <button type="submit">Kirim</button>
        </form>
      </section>
    
      <!DOCTYPE html><html lang="id">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Form Pendaftaran Siswa</title>
    </head>
    <body>
        <nav>
        </nav><section>
        <h2>Form Pendaftaran Siswa Baru Kampus Institut Teknologi Dan Bisnis Sabda Setia</h2>
        <form action="#" method="post">
            <label for="nama">Nama Lengkap:</label>
            <input type="text" id="nama" name="nama" required><br><br>
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required><br><br>
            <label for="tgl_lahir">Tanggal Lahir:</label>
            <input type="date" id="tgl_lahir" name="tgl_lahir"><br><br>
            <label>Jenis Kelamin:</label>
            <input type="radio" id="pria" name="jenis_kelamin" value="Pria">
            <label for="pria">Pria</label>
            <input type="radio" id="wanita" name="jenis_kelamin" value="Wanita">
            <label for="wanita">Wanita</label><br><br>
            <label for="Prodi Pilihan">Prodi Pilihan :</label>
            <input type="checkbox" id="Bisnis Digital" name="Prodi Pilihan" value="Bisnis Digital">
            <label for="Bisnis Digital">Bisnis Digital</label>
            <input type="checkbox" id="Kewirausahaan" name="Prodi Pilihan" value="Kewirausahaan">
            <label for="Kewirausahaan">Kewirausahaan</label>
            <input type="checkbox" id="Sistem & Teknologi Informasi" name="Prodi Pilihan" value="Sistem & Teknologi Informasi">
            <label for="Sistem & Teknologi Informasi">Sistem & Teknologi Informasi</label><br><br>
            <label for="alamat">Alamat:</label><br><br>
            <textarea id="alamat" name="alamat" rows="4"></textarea><br><br>
              <label for="Nama Ayah">Nama Ayah :</label><br>
              <input type="text" id="nama ayah" name="nama ayah" required<br><br>
              <label for="Nama Ibu">Nama Ibu :</label><br>
              <input type="text" id="nama ibu" name="nama ibu" required<br><br>
              <label for="Pekerjaan Iyah">Pekerjaan Ayah :</label><br>
              <input type="text" id="pekerjaan ayah" name="pekerjaan ayah" required<br><br>
              <label for="Pekerjaan Ibu">Pekerjaan Ibu :</label><br>
              <input type="text" id="pekerjaan ayah" name="pekerjaan ayah" required<br><br>
            <button type="submit">Daftar</button><br><br>
              </form>
    </section>
    </body>
    </html>
      <footer>
        <p>© 2025 oleh soniabrigitaabel </p>
      </footer>
    </body>
    </html>
</footer>
    
  
