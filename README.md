<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>DCX Solutions | Digital Corp. Excellence</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">

<style>
:root {
  --primary: #e50914;
  --bg-dark: #0d0d0d;
  --card-dark: #1a1a1a;
  --text-light: #ffffff;
  --text-muted: #bdbdbd;
}

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: 'Poppins', sans-serif;
}

body {
  background: var(--bg-dark);
  color: var(--text-light);
}

/* HEADER */
header {
  background: #000;
  padding: 15px 8%;
  display: flex;
  justify-content: space-between;
  align-items: center;
  border-bottom: 1px solid #222;
}

.logo {
  line-height: 1.1;
}

.logo h1 {
  color: var(--primary);
  font-size: 26px;
}

.logo span {
  font-size: 13px;
  color: var(--text-muted);
  letter-spacing: 1px;
}

nav a {
  margin-left: 25px;
  text-decoration: none;
  color: var(--text-light);
  font-weight: 500;
}

nav a:hover {
  color: var(--primary);
}

/* HERO */
.hero {
  height: 90vh;
  background: linear-gradient(rgba(0,0,0,0.7), rgba(0,0,0,0.7)),
  url('https://images.unsplash.com/photo-1556761175-4b46a572b786') center/cover;
  display: flex;
  align-items: center;
  justify-content: center;
  text-align: center;
  padding: 0 10%;
}

.hero h2 {
  font-size: 48px;
  margin-bottom: 15px;
}

.hero p {
  font-size: 18px;
  color: var(--text-muted);
  margin-bottom: 30px;
}

.hero button {
  padding: 14px 30px;
  border: none;
  background: var(--primary);
  color: white;
  font-size: 16px;
  cursor: pointer;
  border-radius: 6px;
}

/* SECTIONS */
section {
  padding: 70px 8%;
}

.section-title {
  text-align: center;
  margin-bottom: 50px;
}

.section-title h3 {
  font-size: 36px;
  color: var(--primary);
}

/* SERVICES */
.services {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(260px,1fr));
  gap: 25px;
}

.service-box {
  background: var(--card-dark);
  padding: 30px;
  border-radius: 12px;
  transition: 0.3s;
  border: 1px solid #222;
}

.service-box:hover {
  transform: translateY(-8px);
  border-color: var(--primary);
}

.service-box h4 {
  margin-bottom: 10px;
  color: var(--primary);
}

.service-box p {
  color: var(--text-muted);
}

/* ABOUT */
.about {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px,1fr));
  gap: 40px;
  align-items: center;
}

.about p {
  color: var(--text-muted);
}

/* CONTACT */
.contact {
  background: #000;
}

.contact form {
  max-width: 600px;
  margin: auto;
}

.contact input,
.contact textarea {
  width: 100%;
  padding: 14px;
  margin-bottom: 15px;
  border-radius: 6px;
  border: none;
  background: #1c1c1c;
  color: white;
}

.contact button {
  width: 100%;
  padding: 14px;
  background: var(--primary);
  border: none;
  color: white;
  font-size: 16px;
  border-radius: 6px;
  cursor: pointer;
}

.contact-info {
  text-align: center;
  margin-top: 25px;
  color: var(--text-muted);
}

.contact-info a {
  color: var(--primary);
  text-decoration: none;
}

/* FOOTER */
footer {
  background: #000;
  color: #888;
  text-align: center;
  padding: 20px;
  border-top: 1px solid #222;
}

/* RESPONSIVE */
@media(max-width:768px) {
  .hero h2 {
    font-size: 34px;
  }
}
</style>
</head>

<body>

<header>
  <div class="logo">
    <h1>DCX Solutions</h1>
    <span>Digital Corp. Excellence</span>
  </div>
  <nav>
    <a href="#services">Services</a>
    <a href="#about">About</a>
    <a href="#contact">Contact</a>
  </nav>
</header>

<section class="hero">
  <div>
    <h2>Smart Solutions for Digital Growth</h2>
    <p>IT • ERP • LMS • Digital Classrooms • Consultancy • Architecture & Construction Tech</p>
    <button onclick="document.getElementById('contact').scrollIntoView()">Get Started</button>
  </div>
</section>

<section id="services">
  <div class="section-title">
    <h3>Our Solutions</h3>
  </div>

  <div class="services">
    <div class="service-box">
      <h4>IT Solutions</h4>
      <p>Cloud, automation, cybersecurity & enterprise software solutions.</p>
    </div>

    <div class="service-box">
      <h4>ERP Systems</h4>
      <p>Finance, HR, inventory & business process automation.</p>
    </div>

    <div class="service-box">
      <h4>LMS & Digital Classrooms</h4>
      <p>Smart education platforms & virtual learning ecosystems.</p>
    </div>

    <div class="service-box">
      <h4>Business Growth & Consultancy</h4>
      <p>Strategy, scaling & digital transformation services.</p>
    </div>

    <div class="service-box">
      <h4>Architecture & Design</h4>
      <p>BIM tools, architectural design & visualization software.</p>
    </div>

    <div class="service-box">
      <h4>Construction Management</h4>
      <p>Project planning, monitoring & construction ERP systems.</p>
    </div>
  </div>
</section>

<section id="about">
  <div class="about">
    <div>
      <h3>Why DCX Solutions?</h3>
      <p>
        DCX Solutions delivers integrated technology, education, construction
        and business intelligence solutions designed for scale and excellence.
      </p>
    </div>
    <div>
      <img src="https://images.unsplash.com/photo-1522071820081-009f0129c71c"
           style="width:100%; border-radius:12px;">
    </div>
  </div>
</section>

<section id="contact" class="contact">
  <div class="section-title">
    <h3>Contact Us</h3>
  </div>

  <form>
    <input type="text" placeholder="Your Name" required>
    <input type="email" placeholder="Your Email" required>
    <textarea rows="5" placeholder="Your Requirement"></textarea>
    <button type="submit">Send Message</button>
  </form>

  <div class="contact-info">
    <p>Email us at</p>
    <a href="mailto:solutionsdcx@gmail.com">solutionsdcx@gmail.com</a>
  </div>
</section>

<footer>
  <p>© 2026 DCX Solutions. Digital Corp. Excellence.</p>
</footer>

</body>
</html>
