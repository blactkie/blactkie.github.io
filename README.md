<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Morley Tec - Capabilities</title>
  <style>
    /* Add your CSS styles here */
    body {
      font-family: sans-serif;
      margin: 0;
      padding: 0;
    }
    header {
      background-color: #f1f1f1;
      padding: 20px;
    }
    h1, h2 {
      margin: 0;
    }
    nav {
      display: flex;
      justify-content: space-around;
      padding: 20px;
    }
    nav li {
      list-style: none;
    }
    nav a {
      text-decoration: none;
      color: black;
    }
    main {
      padding: 20px;
    }
    section {
      margin-bottom: 20px;
    }
    footer {
      text-align: center;
      padding: 20px;
      background-color: #f1f1f1;
    }
  </style>
</head>
<body>
  <header>
    <h1>Morley Tec</h1>
    <h2>Showcasing Our Expertise</h2>
  </header>

  <nav>
    <ul>
      <li><a href="#about">About Us</a></li>
      <li><a href="#services">Our Services</a></li>
      <li><a href="#portfolio">Our Portfolio</a></li>
      <li><a href="#contact">Contact Us</a></li>
    </ul>
  </nav>

  <main>
    <section id="about">
      <h2>About Us</h2>
      <p>Morley Tec is a company dedicated to [ Briefly describe your industry or area of focus ]. 
        We are a team of passionate professionals with a proven track record of success. 
        Our mission is to [ Briefly state your company's mission ].</p>
    </section>

    <section id="services">
      <h2>Our Services</h2>
      <p>At Morley Tec, we offer a comprehensive range of services to help you achieve your goals. 
        These include: [ List your core services with a brief description of each (around 25 words each) ]. 
        We take pride in our [ Highlight a key strength related to your services, e.g., personalized approach, innovative solutions ].</p>
    </section>

    <section id="portfolio">
      <h2>Our Portfolio</h2>
      <p>We've had the pleasure of working on a variety of projects for diverse clients. 
        Explore our portfolio to see examples of our work and how we can help you achieve similar success. 
        [ Briefly mention if you'll include case studies or project summaries here ].</p>
        </section>

    <section id="contact">
      <h2>Contact Us</h2>
      <p>We'd love to hear from you and discuss how Morley Tec can assist you with your needs. 
        Feel free to reach out using the contact form below or directly at [ Your phone number (optional) ].</p>
      <form action="contact-form.php" method="post">
        <label for="name">Name:</label>
        <input type="text" id="name" name="name" required>
        <label for="email">Email:</label>
        <input type="email" id="email" name="email" required>
        <label for="message">Message:</label>
        <textarea id="message" name="message" required></textarea>
        <button type="submit">Send Message</button>
      </form>
    </section>
  </main>

  <footer>
    <p>&copy; Morley Tec - <?php echo date("Y"); ?></p>
    <p>Contact: <a href="mailto:youremail@morleytec.com">youremail@morleytec.com</a></p>
    <a href="https://www.facebook.com/your-facebook-page"><
