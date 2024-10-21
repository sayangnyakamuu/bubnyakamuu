# bubnyakamuu
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Untukmu, Deatul Fadila</title>
    <link rel="stylesheet" href="s.css">
</head>
<body>
    <header>
        <h1>Untukmu, Deatul Fadila</h1>
        <p>Karena kamu selalu istimewa di hatiku</p>
    </header>

    <section id="intro">
        <h2>Pesan Spesial untuk Kamu</h2>
        <p>Setiap hari yang kujalani bersamamu adalah hari yang paling istimewa. Terima kasih telah hadir di hidupku. Kamu adalah alasanku tersenyum setiap hari.</p>
    </section>

    <section id="galeri">
        <h2>Kenangan Kita</h2>
        <p>Berikut beberapa momen indah kita:</p>
        <img src="c:1.jpg" alt="Momen kamuu abiss tabraan" class="gambar"><p>Momen ini pass kita jauhh yangg pengen sama kamuu akuu</p>
        <img src="c:2.jpg" alt="Momen ini pass kita jauhh yangg pengen sama kamuu akuu" class="gambar"><p>Momen kamuu abiss tabraan</p>
    </section>

    <section id="surprise">
        <h2>Kejutan Kecil untukmu</h2>
        <p>Klik tombol di bawah ini untuk melihat kejutan kecil dari aku buat kamu!</p>
        <button onclick="tampilkanKejutan()">Lihat Kejutan</button>
        <div id="kejutan" style="display:none;">
            <p>Terima kasih sudah menjadi bagian terbaik dalam hidupku. Aku nggak sabar menunggu hari-hari penuh kebahagiaan denganmu. Kamu adalah segalanya bagiku. <strong>Love you, sayangg bububb 💖</strong></p>
        </div>
    </section>

    <footer>
        <p>&copy; tertanda Setyo.</p>
    </footer>

    <script>
        function tampilkanKejutan() {
            document.getElementById('kejutan').style.display = 'block';
        }
    </script>
</body>
</html>
