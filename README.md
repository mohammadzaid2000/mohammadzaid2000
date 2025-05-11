<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Couchtocareer_wfh</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      line-height: 1.6;
      color: #333;
      background: #f9f9f9;
    }
    header {
      background: #1e1e2f;
      color: #fff;
      padding: 1rem 2rem;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }
    header nav a {
      color: #fff;
      text-decoration: none;
      margin: 0 1rem;
    }
    .hero {
      background: #fffae6;
      text-align: center;
      padding: 4rem 2rem;
    }
    .hero h1 {
      font-size: 2.5rem;
      margin-bottom: 1rem;
    }
    .hero p {
      font-size: 1.2rem;
      margin-bottom: 2rem;
    }
    .hero button {
      padding: 0.8rem 2rem;
      font-size: 1rem;
      border: none;
      background: #ff8c42;
      color: white;
      border-radius: 5px;
      cursor: pointer;
    }
    section {
      padding: 3rem 2rem;
      max-width: 1000px;
      margin: auto;
    }
    .benefits, .resources {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 2rem;
    }
    .benefits div, .resources div {
      background: #fff;
      padding: 1.5rem;
      border-radius: 8px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.05);
    }
    footer {
      background: #1e1e2f;
      color: #fff;
      text-align: center;
      padding: 2rem;
    }
    footer a {
      color: #ffa94d;
      margin: 0 0.5rem;
    }
    form {
      display: flex;
      flex-direction: column;
      gap: 1rem;
      max-width: 500px;
      margin: auto;
    }
    form input, form textarea {
      padding: 0.8rem;
      border: 1px solid #ccc;
      border-radius: 5px;
      font-size: 1rem;
    }
    form button {
      background: #ff8c42;
      color: white;
      border: none;
      padding: 0.8rem;
      cursor: pointer;
      font-size: 1rem;
      border-radius: 5px;
    }
  </style>
</head>
<body>

  <header>
    <h2>Couchtocareer_wfh</h2>
    <nav>
      <a href="#about">About</a>
      <a href="#benefits">Benefits</a>
      <a href="#resources">Resources</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section class="hero">
    <h1>Turn Your Couch Into a Career Hub</h1>
    <p>Join thousands building careers from their living rooms—without the commute.</p>
    <button>Start Your WFH Journey</button>
  </section>

  <section id="about">
    <h2>About Us</h2>
    <p>At <strong>Couchtocareer_wfh</strong>, we help remote workers thrive by offering guidance, tools, and motivation to succeed from home. Whether you're just starting or scaling your freelance business, we've got your back.</p>
  </section>

  <section id="benefits">
    <h2>Why Work From Home?</h2>
    <div class="benefits">
      <div><strong>Flex Your Time:</strong> Work when you’re most productive</div>
      <div><strong>Save Money:</strong> No commute, no office rent</div>
      <div><strong>Live Better:</strong> More time for family and self</div>
      <div><strong>Work Globally:</strong> Clients and jobs across the world</div>
    </div>
  </section>

  <section id="resources">
    <h2>Free WFH Resources</h2>
    <div class="resources">
      <div><strong>Starter Kit:</strong> WFH setup checklist (Free PDF)</div>
      <div><strong>Job Boards:</strong> Best remote job platforms</div>
      <div><strong>Video Tutorials:</strong> Learn how to focus, plan & manage time</div>
      <div><strong>Newsletter:</strong> Weekly success tips</div>
    </div>
    <br/>
    <button>Download Free Toolkit</button>
  </section>

  <section id="contact">
    <h2>Contact Us</h2>
    <p>Questions, ideas, or just want to say hi?</p>
    <form>
      <input type="text" placeholder="Your Name" required />
      <input type="email" placeholder="Your Email" required />
      <textarea rows="4" placeholder="Your Message"></textarea>
      <button type="submit">Send Message</button>
    </form>
  </section>

  <footer>
    <p>© 2025 Couchtocareer_wfh | All rights reserved</p>
    <p>Follow us:
      <a href="#">Instagram</a> |
      <a href="#">LinkedIn</a> |
      <a href="#">YouTube</a>
    </p>
  </footer>

</body>
</html>
