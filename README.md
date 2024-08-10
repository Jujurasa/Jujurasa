<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Surat Cinta</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #ffe4e1;
            color: #333;
            padding: 20px;
            max-width: 600px;
            margin: auto;
        }
        h1 {
            color: #ff1493;
        }
        #surat {
            display: none;
            margin-top: 20px;
            border: 2px solid #ff1493;
            padding: 15px;
            background-color: #fff0f5;
        }
        button {
            background-color: #ff1493;
            color: white;
            padding: 10px 15px;
            border: none;
            cursor: pointer;
            border-radius: 5px;
        }
        button:hover {
            background-color: #ff69b4;
        }
    </style>
</head>
<body>
    <h1>Surat Cinta</h1>
    <button onclick="toggleSurat()">Buka Surat</button>
    <div id="surat">
        <p>Sayangku,</p>
        <p>Setiap hari, pikiranku dipenuhi oleh senyummu yang manis dan tawa yang menyejukkan hati. Sejak pertama kali kita bertemu, aku tahu bahwa kita ditakdirkan untuk bersama. Kehadiranmu telah membawa kebahagiaan yang tak terhingga dalam hidupku.</p>
        <p>Aku bersyukur atas setiap momen yang kita habiskan bersama, dan aku sangat menantikan masa depan yang penuh cinta dan kebahagiaan denganmu. Kamu adalah cahaya dalam hidupku, dan aku berjanji akan selalu berada di sampingmu, apa pun yang terjadi.</p>
        <p>Dengan segenap cinta,</p>
        <p>[Namamu]</p>
    </div>

    <script>
        function toggleSurat() {
            const surat = document.getElementById('surat');
            const button = document.querySelector('button');
            if (surat.style.display === 'none') {
                surat.style.display = 'block';
                button.textContent = 'Tutup Surat';
            } else {
                surat.style.display = 'none';
                button.textContent = 'Buka Surat';
            }
        }
    </script>
</body>
</html>

<!---
Jujurasa/Jujurasa is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
