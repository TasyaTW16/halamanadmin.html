<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initialscale=
1.0" />
    <title>Halaman Admin</title>
    <link rel="stylesheet" href="style.css" />
</head>

<body>
    <div class="grid-container">
        <div class="grid-navbar">
            <div class="navbarheader">Sistem Akademik</div>
            <div class="logout"><a href="#">Logout</a></div>
        </div>
        <div class="grid-sidebar">
            <div class="profilepic">
                <img src="ok.jpg" alt="" class="imground" />
                <p>pak luhut</p>
            </div>
            <div class="navigation">
                <ul>
                    <li><a class="active" href="#">Dashboard</a></li>
                    <li><a href="http://">KRS</a></li>
                    <li><a href="http://">KHS</a></li>
                    <li><a href="http://">Edit Profile</a></li>
                </ul>
            </div>
        </div>
        <div class="grid-head">
            <h2>Selamat Datang di Sistem Akademik</h2>
            <p>Sistem Informasi Akademik Campus Terintegrasi</p>
        </div>
        <div class="grid-content">
            <h2 class="judul">Edit Profil</h2>
            <div class="profilepic">
                <img src="ok.jpg" alt="" class="imground" />
                <p>Pak Luhut</p>
            </div>
            <form action="" method="POST">
                <div class="formgroup">
                    <label for="foto">Foto</label>
                    <div class="input"><input type="file" name="foto" id="foto" /></ div>
                    </div>
                    <div class="formgroup">
                        <label for="nama">Nama</label>
                        <div class="input"><input type="text" name="nama" id="Nama" /></ div>
                        </div>
                        <div class="formgroup">
                            <label for="password">Password</label>
                            <div class="input">
                                <input type="password" name="password" id="password" />
                            </div>
                        </div>
                        <div class="formgroup">
                            <input type="submit" value="simpan" class="tmbSimpan" />
                        </div>
            </form>
        </div>
    </div>
    </div>
</body>

</html>
