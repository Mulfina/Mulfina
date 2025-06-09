<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Personal Website</title>
    <link rel="stylesheet" href="css/style.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&family=Montserrat:wght@300;400;500;600&display=swap" rel="stylesheet">
</head>
<body>
    <div class="cursor"></div>
    <div class="cursor-follower"></div>

    <header>
        <div class="logo">
            <h1>My<span>Portfolio</span></h1>
        </div>
        <div class="toggle-menu">
            <div class="hamburger"></div>
        </div>
        <nav class="navbar">
            <ul>
                <li><a href="#home" class="active">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <!-- Home Section -->
        <section id="home" class="home-section">
            <div class="container">
                <div class="content">
                    <div class="text-content">
                        <h1 class="greeting">Hello, I'm</h1>
                        <h2 class="name">Mulfina</h2>
                        <p class="description">Welcome to my personal website. I'm passionate about creating beautiful things and sharing my journey with the world.</p>
                        <div class="cta-buttons">
                            <a href="#about" class="btn primary-btn">About Me</a>
                            <a href="#contact" class="btn secondary-btn">Get In Touch</a>
                        </div>
                    </div>
                    <div class="image-content">
                        <div class="profile-image-container">
                            <img src="d:\All Data\Documents\tugas semester 2 fina\WhatsApp Image 2025-06-09 at 19.34.20.jpeg" alt="Profile Image" class="profile-image">
                        </div>
                    </div>
                </div>
                <div class="social-icons">
                    <a href="#" class="social-icon"><i class="fab fa-instagram"></i></a>
                    <a href="#" class="social-icon"><i class="fab fa-twitter"></i></a>
                    <a href="#" class="social-icon"><i class="fab fa-linkedin-in"></i></a>
                    <a href="#" class="social-icon"><i class="fab fa-github"></i></a>
                </div>
            </div>
        </section>

        <!-- About Section -->
        <section id="about" class="about-section">
            <div class="container">
                <div class="section-title">
                    <h2>About Me</h2>
                    <div class="underline"></div>
                </div>
                <div class="content">
                    <div class="image-content">
                        <div class="about-image-container">
                            <img src="d:\All Data\Documents\tugas semester 2 fina\WhatsApp Image 2025-06-09 at 20.23.32.jpeg" alt="About Image" class="about-image">
                        </div>
                    </div>
                    <div class="text-content">
                        <h3>Who Am I?</h3>
                        <p>Hello, I'm a second-semester student at the University of West Sulawesi, majoring in Information Systems within the Faculty of Engineering. I currently reside in Majene. In my leisure time, I enjoy reading novels, browsing TikTok, and relaxing while listening to music. Fried rice is my favorite dish, always satisfying my taste buds.</p>
                        
                        <h3>My Journey</h3>
                        <p>During my studies at the University of West Sulawesi, I not only gained knowledge, but also beautiful memories and deep friendships. Friends who I consider like my own family, always support each other in every step, including when working on assignments together. When one of us faces difficulties, the others sincerely help. The brotherhood that is formed here is truly extraordinary, and I hope this bond will continue to be maintained forever.</p>
                        
                        <h3>My Skills</h3>
                        <div class="skills">
                            <div class="skill">
                                <span class="skill-name">Skill 1</span>
                                <div class="skill-bar">
                                    <div class="skill-progress" style="width: 90%"></div>
                                </div>
                            </div>
                            <div class="skill">
                                <span class="skill-name">Skill 2</span>
                                <div class="skill-bar">
                                    <div class="skill-progress" style="width: 87%"></div>
                                </div>
                            </div>
                            <div class="skill">
                                <span class="skill-name">Skill 3</span>
                                <div class="skill-bar">
                                    <div class="skill-progress" style="width: 85%"></div>
                                </div>
                            </div>
                            <div class="skill">
                                <span class="skill-name">Skill 4</span>
                                <div class="skill-bar">
                                    <div class="skill-progress" style="width: 78%"></div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Contact Section -->
        <section id="contact" class="contact-section">
            <div class="container">
                <div class="section-title">
                    <h2>Get In Touch</h2>
                    <div class="underline"></div>
                </div>
                <div class="content">
                    <div class="contact-info">
                        <div class="contact-item">
                            <div class="icon">
                                <i class="fas fa-map-marker-alt"></i>
                            </div>
                            <div class="text">
                                <h3>Location</h3>
                                <p>FX5M+Q7R, Tim., Baurung, Kec. Banggae Tim., Kabupaten Majene, Sulawesi Barat 91412</p>
                            </div>
                        </div>
                        <div class="contact-item">
                            <div class="icon">
                                <i class="fas fa-envelope"></i>
                            </div>
                            <div class="text">
                                <h3>Email</h3>
                                <p>mulfina77@gmail.com</p>
                            </div>
                        </div>
                        <div class="contact-item">
                            <div class="icon">
                                <i class="fas fa-phone"></i>
                            </div>
                            <div class="text">
                                <h3>Phone</h3>
                                <p>+6283137132506</p>
                            </div>
                        </div>
                    </div>
                    <div class="contact-form">
                        <form id="contactForm">
                            <div class="form-group">
                                <input type="text" id="name" placeholder="Your Name" required>
                            </div>
                            <div class="form-group">
                                <input type="email" id="email" placeholder="Your Email" required>
                            </div>
                            <div class="form-group">
                                <input type="text" id="subject" placeholder="Subject" required>
                            </div>
                            <div class="form-group">
                                <textarea id="message" placeholder="Your Message" required></textarea>
                            </div>
                            <button type="submit" class="btn primary-btn">Send Message</button>
                        </form>
                    </div>
                </div>
            </div>
        </section>
    </main>

    <footer>
        <div class="container">
            <div class="footer-content">
                <div class="copyright">
                    <p>&copy; 2025 Your Name. All Rights Reserved.</p>
                </div>
                <div class="social-icons">
                    <a href="#" class="social-icon"><i class="fab fa-instagram"></i></a>
                    <a href="#" class="social-icon"><i class="fab fa-twitter"></i></a>
                    <a href="#" class="social-icon"><i class="fab fa-linkedin-in"></i></a>
                    <a href="#" class="social-icon"><i class="fab fa-github"></i></a>
                </div>
            </div>
        </div>
    </footer>

    <script src="js/script.js"></script>
</body>
</html>
