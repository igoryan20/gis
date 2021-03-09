
<html lang="ru">
  <head>
    <script src="https://api-maps.yandex.ru/2.1/?apikey=ваш API-ключ&lang=ru_RU" type="text/javascript">
    </script>
  </head>
  <body>
    <h1>Добро пожаловать на мой сайт</h1>
    <p>Я не люблю показовать свое лицо</p>
    <img src="./image_main.jpg" alt="Мое фото" width="600px" height="400px">
    <style>
      img {
        border: 5px solid sandybrown;
      }  
    </style>
    <h2>Обо мне</h2>
    <h3>Личность</h3>
    <p>Скрытный персонаж</p>
    <h2>Местоположение</h2>
    <iframe src="https://www.google.com/maps/embed?pb=!1m14!1m12!1m3!1d17970.480575946705!2d37.52608285!3d55.7357413!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!5e0!3m2!1sru!2sru!4v1615308471581!5m2!1sru!2sru" width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy"></iframe>
    <div id="map" style="width: 600px; height: 400px"></div>
    <h3>Ссылки на другие страницы</h3>
    <ul>
      <li><a href="about.html">Обо мне подробнее</a></li>
      <li><a href="foto.html">Фоточки</a></li>
      <li><a href="like.html">Мои увлечения</a></li>
    </ul>
    
    <script type="text/javascript">
    // Функция ymaps.ready() будет вызвана, когда
    // загрузятся все компоненты API, а также когда будет готово DOM-дерево.
    ymaps.ready(init);
    function init(){
        // Создание карты.
        var myMap = new ymaps.Map("map", {
            // Координаты центра карты.
            // Порядок по умолчанию: «широта, долгота».
            // Чтобы не определять координаты центра карты вручную,
            // воспользуйтесь инструментом Определение координат.
            center: [55.76, 37.64],
            // Уровень масштабирования. Допустимые значения:
            // от 0 (весь мир) до 19.
            zoom: 7
        });
    }
  </script>
  </body>
</html>
