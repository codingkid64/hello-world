<!DOCTYPE html>
<html>
  <head>
    <title>My Website</title>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
  </head>
  <body>
    <header>
      <nav>
        <ul>
          <li><a href="#home">Home</a></li>
          <li><a href="#about">About</a></li>
          <li><a href="#services">Services</a></li>
          <li><a href="#contact">Contact</a></li>
        </ul>
      </nav>
    </header>
    <section id="home">
      <h1>Welcome to My Website</h1>
      <p>This is the first page of my website.</p>
    </section>
    <section id="about">
      <h2>About Us</h2>
      <p>We are a company that specializes in creating high-quality websites.</p>
    </section>
    <section id="services">
      <h2>Our Services</h2>
      <ul>
        <li>Website Design</li>
        <li>Website Development</li>
        <li>Search Engine Optimization</li>
      </ul>
    </section>
    <section id="contact">
      <h2>Contact Us</h2>
      <form action="submit-form.php" method="post">
        <label for="name">Name:</label>
        <input type="text" id="name" name="name" required>
        <label for="email">Email:</label>
        <input type="email" id="email" name="email" required>
        <label for="message">Message:</label>
        <textarea id="message" name="message" required></textarea>
        <button type="submit">Submit</button>
      </form>
    </section>
    <footer>
      <p>Copyright ©2022 My Website</p>
    </footer>
  </body>
</html>
