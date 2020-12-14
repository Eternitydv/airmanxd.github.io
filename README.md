<!doctype html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="icon" type="image/jpg" href="icon.jpg">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.0-alpha3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-CuOF+2SnTUfTwSZjCXf01h7uYhfOBuxIhGKPbfEJ3+FqH/s6cIFN9bGr1HmAg4fQ" crossorigin="anonymous">

    <title>Музыкальная библиотека</title>
  </head>
  <body>
        <style>
            a{
                text-decoration: none;
                color: white;
            }
            a:hover{
                text-decoration: none;
                color: white; 
            }
            .carousel-item
            {
                height: 100vh;
                background-color: black;
                color:white;
                position: relative;
                background-position: center;
                background-size: cover;
                background-repeat: no-repeat;
            }
            .container
            {
                position: relative;
                text-align: center;
                vertical-align: middle;
                top: 42%;
                font-size: 20px;
            }
            .overlay-image {
                position: absolute;
                bottom: 0;
                left: 0;
                right: 0;
                top: 0;
                opacity: 60%;
                background-position: center;
                background-size: cover;
            };
        </style>
        <div id="myCarousel" class="carousel slide" data-ride="carousel">
            <ol class="carousel-indicators">
                <li data-target="#myCarousel" data-slide-to="1"></li>
                <li data-target="#myCarousel" data-slide-to="2"class="active"></li>                
                <li data-target="#myCarousel" data-slide-to="3"></li>
            </ol>
            <div class="carousel-inner">
                <div class="carousel-item" data-interval="5000">
                    <a href="genre-electronic.html"><div class="overlay-image" style="background-image: url(https://s7d1.scene7.com/is/image/izotope/4%20Popular%20Styles%20in%202018%20EDM%20Production-1?wid=2000&fmt=jpg&resMode=sharp2);"></div>
                    <div class="container">
                        <h1>Электронная музыка</h1>
                        <p>Особое разнообразие в этом жанре достигается тем, что композиторы не привязаны к уже существующим инмструментам</p>
                    </div></a>
                </div>
                
                <div class="carousel-item active"  data-interval="5000">
                    <a href="rock.html">
                    <div class="overlay-image" style="background-image: url(./devilshorns.jpg);"></div>
                    
                    <div class="container">
                        <h1>Рок</h1>
                        <p>Этот раздел будет сфокусирован на более нишевых поджанрах</p>
                    </div></a>
                </div>

                <div class="carousel-item"  data-interval="5000">
                    <a href="metal.html"><div class="overlay-image" style="background-image: url(https://i.pinimg.com/originals/c5/8b/86/c58b86713b51cd555748e0ac7caa2f68.jpg);"></div>
                    <div class="container">
                        <h1>Метал</h1>
                        <p>Наиболее интенсивный из представленных жанров</p>
                    </div></a>
                </div>
                
                
            </div>
        <a href="#myCarousel" class="carousel-control-prev" role="button"
            data-slide="prev"><span class="sr-only"></span>
            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
        </a>
        <a href="#myCarousel" class="carousel-control-next" role="button"
            data-slide="next"><span class="sr-only"></span>
            <span class="carousel-control-next-icon" aria-hidden="true"></span>
        </a>
        </div>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.0-alpha3/dist/js/bootstrap.bundle.min.js" integrity="sha384-popRpmFF9JQgExhfw5tZT4I9/CI5e2QcuUZPOVXb1m7qUmeR2b50u+YFEYe1wgzy" crossorigin="anonymous"></script>
  </body>
</html>
