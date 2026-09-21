---
layout: null
---
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Downsville Ruritan Club</title>
  <style>
    * { box-sizing: border-box; margin: 0; padding: 0; }
    body { font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; background-color: #f8f9fa; color: #333; line-height: 1.6; }
    
    /* Navigation Bar */
    header { background-color: #003366; color: white; padding: 1rem 0; box-shadow: 0 2px 5px rgba(0,0,0,0.1); }
    .nav-container { max-width: 1000px; margin: 0 auto; display: flex; justify-content: space-between; align-items: center; padding: 0 1.5rem; }
    .logo { font-size: 1.4rem; font-weight: bold; color: #ffffff; text-decoration: none; }
    nav a { color: #d0e1f9; text-decoration: none; margin-left: 1.5rem; font-weight: 600; transition: color 0.2s; }
    nav a:hover { color: #ffffff; }

    /* Hero Banner */
    .hero { background: linear-gradient(rgba(0,51,102,0.85), rgba(0,51,102,0.85)), url('https://images.unsplash.com/photo-1517048676732-d65bc937f952?auto=format&fit=crop&w=1200&q=80') center/cover; color: white; padding: 4rem 1.5rem; text-align: center; }
    .hero h1 { font-size: 2.5rem; margin-bottom: 0.5rem; }
    .hero p { font-size: 1.2rem; opacity: 0.9; max-width: 600px; margin: 0 auto; }

    /* Layout Sections */
    .container { max-width: 1000px; margin: 3rem auto; padding: 0 1.5rem; }
    .grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); gap: 1.5rem; margin-top: 1.5rem; }
    .card { background: white; padding: 1.8rem; border-radius: 8px; box-shadow: 0 4px 6px rgba(0,0,0,0.05); border-top: 4px solid #003366; }
    .card h3 { color: #003366; margin-bottom: 0.8rem; }
    
    /* Button */
    .btn { display: inline-block; background-color: #003366; color: white; padding: 0.75rem 1.5rem; border-radius: 5px; text-decoration: none; font-weight: bold; margin-top: 1rem; transition: background 0.2s; }
    .btn:hover { background-color: #002244; }

    /* Footer */
    footer { background-color: #111; color: #aaa; text-align: center; padding: 2rem 1rem; margin-top: 4rem; font-size: 0.9rem; }
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
