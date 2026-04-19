# proje
<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <title>Benim İlk Web Sitem</title>
    <style>
        /* Burası CSS kısmıdır, siteni güzelleştirir */
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            text-align: center;
            padding: 50px;
        }
        .kart {
            background: white;
            padding: 20px;
            border-radius: 15px;
            box-shadow: 0px 0px 10px rgba(0,0,0,0.1);
            display: inline-block;
        }
        button {
            background-color: #007bff;
            color: white;
            border: none;
            padding: 10px 20px;
            border-radius: 5px;
            cursor: pointer;
        }
        button:hover {
            background-color: #0056b3;
        }
    </style>
</head>
<body>

    <div class="kart">
        <h1>Selam! Ben [Senin Adın]</h1>
        <p>VS Code kullanarak ilk web sitemi yapıyorum.</p>
        <button onclick="mesajVer()">Bana Tıkla!</button>
    </div>

    <script>
        // Burası JavaScript kısmıdır, etkileşim sağlar
        function mesajVer() {
            alert("Harika! İlk butonun çalışıyor. 🎉");
        }
    </script>

</body>
</html>
