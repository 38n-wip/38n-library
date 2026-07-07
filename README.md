<!DOCTYPE html>
<html lang="ja">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>38n</title>

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
            padding:180px 20px 120px;
        }

        .profile{
            max-width:650px;
            margin:auto;
        }

        .profile h2{
            font-family:
                "Noto Sans JP",
                sans-serif;
            font-weight:300;
            font-size:1.1rem;
            margin-bottom:40px;
            letter-spacing:2px;
        }

        .profile .name{
            font-size:1.3rem;
            margin-bottom:28px;
        }

        .profile p{
            color:#555;
            line-height:2;
        }

        section{
            max-width:700px;
            margin:120px auto 180px;
            padding:0 20px;
        }

        section h2{
            font-family:
                "Noto Sans JP",
                sans-serif;
            font-weight:300;
            margin-bottom:60px;
            letter-spacing:2px;
            font-size:1.1rem;
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
            padding:80px 0 60px;
            font-size:.8rem;
        }

    </style>

</head>

<body>

<header>

    <div class="profile">

        <h2>Profile</h2>

        <div class="name">
            38n
        </div>

        <p>
            人生や、<br>
            言葉にならなかった時間を書いています。
        </p>

    </div>

</header>

<section>

    <h2>Library</h2>

    <div class="work">

        <a href="works/nomikomenai.html">
            のみこめない
        </a>

        <div class="date">
            2026.05.14
        </div>

    </div>

    <div class="work">

        <a href="works/comet.html">
            彗星のあとに
        </a>

        <div class="date">
            2026.07.07
        </div>

    </div>

    <div class="work">

        <a href="works/bookshelf.html">
            書架のひと
        </a>

        <div class="date">
            Coming Soon
        </div>

    </div>

    <div class="work">

        <a href="works/paranoid.html">
            パラノイドレポート
        </a>

        <div class="date">
            Coming Soon
        </div>

    </div>

    <div class="work">

        <a href="works/fragrance.html">
            名前のない香り
        </a>

        <div class="date">
            Coming Soon
        </div>

    </div>

</section>

<footer>

    © 38n

</footer>

</body>
</html>