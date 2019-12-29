<template>
  <div class="hello">
      <div class="row">
  <div class="column">
    <label class="recent">Recent</label>
    <img src="../assets/Recent.jpg" alt="image" width="300" height="200">
  </div>
  <div class="column">
    <label class="images">Images</label>
   <img src="../assets/image.jpeg" alt="video" width="300" height="200">
  </div>
  <div class="column" >
    <label class="videos">Videos</label>
    <img src="../assets/video.jpg" alt="Documents" width="300" height="200">
  </div>
  <div class="column">
    <label class="docs">Documents</label>
 <img src="../assets/docs.png" alt="video" width="300" height="200">
  </div>
</div>
  </div>
</template>

<script>

export default {
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

* {
  box-sizing: border-box;
}

/* Create four equal columns that floats next to each other */
.column {
  float: left;
  width: 25%;
  padding: 0px;
  text-align: center;
 /* Should be removed. Only for demonstration */
}
label{
  font-size: 22px;
  font-weight: 800;
  cursor: pointer;
}

img{
  cursor: pointer;
}
/* Clear floats after the columns */
.row:after {
  content: "";
  display: table;
  clear: both;
}
</style>
