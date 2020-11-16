<template>
  <section>
    <div class="hero___section">
      <div class="hero-text">
        <h1>Figma ecommerce dashboard template</h1>
        <p>
          Make sure to have a look at this cool new Figma resource shared by
          Bartosz Maryniaczyk. A free e-commerce dashboard template that can be
          readily used for your own project needing a dashboard.
        </p>
      </div>
      <div>
        <img alt="Vue logo" src="../assets/hero.png" />
      </div>
    </div>
  </section>
</template>
<script>
export default {
  name: "Message",
};
</script>
<style>
.hero___section {
  display: flex;
  justify-content: space-around;
}
.hero-text{
  font-size: 20px;
  text-align: left
}
.hero-text h1{
font-size: 30px;
}
</style>
