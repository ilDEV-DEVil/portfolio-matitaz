<script setup lang="ts">
</script>

<template>
  <div class="hero">
    <div class="hero-container">
      <h1 class="title">Matilde Campana</h1>
      <div class="subtitle">Digital artist</div>
      <div class="hero-container-links">
        <a href="">About Me</a>
        <a href="#projects">Projects</a>
        <a href="">Contacts</a>
      </div>
    </div>
    </div>
</template>

<style scoped lang="scss">
.hero {
  width: 100%;
  height: 100vh;
  display: flex;
  align-items: center;
  justify-content: center;
  background-image: url("https://wallpapercave.com/wp/wp7421176.jpg");
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;

  &-container {
    text-align: center;
    color: white;

    .title {
      font-size: 3rem;
      line-height: 1.5;
    }

    .subtitle {
      font-size: 2rem;
      font-weight: lighter;
    }

    &-links {
      display: flex;
      justify-content: space-between;
      font-size: 1rem;
      margin: 16px;

      a {
        color: inherit;
        text-decoration: none;
        font-style: italic;
        transition: all 200ms;

        &:hover {
          transform: translateY(-8px)
        }
      }
    }
  }
}
</style>
