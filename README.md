<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Shehzad Editor - Portfolio</title>
  <style>
    :root {
      --bg-color: #0d0d0d;
      --text-color: #ffffff;
      --accent-color: #0ef;
      --card-bg: #1a1a1a;
      --border-color: #333;
    }* { margin: 0; padding: 0; box-sizing: border-box; }
body {
  font-family: 'Segoe UI', sans-serif;
  background: var(--bg-color);
  color: var(--text-color);
  line-height: 1.6;
}
header {
  background: var(--card-bg);
  padding: 40px 20px;
  text-align: center;
  animation: fadeIn 2s ease-in;
}
header h1 { font-size: 2.8rem; color: var(--accent-color); }
header p { font-size: 1.2rem; color: #aaa; }
nav { text-align: center; margin: 20px 0; }
nav a {
  color: var(--accent-color);
  margin: 0 15px;
  text-decoration: none;
  font-weight: bold;
  transition: color 0.3s;
}
nav a:hover { color: var(--text-color); }
section {
  max-width: 1000px;
  margin: auto;
  padding: 40px 20px;
  animation: slideUp 1.5s ease-in;
}
h2 { color: var(--accent-color); margin-bottom: 20px; }
ul {
  list-style: none;
  display: flex;
  flex-wrap: wrap;
  gap: 10px;
}
li {
  background: var(--card-bg);
  padding: 10px 20px;
  border-radius: 8px;
  border: 1px solid var(--border-color);
}
.contact { background: var(--card-bg); text-align: center; }
.contact a { color: var(--accent-color); text-decoration: none; }
.gallery {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 20px;
  margin-top: 20px;
}
.gallery img,
.gallery video {
  width: 100%;
  border-radius: 10px;
  transition: transform 0.3s;
  background-color: var(--border-color);
}
.gallery img:hover,
.gallery video:hover {
  transform: scale(1.05);
}
form {
  margin-top: 30px;
  display: flex;
  flex-direction: column;
  gap: 15px;
  align-items: center;
}
input,
textarea {
  width: 100%;
  max-width: 500px;
  padding: 10px;
  border: none;
  border-radius: 5px;
  font-size: 1rem;
  background: #222;
  color: var(--text-color);
}
textarea {
  resize: vertical;
  min-height: 100px;
}
button {
  padding: 10px 20px;
  background: var(--accent-color);
  color: #000;
  font-weight: bold;
  border: none;
  border-radius: 5px;
  cursor: pointer;
  transition: background 0.3s;
}
button:hover {
  background: #00c7c7;
}
footer {
  background: #1a1a1a;
  text-align: center;
  padding: 10px;
  color: #888;
}
@keyframes fadeIn {
  from { opacity: 0; transform: translateY(-30px); }
  to { opacity: 1; transform: translateY(0); }
}
@keyframes slideUp {
  from { opacity: 0; transform: translateY(40px); }
  to { opacity: 1; transform: translateY(0); }
}

  </style>
</head>
<body>
  <header>
    <h1>Shehzad Editor</h1>
    <p>Professional Banner, Thumbnail, and Video Editor</p>
  </header>  <nav>
    <a href="#about">About</a>
    <a href="#skills">Skills</a>
    <a href="#work">Work</a>
    <a href="#contact">Contact</a>
  </nav>  <section id="about">
    <h2>About Me</h2>
    <p>I am a passionate editor with 2 years of experience in editing action, dramatic, aggressive, comedy, and vlog content. I specialize in making banners, thumbnails, videos, layouts, and more using tools like Lightroom, Pixellab, and Kinemaster.</p>
  </section>  <section id="skills">
    <h2>My Skills</h2>
    <div class="skills">
      <h3>Editing Areas</h3>
      <ul>
        <li>Banner Editing</li>
        <li>Thumbnail Creation</li>
        <li>Video Editing</li>
        <li>Photo Retouching</li>
        <li>Layout Design</li>
      </ul>
    </div>
    <div class="tools">
      <h3>Tools I Use</h3>
      <ul>
        <li>Lightroom</li>
        <li>Pixellab</li>
        <li>Kinemaster</li>
      </ul>
    </div>
    <div class="genres">
      <h3>Genres I Edit</h3>
      <ul>
        <li>Action</li>
        <li>Dramatic</li>
        <li>Aggressive</li>
        <li>Comedy</li>
        <li>Vlogs</li>
      </ul>
    </div>
  </section>  <section id="work">
    <h2>My Work</h2>
    <div class="gallery">
      <img src="https://i.imgur.com/Y8cRhyn.jpg" alt="Edited Thumbnail 1">
      <img src="https://i.imgur.com/UWhWaMx.jpg" alt="Edited Thumbnail 2">
      <img src="https://i.imgur.com/3TcdvKe.jpg" alt="Edited Thumbnail 3">
      <video controls>
        <source src="https://www.w3schools.com/html/mov_bbb.mp4" type="video/mp4">
        Your browser does not support the video tag.
      </video>
    </div>
  </section>  <section id="contact" class="contact">
    <h2>Contact Me</h2>
    <p>📞 WhatsApp: <strong>6280813882</strong></p>
    <p>📸 Instagram: <a href="https://instagram.com/SKYxShehzad" target="_blank">@SKYxShehzad</a></p><form action="https://formspree.io/f/moqgwqpe" method="POST">
  <input type="text" name="name" placeholder="Your Name" required>
  <input type="email" name="email" placeholder="Your Email" required>
  <textarea name="message" placeholder="Your Message" required></textarea>
  <button type="submit">Send Message</button>
</form>
<p style="margin-top:10px; font-size: 0.9rem; color: #aaa;">This form is powered by Formspree.</p>

  </section>  <footer>
    <p>&copy; 2025 Shehzad Editor. All rights reserved.</p>
  </footer>
</body>
</html># Shehzadeditor-
