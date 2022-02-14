<template>
  <div>
    <header class="header">
      <div class="header__figure">
        <img class="header__img" src="img/logo_ours_noel.svg" alt="Tediber" >
      </div>
    </header>
  </div>
</template>

<script>
export default {
  name: "TheHeader"
}
</script>

<style lang="scss" scoped>
  .header {
    -webkit-backdrop-filter: blur(10px);
    backdrop-filter: blur(10px);
    background-color: rgba(255, 255, 255, 0.3);
    box-shadow: 0px 0px 3px 1px #ccc;
    display: flex;
    height: 100%;
    max-height: 75px;
    padding: 10px;
    place-content: center;
    position: fixed;
    width: 100%;
    z-index: 2;

    &__img {
      width: 60px;
      height: auto;
    }
  }
</style>