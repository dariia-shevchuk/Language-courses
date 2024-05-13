<template>

  <body>
    <nav>
      <div class="nav-logo">
        <a href="#">
          <img src="../assets/logo3.png">
        </a>
      </div>

      <ul class="nav-links">
        <li class="Link"><a href="#">Home</a></li>
        <li class="Link"><a href="#">Features</a></li>
        <li class="Link"><a href="#">Pricing</a></li>
        <li class="Link"><a href="#">About</a></li>
      </ul>

      <button class="btn">Hire Me</button>
    </nav>

    <header class="container">
      <div class="content">
        <span class="blur"></span>
        <span class="blur"></span>
        <h4>SPEAK LANGUAGES LIKE A PRO</h4>
        <H1>Hi, I'm <span>Fedor</span>, Your Future Teacher</H1>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
           Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>

        <button class="btn">Get Started</button>
      </div>
      <div class="image">
        <img src="../assets/img2.png">
      </div>
    </header>

    <section class="container">
      <h2 class="header">Our Features</h2>
      <div class="features">

        <div class="card">
          <span>
            <i class="ri-money-dollar-box-line"></i>
          </span>
          <h4>Free First Lecture</h4>
          <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
          <a href="#">Join Now <i class="ri-arrow-right-line"></i></a>
        </div>

        <div class="card">
          <span>
            <i class="ri-money-dollar-box-line"></i>
          </span>
          <h4>Fix Your Bugs</h4>
          <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
          <a href="#">Join Now <i class="ri-bug-line"></i></a>
        </div>

        <div class="card">
          <span>
            <i class="ri-money-dollar-box-line"></i>
          </span>
          <h4>Study At Any Time</h4>
          <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
          <a href="#">Join Now <i class="ri-arrow-right-line"></i></a>
        </div>

        <div class="card">
          <span>
            <i class="ri-money-dollar-box-line"></i>
          </span>
          <h4>Cooperation</h4>
          <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
          <a href="#">Join Now <i class="ri-arrow-right-line"></i></a>
        </div>
      </div>
    </section>

    <section class="container2">
      <h2 class="header">PRICING PLAN</h2>
      <p class="sub-header">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
      <div class="pricing">
        <div class="card">
          <div class="content">
            <h4>English</h4>
            <h3>50$</h3>
            <p>
              <i class="ri-checkbox-circle-line"></i>
              Good Plan
            </p>
            <p>
              <i class="ri-checkbox-circle-line"></i>
              Remote Work
            </p>
            <p>
              <i class="ri-checkbox-circle-line"></i>
              Personal Coaching
            </p>
          </div>
          <button class="btn">Join Now</button>
        </div>

        <div class="card">
          <div class="content">
            <h4>Spanish</h4>
            <h3>50$</h3>
            <p>
              <i class="ri-checkbox-circle-line"></i>
              Good Plan
            </p>
            <p>
              <i class="ri-checkbox-circle-line"></i>
              Remote Work
            </p>
            <p>
              <i class="ri-checkbox-circle-line"></i>
              Personal Coaching
            </p>
          </div>
          <button class="btn">Join Now</button>
        </div>

        <div class="card">
          <div class="content">
            <h4>France</h4>
            <h3>50$</h3>
            <p>
              <i class="ri-checkbox-circle-line"></i>
              Good Plan
            </p>
            <p>
              <i class="ri-checkbox-circle-line"></i>
              Remote Work
            </p>
            <p>
              <i class="ri-checkbox-circle-line"></i>
              Personal Coaching
            </p>
          </div>
          <button class="btn">Join Now</button>
        </div>
      </div>
    </section>

    <footer class="container3">
      <span class="blur"></span>
      <span class="blur"></span>
      <div class="column">
        <div class="logo">
          <img src="../assets/logo3.png">
        </div>
        <p>
          Lorem ipsum dolor sit amet, consectetur adipiscing elit.
        </p>
        <div class="social">
          <a href="#"><i class="ri-instagram-line"></i></a>
          <a href="#"><i class="ri-youtube-line"></i></a>
          <a href="#"><i class="ri-twitter-line"></i></a>
        </div>
      </div>
      <div class="column">
        <h4>Company</h4>
        <a href="#">Business</a>
        <a href="#">Partnership</a>
        <a href="#">Network</a>
      </div>

      <div class="column">
        <h4>About Us</h4>
        <a href="#">Blogs</a>
        <a href="#">Channels</a>
        <a href="#">Sponsors</a>
      </div>

      <div class="column">
        <h4>Contact</h4>
        <a href="#">Contact Us</a>
        <a href="#">Privacy Policy</a>
        <a href="#">Term & Conditions</a>
      </div>
    </footer>

  </body>
</template>

<style>
@import url('https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&family=Ubuntu:ital,wght@0,300;0,400;0,500;0,700;1,300;1,400;1,500;1,700&display=swap');

*{
  margin: 0;
  padding: 0;
  outline: none;
  border: none;
  box-sizing: border-box;
}

img{
  width: 100%;
  display: flex;
  
}

a{
  text-decoration: none; 
}

body{
  font-family: 'Poppins', sans-serif;
  background-color: black;
  /* background-color: #fff; */
}

nav{
  width: 100%;
  margin: auto;
  padding: 2rem 1rem;
  display: flex;
  align-items: center;
  justify-content: center;
  gap: 15%;
  /* background-color: aliceblue; */
  
}

.nav-logo{
  max-width: 100px;
}

.nav-links{
  list-style: none;
  display: flex;
  align-items: center;
  gap: 3rem;
}

.Link a{
  position: relative;
  padding-bottom: 0.75rem;
  color: #fff;
}

.Link a::after{
  content: "";
  position: absolute;
  height: 2px;
  width: 0;
  bottom: 0;
  left: 0;
  background-color: #6410c3;
  transition: all 0.3s ease;

}

.Link a:hover::after{
  width: 70%;
}

.btn{
  padding: 1rem 2rem;
  font-size: 1rem;
  color: #ffffff;
  background-color: #6410c3;
  border-radius: 5px;
  cursor: pointer;
  transition: all 0.3s ease;
}

.btn:hover{
  background-color: #471284;
}

.container{
  max-width: 1200px;
  height: 70vh;
  margin: auto;
  padding: 5rem 2rem;
}

.container2{
  max-width: 1200px;
  /* height: 70vh; */
  margin: auto;
  padding: 0rem 2rem;
  padding-bottom: 5rem;
}

.container3{
  max-width: 1200px;
  /* height: 70vh; */
  margin: auto;
  padding: 5rem 2rem;
}


/* .container1{
  max-width: 1200px;
  margin: auto;
  padding: 4rem 2rem;
} */

.blur{
  position: absolute;
  box-shadow: 0 0 1000px 50px #522483;
  z-index: -100px;
}

header{
  position: relative;
  padding-top: 2rem;
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  align-items: center;
  gap: 2rem;
  /* color: #fff; */
}

header .content h4{
  margin-bottom: 1rem;
  font-size: 1rem;
  font-weight: 600;
  color: #ccc;
  position: relative;

}

header .content h1{
  color: #fff;
  margin-bottom: 1rem;
  font-size: 3rem;
  font-weight: 700;
  line-height: 4rem;
  position: relative;
}

header .content h1 span{
  -webkit-text-fill-color: transparent;
  -webkit-text-stroke: 1px #fff;
}

header .content p{
  margin-bottom: 2rem;
  color: #fff;
}

header .image{
  position: relative;
}

header .image img{
  max-width: 600px;
  margin: auto;
}

section .header{
  margin-bottom: 1rem;
  color: #fff;
  font-size: 2.25rem;
  text-align: center;
  font-weight: 600;
}

.features{
  margin-top: 4rem;
  display: grid;
  color: #000000;
  grid-template-columns: repeat(4, 1fr);
  gap: 2rem;
}

.features .card{
  background-color: #1a191b;
  padding: 1rem;
  /* border: 2px solid transparent; */
  border-radius: 15px;
  transition: all 0.3s ease;
}

.features .card:hover{
  background-color: #3b3b5e;
  /* border-color: #ccc; */

}
.features .card span{
  display: inline-block;
  background-color: #6410c3;
  padding: 2px 9px;
  margin-bottom: 1rem;
  font-size: 1.75rem;
  color: #fff;
  border-radius: 5px;
}

.features .card h4{
  margin-bottom: 0.5rem;
  font-size: 1.2rem;
  font-weight: 600;
  color: #fff;
}

.features .card p{
  margin-bottom: 1rem;
  color:#ccc;
}

.features .card a{
  color: #fff;
  transition: all 0.3s ease;
}

.features .card a:hover{
  color:#ac9fbb;
}

.sub-header{
  max-width: 600px;
  margin:auto;
  text-align: center;
  color: #fff;
}

.pricing{
  margin-top: 4rem;
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 2rem;
}

.pricing .card{
  padding: 3rem 2rem;
  background-color: #1a191b;
  display: flex;
  flex-direction: column;
  border: 2px solid transparent;
  border-radius: 15px;
  transition: all 0.3s ease;
}

.pricing .card:hover{
  background-color: #2b2a2c;
  color: #fff;
}

.pricing .card .content{
  flex: 1;
  margin-bottom: 2rem;
}

.pricing .card h4{
  margin-bottom: 1rem;
  color: #fff;
  font-size: 1.2rem;
  font-weight: 500;
}

.pricing .card h3{
  color: #fff;
  font-size: 2rem;
  padding-bottom: 1rem;
  margin-bottom: 2rem;
  font-weight: 600;
  border-bottom: 2px dashed #fff;
}

.pricing .card p{
  color: #fff; 
  margin-bottom: 0.75rem;
}

.pricing .card p i{
  color: #ccc;
  font-size: 1.2rem;
  margin-right: 0.6rem;
}

footer{
  position: relative;
  display: grid;
  grid-template-columns: 400px repeat(3, 1fr);
  gap: 4rem;
}

footer .column .logo{
  max-width: 100px;
  margin-bottom: 2rem;
}

footer .column p{
  color: #ccc;
  margin-bottom: 2rem;
}

footer .column .social{
  display: flex;
  align-items: center;
  gap: 1rem;
}

footer .column .social a{
  color: #ccc;
  border: 1px solid #ccc;
  padding: 5px 10px;
  font-size: 1.25rem;
  border-radius: 100%;
  transition: all 0.3s ease;
}

footer .column .social a:hover{
  color: #fff;
  background-color: #5d259e;
  border-color: #5d259e;
}

footer .column h4{
  color: #fff;
  margin-bottom: 2rem;
  font-size: 1.2rem;
  font-weight: 500;
}

footer .column > a{
  display: block;
  color: #ccc;
  margin-bottom: 1rem;
  transition: all 0.3s ease;
}

footer .column > a:hover{
  color: #6410c3;
}

</style>