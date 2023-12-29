<template>
  <div class="about">
    <micro-app
      class="micro-system"
      name="system"
      url="http://localhost:5174"
      :iframe="true"
      :keep-alive="true"
    ></micro-app>
  </div>
</template>

<style>
@media (min-width: 1024px) {
  .about {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
}
</style>
