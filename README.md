# Belajar-Python
```html
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Thrift Berkelas</title>

    <style>
        *{
            margin:0;
            padding:0;
            box-sizing:border-box;
            font-family:Arial, Helvetica, sans-serif;
        }

        body{
            background:#f5f5f5;
            color:#333;
        }

        header{
            background:#fff;
            display:flex;
            justify-content:space-between;
            align-items:center;
            padding:20px 10%;
            box-shadow:0 2px 10px rgba(0,0,0,.1);
        }

        header h2{
            color:#2e7d32;
        }

        nav a{
            text-decoration:none;
            color:#333;
            margin-left:20px;
        }

        .hero{
            text-align:center;
            padding:80px 20px;
            background:#ffffff;
        }

        .hero h1{
            font-size:40px;
            margin-bottom:15px;
        }

        .hero p{
            color:#666;
            margin-bottom:25px;
        }

        .btn{
            background:#2e7d32;
            color:white;
            text-decoration:none;
            padding:12px 25px;
            border-radius:8px;
        }

        .produk{
            padding:60px 10%;
        }

        .produk h2{
            text-align:center;
            margin-bottom:30px;
        }

        .card-container{
            display:flex;
            gap:20px;
            flex-wrap:wrap;
            justify-content:center;
        }

        .card{
            background:white;
            width:250px;
            border-radius:10px;
            overflow:hidden;
            box-shadow:0 3px 10px rgba(0,0,0,.1);
            transition:.3s;
        }

        .card:hover{
            transform:translateY(-5px);
        }

        .card img{
            width:100%;
            height:250px;
            object-fit:cover;
        }

        .card-content{
            padding:15px;
        }

        .harga{
            color:#2e7d32;
            font-weight:bold;
            margin-top:10px;
        }

        footer{
            background:#222;
            color:white;
            text-align:center;
            padding:20px;
            margin-top:40px;
        }
    </style>
</head>
<body>

<header>
    <h2>Thrift.Berkelas</h2>

    <nav>
        <a href="#">Home</a>
        <a href="#">Produk</a>
        <a href="#">Tentang</a>
        <a href="#">Kontak</a>
        <a href="#">Keranjang</a>
        <a href="#">Pesan Sekarang</a>
    </nav>
</header>

<section class="hero">
    <h1>Temukan Fashion Thrift Berkualitas</h1>
    <p>Beli pakaian bekas berkualitas dengan harga yang lebih hemat.</p>

    <a href="#" class="btn">Belanja Sekarang</a>
</section>

<section class="produk">

    <h2>Produk Pilihan</h2>

    <div class="card-container">

        <div class="card">
            <img src="https://picsum.photos/300/300?1">
            <div class="card-content">
                <h3>Hoodie Vintage</h3>
                <p>Kondisi 95%</p>
                <p class="harga">Rp120.000</p>
            </div>
        </div>

        <div class="card">
            <img src="https://picsum.photos/300/300?2">
            <div class="card-content">
                <h3>Jaket Denim</h3>
                <p>Kondisi Like New</p>
                <p class="harga">Rp180.000</p>
            </div>
        </div>

        <div class="card">
            <img src="https://picsum.photos/300/300?3">
            <div class="card-content">
                <h3>T-Shirt Oversize</h3>
                <p>Kondisi 90%</p>
                <p class="harga">Rp75.000</p>
            </div>
        </div>

    </div>

</section>

<footer>
    <p>© 2026 Thrift.Berkelas | Belanja Hemat & Ramah Lingkungan</p>
</footer>

</body>
</html>
```
