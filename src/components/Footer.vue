<template>
  <footer>
    <p>Copyright &copy; 2022</p>
    <router-link to="/about">About</router-link>
    <br />
    <router-link to="/work">Go to working page</router-link>
  </footer>
</template>

<script>
export default {
  name: "FooterView",
};
</script>

<style scoped>
a {
  color: #333;
}

footer {
  margin-top: 30px;
  text-align: center;
}
</style>

