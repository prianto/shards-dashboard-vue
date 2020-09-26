<template>
  <div>
    <slot />
  </div>
</template>

<script>
// OnePage layout components
export default {
  name: 'onepage',
};
</script>

<style scoped>
html,
body {
  height: 100%;
}

body {
  display: flex;
  align-items: center;
  padding-top: 40px;
  padding-bottom: 40px;
  background-color: #f5f5f5;
  font-family: 'Ubuntu', sans-serif;
}

body > div {
  width: 100%;
  height: 100%;
  display: flex;
  -ms-flex-align: center;
  align-items: center;
  text-shadow: 0 0.05rem 0.1rem rgba(255, 255, 255, 0.5);
  box-shadow: inset 0 0 5rem rgba(0, 0, 0, 0.5);
}

h1,
h2,
h3,
h4,
h5,
h6,
.h1,
.h2,
.h3,
.h4,
.h5,
.h6,
.btn {
  font-family: 'Ubuntu Condensed', sans-serif;
}
</style>
