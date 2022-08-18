<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="stylesheet" href="CSS/style.css" />
    <title>Yenoke</title>
    <link rel="icon" type="x-icon" href="IMAGES/icon.png" />
  </head>
  <body>
    
  </body>
  <body>
    <section class="firstPage">
      <section class="navbar-background">
        <nav class="navbar background h-nav-resp" id="nav"> 
            <ul class="nav-list v-class-resp">
              <img src="Images/icon.png" width="30" height="30" alt="logo" class="logo">
              <li><a href="#home">Home</a></li>
              <li><a href="#about">About Me</a></li>
              <li><a href="#visit">Visit me</a></li>
              <li><a href="#moreinfo">More info</a></li>
              <li><a href="#contact">Contact me</a></li>
            </ul>
          </div>
          <div class="burger">
            <div class="line"></div>
            <div class="line"></div>
            <div class="line"></div>
          </div>
          </nav>
        </section>
    <div class="firstSection">
        <h1 class="firsth1" style="font-size: 100px;">HI! I am Yenoke!</h1>
        <h2 class="firsth2">I am a gaming content creator!</h2>
    </div>
</section>
<style>
@import url("https://fonts.googleapis.com/css2?family=Poppins&display=swap");
@import url("https://fonts.googleapis.com/css2?family=Quicksand:wght@500&display=swap");
* {
  margin: 0;
  padding: 0;
}

html {
  scroll-behavior: smooth;
}

/* NAVBAR */
.logo {
  display: block;
}

.navbar {
  background-image: linear-gradient(-280deg, #c441f4, #00eada);
  background-blend-mode: darken;
  background-size: cover;
  animation: navbar-load 500ms ease-out;
}

.navbar {
  display: flex;
  opacity: 90%;
  backdrop-filter: blur(8px);
  align-items: center;
  align-self: center;
  align-self: center;
  margin: auto;
  justify-content: center;
  /* position: sticky; */
  padding: 10px;
  border-radius: 10px;
  width: 90%;
  height: 20px;
}

.nav-list {
  opacity: 100%;
  width: 100%;
  display: flex;
  align-items: center;
  display: flex;
  flex-direction: row;
  flex-wrap: nowrap;
  align-content: space-around;
  justify-content: center;
}

.nav-list li {
  list-style: none;
  padding: 12px 22px;
}

.nav-list li a {
  text-decoration: none;
  color: lightgray;
  font-family: "Open Sans", sans-serif;
  font-size: 15px;
  transition: all 0.3s ease-in;
  cursor: pointer;
}

.nav-list li a:hover {
  text-decoration: none;
  color: white;
}

.bi {
  padding: 0 20px;
  cursor: pointer;
}
.bi:hover {
  color: white;
}

/* SECTION 1 - PAGE 1 */
.firstPage {
  height: 100vh;
  background-image: linear-gradient(#7758d1, #f7cbfd);
}
.firsth1 {
  font-family: "Poppins", sans-serif;
  text-align: center;
  font-weight: bolder;
  padding-top: 50px;
  animation: h1-load 1000ms ease-out;
}

.firsth2 {
  font-family: "Quicksand", sans-serif;
  text-align: center;
  animation: h2-load 1500ms ease-out;
}

/* KEYFRAMES */
@keyframes navbar-load {
  0% {
    transform: translateY(-100%);
  }
  100% {
    transform: translateY(0);
  }
}

@keyframes h1-load {
  0% {
    transform: translateX(-100%);
  }
  100% {
    transform: translateX(0);
  }
}

@keyframes h2-load {
  0% {
    transform: translateX(-100%);
  }
  100% {
    transform: translateX(0);
  }
}

</style>
  </body>
</html>
