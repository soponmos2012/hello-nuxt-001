<!-- Please remove this file from your project -->
<template>
  <div class="blackgd">
    <!-- <link rel="stylesheet" href="/scss/style.scss"> -->
    <div class="">
      <!-- footer -->
      <footer class="margin-footer">
        <img src="/image/askmedemo.jpg" width="320" height="80" />
        <div class="margin-32px large"></div>
        <div class="row_menu_footer">
          <a class="cursor_pointer register">
            สมัครสมาชิก
          </a>
          <div class="sector">|</div>
          <a class="example cursor_pointer">
            เข้าแทงหวย
          </a>
          <div class="sector">|</div>
          <a>
            ตรวจเช็ครางวัลหวย
          </a>
          <div class="sector">|</div>
          <a>
            โปรโมชัน
          </a>
          <div class="sector">|</div>
          <a>
            ติดต่อเรา
          </a>
        </div>
        <p class="t-white">Copyright © <span class="year_now">2022</span> askmebet.com All right reserved.</p>
      </footer>
    </div>
  </div>
</template>
  
<script>
export default {
  name: 'NuxtFooter',
}
</script>
  
<style>
/* footer */
.margin-footer {
  display: flex;
  flex-direction: column;
  align-items: center;
  padding: 2.75rem 0;
  background: radial-gradient(54.69% 77.98% at 50% 0%, #2C2C2C 0%, #141414 100%);
}

.margin-32px.large {
  display: block;
}

.row_menu_footer {
  display: flex;
  gap: 1rem;
  font-size: 100%;
  background-image: url(/images/BG.png);
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
  /* background-color: #000; */
  color: #fff;

}

.t-white {
  color: white;
}
</style>