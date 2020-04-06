<template>
  <div id="AppHeader">
    <b-navbar toggleable type="dark" variant="dark">
    <b-navbar-brand href="#">Hyeokjin-eun</b-navbar-brand>

    <b-navbar-toggle target="navbar-toggle-collapse">
      <template v-slot:default="{ expanded }">
        <b-icon v-if="expanded" icon="chevron-bar-up"></b-icon>
        <b-icon v-else icon="chevron-bar-down"></b-icon>
      </template>
    </b-navbar-toggle>

    <b-collapse id="navbar-toggle-collapse" is-nav>
      <b-navbar-nav class="ml-auto">
        <b-nav-item href="#profile">Profile</b-nav-item>
        <b-nav-item href="#timeline">TimeLine</b-nav-item>
        <b-nav-item href="#skill">Skill</b-nav-item>
        <b-nav-item href="#project">Project</b-nav-item>
      </b-navbar-nav>
    </b-collapse>
  </b-navbar>
  </div>
</template>

<script>
export default {

}
</script>

<style>
  @import url('https://fonts.googleapis.com/css2?family=Jua&display=swap');
  #AppHeader-font {
    font-family: Jua;
  }
</style>