<template>
  <div class="products">
    <h1>This is the products page.</h1>
    <p>Look at all the products here!</p>
  </div>
</template>

<style>
p {
  color: red;
}

@media (min-width: 1024px) {
  .products {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
}
</style>
