<template>
  <header class="header">
    <nuxt-link to="/">
      <img src="~/static/logo.png" alt="Logo" class="logo" />
    </nuxt-link>
    <nav class="nav">
      <ul>
        <li>
          <nuxt-link to="/impressum">Impressum</nuxt-link>
        </li>
      </ul>
    </nav>
  </header>
</template>

<script>
export default {
  name: "Header",
};
</script>
