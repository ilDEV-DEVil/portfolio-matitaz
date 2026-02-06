<script setup lang="ts"></script>

<template>
  <footer class="footer">
    <div id="about" class="footer-section">
      <div class="footer-section-title">About me</div>
      <div class="footer-section-subtitle">
        <div>Hello!</div>
        <div>I'm Matilde Campana, a concept artist from Italy</div>
      </div>
    </div>
    <div id="contacts" class="footer-section contacts">
      <div class="footer-section-title">Contacts</div>
      <div class="footer-section-subtitle">
        <div>matitaz.art@gmail.com</div>
        <div>@mati.taz</div>
      </div>
    </div>
    <!-- <div><img src="../assets/images/matitaz.jpeg" alt="decoration-image"></div> -->
  </footer>
</template>

<style scoped lang="scss">
.footer {
  padding: 1rem;
  display: flex;
  flex-direction: column;
  background-image: url("../assets/images/matitaz.jpeg");
  background-position: right;
  background-repeat: no-repeat;
  background-size: 50%;

  &-section {
    display: flex;
    flex-direction: column;
    gap: .5rem;
    height: 30vh;

    &-title {
      font-size: 2rem;
      font-weight: bold;
    }

    &-subtitle {
      font-size: 1rem;
      font-weight: lighter;
      color: darkgray;
    }
  }
}
</style>
