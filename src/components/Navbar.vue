<template>
  <div>
    <div id="nav">
      <router-link to="/" id="logo-url">
        <img :src="logo" :alt="alt" id="logo" />
      </router-link>
      <router-link to="/">Home</router-link>
      <router-link to="/Pedidos">Pedidos</router-link>
    </div>
  </div>
</template>

<script>
export default {
  name: "Navbar",
  props: ["logo", "alt"]

}
</script>

<style scoped>
#nav {
  background-color: #222;
  border-color: 4px solid #111;
  padding: 15px 50px;
  display: flex;
  justify-content: flex-end;
  align-items: center;
}

#nav #logo-url {
  margin: auto;
  margin-left: 0;
}

#logo {
  width: 30px;
  height: 30px;
}

#nav a {
  color: #FCBA03;
  text-decoration: none;
  margin: 12px;
  transition: 5.s;
}

#nav a:hover {
  color: #FFF
}
</style>