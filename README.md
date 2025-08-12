# my-first-website
Learn how to recycle plastic, glass, paper, metal, and electronic waste. Protect nature, use resources efficiently, and contribute to a cleaner environment with proper recycling methods.
<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Geri Dönüşüm Rehberi</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            background-color: #f5f5f5;
            color: #333;
            text-align: center;
        }
        header {
            background-color: #4CAF50;
            color: white;
            padding: 1rem;
            font-size: 1.5rem;
        }
        .container {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            margin-top: 2rem;
        }
        .card {
            background: white;
            border-radius: 10px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
            width: 200px;
            margin: 1rem;
            padding: 1rem;
            transition: transform 0.2s;
            cursor: pointer;
        }
        .card:hover {
            transform: scale(1.05);
        }
        .card img {
            width: 80px;
            height: 80px;
        }
        .info {
            display: none;
            margin-top: 1rem;
            font-size: 0.9rem;
            color: #555;
        }
    </style>
</head>
<body>

<header>♻️ Geri Dönüşüm Rehberi</header>
<div class="container">
    <div class="card" onclick="toggleInfo(this)">
        <img src="https://cdn-icons-png.flaticon.com/512/1046/1046784.png" alt="Plastik">
        <h3>Plastik</h3>
        <p class="info">Plastik şişe, kap ve poşetleri mavi geri dönüşüm kutusuna atın. Temiz olmasına dikkat edin.</p>
    </div>

    <div class="card" onclick="toggleInfo(this)">
        <img src="https://cdn-icons-png.flaticon.com/512/1046/1046751.png" alt="Cam">
        <h3>Cam</h3>
        <p class="info">Cam şişe ve kavanozları yeşil geri dönüşüm kutusuna atın. Kırık camları ayrı paketleyin.</p>
    </div>

    <div class="card" onclick="toggleInfo(this)">
        <img src="https://cdn-icons-png.flaticon.com/512/1046/1046769.png" alt="Kağıt">
        <h3>Kağıt</h3>
        <p class="info">Gazete, dergi, karton ve ofis kağıtlarını mavi geri dönüşüm kutusuna atın.</p>
    </div>

    <div class="card" onclick="toggleInfo(this)">
        <img src="https://cdn-icons-png.flaticon.com/512/1046/1046787.png" alt="Metal">
        <h3>Metal</h3>
        <p class="info">Alüminyum kutu, teneke kutu ve metal kapakları geri dönüşüm kutusuna atın.</p>
    </div>

    <div class="card" onclick="toggleInfo(this)">
        <img src="https://cdn-icons-png.flaticon.com/512/1046/1046790.png" alt="Elektronik">
        <h3>Elektronik</h3>
        <p class="info">Bozuk telefon, bilgisayar, pil ve küçük elektronik cihazları e-atık toplama merkezine verin.</p>
    </div>
</div>

<script>
    function toggleInfo(card) {
        let info = card.querySelector('.info');
        info.style.display = (info.style.display === 'block') ? 'none' : 'block';
    }
</script>

</body>
</html>
