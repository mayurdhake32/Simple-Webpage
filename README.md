# Simple-Webpage
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Personal Webpage</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        body {
            background: linear-gradient(135deg, #f5f7fa 0%, #c3cfe2 100%);
            color: #333;
            line-height: 1.6;
            padding: 20px;
            min-height: 100vh;
        }
        
        .container {
            max-width: 1000px;
            margin: 40px auto;
            background: white;
            border-radius: 15px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.1);
            overflow: hidden;
        }
        
        header {
            background: linear-gradient(90deg, #4b6cb7 0%, #182848 100%);
            color: white;
            text-align: center;
            padding: 50px 20px;
        }
        
        .profile-container {
            display: flex;
            flex-direction: column;
            align-items: center;
            margin-bottom: 20px;
        }
        
        .profile-img {
            width: 180px;
            height: 180px;
            border-radius: 50%;
            border: 5px solid rgba(255, 255, 255, 0.3);
            object-fit: cover;
            margin-bottom: 20px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.2);
        }
        
        h1 {
            font-size: 2.8rem;
            margin-bottom: 10px;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.3);
        }
        h1:hover {
            color: #13116d;
            transform: translateY(-3px);
            transition: all 0.3s ease;
        }
        .tagline {
            font-size: 1.3rem;
            opacity: 0.9;
            max-width: 600px;
            margin: 0 auto;
        }
        
        .content {
            display: flex;
            padding: 40px;
            gap: 40px;
        }
        
        .main-content {
            flex: 2;
        }
        
        .sidebar {
            flex: 1;
            background: #f8f9fa;
            padding: 25px;
            border-radius: 10px;
            box-shadow: inset 0 0 10px rgba(0, 0, 0, 0.05);
        }
        
        h2 {
            color: #2c3e50;
            margin-bottom: 20px;
            padding-bottom: 10px;
            border-bottom: 2px solid #4b6cb7;
            font-size: 1.8rem;
            font-weight: 600;
        }
        h2:hover {
            color: #13116d;
            transform: translateY(-3px);
            transition: all 0.3s ease;
        }
        
        .bio {
            font-style: "Times New Roman", serif;
            font-size: 1.1rem;
            line-height: 1.8;
            margin-bottom: 25px;
        }
        
        .bio p {
            margin-bottom: 15px;
        }
        
        .skills {
            list-style: none;
            margin-top: 15px;
        }
        
        .skills li {
            background: #4b6cb7;
            color: white;
            display: inline-block;
            padding: 8px 15px;
            border-radius: 20px;
            margin: 0 10px 10px 0;
            font-size: 0.9rem;
        }
        
        .skills li:hover {
            background: #182848;
            transform: translateY(-3px);
            transition: all 0.3s ease;
        }
        .contact-info {
            list-style: none;
        }
        
        .contact-info li {
            padding: 12px 0;
            border-bottom: 1px solid #eee;
            display: flex;
            align-items: center;
        }
        
        .contact-info li:last-child {
            border-bottom: none;
        }
        
        .contact-info i {
            width: 30px;
            color: #4b6cb7;
            font-size: 1.2rem;
        }
        
        .social-links {
            display: flex;
            justify-content: center;
            gap: 20px;
            margin-top: 30px;
        }
        
        .social-links a {
            display: flex;
            align-items: center;
            justify-content: center;
            width: 50px;
            height: 50px;
            border-radius: 50%;
            background: #4b6cb7;
            color: white;
            font-size: 1.5rem;
            transition: all 0.3s ease;
            text-decoration: none;
        }
        
        .social-links a:hover {
            background: #182848;
            transform: translateY(-5px);
        }
        
        footer {
            text-align: center;
            padding: 20px;
            background: #2c3e50;
            color: white;
            font-size: 0.9rem;
        }
        
        @media (max-width: 768px) {
            .content {
                flex-direction: column;
                padding: 25px;
            }
            
            header {
                padding: 30px 20px;
            }
            
            h1 {
                font-size: 2.2rem;
            }
            
            .profile-img {
                width: 150px;
                height: 150px;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <div class="profile-container">
                <img src="04af279a-0d9b-4e4e-acc8-fafbddacafa8.png" alt="Profile Photo" class="profile-img">
                <h1>Mayur Dhake</h1>
                <p class="tagline">Web Developer </p>
            </div>
        </header>
        
        <div class="content">
            <div class="main-content">
                <h2>About Me</h2>
                <div class="bio">
                    <p>Hello! I'm a passionate third-year Computer Engineering student with a strong interest in web development and backend technologies. I thrive on transforming complex problems into elegant solutions through code.</p>
                    
                    <p>My journey in technology began with a fascination for how things work, which led me to pursue computer engineering. Along the way, I discovered my passion for building web applications that combine functionality with great user experiences.</p>
                    
                    <p>I'm currently expanding my expertise in both frontend (HTML, CSS, JavaScript) and backend technologies. I enjoy the challenge of creating responsive, efficient, and accessible web applications that solve real-world problems.</p>
                </div>
                
                <h2>Skills & Expertise</h2>
                <ul class="skills">
                    <li>HTML5 & CSS3</li>
                    <li>JavaScript</li>
                    <!-- <li>React.js</li> -->
                    <li>Responsive Design</li>
                    <li>UI/UX Design</li>
                    <!-- <li>Node.js</li> -->
                    <li>Git & GitHub</li>
                    <li>Web Accessibility</li>
                </ul>
            </div>
            
            <div class="sidebar">
                <h2>Contact Information</h2>
                <ul class="contact-info">
                    <li>
                        <i class="fas fa-envelope"></i>
                        <span><mayur class="dhake">mayur.dhake</mayur>@example.com</span>
                    </li>
                    <li>
                        <i class="fas fa-phone"></i>
                        <span>9763190952</span>
                    </li>
                    <li>
                        <i class="fas fa-map-marker-alt"></i>
                        <span>Pune, India</span>
                    </li>
                    <li>
                        <i class="fas fa-globe"></i>
                        <span>www.mayurdhake.com</span>
                    </li>
                </ul>
                
                <div class="social-links">
                    <a href="https://www.linkedin.com/in/mayurdhake" target="_blank" rel="noopener noreferrer" title="LinkedIn"><i class="fab fa-linkedin-in"></i></a>
                    <a href="https://github.com/mayurdhake" target="_blank" rel="noopener noreferrer" title="GitHub"><i class="fab fa-github"></i></a>
                    <a href="https://twitter.com/mayurdhake" target="_blank" rel="noopener noreferrer" title="Twitter"><i class="fab fa-twitter"></i></a>
                    <a href="https://instagram.com/mayurdhake" target="_blank" rel="noopener noreferrer" title="Instagram"><i class="fab fa-instagram"></i></a>
                </div>
            </div>
        </div>
        
        <footer>
            <p>&copy; 2025 Mayur Dhake. All rights reserved.</p>
        </footer>
    </div>
</body>
</html>
