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
           <img alt="Vue logo" src="@/assets/facebook.svg" id="image" />
           <img alt="Vue logo" src="@/assets/instagram.svg" id="image" />
           <img alt="Vue logo" src="@/assets/twitter.svg" id="image" />
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
  max-width: 100%;
  margin: auto;
  display: block;
}
.container{
  display: flex;
  justify-content: space-around;
  align-items: center;
  flex-wrap: wrap;
}
#image{
  padding-right: 1.2em;
  width: 30%;
}
p{
  padding-left: 20px;
}

</style>
