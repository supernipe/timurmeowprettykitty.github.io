
<html lang="uk">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Україна: Історія, Люди, Місця</title>
    <style>
        /* Общие стили */
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 20px;
            background: linear-gradient(to bottom, #005fba, #ffff00); /* Цвета флага Украины */
            color: #333;
            line-height: 1.6;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }

        header {
            background: #005fba;
            color: white;
            text-align: center;
            padding: 20px 0;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }

        nav {
            background: #ffff00;
            display: flex;
            justify-content: center;
            padding: 10px 0;
            border-radius: 5px;
            margin-bottom: 20px;
        }

        nav a {
            color: #005fba;
            text-decoration: none;
            padding: 10px 20px;
            font-weight: bold;
            transition: background 0.3s ease;
        }

        nav a:hover {
            background: #d4d400;
            border-radius: 5px;
        }

        section {
            background: rgba(255, 255, 255, 0.9);
            padding: 20px;
            border-radius: 10px;
            margin-bottom: 20px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        h1, h2, h3 {
            color: #005fba;
        }

        img {
            max-width: 100%;
            height: auto;
            border-radius: 5px;
            margin-bottom: 10px;
        }

        footer {
            text-align: center;
            padding: 10px 0;
            background: #005fba;
            color: white;
            margin-top: 20px;
            border-radius: 5px;
        }

        blockquote {
            background: #f9f9f9;
            border-left: 4px solid #005fba;
            padding: 10px;
            margin: 15px 0;
            font-style: italic;
        }

        .song {
            background: #f9f9f9;
            padding: 10px;
            border: 2px dashed #005fba;
            margin: 15px 0;
            font-style: italic;
        }

        .card {
            background: #ffffff;
            padding: 15px;
            border-radius: 8px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
            margin-bottom: 20px;
        }

        @media (max-width: 768px) {
            nav {
                flex-direction: column;
            }
            nav a {
                padding: 10px;
            }
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <h1>Україна: Історія, Люди, Місця</h1>
        </div>
    </header>

    <nav class="container">
        <a href="#history">Історія регіонів</a>
        <a href="#personalities">Знамениті люди</a>
        <a href="#landmarks">Достопримічності</a>
        <a href="#map">Карта України</a>
    </nav>

    <!-- Секция Знамениті люди -->
    <section id="personalities" class="container">
        <h2>Знамениті люди України</h2>

        <div class="card">
            <img src="[https://upload.wikimedia.org/wikipedia/commons/thumb/7/7a/Taras_Shevchenko_1841.jpg/220px-Taras_Shevchenko_1841.jpg](https://cdn.culture.ru/images/b63bec59-8a75-565b-8a53-1853e4e751c6/w_1020,c_fill,g_center/2-min-jpg)" alt="Тарас Шевченко">
            <h3>Тарас Григорович Шевченко</h3>
            <p>Народний поет України, художник та політичний діяч. Його твори стали основою української літератури.</p>
            <h4>Книга: "Кобзар"</h4>
            <blockquote>
                "Як жаль, що не маємо свого дому,<br>
                Щоб там спокійно жити ми могли..."
            </blockquote>
        </div>

        <div class="card">
            <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/1/1c/Lesya_Ukrayinka_1910.jpg/220px-Lesya_Ukrayinka_1910.jpg" alt="Леся Українка">
            <h3>Леся Українка</h3>
            <p>Поетеса, драматург та перекладач. Леся Українка написала багато творів, що відображають духовні пошuki та боротьбу за права людини.</p>
            <h4>Книга: "Лісова пісня"</h4>
            <blockquote>
                "О, як мене тягне до лісу темного,<br>
                Де дивовижні дива з'являються..."
            </blockquote>
        </div>

        <div class="card">
            <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/7/7a/Ivan_Franko_1909.jpg/220px-Ivan_Franko_1909.jpg" alt="Іван Франко">
            <h3>Іван Франко</h3>
            <p>Письменник, поет та політичний діяч. Його твори охоплюють широкий спектр тем: від соціальної справедливості до культурних цінностей.</p>
            <h4>Книга: "Мове зірок"</h4>
            <blockquote>
                "Зорі! Як вам добре там на небі синьому,<br>
                Де немає болю, немає сліз..."
            </blockquote>
        </div>

        <div class="card">
            <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/4/4b/Mykola_Lysenko_portrait.jpg/220px-Mykola_Lysenko_portrait.jpg" alt="Микола Лисенко">
            <h3>Микола Лисенко</h3>
            <p>Композитор, диригент та педагог. Микола Лисенко створив багато музики, що відображає дух української народної культури.</p>
            <h4>Пісня: "Ще не вмерла Україна"</h4>
            <div class="song">
                Ще не вмерла Україна,<br>
                Ні слава, ні воля!<br>
                Ми ще насамперед боротьба<br>
                Покажемо всім!
            </div>
        </div>

        <div class="card">
            <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/6/6c/Oksana_Bilozir.jpg/220px-Oksana_Bilozir.jpg" alt="Оксана Білощерка">
            <h3>Оксана Білощерка</h3>
            <p>Сучасна українська пісенніця та композитор. Оксана Білощерка відома своїми патріотичними піснями, які вдихають надію та силу.</p>
            <h4>Пісня: "Два слова"</h4>
            <div class="song">
                Два слова — це все, що потрібно:<br>
                Ти і я.<br>
                В два серця вкладена сила,<br>
                Що нас зберігає.
            </div>
        </div>
    </section>

    <!-- Секция Історія регіонів -->
    <section id="history" class="container">
        <h2>Історія регіонів України</h2>
        <h3>Київська область</h3>
        <p>Київ — столиця України, місто, яке має більше 1500-річну історію. Київська Русь стала однією з найважливіших держав середньовічного світу. Тут зародилася культура, наука та релігія для всієї Східної Європи.</p>
        <h3>Львівська область</h3>
        <p>Львів — місто, яке зберігає дух галицької культури. Він був важливим торговельним центром у Середньовіччі та місцем зустрічі різних культур: української, польської, єврейської та німецької.</p>
        <h3>Харківська область</h3>
        <p>Харків — один з найбільших наукових та промислових центрів України. У Харкові знаходяться видатні університети та наукові інститути, які виховують лідерів у різних галузях знань.</p>
        <h3>Одеська область</h3>
        <p>Одеса — морський порт, який завжди був відкритий до світу. Це місто з несправдженим чувством юмору та великою культурною спадщиной. Оเทศка опера та бальнеологічні курорти приваблюють туристів со всього світу.</p>
        <h3>Закарпаття</h3>
        <p>Закарпаття — регіон, де переплелися культури української, угорської, румунської та словаччини. Карпатські гори — це місце, де можна відпочити від шуму мегаполісу та насолоджуватися природою.</p>
    </section>

    <!-- Секция Достопримічності -->
    <section id="landmarks" class="container">
        <h2>Достопримічності України</h2>

        <div class="card">
            <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/1/1a/Kyiv_Pechersk_Lavra_2017.jpg/220px-Kyiv_Pechersk_Lavra_2017.jpg" alt="Київська Печерська Лавра">
            <h3>Київська Печерська Лавра</h3>
            <p>Монастирський комплекс, заснований у 1051 році. Це одне з найважливіших релігійних місць України, де зберігаються реліквії святих та стародавні рукописи.</p>
        </div>

        <div class="card">
            <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/9a/Carpathians_from_Svydovets.jpg/220px-Carpathians_from_Svydovets.jpg" alt="Карпати">
            <h3>Карпатські гори</h3>
            <p>Гірська система, яка приваблює туристів своєю природною красою. Говерла — найвища вершина України (2061 м), а також багато лісових трас та термальних курортів.</p>
        </div>

        <div class="card">
            <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/3d/Chernobyl_Nuclear_Power_Plant.jpg/220px-Chernobyl_Nuclear_Power_Plant.jpg" alt="Чорнобиль">
            <h3>Чорнобильська зона відчуження</h3>
            <p>Місце, що стало символом трагедії 1986 року. Сьогодні це екологічний заповідник, де можна побачити, як природа повертає себе без людської діяльності.</p>
        </div>

        <div class="card">
            <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/5/5e/Sofiyivka_Park.jpg/220px-Sofiyivka_Park.jpg" alt="Софіївка">
            <h3>Парк Софіївка</h3>
            <p>Архітектурно-парковий комплекс у місті Умань, який поєднує елементи різних культур та стилів. Парк заснований у XVIII столітті та є одним з найкрасивіших у світі.</p>
        </div>

        <div class="card">
            <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/a/a6/Odesa_Opera_House.jpg/220px-Odesa_Opera_House.jpg" alt="Одеський оперний театр">
            <h3>Одеський оперний театр</h3>
            <p>Архітектурна жемчужина України, яка заснована у 1887 році. Театр відомий своєю прекрасною акустикою та великою сценою, де виступають найкращі артисти світу.</p>
        </div>
    </section>

    <!-- Секція Карта -->
    <section id="map" class="container">
        <h2>Карта України</h2>
        <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d2647.715092951112!2d30.523622315603283!3d50.45689998053299!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x40d4ce5ab5fe1a41%3A0x6b8d1d3a3c3b3a2f!2z0JrQvtC70L7QstGB0LrQuNC5INC-0LHQu9C40YHRjg!5e0!3m2!1suk!2sua!4v1633072877032!5m2!1suk!2sua" style="border:0; width: 100%; height: 400px;" allowfullscreen="" loading="lazy"></iframe>
    </section>

    <!-- Футер -->
    <footer class="container">
        <p>© 2023 Україна: Історія, Люди, Місця | Розроблено з любов'ю</p>
    </footer>
</body>
</html>
