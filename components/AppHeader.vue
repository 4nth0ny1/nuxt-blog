<template>
  <header class="header">
      <h1>mB</h1>
      <ul>
          <li><nuxt-link class="link" to="/">home</nuxt-link></li>
          <li><nuxt-link class="link" to="/about">about</nuxt-link></li>
          <li><nuxt-link class="link" to="/blog">blog</nuxt-link></li>
      </ul>
  </header>
</template>

<script>
export default {
    name: "AppHeader"
}
</script>

<style>
    .header {
        display: flex;
        justify-content: space-between;
        align-items: center;
    }

    .header ul {
        display: flex;
        flex-direction: row;
    }

    .header h1 {
        margin: 10px;
    }

    li {
        list-style-type: none;
        margin: 10px;
    }

    .link {
        color: black;
        text-decoration: none;
    }
</style>