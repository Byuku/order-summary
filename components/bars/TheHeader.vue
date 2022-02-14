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
    max-height: 75px;
    position: fixed;
    height: 100%;
    width: 100%;
    display: flex;
    place-content: center;
    background-color: rgba(255, 255, 255, 0.3);
    -webkit-backdrop-filter: blur(10px);
    backdrop-filter: blur(10px);
    padding: 10px;
    box-shadow: 0px 0px 3px 1px #ccc;

    &__img {
      width: 60px;
      height: auto;
    }
  }
</style>