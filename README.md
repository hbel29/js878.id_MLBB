<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>JS878.ID - Joki Mobile Legends Bang Bang</title>
    <link rel="website icon" type="image/png" href="path/to/your/image.png"> <!-- Update the path to the correct image -->
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Roboto', sans-serif;
            margin: 0;
            padding: 0;
            background: linear-gradient(to bottom right, #add8e6, #00008b);
            color: #fff;
            animation: fadeIn 2s ease-in;
            overflow-x: hidden;
        }
        header {
            background-color: rgba(28, 28, 28, 0.9);
            padding: 20px;
            text-align: center;
            position: sticky;
            top: 0;
            z-index: 1000;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.7);
            animation: slideInDown 1s ease-in-out;
            flex-wrap: wrap;
        }
        nav ul {
            list-style: none;
            padding: 0;
            margin: 0;
            display: flex;
            justify-content: center;
            gap: 20px;
        }
        nav ul li a {
            color: #74c7b9;
            text-decoration: none;
            font-weight: bold;
            text-transform: uppercase;
            transition: color 0.3s, transform 0.3s;
            flex-wrap: wrap;
        }
        nav ul li a:hover {
            color: #08f5b9;
            transform: scale(1.1);
        }
        .container {
            max-width: 1200px;
            margin: 20px auto;
            padding: 20px;
            background-color: rgba(28, 28, 28, 0.85);
            box-shadow: 0 4px 20px rgba(0, 0, 0, 0.8);
            border-radius: 15px;
            animation: fadeIn 2s ease-in-out;
        }
        section {
            margin-bottom: 40px;
            animation: fadeInUp 1.5s ease-in-out;
        }
        h2 {
            color: #1de9b6;
            margin-bottom: 20px;
            animation: fadeInRight 1.2s ease-in-out;
        }
        ul {
            list-style: none;
            padding: 0;
        }
        ul li {
            background: linear-gradient(to right, #2c2c2c, #1c1c1c);
            margin: 10px 0;
            padding: 15px;
            border-radius: 10px;
            box-shadow: 0 2px 10px #3956fa80;
            transition: transform 0.3s, background-color 0.3s;
            flex-wrap: wrap;
        }
        ul li:hover {
            transform: scale(1.03);
            background-color: #1de9b6;
            color: #8aeed5;
        }
        .form-group {
            margin-bottom: 20px;
        }
        .form-group label {
            display: block;
            margin-bottom: 10px;
            font-weight: bold;
        }
        .form-group input, .form-group select, .form-group textarea {
            width: 100%;
            padding: 12px;
            border: 1px solid #333;
            border-radius: 5px;
            background-color: #2c2c2c;
            color: #fff;
            transition: border 0.3s, background-color 0.3s;
        }
        .form-group input:focus, .form-group select:focus, .form-group textarea:focus {
            border-color: #1de9b6;
            background-color: #1c1c1c;
        }
        .form-group button {
            background-color: #1de9b6;
            color: #000;
            border: none;
            padding: 12px 25px;
            cursor: pointer;
            font-weight: bold;
            transition: background-color 0.3s, transform 0.3s;
            border-radius: 5px;
        }
        .form-group button:hover {
            background-color: #00bfa5;
            transform: scale(1.1);
        }
        .cards {
            display: flex;
            gap: 20px;
            flex-wrap: wrap;
            justify-content: space-between;
        }
        .card {
            background: linear-gradient(to bottom, #2c2c2c, #1c1c1c);
            flex: 1 1 calc(33.333% - 20px);
            padding: 20px;
            border-radius: 15px;
            text-align: center;
            transition: transform 0.3s, box-shadow 0.3s;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.6);
        }
        .card:hover {
            transform: translateY(-10px);
            box-shadow: 0 6px 20px rgba(0, 0, 0, 0.8);
        }
        footer {
            background-color: rgba(28, 28, 28, 0.9);
            color: #fff;
            text-align: center;
            padding: 15px 0;
            box-shadow: 0 -2px 10px rgba(0, 0, 0, 0.7);
            animation: fadeInUp 1.5s ease-in-out;
        }
        .hidden {
            display: none;
        }
        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }
        @keyframes slideInDown {
            from { transform: translateY(-100%); opacity: 0; }
            to { transform: translateY(0); opacity: 1; }
        }
        @keyframes fadeInUp {
            from { transform: translateY(20px); opacity: 0; }
            to { transform: translateY(0); opacity: 1; }
        }
        @keyframes fadeInRight {
            from { transform: translateX(-20px); opacity: 0; }
            to { transform: translateX(0); opacity: 1; }
        }
    </style>
</head>
<body>

<header>
    <h1>JS878.ID - Joki Mobile Legends Bang Bang</h1>
    <nav>
        <ul>
            <li><a href="#home">Beranda</a></li>
            <li><a href="#services">Layanan</a></li>
            <li><a href="#account-data">Data Akun</a></li>
            <li><a href="#prices">Paket & Pembayaran</a></li>
            <li><a href="#advantages">Keunggulan</a></li>
            <li><a href="#testimonials">Testimoni</a></li>
            <li><a href="#contact">Kontak</a></li>
        </ul>
    </nav>
</header>

<div class="container">
    <section id="home">
        <h2>Selamat datang di JS878.ID!</h2>
        <p>Kami menyediakan layanan joki Mobile Legends Bang Bang terbaik untuk membantu Anda mencapai rank tertinggi dengan cepat dan aman. Dengan pengalaman yang luas dan pemain profesional, kami menjamin kepuasan Anda!</p>
    </section>

    <section id="services">
        <h2>Layanan Kami</h2>
        <div class="cards">
            <div class="card">
                <h3>Peningkatan Rank</h3>
                <p>Joki aman dari Warrior hingga Mythic.</p>
            </div>
            <div class="card">
                <h3>Pelatihan Pro</h3>
                <p>Joki dengan penjoki profesional.</p>
            </div>
        </div>
    </section>

    <section id="account-data">
        <h2>Data Akun</h2>
        <form>
            <div class="form-group">
                <label for="login-via">Login Via</label>
                <select id="login-via" name="login-via" required>
                    <option value="">Pilih Login Via</option>
                    <option value="moonton">Moonton (Rekomendasi)</option>
                    <option value="vk">VK (Rekomendasi)</option>
                    <option value="tiktok">Tiktok</option>
                    <option value="facebook">Facebook</option>
                    <option value="google-play">Google Play</option>
                </select>
            </div>
            <div class="form-group">
                <label for="user-id">User  ID & Nickname</label>
                <input type="text" id="user-id" name="user-id" required>
            </div>
            <div class="form-group">
                <label for="email">Email/No.HP/Moonton ID</label>
                <input type="text" id="email" name="email" required>
            </div>
            <div class="form-group">
                <label for="password">Password</label>
                <input type="password" id="password" name="password" required>
            </div>
            <div class="form-group">
                <label for="notes">Catatan Untuk Penjoki</label>
                <textarea id="notes" name="notes" rows="4"></textarea>
            </div>
        </form>
    </section>

    <section id="prices">
        <h2>Pilih Paket Joki</h2>
        <form>
            <div class="form-group">
                <label for="joki-category">Pilih Kategori Joki</label>
                <select id="joki-category" name="joki-category" required onchange="updateJokiPackages()">
                    <option value="">Pilih Kategori Joki</option>
                    <option value="joki-per-bintang">Joki per Bintang</option>
                    <option value="joki-per-5-bintang">Joki per 5 Bintang</option>
                    <option value="joki-per-rank">Joki per Rank</option>
                </select>
            </div>
    
            <div class="form-group" id="joki-package-options" style="display: none;">
                <label for="joki-package">Pilih Paket Joki</label>
                <select id="joki-package" name="joki-package" required>
                    <option value="">Pilih Paket</option>
                </select>
            </div>

            <div class="form-group" id="amount-group" style="display: none;">
                <label for="amount">Jumlah Nominal</label>
                <input type="number" id="amount" name="amount" required>
            </div>

            <div class="form-group">
                <label for="contact">Nomor WhatsApp/IG</label>
                <input type="text" id="contact" name="contact" required>
            </div>

            <div class="form-group">
                <label for="hero-request">Request Hero <small>(Minimal 3 hero)</small></label>
                <input type="text" id="hero-request" name="hero-request"> <!-- Hapus required -->
            </div>

            <div class="form-group" id="price-display" style="display: none;">
                <label>Harga:</label>
                <span id="price"></span>
            </div>
    
            <div class="form-group" id="total-display" style="display: none;">
                <label>Total:</label>
                <span id="total"></span>
            </div>

            <div class="form-group">
                <label for="payment-method">Pilih Metode Pembayaran</label>
                <select id="payment-method" name="payment-method" required onchange="toggleCustomPaymentInput()">
                    <option value="bca">Transfer Bank (BCA)</option>
                    <option value="ovo">E-wallet (OVO)</option>
                    <option value="dana">E-wallet (DANA)</option>
                    <option value="lainnya">Lainnya</option>
                </select>
            </div>

            <div class="form-group">
                <button type="submit">Order</button>
            </div>
        </form>
    </section>

    <section id="advantages">
        <h2>Keunggulan Kami</h2>
        <ul>
            <li><strong>Aman dan Terpercaya:</strong> Kami menjamin keamanan akun Anda dan tidak menggunakan cheat.</li>
            <li><strong>Pelayanan Cepat:</strong> Proses cepat dan efisien untuk mencapai peringkat yang Anda inginkan.</li>
            <li><strong>Tim Profesional:</strong> Joki yang berpengalaman dan profesional dalam bermain MLBB.</li>
        </ul>
    </section>

    <section id="testimonials">
        <h2>Testimoni</h2>
        <ul>
            <li>"JS878.ID sangat membantu saya mencapai Mythic dengan cepat! Layanannya luar biasa dan sangat profesional." - <strong>Anto</strong></li>
            <li>"Saya sangat puas dengan layanan joki dari JS878.ID. Aman, cepat, dan terpercaya." - <strong>Budi</strong></li>
            <li>"Saya ingin joki lagi di JS878.ID. Soalnya winstreak terus dan gak pernah AFK." - <strong>Ahmad</strong></li>
        </ul>
    </section>

    <section id="contact">
        <h2>Hubungi Kami</h2>
        <p>Email   : <a href="https://mail.google.com/mail/?view=cm&fs=1&to=js878.id@gmail.com" style="color: #1de9b6;">js878.id@gmail.com</a> </p>
        <p>WhatsApp : <a href="https://wa.me/qr/44VFL66RY6ACM1" style="color: #1de9b6;">+62 857-5603-5986</a></p>
        <p>IG      : <a href="https://www.instagram.com/js878.id?igsh=MTIxcGMzaXo4NDhmMg==" style="color: #1de9b6;">js878.id</a> </p>

        </section>
</div>

<footer>
    &copy; 2024 JS878.ID. Semua Hak Dilindungi. | <a href="https://wa.me/qr/44VFL66RY6ACM1" style="color: #1de9b6;">Hubungi kami sekarang</a>
</footer>

</body>
</html>

<script>
    function updateJokiPackages() {
        const priceDisplay = document.getElementById('price-display'); // Define priceDisplay
        const totalDisplay = document.getElementById('total-display'); // Define totalDisplay

        const category = document.getElementById('joki-category').value;
        const jokiPackageOptions = document.getElementById('joki-package-options');
        const jokiPackageSelect = document.getElementById('joki-package');
        const amountGroup = document.getElementById('amount-group');

        jokiPackageSelect.innerHTML = '';
        priceDisplay.style.display = 'none'; // Sembunyikan harga
        totalDisplay.style.display = 'none'; // Sembunyikan total
        
        if (category) {
            jokiPackageOptions.style.display = 'block';

            if (category === 'joki-per-bintang') {
                jokiPackageSelect.innerHTML = `
                    <option value="">Pilih Paket</option>
                    <option value="Warrior" data-price="1000">Warrior = 1.000</option>
                    <option value="Elite" data-price="1500">Elite = 1.500</option>
                    <option value="Master" data-price="2000">Master = 2.000</option>
                    <option value="Grandmaster" data-price="2500">Grandmaster = 2.500</option>
                    <option value="Epic" data-price="3000">Epic = 3.000</option>
                    <option value="Legend" data-price="4000">Legend = 4.000</option>
                    <option value="Mythic" data-price="5000">Mythic = 5.000</option>
                `;
                amountGroup.style.display = 'block'; // Tampilkan jumlah nominal
                priceDisplay.style.display = 'block'; // Tampilkan harga
                totalDisplay.style.display = 'block'; // Tampilkan total
            } else if (category === 'joki-per-5-bintang') {
                jokiPackageSelect.innerHTML = `
                    <option value="">Pilih Paket</option>
                    <option value="Warrior" data-price="4000">Warrior = 4.000</option>
                    <option value="Elite" data-price="7000">Elite = 7.000</option>
                    <option value="Master" data-price="9000">Master = 9.000</option>
                    <option value="Grandmaster" data-price="11000">Grandmaster = 11.000</option>
                    <option value="Epic" data-price="13000">Epic = 13.000</option>
                    <option value="Legend" data-price="15000">Legend = 15.000</option>
                    <option value="Mythic" data-price="18000">Mythic = 18.000</option>
                `;
                amountGroup.style.display = 'block'; // Tampilkan jumlah nominal
                priceDisplay.style.display = 'block'; // Tampilkan harga
                totalDisplay.style.display = 'block'; // Tampilkan total
            } else if (category === 'joki-per-rank') {
                jokiPackageSelect.innerHTML = `
                    <option value="">Pilih Paket</option>
<div class="form-group" id="joki-package-options" style="display: none;">
    <label for="joki-package">Pilih Paket Joki</label>
    <select id="joki-package" name="joki-package" required>
        <option value="">Pilih Paket</option>
        <option value="Warrior => Elite" data-price="20000">Warrior => Elite = 20.000</option>
        <option value="Elite => Master" data-price="30000">Elite => Master = 30.000</option>
        <option value="Master => Grandmaster" data-price="40000">Master => Grandmaster = 40.000</option>
        <option value="Grandmaster => Epic" data-price="50000">Grandmaster => Epic = 50.000</option>
        <option value="Epic => Legend" data-price="60000">Epic => Legend = 60.000</option>
        <option value="Legend => Mythic" data-price="70000">Legend => Mythic = 70.000</option>
        <option value="Mythic => Mythic Honor" data-price="85000">Mythic => Mythic Honor = 85.000</option>
    </select>
</div>
                `;
                amountGroup.style.display = 'none'; // Sembunyikan jumlah nominal
                priceDisplay.style.display = 'block'; // Tampilkan harga
                totalDisplay.style.display = 'block'; // Tampilkan total
            }
        } else {
            jokiPackageOptions.style.display = 'none';
            amountGroup.style.display = 'none'; // Sembunyikan jumlah nominal jika tidak ada kategori
        }

        function calculateTotal() {
        const selectedPackage = document.getElementById('joki-package').selectedOptions[0];
        const amount = document.getElementById('amount').value;
        const price = selectedPackage ? parseInt(selectedPackage.getAttribute('data-price')) : 0;
        let total;

        if (amount && amount > 0) {
            total = price * amount;
            document.getElementById('price').textContent = price.toLocaleString('id-ID') + ' (per unit)';
            document.getElementById('total').textContent = total.toLocaleString('id-ID') + ' (total)';
        } else {
            total = price; // Jika tidak ada jumlah nominal, total hanya harga per unit
            document.getElementById('price').textContent = price.toLocaleString('id-ID') + ' (per unit)';
            document.getElementById('total').textContent = total.toLocaleString('id-ID') + ' (total)';
        }

        document.getElementById('price-display').style.display = 'block';
        document.getElementById('total-display').style.display = 'block';
    }

    document.getElementById('joki-package'). addEventListener('change', calculateTotal);
    document.getElementById('amount').addEventListener('input', calculateTotal);

        // Remove duplicate definition of amountInput
        // This line is already defined above, so we will remove this duplicate
        // The following line is redundant and will be removed
    }
        const category = document.getElementById('joki-category').value;
        const jokiPackageOptions = document.getElementById('joki-package-options');
        const jokiPackageSelect = document.getElementById('joki-package');
        const amountGroup = document.getElementById('amount-group');

</script>
