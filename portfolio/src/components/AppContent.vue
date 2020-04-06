<template>
  <div id="AppContent">
    <b-container class="align-items-center">
      <b-row>
        <b-col class="right-container p-0" sm="12">
          <div class="right-content p-2 shadow">
            <ContentProfile />
            <hr>
            <ContentTimeLine />
            <hr>
            <ContentSkill />
            <hr>
            <ContentProject />
          </div>
        </b-col>
      </b-row>
    </b-container>
  </div>
</template>

<script>
import ContentProfile from './ContentProfile.vue';
import ContentTimeLine from './ContentTimeline.vue';
import ContentSkill from './ContentSkill.vue';
import ContentProject from './ContentProject.vue';

export default {
  components: {
    ContentProfile,
    ContentTimeLine,
    ContentSkill,
    ContentProject
  }
}
</script>

<style>
  @import url('https://fonts.googleapis.com/css2?family=Jua&display=swap');
  @import url('https://fonts.googleapis.com/css2?family=Nanum+Gothic&display=swap');
  .container {
    margin: 20px;
  }
  .left-container {

  }
  .right-container {

  }
  .left-content {
    margin: 8px 8px 8px 8px;
    border: 1px solid lightgray;
    border-radius: 5px;
    height: 350px;
  }
  .right-content {
    margin: 8px 8px 8px 8px;
    border: 1px solid lightgray;
    border-radius: 5px;
  }
  .content-section {

  }
  hr {
    margin: 0px 20px 0px 20px;
  }
  .title-font {
    font-family: Jua;
    font-size: 25px;
  }
  .profile-title-font {
    font-family: Jua;
    font-size: 30px;
    color: darkblue;
  }
  .profile-content-font {
    font-family: Jua;
    font-size: 17px;
  }
  .profile-content {
    margin: 10px;
  }
  .timeline-title-font {
    font-family: Jua;
    font-size: 20px;
  }
</style>