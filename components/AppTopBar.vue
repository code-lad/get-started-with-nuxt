<template>
  <div class="navbar">
    <nav>
      <ul>
        <li>
          <nuxt-link to="/">HOME</nuxt-link>
        </li>
        <li>
          <nuxt-link to="/users">USERS</nuxt-link>
        </li>
      </ul>
    </nav>
  </div>
</template>
<script>
export default {};
</script>
<style>
.navbar {
  background-color: #ffffff;
  padding: 20px;
  margin-bottom: 20px;
}
.navbar nav {
  display: flex;
  justify-content: center;
  align-items: center;
}
.navbar nav ul li {
  display: inline-block;
  margin-right: 10px;
}
.navbar nav ul li a {
  text-decoration: none;
}
</style>