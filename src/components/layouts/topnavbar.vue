<template>
  <div class="row border-bottom">
    <nav class="navbar navbar-static-top" role="navigation" style="margin-bottom: 0">
      <div class="navbar-header">
        <a class="navbar-minimalize minimalize-styl-2 btn btn-primary" v-minimaliza-sidebar><i class="fa fa-bars"></i></a>
        <form role="search" class="navbar-form-custom" method="post" action="">
          <div class="form-group">
            <input type="text" placeholder="Search for something..." class="form-control" name="top-search" id="top-search">
          </div>
        </form>
      </div>
      <ul class="nav navbar-top-links navbar-right">
        <li>
          <router-link to="/logout">
            <i class="fa fa-sign-out"></i> Log out
          </router-link>
        </li>
      </ul>
    </nav>
  </div>
</template>

<script>
  export default{};
</script>
