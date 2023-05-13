<script setup lang="ts">
</script>

<template>

  <main>
   <RouterLink to="/">
   <h1>Digi AI Hub</h1><br>
   </RouterLink>

  <RouterLink to="/about"><p class="browse-link">See Contents</p></RouterLink>

  <div class="sideNav">

    <a href="https://mail.google.com/mail/?authuser=0" target="_blank">
      <img width="48" height="48" src="https://img.icons8.com/fluency/48/gmail-new.png" alt="gmail-new"/>
    </a>
    <a href="https://chat.openai.com/?model=text-davinci-002-render-sha" target="_blank">
      <img width="48" height="48" src="https://img.icons8.com/pulsar-line/48/FFFFFF/chatgpt.png" alt="chatgpt"/>
    </a>
    <a href="https://www.youtube.com/?authuser=0" target="_blank">
      <img width="48" height="48" src="https://img.icons8.com/color/48/youtube-play.png" alt="youtube-play"/>
    </a>
    <a href="https://github.com/" target="_blank">
      <img width="48" height="48" src="https://img.icons8.com/color/48/github--v1.png" alt="github--v1"/>
    </a>
    <a href="https://id.atlassian.com/login?application=bitbucket&continue=https%3A%2F%2Fbitbucket.org%2Faccount%2Fsignin%2F%3Fnext%3D%252F%26redirectCount%3D1" target="_blank">
      <img width="48" height="48" src="https://img.icons8.com/color/48/bitbucket.png" alt="bitbucket"/>
    </a>
    <a href="" target="_blank">
      
    </a>
    <a href="" target="_blank">
      
    </a>

  </div>

  </main>

</template>

<style scoped>
h1{
  font-family: 'Questrial', sans-serif;
  font-size: 6rem;
  color:#B6EADA;
  text-align: center;
  margin-top:10%;
}
.browse-link{
  text-align: center;
  color:#647E68;
  font-family: 'Questrial', sans-serif;
  font-size: 1.5rem;
}
.browse-link:hover{
 color: #F0CAA3;
}
.sideNav{
  position: absolute;
  width:2%;
  right:0;
  top:0;
  height:100%;
}
.sideNav a img:hover{
border-bottom: 2px solid #E1D4BB;
}

</style>