<!DOCTYPE html>
<html>
  <head>
    <title>Izumi No Nihongo</title>
    <link link rel="icon" href="Gambar/bahan web gambar.png">
    </head>
    <head>
      <style>
        body{
            text-align: center;
            }

        li{
            text-align: center;
            font-size: 20px;
            color: white;
            background-color: #10da86;   
            width: 100%;         
            font-family: 'Arial Black';
            list-style: none;
            text-decoration: none;
        }

        footer{
            background-color:  #10da86;
            color: white;
            text-align: center;
            font-size: 20px;
        width: 100%;
        height: 60px;
        line-height: 60px; 
        }
        
        .bar {
            width: 30px;
            height: 3px;
            background-color: #000;
            margin: 6px 0;
        }

        .dropdown-container {
            position: relative;
            display: inline-block;
        }

        .dropdown-content {
    display: none;
    position: absolute;
    background-color: white;
    min-width: 160px;
    box-shadow: 0px 8px 16px 0px rgba(0, 0, 0, 0.2);
    z-index: 1;
    top: 420px; /* Sesuaikan nilai ini */
    height: 100%;
    left: 0;
    text-align: left;
}


        /* Tambahkan padding dan background putih pada li */
        .dropdown-content a {
            color: black;
            padding: 12px 16px;
            text-decoration: none;
            display: block;
            background-color: white;
        }

        /* Tambahkan properti display: block; pada ul */
        ul {
            list-style-type: none;
            margin: 0;
            padding: 0;
            display: block; /* Ubah display menjadi block */
            align-items: center;
            width: 100%;
        }
    </style>


    </style>
<img
src="Gambar/bahan web gambar.png"
alt="Header Image"
width="100%"
height="350"
/>
<body1>
    <div class="Dropdown" style="display: flex; justify-content: space-between; align-items: center; padding: 0 20px; background-color: #10da86; height: 60px; width: 100%;">
    <!-- Tombol ikon align -->
    <div class="menu-icon" >
      <div class="bar"></div>
      <div class="bar"></div>
      <div class="bar"></div>
    </div>

     <!-- Dropdown content -->
     <div class="dropdown-content" id="dropdown-content">
      <a href="Ujian JLPT.html" style="font-family: 'Arial Black', sans-serif; font-size: 25px; font-weight: bold; color: black; text-decoration: none;">Ujian JLPT</a>
      <hr>
      <a href="Materi Dasar.html" style="font-family: 'Arial Black', sans-serif; font-size: 25px; font-weight: bold; color: black; text-decoration: none;">Materi Dasar</a>
      <hr>
      <a href="Login.html" style="font-family: 'Arial Black', sans-serif; font-size: 25px; font-weight: bold; color: black; text-decoration: none;">Login</a>
    </div>

    <!-- Navigasi -->
    <ul style="list-style-type: none; margin: 0; padding: 0; display: flex; align-items: center; width: 100%;">
      <li style="padding: 0 10px;"><a href="Kursus online" style="color: white; text-decoration: none;">Kursus online</a></li>
      <li style="padding: 0 10px;"><a href="About Us.html" style="color: white; text-decoration: none;">About Us</a></li>
      <li style="padding: 0 10px;"><a href="Contact.html" style="color: white; text-decoration: none;">Contact</a></li>
    </ul>
  </div>

  <script>
    // Menambahkan event listener untuk mengontrol perilaku ikon menu saat diklik
    document.addEventListener('DOMContentLoaded', function () {
        // Mengambil referensi ke ikon menu dan konten dropdown
        var menuIcon = document.querySelector('.menu-icon');
        var dropdownContent = document.getElementById('dropdown-content');

        // Menambahkan event listener untuk mengubah status tampilan konten dropdown saat ikon menu diklik
        menuIcon.addEventListener('click', function () {
            // Jika konten dropdown sedang ditampilkan, sembunyikan. Jika tidak, tampilkan.
            if (dropdownContent.style.display === 'block') {
                dropdownContent.style.display = 'none';
            } else {
                dropdownContent.style.display = 'block';
            }
        });
    });
</script>

  </script>
  

</body1>



<body>
<p style="font-size: 23px;"><b>🎌 Selamat Datang di Izumi no Nihongo!</b></p>
<p style="font-size: 14px;">Di sini, kami menyambut Anda dengan tulus ke dunia belajar Bahasa Jepang yang menarik dan penuh inspirasi.<br>
<br>
Izumi no Nihongo adalah tempat di mana Anda bisa mengeksplorasi keindahan Bahasa Jepang,
<br>
menemukan kegembiraan dalam setiap kata, dan meraih kemahiran baru dengan percaya diri.</p>
<p style="font-size: 14px;">Dengan pengalaman belajar yang disesuaikan, materi yang kaya, dan dukungan dari tim kami.
  <br>
kami berkomitmen untuk membantu Anda mencapai tujuan Bahasa Jepang Anda bersama-sama.
<br>
mari kita mulai perjalanan yang menarik dan memperkaya diri dengan kekayaan budaya dan bahasa Jepang.</p>
<p style="font-size: 14px;">Terima kasih telah memilih Izumi no Nihongo sebagai mitra belajar Anda.
<br>
Selamat belajar, dan selamat menemukan keindahan Bahasa Jepang bersama kami!</p>
</body>
<p style="color: rgb(156, 221, 237); font-size: 16px; text-align: center; font-family: 'Arial Black'; "> IZUMI NO NIHONGO COLABORATION WITH BENKYOU SHITAI 1 </p>

<footer>
<p>&copy; 2024 Izumi no Nihongo. All rights reserved.</p>
</footer>
</html>
