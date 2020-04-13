<template>
  <div id="AppContent">
    <div class="align-items-center container">
      <div class="row">
        <div class="app-content-container p-0 col-sm-12">
          <div class="app-content-content p-2 shadow">
            <ContentProfile />
            <hr>
            <ContentTimeLine />
            <hr>
            <ContentSkill />
            <hr>
            <ContentProject />
          </div>
        </div>
      </div>
    </div>
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
  .container {
    margin: 20px;
  }
  .app-content-content {
    margin: 8px 8px 8px 8px;
    border: 1px solid lightgray;
    border-radius: 5px;
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
  .timeline-content-font {
    font-family: Jua;
    font-size: 20px;
  }
  .timeline-content-font-2 {
    font-family: Jua;
    font-size: 18px;
  }
</style>