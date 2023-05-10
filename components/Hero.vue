<template>
  <div class="Hero container">
    <div class="text-container">
      <h1 class="header">Find Your Fire Extinguisher</h1>
      <p class="snippet">
        Lorem ipsum dolor, sit amet consectetur adipisicing elit. Quibusdam
        optio ipsum esse pariatur beatae quod libero magnam molestias voluptas
        odit?
      </p>
      <button class="button btn">Start Looking</button>
    </div>
    <img src="~assets/svg/fire-extinguisher.svg" class="image" />
  </div>
</template>

<script>
export default {
  name: 'HeroPage',
}
</script>

<style scoped>
.Hero {
  height: 80vh;
  position: relative;
  display: flex;
  padding: 3rem 0;
  align-items: flex-start;
  justify-content: space-between;
}
.text-container {
  width: 50%;
  margin-top: 4rem;
}
.header {
  font-weight: 900;
  font-size: 4rem;
}
.snippet {
  color: grey;
  font-size: 1.25rem;
}
.image {
  width: 22.5rem;
  margin-top: 2rem;
}
.overlay {
  background: rgba(0, 0, 0, 0);
  position: absolute;
  width: 100%;
  height: 100%;
  top: 0;
}
.button {
  padding: 1rem 3rem;
  border-radius: 100rem;
  background-color: rgb(231, 81, 43);
  color: white;
  width: 16rem;
  font-weight: 700;
  transition: 0.5s;
}
.button:hover {
  width: 17.5rem;
}
@media (max-width: 500px) {
  .Hero {
    height: 40vh;
  }
}
</style>
