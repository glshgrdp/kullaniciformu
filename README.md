
<img width="1920" height="963" alt="kullanicibilgiformu" src="https://github.com/user-attachments/assets/5d16cc33-8c02-4583-9624-413e661f6fb6" />






<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kullanıcı Formu</title>
</head>
<body>
    <h1>Kullanıcı Bilgi Formu</h1>
    <form action="#" method="post">
        <!-- Ad ve Soyad -->
        <label for="ad">Ad:</label>
        <input type="text" id="ad" name="ad" required><br><br>

        <label for="soyad">Soyad:</label>
        <input type="text" id="soyad" name="soyad" required><br><br>

        <!-- E-posta -->
        <label for="email">E-posta:</label>
        <input type="email" id="email" name="email" required><br><br>

        <!-- Parola -->
        <label for="parola">Parola:</label>
        <input type="password" id="parola" name="parola" required><br><br>

        <!-- Cinsiyet -->
        <label>Cinsiyet:</label>
        <input type="radio" id="erkek" name="cinsiyet" value="Erkek" required>
        <label for="erkek">Erkek</label>
        <input type="radio" id="kadin" name="cinsiyet" value="Kadın">
        <label for="kadin">Kadın</label><br><br>

        <!-- Favori Meyve -->
        <label for="meyve">Favori Meyve:</label>
        <select id="meyve" name="meyve" required>
            <option value="">Seçiniz</option>
            <option value="Elma">Elma</option>
            <option value="Muz">Muz</option>
            <option value="Cilek">Çilek</option>
        </select><br><br>

        <!-- Mesaj -->
        <label for="mesaj">Mesaj:</label><br>
        <textarea id="mesaj" name="mesaj" rows="5" cols="40" placeholder="Mesajınızı buraya yazın..."></textarea><br><br>

        <!-- Gönder Butonu -->
        <input type="submit" value="Gönder">
    </form>
</body>
</html>










# kullaniciformu
Form Elemanları Kullanımı (input, select, textarea vb.)
