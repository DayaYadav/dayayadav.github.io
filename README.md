<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Daya Yadav- Technical Lead</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            color: #333;
        }
        
        /* Navigation */
        nav {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            padding: 1rem 2rem;
            position: sticky;
            top: 0;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        
        nav h1 {
            color: white;
            font-size: 24px;
        }
        
        nav a {
            color: white;
            text-decoration: none;
            margin: 0 1rem;
            transition: opacity 0.3s;
        }
        
        nav a:hover {
            opacity: 0.7;
        }
        
        /* Hero Section */
        .hero {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            padding: 4rem 2rem;
            text-align: center;
        }
        
        .hero h2 {
            font-size: 48px;
            margin-bottom: 1rem;
        }
        
        .hero p {
            font-size: 20px;
            margin-bottom: 2rem;
            opacity: 0.9;
        }
        
        .cta-button {
            background: white;
            color: #667eea;
            padding: 12px 30px;
            border-radius: 25px;
            text-decoration: none;
            font-weight: bold;
            display: inline-block;
            transition: transform 0.3s;
        }
        
        .cta-button:hover {
            transform: translateY(-3px);
        }
        
        /* Skills Section */
        .skills {
            padding: 3rem 2rem;
            background: #f4f4f4;
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
        }
        
        .skills h3 {
            font-size: 32px;
            margin-bottom: 2rem;
            text-align: center;
        }
        
        .skill-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 20px;
        }
        
        .skill-card {
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 4px 6px rgba(0,0,0,0.1);
            text-align: center;
        }
        
        .skill-card h4 {
            color: #667eea;
            margin-bottom: 10px;
        }
        
        /* Projects Section */
        .projects {
            padding: 3rem 2rem;
        }
        
        .project-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 30px;
            margin-top: 2rem;
        }
        
        .project-card {
            border: 1px solid #ddd;
            border-radius: 10px;
            overflow: hidden;
            transition: transform 0.3s;
        }
        
        .project-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 20px rgba(0,0,0,0.15);
        }
        
        .project-image {
            width: 100%;
            height: 200px;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
        }
        
        .project-info {
            padding: 20px;
        }
        
        .project-info h4 {
            color: #667eea;
            margin-bottom: 10px;
        }
        
        /* Experience Section */
        .experience {
            padding: 3rem 2rem;
            background: #f4f4f4;
        }
        
        .timeline {
            position: relative;
            max-width: 900px;
            margin: 0 auto;
        }
        
        .timeline-item {
            margin-bottom: 50px;
            padding: 20px;
            background: white;
            border-radius: 10px;
            border-left: 4px solid #667eea;
        }
        
        .timeline-item h4 {
            color: #667eea;
            margin-bottom: 5px;
        }
        
        .timeline-item p {
            color: #666;
            font-size: 14px;
        }
        
        /* Footer */
        footer {
            background: #333;
            color: white;
            text-align: center;
            padding: 2rem;
        }
        
        footer a {
            color: #667eea;
            text-decoration: none;
            margin: 0 1rem;
        }
        
        /* Responsive */
        @media (max-width: 768px) {
            .hero h2 {
                font-size: 32px;
            }
            
            nav {
                flex-direction: column;
            }
            
            nav a {
                display: block;
                margin: 0.5rem 0;
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
        <h2>Senior Mobile Developer</h2>
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
                <a href="www.linkedin.com/in/daya-yadav-403a122b">LinkedIn</a> | 
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
