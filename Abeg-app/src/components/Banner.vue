<template>
  <section>
    <section class="banner-section">
      <div class="logo">
            <img alt="Vue logo" src="@/assets/abeg.svg" id="logo" />
      </div>
      <div class="text">
        <h1>Make Someone<br> Happy With Cash</h1>
        <p>
          Do you want to pay for the food you ordered,<br> send money to your babe
          or receive money <br>from your friends? use Abeg.
        </p>
        <div id="button">
          <div class="input">
            <input type="search" name="" id="input" placeholder="Enter your email address">
          </div>

          <div class="butt">
            <button type="submit" class="button">GET EARLY ACCESS</button>
          </div>
        </div>
      </div>
    </section>
  </section>
</template>
<script>
export default {
  name: "Banner",
};
</script>
<style scoped>
.banner-section {
  background-image: url("../assets/line-background.png");
  height: 100vh;
  background-size: cover;
}
h1,
p {
  text-align: center;
  padding: 7px;
  font-size: 25px;
}
h1 {
  font-size: 50px;
  font-weight: 900;
}
.text {
  padding-top: 10%;
}
.button {
    position: relative;
    height: 64px;
    min-width: 100px;
    display: block;
    font-size: 17px;
    border: none;
    text-transform: uppercase;
    border-radius: 8px;
    background-color: #8a5cf7;
    color: #fff;
    font-family: Asap;
    font-weight: 500;
    padding: 0 22px;
}
#input{
  border: transparent;
  border-radius: 8px;
  font-size: 16px;
  height: 64px;
  padding: 0 22px;
  min-width: 272px;
  background-color: #fff;
  font-family: Asap;
  font-weight: 500;
  box-sizing: border-box;
}
#button{
  display: flex;
  align-items: center;
  justify-content: center;
  margin-top: 20px;
  flex-wrap: wrap;
}
.butt, .input{
  margin-right: 16px;
}
#logo{
  width: fit-content;
  margin:auto;
  display: block;
}
</style>
