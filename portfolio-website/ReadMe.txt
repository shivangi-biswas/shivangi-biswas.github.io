<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Portfolio</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet">
  <style>
    /* Existing styles */
    .navbar {
      position: sticky;
      top: 0;
      z-index: 1000;
    }

    section {
      padding-top: 70px;
    }

    html {
      scroll-behavior: smooth;
    }

    .navbar-nav .nav-link.active {
      color: #ff7ab5 !important;
    }

    .navbar-nav .nav-link {
      transition: color 0.3s ease;
    }

    .navbar-nav .nav-link:hover {
      color: #ff7ab5;
    }

    /* Additional styles for social media icons */
    .btn-pink {
      background-color: #ff7ab5;
      color: white;
    }
  </style>
</head>
<body>
  <!-- Existing Navbar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark fixed-top">
    <div class="container">
      <a class="navbar-brand" href="#">My Portfolio</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item">
            <a class="nav-link" href="#home">Home</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#about">About</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#projects">Projects</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#skills">Skills</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#contact">Contact</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- Home Section -->
  <section id="home" class="py-5">
    <div class="container text-center">
      <h1>Welcome to My Portfolio</h1>
      <p>Data Scientist | AI Enthusiast | Data Visualization Specialist</p>
    </div>
  </section>

  <!-- About Section -->
  <section id="about" class="py-5 bg-light">
    <div class="container text-center">
      <h2 class="mb-4">About</h2>
      <div class="d-flex justify-content-center">
        <img src="images/about/1.jpg" alt="Profile Picture"
             class="rounded-circle border border-dark"
             style="width: 200px; height: 200px; object-fit: cover;">
      </div>
      <div class="mt-4 mx-auto" style="max-width: 600px;">
        <p>
           Hi, I’m Shivangi, a passionate Data Analyst and AI Specialist with a proven
           track record of transforming raw data into actionable insights. With over 3 years of
           experience working with global brands, I specialize in creating dynamic dashboards,
           AI-driven solutions, and data strategies that drive growth and efficiency.
        </p>
        <p>
           Whether it's developing interactive dashboards using Tableau and Power BI,
           optimizing marketing campaigns through analytics,
           or building machine learning models to automate processes,
           I bring a unique blend of technical expertise and business acumen to every project.
        </p>
        <p>
          Operating from India, I strive to deliver exceptional results that align with
          client goals. Explore my portfolio to see how I can contribute to your success
          through analytics and innovation.
        </p>
      </div>
    </div>
  </section>

  <!-- Projects Section -->
  <section id="projects" class="py-5">
    <div class="container text-center">
      <h2 class="mb-5">Projects</h2>
      <div class="row">
        <div class="col-md-4 mb-4">
          <div class="card">
            <img src="images/projects/1.jpg" class="card-img-top" alt="Project 1" style="height: 200px; object-fit: cover;">
            <div class="card-body">
              <h5 class="card-title">Project 1</h5>
              <p class="card-text">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
              <a href="#" class="btn btn-primary">Blog Post</a>
              <a href="#" class="btn btn-secondary">Source Code</a>
            </div>
          </div>
        </div>
        <div class="col-md-4 mb-4">
          <div class="card">
            <img src="images/projects/2.jpg" class="card-img-top" alt="Project 2" style="height: 200px; object-fit: cover;">
            <div class="card-body">
              <h5 class="card-title">Project 2</h5>
              <p class="card-text">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
              <a href="#" class="btn btn-primary">Blog Post</a>
              <a href="#" class="btn btn-secondary">Source Code</a>
            </div>
          </div>
        </div>
        <div class="col-md-4 mb-4">
          <div class="card">
            <img src="images/projects/3.jpg" class="card-img-top" alt="Project 3" style="height: 200px; object-fit: cover;">
            <div class="card-body">
              <h5 class="card-title">Project 3</h5>
              <p class="card-text">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
              <a href="#" class="btn btn-primary">Blog Post</a>
              <a href="#" class="btn btn-secondary">Source Code</a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Skills Section -->
  <section id="skills" class="py-5">
    <div class="container text-center">
      <h2 class="mb-5">Skills</h2>
      <div class="row">
        <div class="col-md-3 mb-4">
          <div class="card">
            <img src="images/skills/1.png" class="card-img-top" alt="Python Icon" style="height: 100px; object-fit: contain;">
            <div class="card-body">
              <h5 class="card-title">Python</h5>
              <p class="card-text">Data analysis and machine learning</p>
              <a href="#" class="btn btn-primary">Learn More</a>
            </div>
          </div>
        </div>

        <div class="col-md-3 mb-4">
          <div class="card">
            <img src="images/skills/2.png" class="card-img-top" alt="Data Visualization Icon" style="height: 100px; object-fit: contain;">
            <div class="card-body">
              <h5 class="card-title">Data Visualization</h5>
              <p class="card-text">Creating insightful & interactive dashboards</p>
              <a href="#" class="btn btn-primary">Learn More</a>
            </div>
          </div>
        </div>

        <div class="col-md-3 mb-4">
          <div class="card">
            <img src="images/skills/3.png" class="card-img-top" alt="SQL Icon" style="height: 100px; object-fit: contain;">
            <div class="card-body">
              <h5 class="card-title">SQL</h5>
              <p class="card-text">Database querying and management</p>
              <a href="#" class="btn btn-primary">Learn More</a>
            </div>
          </div>
        </div>
        <div class="col-md-3 mb-4">
          <div class="card">
            <img src="images/skills/4.png" class="card-img-top" alt="Data Storytelling Icon" style="height: 100px; object-fit: contain;">
            <div class="card-body">
              <h5 class="card-title">Data Storytelling</h5>
              <p class="card-text">Communicating insights effectively</p>
              <a href="#" class="btn btn-primary">Learn More</a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Contact Section -->
  <section id="contact" class="py-5 bg-dark text-white">
    <div class="container text-center">
      <h2 class="mb-5">Contact Me</h2>
      <div class="row mb-4">
        <div class="col-md-6 mb-3">
          <div class="d-flex justify-content-center">
            <img src="images/icons/mail.png" alt="Email Icon" class="me-3" style="width: 30px;">
            <p class="mb-0">shivangibiswas2@gmail.com</p>
          </div>
        </div>
        <div class="col-md-6 mb-3">
          <div class="d-flex justify-content-center">
            <img src="images/icons/phone.png" alt="Phone Icon" class="me-3" style="width: 30px;">
            <p class="mb-0">+91 9971887449</p>
          </div>
        </div>
      </div>
      <div class="mb-4">
        <a href="https://www.linkedin.com/in/shivangi-biswas/" target="_blank" class="btn btn-pink rounded-circle mx-2" data-bs-toggle="tooltip" data-bs-placement="top" title="LinkedIn">
          <img src="images/icons/linkedin.png" alt="LinkedIn" style="width: 30px;">
        </a>
        <a href="https://github.com/Shivangi-biswas" target="_blank" class="btn btn-pink rounded-circle mx-2" data-bs-toggle="tooltip" data-bs-placement="top" title="GitHub">
          <img src="images/icons/github.png" alt="GitHub" style="width: 30px;">
        </a>
        <a href="https://medium.com/@shivangibiswas2" target="_blank" class="btn btn-pink rounded-circle mx-2" data-bs-toggle="tooltip" data-bs-placement="top" title="Medium">
          <img src="images/icons/medium.png" alt="Medium" style="width: 30px;">
        </a>
        <a href="https://www.instagram.com/words_of_a_witch/" target="_blank" class="btn btn-pink rounded-circle mx-2" data-bs-toggle="tooltip" data-bs-placement="top" title="YouTube">
          <img src="images/icons/insta.png" alt="YouTube" style="width: 30px;">
        </a>
      </div>
    </div>
  </section>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
