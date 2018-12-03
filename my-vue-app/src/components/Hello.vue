<template>
  <div class="hero">
    <div>
      <h1 class="display-3 title">Hello World</h1>
      <i><p class="lead">DO YOU SEE THIS HELLO WORLD? MIND BLOWN</p></i>
    </div>
  </div>
</template>

<style>
  body {
    background-image: linear-gradient(to right, rgb(65, 184, 181) , rgb(53, 73, 94));
    color: white;
  }

  .title {
    text-shadow: 2px 2px 35px;
  }

  .hero {
    height: 90vh;
    display: flex;
    align-items: center;
    justify-content: center;
    text-align: center;
  }
  .hero .lead {
    font-weight: 200;
    font-size: 1.5rem;
  }
</style>