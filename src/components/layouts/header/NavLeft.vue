<template>
<ul class="nav navbar-nav"> 
  <router-link to="/" tag="li" exact>
    <a href="#">Amigos</a>
  </router-link>
  <router-link to="/" tag="li" exact>
    <a href="/">Publicações</a>
  </router-link>
</ul>
</template>

<script>

export default {
    
  name: "NavLeft",
  data (){
    return {}
  }
}

</script>