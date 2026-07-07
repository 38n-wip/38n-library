<!DOCTYPE html>
<html lang="ja">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>サイト名</title>

    <style>
        *{
            margin:0;
            padding:0;
            box-sizing:border-box;
        }

        body{
            background:#F8F7F4;
            color:#1C1C1C;
            font-family:
                "Yu Mincho",
                "Hiragino Mincho ProN",
                "BIZ UDPMincho",
                serif;
            line-height:2.2;
            animation:fade 0.8s ease;
        }

        @keyframes fade{
            from{
                opacity:0;
            }
            to{
                opacity:1;
            }
        }

        header{
            text-align:center;
            padding:180px 20px 120px;
        }

        h1{
            font-family:
                "Noto Sans JP",
                sans-serif;

            font-weight:300;
            letter-spacing:8px;
            font-size:2.4rem;
            margin-bottom:40px;
        }

        .tagline{
            font-size:1rem;
            color:#555;
            margin-bottom:70px;
        }

        .profile{
            max-width:650px;
            margin:auto;
            text-align:left;
        }

        .profile h2{
            font-family:
                "Noto Sans JP",
                sans-serif;
            font-weight:300;
            font-size:1.1rem;
            margin-bottom:18px;
            letter-spacing:2px;
        }

        .profile p{
            margin-bottom:10px;
        }

        section{
            max-width:700px;
            margin:180px auto;
            padding:0 20px;
        }

        section h2{
            font-family:
                "Noto Sans JP",
                sans-serif;
            font-weight:300;
            margin-bottom:60px;
            letter-spacing:3px;
        }

        .work{
            margin-bottom:70px;
        }

        .work a{
            color:#1C1C1C;
            text-decoration:none;
            font-size:1.2rem;
            transition:.3s;
        }

        .work a:hover{
            color:#4A7C7E;
        }

        .date{
            color:#777;
            margin-top:8px;
            font-size:.9rem;
        }

        footer{
            text-align:center;
            color:#999;
            padding:120px 0 60px;
            font-size:.8rem;
        }

        hr{
            border:none;
            border-top:1px solid #ddd;
            margin:120px auto;
            width:120px;
        }

    </style>

</head>

<body>

<header>

    <h1>サイト名</h1>

    <p class="tagline">
        小説の余白や沈黙を、そのまま記録する場所。
    </p>

    <hr>

    <div class="profile">

        <h2>About</h2>

        <p><strong>ペンネーム</strong></p>

        <p>
            人の感情や、言葉にならない時間を描いています。
        </p>

    </div>

</header>

<section>

    <h2>Works</h2>

    <div class="work">

        <a href="works/comet.html">
            彗星のあとに
        </a>

        <div class="date">
            2026.07.07
        </div>

    </div>

    <div class="work">

        <a href="works/fragrance.html">
            名前のない香り
        </a>

        <div class="date">
            2026.06.01
        </div>

    </div>

    <div class="work">

        <a href="works/nomikomenai.html">
            のみこめない
        </a>

        <div class="date">
            2026.05.14
        </div>

    </div>

</section>

<footer>

    © Pen Name

</footer>

</body>
</html>