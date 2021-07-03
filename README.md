# hell-world
Week 5
<!DOCTYPE html>
<html lang="ru">
<link rel="stylesheet" href="/week4/figma4/styles/normalize.css">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>

    <style>
        body {
            background-color: rgb(223, 215, 215)
        }

        h1 {
            text-align: center;
        }

        section {
            text-align: center;
            float: left;
            width: 70%;
            height: 200px;
            background-color: rgb(238, 237, 178);

        }

        aside {
            float: right;
            height: 200px;
            width: 29%;
            background-color: rgb(156, 235, 186);
            text-align: center;
        }
        .block1,.block2 {
            display: flex;
            flex-wrap: wrap;
            flex-direction: row;
            justify-content: space-between;
           height: 30px;
width:150px;
margin: 5px;
background-color: rgb(243, 213, 129);
            
        }

        .block3 {
            display: flex;
            flex-wrap: wrap;
            padding: 10px;
            margin: 5px;
            flex-grow: 1;
            background-color: rgb(243, 213, 129);        }

                p {
            border: 1px solid rgb(248, 245, 241);
            display: inline-block;
            padding: 9px;
            margin: 5px;
            height: 5vh;
            background-color: rgb(248, 245, 241);
        }
    </style>

</head>

<body>
    <h1>[Шапка страницы]</h1>
<main>
    <section><b>[Основная часть] </b>
        <div class="block1">1</div>
        <div class="block2">2</div>
        <div class="block3">3</div>
        </div>
    </section>

    <aside><b>[Боковая область]</b</aside> 
    </main>

        <footer>
            <p><b>[Секция футера 1]</b></p>
            <p><b>[Секция футера 2]</b></p>
            <p><b>[Секция футера 3]</b></p>
            <p><b>[Секция футера 4]</b></p>
                        </footer>
            </body>

</html>
