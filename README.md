
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>SD Negeri Kauman 02</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            scroll-behavior: smooth;
          }
          
          body {
            font-family: sans-serif;
            line-height: 1;
          }
          
          
          /* Header styling */
          .header {
            display: flex;
            align-items: center;
            justify-content: space-between;
            background-color: #fff;
            padding: 10px 15px;
            border-top: 3px solid #BEDC74;
            position: fixed;
          }
          
          /* Logo and school name */
          .logo {
            display: flex;
            align-items: center;
          }
          
          .logo img {
            height: 50px;
            margin-right: 10px;
          }
          
          .school-info {
            display: flex;
            flex-direction: column;
          }
          
          .school-info .school-name {
            font-size: 15px;
            font-weight: bold;
            color: #333;
          }
          
          .school-info .motto {
            font-size: 12px;
            color: #777;
          }
          
          /* Navigation menu */
          .nav {
            display: flex;
            gap: 20px;
            background-color: white;
          }
          
          .nav a {
            text-decoration: none;
            color: #333;
            font-weight: bold;
          }
          
          /* Contact info and search */
          .contact-search {
            display: 1;
            align-items: center;
            gap: 15px;
          }
          
          .contact-search .contact {
            font-size: 12px;
            color: #555;
          }
          
          .contact-search .search-box {
            display: flex;
            align-items: center;
            border: 1px solid #ccc;
            border-radius: 15px;
            padding: 5px 10px;
          }
          
          .contact-search .search-box input {
            border: none;
            outline: none;
            width: 150px;
          }
          
          .contact-search .search-box button {
            background: none;
            border: none;
            cursor: pointer;
          }
            nav ul {
              
                list-style: none;
                display: flex;
                gap: 0px;
                margin-left: auto; /* Push the navbar to the right */
            
            }
            
            nav ul li {
              margin-right: 50px;
            }
            
            nav ul li a {
              color: rgb(0, 0, 0);
              text-decoration: none;
              font-weight: bold;
            }
            
            .hero {
              background: url('png_penting/lapangan.jpg') no-repeat center center/cover;
              color: white;
              height: 450px;
              display: flex;
              flex-direction: column;
              justify-content: center;
              align-items: center;
              text-align: center;
            }
            
            .hero h1 {
              font-size: 48px;
              margin-bottom: 20px;
            }
            
            .hero .btn-profil {
              background-color: #8BC34A;
              padding: 10px 20px;
              color: white;
              text-decoration: none;
              font-weight: bold;
              border-radius: 5px;
            }
            
            .content {
              display: flex;
              gap:50px; /* Menambahkan jarak antara konten utama dan sidebar */
              padding: 30px;
            }
             
            .berita {
              padding: 40px;
           }
            /* Tambahkan CSS ini pada file CSS Anda atau dalam tag <style> di file HTML Anda */
          
          .berita-terbaru-title {
            font-size: 24px;
            font-weight: bold;
            color: black; /* Warna teks judul */
            position: relative;
            padding-bottom: 10px; /* Jarak antara teks dengan garis */
            z-index: -1;
          }
            .berita h2 {
              text-align: center;
              margin-bottom: 0px;
            }
            
            .berita-item {
              display: flex;
              align-items: flex-start;
              background-color: white;
              padding: 20px;
              margin-bottom: 50px;
              box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            }
            
            .berita-item img {
              width: 300px;
              height: auto;
              margin-right: 20px;
              object-fit: cover; 
            }
            
            .berita-text {
              flex: 1;
            }
            
            .berita-text h3 {
              margin: 0;
              margin-bottom: 10px; 
              font-size: 20px;
              color: #333;
            }
            
            .berita-text p {
              margin: 0;
              color: #666;
              font-size: 16px;
              line-height: 1.6;
            }
            
            
          /* Styling untuk sidebar */
          .sidebar {
            flex: 5; /* Memberi ruang lebih kecil untuk sidebar */
            background-color: #f5f5f5; /* Warna latar opsional */
            padding: 15px;
            border-radius: 0px;
            color: black;
          }
          .sidebar-section-title {
            font-size: 18px;
            font-weight: bold;
            display: flex;
            align-items: center;
            margin-bottom: 10px;
          }
          
          /* Gaya untuk garis kecil kuning di samping judul */
          .sidebar-section-title::before {
            content: "";
            width: 5px;
            height: 20px;
            background-color: #F6E96B; /* Warna kuning */
            margin-right: 8px;
          }
            
            .sosmed-links {
              display: flex;
              flex-direction: column; 
              gap: 8px; 
            }
          
            .sosmed-links img{
              width: 30px;
              margin-left: 10px;
              margin-right: 10px;
            }
          
            .sosmed-box {
              width: 250px;
              height: 40px;
              display: flex;
              justify-content: left;
              align-items: center;
              background-color: #f0f0f0;
              border-radius: 8px;
              text-decoration: none;
              color: black;
              transition: background-color 0.3s ease;
            }
            
            .sosmed-box:hover {
              background-color: #ddd; 
            }
            
            .sosmed-box i {
              font-size: 24px;
            }
            
            .merdeka-mengajar {
              background-color: #ececec; /* Warna latar Merdeka Mengajar */
              padding: 10px;
              border-radius: 8px;
              text-align: center;
              margin-bottom: 20px;
          }
          
          .merdeka-mengajar img {
              width: 100px;
              margin-bottom: 10px;
          }
          
          /* Gaya untuk teks deskripsi */
          .sidebar-description {
              font-size: 14px;
              line-height: 1.6;
            color: black;
          }
          
            footer {
              background-color: #BEDC74;
              color: white;
              padding: 20px;
              display: flex;
              justify-content: space-between;
              font-family:Arial, Helvetica, sans-serif;
            }
            
           
          .container {
              max-width: 1200px;
              margin: 0 auto;
              padding: 2rem;
          }
          .grid {
              display: grid;
              grid-template-columns: repeat(3, 1fr);
              gap: 2rem;
          }
          h2 {
              color: white;
              font-weight: bold;
              margin-bottom: 1rem;
          }
          h3 {
              color: white;
              font-weight: bold;
              margin-bottom: 0.5rem;
          }
          p, a {
              color: white;
              margin-bottom: 0.5rem;
          }
          a {
              text-decoration: none;
          }
          .text-left {
              text-align: left;
              display: 1;
              margin-top: 20px;
              list-style-type: none;
             line-height: 1.5;
          }
          
          .sosmed-links-footer{
          display: flex;
          flex-direction: column; 
          gap: 10px;
          }
          
          .sosmed-links-footer img{
            width: 30px;
            margin-left: 10px;
            margin-right: 10px;
          }
          
          .flex {
              display: flex;
              justify-content: flex-start;
              gap: 1rem;
          }
          .text-2xl {
              font-size: 1.5rem;
          }
          .footer-location {
            text-align: center;
            font-size: 16px; /* Sesuaikan ukuran font jika diperlukan */
            padding: 10px 0;
          }
    </style>
    </head>
    <body>
        <header class="header">
           
            <div class="logo">
                <img src="png_penting/channels4_profile.jpg" alt="School Logo">
                <div class="school-info">
                    <div class="school-name">SD Negeri 02 Kauman Kota Malang</div>
                    <div class="motto">Satya Bhakti Pertiwi</div>
                </div>
            </div>
    
            
            <nav class="nav">
                <ul>
                  <li><a href="beranda.html">BERANDA</a></li>
                   <li><a href="profil.html">PROFIL</a></li>
                    <li><a href="prestasi.html">PRESTASI</a></li>
                    <li><a href="galeri.html">GALERI</a></li>
                    <li><a href="sapras.html">SAPRAS</a></li>
                    <li><a href="ekstrakurikuler.html">EKSTRAKULIKULER</a></li>
                </ul>
            </nav>
    
            
            <div class="contact-search">
                <div class="search-box">
                    <input type="text" placeholder="Search">
                    <button><img src="png_penting/Search2.png" alt="Search" width="16px"></button>
                </div>
            </div>
        </header>
    
        <section class="hero">
            <h1>SELAMAT DATANG DI <p>SD NEGERI KAUMAN 02</h1>
            <a href="profil.html" class="btn-profil">PROFIL</a>
        </section>
        <section class="content">
            <div class="berita">
               <h2 class="berita-terbaru-title">BERITA TERBARU</h2>
                <div class="berita-item">
                    <img src="png_penting/perjusami_baru.jpg" alt="Perjusami SD Negeri Kauman 02">
                    <div class="berita-text">
                       <h3>PERJUSAMI 2023-2024</h3>
                       <p>Perjusami Atau biasa disebut Perkemahan Jumat, Sabtu, Minggu yang yang dilaksanakan oleh siswa dan siswa SDN Kauman 2 Malang.Lorem ipsum dolor sit amet,consecteturadipiscing elit. sed do elusmod tempor incididunt ut labore et dolore magnaaliqua. UT enim ad minim veniam quis nostrud exercitation ullamco laboris nisiut aliquip ex ea commodo consequat.</p>
                    </div>
                </div>
                <div class="berita-item">
                    <img src="png_penting/upacaraMerdeka.png" alt="Semarak Kemerdekaan">
                    <div class="berita-text">
                       <h3>SEMARAK KEMERDEKAAN DIRGAHAYU INDONESIA YANG KE-79</h3>
                       <p>Semarakkan Hari Kemerdekaan yang ke-79 SDN Kauman 02 Malang gelar UpacaraUntuk merayakan Hari Kemerdekaan.Pada Agustus 2024........</p>
                    </div>
                </div>
                <div class="berita-item">
                    <img src="png_penting/Ramadhan.jpg" alt="Peringatan Bulan Ramadhan">
                    <div class="berita-text">
                       <h3>PERINGATAN BULAN RAMADHAN DISEMARAKKAN DENGAN KIRAB</h3>
                       <p>Hai sobat semua.Di bulan yang suci ini yaitu dibulan ramadhan,SDN Kauman 02
                          Mengadakan kirab untuk merayakan bulan suci ramadhan ...</p>
                    </div>   
                </div>
                <div class="berita-item">
                    <img src="png_penting/isramiraj.jpg" alt="Isra' Mi'raj">
                    <div class="berita-text">
                       <h3>SEMARAK PERINGATAN ISRA' MI'RAJ NABI MUHAMMAD SAW</h3>
                       <p>Selamat memperingati hari Isra Mi'raj Nabi Muhammad SAW 1445 hijriah. Mari
                          jadikan peristiwa ini menjadi momentum untuk meningkatkan keimanan dan
                          ketaqwaan kepada ALLAH SWT .</p>
                    </div>
                </div>
            </div>

            <aside class="sidebar">
                 <div class="sidebar-section">
            <div class="sidebar-section-title">Kontak</div>
                    <div class="sosmed-links">
                        <a href="https://www.instagram.com/sdnkauman2malang/?hl=id" target="_blank" class="sosmed-box">
                            <i class="fab fa-instagram"></i>
                            <img src="https://img.icons8.com/ios-filled/50/ffffff/instagram-new.png" alt="Instagram Logo">
                            @sdnkauman2malang
                        </a>
                        <a href="https://www.facebook.com/p/SDN-Kauman-2-Malang-100071041394695/?locale=id_ID" target="_blank" class="sosmed-box">
                            <i class="fab fa-facebook"></i>
                            <img src="https://img.icons8.com/ios-filled/50/ffffff/facebook-new.png" alt="Facebook Logo">
                            SDN Kauman 2
                        </a>
                        <a href="https://www.youtube.com/@sdnkauman2519" target="_blank" class="sosmed-box">
                            <i class="fab fa-youtube"></i>
                            <img src="https://img.icons8.com/ios-filled/50/ffffff/youtube-play.png" alt="YouTube Logo">
                        sdn kauman 2
                        </a>
                    </div>
                </div>
                
                <div class="sidebar-section">
                    <div class="sidebar-section-title">Merdeka Mengajar</div>
                    <div class="logo">
                        <img src="png_penting/Merdeka Mengajar (1).png" alt="logo kurikulum merdeka">
                    </div>
                    <h2>Merdeka Mengajar</h2>
                    <p>sebuah platform edukasi yang dirancang untuk mendukung guru dan kepala sekolah dalam mengimplementasikan kurikulum merdeka di Indonesia</p>
                </div>
            </aside>
        </section>
        <footer>
            <div class="footer-info">
            <div class="container">
                <div class="grid">
                    <div>
                        <h2>Location</h2>
                        <img src="png_penting/peta.png" alt="Map showing location in Malang, Indonesia" class="w-full" width="300" height="250">
                    </div>
                    <div>
                        <h2 class="text-left">Contact us</h2>
                        <div class="text-left">
                            <p>+62 (0341) 354254</p>
                            <p>kaumandua@rocketmail.com</p>
                            <h3>Follow us</h3>
                            <div class="sosmed-links-footer">
                                <a href="https://www.instagram.com/sdnkauman2malang/?hl=id" target="_blank" >
                                    <i class="fab fa-instagram"></i>
                                    <img src="https://img.icons8.com/ios-filled/50/ffffff/instagram-new.png" alt="Instagram Logo">
                                </a>
                                <a href="https://www.facebook.com/p/SDN-Kauman-2-Malang-100071041394695/?locale=id_ID" target="_blank" >
                                    <i class="fab fa-facebook"></i>
                                    <img src="https://img.icons8.com/ios-filled/50/ffffff/facebook-new.png" alt="Facebook Logo">
                                </a>
                                <a href="https://www.youtube.com/@sdnkauman2519" target="_blank" class=>
                                    <i class="fab fa-youtube"></i>
                                    <img src="https://img.icons8.com/ios-filled/50/ffffff/youtube-play.png" alt="YouTube Logo">
                                </a>
                            </div>
                        </div>
                    </div>
                    <div>
                        <h2 class="text-left">Navigation</h2>
                        <ul class="text-left">
                            <li><a href="#">Profil</a></li>
                            <li><a href="#">Prestasi</a></li>
                            <li><a href="#">Galeri</a></li>
                            <li><a href="#">Sapras</a></li>
                            <li><a href="#">Ekstrakulikuler</a></li>
                        </ul>
                    </div>
                </div>
                <div class="footer-location">
                    <h3>Location</h3>
                    <p>Kawi St No.24 D 3, Kauman, Klojen, Malang City, East Java 65119</p>
                </div>
            </div>
        </div>
        </footer>
    </body>
</html
