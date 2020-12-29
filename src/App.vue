<template>
  <div id="app">
    <link rel="preconnect" href="https://fonts.gstatic.com">
    <link href="https://fonts.googleapis.com/css2?family=Noto+Sans+JP:wght@100;300;400;500;700&display=swap" rel="stylesheet">
    <b-container fluid align='center' class="slide-in-left">
      <b-row>
        <b-col xl="6">
          <img class="avatar mt-5" src="./assets/avataaars.png" alt="Responsive image">
          <img>
          <h2>
            <strong>
              <p class="name mt-3">Nathan Pereira</p>
            </strong>
          </h2>
          <p class="id">Developer Intern</p>
          <p class="id mt-2">@nathan.pereira</p>
        </b-col>

        <b-col xl="6">
          <b-row class="linha">
            <b-col xl="6">
              <a href="https://www.linkedin.com/in/nathan-pereira-0543a9190/">
                <div class="linkedin p-3 mt-4">
                  <img class="imgLinkedin" src="./assets/linkedin.png" alt="Logo Linkedin">
                </div> 
              </a>
            </b-col>
            <b-col xl="6">
              <a href="https://gitlab.com/nathan.pereira">
                <div class="gitlab p-3 mt-4">
                  <img class="imgGitlab" src="./assets/gitlab.png" alt="Logo Gitlab">
                </div>
              </a>
            </b-col>
            <b-col xl="6">
              <a href="https://www.instagram.com/nathan_perei/">
                <div class="instagram p-3 mt-4">
                  <img class="imgInstagram" src="./assets/instagram.png" alt="Logo Instagram">
                </div> 
              </a>
            </b-col>
            <b-col xl="6">
              <a href="https://github.com/Nathan-P2">
                <div class="github p-3 mt-4">
                  <img class="imgGithub" src="./assets/github.png" alt="Logo Github">
                </div>
              </a>
            </b-col>
          </b-row>
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
  #app {
    font-family: 'Noto Sans JP', sans-serif;
    background: #242424;
    min-height: 100vh;
  }

  p.name {
    color: #ffffff;
    font-weight: 700;
  }

  p.id {
    color: #ffffff;
    font-weight: 300;
  }

  .btnOrange {
    border: none;
    cursor: pointer;
    background:  linear-gradient(to bottom right, red, yellow) !important;
  }

  .btnBlue {
    border: none;
    cursor: pointer;
    background:  linear-gradient(to bottom right, blue, purple) !important;
  }

  .linkedin {
    background: rgb(111,139,231);
    background: linear-gradient(90deg, rgba(111,139,231,1) 0%, rgba(47,41,157,1) 100%);
  }

  .gitlab {
    background: #F29727;
    background: linear-gradient(90deg, #F25D27 0%, #D93829 100%);
  }

  .instagram {
    background: #24292e;
    background: linear-gradient(90deg, #6f42c1 0%, #d73a49 100%);
  }

  .github {
    background: #f6f8fa;
    background: linear-gradient(90deg, #24292e 0%, #3a3a3a 100%);
  }

  .imgLinkedin {
    max-width: 80px;
    max-height: 100px;
  }

  .imgGitlab {
    max-width: 80px;
    max-height: 100px;
  }

  .imgInstagram {
    max-width: 80px;
    max-height: 100px;
  }

  .imgGithub {
    max-width: 80px;
    max-height: 100px;
  }

@media only screen and (min-width: 1080px) {
.linha {
    margin-top: 120px;
  }
}

.slide-in-left {
	-webkit-animation: slide-in-left 1.3s cubic-bezier(0.250, 0.460, 0.450, 0.940) both;
	        animation: slide-in-left 1.3s cubic-bezier(0.250, 0.460, 0.450, 0.940) both;
}

@-webkit-keyframes slide-in-left {
  0% {
    -webkit-transform: translateX(-1000px);
            transform: translateX(-1000px);
    opacity: 0;
  }
  100% {
    -webkit-transform: translateX(0);
            transform: translateX(0);
    opacity: 1;
  }
}
@keyframes slide-in-left {
  0% {
    -webkit-transform: translateX(-1000px);
            transform: translateX(-1000px);
    opacity: 0;
  }
  100% {
    -webkit-transform: translateX(0);
            transform: translateX(0);
    opacity: 1;
  }
}

.avatar {
  max-width: 40%;
}

</style>