```html
<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>موقع الرياضات - B</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family:  Roboto , sans-serif;
            background: linear-gradient(to right, #f0f4ff, #e2e6ea);
            margin: 0;
            padding: 20px;
            color: #333;
        }
        header {
            background: #0044cc;
            color: #fff;
            padding: 30px 0;
            text-align: center;
            border-radius: 10px;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.2);
            margin-bottom: 20px;
        }
        nav {
            margin: 20px 0;
            text-align: center;
        }
        nav a {
            margin: 0 10px;
            text-decoration: none;
            color: #fff;
            background: #ffcc00;
            padding: 10px 15px;
            border-radius: 5px;
            transition: background 0.3s;
        }
        nav a:hover {
            background: #ffaa00;
        }
        article {
            background: #fff;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 15px rgba(0,0,0,0.1);
            margin-bottom: 20px;
        }
        h2 {
            color: #0044cc;
            border-bottom: 2px solid #0044cc;
            padding-bottom: 5px;
            margin-bottom: 15px;
        }
        footer {
            text-align: center;
            margin-top: 20px;
            font-size: 0.9em;
            color: #777;
        }
        img {
            max-width: 100%;
            border-radius: 10px;
        }
        .players, .teams {
            padding: 10px;
            background: #f9f9f9;
            border-left: 5px solid #0044cc;
            margin-top: 10px;
            border-radius: 5px;
        }
        .players ul, .teams ul {
            list-style-type: none;
            padding: 0;
        }
        .players li, .teams li {
            padding: 5px;
            border-bottom: 1px solid #ddd;
            transition: background 0.3s;
            display: flex;
            align-items: center;
        }
        .players li:hover, .teams li:hover {
            background: #e0f7e6;
        }
        .player-img {
            width: 50px;
            height: 50px;
            border-radius: 50%;
            margin-right: 10px;
            vertical-align: middle;
        }
        .section {
            margin-bottom: 20px;
        }
        .telegram-icon {
            width: 40px;
            height: 40px;
            margin-top: 20px;
            cursor: pointer;
        }
    </style>
</head>
<body>

<header>
    <h1>موقع الرياضات - B</h1>
</header>

<nav>
    <a href="#كرة-القدم">كرة القدم</a>
    <a href="#كرة-السلة">كرة السلة</a>
    <a href="#التنس">التنس</a>
    <a href="#الملاكمة">الملاكمة</a>
    <a href="#كرة-الطائرة">كرة الطائرة</a>
    <a href="#كرة-اليد">كرة اليد</a>
</nav>

<article>
    <section id="كرة-القدم" class="section">
        <h2>كرة القدم</h2>
        <img src="https://upload.wikimedia.org/wikipedia/commons/8/8b/Football_%28soccer%29.jpg" alt="صورة كرة القدم">
        <p>كرة القدم هي رياضة جماعية تُلعب بين فريقين يتكون كل منهما من 11 لاعباً. تعتبر كرة القدم أكثر الرياضات شعبية في العالم.</p>
        <div class="players">
            <h3>أفضل اللاعبين</h3>
            <ul>
                <li>
                    <img class="player-img" src="https://upload.wikimedia.org/wikipedia/commons/6/6c/Lionel_Messi_20180626.jpg" alt="ليونيل ميسي">
                    <strong>ليونيل ميسي</strong> - لاعب أرجنتيني، يعتبر من أعظم اللاعبين في تاريخ كرة القدم.
                </li>
                <li>
                    <img class="player-img" src="https://upload.wikimedia.org/wikipedia/commons/8/8b/Cristiano_Ronaldo_2018.jpg" alt="كريستيانو رونالدو">
                    <strong>كريستيانو رونالدو</strong> - لاعب برتغالي، يُعرف بسرعته وقوته البدنية.
                </li>
                <li>
                    <img class="player-img" src="https://upload.wikimedia.org/wikipedia/commons/f/f9/Neymar_2018.jpg" alt="نيمار جونيور">
                    <strong>نيمار جونيور</strong> - لاعب برازيلي، يتميز بمهاراته الفنية العالية.
                </li>
            </ul>
        </div>
    </section>

    <section id="كرة-السلة" class="section">
        <h2>كرة السلة</h2>
        <img src="https://upload.wikimedia.org/wikipedia/commons/e/e5/Basketball.png" alt="صورة كرة السلة">
        <p>كرة السلة هي رياضة تُلعب بين فريقين، كل فريق يتكون من خمسة لاعبين. الهدف هو تسجيل النقاط عن طريق إدخال الكرة في سلة الخصم.</p>
        <div class="players">
            <h3>أفضل اللاعبين</h3>
            <ul>
                <li>
                    <img class="player-img" src="https://upload.wikimedia.org/wikipedia/commons/0/0e/Michael_Jordan_in_2014.jpg" alt="مايكل جوردان">
                    <strong>مايكل جوردان</strong> - يُعتبر أعظم لاعب في تاريخ كرة السلة.
                </li>
                <li>
                    <img class="player-img" src="https://upload.wikimedia.org/wikipedia/commons/4/4c/LeBron_James_in_2014.jpg" alt="ليبرون جيمس">
                    <strong>ليبرون جيمس</strong> - لاعب أمريكي، يعتبر من أفضل اللاعبين في العصر الحديث.
                </li>
                <li>
                    <img class="player-img" src="https://upload.wikimedia.org/wikipedia/commons/7/73/Kobe_Bryant_2014.jpg" alt="كوبي براينت">
                    <strong>كوبي براينت</strong> - لاعب أمريكي، لعب لفريق لوس أنجلوس ليكرز.
                </li>
            </ul>
        </div>
    </section>

    <section id="التنس" class="section">
        <h2>التنس</h2>
        <img src="https://upload.wikimedia.org/wikipedia/commons/4/4f/Tennis_court.jpg" alt="صورة التنس">
        <p>التنس هو رياضة فردية أو زوجية تُلعب باستخدام مضرب وكرة. الهدف هو ضرب الكرة بطريقة تجعل الخصم غير قادر على إرجاعها.</p>
        <div class="players">
            <h3>أفضل اللاعبين</h3>
            <ul>
                <li>
                    <img class="player-img" src="https://upload.wikimedia.org/wikipedia/commons/8/8a/Roger_Federer_2019.jpg" alt="روجر فيدرر">
                    <strong>روجر فيدرر</strong> - لاعب سويسري، يعتبر من أعظم لاعبي التنس.
                </li>
                <li>
                    <img class="player-img" src="https://upload.wikimedia.org/wikipedia/commons/6/66/Rafael_Nadal_2018.jpg" alt="رافائيل نادال">
                    <strong>رافائيل نادال</strong> - لاعب إسباني، يُعرف بقوته على ملاعب الطين.
                </li>
                <li>
                    <img class="player-img" src="https://upload.wikimedia.org/wikipedia/commons/e/e8/Novak_Djokovic_2019.jpg" alt="نوفاك دجوكوفيتش">
                    <strong>نوفاك دجوكوفيتش</strong> - لاعب صربي، يعتبر من أفضل اللاعبين في العصر الحديث.
                </li>
            </ul>
        </div>
    </section>

    <section id="الملاكمة" class="section">
        <h2>الملاكمة</h2>
        <img src="https://upload.wikimedia.org/wikipedia/commons/3/3b/Boxing.jpg" alt="صورة الملاكمة">
        <p>الملاكمة هي رياضة قتال تُمارس بين اثنين من المتنافسين باستخدام قبضات اليد.</p>
        <div class="players">
            <h3>أفضل اللاعبين</h3>
            <ul>
                <li>
                    <img class="player-img" src="https://upload.wikimedia.org/wikipedia/commons/9/9e/Muhammad_Ali_1967.jpg" alt="محمد علي">
                    <strong>محمد علي</strong> - يُعتبر من أعظم الملاكمين في التاريخ.
                </li>
                <li>
                    <img class="player-img" src="https://upload.wikimedia.org/wikipedia/commons/0/0c/Mike_Tyson_2011.jpg" alt="مايك تايسون">
                    <strong>مايك تايسون</strong> - ملاكم أمريكي، معروف بقوته وسرعته.
                </li>
                <li>
                    <img class="player-img" src="https://upload.wikimedia.org/wikipedia/commons/7/75/Floyd_Mayweather_Jr_%28cropped%29.jpg" alt="فلويد مايويذر">
                    <strong>فلويد مايويذر</strong> - ملاكم أمريكي، يعرف بسجله المثالي.
                </li>
            </ul>
        </div>
    </section>

    <section id="كرة-الطائرة" class="section">
        <h2>كرة الطائرة</h2>
        <img src="https://upload.wikimedia.org/wikipedia/commons/0/0e/Volleyball.jpg" alt="صورة كرة الطائرة">
        <p>كرة الطائرة هي رياضة تُلعب بين فريقين، يتكون كل فريق من ستة لاعبين.</p>
        <div class="players">
            <h3>أفضل اللاعبين</h3>
            <ul>
                <li>
                    <img class="player-img" src="https://upload.wikimedia.org/wikipedia/commons/9/9c/Gabriela_Garcia.jpg" alt="غابرييل غارسيا">
                    <strong>غابرييل غارسيا</strong> - لاعبة بارزة في رياضة كرة الطائرة.
                </li>
                <li>
                    <img class="player-img" src="https://upload.wikimedia.org/wikipedia/commons/6/6e/Claudio_Silvio.jpg" alt="كلاوديو سيلفيو">
                    <strong>كلاوديو سيلفيو</strong> - لاعب معروف في كرة الطائرة.
                </li>
                <li>
                    <img class="player-img" src="https://upload.wikimedia.org/wikipedia/commons/2/2a/Brook_Courtney.jpg" alt="بروك كورتني">
                    <strong>بروك كورتني</strong> - لاعبة مميزة في كرة الطائرة النسائية.
                </li>
            </ul>
        </div>
    </section>

    <section id="كرة-اليد" class="section">
        <h2>كرة اليد</h2>
        <img src="https://upload.wikimedia.org/wikipedia/commons/8/8f/Handball.jpg" alt="صورة كرة اليد">
        <p>كرة اليد هي رياضة جماعية تُلعب بين فريقين يتكون كل منهما من سبعة لاعبين.</p>
        <div class="players">
            <h3>أفضل اللاعبين</h3>
            <ul>
                <li>
                    <img class="player-img" src="https://upload.wikimedia.org/wikipedia/commons/f/f0/Magnus_Richardson.jpg" alt="ماغنوس ريتشاردسون">
                    <strong>ماغنوس ريتشاردسون</strong> - لاعب معروف في كرة اليد.
                </li>
                <li>
                    <img class="player-img" src="https://upload.wikimedia.org/wikipedia/commons/b/b4/Emil_Nielsen.jpg" alt="إيميل نيلسون">
                    <strong>إيميل نيلسون</strong> - أحد أبرز لاعبي كرة اليد.
                </li>
                <li>
                    <img class="player-img" src="https://upload.wikimedia.org/wikipedia/commons/1/15/Ole_Christian.jpg" alt="أولي كريستيان">
                    <strong>أولي كريستيان</strong> - لاعب بارز في كرة اليد.
                </li>
            </ul>
        </div>
    </section>
</article>

<footer>
    <p>جميع الحقوق محفوظة &copy; 2023 - B</p>
    <a href="https://t.me/ba515kr" target="_blank">
        <img class="telegram-icon" src="https://upload.wikimedia.org/wikipedia/commons/6/6e/Telegram_logo.svg" alt="Telegram">
    </a>
</footer>

</body>
</html>
```
