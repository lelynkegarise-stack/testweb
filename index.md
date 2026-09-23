---
layout: default
title: Home
---

<!-- ===== Intro Section ===== -->
<div class="intro">
  <h1>
    Welcome to the Downsville Ruritan Club!<br>
  </h1>
  <img src="{{ '/images/rlogo.png' | relative_url }}" alt="logo" class="logo1">

  <p>
    Serving Downsville, Maryland and the surrounding area since 1954.
    Ruritans’ purpose is to create a better understanding among people and improve America’s communities
    through volunteer community service. Our slogan is "Fellowship, Goodwill, and Community Service."
    People of all occupations, social positions, and backgrounds are encouraged to join.
  </p>
  <!--- <div class="button-container">
    <button class="button" onclick="window.location.href='{{ '/tipjarWinners.html' | relative_url }}';">
      Carnival Tip Jar Winners 2026
    </button>
  </div>--->
</div>

<!-- ===== Location Section (Responsive) ===== -->
<section class="location-container">
  <div class="location-content">
    <div class="location-text">
      <h2>Downsville Ruritan Club</h2>
      <p>
        Our community building and mailing address is located at:<br>
        8629 Downsville Pike, Williamsport, Maryland 21795
      </p>
    </div>
    <div class="button-container"></div>
    <div class="location-map">
      <iframe
        src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3060.395219312246!2d-77.779747184623!3d39.58825497948585!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x89c9f104e3fba97f%3A0x1760e52c7485a60a!2s8629%20Downsville%20Pike%2C%20Williamsport%2C%20MD%2021795!5e0!3m2!1sen!2sus!4v1707483271971!5m2!1sen!2sus"
        width="100%" height="250" style="border:0;" loading="lazy" allowfullscreen="">
      </iframe>
    </div>
  </div>
</section>    footer { background-color: #111; color: #aaa; text-align: center; padding: 2rem 1rem; margin-top: 4rem; font-size: 0.9rem; }
  </style>
</head>
<body>

  <!-- NAVBAR -->
  <header>
    <div class="nav-container">
      <a href="#" class="logo">Downsville Ruritan Club</a>
      <nav>
        <a href="#">Home</a>
        <a href="#about">About</a>
        <a href="#meetings">Meetings</a>
        <a href="#rentals">Hall Rentals</a>
      </nav>
    </div>
  </header>

  <!-- HERO SECTION -->
  <section class="hero">
    <h1>Downsville Ruritan Club</h1>
    <p>Serving the Downsville, MD community through fellowship, goodwill, and local support.</p>
  </section>

  <!-- MAIN CONTENT GRID -->
  <div class="container">
    <div class="grid">
      
      <!-- MEETING CARD -->
      <div class="card" id="meetings">
        <h3>Regular Meetings</h3>
        <p><strong>When:</strong> 2nd Tuesday of every month at 7:00 PM</p>
        <p><strong>Where:</strong> Community Center Hall</p>
        <p style="margin-top: 0.5rem;">All community members and guests are welcome to attend!</p>
      </div>

      <!-- HALL RENTALS CARD -->
      <div class="card" id="rentals">
        <h3>Community Hall Rentals</h3>
        <p>Planning a family gathering, birthday party, or local meeting? Our facility is open for public rental.</p>
        <ul style="margin: 0.8rem 0 0.8rem 1.2rem;">
          <li><strong>Capacity:</strong> Up to 150 guests</li>
          <li><strong>Amenities:</strong> Kitchen, tables, chairs, parking</li>
        </ul>
        <a href="mailto:info@downsvilleruritan.com" class="btn">Inquire About Rental</a>
      </div>

    </div>
  </div>

  <!-- FOOTER -->
  <footer>
    <p>Downsville Ruritan Club &bull; Downsville Ruritan Community Center, Downsville, MD 21733</p>
    <p>&copy; 2026 Downsville Ruritan Club. All rights reserved.</p>
  </footer>

</body>
</html>
