<template>
  <header class="header">
      <a  class="toogle">
          <i class="fa fa-lg"></i>
      </a>
      <h1 class="title">
          {{ title }}
      </h1>
  </header>
</template>

<script>
export default {
    name: 'Header',
    props: {
        title: String,
        hideToggle: Boolean
    }
}
</script>

<style>
    .header{
        grid-area: header;
        background: linear-gradient(to right, #1254C4 ,#01FFEC);
        display: flex;
        justify-content: center;
        align-items: center;
    }
</style>