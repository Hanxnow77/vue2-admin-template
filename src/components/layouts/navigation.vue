<template>
  <nav class="navbar-default navbar-static-side" role="navigation">
    <div class="sidebar-collapse">
      <ul side-navigation class="nav metismenu" id="side-menu">
        <li class="nav-header">
          <div class="profile-element dropdown" v-dropdown>
            <span><img alt="image" class="img-circle" :src="require('../../assets/avatar.jpg')"></span>
            <a class="dropdown-handler">
              <span class="clear">
                  <span class="block m-t-xs"><strong class="font-bold">test</strong></span>
                  <span class="text-muted text-xs block">Example menu<b class="caret"></b></span>
              </span>
            </a>
            <ul class="animated fadeInRight m-t-xs">
              <li>
                <router-link to="/logout">Logout</router-link>
              </li>
            </ul>
          </div>
          <div class="logo-element">
            FL
          </div>
        </li>

        <router-link tag="li" to="/index/main" active-class="active">
          <a><i class="fa fa-laptop"></i> <span class="nav-label">Main</span></a>
        </router-link>

        <router-link tag="li" to="/index/tabs" active-class="active">
          <a><i class="fa fa-desktop"></i> <span class="nav-label">Tabs</span></a>
        </router-link>

        <router-link tag="li" to="/index/tables" active-class="active">
          <a><i class="fa fa-desktop"></i> <span class="nav-label">Tables</span></a>
        </router-link>

        <router-link tag="li" to="/index/gallery" active-class="active">
          <a><i class="fa fa-desktop"></i> <span class="nav-label">Gallery</span></a>
        </router-link>

        <router-link tag="li" to="/index/form" active-class="active">
          <a><i class="fa fa-desktop"></i> <span class="nav-label">Form</span></a>
        </router-link>

      </ul>
    </div>
  </nav>
</template>

<script>
  export default{};
</script>


<style lang="scss">
  .nav-header {
    img {
      width: 48px;
      height: 48px;
    }
  }
</style>
