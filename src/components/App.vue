<template>
  <section class="yoof">
    <header class="yoof__header">
      <header class="container header__container">
        <div class="header__nav_bar">
          <span class="nav_bar__item"></span>
        </div>
        <div class="header__nav_logo">
          <img src="./static/logo--green.svg" alt="logo">
        </div>
        <div class="header__nav_interface">
          <h3 class="nav_inteface__city"><i class="fas fa-map-marker-alt"></i> Москва</h3>
        </div>
      </header>
    </header>
    <main class="yoof__banner">

    </main>
  </section>
</template>

<script>
  export default {
    name: 'yoof'
  }
</script>

<style src="normalize.css/normalize.css"></style>
<style src="./ComponentsStyles/app.css"></style>
<style src="./ComponentsStyles/header.css"></style>
<style src="./ComponentsStyles/banner.css"></style>

<style>
    .yoof {
      width: 100%;
    }
</style>
