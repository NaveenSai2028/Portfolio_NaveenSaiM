<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title> M Naveen Sai — AI&DS Portfolio</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css"/>
  <style>
    *{
             
        margin:0;
        padding:0;
        box-sizing:border-box;
        font-family:'Inter',sans-serif;
    }
    body { 
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; 
            background-color: rgb(148, 213, 246); 
            color: #333; 
            
            
              justify-content: center; 
            }
    header{
        background:#0e587e;
        color:white;
        text-align:center;
        padding:50px 20px;
        position:relative;
    }
    header img.profile{
      width:140px;
      height:140px;
      border-radius:50%;
      border:4px solid #fff;
      object-fit:cover;
      margin-bottom:15px;
    }
    header h1
    {font-size:48px;
        margin-bottom:5px;
        text-align:left;
         color:#85bee1;
         
    }
    header p
    {font-size:20px;
       text-align:right;
         color:#85bee1;
    }`
    .resume-btn{
      display:inline-block;
      margin-top:15px;
      padding:10px 20px;
      background:#2a84dd;
      color:#03045e;
      border-radius:8px;
      font-weight:600;t
      ext-decoration:none;
      transition:0.3s;
    }
    .resume-btn:hover{
        background:#074667;
        color:white;
    }

 nav{
        background:#bbbbc0;
        padding:12px;
        text-align:right;
        position:sticky;
        top:0;
        z-index:100;
    }

    nav a{
        color:rgb(7, 7, 7);
        text-decoration:none;
        margin:0 15px;
        font-weight:600;
        transition:0.3s;
    }
    nav a:hover{
        color:#e60e0e;
    }
    section{
        max-width:900px;
        margin:50px 
        auto;padding:20px;
    }

    h2{
        color:#180bd4;
        margin-bottom:15px;
        border-bottom:2px solid #041daa;p
        adding-bottom:5px;
    }
       h3{
        color:#051f6d;
        text-align:left;
        padding:5px;
    }
        ul{
        list-style:disc;
        margin-left:20px;
        margin-top:10px;
        flex-direction:column;
        align-items:flex-start;
  
    }

    .skills span{
      display:inline-block;
      background:#54b4c5;
      color:#03045e;
      padding:5px 12px;
      margin:5px;
      border-radius:12px;
      font-weight:600;
      transition:0.3s;
    }
    .skills span:hover{
        background:#0077b6;
        color:white;
    }
    .project-card{
      background:white;
      padding:15px;
      margin:20px 0;
      border-radius:12px;
      box-shadow:0 6px 15px rgba(0,0,0,0.1);
      transition:transform 0.3s;
      display:flex;gap:15px;align-items:center;
    }
    .project-card span{
        width:120px;
        height:80px;
        border-radius:8px;
        object-fit:cover;
    }
    .project-card:hover{
        transform:translateY(-5px);

    }
     .proj span{
      display:inline-block;
      background:#90e0ef;
      color:#03045e;
      padding:50px 12px;
      margin:5px;
      border-radius:12px;
      font-weight:600;
      transition:0.3s;
    }
    .proj span:hover{
        background:#d6143e;
        color:white;
    }
    .certi{
      background:rgb(184, 219, 251);
      padding:15px;
      margin:20px 0;
      border-radius:12px;
      box-shadow:0 6px 15px rgba(0,0,0,0.1);
      transition:transform 0.3s;
      display:flex;gap:15px;align-items:center;
    }
    .contact{
      background:rgb(184, 219, 251);
      padding:15px;
      margin:20px 0;
      border-radius:12px;
      box-shadow:0 6px 15px rgba(0,0,0,0.1);
      transition:transform 0.3s;
      display:flex;gap:15px;align-items:center;
    }
    .certi:hover{
        transform:translateY(-5px);
    }
    .contact p{
        margin:10px 0;
        font-size:16px;
    }
    .contact i{
        color:#0077b6;
        margin-right:8px;
    }
    .social-links a{
      display:inline-block;
      margin:10px 10px 0 0;
      padding:10px;
      border-radius:50%;
      background:#90e0ef;
      color:#03045e;
      text-decoration:none;
      font-size:18px;
      transition:0.3s;
    }
    .social-links a:hover{
        background:#0077b6;
        color:white;
    }
    footer{
        text-align:center;
        padding:20px;
        background:#155e70;
        color:white;
        margin-top:40px;
    }
    @media(
        max-width:700px
    ){
      .project-card{
        flex-direction:column;
        align-items:flex-start;
    }

      .project-card i{
        width:100%;
        height:auto;}
    }
  </style>
</head>
<body>
  <header>
     <h1>M Naveen Sai</b></h1>
    <p> <b>Pursuing B.Tech (2nd Year)</b></p>
    <p>-Artificial Intelligence & Data Science</p>
    <p>Mother Theresa Institute of Engineering and Technology</p>
    
  </header>
<nav>
   <h3><p><b>PORTFOLIO </b>  <i class="fa-solid fa-briefcase"></i></p></h3>
    <a href="#about"><i class="fa-solid fa-address-card"></i>About</a>
    <a href="#education"><i class="fa-solid fa-building-columns"></i>Education</a>
    <a href="#skills"><i class="fa-solid fa-link"></i>Skills</a>
    <a href="#projects"><i class="fa-solid fa-file-shield"></i>Projects</a>
    <a href="#certificates"><i class="fa-solid fa-certificate"></i>Certificates</a>
    <a href="#contact"><i class="fa-solid fa-phone-volume"></i>Contact</a>
  </nav>
  

  <section id="about">
    <h2>About Me</h2>
    <p>Hello! I am <b> M Naveen Sai</b>, a 2nd-year B.Tech student in AI & DS. I am passionate about programming, web development, and exploring Artificial Intelligence applications. I enjoy building mini-projects and improving my technical skills.</p>
  </section>

  <section id="education">
    <h2>Education</h2>
    <ul>
      <li><b>B.Tech (AI & DS):</b> Mother Theresa Institute of Engineering and Technology, CGPA: 8.45 (2024–2028)</li>
      <li><b>Intermediate (+2):</b> Mother Theresa Institute of Engineering and Technology, (2022-2024) — 91%</li>
      <li><b>SSC (10th):</b> Sri Sarada English Medium High School, 2022 — 89%</li>
    </ul>
  </section>

                                                                                                                                                                               
  <section id="skills">
    <h2>Technical Skills</h2>
    <div class="skills">
      <span><i class="fas fa-code"></i> C</span><br>
      <span><i class="fa-brands fa-python"></i></i> Python</span><br>
      <span><i class="fab fa-java"></i> Java</span><br>
     <span><i class="fab fa-html5"></i> HTML</span><br>
      <span><i class="fab fa-css3-alt"></i> CSS</span><br>
      <span><i class="fab fa-js"></i> JavaScript</span>
    </div>
  </section>

  <section id="projects">
    <h2>Mini Projects</h2>
    <div class="project-card">
        <div>
      <div class="proj">
        <i class="fa-solid fa-web-awesome fa-beat"></i>
    </div> 
    
        <b><h3><i class="fa-solid fa-database"></i></h3>  College Result Website</b>
        <p>Developed a dynamic web portal to allow students to view their marks and academic performance securely.This is focusing on user authentication, database design.</p>
      
    </div>
      
    </div>
   
    
    <div class="project-card">
      <div>
        <div class="proj">
               
        </div>
        <b> <h3><i class="fa-solid fa-briefcase"></i> </h3> Personal Portfolio Website (HTML, CSS, JS)</b>
        <p>Designed a responsive portfolio website to showcase skills, projects, and certifications.</p>
      </div>
    </div>
    <div class="project-card">
      <div>
        <div class="proj">
            
        </div>
        <b><h3><i class="fa-solid fa-calculator"></i></h3> Simple Calculator (java/HTML version)</b>
        <p>Created a basic calculator application using Java logic and HTML interface for user-friendly operations.</p>
      </div>
      
    </div>
  </section>

  <section id="certificates">
    <h2>Certificates</h2>
    <div class="certi">
    <ul>
        <li>Certificate of IIITK Completion of Hands-on Project [ Internship]</li>
       <li>Certificate of Achievement of Participating & Winning First Prize in ProjectExpo conducted by Kuppam Engineering College  </li>
      <li>Certificate of Virtual Internship – Cloud Gen AI</li>
      <li>Certificate of Achievement-Intellectual Property Rights, Legal & Ethical Steps for Startup</li>
    </ul>
    </div>
  </section>
    

   <section id="contact">
    <h2>Contact</h2>
    <div class="contact">
     
      <p><i class="fas fa-envelope"></i> <a href="mailto:naveenmuthu2028@gmail.com">naveenmuthu2028@gmail.com</a></p><br>
       <p><i class="fas fa-phone"></i> <a href="tel:+919505482090">+9195054820920</a></p> <br>
       <p><i class="fab fa-linkedin"></i><a href="https://www.linkedin.com/in/naveen-sai-m-25365131b?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app">LINKEDIN PROFILE</a></p>
    </div>
    <div class="social-links">
      <!-- You can add other social icons later if needed -->
      <a href="mailto:naveenmuthu2028@gmail.com" title="Email"><i class="fas fa-envelope"></i></a>
      <a href="tel:+919505482090" title="Call"><i class="fas fa-phone"></i></a>
      <a href="https://www.linkedin.com/in/naveen-sai-m-25365131b?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app" title="LinkedIn Profile">
    <i class="fab fa-linkedin"></i></a>
    </div>
  </section>

  <footer>
    © 2025 M Naveen Sai | All RIGHTS ARE RESERVED
</body>
</html>
