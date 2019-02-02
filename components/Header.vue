<template>
    <nav class="navbar container column is-12 is-paddingless" role="navigation" aria-label="main navigation">
        <div class="navbar-brand column is-6 is-paddingless">
            <a href="/" class="navbar-item"><img src="@/static/3d-rhombus.png" alt="Logo"></a>

            <a role="button" class="navbar-burger burger" aria-label="menu" aria-expanded="false" data-target="navbarBasicExample">
              <span aria-hidden="true"></span>
              <span aria-hidden="true"></span>
              <span aria-hidden="true"></span>
            </a>
        </div>
        <div id="navbarBasicExample" class="navbar-menu column is-6 is-paddingless">
            <div class="navbar-end column is-12 is-paddingless">
                <a aria-current="true" href="/" class="navbar-item has-text-white column is-2 is-paddingless">Homepage</a>
                <a aria-current="true" href="/" class="navbar-item has-text-white column is-2 is-paddingless">Preise</a>
                <a aria-current="true" href="/" class="navbar-item has-text-white column is-2 is-paddingless">Prozess</a>
            </div>
        </div>
    </nav>
</template>
<style>
.navbar {
    position: absolute;
    left: 0;
    right: 0;
    margin-top: 20px;
}
.navbar-item img {
    max-height: 80px;
}
.navbar-end .column {
    justify-content: center;
}
</style>
<script>
export default {
  name: 'Header'
}

</script>
