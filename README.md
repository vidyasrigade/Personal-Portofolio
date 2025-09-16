<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>VidyaSri | Software Engineer </title>

    <!-- Bootstrap 5 CDN -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet" />

    <!-- Embedded Custom CSS -->
    <style>
        body {
            font-family: 'Segoe UI', sans-serif;
            background-color: #f8f9fa;
            line-height: 1.6;
        }

        h2 {
            color: #343a40;
            font-weight: 600;
        }

        .card:hover {
            transform: scale(1.02);
            transition: transform 0.3s ease;
        }

        .navbar-nav .nav-link:hover {
            text-decoration: underline;
            color: #007bff;
        }

        footer {
            font-size: 0.9rem;
        }

        img {
            transition: transform 0.3s ease;
        }

        img:hover {
            transform: rotate(-1deg) scale(1.05);
        }

        .skill-box {
            border: 2px solid #080808;
            /* Example border color */
            background-color: #f8f9fa;
            /* Light background color */
            padding: 20px;
            border-radius: 8px;
            /* Rounded corners for a softer look */
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            /* Subtle shadow for depth */
            transition: transform 0.3s ease-in-out;
            /* Smooth transition for hover effect */
            cursor: pointer;
        }

        .skill-box:hover {
            transform: translateY(-5px);
            /* Lift the box on hover */
            box-shadow: 0 8px 16px rgba(0, 0, 0, 0.2);
            /* Enhance shadow on hover */
        }
    </style>
</head>

<body>

    <!-- Header -->
    <header class="bg-dark text-white text-center py-4">
        <h1>Gade Vidya Sri</h1>
        <p>I am a Solution Architect.</p>
    </header>

    <!-- Navbar -->
    <nav class="navbar navbar-expand-lg navbar-light bg-light sticky-top">
        <div class="container">
            <a class="navbar-brand" href="#">My Portfolio</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item"><a class="nav-link" href="#about">About</a></li>
                    <li class="nav-item"><a class="nav-link" href="#skills">Skills</a></li>
                    <li class="nav-item"><a class="nav-link" href="#projects">Projects</a></li>
                    <li class="nav-item"><a class="nav-link" href="#contact">Contact</a></li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- About Section -->
    <section id="about" class="container py-5">
        <div class="row align-items-center">
            <div class="col-md-4 text-center">
                <img src="https://www.bing.com/th/id/OIP.ErLtQNCeJTiNdFPr0eJuuAHaHa?w=201&h=211&c=8&rs=1&qlt=90&o=6&dpr=1.5&pid=3.1&rm=2"
                    alt="Profile" class="rounded-circle img-fluid" />
            </div>
            <div class="col-md-8">
                <h2>About Me</h2>
                <p>Hi, I'm Vidya Sri Gade, a passionate and detail-oriented Software Engineer based in Bangalore. I
                    thrive on solving complex problems and building scalable, user-centric solutions that make a real
                    impact. With a strong foundation in software development and a continuous drive to learn, I enjoy
                    working across the stack—from crafting intuitive front-end experiences to architecting robust
                    back-end systems.

                    I believe in clean code, collaborative teamwork, and the power of technology to transform lives.
                    Whether it's optimizing performance, exploring new frameworks, or mentoring peers, I bring energy
                    and curiosity to every project I take on.

                    When I'm not coding, you’ll find me exploring new tech trends, contributing to open-source, or
                    enjoying a good book with a cup of chai.</p>
            </div>
        </div>
    </section>

    <!-- Skills Section -->
    <section id="skills" class="bg-light py-5">
        <div class="container">
            <h2 class="text-center mb-4">Skills</h2>
            <div class="row text-center g-4">
                <div class="col-md-3 skill-box">Python</div>
                <div class="col-md-3 skill-box">Java</div>
                <div class="col-md-3 skill-box">JavaScript</div>
                <div class="col-md-3 skill-box">SQL</div>
            </div>
        </div>
    </section>

    <!-- Projects Section -->
    <section id="projects" class="container py-5">
        <h2 class="text-center mb-4">Projects</h2>
        <div class="row g-4">
            <div class="col-md-4">
                <div class="card h-100 shadow-sm">
                    <div class="card-body">
                        <h5 class="card-title">CDMA Crossbar </h5>
                        <p class="card-text">Designed and implemented a crossbar switch using Code Division Multiple
                            Access (CDMA) for efficient data routing.
                            Utilized orthogonal codes to enable simultaneous data transmission across shared
                            communication lines.
                            Improved bandwidth utilization and reduced latency in multi-channel communication systems.
                            Simulated and validated the design using HDL tools, ensuring scalability and performance.
                        </p>
                    </div>
                </div>
            </div>
            <div class="col-md-4">
                <div class="card h-100 shadow-sm">
                    <div class="card-body">
                        <h5 class="card-title">Colour Display</h5>
                        <p class="card-text">Developed a color display system using an Arduino Uno and an RGB LED
                            matrix.
                            Programmed dynamic color transitions and patterns using PWM and custom logic.
                            Integrated user input via buttons/potentiometers to control color modes in real-time.
                            Enhanced visual output with smooth fading effects and modular code structure.</p>

                    </div>
                </div>
            </div>
            <div class="col-md-4">
                <div class="card h-100 shadow-sm">
                    <div class="card-body">
                        <h5 class="card-title">E-Commerce Website</h5>
                        <p class="card-text">Built a fully functional e-commerce platform with product listings, shopping cart, and secure checkout.
Implemented user authentication, order management, and responsive UI using modern web technologies.
Integrated payment gateway and real-time inventory updates for seamless user experience.
Used technologies like HTML, CSS, JavaScript, and backend with Node.js/PHP and MySQL/MongoDB.

</p>

                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="bg-light py-5">
        <div class="container">
            <h2 class="text-center mb-4">Contact Me</h2>
            <form>
                <div class="mb-3">
                    <label for="name" class="form-label">Your Name</label>
                    <input type="text" class="form-control" id="name" required />
                </div>
                <div class="mb-3">
                    <label for="email" class="form-label">Your Email</label>
                    <input type="email" class="form-control" id="email" required />
                </div>
                <div class="mb-3">
                    <label for="message" class="form-label">Your Message</label>
                    <textarea class="form-control" id="message" rows="4" required></textarea>
                </div>
                <button type="submit" class="btn btn-success">Send Message</button>
            </form>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-dark text-white text-center py-3">
        <p>&copy; 2025 Vidya Sri Gade</p>
    </footer>

    <!-- Bootstrap JS Bundle -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"></script>
</body>

</html>
