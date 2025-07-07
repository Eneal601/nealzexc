<!DOCTYPE html> 
<html lang="en" dir="ltr">
<head>
  <meta charset="UTF-8">
  <title>Morzess</title>
  <link rel="stylesheet" href="css.css">
  <link rel="stylesheet" href="https://unpkg.com/aos@next/dist/aos.css" />
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
  <style>
    .cursor {
      font-weight: 500;
      color: #b74b4b;
      animation: blink 0.8s infinite;
    }

    @keyframes blink {
      0%, 100% { opacity: 1; }
      50% { opacity: 0; }
    }
  </style>
</head>
<body>S

  <!-- Navigation Menu -->
  <nav data-aos="fade-down">
    <div class="nav-container">
      <div class="logo"><span>Morzess</span></div>
      <div class="link"><a href="#">Home</a></div>
      <div class="link"><a href="#">About</a></div>
      <div class="link"><a href="#">Hobby</a></div>
      <div class="link"><a href="#">Favorite Games</a></div>
      <div class="link"><a href="#">Fight Scene</a></div>
      <div>
        <i class="fa-solid fa-bars hamburg" onclick="hamburg()"></i>
      </div>
    </div>
  </nav>

  <br><br>

  <!-- Hero Section -->
  <section>
    <div class="main-container">
      <div class="image" data-aos="fade-right">
        <div class="hero-img-circle">
          <img src="MP.jpeg" alt="Profile Image">
        </div>
      </div>
      <div class="content" data-aos="fade-left">
        <h1>Hey, I'm<span class="name"> Morzess</span></h1>
        <div class="typewriter">
          I'm a <span class="typewriter-text"></span><span class="cursor">|</span>
        </div>
        <p>Web Developmen Assigment (WAT5103)</p>
        <div class="social-links" data-aos="fade-up">
          <a href="#"><i class="fa-brands fa-github"></i></a>
          <a href="#"><i class="fa-brands fa-discord"></i></a>
          <a href="#"><i class="fa-brands fa-facebook"></i></a>
          <a href="#"><i class="fa-brands fa-youtube"></i></a>
        </div>
      </div>
    </div>
  </section>

  <!-- About Section -->
  <section class="about" id="about">
    <div>
      <div class="title" data-aos="fade-up"><span>About Me</span></div>
      <div class="about-details">
        <div class="left" data-aos="fade-right">
          <img src="MP.jpeg" alt="About Image" />
        </div>
        <div class="right" data-aos="fade-left">
          <div class="topic"></div>
          <p>Hi, Morzess Ken O'neal Lukin. I was born on April, 21,2003, and i'm 22 years old this years. Im originally from kudat and completed my secondary education at SMK Matunggong. I have one brother</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Hobby Section -->
  <section class="skills" id="skills">
    <div class="content">
      <div class="title" data-aos="fade-up"><span>Hobby</span></div>
      <div class="skills-details">
        <div class="text" data-aos="fade-right">
          <div class="topic"></div>
          <p>My hobby is playing video games. I enjoy spending my free time playing games like Dota 2, Mobile Legends, Wuthering Waves, Monster Hunter: World, and Punishing: Gray Raven. These games are fun, exciting, and help me relax. I like learning new skills in the games and sometimes play with my friends, which makes it even more enjoyable. Playing games is a hobby that makes me happy and keeps me entertained.
          </p>
        </div>
      </div>
    </div>
  </section>

  <!-- Favorite Games Section -->
  <section class="services" id="services">
    <div class="content">
      <div class="title" data-aos="fade-up"><span>Favorite Games</span></div>
      <div class="boxes">

        <!-- Row 1 -->
        <div class="box" data-aos="zoom-in" data-aos-delay="100">
          <div class="icon"><img src="D2.jpg" alt="Dota 2" style="width: 100%; height: 100%; border-radius: 50%; object-fit: cover;"></div>
          <div class="topic">Dota 2</div>
          <p>Genre:Strategy/MOBA</p>
        </div>

        <div class="box" data-aos="zoom-in" data-aos-delay="200">
          <div class="icon"><img src="ml.jpg" alt="Mobile Legends" style="width: 100%; height: 100%; border-radius: 50%; object-fit: cover;"></div>
          <div class="topic">Mobile Legends</div>
          <p>Genre:Strategy/Advanture/MOBA</p>
        </div>

        <div class="box" data-aos="zoom-in" data-aos-delay="300">
          <div class="icon"><img src="WW.png" alt="Wuthering Waves" style="width: 100%; height: 100%; border-radius: 50%; object-fit: cover;"></div>
          <div class="topic">Wuthering Waves</div>
          <p>Genre:Role-Play(RPG)/Advanture</p>
        </div>

        <!-- Row 2 -->
        <div class="box" data-aos="zoom-in" data-aos-delay="400">
          <div class="icon"><img src="mhw.jpg" alt="Monster Hunter World" style="width: 100%; height: 100%; border-radius: 50%; object-fit: cover;"></div>
          <div class="topic">Monster Hunter: World</div>
          <p>Genre:Action Role-Playing Game</p>
        </div>

        <div class="box" data-aos="zoom-in" data-aos-delay="500">
          <div class="icon"><img src="PGR.png" alt="Punishing Gray Raven" style="width: 100%; height: 100%; border-radius: 50%; object-fit: cover;"></div>
          <div class="topic">Punishing: Gray Raven</div>
          <p>Genre:Hack And Slash/Advanture</p>
        </div>

      </div>
    </div>
  </section>

  <!-- Fight Scene Section -->
  <section class="contact" id="contact">
    <video autoplay muted loop id="background">
      <source src="fight-scene.mp4" type="video/mp4" />
    </video>
    <div class="content" data-aos="fade-up">
      <div class="title"><span>Fight Scene</span></div>
    </div>
  </section>

  <!-- Footer -->
  <footer data-aos="fade-up">
    <div class="text">
      <p>Created by <strong>Morzess</strong> &copy; 2025 All Rights Reserved</p>
    </div>
  </footer>

  <!-- AOS and Typewriter Script -->
  <script src="https://unpkg.com/aos@next/dist/aos.js"></script>
  <script>
    AOS.init({
      duration: 1000,
      once: true
    });
  </script>

  <script>
    const words = ["Student", "Gamer"]; // Customize this list
    let i = 0;
    let j = 0;
    let currentWord = "";
    let isDeleting = false;
    const speed = 150;
    const typewriterText = document.querySelector(".typewriter-text");

    function type() {
      if (i < words.length) {
        if (!isDeleting && j <= words[i].length) {
          currentWord = words[i].substring(0, j++);
          typewriterText.textContent = currentWord;
          setTimeout(type, speed);
        } else if (isDeleting && j >= 0) {
          currentWord = words[i].substring(0, j--);
          typewriterText.textContent = currentWord;
          setTimeout(type, speed / 2);
        } else if (!isDeleting && j > words[i].length) {
          isDeleting = true;
          setTimeout(type, 1000);
        } else if (isDeleting && j < 0) {
          isDeleting = false;
          i = (i + 1) % words.length;
          setTimeout(type, speed);
        }
      }
    }

    document.addEventListener("DOMContentLoaded", () => {
      type();
    });
  </script>

  <!-- Custom Script -->
  <script src="script.js"></script>

</body>
</html>
