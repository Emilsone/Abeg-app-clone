<template>
  <section>
    <footer>
      <div class="container">
        <div class="footer-text">
          <p>©2020 Abeg. All rights reserved </p>
        </div>
        <div class="footer-image">
          <img alt="Vue logo" src="@/assets/iphone.png" class="image" />
        </div>
        <div class="footer-icons">
          <span><i class="fa fa-facebook" aria-hidden="true"></i></span>
          <span><i class="fa fa-twitter" aria-hidden="true"></i></span>
          <span><i class="fa fa-instagram" aria-hidden="true"></i></span>
        </div>
      </div>
    </footer>
  </section>
</template>
<script>
export default {
  name: "Footer",
};
</script>
<style scoped>
.image {
  width: 30%;
  max-width: 80%;
}
.container{
  display: flex;
  justify-content: space-around;
  align-items: center;
  flex-wrap: wrap;
}
.fa-facebook,.fa-twitter, .fa-instagram{
  padding-right: 2em;
  background-color:#8a5cf7;
  width: 50px;

}
</style>
