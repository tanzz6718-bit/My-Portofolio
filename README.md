
<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Portofolio Saya</title>
  <style>
    /* Reset */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Poppins', sans-serif;
      background: #f4f6f9;
      color: #2d3436;
      line-height: 1.6;
    }

    header {
      background: linear-gradient(135deg, #6c5ce7, #00cec9);
      color: white;
      padding: 50px 20px;
      text-align: center;
    }

    header img {
      width: 150px;
      height: 150px;
      border-radius: 50%;
      border: 4px solid white;
      margin-bottom: 15px;
      object-fit: cover;
    }

    header h1 {
      font-size: 2.2em;
    }

    header p {
      font-size: 1.2em;
      opacity: 0.9;
    }

    nav {
      background: #2d3436;
      padding: 10px;
      text-align: center;
    }

    nav a {
      color: white;
      margin: 0 15px;
      text-decoration: none;
      font-weight: 500;
      transition: color 0.3s;
    }

    nav a:hover {
      color: #00cec9;
    }

    .container {
      max-width: 1000px;
      margin: 40px auto;
      padding: 20px;
    }

    section {
      margin-bottom: 50px;
    }

    h2 {
      margin-bottom: 20px;
      font-size: 1.8em;
      border-left: 6px solid #6c5ce7;
      padding-left: 10px;
      color: #2d3436;
    }

    .about p {
      font-size: 1.1em;
    }

    .projects {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }

    .project-card {
      background: white;
      padding: 20px;
      border-radius: 12px;
      box-shadow: 0 6px 15px rgba(0,0,0,0.1);
      transition: transform 0.3s;
    }

    .project-card:hover {
      transform: translateY(-5px);
    }

    .contact form {
      display: grid;
      gap: 15px;
    }

    input, textarea {
      padding: 12px;
      font-size: 1em;
      border: 1px solid #ccc;
      border-radius: 8px;
      outline: none;
      transition: border 0.3s;
    }

    input:focus, textarea:focus {
      border-color: #6c5ce7;
    }

    button {
      padding: 12px;
      border: none;
      border-radius: 8px;
      background: linear-gradient(135deg, #6c5ce7, #00cec9);
      color: white;
      font-size: 1em;
      cursor: pointer;
      transition: transform 0.3s;
    }

    button:hover {
      transform: scale(1.05);
    }

    footer {
      background: #2d3436;
      color: white;
      text-align: center;
      padding: 20px;
      margin-top: 40px;
    }
  </style>
</head>
<body>
  <header>
    <!-- Ganti 'foto.jpg' dengan foto kamu -->
    <img src="foto.jpg" alt="Foto Profil">
    <h1>Tristan Febian H.</h1>
    <p>Web Developer | Designer | Programmer</p>
  </header>

  <nav>
    <a href="#about">Tentang Saya</a>
    <a href="#projects">Projek</a>
    <a href="#contact">Kontak</a>
  </nav>

  <div class="container">
    <section id="about" class="about">
      <h2>👤 Tentang Saya</h2>
      <p>
        Halo! Saya adalah seorang pelajar yang sedang belajar pemrograman web. 
        Saya suka membuat website yang modern, elegan, dan interaktif. 
        Saya memiliki ketertarikan pada desain UI/UX dan pengembangan aplikasi.
      </p>
    </section>

    <section id="projects" class="projects">
      <h2>💻 Projek Saya</h2>
      <div class="project-card">
        <h3>Kas Kelas</h3>
        <p>Aplikasi web sederhana untuk mencatat kas kelas dengan total otomatis.</p>
      </div>
      <div class="project-card">
        <h3>Peminjaman Buku</h3>
        <p>Web form peminjaman buku perpustakaan yang menampilkan data dalam tabel.</p>
      </div>
      <div class="project-card">
        <h3>Portofolio</h3>
        <p>Website portofolio pribadi elegan dengan desain responsif.</p>
      </div>
    </section>

    <section id="contact" class="contact">
      <h2>📩 Kontak</h2>
      <form>
        <input type="text" placeholder="Nama" required>
        <input type="email" placeholder="Email" required>
        <textarea rows="5" placeholder="Pesan kamu..." required></textarea>
        <button type="submit">Kirim</button>
      </form>
    </section>
  </div>

  <footer>
    <p>© 2025 Teistan Febian H. | Dibuat dengan ❤️</p>
  </footer>
</body>
</html>
