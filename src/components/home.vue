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
          <a class="nav-link" href="#scrollspyHeading3">PROJECTS</a>
        </li>
      </ul>
    </nav>
    <div
      data-bs-spy="scroll"
      data-bs-target="#navbar-example2  "
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
        <div class="container hero-box">
          <div class="row hero p-8">
            <div class="col-sm-8 details">
              <h1>
                <span style="color: orange">Arinzechi chiagozie</span>
              </h1>
              <h3>web developer, Aspiring Software developer</h3>

              <button
                type="button"
                class="btn btn-lg btn btn-outline-warning"
                style="border-radius: 50px"
                data-bs-spy="scroll"
                data-bs-target="#scrollspyHeading5"
                data-bs-offset="0"
                tabindex="0"
              >
                <a href="#scrollspyHeading5" style="color: white">
                  Contact me</a
                >
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
              naturally curious, a huge football fan and also very intersted in
              the stock market.
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
                  <a
                    href="#"
                    class="btn-lg btn btn-outline-warning"
                    style="border-radius: 50px"
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
                  <a
                    href="#"
                    class="btn-lg btn btn-outline-warning"
                    style="border-radius: 50px"
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
                  <a
                    href="#"
                    class="btn-lg btn btn-outline-warning"
                    style="border-radius: 50px"
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
            <h3>here are technology stacks i used in prodution</h3>
            <div class="stack">
              <div class="d-flex flex-wrap">
                <div class="w">
                  <div class="mx-auto">
                    <svg
                      width="48"
                      height="48"
                      fill="none"
                      xmlns="http://www.w3.org/2000/svg"
                      class="mx-auto"
                    >
                      <path
                        fill-rule="evenodd"
                        clip-rule="evenodd"
                        d="M41.42 8.084c.78-.78.78-2.04 0-2.82L36.74.584a1.992 1.992 0 00-2.82 0L30 4.505l7.5 7.5 3.92-3.92zM8 26.502L28 6.504l7.5 7.5-20 19.998H8v-7.5zm4 3.5h1.84l16-15.998-1.84-1.84-16 15.998v1.84zM48 40H0V48h48v-8z"
                        fill="#1CB1BB"
                        data-v-6b15a60d=""
                      ></path>
                    </svg>
                  </div>
                  <h4 class="pt-4">DESIGNS</h4>
                  <p class="mt-4">
                    I love clean, simple and high performance designs, with
                    smooth interactions.
                  </p>
                  <h6 class="pt-4 pb-2">DESIGNS TOOLS :</h6>
                  <p>Figma</p>
                  <p>Canva</p>
                  <p>Adobe Photoshop</p>
                  <p>Scribble</p>
                </div>
                <div class="w w-b">
                  <div class="mx-auto">
                    <svg
                      width="48"
                      height="48"
                      fill="none"
                      xmlns="http://www.w3.org/2000/svg"
                      class="mx-auto"
                      data-v-6b15a60d=""
                    >
                      <path
                        fill-rule="evenodd"
                        clip-rule="evenodd"
                        d="M6 12h36V8H6c-2.2 0-4 1.8-4 4v24c0 2.2 1.8 4 4 4h8v-4H6V12zm20 12h-8v3.56c-1.22 1.1-2 2.66-2 4.44 0 1.78.78 3.34 2 4.44V40h8v-3.56c1.22-1.1 2-2.68 2-4.44 0-1.76-.78-3.34-2-4.44V24zm-7 8c0 1.66 1.34 3 3 3s3-1.34 3-3-1.34-3-3-3-3 1.34-3 3zm25-16H32c-1 0-2 1-2 2v20c0 1 1 2 2 2h12c1 0 2-1 2-2V18c0-1-1-2-2-2zM34 36h8V20h-8v16z"
                        fill="#1CB1BB"
                        data-v-6b15a60d=""
                      ></path>
                    </svg>
                    <h4 class="pt-4">FRONT-END DEVELOPMENT</h4>

                    <p class="mt-4">
                      I also build Quality UI, i'm comfortable with templates,
                      themes and whatever it is to get my job upto speed.
                    </p>
                    <h6 class="pt-4 pb-2">TECHNOLOGY STACK :</h6>
                    <p>HTML</p>
                    <p>CSS</p>
                    <p>JavaScript</p>

                    <h6 class="pt-4 pb-2">FRAMEWORKS USED :</h6>

                    <p>VUE.JS</p>
                    <p>JQUERY</p>
                    <p>BOOTSTAP</p>
                    <p>TAILWIND CSS</p>
                    <p>FOUNDATION</p>
                  </div>
                </div>
                <div class="w">
                  <div class="mx-auto">
                    <svg
                      width="48"
                      height="48"
                      fill="none"
                      xmlns="http://www.w3.org/2000/svg"
                      class="mx-auto"
                    >
                      <path
                        fill-rule="evenodd"
                        clip-rule="evenodd"
                        d="M41.42 8.084c.78-.78.78-2.04 0-2.82L36.74.584a1.992 1.992 0 00-2.82 0L30 4.505l7.5 7.5 3.92-3.92zM8 26.502L28 6.504l7.5 7.5-20 19.998H8v-7.5zm4 3.5h1.84l16-15.998-1.84-1.84-16 15.998v1.84zM48 40H0V48h48v-8z"
                        fill="#1CB1BB"
                        data-v-6b15a60d=""
                      ></path>
                    </svg>
                  </div>
                  <h4 class="pt-4">DEPLOYMENT</h4>
                  <p class="mt-4">
                    I am flexible with different platforms used in Deploying my
                    codes.
                  </p>
                  <h6 class="pt-4 pb-2">Deployment tools :</h6>
                  <p>Netlify</p>
                  <p>Infinityfree</p>
                  <p>Digital ocean</p>

                  <h6 class="pt-4 pb-2">DEVELOPMENT TOOL :</h6>
                  <p>vscode</p>
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>

      <!-- END OF TECH STACKS  section-->

      <!-- CONTACT ME  section-->
      <section id="scrollspyHeading5">
        <div class="container-fluid contact-me-section">
          <div class="container contact-me p-8">
            <h3>let's work togeher on something Great</h3>
            <div class="underline-2 mx-auto"></div>
            <p class="">
              Think of a Project or Product idea ! , you can get in touch with
              my contact information and social link.
            </p>

            <div class="social-links container">
              <div class="row text-center socials">
                <div class="col-md-3">
                  <div class="flex-col">
                    <div class="icon"><i class="fas fa-mobile-alt"></i></div>
                    <a
                      class="icon-link"
                      target="_blank"
                      href="tel:+2348160545944"
                    >
                      phone
                    </a>
                  </div>
                </div>
                <div class="col-md-3">
                  <div class="flex-col">
                    <div class="icon"><i class="fas fa-envelope"></i></div>
                    <a
                      class="icon-link"
                      target="_blank"
                      href="mail:imakandiboi@yahoo.com"
                    >
                      e-mail</a
                    >
                  </div>
                </div>
                <div class="col-md-3">
                  <div class="flex-col">
                    <div class="icon"><i class="fab fa-linkedin"></i></div>
                    <a
                      class="icon-link"
                      target="_blank"
                      href="https://www.linkedin.com/in/arinzechi-chiagozie-30a294202/"
                    >
                      linkedin</a
                    >
                  </div>
                </div>
                <div class="col-md-3">
                  <div class="flex-col">
                    <div class="icon"><i class="fab fa-github"></i></div>
                    <a
                      class="icon-link"
                      target="_blank"
                      href="https://github.com/imakandiboi"
                    >
                      github repo</a
                    >
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="container-fluid copyright text-center">
          <p class="copyright-text">
            Arinzechi Chiagozie © {{ new Date().getFullYear() }}
          </p>
        </div>
      </section>
      <!-- END OF CONTACT ME  section-->
    </div>
  </div>
</template>

<script>
export default {
  name: "home",
};
</script>

<style scoped>
@import url("https://fonts.googleapis.com/css2?family=Nunito&family=Odibee+Sans&family=Open+Sans&family=Roboto+Condensed&family=Roboto+Slab:wght@100;200;400;500;800;900&display=swap");
@import url("https://fonts.googleapis.com/css2?family=Nunito&family=Odibee+Sans&family=Open+Sans&family=Roboto+Condensed&family=Roboto+Slab&display=swap");
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
  font-size: 12px;
}
.nav-item {
  margin: 0 15px;
}
/*---LANDER--*/
.lander {
  height: 60vh;
}

.hero {
  height: auto;
}

.hero details {
  display: flex;
  flex-direction: column;
}

.hero h1 {
  text-align: left;
  margin: 30px 10px;
  font-family: "Odibee Sans", cursive;
  font-weight: Thin 100;
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
  font-family: "Roboto Slab", serif;

  line-height: 3rem;
}
.underline {
  width: 100%;
  height: 3px;
  background-color: orange;
}
.underline-2 {
  width: 70%;
  height: 10px;
  background-color: black;
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
  height: 80vh;
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
  text-align: center;
}
/**THIS IS THE TECH STACK W-CLASS FOR WIDTH AT MEDIA QUERIES (DESKTOP SCREEN ) */
.w {
  width: 33.3%;
  padding: 10px;
}
.w-b {
  border-left: 2px solid orange;
  border-right: 2px solid orange;
}
.w h4 {
  color: orange;
}
.w h6 {
  color: orange;
}
/**THIS IS THE TECH STACK W-CLASS FOR WIDTH AT MEDIA QUERIES (DESKTOP SCREEN ) */

/**THIS IS THE CONTACT-ME SECTION (DESKTOP SCREEN ) */

.contact-me-section {
  height: 40vh;
  background-color: rgb(209, 137, 3);
}
.contact-me h3 {
  text-align: center;
  text-transform: uppercase;
  font-weight: bolder;
  font-family: "Odibee Sans", cursive;
  padding-top: 20px;
  padding-bottom: 20px;
  font-size: 40px;
  color: rgb(0, 0, 0);
}

.contact-me p {
  text-align: center;
  text-transform: uppercase;
  font-weight: bolder;
  font-family: "Roboto Slab", serif;
  padding-top: 20px;
  padding-bottom: 20px;
  font-size: 20px;
  color: rgb(0, 0, 0);
}
.copyright {
  height: 10vh;
  color: #999999ee;
  background-color: rgb(0, 0, 0);
}
.copyright-text {
  padding-top: 40px;
  font-size: 20px;
  letter-spacing: 0.1rem;
  font-family: "Odibee Sans", cursive;
}

.socials {
  padding: 40px 10px;
}
.icon {
  font-size: 40px;
}

.icon-link {
  font-size: 15px;
  color: black;
  text-transform: uppercase;
  font-weight: bold;
  font-family: "Roboto Slab", serif;
  padding-top: 20px;
  padding-bottom: 20px;
  text-decoration-line: none;
}
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
    font-family: "Odibee Sans", cursive;
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

  /**CONTACT ME SECTION FOR MEDIA QUREIES (SMALL SCREEN ) */
  .contact-me-section {
    height: auto;
    background-color: rgb(209, 137, 3);
  }

  .contact-me p {
    text-align: left;
    text-transform: uppercase;
    font-weight: bolder;
    font-family: "Roboto Slab", serif;
    padding-top: 20px;
    padding-bottom: 25px;
    font-size: 20px;
    color: rgb(0, 0, 0);
  }
}
</style>