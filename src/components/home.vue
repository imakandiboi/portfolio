<template>
  <div>
    <nav id="navbar-example2" class="navbar navbar-light sticky-top px-4">
      <a class="navbar-brand" href="#">C-A</a>
      <ul class="nav nav-pills mt-8">
        <li class="nav-item mr-8">
          <a class="nav-link" href="#scrollspyHeading1">HOME</a>
        </li>
        <li class="nav-item mr-8">
          <a class="nav-link" href="#scrollspyHeading2">ABOUT</a>
        </li>
        <li class="nav-item mr-8">
          <a class="nav-link" href="#scrollspyHeading2">RESUME</a>
        </li>
      </ul>
    </nav>
    <div
      data-bs-spy="scroll"
      data-bs-target="#navbar-example2"
      data-bs-offset="0"
      class="scrollspy-example"
      tabindex="0"
    >
      <!-- lander section-->
      <section
        id="scrollspyHeading1"
        class="lander"
        :style="{
          'background-image': 'url(https://wallpapercave.com/wp/uhvYTtV.jpg)',
        }"
      >
        <div class="container">
          <div class="row hero p-8">
            <div class="col-sm-8 details">
              <h1>
                <span style="color: orange">Arinzechi chiagozie</span>
              </h1>
              <h3>web developer, Aspiring Software developer</h3>

              <button type="button" class="btn btn-lg btn btn-outline-warning">
                Contact me
              </button>
            </div>
            <div class="col-sm-4"></div>
          </div>
        </div>
      </section>

      <!-- end of lander section-->
      <div class="underline"></div>
      <!-- MOORE ABOUT ME section-->

      <section id="scrollspyHeading2">
        <div class="container-fluid About">
          <header class="px-24 pt-12">
            <h2>Hi , Lets Meet.</h2>
            <p>
              Hi , my is
              <span style="color: orange"
                >Arinzechi Chiagozie Chukwunyelu.</span
              >
              I am a javascript developer Since the beginning of my career as a
              developer for a year, i have developed some websites for
              businesses and i have also collaborated with some creative
              developers on digital products, i am bold , confident & naturally
              curious and a huge football fan.
            </p>
          </header>
        </div>
      </section>

      <!-- END OF MOORE ABOUT ME section-->

      <h4 id="scrollspyHeading3">Third headig</h4>
      <p>...</p>
      <h4 id="scrollspyHeading4">Fourth heading</h4>
      <p>...</p>
      <h4 id="scrollspyHeading5">Fifth heading</h4>
      <p>...</p>
    </div>
  </div>
</template>

<script>
export default {
  name: "home",
};
</script>

<style scoped>
.navbar {
  background-color: black;
  font-weight: bold;
  justify-content: space-around !important;
}
#navbar-example2 {
  height: 100px;
  padding-right: 50px;
}
#navbar-example2 a {
  color: rgb(255, 255, 255);
}
.nav-item {
  margin: 0 15px;
}
/*---LANDER--*/
.lander {
  height: 60vh;
}
.hero {
  height: 40vh;
}

.hero details {
  display: flex;
  flex-direction: column;
}

.hero h1 {
  text-align: left;
  margin: 30px 10px;
  color: #f5f3f3;
  text-transform: uppercase;
  font-size: 3rem;
  line-height: 4rem;
}
.hero h3 {
  text-align: left;
  margin: 30px 10px;
  color: #949393;
  text-transform: uppercase;
  font-size: 1.2rem;
}
.btn {
  border-radius: 2px;
  height: 60px;
  margin: 4px 16px;
  color: #efefef;
}

/* ABOUT ME*/
.About {
  background-color: rgb(22, 22, 22);
  color: #efefef;
  height: 50vh;
}

.About header {
  align-content: center;
  justify-content: center;
  padding: 40px 0 20px;
  text-align: center;
  margin: 0 auto;
  width: 50%;
}
.About h2 {
  margin: 20px 0;
  font-size: 2rem;
  font-family: Georgia, "Times New Roman", Times, serif;
}

.About p {
  font-size: 1.2rem;
  line-height: 3rem;
}
.underline {
  width: 100%;
  height: 3px;
  background-color: orange;
}

@media only screen and (max-width: 900px) {
  .hero h1 {
    text-align: left;
    margin: 30px 10px;
    color: #f5f3f3;
    text-transform: uppercase;
    font-size: 2rem;
    line-height: 4rem;
    font-family: sans-serif;
  }
  .About {
    background-color: rgb(22, 22, 22);
    color: #efefef;
    height: 80vh;
  }
  .About header {
    align-content: center;
    justify-content: center;
    padding: 40px 0 20px;
    text-align: center;
    margin: 0 auto;
    width: 100%;
  }
  .About p {
    font-size: 15px;
  }
}
</style>