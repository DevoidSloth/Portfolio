<script>
    import "./styles.css";
</script>


<nav class="navbar">
  <ul>
    <li><a href="#head"><i class="fas fa-home"></i><span>Home</span></a></li>
    <li><a href="#about"><i class="fas fa-user"></i><span>About Me</span></a></li>
    <li><a href="#projects"><i class="fas fa-laptop-code"></i><span>Projects</span></a></li>
    <li><a href="#contact"><i class="fas fa-envelope"></i><span>Contact</span></a></li>
  </ul>
</nav>
<!-- Head section -->
<section id="head" class="head">
  <!-- Background image -->
  <div class="bg-image"></div>
  <!-- Overlay with name and tagline -->
  <div class="overlay">
    <h1>Jason Pitchford 👋</h1>
    <h2>Bot Developer and AI Designer</h2>
  </div>
</section>
<!-- About me section -->
<section id="about" class="about">
  <!-- Horizontal timeline -->
  <div class="timeline">
    <!-- Timeline item -->
    <div class="timeline-item">
      <!-- Timeline content -->
      <div class="timeline-content">
        <h3>2018</h3>
        <p>Started coding via Florida Virtual</p>
      </div>
    </div>
    <!-- Timeline item -->
    <div class="timeline-item">
      <!-- Timeline content -->
      <div class="timeline-content">
        <h3>2020</h3>
        <p>Started to look into game development and made my first games.</p>
      </div>
    </div>
    <!-- Timeline item -->
    <div class="timeline-item">
      <!-- Timeline content -->
      <div class="timeline-content">
        <h3>2021</h3>
        <p>Begun tinkering with AI and machine learning.</p>
      </div>
    </div>
    <!-- Timeline item -->
    <div class="timeline-item">
      <!-- Timeline content -->
      <div class="timeline-content">
        <h3>2022</h3>
        <p>Started building applicationsa and websites using machine learning</p>
      </div>
    </div>
    <!-- Timeline item -->
    <div class="timeline-item">
      <!-- Timeline content -->
      <div class="timeline-content">
        <h3>2023</h3>
        <p>Built Entity my first machine learning package to make multiagent systems easier for the public.</p>
      </div>
    </div>
  </div>
</section>

<!-- Projects section -->
<section id="projects" class="projects">
  <!-- Carousel layout -->
  <div class="carousel">
    <!-- Carousel item -->
    <div class="carousel-item">
      <!-- Project image -->
      <img src="src/Entity Logo (1).png" alt="Project 1">
      <!-- Project description -->
      <p>Entity is a system to allow beginners and more experienced programmers to enjoy working with muiltiagent neural networks and to allow the general public to learn more about them.</p>
    </div>
    <!-- Carousel item -->
    <div class="carousel-item">
      <!-- Project image -->
      <img src="src/on09x8wc.bmp" alt="Project 2">
      <!-- Project description -->
      <p>Confines is a game in progress about trying to survive on an island while getting stronger. It weaves together survival game mechanics with rougelike elements..</p>
    </div>
    <!-- Carousel item -->
    <div class="carousel-item">
      <!-- Project image -->
      <img src="src/b3ng5e98.bmp" alt="Project 3">
      <!-- Project description -->
      <p>LINA is an AI assistant capable of managing a calculator. She is quite versitile and getting better with the help of entity.</p>
    </div>
    <!-- Left arrow -->
    <!-- <div class="arrow left"><i class="fas fa-chevron-left"></i></div> -->
    <!-- Right arrow -->
    <!-- <div class="arrow right"><i class="fas fa-chevron-right"></i></div> -->
  </div>
</section>
<!-- Contact section -->
<section id="contact" class="contact">
  <!-- Map with location and popup -->
  <div class="map">
    <!-- Map iframe -->
    <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3579.581637115508!2d-80.0997606849788!3d26.93422498313029!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x88ded55a5fbc10d9%3A0x8019b6c0aee28f6b!2sJupiter%2C%20FL%2C%20USA!5e0!3m2!1sen!2sin!4v1633715845437!5m2!1sen!2sin" allowfullscreen="" loading="lazy"></iframe>
    <!-- Popup window -->
    <div class="popup">
      <h3>Contact Me</h3>
      <ul>
        <li><i class="fas fa-phone"></i><span>+1 561 676 3897</span></li>
        <li><i class="fas fa-envelope"></i><span>Jasonpitchford@gmail.com</span></li>
        <li><i class="fas fa-globe"></i><span>www.jasonpitchford.com</span></li>
      </ul>
    </div>
  </div>
</section>
