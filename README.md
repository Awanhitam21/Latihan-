<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Biodata & Portofolio</title>
    <style>
        body { font-family: Arial, sans-serif; margin: 0; padding: 0; }
        .container { width: 80%; margin: auto; }
        .menu { background: #333; padding: 10px; text-align: center; }
        .menu a { color: white; text-decoration: none; margin: 0 15px; }
        .section { padding: 20px; }
        .judul { display: flex; align-items: center; justify-content: space-between; }
        .judul img { width: 150px; height: auto; }
        .biodata { display: grid; grid-template-columns: repeat(3, 1fr); gap: 10px; }
        .biodata div { background: #f4f4f4; padding: 20px; text-align: center; border-radius: 5px; }
        .portofolio { display: flex; flex-wrap: wrap; gap: 10px; }
        .portofolio div { flex: 1 1 calc(33.333% - 10px); background: #ddd; padding: 20px; text-align: center; border-radius: 5px; }
    </style>
</head>
<body>
    <div class="menu">
        <a href="#biodata">Biodata</a>
        <a href="#portofolio">Portofolio</a>
    </div>

    <div class="container">
        <div class="section judul">
            <h2>Biodata Saya</h2>
            <img src="profile.jpg" alt="Foto Profil">
        </div>

        <div id="biodata" class="section biodata">
            <div>Nama: [Nama Anda]</div>
            <div>Usia: [Usia Anda]</div>
            <div>Pekerjaan: [Pekerjaan Anda]</div>
            <div>Email: [Email Anda]</div>
            <div>Telepon: [Nomor Anda]</div>
            <div>Alamat: [Alamat Anda]</div>
        </div>

        <div id="portofolio" class="section portofolio">
            <div>Proyek 1</div>
            <div>Proyek 2</div>
            <div>Proyek 3</div>
            <div>Proyek 4</div>
            <div>Proyek 5</div>
            <div>Proyek 6</div>
        </div>
    </div>
</body>
</html>
