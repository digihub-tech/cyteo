<template>
  <div class="about">

    <div class="glass-container">
      <div class="glass-content">
        <RouterLink to="/academic" class="links"><img width="40" height="40" src="https://img.icons8.com/stickers/40/school--v1.png" alt="school--v1"/> Academic</RouterLink>
        <RouterLink to="/dev" class="links"><img width="40" height="40" src="https://img.icons8.com/plasticine/40/developer.png" alt="developer"/> Developer</RouterLink>
        <RouterLink to="/" class="links"><img width="40" height="40" src="https://img.icons8.com/3d-fluency/40/phone.png" alt="phone"/> Socials</RouterLink>
        <RouterLink to="/" class="links"><img width="40" height="40" src="https://img.icons8.com/fluency/40/credit-card-front.png" alt="credit-card-front"/> Finance</RouterLink>
        <RouterLink to="/" class="links"><img width="40" height="40" src="https://img.icons8.com/fluency/40/news.png" alt="news"/> News</RouterLink>
        <RouterLink to="/" class="links"><img width="40" height="40" src="https://img.icons8.com/fluency/40/china-circular.png" alt="china-circular"/> China</RouterLink>
        <RouterLink to="/" class="links"><img width="40" height="40" src="https://img.icons8.com/fluency/40/documents.png" alt="documents"/> Documents</RouterLink>
        <RouterLink to="/" class="links"><img width="40" height="40" src="https://img.icons8.com/ios-filled/40/retro-tv.png" alt="retro-tv"/> Entertainment</RouterLink>
        <RouterLink to="/" class="links"><img width="40" height="40" src="https://img.icons8.com/external-solidglyph-m-oki-orlando/40/external-web3-web-development-solid-solidglyph-m-oki-orlando.png" alt="external-web3-web-development-solid-solidglyph-m-oki-orlando"/> Web3</RouterLink>
        <RouterLink to="/" class="links"><img width="40" height="40" src="https://img.icons8.com/color/40/innovation.png" alt="innovation"/> Creatives</RouterLink>
        <RouterLink to="/" class="links"><img width="40" height="40" src="https://img.icons8.com/fluency/40/museum.png" alt="museum"/> Government</RouterLink>
        <RouterLink to="/" class="links"><img width="40" height="40" src="https://img.icons8.com/dusk/40/neutral-trading.png" alt="neutral-trading"/> Trading</RouterLink>
        <RouterLink to="/" class="links"><img width="40" height="40" src="https://img.icons8.com/fluency/40/group-of-projects.png" alt="group-of-projects"/> Projects</RouterLink>
        <RouterLink to="/" class="links"><img width="40" height="40" src="https://img.icons8.com/color/40/people-working-together.png" alt="people-working-together"/> Community</RouterLink>
        <RouterLink to="/" class="links"><img width="40" height="40" src="https://img.icons8.com/stickers/40/online-group-studying.png" alt="online-group-studying"/>e-Course</RouterLink>
        <RouterLink to="/" class="links"><img width="40" height="40" src="https://img.icons8.com/fluency/40/job.png" alt="job"/> Jobs</RouterLink>
        <RouterLink to="/" class="links"><img width="40" height="40" src="https://img.icons8.com/fluency/40/repository.png" alt="repository"/> Repositories</RouterLink>
        <RouterLink to="/" class="links"><img width="40" height="40" src="https://img.icons8.com/fluency/40/library.png" alt="library"/> Library</RouterLink>
        <RouterLink to="/" class="links"><img width="40" height="40" src="https://img.icons8.com/cotton/40/online-coding.png" alt="online-coding"/> Coding Ground</RouterLink>
        <RouterLink to="/" class="links"><img width="40" height="40" src="https://img.icons8.com/3d-plastilina/40/add-bookmark--v1.png" alt="add-bookmark--v1"/> Certifications</RouterLink>
        <RouterLink to="/" class="links"><img width="40" height="40" src="https://img.icons8.com/fluency/40/portfolio.png" alt="portfolio"/> Portfolio</RouterLink>
        <RouterLink to="/" class="links"></RouterLink>
        <RouterLink to="/" class="links"></RouterLink>
        <RouterLink to="/" class="links"></RouterLink>
        <RouterLink to="/" class="links"></RouterLink>
        <RouterLink to="/" class="links"></RouterLink>
        <RouterLink to="/" class="links"><img width="40" height="40" src="https://img.icons8.com/ios-filled/40/connection-status-off.png" alt="connection-status-off"/> Others</RouterLink>
      </div>
    </div>

  </div>
</template>

<style>

h2{
  font-family: 'Questrial', sans-serif;
  color:#C69749;
  font-size: 1.8rem;
}
.glass-container{
  background: rgba( 255, 255, 255, 0.25 );
  box-shadow: 0 8px 32px 0 rgba( 31, 38, 135, 0.37 );
  backdrop-filter: blur( 4px );
  -webkit-backdrop-filter: blur( 4px );
  border-radius: 10px;
  border: 1px solid rgba( 255, 255, 255, 0.18 );
  width:550px;
  height:500px;
  margin:3% 0 0 25%;
  overflow-y: scroll;
}
.glass-container::-webkit-scrollbar {
  display: none;
}
.glass-content{
  display: flex;
  gap:10px;
  flex-wrap: wrap;
  align-items: center;
  justify-content: center;
}
.links{

  color:#000000;
  background-color: #E8A0BF;
  padding:10px;
  margin:1%;
  max-width:300px;
  border-radius: 10px;
  display: flex;
  align-items: center;
  font-family: 'Questrial', sans-serif;
}
.links:hover{
  background-color: #C7E9B0;
}
</style>
