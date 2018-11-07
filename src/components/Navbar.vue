<template>

  <b-container>

    <b-navbar toggleable="md" type="light" variant="default">

      <b-navbar-toggle target="nav_collapse"></b-navbar-toggle>

      <b-navbar-brand to="/"><b>Collegestudyer</b></b-navbar-brand>

      <b-collapse is-nav id="nav_collapse">

        <b-navbar-nav class="localnav">
          <b-nav-item to="/login">Авторизация</b-nav-item>
        </b-navbar-nav>
      </b-collapse>
    </b-navbar>
  </b-container>
</template>

<style>
  .abc {
    color: black;
  }

  .localnav {
    margin: 2px;
  }

</style>
