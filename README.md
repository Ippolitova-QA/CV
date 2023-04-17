# cv
Сайт-визитка на HTML + CSS + JS
<!doctype html>
<html lang="ru">

<head>
   <!-- Название страницы, которое отображается в верху вкладки браузера -->
   <title>Super Mario</title>
   <meta http-equiv="Content-type" content="text/html;charset=UTF-8" />
   <meta name="viewport" content="width=device-width" initial-scale=1.0>
   <!-- изображение Марио, отображается перед названием страницы вверху вкладки браузера -->
   <link rel="icon" href="./image/favicon__mario.png" type="image/png">
   <!-- подключение файла стилей, который убирает настройки браузера для одинакового отображения страницы во всех браузерах -->
   <link rel="stylesheet" href="css/resetStyle.css">
   <!-- подключение файла стилей -->
   <link rel="stylesheet" href="css/style.css?_v=1">
</head>

<body>
   <div class="wrapper">
      <main class="main">
         <!-- Облако -->
         <img class="cloud_1" src="./image/cloud.png" alt="Облако">
         <!-- Облако -->
         <img class="cloud_2" src="./image/cloud.png" alt="Облако">
         <!-- Облако -->
         <img class="cloud_3" src="./image/cloud.png" alt="Облако">
         <!-- Облако -->
         <img class="cloud_4" src="./image/cloud.png" alt="Облако">
         <!-- Полка на которой стоит Марио -->
         <img class="shelf" src="./image/shelf.jpg" alt="Полка на которой стоит Mario">
         <!-- Изображение Марио -->
         <div class="mario duble_jump">
            <img class="mario-img" src="./image/mario.png" alt="Марио">
         </div>
         <!-- Зелёная труба -->
         <img class="green__pipe" src="./image/green__pipe.png" alt="Зеленая труба">
         <!-- Пол -->
         <div class="floor">
            <img class="floor-img" src="./image/floor.jpg" alt="Пол из камней">
         </div>

         <!-- аудио файл, воспроизводится при прыжке Марио -->
         <audio src="./audio/super-mario.mp3" preload></audio>
         <div class="container">
            <section class="data">
               <div class="foto">
                  <div class="foto__frame">
                     <!-- Рамка для фото -->
                     <img src="./image/foto__frame.jpg" alt="Рамка для фотографии из камней">
                  </div>
                  <div class="foto__foto">
                     <!-- Фото -->
                     <img src="./ibb.co/JcZwpWb" alt="Фотография">
                  </div>
               </div>
               <div class="text">
                  <!-- Имя -->
                  <div class="name">
                     <div>ANASTASIA</div>
                     <div>IPPOLITOVA</div>
                  </div>
                  <div>
                     <div class="list"><span>age</span><span>:</span><span>24</span></div>
                     <div class="list"><span>work</span><span>:</span><span>qa-engineer</span></div>
                     <div class="list"><span>Power</span><span>:</span><span>Postman</span></div>
                     <div class="list"><span>location</span><span>:</span><span>moscow</span></div>

                  </div>
               </div>
            </section>
            <!-- Ссылки -->
            <section class="links">
               <div class="link"><a href="https://t.me/anastasi.vitalievna">Telegram</a></div>
               <div class="link"><a href="https://vk.com/anastasi.vitalievna">Vkontakte</a></div>
               <div class="link"><a href="mailto:an.ipp@yandex.ru">Email</a></div>
               <div class="link"><a href="https://www.linkedin.com/">Linkedin</a></div>

            </section>
         </div>
      </main>
   </div>
   <!-- подключение файла javascript -->
   <script src="js/script.js"></script>
</body>

</html>
