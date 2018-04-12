<template>
  <header class="header">
    <ul>
      <li>
        <nuxt-link to="/">Home</nuxt-link>
        <nuxt-link to="/users/">Users</nuxt-link>
      </li>
    </ul>
  </header>
</template>

<style scoped>
.header {
  width: 100%;
  height: 60%;
  display: flex;
  justify-content: center;
  align-items: center;
}

.nav-items {
  list-style: none;
  padding: 0;
  margin: 0;
  display: flex;
  justify-content: space-around;
  align-items: center;
}
</style>
