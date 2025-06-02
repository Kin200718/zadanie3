# zadanie3
<html>
    <head>
        <style>
            header {
            background-image: url('https://avatars.mds.yandex.net/i?id=2ebec07dceca597e7878b4d22f78a069e7a0d441-5278273-images-thumbs&n=13');
            background-size: cover;
            background-position: center;
            height: 80px;
            width: 100%;
            }

            nav {
                font-size: 18px;
                font-family: "Arial";
                text-align: center;
                margin: 30;
            }

            nav a {
                color: black;
                text-decoration: none;
                margin: 0 30px;
                padding-bottom: 1px;
                border-bottom: 5px solid black;
                display: inline-block;
            }
            main h1 {
                font-size: 40;
                text-align: center;
                font-family: "Arial";
                margin: 45;
                font-weight: normal;
            }

            .images-container {
                display: flex;
                justify-content: center;
                flex-wrap: wrap;
                gap: 80px;

            }

            .image-block {
                position: relative;
            }

            .image-block::before {
                content: "";
                position: absolute;
                left: -15px;
                top: 0;
                bottom: 0;
                width: 3px;
                border-left: 10px dotted black;
            }

            .image-block img {
                width: 200px;
                height: 150px;
                object-fit: cover;
                display: block;
            }

            main p {
                font-family: "Arial";
                border: 1px solid black;
                border-radius: 15px;
                margin: 30px;
                padding: 10;

            }

            footer {
				background-color: #98FB98;
				padding: 10px;
			}

			footer p {
				background-color: white;
				padding: 5px;
                font-family: "Arial";
			}
        </style>
    </head>
    <body>
        <header>

        </header>
        <main>
            <h1><strong>Зоопарк "САФАРИ"</strong></h1>
            <div class="images-container">
                <div class="image-block">
                    <img src="https://avatars.mds.yandex.net/i?id=5109eb88e7abeaac1a1456bf978c0e45_l-5473596-images-thumbs&n=13" alt="Image 1">
                </div>
                <div class="image-block">
                    <img src="https://get.pxhere.com/photo/tree-grass-plant-animal-wildlife-zoo-fauna-elephant-tusk-family-snout-african-organism-indian-elephant-african-elephant-elephants-and-mammoths-terrestrial-animal-1375941.jpg" alt="Image 2">
                </div>
                <div class="image-block">
                    <img src="https://img.razrisyika.ru/kart/77/1200/307817-zhivotnye-zooparka-6.jpg" alt="Image 3">
                </div>
            </div>

            <p>Если вы находитесь на нашем сайте, то, вероятно, задумываетесь о приобретении билета в наш зоопарк "САФАРИ". Не стоит размышлять! Посетив "Сафари" один раз вы обязательно задумаетесь о возвращении. К тому же только в июне проходит главная акция года "Летний акцент"! Условия акции просты - если приходите с двумя детьми - билет второму ребенку совершенно бесплатно! В нашем зоопарке вы можете увидеть данных животных:</p1>
            <ul type="circle">
            	<li>Лев</li>
            	<li>Слон</li>
            	<li>Крокодил</li>
            	<li>Жираф</li>
            	<li>Бегемот</li>
            </ul>
	    <p>Для участия в акции введите ниже свои данные для высылания нами специального купона.</p1>
        </main>
        <footer>
            <p>E-mail:</p>
            <p>Телефон</p>
        </footer>
    </body>
</html>
