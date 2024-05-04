<template>
  <div>
  
    <div class="preloader-wrapper">
    <div class="preloader">
    </div>
  </div>

  <nav class="navbar navbar-expand-lg navbar-light bg-light fixed-top py-4">
    <div class="container-fluid">
      <div class="main-logo">
        <a href="index.html">
          <img src="../assets/images/main-logo.png" alt="logo">
        </a>
      </div>
      <button class="navbar-toggler" type="button" data-bs-toggle="offcanvas" data-bs-target="#offcanvasNavbar"
        aria-controls="offcanvasNavbar">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="offcanvas offcanvas-end" tabindex="-1" id="offcanvasNavbar" aria-labelledby="offcanvasNavbarLabel">
        <div class="offcanvas-header">
          <h5 class="offcanvas-title" id="offcanvasNavbarLabel">Menu</h5>
          <button type="button" class="btn-close text-reset" data-bs-dismiss="offcanvas" aria-label="Close"></button>
        </div>
        <div class="offcanvas-body">
          <ul class="navbar-nav justify-content-end align-items-center flex-grow-1 pe-3 gap-4">
            <li class="nav-item text-uppercase">
              <a href="#" class="nav-link active">Главная</a>
            </li>
            <li class="nav-item text-uppercase">
              <a href="blog.html" class="nav-link">Танцы</a>
            </li>
            <li class="nav-item dropdown">
              <a class="nav-link dropdown-toggle" href="#" id="dropdownPages" data-bs-toggle="dropdown"
                aria-haspopup="true" aria-expanded="false">Школа</a>
              <ul class="dropdown-menu" aria-labelledby="dropdownPages">
                <li>
                  <a href="about.html" class="dropdown-item text-uppercase">Контакты</a>
                </li>
                <li>
                  <a href="classes.html" class="dropdown-item text-uppercase">Танцы </a>
                </li>
                <li>
                  <a href="shop.html" class="dropdown-item text-uppercase">Наставники</a>
                </li>
              </ul>
            </li>
            <li class="nav-item text-uppercase">
              <a href="shop.html" class="nav-link">Цены</a>
            </li>
            <li class="nav-item text-uppercase">
              <a href="contact.html" class="nav-link">Контакты</a>
            </li>
            <li class="nav-item text-uppercase">
              <a href="https://templatesjungle.gumroad.com/l/dance-html-website-template" target="_blank"
                class="item-anchor btn btn-outline-primary rounded-pill">Записаться</a>
            </li>
            <li class="user-items">
              <div class="search-bar">
                <a href="#" class="search-button search-toggle" data-selector=".primary-nav">
                  <i class="icon icon-search"></i>
                </a>
                <form role="search" method="get" class="search-box" action="index.html">
                  <input class="search-field search-input" placeholder="Search" type="search">
                </form>
              </div>
            </li>
          </ul>
        </div>
      </div>
    </div>
  </nav>

  <section id="hero-section" class="text-center jarallax mt-5 py-5">
    <img src="../assets/images/dance-banner3.jpg" alt="dancer" class="jarallax-img">
    <div class="banner-content py-5 my-5">
      <div class="container">
        <div class="row justify-content-center">
          <div class="col-md-6">
            <h1 class="text-white display-1 mt-5">Лунный свет</h1>
            <span class="text-white">Здесь вы быстро научитесь двигаться под романтичные ритмы бачаты или сможете закрутиться в страстном порыве кубинской сальсы. Обжигающей, как острый соус. </span>
            <div class="buttons d-flex flex-wrap justify-content-center gap-3 my-4">
              <a href="#" class="btn btn-medium btn-primary rounded-pill">Расписание</a>
              <a href="#" class="btn btn-medium btn-dark rounded-pill">Запись</a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <section id="about-us" class="padding-large">
    <div class="container">
      <div class="row align-items-center">
        <div class="col-md-6">
          <img src="../assets/images/introimg.png" alt="image" class="img-fluid">
        </div>
        <div class="col-md-6">
          <div class="block-text">
            <h2 class="section-title" data-aos="fade-up" data-aos-delay="0">
              <span class="text-primary">Школа танцев</span> Лунный свет
            </h2>
            <p data-aos="fade-up" data-aos-delay="100">Индивидуальный подход. Не на словах, а на деле — в небольших группах вы никогда не останетесь без внимания наставника. Группы набираются по 6-8 человек, что гарантирует комфортное и эффективное обучение в большом, чистом и красивом танцевальном зале в центре города.</p>
            <p data-aos="fade-up" data-aos-delay="100">Доступность и легкость. Наша цель — не собрать с вас максимум денег за минимум информации, а научить танцу и свободу движений под теплые звуки Кубы и Доминиканы. Понятная и простая подача материала, практика и позитивное настроение на уроках — то, что отличает нас от формального подхода других школ.</p>
            <div class="btn-left" data-aos="fade-up" data-aos-delay="200">
              <a href="about.html" class="btn btn-outline-primary btn-pill btn-medium">Контакты</a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <section id="videos">
    <div class="container-fluid">
      <div class="row">
        <div class="section-header">
          <h2 class="section-title text-center">
            <span class="text-primary">Обучаем</span> Танцам
          </h2>
        </div>
        <div class="row">
          <div class="col-md-6">
            <div class="class-item" data-aos="fade" data-aos-delay="0">
              <figure>
                <img src="../assets/images/video-item.jpg" alt="video">
                <figcaption class="p-5 text-white">
                  <h2 class="text-white m-0">Сальса</h2>
                  <p class="m-0">В школе танцев “Лунный свет” вы научитесь именно кубинской сальсе (касино)</p>
                  <a href="#" class="btn btn-outline-light rounded-pill">Записаться</a>
                </figcaption>
              </figure>
            </div>
          </div>
          <div class="col-md-6">
            <div class="class-item" data-aos="fade" data-aos-delay="100">
              <figure>
                <img src="../assets/images/video-item1.jpg" alt="video">
                <figcaption class="p-5 text-white">
                  <h2 class="text-white m-0">Бачата</h2>
                  <p class="m-0">Парень с девушкой очень близко танцуют друг с другом. Плавно, волнообразно в едином ритме и порыве пара ведет молчаливый диалог между мужчиной и женщиной. </p>
                  <a href="#" class="btn btn-outline-light rounded-pill">Записаться</a>
                </figcaption>
              </figure>
            </div>
          </div>
        </div>
        <div class="row">
          <div class="col-md-4">
            <div class="class-item" data-aos="fade" data-aos-delay="200">
              <figure>
                <img src="../assets/images/video-item2.jpg" alt="video">
                <figcaption class="p-5 text-white">
                  <h2 class="text-white m-0">Меренге</h2>
                  <p class="m-0">На Кубе говорят: если вы можете ходить, то значит, вы уже танцуете меренге.</p>
                  <a href="#" class="btn btn-outline-light rounded-pill">Записаться</a>
                </figcaption>
              </figure>
            </div>
          </div>
          <!-- <div class="col-md-4">
            <div class="class-item" data-aos="fade" data-aos-delay="300">
              <figure>
                <img src="../assets/images/video-item3.jpg" alt="video">
                <figcaption class="p-5 text-white">
                  <h2 class="text-white m-0">Ballet</h2>
                  <p class="m-0">Lorem consequatur eligendi vel esse culpa repudiandae</p>
                  <a href="#" class="btn btn-outline-light rounded-pill">Register Now</a>
                </figcaption>
              </figure>
            </div>
          </div>
          <div class="col-md-4">
            <div class="class-item" data-aos="fade" data-aos-delay="400">
              <figure>
                <img src="../assets/images/video-item4.jpg" alt="video">
                <figcaption class="p-5 text-white">
                  <h2 class="text-white m-0">Musical Theatre</h2>
                  <p class="m-0">Lorem consequatur eligendi vel esse culpa repudiandae</p>
                  <a href="#" class="btn btn-outline-light rounded-pill">Register Now</a>
                </figcaption>
              </figure>
            </div>
          </div> -->
        </div>
      </div>
    </div>
  </section>

  <section class="my-2 py-2 my-lg-5 py-lg-5">
    <div class="container">
      <h2>Цены</h2>
      <div class="table-responsive">
        <table class="table table-striped
        table-hover	
        table-borderless
        align-middle">
          <thead>
            <tr>
              <th>Заняние</th>
              <th>Кол-во</th>
              <th>Цена</th>
              <th>Запись</th>
            </tr>
          </thead>
          <tbody class="table-group-divider">
            <tr>
              <td><strong>Группа 4-8 человек</strong></td>
              <td>1</td>
              <td>700₽</td>
              <td><a href="#" class="btn btn-outline-dark rounded-pill">Записаться</a></td>
            </tr>
            <tr>
              <td><strong>Группа 4-8 человек</strong></td>
              <td>4</td>
              <td>2600₽</td>
              <td><a href="#" class="btn btn-outline-dark rounded-pill">Записаться</a></td>
            </tr>
            <tr>
              <td><strong>Индивидуальное</strong></td>
              <td>1</td>
              <td>2300₽</td>
              <td><a href="#" class="btn btn-outline-dark rounded-pill">Записаться</a></td>
            </tr>
          </tbody>
          <tfoot>

          </tfoot>
        </table>
      </div>

    </div>
  </section>

  <section class="inspiring-quote bg-light-grey padding-large">
    <div class="container">
      <div class="row">
        <div class="section-header text-center">
          <h2 class="section-title">
            <span class="text-primary">Кирилл </span> Кобзарь
          </h2>
        </div>
        <div class="quotation">
          <blockquote class="blockquote align-center">
            <p>"Открыл для себя танцы в 2010 году. Владеет следующими направлениями латиноамериканской программы: сальса, бачата и меренге. Они пришли с островов Кубы и Доминиканы. Учился у настоящих кубинцев, поэтому с его помощью вы сможете танцевать так, как это делают на побережье Карибского моря."</p>
            <span class="author">-Учитель танцев</span>
          </blockquote>
        </div>
      </div>
    </div>
  </section>

  <section id="blog" class="latest-blogs padding-large">
    <div class="container">
      <div class="section-header text-center">
        <h2 class="section-title">
          <span class="text-primary">Читайте</span> Новости
        </h2>
      </div>
      <div class="row">
        <div class="col-md-4">
          <div class="post-item" data-aos="fade" data-aos-delay="0">
            <figure class="zoom-effect">
              <img src="../assets/images/post-item1.jpg" alt="postitem" class="blog-image">
            </figure>
            <div class="post-content">
              <div class="meta-tags">
                <span class="meta-date">Опубликовано Мая 1, 2024</span>
              </div>
              <h3 class="post-title">
                <a href="single-post.html">Почему тебе это нужно</a>
              </h3>
              <p>О, мы знаем, ты давно хочешь научиться танцевать так, чтобы собирать восторженные взгляды на вечеринках. <a href="#" class="link">Далее</a>
              </p>
            </div>
          </div>
        </div>
        <div class="col-md-4">
          <div class="post-item" data-aos="fade" data-aos-delay="100">
            <figure class="zoom-effect">
              <img src="../assets/images/post-item2.jpg" alt="postitem" class="blog-image">
            </figure>
            <div class="post-content">
              <div class="meta-tags">
                <span class="meta-date">Опубликовано Мая 2, 2024</span>
              </div>
              <h3 class="post-title">
                <a href="single-post.html">Почему тебе к нам</a>
              </h3>
              <p>Во-первых, потому что мы давно в танцах, любим их и хотим собирать вокруг себя таких же открытых к новому единомышленников.
 <a href="#" class="link">Далее</a>
              </p>
            </div>
          </div>
        </div>
        <div class="col-md-4">
          <div class="post-item" data-aos="fade" data-aos-delay="200">
            <figure class="zoom-effect">
              <img src="../assets/images/post-item3.jpg" alt="postitem" class="blog-image">
            </figure>
            <div class="post-content">
              <div class="meta-tags">
                <span class="meta-date">Опубликовано Мая 3, 2024</span>
              </div>
              <h3 class="post-title">
                <a href="single-post.html">Кто будет учить</a>
              </h3>
              <p>Кирилл Кобзарь — танцор с преподавательским стажем более 16 лет. Обучался технике у преподавателей России (Москва, Екатеринбург), Кубы и Турции. <a href="#" class="link">Далее</a>
              </p>
            </div>
          </div>
        </div>
      </div>
      <div class="btn-center">
        <a href="blog.html" class="btn btn-outline-primary btn-pill btn-medium">Читать все новости</a>
      </div>
    </div>
  </section>

  <section id="newsletter" class="newsletter padding-large no-padding-top">
    <div class="container position-relative">
      <div class="row justify-content-center">
        <div class="col-md-4">
          <div class="image-holder">
            <img src="../assets/images/newsletterimg.png" alt="dancer" class="newsletter-image">
          </div>
        </div>
        <div class="col-md-6">
          <div class="form-content">
            <div class="section-header">
              <h2 class="section-title text-center mb-0">
                <span class="text-primary">Записаться</span> Бесплатно
              </h2>
            </div>
            <form id="form">
              <input type="text" name="fullname" placeholder="Введите имя" data-name="fullname"
                class="bg-light u-full-width">
              <input type="text" name="email" placeholder="Введите номер телефона" required="" data-name="email"
                class="bg-light u-full-width">
              <div class="btn-submit align-center">
                <button class="submit btn btn-pill btn-medium btn-primary btn-full" type="submit">Отправить</button>
              </div>
            </form>
          </div>
        </div>
      </div>
    </div>
  </section>

  <section id="instagram">
    <div class="section-header text-center">
      <h2 class="section-title">
        <span class="text-primary">Наши</span> Фото
      </h2>
    </div>
    <div class="container-fluid">
      <div class="row">
        <div class="instagram-content d-flex flex-wrap justify-content-center">
          <div class="col-md-2 col-sm-4">
            <figure class="zoom-effect magnific">
              <a href="../assets/images/largeitem1.jpg">
                <img src="../assets/images/item1.jpg" alt="instagram">
                <div class="icon-overlay">
                  <i class="icon icon-instagram1"></i>
                </div>
              </a>
            </figure>
          </div>
          <div class="col-md-2 col-sm-4">
            <figure class="zoom-effect magnific">
              <a href="../assets/images/largeitem2.jpg">
                <img src="../assets/images/item2.jpg" alt="instagram">
                <div class="icon-overlay">
                  <i class="icon icon-instagram1"></i>
                </div>
              </a>
            </figure>
          </div>
          <div class="col-md-2 col-sm-4">
            <figure class="zoom-effect magnific">
              <a href="../assets/images/largeitem3.jpg">
                <img src="../assets/images/item3.jpg" alt="instagram">
                <div class="icon-overlay">
                  <i class="icon icon-instagram1"></i>
                </div>
              </a>
            </figure>
          </div>
          <div class="col-md-2 col-sm-4">
            <figure class="zoom-effect magnific">
              <a href="../assets/images/largeitem4.jpg">
                <img src="../assets/images/item4.jpg" alt="instagram">
                <div class="icon-overlay">
                  <i class="icon icon-instagram1"></i>
                </div>
              </a>
            </figure>
          </div>
          <div class="col-md-2 col-sm-4">
            <figure class="zoom-effect magnific">
              <a href="../assets/images/largeitem5.jpg">
                <img src="../assets/images/item5.jpg" alt="instagram">
                <div class="icon-overlay">
                  <i class="icon icon-instagram1"></i>
                </div>
              </a>
            </figure>
          </div>
          <div class="col-md-2 col-sm-4">
            <figure class="zoom-effect magnific">
              <a href="../assets/images/largeitem6.jpg">
                <img src="../assets/images/item6.jpg" alt="instagram">
                <div class="icon-overlay">
                  <i class="icon icon-instagram1"></i>
                </div>
              </a>
            </figure>
          </div>
        </div>
      </div>
    </div>
  </section>
  <footer id="footer" class="padding-large">
    <div class="container">
      <div class="footer-content row">
        <div class="col-md-4">
          <div class="footer-menu">
            <ul class="d-flex list-unstyled justify-content-md-start justify-content-center">
              <li>
                <a href="#"></a>
              </li>
              <li>
                <a href="https://disk.yandex.com/d/zwn6vvhLRf2nag">Лицензионное соглашение</a>
              </li>
              <li>
                <a href="#"></a>
              </li>
            </ul>
          </div>
        </div>
        <div class="col-md-4">
          <div class="footer-logo align-center">
          </div>
        </div>
        <div class="col-md-4">
          <div class="social-links">
            <ul class="d-flex list-unstyled justify-content-md-end justify-content-center">
              <li>
                <a href="#">
                  <i class="icon icon-instagram"></i>
                </a>
              </li>
              <li>
                <a href="https://vk.com/kkobzar87">
                  vk
                </a>
              </li>
              <li>
                <a href="#">
                  <i class="icon icon-youtube"></i>
                </a>
              </li>
            </ul>
          </div>
        </div>
      </div>
    </div>
  </footer>
  <div id="footer-bottom">
    <div class="container">
      <div class="copyright align-center">
        <p>Полный доступ, после <a target="_blank" href="https://disk.yandex.com/d/zwn6vvhLRf2nag">подписания соглашения</a></p>
      </div>
    </div>
  </div>
  </div>

</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
