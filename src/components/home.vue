<template>
  <div>
    <nav id="navbar-example2" class="navbar navbar-light sticky-top px-1">
      <a class="navbar-brand" href="#">C-A</a>
      <ul class="nav nav-pills mt-8">
        <li class="nav-item">
          <a class="nav-link" href="#scrollspyHeading1">HOME</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#scrollspyHeading2">ABOUT</a>
        </li>
        <li class="nav-item">
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
            <h2>Hi, Let's Meet.</h2>
            <p>
              Hi, my is
              <span style="color: orange"
                >Arinzechi Chiagozie Chukwunyelu.</span
              >
              I am a
              <span style="color: orange">JavaScript developer</span> Since the
              beginning of my career as a developer for a year, i have developed
              websites for start-up businesses and i have also collaborated with
              some creative developers on websites, i am bold , confident &
              naturally curious and a huge football fan.
            </p>
          </header>
        </div>
      </section>

      <!-- END OF MOORE ABOUT ME section-->
      <div class="underline"></div>

      <!-- PROJECT section-->

      <section
        id="scrollspyHeading3"
        :style="{
          'background-image': 'url(https://wallpapercave.com/wp/uhvYTtV.jpg)',
        }"
      >
        <div class="container-fluid project-section">
          <div class="container project">
            <h1 class="project-caption">here are some of my recent Projects</h1>
            <div class="row cards">
              <div class="card" style="width: 24rem">
                <img src="#" class="card-img-top" alt="..." />
                <div class="card-body">
                  <h5 class="card-title">Card title</h5>
                  <p class="card-text">
                    Some quick example text to build on the card title and make
                    up the bulk of the card's content.
                  </p>
                  <a href="#" class="btn-lg btn btn-outline-warning"
                    >Take a Look</a
                  >
                </div>
              </div>
              <div class="card" style="width: 24rem">
                <img src="#" class="card-img-top" alt="..." />
                <div class="card-body">
                  <h5 class="card-title">Card title</h5>
                  <p class="card-text">
                    Some quick example text to build on the card title and make
                    up the bulk of the card's content.
                  </p>
                  <a href="#" class="btn-lg btn btn-outline-warning"
                    >Take a Look</a
                  >
                </div>
              </div>
              <div class="card" style="width: 24rem">
                <img src="#" class="card-img-top" alt="..." />
                <div class="card-body">
                  <h5 class="card-title">Card title</h5>
                  <p class="card-text">
                    Some quick example text to build on the card title and make
                    up the bulk of the card's content.
                  </p>
                  <a href="#" class="btn-lg btn btn-outline-warning"
                    >Take a Look</a
                  >
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>

      <!-- END OF PROJECT section-->
      <div class="underline"></div>

      <!-- TECH STACKS  section-->
      <section id="scrollspyHeading4">
        <div class="container-fluid tech-stack-section">
          <div class="tech-stack container">
            <h3>here are tech-stacks i used in prodution</h3>
            <div class="stack">
              <div class="d-flex flex-wrap">
                <div class="w">1</div>
                <div class="w">2</div>
                <div class="w">3</div>
              </div>
            </div>
          </div>
        </div>
      </section>

      <!-- END OF TECH STACKS  section-->

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

/* ---- PROJECT SECTIONS -----*/

.project-section {
  height: auto;
}
.project {
  padding: 80px 10px;
  height: auto;
}
.project-caption {
  padding: 30px 0;
  width: auto;
  text-align: center;
  text-transform: uppercase;
  color: #efefef;
  font-size: 2rem;
  font-family: "Gill Sans", "Gill Sans MT", Calibri, "Trebuchet MS", sans-serif;
}
.cards {
  justify-content: space-around;
  padding: 60px 0;
}
.card {
  border-radius: 5px;
  border: 1px orange solid;
  color: #efefef;
  background-color: rgb(19, 19, 19);
  margin-bottom: 50px;
}
.card-img-top {
  height: 250px;
}

/*TECH-STACK SECTIONS  */

.tech-stack-section {
  color: #efefef;
  height: 60vh;
  background-color: rgb(22, 22, 22);
}
.tech-stack {
  padding: 10px;
}
.tech-stack h3 {
  margin: 30px 0;
  font-size: 1.7rem;
  font-family: Georgia, "Times New Roman", Times, serif;
  text-align: center;
  text-transform: uppercase;
}
.stack {
  padding: 20px 0;
}
/**THIS IS THE TECH STACK W-CLASS FOR WIDTH AT MEDIA QUERIES (DESKTOP SCREEN ) */
.w {
  width: 33.3%;
  padding: 10px;
}
/**THIS IS THE TECH STACK W-CLASS FOR WIDTH AT MEDIA QUERIES (DESKTOP SCREEN ) */

/* MEDIA QUERIES*/

@media only screen and (max-width: 900px) {
  #navbar-example2 {
    height: 100px;
    padding-right: 20px;
  }
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
  .cards {
    gap: 30px;
  }
  .tech-stack-section {
    height: auto;
  }
  /**THIS IS THE TECH STACK W-CLASS FOR WIDTH AT MEDIA QUERIES (SMALL SCREEN ) */
  .w {
    width: 100%;
    padding: 5px;
  }
  /**THIS IS THE TECH STACK W-CLASS FOR WIDTH AT MEDIA QUERIES (SMALL SCREEN ) */
}
</style>