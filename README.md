<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Daya Yadav- Technical Lead</title>
    <style>
 {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', 'Roboto', 'Oxygen',
    'Ubuntu', 'Cantarell', 'Fira Sans', 'Droid Sans', 'Helvetica Neue',
    sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #3d3d3d;
  line-height: 1.6;
  background-color: #fefaf6;
}

/* ============================================
   NAVIGATION - Cream & Warm Brown
   ============================================ */

.navbar {
  background: linear-gradient(135deg, #f5f1e8 0%, #e8dfd2 100%);
  color: #3d3d3d;
  padding: 1rem 2rem;
  position: sticky;
  top: 0;
  z-index: 100;
  box-shadow: 0 2px 8px rgba(61, 61, 61, 0.08);
  border-bottom: 2px solid #d4c5b0;
}

.nav-content {
  max-width: 1200px;
  margin: 0 auto;
  display: flex;
  justify-content: space-between;
  align-items: center;
  flex-wrap: wrap;
  gap: 1rem;
}

.logo {
  font-size: 28px;
  font-weight: 700;
  letter-spacing: -0.5px;
  color: #6b5344;
}

.nav-links {
  display: flex;
  gap: 1.5rem;
  flex-wrap: wrap;
}

.nav-link {
  background: none;
  border: none;
  color: #8b7355;
  cursor: pointer;
  font-size: 16px;
  font-weight: 500;
  transition: all 0.3s ease;
  padding: 0.5rem 0;
  border-bottom: 2px solid transparent;
}

.nav-link:hover {
  color: #6b5344;
  border-bottom-color: #d4a574;
}

.nav-link.active {
  color: #6b5344;
  border-bottom-color: #d4a574;
  font-weight: 600;
}

/* ============================================
   HERO SECTION - Cream Gradient
   ============================================ */

.hero {
  background: linear-gradient(135deg, #fefaf6 0%, #f5f1e8 50%, #ede5d8 100%);
  color: #3d3d3d;
  padding: 6rem 2rem;
  text-align: center;
  min-height: 500px;
  display: flex;
  align-items: center;
  justify-content: center;
  animation: fadeIn 0.8s ease-in;
  border-bottom: 1px solid #e8dfd2;
}

.hero-content h2 {
  font-size: 56px;
  margin-bottom: 1rem;
  font-weight: 700;
  letter-spacing: -1px;
  color: #6b5344;
}

.hero .tagline {
  font-size: 24px;
  margin-bottom: 1rem;
  opacity: 0.9;
  font-weight: 300;
  color: #8b7355;
}

.hero .subtitle {
  font-size: 18px;
  margin-bottom: 2rem;
  opacity: 0.85;
  letter-spacing: 1px;
  color: #9d8b76;
}

.cta-button {
  background: linear-gradient(135deg, #d4a574 0%, #c89456 100%);
  color: white;
  border: none;
  padding: 14px 40px;
  font-size: 16px;
  font-weight: 600;
  border-radius: 30px;
  cursor: pointer;
  transition: all 0.3s ease;
  box-shadow: 0 4px 15px rgba(212, 165, 116, 0.3);
}

.cta-button:hover {
  transform: translateY(-3px);
  box-shadow: 0 6px 25px rgba(212, 165, 116, 0.4);
}

/* ============================================
   CONTAINER
   ============================================ */

.container {
  max-width: 1200px;
  margin: 0 auto;
  padding: 0 2rem;
}

.section {
  padding: 4rem 2rem;
  animation: slideInUp 0.6s ease-out;
  background-color: #fefaf6;
}

.section:nth-child(even) {
  background-color: #f5f1e8;
}

.section h3 {
  font-size: 42px;
  margin-bottom: 3rem;
  text-align: center;
  position: relative;
  padding-bottom: 1rem;
  color: #6b5344;
}

.section h3::after {
  content: '';
  position: absolute;
  bottom: 0;
  left: 50%;
  transform: translateX(-50%);
  width: 60px;
  height: 4px;
  background: linear-gradient(90deg, #d4a574 0%, #c89456 100%);
  border-radius: 2px;
}

/* ============================================
   ABOUT SECTION
   ============================================ */

.about-section {
  background: #f5f1e8;
}

.about-content {
  max-width: 900px;
  margin: 0 auto;
}

.about-content p {
  font-size: 16px;
  line-height: 1.8;
  margin-bottom: 1.5rem;
  color: #5d5d5d;
}

.about-stats {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
  gap: 2rem;
  margin-top: 3rem;
  padding-top: 2rem;
  border-top: 2px solid #e8dfd2;
}

.stat {
  text-align: center;
}

.stat-number {
  font-size: 36px;
  font-weight: 700;
  background: linear-gradient(135deg, #d4a574 0%, #c89456 100%);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  background-clip: text;
}

.stat-label {
  font-size: 14px;
  color: #8b7355;
  margin-top: 0.5rem;
  text-transform: uppercase;
  letter-spacing: 0.5px;
  font-weight: 600;
}

/* ============================================
   SKILLS SECTION
   ============================================ */

.skills-section {
  background: #fefaf6;
}

.skills-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(400px, 1fr));
  gap: 3rem;
  margin-top: 2rem;
}

.skills-category {
  background: white;
  padding: 2rem;
  border-radius: 10px;
  border-left: 4px solid #d4a574;
  box-shadow: 0 2px 8px rgba(212, 165, 116, 0.1);
}

.skills-category h4 {
  font-size: 20px;
  color: #d4a574;
  margin-bottom: 1.5rem;
  text-transform: uppercase;
  letter-spacing: 1px;
}

.skill-item {
  margin-bottom: 1.5rem;
}

.skill-item h5 {
  font-size: 16px;
  margin-bottom: 0.8rem;
  color: #6b5344;
  font-weight: 600;
}

.skill-tags {
  display: flex;
  flex-wrap: wrap;
  gap: 0.5rem;
}

.skill-tag {
  background: #fefaf6;
  color: #d4a574;
  border: 2px solid #d4a574;
  padding: 6px 12px;
  border-radius: 20px;
  font-size: 13px;
  font-weight: 500;
  transition: all 0.3s ease;
  cursor: default;
}

.skill-tag:hover {
  background: #d4a574;
  color: white;
}

/* ============================================
   PROJECTS SECTION
   ============================================ */

.projects-section {
  background: #f5f1e8;
}

.projects-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 2rem;
  margin-top: 2rem;
}

.project-card {
  background: white;
  border-radius: 10px;
  overflow: hidden;
  box-shadow: 0 4px 6px rgba(61, 61, 61, 0.08);
  transition: all 0.3s ease;
  display: flex;
  flex-direction: column;
  height: 100%;
  border-top: 4px solid #d4a574;
}

.project-card:hover {
  transform: translateY(-8px);
  box-shadow: 0 12px 24px rgba(212, 165, 116, 0.15);
}

.project-header {
  background: linear-gradient(135deg, #f5f1e8 0%, #ede5d8 100%);
  color: #6b5344;
  padding: 2rem;
  min-height: 120px;
  display: flex;
  align-items: center;
  border-bottom: 1px solid #e8dfd2;
}

.project-header h4 {
  font-size: 20px;
  font-weight: 600;
  color: #6b5344;
}

.project-description {
  padding: 1.5rem;
  color: #5d5d5d;
  font-size: 14px;
  line-height: 1.6;
  flex-grow: 1;
}

.project-tech {
  padding: 0 1.5rem;
  display: flex;
  flex-wrap: wrap;
  gap: 0.5rem;
}

.tech-badge {
  background: #fef5f0;
  color: #d4a574;
  padding: 4px 10px;
  border-radius: 15px;
  font-size: 12px;
  font-weight: 500;
  border: 1px solid #e8dfd2;
}

.project-links {
  padding: 1.5rem;
  display: flex;
  gap: 1rem;
  border-top: 1px solid #e8dfd2;
}

.project-link {
  color: #d4a574;
  text-decoration: none;
  font-weight: 600;
  transition: all 0.3s ease;
  display: inline-block;
}

.project-link:hover {
  color: #c89456;
  text-decoration: underline;
}

/* ============================================
   EXPERIENCE SECTION
   ============================================ */

.experience-section {
  background: #fefaf6;
}

.timeline {
  position: relative;
  max-width: 900px;
  margin: 2rem auto;
}

.timeline::before {
  content: '';
  position: absolute;
  left: 50%;
  transform: translateX(-50%);
  width: 3px;
  height: 100%;
  background: linear-gradient(180deg, #d4a574 0%, #c89456 100%);
}

.timeline-item {
  margin-bottom: 3rem;
  position: relative;
}

.timeline-item:nth-child(odd) {
  padding-right: 52%;
  text-align: right;
}

.timeline-item:nth-child(even) {
  padding-left: 52%;
  text-align: left;
}

.timeline-marker {
  position: absolute;
  left: 50%;
  transform: translateX(-50%);
  width: 16px;
  height: 16px;
  background: white;
  border: 3px solid #d4a574;
  border-radius: 50%;
  top: 0;
  z-index: 10;
}

.timeline-content {
  background: white;
  padding: 1.5rem;
  border-radius: 8px;
  border-left: 3px solid #d4a574;
  box-shadow: 0 2px 8px rgba(212, 165, 116, 0.1);
}

.timeline-content h4 {
  font-size: 18px;
  color: #d4a574;
  margin-bottom: 0.5rem;
  font-weight: 600;
}

.company {
  color: #8b7355;
  font-size: 14px;
  margin-bottom: 1rem;
  font-style: italic;
}

.achievements {
  list-style: none;
}

.achievements li {
  margin-bottom: 0.8rem;
  padding-left: 1.5rem;
  position: relative;
  color: #5d5d5d;
  font-size: 14px;
  line-height: 1.6;
}

.achievements li::before {
  content: '✓';
  position: absolute;
  left: 0;
  color: #d4a574;
  font-weight: bold;
}

@media (max-width: 768px) {
  .timeline::before {
    left: 10px;
  }

  .timeline-marker {
    left: 10px;
  }

  .timeline-item:nth-child(odd),
  .timeline-item:nth-child(even) {
    padding-left: 50px;
    padding-right: 0;
    text-align: left;
  }

  .timeline-content {
    border-left: 3px solid #d4a574;
  }
}

/* ============================================
   CONTACT SECTION
   ============================================ */

.contact-section {
  background: #f5f1e8;
}

.contact-intro {
  text-align: center;
  font-size: 16px;
  color: #5d5d5d;
  max-width: 600px;
  margin: 0 auto 3rem;
  line-height: 1.8;
}

.contact-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
  gap: 2rem;
  margin-bottom: 3rem;
}

.contact-card {
  background: white;
  padding: 2rem;
  border-radius: 10px;
  text-align: center;
  box-shadow: 0 4px 6px rgba(61, 61, 61, 0.08);
  transition: all 0.3s ease;
  border-top: 3px solid #d4a574;
}

.contact-card:hover {
  transform: translateY(-5px);
  box-shadow: 0 8px 12px rgba(212, 165, 116, 0.15);
}

.contact-icon {
  font-size: 32px;
  color: #d4a574;
  margin-bottom: 1rem;
}

.contact-card h4 {
  font-size: 18px;
  color: #6b5344;
  margin-bottom: 0.8rem;
  font-weight: 600;
}

.contact-card a {
  color: #d4a574;
  text-decoration: none;
  font-weight: 500;
  transition: all 0.3s ease;
}

.contact-card a:hover {
  color: #c89456;
  text-decoration: underline;
}

.contact-form {
  max-width: 600px;
  margin: 3rem auto 0;
  background: white;
  padding: 2rem;
  border-radius: 10px;
  box-shadow: 0 4px 6px rgba(61, 61, 61, 0.08);
  display: flex;
  flex-direction: column;
  gap: 1rem;
  border-top: 3px solid #d4a574;
}

.contact-form input,
.contact-form textarea {
  padding: 12px;
  border: 2px solid #e8dfd2;
  border-radius: 6px;
  font-family: inherit;
  font-size: 14px;
  transition: all 0.3s;
  background-color: #fefaf6;
  color: #3d3d3d;
}

.contact-form input:focus,
.contact-form textarea:focus {
  outline: none;
  border-color: #d4a574;
  background-color: white;
}

.submit-button {
  background: linear-gradient(135deg, #d4a574 0%, #c89456 100%);
  color: white;
  border: none;
  padding: 12px;
  border-radius: 6px;
  font-size: 16px;
  font-weight: 600;
  cursor: pointer;
  transition: all 0.3s ease;
}

.submit-button:hover {
  transform: translateY(-2px);
  box-shadow: 0 4px 12px rgba(212, 165, 116, 0.4);
}

/* ============================================
   FOOTER
   ============================================ */

.footer {
  background: #6b5344;
  color: white;
  padding: 2rem;
  text-align: center;
  border-top: 3px solid #d4a574;
}

.social-links {
  display: flex;
  justify-content: center;
  gap: 2rem;
  margin-bottom: 1.5rem;
}

.social-links a {
  color: #fefaf6;
  font-size: 24px;
  transition: all 0.3s ease;
}

.social-links a:hover {
  color: #d4a574;
  transform: translateY(-3px);
}

/* ============================================
   ANIMATIONS
   ============================================ */

@keyframes fadeIn {
  from {
    opacity: 0;
  }
  to {
    opacity: 1;
  }
}

@keyframes slideInUp {
  from {
    opacity: 0;
    transform: translateY(30px);
  }
  to {
    opacity: 1;
    transform: translateY(0);
  }
}

/* ============================================
   RESPONSIVE DESIGN
   ============================================ */

@media (max-width: 768px) {
  .hero-content h2 {
    font-size: 36px;
  }

  .hero .tagline {
    font-size: 18px;
  }

  .section h3 {
    font-size: 28px;
    margin-bottom: 2rem;
  }

  .nav-links {
    gap: 0.5rem;
    width: 100%;
  }

  .nav-link {
    font-size: 14px;
  }

  .skills-grid {
    grid-template-columns: 1fr;
  }

  .projects-grid {
    grid-template-columns: 1fr;
  }

  .about-stats {
    grid-template-columns: repeat(2, 1fr);
    gap: 1rem;
  }

  .stat-number {
    font-size: 24px;
  }

  .stat-label {
    font-size: 12px;
  }
}

@media (max-width: 480px) {
  .hero {
    padding: 4rem 1rem;
  }

  .hero-content h2 {
    font-size: 24px;
  }

  .hero .tagline {
    font-size: 16px;
  }

  .section {
    padding: 2rem 1rem;
  }

  .nav-content {
    flex-direction: column;
    gap: 0.5rem;
  }

  .nav-links {
    flex-direction: column;
    gap: 0.3rem;
  }

  .contact-grid {
    grid-template-columns: 1fr;
  }

  .about-stats {
    grid-template-columns: repeat(2, 1fr);
  }
}
    </style>
</head>
<body>
    <!-- Navigation -->
    <nav>
        <h1>Daya Yadav</h1>
        <div>
            <a href="#about">About</a>
            <a href="#skills">Skills</a>
            <a href="#projects">Projects</a>
            <a href="#experience">Experience</a>
            <a href="#contact">Contact</a>
        </div>
    </nav>
    
    <!-- Hero Section -->
    <section class="hero">
        <h2>Technical Lead</h2>
        <p>14 Years Building Exceptional Mobile Apps | Android | React Native | Kotlin</p>
        <a href="#contact" class="cta-button">Get In Touch</a>
    </section>
    
    <!-- About Section -->
    <section id="about" class="container" style="padding: 3rem 2rem;">
        <h3 style="margin-bottom: 1rem;">About Me</h3>
        <p>Senior Mobile Developer with 14+ years of native Android development and comprehensive expertise in building robust, high-performance applications. Proficient in Java and Kotlin with deep knowledge of Object-Oriented Programming, MVVM/MVI architecture patterns, and Android best practices. Expert in REST API integration, automated testing (JUnit, Espresso, Robolectric), and secure authentication protocols (OAuth 2.0, OpenID Connect). Strong track record designing scalable, multi-module architectures with Dagger/Hilt dependency injection and implementing security using Android Keystore. Proven ability to collaborate effectively with cross-functional teams throughout requirements, architecture, and development phases. Agile/Scrum certified with experience leading engineering teams and mentoring developers. Familiar with emerging Android SDK components and modern architectural approaches including Jetpack Compose and Kotlin Coroutines..</p>
    </section>
    
    <!-- Skills Section -->
    <section id="skills" class="skills">
        <div class="container">
            <h3>Technical Skills</h3>
            <div class="skill-grid">
                <div class="skill-card">
                    <h4>Android Development</h4>
                    <p>Kotlin, Jetpack Compose, MVVM, Clean Architecture</p>
                </div>
                <div class="skill-card">
                    <h4>Cross-Platform</h4>
                    <p>React Native, Firebase, Performance Optimization</p>
                </div>
                <div class="skill-card">
                    <h4>Architecture</h4>
                    <p>Clean Architecture, MVVM, Design Patterns, Unit Testing</p>
                </div>
                <div class="skill-card">
                    <h4>Testing</h4>
                    <p>Mockito, Unit Testing, Integration Testing</p>
                </div>
                <div class="skill-card">
                    <h4>Agile Methodology</h4>
                    <p>Scrum, Kanban, Team Leadership, Mentoring</p>
                </div>
                <div class="skill-card">
                    <h4>Tools & Platforms</h4>
                    <p>Git, Android Studio, VS Code, CI/CD</p>
                </div>
            </div>
        </div>
    </section>
    
    <!-- Projects Section -->
    <section id="projects" class="projects">
        <div class="container">
            <h3>Featured Projects</h3>
            <div class="project-grid">
                <div class="project-card">
                    <div class="project-image"></div>
                    <div class="project-info">
                        <h4>News and Article Mobile Application</h4>
                        <p>-Architected multi-module application using Clean Architecture, Jetpack Compose, and advanced dependency injection ensuring scalability and maintainability.</p>
                        <p><strong>Tech Stack:</strong> Kotlin, Jetpack Compose, MVVM</p>
                       
                    </div>
                </div>
                <div class="project-card">
                    <div class="project-image"></div>
                    <div class="project-info">
                        <h4>Grameenphone Mobile Application</h4>
                        <p>-Led large-scale architectural migration from legacy Java codebase to Kotlin, resulting in 30% code reduction and 90% decrease in NullPointerExceptions.
-	Replaced asynchronous Java threads with Kotlin Coroutines achieving low-latency real-time operations critical for telecom infrastructure.
-	Developed robust functionality for user recharge management and roaming options in close collaboration with stakeholders.
</p>
                        <p><strong>Tech Stack:</strong> Android,Java,Kotlin, Firebase</p>
                        <a href="#" style="color: #667eea; text-decoration: none;">View Project →</a>
                    </div>
                </div>
            </div>
        </div>
    </section>
    
    <!-- Experience Section -->
    <section id="experience" class="experience">
        <div class="container">
            <h3 style="margin-bottom: 2rem; text-align: center;">Experience</h3>
            <div class="timeline">
                <div class="timeline-item">
                    <h4>Technical Lead</h4>
                    <p>Wipro Technology | Sep 2018 - April 2028</p>
                    <p>-Architected scalable, high-reliability Android applications using Kotlin, Jetpack Compose, and MVVM architecture, consistently achieving 99.9% crash-free rate and maintaining secure authentication with OAuth 2.0 and Android Keystore for sensitive data protection.
-	Implemented comprehensive automated testing framework (JUnit, Espresso, Robolectric, Mockito) reducing production bugs by 30%; ensured robust REST API integration with Retrofit and OkHttp following Android best practices and design patterns.
-	Led and mentored cross-functional team of 10+ engineers; demonstrated excellent communication skills across requirements gathering, architecture design, and code reviews. Implemented Agile/Scrum practices that reduced delivery cycles by 20%.
-	Directed full SDLC for Office Depot e-commerce and Grameenphone telecom platforms; led migration of legacy Java codebases to Kotlin, improving code maintainability through MVVM and Clean Architecture design patterns.
-	Championed adoption of multi-module architecture, Dagger/Hilt dependency injection, and design patterns (MVVM, MVI) to improve code reusability, testability, and performance of mission-critical systems.
-	Optimised application performance through system-level debugging, memory profiling, and replacement of asynchronous Java threads with Kotlin Coroutines for low-latency real-time operations
</p>
                </div>
                <div class="timeline-item">
                    <h4>Technical Analyst</h4>
                    <p>NIIT Technology | December 2015 - September 2018 </p>
                    <p>-Designed and developed mobile applications for Android and iOS platforms focusing on performance optimisation and user experience.
-	Reduced defect rate by 30% through enhanced testing practices and rigorous quality assurance protocols.
-	Managed comprehensive SDLC documentation ensuring project quality, traceability, and timely delivery.
-	Customised applications based on diverse client requirements, improving customer satisfaction and sustaining business relationships.
</p>
                </div>
                <div class="timeline-item">
                    <h4>Associate Consultant</h4>
                    <p>Infogain | February 2015 - December 2015 </p>
                    <p>-Developed Android applications addressing diverse client requirements across multiple domains.
-	Collaborated with cross-functional teams to troubleshoot and resolve application issues in fast-paced environments.
-	Took full ownership of coding, testing, and implementation phases for assigned features and components.
</p>
                </div>
            </div>
        </div>
    </section>
    
    <!-- Contact Section -->
    <section id="contact" style="padding: 3rem 2rem; background: #f4f4f4; text-align: center;">
        <div class="container">
            <h3>Let's Work Together</h3>
            <p style="margin: 1rem 0; font-size: 18px;">I'm always interested in hearing about new projects and opportunities.</p>
            <p style="margin: 2rem 0;">
                <a href="mailto:daya20oct@gmail.com" style="background: #667eea; color: white; padding: 12px 30px; border-radius: 25px; text-decoration: none; display: inline-block; font-weight: bold;">Send Me an Email</a>
            </p>
            <p>
                <a href="https://www.linkedin.com/in/daya-yadav-403a122b">LinkedIn</a> | 
                <a href="https://github.com/DayaYadav/LBG/tree/dev/demo6Feb">GitHub</a> 
            </p>
        </div>
    </section>
    
    <!-- Footer -->
    <footer>
        <p>&copy; 2026 Daya Yadav. All rights reserved.</p>
    </footer>
</body>
</html>
