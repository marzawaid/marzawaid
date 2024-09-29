<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Biografi Riyana Malik</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>

    <!-- Header / Navbar -->
    <header>
        <h1>Riyana Malik</h1>
        <nav>
            <ul>
                <li><a href="#about">Tentang Saya</a></li>
                <li><a href="#business">Usaha Saya</a></li>
                <li><a href="#gallery">Galeri Karya</a></li>
                <li><a href="#contact">Hubungi Saya</a></li>
            </ul>
        </nav>
    </header>

    <!-- Tentang Saya Section -->
    <section id="about" class="section">
        <h2>Tentang Saya</h2>
        <p>Halo! Nama saya Riyana Malik. Saya adalah seorang pengusaha yang sangat mencintai dunia kuliner. Usaha saya berfokus pada makanan instan dengan kualitas yang tetap terjaga. Saya memulai ini dari hobi memasak dan sekarang, usaha ini sudah berkembang luas. Saya percaya bahwa makanan enak bisa dinikmati kapan saja dan di mana saja, tanpa mengurangi cita rasa.</p>
    </section>

    <!-- Usaha Saya Section -->
    <section id="business" class="section">
        <h2>Usaha Saya</h2>
        <p>Usaha saya berfokus pada produksi bakso instan dan bumbu kuah berkualitas. Kami menawarkan solusi praktis untuk para pencinta makanan yang ingin menikmati kelezatan bakso di rumah tanpa harus repot.</p>
        <ul>
            <li><strong>Nama Usaha:</strong> Bakso Instan Lezat</li>
            <li><strong>Jenis Produk:</strong> Bakso instan, bumbu kuah per porsi</li>
            <li><strong>Keunggulan Usaha:</strong> Kualitas terjamin, bahan alami, mudah disiapkan</li>
        </ul>
    </section>

    <!-- Galeri Karya Section -->
    <section id="gallery" class="section">
        <h2>Galeri Karya</h2>
        <div class="gallery">
            <img src="gambar1.jpg" alt="Produk bakso instan" class="gallery-img">
            <img src="gambar2.jpg" alt="Bumbu kuah bakso" class="gallery-img">
            <img src="gambar3.jpg" alt="Proses produksi bakso" class="gallery-img">
        </div>
    </section>

    <!-- Hubungi Saya Section -->
    <section id="contact" class="section">
        <h2>Hubungi Saya</h2>
        <form action="submit_form.php" method="post">
            <label for="name">Nama:</label>
            <input type="text" id="name" name="name" required>

            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>

            <label for="message">Pesan:</label>
            <textarea id="message" name="message" required></textarea>

            <button type="submit">Kirim</button>
        </form>
    </section>

    <!-- Footer -->
    <footer>
        <p>&copy; 2024 Riyana Malik. All Rights Reserved.</p>
        <p>Follow me on 
            <a href="https://www.instagram.com">Instagram</a>, 
            <a href="https://www.facebook.com">Facebook</a>, 
            <a href="https://www.twitter.com">Twitter</a>
        </p>
    </footer>

</body>
</html>
