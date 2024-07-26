<script lang="ts">
import IconDocumentation from "../IconDocumentation.vue";

</script>

<template>
  <div class="about">
    <h1>This is an about page</h1>
    <br />
    <p>Was just too lasy to do more so we got what we got but u can read some interesting page on <a
        href="https://ru.wikipedia.org/wiki/%D0%92%D1%81%D0%B5%D0%BC%D0%B8%D1%80%D0%BD%D0%B0%D1%8F_%D0%BF%D0%B0%D1%83%D1%82%D0%B8%D0%BD%D0%B0"
        target="_blank" rel="noopener">wiki</a></p>
  </div>
</template>

<style>
@media (min-width: 1024px) {
  .about {
    min-height: 100vh;
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 20px;
    margin: 0 60px;
    padding-top: 225px; 
  }
}
.underAbout{
  width: 500px;
  height: 500px;
  background-color: red;
}
</style>
