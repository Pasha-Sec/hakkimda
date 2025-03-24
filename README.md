<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cyber Profil</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Share+Tech+Mono&display=swap');

        body {
            background-color: black;
            color: #00ff00;
            font-family: 'Share Tech Mono', monospace;
            text-shadow: 0 0 5px #00ff00, 0 0 10px #00ff00;
            padding: 20px;
            overflow: hidden;
        }

        h2 {
            border-bottom: 2px solid #00ff00;
            display: inline-block;
            animation: glow 1.5s infinite alternate;
        }

        ul {
            list-style: none;
            padding: 0;
        }

        li {
            margin: 10px 0;
            animation: fadeIn 2s ease-in-out;
        }

        @keyframes glow {
            0% { text-shadow: 0 0 5px #00ff00, 0 0 10px #00ff00; }
            100% { text-shadow: 0 0 10px #00ff00, 0 0 20px #00ff00; }
        }

        @keyframes fadeIn {
            0% { opacity: 0; transform: translateY(-10px); }
            100% { opacity: 1; transform: translateY(0); }
        }

        .matrix-bg {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: url('https://media.giphy.com/media/l3vRn3931E9FcgJEA/giphy.gif') repeat;
            opacity: 0.2;
            z-index: -1;
        }

        .hacker-text {
            overflow: hidden;
            white-space: nowrap;
            border-right: 2px solid #00ff00;
            animation: typing 4s steps(40, end) forwards, blink 0.8s infinite;
        }

        @keyframes typing {
            from { width: 0 }
            to { width: 100% }
        }

        @keyframes blink {
            50% { border-color: transparent; }
        }
    </style>
</head>
<body>

    <div class="matrix-bg"></div> 

    <h2>📌 İş Deneyimleri</h2>
    <ul>
        <li><strong>Yazılım Geliştirme Elemanı</strong> – Plan Gayrimenkul ON3 Yatırım (Ocak 2024 - Mart 2025)</li>
        <li><strong>Yazılım Geliştirme Elemanı</strong> – Desen Astar (Nisan 2018 - Ocak 2023)</li>
    </ul>

    <h2>🌍 Diller</h2>
    <ul>
        <li>İngilizce (Temel)</li>
    </ul>

    <h2>🛠️ Yetenekler</h2>
    <ul>
        <li>Linux, Linux Yönetimi, Debian Linux, Linux Kernel</li>
        <li>HTML, JSON, CSS, Web Servis</li>
        <li>MS SQL Server, MySQL</li>
        <li>Python, Java, Kotlin, PHP, C, Bash/Shell, jQuery</li>
        <li>Android & iOS Uygulama Geliştirme</li>
        <li>Adobe Illustrator, Adobe Photoshop</li>
        <li>Otomasyon Sistemleri</li>
        <li>Sertifikalı Etik Hacker</li>
    </ul>

    <h2>🎓 Sertifikalar & Kurslar</h2>
    <div class="hacker-text">
        <ul>
            <li><strong>HTP Academy – Hack The Box Academy</strong> (Temmuz 2022)<br>
                "Certified Bug Bounty Hunter" (CBBH) programını başarıyla tamamladı.<br>
                Hack The Box platformunda siber güvenlik becerilerini geliştirdi.
            </li>
            <li><strong>TryHackMe</strong> (Ocak 2021)<br>
                "Complete Beginner Learning Path" kursunu tamamladı.<br>
                Siber güvenlik eğitimleri sunan TryHackMe platformunda yetkinlik kazandı.
            </li>
        </ul>
    </div>

</body>
</html>