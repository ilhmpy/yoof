<template>
  <section class="yoof">
    <section class="black_bg">
      <div class="modal__authorization">
        <div class="modal__close authorization__close">
          <span class="modal__close_times"></span>
        </div>
        <div class="authorization__tabs_btns">
          <button type="button" name="button" class="tabs_btns__btn activeTabsBtn" data-tab="registration">РЕГИСТРАЦИЯ</button>
          <button type="button" name="button" class="tabs_btns__btn" data-tab="enter">ВХОД</button>
        </div>
        <div class="authorization__tabs">
          <div class="authorization__tab" data-tab="registration" id="registration_tab">
            <h3 class="authorization_tab__title">ЗАРЕГИСТРИРОВАТЬСЯ КАК</h3>
            <div class="autorization_tab__checkeds">
              <div class="tab_checkeds__checked activeChecked" data-type="payer"><span></span>Покупатель</div>
              <div class="tab_checkeds__checked" data-type="seller"><span></span> Продавец (юридическое лицо)</div>
            </div>
            <div class="authorization__registration_tabs">
              <div class="registration_tabs__tab" data-type="payer">
                <div class="registration__row_inputs">
                  <div class="row_inputs__box">
                    <label class="row_inputs__description">Фамилия</label>
                    <input type="text" class="row_inputs__input">
                  </div>
                  <div class="row_inputs__box">
                    <label class="row_inputs__description">Имя</label>
                    <input type="text" class="row_inputs__input">
                  </div>
                  <div class="row_inputs__box">
                    <label class="row_inputs__description">Отчество</label>
                    <input type="text" class="row_inputs__input">
                  </div>
                </div>
                <div class="registration__row_inputs">
                  <div class="row_inputs__box">
                    <label class="row_inputs__description">Телефон</label>
                    <input type="text" class="row_inputs__input">
                  </div>
                  <div class="row_inputs__box">
                    <label class="row_inputs__description">Адрес электронной почты</label>
                    <input type="text" class="row_inputs__input">
                  </div>
                  <div class="row_inputs__box">
                    <label class="row_inputs__description">Пароль <span class="description__forgot">Забыли пароль?</span></label>
                    <input type="text" class="row_inputs__input">
                  </div>
                </div>
                <button type="button" name="button" class="registration__btn focusable--btns">ЗАРЕГИСТРИРОВАТЬСЯ</button>
                <h3 class="registration__subtitle">Или авторизуйтесь через аккаунт в социальной сети</h3>
                <p class="registration__socials">
                  <img src="./static/google_socials.svg" alt="google">
                  <img src="./static/vk_socials.svg" alt="vk">
                  <img src="./static/facebook_socials.svg" alt="facebook">
                </p>
              </div>
              <div class="registration_tabs__tab" data-type="seller" style="display: none">
                <div class="registration__row_inputs">
                  <div class="row_inputs__box">
                    <label class="row_inputs__description" id="description--addaptive">Название организации или ИП</label>
                    <input type="text" class="row_inputs__input">
                  </div>
                  <div class="row_inputs__box">
                    <label class="row_inputs__description">Юридический адрес</label>
                    <input type="text" class="row_inputs__input">
                  </div>
                  <div class="row_inputs__box">
                    <label class="row_inputs__description">ИНН</label>
                    <input type="text" class="row_inputs__input">
                  </div>
                </div>
                <div class="registration__row_inputs">
                  <div class="row_inputs__box">
                    <label class="row_inputs__description">Банк</label>
                    <input type="text" class="row_inputs__input">
                  </div>
                  <div class="row_inputs__box">
                    <label class="row_inputs__description">Расчетный счет</label>
                    <input type="text" class="row_inputs__input">
                  </div>
                  <div class="row_inputs__box">
                    <label class="row_inputs__description">КПП</label>
                    <input type="text" class="row_inputs__input">
                  </div>
                </div>
                <div class="registration__row_inputs">
                  <div class="row_inputs__box">
                    <label class="row_inputs__description">БИК банка</label>
                    <input type="text" class="row_inputs__input">
                  </div>
                  <div class="row_inputs__box">
                    <label class="row_inputs__description">Адрес электронной почты</label>
                    <input type="text" class="row_inputs__input">
                  </div>
                  <div class="row_inputs__box">
                    <label class="row_inputs__description">Пароль <span class="description__forgot">Забыли пароль?</span></label>
                    <input type="text" class="row_inputs__input">
                  </div>
                </div>
                <button type="button" name="button" class="registration__btn focusable--btns">ЗАРЕГИСТРИРОВАТЬСЯ</button>
              </div>
            </div>
          </div>
          <div class="authorization__tab" data-tab="enter" style="display: none">
            <h3 class="authorization_tab__title">ВОЙТИ КАК</h3>
            <div class="autorization_tab__checkeds">
              <div class="tab_checkeds__checked activeChecked" data-type="enter-payer"><span></span>Покупатель</div>
              <div class="tab_checkeds__checked" data-type="enter-seller"><span></span> Продавец (юридическое лицо)</div>
            </div>
            <div class="authorization__enter_tabs">
              <div class="authorization__enter_tab" data-type="enter-payer">
                <div class="registration__row_inputs enter__tabs_rows">
                  <div class="row_inputs__box">
                    <label class="row_inputs__description">Адрес электронной почты</label>
                    <input type="text" class="row_inputs__input">
                  </div>
                  <div class="row_inputs__box">
                    <label class="row_inputs__description">Пароль <span class="description__forgot">Забыли пароль?</span></label>
                    <input type="text" class="row_inputs__input">
                  </div>
                </div>
                <button type="button" name="button" class="registration__btn focusable--btns">ВОЙТИ</button>
                <h3 class="registration__subtitle">Или авторизуйтесь через аккаунт в социальной сети</h3>
                <p class="registration__socials">
                  <img src="./static/google_socials.svg" alt="google">
                  <img src="./static/vk_socials.svg" alt="vk">
                  <img src="./static/facebook_socials.svg" alt="facebook">
                </p>
              </div>
              <div class="authorization__enter_tab" data-type="enter-seller" style="display: none">
                <div class="registration__row_inputs enter__tabs_rows">
                  <div class="row_inputs__box">
                    <label class="row_inputs__description">Адрес электронной почты</label>
                    <input type="text" class="row_inputs__input">
                  </div>
                  <div class="row_inputs__box">
                    <label class="row_inputs__description">Пароль <span class="description__forgot">Забыли пароль?</span></label>
                    <input type="text" class="row_inputs__input">
                  </div>
                </div>
                <button type="button" name="button" class="registration__btn focusable--btns">ВОЙТИ</button>
                <h3 class="registration__subtitle">Или авторизуйтесь через аккаунт в социальной сети</h3>
                <p class="registration__socials">
                  <img src="./static/google_socials.svg" alt="google">
                  <img src="./static/vk_socials.svg" alt="vk">
                  <img src="./static/facebook_socials.svg" alt="facebook">
                </p>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="modal__enter_email">
        <div class="modal__close authorization__close">
          <span class="modal__close_times"></span>
        </div>
        <h3 class="enter_email__title">ВВЕДИТЕ АДРЕС ЭЛЕКТРОННОЙ ПОЧТЫ</h3>
        <div class="row_inputs__box enter_email__inputs_box">
          <label class="row_inputs__description">Адрес электронной почты</label>
          <input type="text" class="row_inputs__input">
        </div>
        <button type="button" name="button" class="registration__btn focusable--btns">ВОССТАНОВИТЬ ПАРОЛЬ</button>
      </div>
      <div class="modal__message_send_email">
        <div class="modal__close authorization__close">
          <span class="modal__close_times"></span>
        </div>
        <h3 class="enter_email__title message_send_email__title">ВОССТАНОВЛЕНИЕ ПАРОЛЯ</h3>
        <article class="message_send_email__massage_box">
          <p>Мы отправили письмо со ссылкой для смены пароля на указанный Вами при регистрации адрес.</p>
          <p>Для смены пароля перейдите по ссылке из письма и введите новый пароль.</p>
        </article>
      </div>
      <div class="modal__change_password">
        <div class="modal__close authorization__close">
          <span class="modal__close_times"></span>
        </div>
        
      </div>
    </section>
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
    </main>
    <main class="yoof__ourpartners">
      <main class="container ourpartners__container">
        <div class="ourpartners__text_box">
          <h1 class="ourpartners__title">НАШИ ПАРТНЕРЫ</h1>
          <p class="ourpartners__text">Мы сотрудничаем с самыми популярными брендами</p>
        </div>
        <div class="ourpartners__companies_cards">
          <div class="companies_cards__truck">
            <img src="./static/Samsung.svg" alt="samsung" class="cards_truck__item">
            <img src="./static/Apple.svg" alt="apple" class="cards_truck__item">
            <img src="./static/Indesit.svg" alt="indesit" class="cards_truck__item">
            <img src="./static/LG.svg" alt="lg" class="cards_truck__item">
            <img src="./static/ASUS.svg" alt="asus" class="cards_truck__item">
            <img src="./static/BEKO.svg" alt="beko" class="cards_truck__item">
          </div>
        </div>
      </main>
    </main>
    <main class="yoof__our_advantages">
      <main class="container our_advantages__container">
        <div class="our_advantages__title_box">
          <h1 class="our_advantages__title">ПРЕИМУЩЕСТВА СЕРВИСА</h1>
          <p class="our_advantages__text">На нашем сервисе есть широкие возможности для покупателей и продавцов</p>
        </div>
        <div class="our_advantages__cards">
          <div class="our_advantages__card">
            <div class="our_advantages_card__img">
              <img src="./static/time_advant_card.svg" alt="time">
            </div>
            <div class="our_advantages_card__content">
              <h2 class="card_content__title">ЭКОНОМИЯ ВРЕМЕНИ</h2>
              <p class="card_content__text">Вам не нужно тратить время на посещение магазинов в поиске нужного товара</p>
            </div>
          </div>
          <div class="our_advantages__card">
            <div class="our_advantages_card__img">
              <img src="./static/money_advant_card.svg" alt="money">
            </div>
            <div class="our_advantages_card__content">
              <h2 class="card_content__title">ЭКОНОМИЯ ДЕНЕГ</h2>
              <p class="card_content__text">Вы приобретаете товар по минимальной цене</p>
            </div>
          </div>
          <div class="our_advantages__card">
            <div class="our_advantages_card__img">
              <img src="./static/service_advant_card.svg" alt="service">
            </div>
            <div class="our_advantages_card__content">
              <h2 class="card_content__title">ЧЕСТНЫЙ СЕРВИС</h2>
              <p class="card_content__text">
                Yoof – место, где покупатели знают, что сделанные им предложения абсолютно честны, и условия будут исполнены
                магазинами так, как они это обещали
              </p>
            </div>
          </div>
          <div class="our_advantages__card">
            <div class="our_advantages_card__img">
              <img src="./static/care_advant_card.svg" alt="care">
            </div>
            <div class="our_advantages_card__content">
              <h2 class="card_content__title">ЗАБОТА О КЛИЕНТАХ</h2>
              <p class="card_content__text">
                Мы стоим на стороне покупателей, и будем делать все, что в наших силах, для того,
                чтобы покупатели были довольны.
              </p>
            </div>
          </div>
        </div>
      </main>
    </main>
    <main class="yoof__our_popular_news">
      <main class="container our_popular_news__container">
        <div class="our_popular_news__title_box">
          <h1 class="our_popular_news__title">ПОПУЛЯРНЫЕ НОВОСТИ</h1>
          <p class="our_popular_news__text">Статьи, обзоры, новости рынка</p>
        </div>
        <div class="our_popular_news__cards">
          <div class="our_popular_news__card">
            <img src="./static/news1.svg" alt="news1">
          </div>
          <div class="our_popular_news__card">
            <img src="./static/news2.svg" alt="news2">
          </div>
          <div class="our_popular_news__card">
            <img src="./static/news3.svg" alt="news3">
          </div>
        </div>
        <button type="button" name="button" class="our_popular_news__btn focusable--btns">ЧИТАТЬ ВСЕ НОВОСТИ</button>
      </main>
    </main>
    <footer class="yoof__footer">
      <footer class="container footer__container">
        <img src="./static/logo--yellow.svg" alt="logo--yellow" class="footer__yellow_logo">
        <div class="footer__links_box">
          <ul class="footer__links">
            <li class="footer__links_title">О СЕРВИСЕ</li>
            <li class="footer__links_link"><a href="#">Как работает сервис?</a></li>
            <li class="footer__links_link"><a href="#">Правила использования</a></li>
            <li class="footer__links_link"><a href="#">Отзывы о нас</a></li>
          </ul>
          <ul class="footer__links">
            <li class="footer__links_title">Контакты</li>
            <li class="footer__links_link"><a href="#"><i class="fab fa-instagram"></i> INSTAGRAM</a></li>
            <li class="footer__links_link"><a href="#"><i class="fab fa-facebook"></i> FACEBOOK</a></li>
            <li class="footer__links_link"><a href="#"><i class="fab fa-telegram"></i> TELEGRAM</a></li>
          </ul>
        </div>
      </footer>
    </footer>
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
    const companiesCardsTruck = document.querySelector(".companies_cards__truck");
    const tabsBtns = document.querySelectorAll(".tabs_btns__btn");
    const checkedBtns = document.querySelectorAll(".tab_checkeds__checked");
    const checkedTabs = document.querySelectorAll(".registration_tabs__tab");
    const authorizationTabs = document.querySelectorAll(".authorization__tab");
    const enterTabs = document.querySelectorAll(".authorization__enter_tab");

    let moveCompanies = false;
    let position = 0;
    let initialPosition = 0;
    let positionX1 = 0;
    let positionX2 = 0;
    let transform = 0;
    let finalPosition = 0;
    let regPx = /[-0-9.]+(?=px)/;

    companiesCardsTruck.style.transform = "translate3d(0px, 0px, 0px)";

    class DOM {
      show(selector) {
        if (typeof selector == "string") {
          document.querySelectorAll(selector).forEach(sel => sel.style.display = "block")
        } else selector.style.display = "block";
      };

      hide(selector) {
        if (typeof selector == "string") document.querySelectorAll(selector).forEach(sel => sel.style.display = "none");
        else selector.style.display = "none";
      };

      addClass(selector, className) {
        if (typeof selector == "string") document.querySelectorAll(selector).forEach(item => item.classList.add(className))
        else selector.classList.add(className);
      };

      removeClass(selector, className) {
        if (typeof selector == "string") document.querySelectorAll(selector).forEach(item => item.classList.remove(className))
        else selector.classList.remove(className)
      };

      css(selector, object = {}) {
        selector.style = object;
      };
    };

    const $ = new DOM();

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

    if (screen.width < 481) document.addEventListener("touchstart", touchStart);

    function touchMove(e) {
      if (moveCompanies) {
        transform = companiesCardsTruck.style.transform.match(regPx)[0];
        positionX2 = positionX1 - e.touches[0].clientX;
        positionX1 = e.touches[0].clientX;
        companiesCardsTruck.style.transform = `translate3d(${transform - positionX2}px, 0px, 0px)`;
      };
    };

    function touchStart(e) {
      initialPosition = e.touches[0].pageX;
      initialPosition = positionX1 = e.touches[0].clientX;

      moveCompanies = true;
      document.addEventListener("touchmove", touchMove);
      document.addEventListener("touchend", touchEnd);
    };

    function touchEnd(e) {
      moveCompanies = false;
      finalPosition = companiesCardsTruck.style.transform.match(regPx)[0];
      document.removeEventListener("touchmove", touchMove);
      document.removeEventListener("touchend", touchEnd);
    };

    document.querySelectorAll(".tabs_btns__btn").forEach(btn => btn.addEventListener("click", e => {
      if (e.target.className == "tabs_btns__btn") {
        tabsBtns.forEach(btn => $.removeClass(btn, "activeTabsBtn"));
        $.addClass(e.target, "activeTabsBtn");
        authorizationTabs.forEach(tab => {
          $.hide(tab);
          if (tab.dataset.tab == e.target.dataset.tab) $.show(tab);
        });
      };
    }));

    document.querySelectorAll(".tab_checkeds__checked").forEach(checked => checked.addEventListener("click", e => {
      if (e.target.className == "tab_checkeds__checked") {
        checkedBtns.forEach(checked => checked.classList.remove('activeChecked'));
        e.target.classList.add("activeChecked");
        checkedTabs.forEach(tab => {
          $.hide(tab);
          if (tab.dataset.type == e.target.dataset.type) $.show(tab);
        });

        enterTabs.forEach(tab => {
          $.hide(tab);
          if (tab.dataset.type == e.target.dataset.type) $.show(tab);
        });
      };
    }));

    document.querySelector(".authorization__close").addEventListener("click", e => {
      $.hide(".black_bg");
      $.hide(".modal__authorization");
    });

    document.querySelector(".nav_interface__authorization").addEventListener("click", e => {
      $.show(".black_bg");
      $.show(".modal__authorization");
    });
  });
</script>

<style src="normalize.css/normalize.css"></style>
<style src="./ComponentsStyles/app.css"></style>
<style src="./ComponentsStyles/ourAdvantages.css"></style>
<style src="./ComponentsStyles/ourPopularNews.css"></style>
<style src="./ComponentsStyles/footer.css"></style>
<style src="./ComponentsStyles/modals.css"></style>

<style>
    .yoof {
      width: 100%;
    }
</style>
