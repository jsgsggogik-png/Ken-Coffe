<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Toko Vintage Ken</title>

    <style>
        * {
            box-sizing: border-box;
        }

        body {
            margin: 0;
            font-family: Georgia, serif;
            background-color: #e8d5b5;
            color: #3e2723;
        }

        /* HEADER */
        header {
            background-color: #4e342e;
            color: #f5e6c8;
            text-align: center;
            padding: 40px 20px;
            border-bottom: 6px solid #b08968;
        }

        header h1 {
            font-size: 42px;
            margin: 0;
            letter-spacing: 3px;
        }

        header p {
            font-size: 18px;
            font-style: italic;
        }

        /* MENU */
        nav {
            background-color: #6d4c41;
            text-align: center;
            padding: 15px;
        }

        nav a {
            color: #f5e6c8;
            text-decoration: none;
            margin: 0 15px;
            font-weight: bold;
        }

        nav a:hover {
            color: #d7b899;
        }

        /* PRODUK */
        .judul {
            text-align: center;
            margin-top: 40px;
        }

        .judul h2 {
            font-size: 30px;
            text-decoration: underline;
        }

        .produk-container {
            display: flex;
            justify-content: center;
            gap: 25px;
            flex-wrap: wrap;
            padding: 30px;
        }

        .produk {
            background-color: #f5e6c8;
            width: 280px;
            padding: 25px;
            text-align: center;
            border: 3px solid #8d6e63;
            border-radius: 5px;
            box-shadow: 6px 6px 0px #8d6e63;
        }

        .produk .icon {
            font-size: 55px;
        }

        .produk h3 {
            font-size: 24px;
            margin: 15px 0;
        }

        .harga {
            font-size: 22px;
            font-weight: bold;
            color: #7b3f00;
        }

        .beli {
            display: inline-block;
            margin-top: 15px;
            padding: 12px 25px;
            background-color: #5d4037;
            color: white;
            text-decoration: none;
            border-radius: 4px;
        }

        .beli:hover {
            background-color: #3e2723;
        }

        /* KONTAK */
        .kontak {
            text-align: center;
            background-color: #c2a383;
            padding: 35px 20px;
            margin-top: 30px;
        }

        .kontak h2 {
            font-size: 28px;
        }

        .telepon {
            font-size: 22px;
            font-weight: bold;
        }

        /* FOOTER */
        footer {
            background-color: #3e2723;
            color: #f5e6c8;
            text-align: center;
            padding: 20px;
        }

        /* HP */
        @media (max-width: 600px) {
            header h1 {
                font-size: 32px;
            }

            .produk {
                width: 90%;
            }
        }
    </style>
</head>

<body>

    <header>
        <h1>☕ TOKO VINTAGE KEN</h1>
        <p>Rasa Klasik, Kualitas Terbaik</p>
    </header>

    <nav>
        <a href="#produk">Produk</a>
        <a href="#kontak">Kontak</a>
    </nav>

    <section id="produk">

        <div class="judul">
            <h2>Daftar Produk</h2>
            <p>Pilihan produk terbaik untuk Anda</p>
        </div>

        <div class="produk-container">

            <!-- KOPI -->
            <div class="produk">
                <div class="icon">☕</div>
                <h3>Kopi Robusta</h3>
                <p>Kopi robusta dengan cita rasa klasik dan aroma yang nikmat.</p>
                <p class="harga">Rp40.000</p>
                <a class="beli" href="tel:085850534399">
                    Beli Sekarang
                </a>
            </div>

            <!-- KELOMANG -->
            <div class="produk">
                <div class="icon">🦀</div>
                <h3>Kelomang</h3>
                <p>Kelomang pilihan untuk menemani koleksi hewan peliharaan Anda.</p>
                <p class="harga">Rp80.000</p>
                <a class="beli" href="tel:085850534399">
                    Beli Sekarang
                </a>
            </div>

            <!-- BOTI -->
            <div class="produk">
                <div class="icon">🥖</div>
                <h3>Boti</h3>
                <p>Produk berkualitas dengan harga yang bersahabat.</p>
                <p class="harga">Rp100.000</p>
                <a class="beli" href="tel:085850534399">
                    Beli Sekarang
                </a>
            </div>

        </div>

    </section>

    <!-- KONTAK -->
    <section class="kontak" id="kontak">
        <h2>📞 Hubungi Kami</h2>
        <p>Untuk pemesanan dan informasi lebih lanjut:</p>

        <p class="telepon">
            ☎ 0858-5053-4399
        </p>
    </section>

    <!-- FOOTER -->
    <footer>
        <p>
            © 2026 Toko Vintage Kenzy putra widodo XRPL-1 (14).
        </p>
        <p>
            Dibuat dengan ❤️ untuk pecinta produk klasik.
        </p>
    </footer>

</body>
</html>
