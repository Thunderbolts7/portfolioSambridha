<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sambridha Bhattarai - Web Developer Portfolio</title>
    <link rel="stylesheet" href="style.css">
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
</head>
<body>
    <!-- Navigation -->
    <nav class="navbar">
        <div class="nav-container">
            <div class="nav-logo">
                <h2>Sambridha</h2>
            </div>
            <div class="nav-menu">
                <a href="#home" class="nav-link">Home</a>
                <a href="#about" class="nav-link">About</a>
                <a href="#education" class="nav-link">Education</a>
                <a href="#skills" class="nav-link">Skills</a>
                <a href="#contact" class="nav-link">Contact</a>
            </div>
            <div class="hamburger">
                <span></span>
                <span></span>
                <span></span>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section id="home" class="hero">
        <div class="hero-container">
            <div class="hero-content">
                <h1 class="hero-title">
                    Hi, I'm <span class="highlight">Sambridha Bhattarai</span>
                </h1>
                <h2 class="hero-subtitle">Beginner Web Developer</h2>
                <p class="hero-description">
                    Passionate about creating beautiful and functional web experiences with 1 year of hands-on experience in HTML, CSS, and JavaScript.
                </p>
                <div class="hero-buttons">
                    <a href="#contact" class="btn btn-primary">Get In Touch</a>
                    <a href="#about" class="btn btn-secondary">Learn More</a>
                </div>
            </div>
            <div class="hero-image">
                <div class="profile-card">
                    <div class="profile-avatar">
                        <i class="fas fa-user"></i>
                    </div>
                    <div class="floating-elements">
                        <div class="floating-element" data-tech="HTML">
                            <i class="fab fa-html5"></i>
                        </div>
                        <div class="floating-element" data-tech="CSS">
                            <i class="fab fa-css3-alt"></i>
                        </div>
                        <div class="floating-element" data-tech="JS">
                            <i class="fab fa-js"></i>
                        </div>
                        <div class="floating-element" data-tech="C++">
                            <i class="fas fa-code"></i>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="about">
        <div class="container">
            <h2 class="section-title">About Me</h2>
            <div class="about-content">
                <div class="about-text">
                    <p class="about-description">
                        I'm a dedicated beginner web developer from Pokhara, Kaski, with a passion for creating engaging digital experiences. Over the past year, I've been immersing myself in web development technologies, building a solid foundation in HTML, CSS, and JavaScript.
                    </p>
                    <p class="about-description">
                        My journey in programming started with C++, which gave me a strong understanding of programming fundamentals. Now, I'm focused on web development, constantly learning new techniques and best practices to create modern, responsive websites.
                    </p>
                    <div class="about-info">
                        <div class="info-item">
                            <i class="fas fa-map-marker-alt"></i>
                            <span>Pokhara, Kaski</span>
                        </div>
                        <div class="info-item">
                            <i class="fas fa-envelope"></i>
                            <span>bhattaraisambridha@gmail.com</span>
                        </div>
                        <div class="info-item">
                            <i class="fas fa-phone"></i>
                            <span>+977-9861070277</span>
                        </div>
                        <div class="info-item">
                            <i class="fas fa-calendar"></i>
                            <span>1 Year Experience</span>
                        </div>
                    </div>
                </div>
                <div class="about-stats">
                    <div class="stat-card">
                        <h3>1+</h3>
                        <p>Year Experience</p>
                    </div>
                    <div class="stat-card">
                        <h3>4</h3>
                        <p>Technologies</p>
                    </div>
                    <div class="stat-card">
                        <h3>10+</h3>
                        <p>Projects</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Education Section -->
    <section id="education" class="education">
        <div class="container">
            <h2 class="section-title">Education</h2>
            <div class="education-timeline">
                <div class="timeline-item">
                    <div class="timeline-marker"></div>
                    <div class="timeline-content">
                        <h3>Secondary Education Examination (SEE)</h3>
                        <h4>SSCSS School</h4>
                        <span class="timeline-date">Completed</span>
                        <p class="timeline-description">
                            Successfully completed SEE with a GPA of 3.6+, demonstrating strong academic performance and dedication to learning.
                        </p>
                        <div class="achievement-badge">
                            <i class="fas fa-trophy"></i>
                            <span>GPA: 3.6+</span>
                        </div>
                    </div>
                </div>
                <div class="timeline-item">
                    <div class="timeline-marker"></div>
                    <div class="timeline-content">
                        <h3>Basic Level Examination</h3>
                        <h4>SSCSS School</h4>
                        <span class="timeline-date">Completed</span>
                        <p class="timeline-description">
                            Achieved excellent academic results in Basic Level Examination, securing a GPA of 3.60+ and building a strong educational foundation.
                        </p>
                        <div class="achievement-badge">
                            <i class="fas fa-trophy"></i>
                            <span>GPA: 3.60+</span>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Skills Section -->
    <section id="skills" class="skills">
        <div class="container">
            <h2 class="section-title">Skills & Technologies</h2>
            <div class="skills-grid">
                <div class="skill-card">
                    <div class="skill-icon">
                        <i class="fab fa-html5"></i>
                    </div>
                    <h3>HTML5</h3>
                    <p>Semantic markup and modern HTML features for building structured web content.</p>
                    <div class="skill-level advanced"></div>
                </div>
                <div class="skill-card">
                    <div class="skill-icon">
                        <i class="fab fa-css3-alt"></i>
                    </div>
                    <h3>CSS3</h3>
                    <p>Responsive design, animations, flexbox, and grid for beautiful user interfaces.</p>
                    <div class="skill-level advanced"></div>
                </div>
                <div class="skill-card">
                    <div class="skill-icon">
                        <i class="fab fa-js"></i>
                    </div>
                    <h3>JavaScript</h3>
                    <p>Dynamic functionality, DOM manipulation, and modern ES6+ features.</p>
                    <div class="skill-level intermediate"></div>
                </div>
                <div class="skill-card">
                    <div class="skill-icon">
                        <i class="fas fa-code"></i>
                    </div>
                    <h3>C++</h3>
                    <p>Programming fundamentals, object-oriented concepts, and problem-solving skills.</p>
                    <div class="skill-level beginner"></div>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="contact">
        <div class="container">
            <h2 class="section-title">Get In Touch</h2>
            <div class="contact-content">
                <div class="contact-info">
                    <h3>Let's Connect</h3>
                    <p>I'm always interested in new opportunities and collaborations. Feel free to reach out!</p>
                    <div class="contact-details">
                        <div class="contact-item">
                            <i class="fas fa-envelope"></i>
                            <div>
                                <h4>Email</h4>
                                <p>bhattaraisambridha@gmail.com</p>
                            </div>
                        </div>
                        <div class="contact-item">
                            <i class="fas fa-phone"></i>
                            <div>
                                <h4>Phone</h4>
                                <p>+977-9861070277</p>
                            </div>
                        </div>
                        <div class="contact-item">
                            <i class="fas fa-map-marker-alt"></i>
                            <div>
                                <h4>Location</h4>
                                <p>Pokhara, Kaski, Nepal</p>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="contact-form">
                    <form id="contactForm">
                        <div class="form-group">
                            <input type="text" id="name" name="name" placeholder="Your Name" required>
                        </div>
                        <div class="form-group">
                            <input type="email" id="email" name="email" placeholder="Your Email" required>
                        </div>
                        <div class="form-group">
                            <input type="text" id="subject" name="subject" placeholder="Subject" required>
                        </div>
                        <div class="form-group">
                            <textarea id="message" name="message" placeholder="Your Message" rows="5" required></textarea>
                        </div>
                        <button type="submit" class="btn btn-primary">
                            <span class="btn-text">Send Message</span>
                            <span class="btn-loading">
                                <i class="fas fa-spinner fa-spin"></i>
                            </span>
                        </button>
                    </form>
                    <div class="form-message" id="formMessage"></div>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="footer">
        <div class="container">
            <p>&copy; 2024 Sambridha Bhattarai. All rights reserved.</p>
        </div>
    </footer>

    <script src="https://cdnjs.cloudflare.com/ajax/libs/gsap/3.12.2/gsap.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/gsap/3.12.2/ScrollTrigger.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/@emailjs/browser@3/dist/email.min.js"></script>
    <script src="script.js"></script>
</body>
</html>
