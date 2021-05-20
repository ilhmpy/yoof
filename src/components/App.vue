<template>
  <section class="yoof">
    <header class="yoof__header">
      <header class="container header__container">
        <div class="header__nav_bar">
          <span class="nav_bar__item"></span>
        </div>
        <h3 class="nav_inteface__city nav_inteface__city--addaptive_version"><i class="fas fa-map-marker-alt"></i> Москва</h3>
        <div class="header__nav_logo">
          <img src="./static/logo--green.svg" alt="logo">
        </div>
        <div class="header__nav_interface">
          <h3 class="nav_inteface__city"><i class="fas fa-map-marker-alt"></i> Москва</h3>
          <div class="nav_interface__authorization">
            <h3 class="authorization__item">Вход</h3>
            <h3 class="authorization__item">Регистрация</h3>
          </div>
        </div>
        <div class="header__nav_bar header__nav_bar--addaptive_version">
          <span class="nav_bar__item"></span>
        </div>
      </header>
    </header>
    <main class="yoof__banner">
      <main class="container banner__container">
        <div class="yoof__banner_inner">
          <div class="banner_inner__search_box">
            <img src="./static/search.svg" alt="search">
            <input class="banner_inner__search_input" type="text" placeholder="Введите модель техники или воспользуйтесь фильтрами">
            <button class="banner_inner__search_btn focusable--btns">ИСКАТЬ</button>
            <h3 class="banner_inner__add_filter"><img src="./static/add.svg" alt="add">Применить фильтр</h3>
          </div>
          <div class="banner_inner__banner">
            <div class="inner_banner__text_box">
              <h1 class="text_box__title">ЧЕЛОВЕЧНЫЙ МАРКЕТПЛЕЙС</h1>
              <h3 class="text_box__text">Соединяем покупателей и продавцов электроники</h3>
              <button class="inner_banner__btn focusable--btns">О СЕРВИСЕ</button>
            </div>
            <div class="inner_banner__img_box">
              <img src="./static/banner.svg" alt="banner">
            </div>
            <button class="inner_banner__btn inner_banner__btn--addaptive_version focusable--btns">О СЕРВИСЕ</button>
          </div>
          <div class="inner__banner__texts_about">
            <article class="texts_about__text">
              <h3>Устали от поиска нужного товара по выгодной для вас цене?</h3>
              <h3 class="about__text_item">Обошли десятки магазинов и просмотрели сотни страниц в интернете?</h3>
            </article>
            <article class="texts_about__text">
              <h3>На YOOF, продавцы сами готовы предложить вам самую низкую цену. Достаточно просто сообщить им какой товар вы хотите купить,
              и ... запустить аукцион.</h3>
            </article>
          </div>
        </div>
      </main>
    </main>
    <main class="yoof__about_slider">
      <main class="container about_slider__container">
        <article class="about_slider__text">
          <h1 class="yoof__title">КАК ЭТО РАБОТАЕТ?</h1>
          <p class="yoof__about">Помогаем покупателям и продавцам электроники находить друг друга</p>
        </article>
        <div class="about_slider__arrow">
          <i class="fas fa-chevron-right"></i>
        </div>
        <div class="about_slider__arrow">
          <i class="fas fa-chevron-left"></i>
        </div>
        <div class="about_slider__cards">
          <div class="about_slider__cards_truck">
            <div class="about_slider__card">
              <div class="slider_card__img registration_card"></div>
              <div class="slider_card__text_box">
                <div class="slider_card__title_box">
                  <span class="slider_card__number">01</span>
                  <span class="slider_card__title">РЕГИСТРАЦИЯ</span>
                </div>
                <p class="slider_card__text">Зарегистрируйтесь, или войдите в свой личный кабинет</p>
                <div class="slider_card__btns">
                  <button type="button" name="button" class="slider_card__btn">ВХОД</button>
                  <button type="button" name="button" class="slider_card__btn">РЕГИСТРАЦИЯ</button>
                </div>
              </div>
            </div>
          </div>
        </div>
      </main>
    </main>
  </section>
</template>

<script>
  import "./fonts/FontAwesome/css/font-awesome.min.css";
  export default {
    name: 'yoof'
  }

</script>

<style src="normalize.css/normalize.css"></style>
<style src="./ComponentsStyles/app.css"></style>
<style src="./ComponentsStyles/header.css"></style>
<style src="./ComponentsStyles/banner.css"></style>
<style src="./ComponentsStyles/aboutSlider.css"></style>

<style>
    .yoof {
      width: 100%;
    }
</style>
