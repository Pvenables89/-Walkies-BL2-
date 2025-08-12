<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Pawsome Walks - Dog Walking Services</title>
  <style>
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      margin: 0;
      background-color: #f9f9f9;
      color: #333;
    }
    header {
      background-color: #6c9a4f;
      color: white;
      padding: 1rem;
      text-align: center;
    }
    nav {
      display: flex;
      justify-content: center;
      background-color: #547a33;
    }
    nav a {
      color: white;
      text-decoration: none;
      padding: 1rem 2rem;
      display: block;
    }
    nav a:hover {
      background-color: #466828;
    }
    main {
      max-width: 900px;
      margin: 2rem auto;
      padding: 0 1rem;
    }
    section {
      margin-bottom: 3rem;
    }
    h1, h2 {
      color: #405d27;
    }
    footer {
      text-align: center;
      padding: 1rem;
      background-color: #6c9a4f;
      color: white;
      position: fixed;
      bottom: 0;
      width: 100%;
    }
    form {
      display: flex;
      flex-direction: column;
      max-width: 400px;
      margin-top: 1rem;
    }
    label {
      margin: 0.5rem 0 0.2rem;
    }
    input, textarea {
      padding: 0.5rem;
      font-size: 1rem;
      border: 1px solid #ccc;
      border-radius: 4px;
    }
    button {
      margin-top: 1rem;
      background-color: #547a33;
      color: white;
      border: none;
      padding: 0.7rem;
      font-size: 1rem;
      border-radius: 4px;
      cursor: pointer;
    }
    button:hover {
      background-color: #466828;
    }
    @media (max-width: 600px) {
      nav {
        flex-direction: column;
      }
      nav a {
        padding: 0.8rem;
      }
      footer {
        position: static;
      }
    }
  </style>
</head>
<body>
  <header>
    <h1>Pawsome Walks</h1>
    <p>Your trusted dog walking service</p>
  </header>

  <nav>
    <a href="#home">Home</a>
    <a href="#about">About Us</a>
    <a href="#services">Services</a>
    <a href="#contact">Contact</a>
  </nav>

  <main>
    <section id="home">
      <h2>Welcome to Pawsome Walks!</h2>
      <p>We provide caring and reliable dog walking services to keep your furry friends happy and healthy. Whether your dog needs a quick walk or a long adventure, we’re here to help!</p>
    </section>

    <section id="about">
      <h2>About Us</h2>
      <p>At Pawsome Walks, our team loves dogs and has years of experience in dog care. We treat every dog like our own and prioritize safety, fun, and exercise.</p>
    </section>

    <section id="services">
      <h2>Our Services</h2>
      <ul>
        <li>30-minute walk - $15</li>
        <li>60-minute walk - $25</li>
        <li>Group walks (up to 3 dogs) - $20 per dog</li>
        <li>Pet sitting and feeding available upon request</li>
      </ul>
    </section>

    <section id="contact">
      <h2>Contact Us</h2>
      <p>Have questions or want to book a walk? Get in touch!</p>
      <form>
        <label for="name">Name</label>
        <input id="name" name="name" type="text" required />

        <label for="email">Email</label>
        <input id="email" name="email" type="email" required />

        <label for="message">Message</label>
        <textarea id="message" name="message" rows="4" required></textarea>

        <button type="submit">Send</button>
      </form>
    </section>
  </main>

  <footer>
    &copy; 2025 Pawsome Walks. All rights reserved.
  </footer>
</body>
</html> 
