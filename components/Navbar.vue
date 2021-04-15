<template>
<div>
  <b-navbar toggleable="lg">
    <b-navbar-brand href="#"><Logo /></b-navbar-brand>

    <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

    <b-collapse id="nav-collapse" is-nav>

      <!-- Right aligned nav items -->
      <b-navbar-nav class="ml-auto">
        <b-navbar-nav>
          <b-nav-item href="#jobs">Jobs</b-nav-item>
          <b-nav-item href="#about">About Us</b-nav-item>
        </b-navbar-nav>
       <!--  <b-nav-item-dropdown text="Lang" right>
          <b-dropdown-item href="#">EN</b-dropdown-item>
          <b-dropdown-item href="#">ES</b-dropdown-item>
        </b-nav-item-dropdown> -->

      </b-navbar-nav>
    </b-collapse>
  </b-navbar>
</div>
</template>

<style>
</style>
