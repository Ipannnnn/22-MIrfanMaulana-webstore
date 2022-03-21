<template>
  <v-app-bar app elevation="5" elevate-on-scroll>
    <div class="container">
      <v-row class="nav">
        <v-img max-height="50" max-width="50" src="@/assets/logo.png"></v-img>
        <ul class="d-flex">
          <li><router-link to="/" class="link">HOME</router-link></li>
          <li><router-link to="/" class="link">Product</router-link></li>
          <li><router-link to="/" class="link">About us</router-link></li>
          <li><router-link to="/" class="link">Contact us</router-link></li>
        </ul>

        <v-spacer></v-spacer>

        <v-btn outlined>Contact Us</v-btn>
      </v-row>
    </div>
  </v-app-bar>
</template>

<script>
export default { name: 'NavbarComponent'
};
</script>

<style scoped>
.link {
  text-decoration: none;
  color: inherit;
}

.nav {
  align-items: center;
}

ul {
  list-style: none;
}

ul li {
  margin: 0 50px;
}

ul li:last-child {
  margin-right: 0;
}
</style>
