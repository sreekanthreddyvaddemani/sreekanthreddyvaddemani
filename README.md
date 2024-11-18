<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sreekanth Reddy Vaddemani - Portfolio</title>
    <link rel="stylesheet" href="styles.css">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.2/css/all.min.css">
    <style>
        * {
            padding: 0;
            margin: 0;
            box-sizing: border-box;
        }
        .portfolio {
            height: 100%;
            width: 100%;
        }

        /* Navbar Section */
        #nav {
            position: fixed;
            top: 0;
            left: 0;
            height: 80px;
            width: 100%;
            background-color: rgb(4, 2, 28);
            display: flex;
            align-items: center;
            justify-content: space-evenly;
            z-index: 1000;
        }

        #logo {
            height: 80px;
            width: 230px;
            display: flex;
            align-items: center;
            justify-content: space-between;
            position: relative;
            margin-left: 50px;
            

        }

        #logo h1 {
            color: white;
            font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
            font-size: 40px;
        }

        #circle {
    font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
    font-size: 30px;
    font-weight: bolder;
    color: #d900b3;
    margin-right: 35px;
    display: inline-block; 
    animation: bounce 1s ease-in-out infinite;
}

/* Bounce Animation for the Circle */
@keyframes bounce {
    0% {
        transform: translateY(5px) scale(1);
    }
    50% {
        transform: translateY(-30px) scale(1.2);
    }
    100% {
        transform: translateY(5px) scale(1);
    }
}

        /* Menu Section */
        #menulist {
            height: 80px;
            width: 800px;
            display: flex;
            align-items: center;
            justify-content: space-evenly;

        }

        .menu-container {
            display: flex;
            justify-content: space-evenly;
            width: 100%;
        }

        .menu {
            height: 40px;
            width: 100px;
            font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
            font-weight: 900;
            list-style-type: none;
            color: white;
            display: flex;
            align-items: center;
            justify-content: center;
            cursor: pointer;
            position: relative;
        }

        /* Highlight active menu item */
        .menu.active {
            color: #ff00cc;
            background-color:white;
            border-radius: 10px;
        }

        .menu:hover {
            border-bottom: 2px solid white;
        }

        .section {
            height: 100vh;
            padding-top: 100px;
           
        }

       

        
 .home-section {
            background-color: rgb(4, 2, 28);
            color: white;
        }


        .profile {
            height: 86vh;
            width: 100%;
            background-color: rgb(4, 2, 28);
            display: flex;
            align-items: center;
            justify-content: space-evenly;
        }

        .info {
            height: 74vh;
            width: 50%;
        }

        .info h1 {
            color: white;
            font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
        }

        .photo {
            height: 70vh;
            width: 70vh;
           
            display: flex;
            align-items: center;
            justify-content: space-evenly;
        }


        .photo .img {
            height: 100%;
            width: 80%;
            border-radius: 100%;
            display: flex;
            align-items: center;
            justify-content: space-evenly;
            border-bottom-left-radius: 60%;
            border-bottom-right-radius: 60%;

        }

        .photo .img img {
            height: 90%;
            width: 90%;
            border-radius: 30px;
            box-shadow: 0px 1px 30px rgba(142, 134, 134, 0.3);
            
        }
  
/* Section container */
.about-section {
    padding: 50px 20px;
    background-color: rgb(4, 2, 28);
}

/* About Container */
.about-container {
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    align-items: center;
    max-width: 1200px;
    margin: 0 auto;
}

/* About Image Section */
.about-image {
    flex: 1;
    padding: 20px;
    text-align: center;
}

.about-image img {
    width: 80%;
    max-width: 300px;
    border-radius: 10px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);

}

/* About Content Section */
.about-content {
    flex: 3;
    padding: 20px;
    line-height: 1.6;
    font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
}

.about-content h2 {
    margin-top: 35px;
    font-size: 2rem;
    color: #d900b3;
    margin-bottom: 5px;
}

.about-content p {
    font-size: 1.1rem;
    color: #ffffff;
    margin-bottom: 15px;
}

.about-content strong {
    font-weight: bold;
}





/* Services Section */
.services-section {
    padding: 50px 20px;
    background-color: rgb(4, 2, 28);

}

.services-container {
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    align-items: center;
    max-width: 1200px;
    margin: 0 auto;
}

/* Experience Section */
.experience-container {
    flex: 1;
    padding: 20px;
    margin-top: 70px;
    font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
}

.experience-container h2 {
    font-size: 2rem;
    color: #d900b3;
    margin-bottom: 20px;
    
}

.experience {
    margin-bottom: 20px;
    padding: 15px;
    border-left: 5px solid #ff00cc;
    background-color: #f4f4f4;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}

.experience h4 {
    color: #444;
    margin-bottom: 10px;
}

.experience p {
    color: #666;
    line-height: 1.5;
}

/* Services Image */
.services-image {
    flex: 1;
    padding: 20px;
    text-align: center;
}

.services-image img {
    width: 80%;
    max-width: 400px;
    border-radius: 10px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
    margin-top: 100px;
}







.skills-section {
    width: 100%;
    height: 100vh;
    display: flex;
    align-items: center;
    justify-content: center;
    background-color: rgb(4, 2, 28);
    overflow-y: auto;
    font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;

}

.skills-container {
    width: 100%;
    color: #333;
    padding: 20px;
    overflow: auto;
}

.skills-container h2 {
    text-align: center;
    margin-bottom: 10px;
    margin-top: -27px;
    color: #d900b3;
}



.skills-category h3 {
    margin-top: 6px;
    margin-bottom: 5px;
    color: #6a11cb;
    
}

.skills-items {
    display: flex;
    gap: 25px;
}

.skill-item {
    display: flex;
    flex-direction: column;
    align-items: center;
    width: 140px;
    height: 75px;
    text-align: center;
    background: #f9f9f9;
    border-radius: 10px;
    padding: 10px;
    transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.skill-item:hover {
    transform: translateY(-5px);
    box-shadow: 0 6px 12px rgba(0, 0, 0, 0.2);
}

.skill-item img {
    margin-bottom: 5px;
    background: #f0f0f0;
    border-radius: 5px;
}

.skill-item span {
    font-size: 1rem;
    font-weight: 600;
    color: #333;
}    






.projects-section {
    background: rgb(4, 2, 28);
    color: #333;
    font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
    margin-top: -10px;
}

.projects-section h2 {
    text-align: center;
    margin-bottom: 20px;
    color: #2c3e50;
    color: #d900b3;
    
}

.projects-container {
    display: flex;
    flex-direction: row;
    gap: 20px;
    justify-content: center;
    align-items: flex-start;
    flex-wrap: wrap;
}

.project {
    display: flex;
    flex-direction: column;
    width: 30%;
    min-width: 250px;
    background: #fff;
    padding: 15px;
    border-radius: 8px;
    box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
    transition: transform 0.3s ease, box-shadow 0.3s ease;
    overflow: hidden;
    text-align: center;
}

.project:hover {
    transform: translateY(-5px);
    box-shadow: 0 6px 15px rgba(0, 0, 0, 0.2);
}

.project-image img {
    width: 100%;
    height: auto;
    border-radius: 5px;
    transition: transform 0.5s ease, filter 0.5s ease;
}

.project:hover .project-image img {
    transform: scale(1.1);
    filter: brightness(0.9);
}

.project-details {
    margin-top: 15px;
}

.project h3 {
    font-size: 1.8rem;
    margin-bottom: 10px;
    color: #3498db;
}

.project p {
    font-size: 1rem;
    margin-bottom: 15px;
    color: #555;
}

.project ul {
    list-style-type: disc;
    margin-left: 15px;
    font-size: 0.9rem;
    color: #666;
    text-align: left;
}

.project ul li {
    margin-bottom: 5px;
}

/* Responsive Design */
@media (max-width: 768px) {
    .projects-container {
        flex-direction: column;
        align-items: center;
    }

    .project {
        width: 90%;
    }
}
       /* General Section Styling */
.contact-section {
    color: #7e1d1d;
    padding: 50px 20px;
    text-align: center;
    height: 79vh;
    box-shadow: 0 4px 15px rgba(0, 0, 0, 0.2);
    background: rgb(4, 2, 28);
font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
}

/* Heading Styling */
.contact-heading {
    font-size: 2.5rem;
    font-weight: bold;
    margin-top: 60px;
    text-transform: uppercase;
    animation: fadeIn 2s ease-in-out;
    color: #d900b3;
}

.contact-info {
    font-size: 1.2rem;
    animation: slideUp 1.5s ease-in-out;
    color: #d900b3;
}

.contact-item {
    margin: 10px 0;
    font-weight: 500;
}

.contact-item a {
    color: #fff;
    text-decoration: none;
    font-weight: bold;
    transition: color 0.3s ease-in-out;
}

.contact-item a:hover {
    color: #ffcc00;
}

/* Icon Styling */
.contact-item i {
    margin-right: 10px;
    font-size: 1.5rem;
    vertical-align: middle;
}

/* Animations */
@keyframes fadeIn {
    from {
        opacity: 0;
        transform: translateY(-20px);
    }
    to {
        opacity: 1;
        transform: translateY(0);
    }
}

@keyframes slideUp {
    from {
        opacity: 0;
        transform: translateY(50px);
    }
    to {
        opacity: 1;
        transform: translateY(0);
    }
}






/* Style for contact buttons */
.contact-buttons {
    margin-top: 20px;
    display: flex;
    justify-content: center;
}

.contact-buttons .btn {
    margin: 0 10px;
    padding: 10px 20px;
    background-color: #ff00cc;
    color: white;
    border: none;
    border-radius: 5px;
    font-size: 1rem;
    cursor: pointer;
    transition: background-color 0.3s ease;
}

.contact-buttons .btn:hover {
    background-color: #d900b3; /* Darken button on hover */
}


/* Social Media Icon Container */
.my-12 {
  display: flex;
  justify-content: center;
  gap: 1rem;
}

/* Icon Link */
.icon-link {
  display: inline-block;
  transition: transform 0.3s ease, color 0.3s ease;
}

/* Icon Styling */
.social-icon {
  fill: #d900b3;
  transition: transform 0.3s ease, fill 0.3s ease;
}

/* Hover Effects */
.icon-link:hover {
  transform: scale(1.2);
}

.icon-link:hover .social-icon {
  transform: rotate(15deg) scale(1.15);
  fill: #ffffff;  /* Change color on hover */
}

/* Apply Bounce In Effect on Load */
.icon-link {
  animation: bounceIn 1s ease-out;
}

@keyframes bounceIn {
  0% {
    transform: scale(0);
  }
  50% {
    transform: scale(1.2);
  }
  100% {
    transform: scale(1);
  }
}

/* Responsive Design */
@media (max-width: 768px) {
  .my-12 {
    gap: 1rem;
  }

  .social-icon {
    height: 25px;
    width: 25px;
  }
}


.container1 {
    padding: 20px;
    font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;

}

.greeting1 {
    font-size: 36px;
    margin-bottom: 10px;
    font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
}

.name1 {
    font-size: 48px;
    font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
    font-weight: bold;
    margin-bottom: 10px;
    color: #d900b3;

}

.profession1 {
    font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;

    font-size: 36px;
    margin-bottom: 20px;

}

.social-icons1 {
    margin-bottom: 20px;
    margin-top: 40px;
}

.social-icons1 a {
    color: #d900b3;
    margin-right: 40px;
    font-size: 40px;
    text-decoration: none;
}
.social-icons1 a:hover {
    color: white;
  
}

.buttons1 {
    display: flex;

}

.contact-button1, .resume-button1 {
    padding: 13px 40px;
    border-radius: 25px;
    cursor: pointer;
    margin-right:40px ;
    border: 2px solid #d900b3;
font-size: 20px;
font-weight: bolder;
text-decoration: none;

}

.contact-button1{
    background-color: rgb(4, 2, 28);
    color: #fff;
    font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
}

.resume-button1 {
    background-color: rgb(4, 2, 28);
    color: #fff;
    font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
}

.contact-button1:hover, .resume-button1:hover {
    background-color: #d900b3;
}


.footer {
    width: 100%;
    height: 21vh;
    background-color: rgb(4, 2, 28);
    color: #fff;
    text-align: center;
    font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
}

.social-icons {
    height: 8vh;
    width: 100%;
    display: flex;
    align-items: center;
    justify-content: center;
    border-top: 1px solid #d900b3;
}

.social-icons a {
    color: #fff;
    margin: 0 25px;
    font-size: 24px;
}

.social-icons a:hover,.footer-links a:hover{
   color:  #d900b3;

}

.footer-links{
height: 5vh;
    display: flex;
    align-items: center;
    justify-content: space-evenly;
    width: 100%;
}


.footer-links a {
    color: #fff;
    margin: 0 10px;
    text-decoration: none;
    font-weight: bolder;
}

.footer-links a:hover {
   border: none;
}

.copyright {
    font-size: 17px;
    height: 8vh;
    width: 100%;
    display:flex;
    align-items: center;
    justify-content: center;
    background-color: #d900b3;
    font-weight: bold;

}


/* Responsive Navbar */
@media (max-width: 480px) {
    #nav {
        flex-direction: column;
        height: auto;
        padding: 10px 0;
    }

    #logo {
        margin: 0 auto;
    }

    #menulist {
        flex-direction: column;
        gap: 10px;
        width: 100%;
    }

    .menu {
        width: 100%;
        text-align: center;
    }
}

/* Profile Section */
@media (max-width: 480px) {
    .profile {
        flex-direction: column;
        padding: 20px;
        margin-top: 100px;
    }

    .info, .photo {
        width: 100%;
        text-align: center;
    }

    .photo .img img {
        width: 100%;
        height: auto;
        border-radius: 50%;
    }
}

/* About Section */
@media (max-width: 480px) {
    .about-container {
        flex-direction: column;
        text-align: center;
    }

    .about-image img {
        width: 100%;
        max-width: 200px;
    }

    .about-content {
        padding: 10px;
    }
}

/* Projects Section */
@media (max-width: 480px) {
    .projects-container {
        flex-direction: column;
        align-items: center;
    }

    .project {
        width: 90%;
    }
}

/* Contact Section */
@media (max-width: 480px) {
    .contact-section {
        padding: 20px;
    }

    .contact-heading {
        font-size: 1.8rem;
    }

    .contact-info {
        font-size: 1rem;
    }
}
    </style>
</head>
<body>
    <div class="portfolio">
        <!-- Navbar -->
        <div id="nav">
            <div id="logo">
                <h1>Portfoli </h1>
                <span id="circle">O</span>
            </div>            
            <div class="menu-container">
                <ul id="menulist">
                    <li class="menu active" data-section="home">Home</li>
                    <li class="menu" data-section="about">About</li>
                    <li class="menu" data-section="services">Experience</li>
                    <li class="menu" data-section="skills">Skills</li>
                    <li class="menu" data-section="projects">Projects</li>
                    <li class="menu" data-section="contact">Contact</li>
                </ul>
            </div>
        </div>

        <!-- Section for Home -->
<div class="section home-section" id="home">
    <div class="profile">
        <div class="info">
            
    <div class="container1">
        <h1 class="greeting1">Hello, This is</h1>
        <h2 class="name1">SREEKANTH REDDY V</h2>
        <h2 class="profession1">I'm a Professional</h2>
        <h2 class="profession1">Java Full Stack Developer</h2>

        <div class="social-icons1">
            <a href="https://github.com/sreekanthreddyvaddemani" target="_blank" ><i class="fab fa-github"></i></a>
            <a href="https://www.linkedin.com/in/sreekanth-reddy-vaddemani-2664a6225/" target="_blank"><i class="fab fa-linkedin"></i></a>
            <a href="#" target="_blank"><i class="fab fa-facebook"></i></a>
            <a href="#" target="_blank"><i class="fab fa-dribbble"></i></a>
            <a href="#" target="_blank"><i class="fab fa-twitter"></i></a>
        </div>
        <div class="buttons1">
            <a href="tel:+91 9390070375" class="contact-button1">CONTACT ME <i class="fas fa-phone"></i></a>
            <a href="https://drive.google.com/file/d/1F6tg5Uk3TZvcG5QKu1w8FZ3icitPF2Bf/view?usp=sharing" class="resume-button1">GET RESUME <i class="fas fa-download"></i></a>
        </div>
    </div>
            </div>
        <div class="photo">
            <div class="img">
                <img src="C:\Users\vvenk\Downloads\Sreekanth_reddy_HD-removebg-preview.png" alt="Profile Picture">
            </div>
        </div>
    </div>
</div>


        <!-- Section for About -->
<div class="section about-section" id="about">
    <div class="about-container">
        <div class="about-image">
            <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQL87iYwIQjwtYiYX4FDJ0A7wZgdkOu4ErPGg&s" alt="Sreekanth Reddy Vaddemani">
        </div>
        <div class="about-content">
            <h2>About Me</h2>
            <p>
                Hello! I'm <strong>Sreekanth Reddy Vaddemani</strong>, a passionate and dedicated Full Stack Developer with expertise in Java, Spring Boot, Angular, React, and cloud technologies. I hold a Bachelor's degree in Electrical and Electronics Engineering from Annamacharya Institute Of Technology & Sciences, Kadapa, and I have certification as a Java Full Stack Developer from JSpiders-BTM, Bengaluru.
            </p>
            <p>
                I have experience working on various projects, including building web applications, developing microservices using Spring Boot, and designing scalable solutions. My skills encompass a wide range of technologies such as Hibernate, SQL, AWS, and more. I am always eager to learn new technologies and improve my skills to stay ahead in this ever-evolving field of software development.
            </p>
            <p>
                I have had the opportunity to work with diverse teams and contribute to projects in different domains, such as insurance services, ticket reservation systems, and e-commerce platforms. I'm passionate about solving complex problems, optimizing code, and delivering efficient and high-quality software solutions.
            </p>
            <p>
                I'm always open to new opportunities that challenge my skills and provide a platform to grow as a developer. Let's connect and create something amazing together!
            </p>
        </div>
    </div>
</div>

            
       

       <!-- Services Section -->
<div class="section services-section" id="services">
    <div class="services-container">
        <!-- Experience Divs -->
        <div class="experience-container">
            <h2>Experience</h2>
            <div class="experience">
                <h4>Associate Software Engineer at Mphasis</h4>
                <h4>07-2024 To 10-2024</h4>
                <p>Worked on developing and maintaining scalable web applications using Java, Spring Boot, Angular, and AWS. Contributed to projects like Insurance Policy Management and Ticket Reservation API.</p>
                
            </div>
            <div class="experience">
                <h4>Java Full Stack Developer (JSpiders-BTM Certified)</h4>
                <h4>12-2022 To 12-2023</h4>
                <p>Gained hands-on experience in building enterprise-grade applications, focusing on microservices architecture, cloud integration, and responsive UI design using modern frameworks.</p>
            </div>
        </div>

        <!-- Picture -->
        <div class="services-image">
            <img src="https://st3.depositphotos.com/3126965/17336/v/600/depositphotos_173365774-stock-illustration-young-programmer-coding-a-new.jpg" alt="Services Image">
        </div>
    </div>
</div>




<div class="section skills-section" id="skills">
    <div class="skills-container">
        <h2>Things I Code With</h2>

        <div class="skills-category">
            <h3>Programming Languages</h3>
            <div class="skills-items">
                <div class="skill-item">
                    <img src="https://skillicons.dev/icons?i=java" height="40" alt="Java logo" />
                    <span>Java</span>
                </div>
                <div class="skill-item">
                    <img src="https://skillicons.dev/icons?i=js" height="40" alt="JavaScript logo" />
                    <span>JavaScript</span>
                </div>
                <div class="skill-item">
                    <img src="https://skillicons.dev/icons?i=html" height="40" alt="HTML logo" />
                    <span>HTML</span>
                </div>
                <div class="skill-item">
                    <img src="https://skillicons.dev/icons?i=css" height="40" alt="CSS logo" />
                    <span>CSS</span>
                </div>
                <div class="skill-item">
                    <img src="https://skillicons.dev/icons?i=ts" height="40" alt="TypeScript logo" />
                    <span>TypeScript</span>
                </div>
            </div>
        </div>

        <div class="skills-category">
            <h3>Frameworks and Libraries</h3>
            <div class="skills-items">
                <div class="skill-item">
                    <img src="https://skillicons.dev/icons?i=spring" height="40" alt="Spring Boot logo" />
                    <span>Spring Boot</span>
                </div>
                <div class="skill-item">
                    <img src="https://skillicons.dev/icons?i=react" height="40" alt="React logo" />
                    <span>React</span>
                </div>
                <div class="skill-item">
                    <img src="https://skillicons.dev/icons?i=angular" height="40" alt="Angular logo" />
                    <span>Angular</span>
                </div>
                <div class="skill-item">
                    <img src="https://skillicons.dev/icons?i=hibernate" height="40" alt="Hibernate logo" />
                    <span>Hibernate</span>
                </div>
                <div class="skill-item">
                    <img src="https://skillicons.dev/icons?i=nodejs" height="40" alt="Node.js logo" />
                    <span>Node.js</span>
                </div>
                <div class="skill-item">
                    <img src="https://skillicons.dev/icons?i=bootstrap" height="40" alt="Bootstrap logo" />
                    <span>Bootstrap</span>
                </div>
            </div>
        </div>

        <div class="skills-category">
            <h3>Database & Cloud Platforms</h3>
            <div class="skills-items">
                <div class="skill-item">
                    <img src="https://skillicons.dev/icons?i=mysql" height="40" alt="MySQL logo" />
                    <span>MySQL</span>
                </div>
                <div class="skill-item">
                    <img src="https://skillicons.dev/icons?i=aws" height="40" alt="AWS logo" />
                    <span>AWS</span>
                </div>
                <div class="skill-item">
                    <img src="https://skillicons.dev/icons?i=googlecloud" height="40" alt="Google Cloud logo" />
                    <span>Google Cloud</span>
                </div>
            </div>
        </div>

        <div class="skills-category">
            <h3>Tools and IDEs</h3>
            <div class="skills-items">
                <div class="skill-item">
                    <img src="https://skillicons.dev/icons?i=vscode" height="40" alt="VSCode logo" />
                    <span>VSCode</span>
                </div>
                <div class="skill-item">
                    <img src="https://skillicons.dev/icons?i=eclipse" height="40" alt="Eclipse logo" />
                    <span>Eclipse</span>
                </div>
                <div class="skill-item">
                    <img src="https://skillicons.dev/icons?i=git" height="40" alt="Git logo" />
                    <span>Git</span>
                </div>
                <div class="skill-item">
                    <img src="https://skillicons.dev/icons?i=github" height="40" alt="GitHub logo" />
                    <span>GitHub</span>
                </div>
                <div class="skill-item">
                    <img src="https://skillicons.dev/icons?i=docker" height="40" alt="Docker logo" />
                    <span>Docker</span>
                </div>
                <div class="skill-item">
                    <img src="https://skillicons.dev/icons?i=postman" height="40" alt="Postman logo" />
                    <span>Postman</span>
                </div>
            </div>
        </div>
    </div>
</div>







<div class="section projects-section" id="projects">
    <h2>Projects</h2>
    <div class="projects-container">
        <!-- Project 1 -->
        <div class="project">
            <div class="project-image">
                <img src="https://user-images.githubusercontent.com/102630199/226198462-88bddc4e-aff8-4b01-a72a-7977a0d19575.jpg" alt="Insurance Policy Management">
            </div>
            <div class="project-details">
                <h3>Insurance Policy Management</h3>
                <p>A web application to manage health insurance policies, allowing users to select plans, calculate premiums, and manage payments seamlessly.</p>
                
            </div>
        </div>

        <!-- Project 2 -->
        <div class="project">
            <div class="project-image">
                <img src="https://media.licdn.com/dms/image/v2/D5612AQHtGJm6WsBvrA/article-cover_image-shrink_600_2000/article-cover_image-shrink_600_2000/0/1711610742581?e=2147483647&v=beta&t=Nr9HVQj-sEAI6NpnmiUXN2rbJw-HHFIcFKSlVyVs4ik" alt="Ticket Reservation API">
            </div>
            <div class="project-details">
                <h3>Ticket Reservation Application</h3>
<p>The Ticket Reservation Application enables users to effortlessly book tickets for travel or events, featuring quick searches, flexible options.</p>            </div>
        </div>

        <!-- Project 3 -->
        <div class="project">
            <div class="project-image">
                <img src="https://www.webplanex.com/wp-content/uploads/2022/02/hotel-booking-app.jpg" alt="E-commerce Website">
            </div>
            <div class="project-details">
                <h3>Hotel Booking Application</h3>
                <p>The Hotel Booking Application simplifies travel planning with a user-friendly interface for browsing, booking, and managing accommodations, offering secure payment options for a seamless experience.</p>                
            </div>
        </div>
    </div>
</div>








        <div class="section contact-section" id="contact">
            <h2 class="contact-heading">Contact</h2>
            <div class="contact-info">
                <p class="contact-item">
                    <i class="fas fa-envelope"></i> Email: <a href="vsreekanthreddy16213@gmail.com">vsreekanthreddy16213@gmail.com</a>
                </p>
                <p class="contact-item">
                    <i class="fas fa-phone-alt"></i> Phone: <a href="tel:+91 9390070375">+91 9390070375</a>
                </p>
            </div>
            


        </div>





        <footer class="footer">
            <div class="social-icons">
                <a href="#"><i class="fab fa-facebook-f"></i></a>
                <a href="#"><i class="fab fa-instagram"></i></a>
                <a href="#"><i class="fab fa-twitter"></i></a>
                <a href="#"><i class="fab fa-google-plus-g"></i></a>
                <a href="#"><i class="fab fa-youtube"></i></a>
            </div>
            <div class="footer-links">
                    <a href="#" class="menu active" data-section="home">Home</a>
                    <a href="#" class="menu" data-section="skills">Skills</a>
                    <a href="#" class="menu" data-section="about">About</a>
                    <a href="#" class="menu" data-section="our-team">Our Team</a>                
            </div>
            <div class="copyright">
                Copyright ©2024. Designed by Sreekanth Reddy Vaddemani
            </div>
        </footer>




       
        




        
    </div>

    <script>
        // Smooth scrolling and active menu highlight
        const menuItems = document.querySelectorAll('.menu');
        const sections = document.querySelectorAll('.section');

        // Smooth Scroll to Section
        menuItems.forEach(menuItem => {
            menuItem.addEventListener('click', (e) => {
                e.preventDefault();
                const sectionId = menuItem.getAttribute('data-section');
                const section = document.getElementById(sectionId);

                // Scroll to section smoothly
                section.scrollIntoView({ behavior: 'smooth' });

                // Remove active class from all menu items
                menuItems.forEach(item => item.classList.remove('active'));

                // Add active class to clicked menu item
                menuItem.classList.add('active');
            });
        });

        // Highlight the current section in the navbar as you scroll
        window.addEventListener('scroll', () => {
            sections.forEach(section => {
                const rect = section.getBoundingClientRect();
                const menuItem = document.querySelector(`[data-section="${section.id}"]`);

                if (rect.top <= 0 && rect.bottom > 0) {
                    menuItems.forEach(item => item.classList.remove('active'));
                    menuItem.classList.add('active');
                }
            });
        });
    </script>
</body>
</html>



