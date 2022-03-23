<template>
  <div>
    <div class="container">
      <div class="box">
        <router-link to="/">Panel Exterior</router-link>
      </div>
      <div class="box">
        <router-link to="/">Panel Interior</router-link>
      </div>
      <div class="box">
        <router-link to="/">Panel Exterior - Exterior</router-link>
      </div>
      <div class="box">
        <router-link to="/">Cubierta</router-link>
      </div>
      <div class="box">
        <router-link to="/">Viga Tubo</router-link>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Paneles",
  components: {},
};
</script>

<style scoped>
.container {
  margin-left: 50px;
  display: flex;
  flex-direction: column;
  gap: 15px;
}
.box {
  width: 300px;
  border: 3px solid orange;
  border-radius: 5px;
  padding: 15px;
}
a {
  text-decoration: none;
  font: 16px;
  color: #666666;
}
</style>
