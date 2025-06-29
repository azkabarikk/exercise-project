<!DOCTYPE html>
<html>
<head>
    <title>Contoh Layout dengan Table</title>
</head>
<body>

<!-- Section 1: Menu -->
<table border="1" width="100%">
    <tr>
        <td><a href="#section2">Header</a></td>
        <td><a href="#section3">Biodata</a></td>
        <td><a href="#section4">Portfolio</a></td>
    </tr>
</table>

<!-- Section 2: Judul di kiri dan gambar -->
<table border="1" width="100%" id="section2">
    <tr>
        <td width="50%" valign="middle">
            <h2>Selamat Datang di Web Saya</h2>
            <p>Ini  adalah contoh header dengan dua kolom. Kolom kiri berisi teks seperti ini</p>
            <button>Pelajari Lebih Lanjut</button>
        </td>
        <td width="50%">
            <img src="https://via.placeholder.com/300" alt="Gambar Contoh" width="600px" height="400px">
        </td>
    </tr>
</table>

<!-- Section 3: Biodata dengan 6 box -->
<table border="1" width="100%" id="section3" cellpadding="10" cellspacing="0">
     <tr align="center">
        <ul align="center">
          <h2>About Me</h2>
          <p>A brief introduction about my self!</p>
        </ul>
     </tr>  
     <tr align="center">
        <td><b>Full Name</b></td>
        <td><b>Education</b></td>
        <td><b>Pekerjaan</b></td>
    </tr>
    <tr align="center">
        <td><b>Contact</b></td>
        <td><b>Hobi</b></td>
        <td><b>Alamat</b></td>
    </tr>
</table>

<!-- Section 4: Portfolio -->
<table border="1" width="100%" id="section4" cellpadding="10" cellspacing="0">
       <tr align="center">
        <ul align="center">
          <h2>Portfolio</h2>
        </ul>
     </tr>  
    <tr>
        <td><b>Project 1</b><br>Deskripsi project 1</td>
        <td><b>Project 2</b><br>Deskripsi project 2</td>
    </tr>
    <tr>
        <td><b>Project 3</b><br>Deskripsi project 3</td>
        <td><b>Project 4</b><br>Deskripsi project 4</td>
    </tr>
</table>

</body>
</html>
