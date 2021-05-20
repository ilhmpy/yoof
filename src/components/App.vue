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
          <i class="fas fa-chevron-right" data-arrow="right"></i>
        </div>
        <div class="about_slider__arrow">
          <i class="fas fa-chevron-left" data-arrow="left"></i>
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
                <div class="slider_card__img slider_card__img--addaptive_version registration_card"></div>
                <div class="slider_card__btns slider_registration__btns">
                  <button type="button" name="button" class="slider_card__btn slider_registration__btn">ВХОД</button>
                  <button type="button" name="button" class="slider_card__btn slider_registration__btn">РЕГИСТРАЦИЯ</button>
                </div>
              </div>
            </div>
            <div class="about_slider__card">
              <div class="slider_card__img search_card"></div>
              <div class="slider_card__text_box">
                <div class="slider_card__title_box">
                  <span class="slider_card__number">02</span>
                  <span class="slider_card__title" id="search__title">ПОИСК</span>
                </div>
                <p class="slider_card__text" id="search__text">
                    Введите в форму поиска модель нужного вам товара, или подберите его при помощи наших умных фильтров
                </p>
                <div class="slider_card__img slider_card__img--addaptive_version search_card"></div>
                <div class="slider_card__btns focusable--btns" id="search__btns">
                  <button type="button" name="button" class="slider_card__btn" id="search__btn">НАЧАТЬ ПОДБОР</button>
                </div>
              </div>
            </div>
            <div class="about_slider__card">
              <div class="slider_card__img auction_card"></div>
              <div class="slider_card__text_box">
                <div class="slider_card__title_box">
                  <span class="slider_card__number">03</span>
                  <span class="slider_card__title" id="search__title">ПРЕДЛОЖЕНИЕ</span>
                </div>
                <p class="slider_card__text" id="auction__text">
                    Поздравляем, вы почти у цели. Ваша заявка отправлена нашим партнёрам, которые готовы предложить вам лучшую цену.
                    Вы можете видеть сколько продавцов выразили заинтересованность поторговаться, снижая цену на интересующий вас товар
                </p>
                <div class="slider_card__img slider_card__img--addaptive_version auction_card"></div>
                <div class="slider_card__btns focusable--btns" id="search__btns">
                  <button type="button" name="button" class="slider_card__btn" id="search__btn">ЗАПУСТИТЬ АУКЦИОН</button>
                </div>
              </div>
            </div>
            <div class="about_slider__card">
              <div class="slider_card__img paid_card"></div>
              <div class="slider_card__text_box">
                <div class="slider_card__title_box">
                  <span class="slider_card__number">04</span>
                  <span class="slider_card__title" id="search__title">ОПЛАТА</span>
                </div>
                <p class="slider_card__text" id="paid_text">
                    Для запуска аукциона, вам нужно внести необходимую сумму, обычно это минимальная цена
                    на вашу модель, найденная в интернет-магазинах. После того как вы запустите аукцион, продавцы начнут торги
                </p>
                <div class="slider_card__img slider_card__img--addaptive_version paid_card"></div>
                <div class="slider_card__btns focusable--btns" id="search__btns">
                  <button type="button" name="button" class="slider_card__btn" id="search__btn">МОИ ТОРГИ</button>
                </div>
              </div>
            </div>
            <div class="about_slider__card">
              <div class="slider_card__img result_card"></div>
              <div class="slider_card__text_box">
                <div class="slider_card__title_box">
                  <span class="slider_card__number">05</span>
                  <span class="slider_card__title" id="search__title">РЕЗУЛЬТАТ</span>
                </div>
                <p class="slider_card__text" id="paid_text">
                    Ура!!! Торги завершились. Вы можете быть уверены, что купили свой товар по самой лучшей цене.
                    Вам остаётся только дождаться, когда вам привезут вашу покупку
                </p>
                <div class="slider_card__img slider_card__img--addaptive_version result_card"></div>
                <div class="slider_card__btns focusable--btns" id="search__btns">
                  <button type="button" name="button" class="slider_card__btn" id="search__btn">МОИ ЗАКАЗЫ</button>
                </div>
              </div>
            </div>
          </div>
        </div>
      </main>
      <main class="yoof__ourpartners">
        <main class="container ourpartners__container">
          
        </main>
      </main>
    </main>
  </section>
</template>

<script>
  import "./fonts/FontAwesome/css/font-awesome.min.css";
  export default {
    name: 'yoof'
  }

  window.addEventListener("load", e => {
    const width = document.querySelector(".about_slider__card").offsetWidth;
    const truck = document.querySelector(".about_slider__cards_truck");
    const countCards = 1;
    const move = countCards * width;
    const maxTranslate = -5200;

    let position = 0;

    function translate() {
      if (position === maxTranslate) {
        position = 0;
        truck.style.transition = "0.1s";
      } else truck.style.transition = "0.5s";

      if (position === 1040) position = 0;
      truck.style.transform = `translateX(${position}px)`;
    };

    document.querySelectorAll(".about_slider__arrow").forEach(arrow => arrow.addEventListener("click", e => {
      if (e.target.dataset.arrow == "right") {
        position -= move;
        translate();
      };

      if (e.target.dataset.arrow == "left") {
        position += move;
        translate();
      };
    }));
  })
</script>

<style src="normalize.css/normalize.css"></style>
<style src="./ComponentsStyles/app.css"></style>
<style src="./ComponentsStyles/header.css"></style>
<style src="./ComponentsStyles/banner.css"></style>
<style src="./ComponentsStyles/aboutSlider.css"></style>
<style src="./ComponentsStyles/ourPartners.css"></style>

<style>
    .yoof {
      width: 100%;
    }
</style>
