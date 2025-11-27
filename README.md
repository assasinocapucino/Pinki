<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Website Cantik</title>

    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background: #ffe6f2;
            animation: fadeIn 1.2s ease-in-out;
        }

        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }

        /* NAVBAR */
        nav {
            background-color: #ff99c8;
            padding: 15px;
            animation: slideDown 1s ease;
        }

        @keyframes slideDown {
            from { transform: translateY(-50px); opacity: 0; }
            to { transform: translateY(0); opacity: 1; }
        }

        nav ul {
            margin: 0;
            padding: 0;
            list-style: none;
            display: flex;
        }

        nav ul li {
            margin-right: 20px;
        }

        nav ul li a {
            color: white;
            text-decoration: none;
            font-weight: bold;
            font-size: 16px;
        }

        nav ul li a:hover {
            color: #ffe6f2;
        }

        /* CONTENT */
        .container {
            max-width: 900px;
            margin: 40px auto;
            background: white;
            padding: 30px;
            border-radius: 15px;
            box-shadow: 0 0 10px rgba(255, 105, 180, 0.2);
            animation: popUp 1s ease;
        }

        @keyframes popUp {
            from { transform: scale(0.8); opacity: 0; }
            to { transform: scale(1); opacity: 1; }
        }

        h1 {
            margin-top: 0;
            color: #ff4da6;
            text-align: center;
        }

        p { line-height: 1.6; font-size: 17px; }

        .praise-box {
            background: #ffd1e8;
            padding: 20px;
            border-radius: 12px;
            margin-top: 25px;
            border: 2px solid #ff99c8;
            animation: glow 2s infinite alternate;
        }

        @keyframes glow {
            from { box-shadow: 0 0 10px #ffb3d9; }
            to { box-shadow: 0 0 20px #ff4da6; }
        }

        .cute-btn {
            display: inline-block;
            padding: 12px 25px;
            margin-top: 20px;
            background: #ff99c8;
            color: white;
            text-decoration: none;
            border-radius: 25px;
            font-size: 18px;
            transition: 0.3s;
            animation: bounce 1.5s infinite;
        }

        @keyframes bounce {
            0%, 100% { transform: translateY(0); }
            50% { transform: translateY(-7px); }
        }

        .cute-btn:hover {
            background: #ff4da6;
        }

        .bear-img {
            display: block;
            margin: 25px auto;
            width: 200px;
            animation: float 3s ease-in-out infinite;
        }

        @keyframes float {
            0%, 100% { transform: translateY(0); }
            50% { transform: translateY(-10px); }
        }

        .footer {
            text-align: center;
            padding: 20px;
            margin-top: 40px;
            background: #ff99c8;
            color: white;
        }
    </style>
</head>

<body>

    <nav>
        <ul>
            <li><a href="beranda.html">Beranda</a></li>
            <li><a href="#">Tentang</a></li>
            <li><a href="#">Pesan Cantik</a></li>
            <li><a href="#">Kontak</a></li>
        </ul>
    </nav>

    <div class="container">
        <h1>Website Penuh Pujian Cantik</h1>

        <img class="bear-img" src="https://i.imgur.com/2nCt3Sb.png" alt="Beruang Lucu">

        <p>
            Selamat datang di halaman penuh warna pink yang manis dan lembut.
            Didedikasikan untuk seseorang yang cantik, mempesona, dan penuh pesona.
        </p>

        <div class="praise-box">
            <h2 style="color:#ff4da6; text-align:center;">✨ Kata-Kata Pujian ✨</h2>
            <p>
                • Senyummu itu seperti cahaya pagi—hangat dan menenangkan.<br>
                • Kamu cantik luar dalam, dengan hati selembut awan pink.<br>
                • Ada pesona istimewa darimu yang bikin dunia terlihat lebih indah.<br>
                • Tawamu seperti musik lembut yang bikin suasana cerah seketika.<br>
                • Kamu seperti mawar pink—lembut, wangi, dan selalu memikat.
            </p>
        </div>

        <a class="cute-btn" href="#">Klik di sini, Cantik 💗</a>

    </div>

    <div class="footer">
        Dibuat dengan penuh cinta, warna pink, dan animasi lucu.
    </div>

</body>
</html>
