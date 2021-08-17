<template>
  <div class="logos-wrapper">
    <h2>Find Your Best Logo</h2>
    <div class="item-logos">
      <img src="../assets/logos/logo-1.png" alt="" class="logo" />
    </div>
    <div class="item-logos">
      <img src="../assets/logos/logo-2.png" alt="" class="logo" />
    </div>
    <div class="item-logos">
      <img src="../assets/logos/logo-3.png" alt="" class="logo" />
    </div>
    <div class="item-logos">
      <img src="../assets/logos/logo-4.png" alt="" class="logo" />
    </div>
    <div class="item-logos">
      <img src="../assets/logos/logo-5.png" alt="" class="logo" />
    </div>
    <div class="item-logos">
      <img src="../assets/logos/logo-6.png" alt="" class="logo" />
    </div>
    <div class="item-logos">
      <img src="../assets/logos/logo-7.png" alt="" class="logo" />
    </div>
  </div>
</template>

<script>
export default {
  name: "Logos",
};
</script>

<style scoped>
.logos-wrapper {
  width: 70%;
  overflow: hidden;
  margin: 50px auto;
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
}

.logos-wrapper h2 {
  flex: 0 0 100%;
}

.logos-wrapper .item-logos {
  flex: 0 0 20%;
  border-radius: 10px;
  box-sizing: border-box;
  padding: 20px;
  margin: 20px 20px;
  width: 150px;
  height: 150px;
  background: #c4c4c4;
}

.item-logos .logo {
  width: 70%;
}
</style>
