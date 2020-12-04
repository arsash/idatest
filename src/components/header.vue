<template>
  <div class="container">
    <div class="header">
      <div class="left">
        <div class="logo">
          <img src="../assets/Logo.png" alt="Logo">
          <span class="logo__text">Pepelane</span>
        </div>
        <span class="slogan">World's first affordable airsharing</span>
      </div>
      <div class="right">
        <div class="color-scheme">
          <img src="../assets/moon.png" alt="moon">
          <span class="mode">Night mode</span>
        </div>
        <div class="controls">
          <img src="../assets/msg.png" alt="msg">
          <img src="../assets/notice.png" alt="notice" width="21">
        </div>
        <div class="user">
          <div class="user__name">
            <span>Bessie Cooper</span>
          </div>
          <div class="user__img">
            <img src="../assets/user.png" alt="user">
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'header-block'
}
</script>

<style scoped>
.container {
  max-width: 1312px;
  margin: 0 auto;
  box-sizing: border-box;
}
.header {
  width: 100%;
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin: 60px auto;
}
.left, .right {
  width: 40%;
  display: flex;
  justify-content: space-between;
  align-items: center;
}
.logo, .color-scheme, .controls {
  display: flex;
  justify-content: flex-start;
  align-items: center;
}

.color-scheme:hover {
  transform: scale(1.1);
  transition: 0.7s;
}
.controls img:hover {
  transform: scale(1.3);
  transition: 0.7s;
}

.logo__text, .user__name {
  color: #012345;
  font-family: sans-serif;
  font-weight: bold;
  font-size: 25px;
}
.user__name {
  font-size: 16px;
}
.slogan, .mode {
  font-family: 'Codec Pro', sans-serif;
  font-style: normal;
  font-weight: 300;
  font-size: 16px;
  line-height: 152%;
  color: #677B8F;
}
.color-scheme {
  width: 120px;
  justify-content: space-between;
  cursor: pointer;
}
.controls {
  width: 65px;
  justify-content: space-between;
}
.controls img {
  cursor: pointer;
}
.user {
  width: 180px;
  width: 180px;
  display: flex;
  justify-content: space-between;
  align-items: center;
}
.user__img img {
  border-radius: 50%;
}

@media (max-width: 1050px) {
  .slogan, .mode, .user__name span {
    display: none;
  }
}

</style>
