<template>
  <div class="topbar">
    <div class="topbar__left">
      <a href="tel:++38(050)1234567">
        <img
          src="../assets/topbar-icons/phone_icon.svg"
          alt=""
        />+38(050)123567</a
      >
      <a href="https://goo.gl/maps/bhQfszGyRP6ziT3aA">
        <img src="../assets/topbar-icons/location_icon.svg" alt="" />
        Ukraine, Kyiv,Khreshchatyk 1
      </a>
      <span>
        <img src="../assets/topbar-icons/clock_icon.svg" alt="" />
        All week 24/7</span
      >
    </div>
    <div class="topbar__right">
      <a href="www.facebook.com">
        <img src="../assets/topbar-icons/facebook-icon.svg" alt="" />
      </a>
      <a href="www.twitter.com">
        <img src="../assets/topbar-icons/twitter-icon.svg" alt="" />
      </a>
      <a href="www.instagram.com">
        <img src="../assets/topbar-icons/instagramm-icon.svg" alt="" />
      </a>
      <a href="www.pinteres.com">
        <img src="../assets/topbar-icons/pinterse-icon.svg" alt="" />
      </a>
    </div>
  </div>
</template>

<script>
export default {
  name: "TopBar",
};
</script>

<style scoped>
.topbar {
  height: 24px;
  background-color: black;
  padding: 10px 90px;
  display: flex;
  justify-content: space-between;
  align-items: center;
}
.topbar__left {
  display: flex;
  column-gap: 24px;
}
.topbar a,
span {
  color: white;
  text-decoration: none;
  display: flex;
  align-items: center;
  column-gap: 10px;
}
.topbar__right {
  display: flex;
  column-gap: 12px;
}
</style>
