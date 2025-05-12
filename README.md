# spac<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>SPACE DECOR & DESIGN</title>
  <style>
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      margin: 0;
      padding: 0;
      background: linear-gradient(to right, #f5f7fa, #c3cfe2);
      color: #333;
    }
    header {
      background: linear-gradient(to right, #6a11cb, #2575fc);
      color: white;
      padding: 2rem;
      text-align: center;
    }
    header img {
      max-width: 120px;
      margin-bottom: 1rem;
    }
    nav a {
      margin: 0 1rem;
      color: white;
      text-decoration: none;
      font-weight: bold;
    }
    section {
      padding: 2rem;
      background: white;
      margin: 1rem auto;
      max-width: 1000px;
      border-radius: 12px;
      box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
    }
    h2 {
      color: #2575fc;
    }
    .services ul {
      list-style: none;
      padding: 0;
    }
    .services li {
      background-color: #e0f7fa;
      margin-bottom: 1rem;
      padding: 1rem;
      border-left: 5px solid #00796b;
      border-radius: 8px;
      font-weight: 500;
    }
    .contact a {
      color: #00796b;
      text-decoration: none;
      font-weight: bold;
    }
    .gallery {
      display: flex;
      flex-wrap: wrap;
      gap: 1rem;
      justify-content: center;
    }
    .gallery img {
      width: 100%;
      max-width: 300px;
      border-radius: 12px;
      box-shadow: 0 4px 12px rgba(0,0,0,0.2);
      transition: transform 0.3s ease;
    }
    .gallery img:hover {
      transform: scale(1.05);
    }
    footer {
      text-align: center;
      background-color: #2575fc;
      color: white;
      padding: 1rem;
    }
    form {
      display: flex;
      flex-direction: column;
      gap: 1rem;
      max-width: 400px;
      margin-top: 1rem;
    }
    input, textarea {
      padding: 0.75rem;
      border: 1px solid #ccc;
      border-radius: 6px;
      font-size: 1rem;
    }
    button {
      padding: 0.75rem;
      background-color: #6a11cb;
      color: white;
      border: none;
      border-radius: 6px;
      font-size: 1rem;
      cursor: pointer;
    }
    #whatsapp-button {
      position: fixed;
      bottom: 20px;
      right: 20px;
      background-color: #25D366;
      color: white;
      padding: 15px;
      border-radius: 50%;
      box-shadow: 0 2px 6px rgba(0,0,0,0.2);
      font-size: 24px;
      text-align: center;
      z-index: 1000;
      text-decoration: none;
    }
  </style>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
</head>
<body>
  <header>
    <img src="logo-placeholder.png" alt="SPACE DECOR & DESIGN Logo" />
    <h1>SPACE DECOR & DESIGN</h1>
    <p>Interior Design & Turnkey Solutions in Asansol, Durgapur & Nearby Areas</p>
    <nav>
      <a href="#about">About</a>
      <a href="#services">Services</a>
      <a href="#contact">Contact</a>
      <a href="#social">Social</a>
      <a href="#gallery">Gallery</a>
    </nav>
  </header>

  <section id="about">
    <h2>About Us</h2>
    <p><strong>Welcome to SPACE DECOR & DESIGN</strong> — your trusted destination for innovative, personalized interior solutions in Asansol, Durgapur, and surrounding areas. As a passionate and growing interior startup, we specialize in transforming everyday spaces into elegant, functional, and inspiring environments. Our mission is to blend creativity with practicality, delivering end-to-end interior services tailored to your lifestyle and vision. Whether it's a complete home makeover, turnkey project, modular kitchen, or renovation, our skilled team works closely with you from concept to completion. At SPACE DECOR & DESIGN, we believe every space tells a story — let us help you craft yours.</p>
  </section>

  <section id="services" class="services">
    <h2>Our Services</h2>
    <ul>
      <li>🔹 Turnkey Residential Projects</li>
      <li>🔹 Home Renovation & Remodeling</li>
      <li>🔹 Modular Kitchens & Wardrobes</li>
      <li>🔹 End-to-End Interior Execution</li>
      <li>🔹 Design & Consultation</li>
    </ul>
  </section>

  <section id="gallery">
    <h2>Our Work</h2>
    <div class="gallery">
      <img src="image1-placeholder.jpg" alt="Interior project 1">
      <img src="image2-placeholder.jpg" alt="Interior project 2">
      <img src="image3-placeholder.jpg" alt="Interior project 3">
      <img src="image4-placeholder.jpg" alt="Interior project 4">
    </div>
  </section>

  <section id="contact" class="contact">
    <h2>Contact Us</h2>
    <p>📍 Asansol, Durgapur & Nearby Areas</p>
    <p>📞 <a href="tel:+919749245481">+91 97492 45481</a></p>

    <form action="https://formspree.io/f/your-form-id" method="POST">
      <input type="text" name="name" placeholder="Your Name" required />
      <input type="email" name="email" placeholder="Your Email" required />
      <textarea name="message" rows="5" placeholder="Your Message" required></textarea>
      <button type="submit">Send Message</button>
    </form>
    <p style="font-size: 0.9rem; color: gray;">*Form submission requires Formspree setup (free).</p>
  </section>

  <section id="social">
    <h2>Follow Us</h2>
    <p>
      📘 <a href="https://www.facebook.com/share/1CG4sH527X/" target="_blank">Facebook</a><br />
      📸 <a href="https://www.instagram.com/spacedecordesign?igsh=dHAzZG83bmJoaHFo" target="_blank">Instagram</a>
    </p>
  </section>

  <footer>
    <p>&copy; 2025 SPACE DECOR & DESIGN. All Rights Reserved.</p>
  </footer>

  <a id="whatsapp-button" href="https://wa.me/919749245481" target="_blank">
    <i class="fab fa-whatsapp"></i>
  </a>
</body>
</html>
e-decor-design
