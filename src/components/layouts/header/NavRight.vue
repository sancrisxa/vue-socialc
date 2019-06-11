<template>
<ul class="nav navbar-nav navbar-right">
  <router-link to="/" tag="li" exact>
    <a href="#"><i class="fa fa-bell"></i></a>
  </router-link>
  <router-link to="/login" tag="li" exact>
    <a href="#">Login</a>
  </router-link>
</ul>
</template>

<script>

export default {

  name: 'NavRight',
  data () {
    return {}
  }
}

</script>