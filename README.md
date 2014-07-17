nerds
=====
<!DOCTYPE html>
<html>
    <head>
        <title>NЁRDS | Главная</title>
        <meta charset="utf-8">
        <base href="http://barbershop-borodinski.ru/rybalko/nerds/">
        <link href="images/favicon.png" type="image/png" rel="shortcut icon">
        <link href="css/style.css" rel="stylesheet">
        <link href='http://fonts.googleapis.com/css?family=Roboto:100,300,500&subset=latin,cyrillic-ext,cyrillic,latin-ext' rel='stylesheet' type='text/css'>
    </head>
<body>
<!-- Header -->
    <header class="page-header">
        <div class="layout-center-wrapper">
            <div class="header-top clearfix">
                <div class="header-top__logo"><a href="index.html"><img src="images/header-logo.png" alt="NЁRDS"></a></div>
                <ul class="header-top__menu">
                    <li><a href="index.html"><span class="header-menu-active">Студия</span></a></li>
                    <li><a href="javascript:void(0)">Клиенты</a></li>
                    <li><a href="shop.html">Магазин</a></li>
                    <li><a href="javascript:void(0)">Контакты</a></li>
                </ul>
                <div class="header-top__cart">
                    <a class="header-top__cart-enter" href="#">Корзина</a>
                </div>
            </div>
            <div class="slider">
                <div class="slides">
                    <div class="slider__slide slide--first">
                        <div class="slider__slide-text">
                            <span class="slider__slide-h1">Долго, дорого,<br> скрупулезно</span>
                            <p>Математически выверенный дизайн<br> для вашего сайта или мобильного приложения.</p>
                            <a class="btn slide-btn" href="#">Узнать больше</a>
                        </div>
                    </div>
                    <div class="slider__slide slide--second">
                        <div class="slider__slide-text">
                            <span class="slider__slide-h1">Любите ли вы математику,<br> как любим ее мы?</span>
                            <p>Нашим дизайнерам мы удаляем нейроны, ответственные<br> за креатив, чтобы дать им возможность все просчитать</p>
                            <a class="btn slide-btn" href="#">Узнать больше</a>
                        </div>
                    </div>
                    <div class="slider__slide slide--third">
                        <div class="slider__slide-text">
                            <span class="slider__slide-h1">Только наркотики,<br>только хардкор!</span>
                            <p>Математически выверенный дизайн для вашего сайта или мобильного приложения.</p>
                            <a class="btn slide-btn" href="#">Узнать больше</a>
                        </div>
                    </div>
                </div>
                <div class="slider__paginator">
                    <i class="active"></i>
                    <i></i>
                    <i></i>
                </div>
            </div>
        </div>
    </header>
<!-- Main -->
    <div class="layout-center-wrapper">
        <div class="promo-blocks clearfix">
            <div class="promo promo__red">
                <p class="promo--title">Веб-сайты</p>
                <p>Мир никогда не будет прежним после того как увидит ваш сайт!</p>
                <a class="btn promo__red-btn" href="javascript:void(0)">Заказать</a>
            </div>
            <div class="promo promo__green">
                <p class="promo--title">Приложения</p>
                <p>Покорите топ-10 приложений в AppStore и Google Play</p>
                <a class="btn promo__green-btn" href="javascript:void(0)">Заказать</a>
            </div>
            <div class="promo promo__yellow">
                <p class="promo--title">Презентации</p>
                <p>Вы даже не подозреваете насколько вы изумительны!</p>
                <a class="btn promo__yellow-btn" href="javascript:void(0)">Заказать</a>
            </div>
        </div>
        <div class="content">
            <div class="content__block-top">
                <h1 class="content-h1">Мы — маленькая, но гордая<br>дизайн-студия из Краснодара.</h1>
                Исповедуем принципы минимализма и чистоты. Ставим математический расчет выше креатива. Работаем не покладая рук, как роботы.
            </div>
            <div class="content__block-bottom clearfix">
                <div class="block-bottom--left">
                    <h2 class="block-bottom--h2">Выполняем заказы на разработку:</h2>
                    <ul class="block-bottom--ul">
                        <li>Веб-сайтов любой сложности</li>
                        <li>Мобильных приложений для iOS и Android</li>
                        <li>Слайдшоу и видео для корпоративных презентаций</li>
                    </ul>
                </div>
                <div class="block-bottom--right">
                    <h2 class="block-bottom--h2">Как мы работаем:</h2>
                    <ul class="block-bottom--ul">
                        <li>С самоотдачей 146%</li>
                        <li>Соблюдая сроки на 100%</li>
                        <li>По предоплате 50%</li>
                    </ul>
                </div>
            </div>
        </div>
        <div class="partners">
            <a href="javascript:void(0)"><img src="images/logo-glukhanko.png" alt=""></a>
            <a href="javascript:void(0)"><img src="images/logo-htmlacademy.png" alt=""></a>
            <a href="javascript:void(0)"><img src="images/logo-barbershop.png" alt=""></a>
        </div>
    </div>
<!-- Form Write us -->
    <div class="write-us">
      <form class="contact-form" action="#" method="post">
        <div class="half-width">
          <label for="login-field" class="contact-name">Ваше имя:</label>
          <input type="text" name="login" id="login-field" placeholder="Представьтесь, пожалуйста" required>
        </div>
        <div class="half-width">
          <label for="email-field" class="contact-email">Ваш e-mail:</label>
          <input type="email" name="email" id="email-field" placeholder="Для отправки ответа" required>
        </div>
        <label for="text-field">Текст письма:</label>
        <textarea name="contact-text" id="text-field" rows="4">В свободной форме</textarea>
        <div class="contact-buttons">
          <input class="btn form-submit-btn" type="submit" value="Отправить">
          <input class="btn form-esc-btn write-us-close" type="button" value="Отмена">
        </div>
      </form>
    </div>

<!-- Map -->
    <div class="map">
        <div class="layout-center-wrapper clearfix">
            <div class="map__adds">
                <p class="map__adds--h1"><strong>NЁRDS</strong> DESIGN STUDIO</p>
                <p class="map__adds--p">350000, Краснодар,<br>
                ул. Головатого, 100</p>
                <p class="map__adds--p">тел. +7 (861) 275-75-75</p>
                <a class="btn map__adds--btn" href="#">Напишите нам</a>
            </div>
        </div>
    </div>
<!-- Footer -->
    <footer class="page-footer layout-center-wrapper clearfix">
        <div class="page-footer__btn-social">
            <a href="http://vk.com" class="btn-social btn-social--vk">Вконтакте</a>
            <a href="http://facebook.com" class="btn-social btn-social--fb">Facebook</a>
            <a href="http://instagram.com" class="btn-social btn-social--inst">Instagram</a>
        </div>
        <div class="page-footer__text">
            <span class="page-footer__text-p">Давайте дружить, это выгодно!</span>
            Скидка 10% для друзей из социальных сетей.
        </div>
    </footer>
<script>

  var link = document.querySelector('.map__adds--btn');
  var popup = document.querySelector('.write-us');
  var close = popup.querySelector('.write-us-close');
  var form = popup.querySelector('form');
  var login = form.querySelector('.login-field');
  var password = form.querySelector('.email-field');
  var storage = localStorage.getItem('login');

  link.addEventListener('click', function(event) {
    event.preventDefault();
    popup.classList.add('write-us-show');
    if (storage) {
      login.value = storage;
      email.focus();
    } else {
      login.focus();
    }
  }, false);

  close.addEventListener('click', function(event) {
    event.preventDefault();
    popup.classList.remove('write-us-show');
  }, false);

  form.addEventListener('submit', function(event) {
    if (!login.value || !password.value) {
      event.preventDefault();
      popup.classList.add('login-popup-error');
    } else {
      localStorage.setItem('login', login.value);
    }
  }, false);

  window.addEventListener('keydown', function(event) {
    if (event.keyCode == 27 && popup.classList.contains('write-us-show')) {
      popup.classList.remove('write-us-show');
    }
  }, false);

</script>
</body>
</html>
