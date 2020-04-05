<template>
  <div id="AppContent">
    <b-container class="align-items-center">
      <b-row>
        <b-col class="left-container p-0" sm="4">
          <div class="left-content p-2 shadow text-center">
            Back-End Developer
          </div>
          <div class="left-content p-2 shadow text-center">
            Introduction
          </div>
          <div class="left-content p-2 shadow text-center">
            Contact
          </div>
          <div class="left-content p-2 shadow text-center">
            Interests
          </div>
        </b-col>
        <b-col class="light-container p-0" sm="8">
          <div class="light-content p-2 shadow">
            <div class="content-section text-center">
              Profile
            </div>
            <hr>
            <div class="content-section text-center">
              TimeLine
            </div>
            <hr>
            <div class="content-section text-center">
              Skill
            </div>
          </div>
        </b-col>
      </b-row>
    </b-container>
  </div>
</template>

<script>
export default {

}
</script>

<style>
  .container {
    margin: 20px;
  }
  .left-container {

  }
  .light-container {

  }
  .left-content {
    margin: 16px 8px 16px 8px;
    border: 1px solid lightgray;
    border-radius: 5px;
    height: 350px;
  }
  .light-content {
    margin: 16px 8px 16px 8px;
    border: 1px solid lightgray;
    border-radius: 5px;
    height: 100%;
  }
  .content-section {
    height: 33%;
  }
  hr {
    margin: 0px 20px 0px 20px;
  }
</style>