<!-- Please remove this file from your project -->
<template>
    <div class="blackgd">
    <!-- <link rel="stylesheet" href="/scss/style.scss"> -->
      <div class="top_bar">
        <div class="logo">
          <img src="/image/askmedemo.jpg" width="320" height="80" />
        </div>
        <div class="group_menu d-flex">
          <a class="cursor_pointer example">
            <div class="outside_menu">
              <div class="inside_menu d-flex">
                <img class="icon_intro" src="https://sale3.pirate168.com/images/icon_intro_lotto.png" alt="">
                <div class="text-gold link_intro">เข้าแทงหวย</div>
              </div>
            </div>
          </a>
          <a class="cursor_pointer register">
            <div class="outside_menu">
              <div class="inside_menu d-flex">
                <img class="icon_regis" src="https://sale3.pirate168.com/images/icon_regis_lotto.png" alt="">
                <div class="text-gold link_intro">สมัครสมาชิก</div>
              </div>
            </div>
          </a>
        </div>
      </div>
      <header>
        <nav>
          <nuxt-link class="active" to="/">หน้าแรก</nuxt-link>
          <nuxt-link to="/playgame">เข้าเล่นเกมส์</nuxt-link>
          <nuxt-link to="/chek">วิธีเช็ครางวัลหวย</nuxt-link>
          <nuxt-link to="/promotion">โปรโมชั่น</nuxt-link>
          <nuxt-link to="/article">บทความ</nuxt-link>
          <nuxt-link to="/login">เข้าสู่ระบบ</nuxt-link>
        </nav>
      </header>
  
      <div id="carouselExampleInterval" class="carousel slide" data-bs-ride="carousel">
        <div class="carousel-inner">
          <div class="carousel-item active" data-bs-interval="10000">
            <img src="https://sale3.pirate168.com/images/core_slide.png" class="d-block w-100" alt="...">
          </div>
          <div class="carousel-item active" data-bs-interval="5000">
            <img src="https://sale3.pirate168.com/images/slide_1.png" class="d-block w-100" alt="...">
          </div>
          <div class="carousel-item active" data-bs-interval="5000">
            <img src="https://sale3.pirate168.com/images/slide_2.png" class="d-block w-100" alt="...">
          </div>
        </div>
      </div>
      <div class="slide_announce large">
        <div class="announce text-gold">
          ประกาศจากเว็บ :
        </div>
        <marquee loop="infinite">ยินดีต้อนรับเข้าสู่เว็บแทงหวยออนไลน์ <b><span class="text-yello">AMBLOTTO.COM
            </span></b><span class="line-announce">Line ID : @amblotto.vip</span>
        </marquee>
      </div>

    </div>
  </template>
  
  <script>
  export default {
    name: 'NuxtTopBar',
  }
  </script>
  
  <style>
  
  /* เมนู */
  nav {
    /* margin: 25px auto; */
    display: flex;
    justify-content: center;
    align-items: center;
    background-color: #262626;
    font-size: 1.25rem;
    /* background: #262626; */
    border-bottom: 2px solid #fbf995;
  }
  
  nav a {
    color: #FBF995;
    text-decoration: none;
    margin-left: 12px;
    font-size: 18px;
    padding: 14px;
    display: flex;
    /* background: #262626; */
  }
  
  nav a:hover {
    color: #000;
    background: #FBF995;
  }
  
  nuxt-link.active {
    background-color: #FBF995;
    color: #000;
  }
  
  /* Topbar */
  div.top_bar {
    display: flex;
    padding: 2rem 0;
    justify-content: space-around;
  }
  
  div.outside_menu:nth-child(1) {
    margin-right: 0.5rem;
  }
  
  div.outside_menu {
    background: linear-gradient(98.57deg, #C88423 5.82%, #CA8826 9.58%, #CF9430 13.24%, #D8A741 16.87%, #E5C358 20.48%, #F4E675 24.05%, #FEFB87 25.87%, #F8EC7A 28.41%, #EBCE5F 34.44%, #E2B94C 40.38%, #DDAC41 46.16%, #DBA83D 51.57%, #DCAB40 55.97%, #E1B549 59.53%, #E8C658 62.78%, #F2DE6D 65.83%, #FEFB87 68.65%, #EDDD70 71.34%, #D6B551 75.45%, #C59639 79.51%, #B88028 83.44%, #B1731E 87.2%, #AE6E1A 90.57%);
    padding: 0.125rem;
    border-radius: 50px;
    width: 15rem;
  }
  
  div.inside_menu {
    background: linear-gradient(180deg, #121010 0%, #221D1E 16.67%, #3F3538 32.81%, #44393D 49.48%, #44393D 66.15%, #41373A 82.29%, #2C2627 98.96%);
    border-radius: inherit;
    padding: 0.75rem 0;
    align-items: center;
    justify-content: center;
    max-width: 100%;
  }
  
  div.link_intro {
    font-size: 20px;
    /* color: #FBF995; */
  }
  
  div.text-gold {
    background: linear-gradient(90deg, #AE8625 0%, #F7EF8A 36.46%, #D2AC47 79.69%, #EDC967 100%);
    -webkit-background-clip: text;
    background-clip: text;
  
  }
  
  div.d-flex {
    display: flex !important;
  }
  
  div.inside_menu .icon_regis {
    width: 1.8125rem;
    height: 1.8125rem;
    margin-right: 0.5rem;
  }
  
  div.inside_menu .icon_intro {
    width: 1.8125rem;
    height: 1.8125rem;
    margin-right: 0.5rem;
  }
  
  div.text-gold {
    background: linear-gradient(90deg, #AE8625 0%, #F7EF8A 36.46%, #D2AC47 79.69%, #EDC967 100%);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    background-clip: text;
  }
  
  /* banner */
  div.carousel {
    position: relative;
  }
  
  div.carousel-inner {
    position: relative;
    width: 100%;
    overflow: hidden;
  }
  
  div.carousel-item {
    position: relative;
    display: none;
    float: left;
    width: 100%;
    margin-right: -100%;
    backface-visibility: hidden;
    transition: transform .6s ease-in-out;
  }
  
  div.carousel-item.active,
  .carousel-item-next,
  .carousel-item-prev {
    display: block;
  }
  
  img.w-100 {
    width: 100% !important;
  }
  
  img.d-block {
    display: block !important;
  }
  
  /* ประกาศจากเว็บ */
  div.slide_announce.large {
    display: flex;
  }
  
  div.slide_announce {
    /* width: 100%; */
    background: #262626;
    padding: 0.3rem 20rem;
  }
  
  div.slide_announce .announce {
    font-size: 1.1rem;
    width: 17.5%;
  }
  
  div.slide_announce marquee {
    font-size: 1rem;
    background: #606060;
    border-radius: 4px;
    display: flex;
    align-items: center;
  }
  
  span.text-yello {
    color: #fbf995;
  }
  
  div.body_content {
    padding: 0.5rem 20rem 0;
  }

  /* ิพื้นหลัง */
  /* div.blackgd {
    font-size: 100%;
    background-image: url(/image/BG.png);
    background-repeat: no-repeat;
    background-size: cover;
    background-color: #000;
    color: #fff;
  } */
  
  </style>