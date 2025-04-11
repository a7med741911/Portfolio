<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>AS</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="2.css">
    <link  rel="icon" href="d:\My project\task\3\7215642_resume_business_cv_work_job_icon.png">

    <!-- --------- UNICONS ---------- -->
    <link rel="stylesheet" href="https://unicons.iconscout.com/release/v4.0.8/css/line.css">

    <!-- --------- FAVICON ---------- -->
    <link rel="shortcut icon" href="assets/images/favicon.png" type="image/x-icon">
</head>
<body>
   <div class="container">
    <!-- --------------- HEADER --------------- -->
      <nav id="header">
        <div class="nav-logo">
            <p class="nav-name">AS</p>
            <span>.</span>
        </div>
        <div class="nav-menu" id="myNavMenu">
            <ul class="nav_menu_list">
                <li class="nav_list">
                    <a href="#home" class="nav-link active-link">Home</a>
                    <div class="circle"></div>
                </li>
                <li class="nav_list">
                    <a href="#about" class="nav-link">About</a>
                    <div class="circle"></div>
                </li>
                <li class="nav_list">
                    <a href="#projects" class="nav-link">Projects</a>
                    <div class="circle"></div>
                </li>
                <li class="nav_list">
                    <a href="#contact" class="nav-link">Contact</a>
                    <div class="circle"></div>
                </li>
            </ul>
        </div>
        <div class="nav-button">
            <button class="btn" onclick="location.href='Portfolio.pdf'">Portfolio<i class="uil uil-file-alt"></i></button>
        </div>
        <div class="nav-menu-btn">
            <i class="uil uil-bars" onclick="myMenuFunction()"></i>
        </div>
      </nav>
    <!-- -------------- MAIN ---------------- -->
    <main class="wrapper">
       <!-- -------------- FEATURED BOX ---------------- -->
       <section class="featured-box" id="home">
          <div class="featured-text">
            <div class="featured-text-card">
                <span>Ahmed Samir</span>
            </div>
            <div class="featured-name">
                <p>I'm <span class="typedText"></span></p>
            </div>
            <div class="featured-text-info">
                <p>Experienced frontend developer with a passion for creating visually stunning
                   and user-friendly websites.
                </p>
            </div>
            <div class="featured-text-btn">
                <button class="btn blue-btn">contact</button>
                <button class="btn" onclick="location.href='https://drive.google.com/file/d/1xwiIo2FFn1IgE3wby9O5hD3WprqzV6-D/view?usp=sharing'">Download CV <i class="uil uil-file-alt" ></i></button>
            </div>
            <div class="social_icons">
                <div class="icon"><a href="https://www.instagram.com/_a7medsa_/"><i class="uil uil-instagram"></i></a></div>
                <div class="icon"><a href="https://www.linkedin.com/in/ahmed-samir-84512b233/"><i class="uil uil-linkedin-alt"></i></a></div>
                <div class="icon"><a href="https://www.facebook.com/profile.php?id=100012858407076"><i class="uil uil-facebook"></i></a></div>
                <div class="icon"><a href="https://github.com/a7med741911"><i class="uil uil-github-alt"></i></a></div>
            </div>
          </div>
          <div class="featured-image">
            <div class="image">
                <img src="2.jpg" alt="avatar">
            </div>
          </div>
          <div class="scroll-icon-box">
            <a href="#about" class="scroll-btn">
                <i class="uil uil-mouse-alt"></i>
                <p>Scroll Down</p>
            </a>
          </div>
       </section>
       <!-- -------------- ABOUT BOX ---------------- -->
       <section class="section" id="about">
          <div class="top-header">
            <h1>About Me</h1>
          </div>
          <div class="row">
            <div class="col">
                <div class="about-info">
                    <h3>My introduction</h3>
                    <p>A passionate front-end developer with a solid foundation HTML ,CSS,BootstrapJavaScript.I specialize in building responsive ,user-friendly websites and interfaces .my skills inweb development allow me to create visually appealing and functional designs thatenhance user experience .I am always eager to learn new technologies and improvemy coding skills to stay up-to-date with industry trends.
                    </p>
             
                </div>
            </div>
            <div class="col">
                <div class="skills-box">
                    <div class="skills-header">
                        <h3>Frontend</h3>
                    </div>
                    <div class="skills-list">
                        <span>HTML</span>
                        <span>CSS</span>
                        <span>Bootstrap</span>
                        <span>JavaScript</span>
                        <span>UI/UX</span>
                        <span>React</span>
                    </div>
                </div>
            </div>
          </div>
       </section>
       <!-- -------------- PROJECT BOX ---------------- -->

       <section class="section" id="projects">
          <div class="top-header">
              <h1>Projects</h1>
          </div>
          <div class="project-container">
            <div class="project-box">
                <i class="uil uil-briefcase-alt"></i>
                <h3>Nankol</h3>
                <label></label>
            </div>
            <div class="project-box">
                <i class="uil uil-users-alt"></i>
                <h3>Ma3rfa</h3>
                <label></label>
            </div>
            <div class="project-box">
                <i class="uil uil-award"></i>
                <h3></h3>
                <label></label>
            </div>
          </div>
       </section>

       <!-- -------------- CONTACT BOX ---------------- -->

       <section class="section" id="contact">
          <div class="top-header">
            <h1>Get in touch</h1>
            <span>Do you have a project in your mind, contact me here</span>
          </div>
          <div class="row">
             <div class="col">
                <div class="contact-info">
                    <h2>Find Me <i class="uil uil-corner-right-down"></i></h2>
                    <p><i class="uil uil-envelope"></i> Email: a7med.samir741911@gmail.com</p>
                    <p><i class="uil uil-phone"></i> Tel: +20 1006160704</p>
                </div>
             </div>
             <div class="col">
                <div class="form-control">
                    <div class="form-inputs">
                        <input type="text" class="input-field" placeholder="Name">
                        <input type="text" class="input-field" placeholder="Email">
                    </div>
                    <div class="text-area">
                        <textarea placeholder="Message"></textarea>
                    </div>
                    <div class="form-button">
                        <button class="btn">Send <i class="uil uil-message"></i></button>
                    </div>
                </div>
             </div>
          </div>
       </section>

    </main>


    <!-- --------------- FOOTER --------------- -->
    <footer>
        <div class="top-footer">
            <p>Ahmed Samir</p>
        </div>
        <div class="middle-footer">
            <ul class="footer-menu">
                <li class="footer_menu_list">
                    <a href="#home">Home</a>
                </li>
                <li class="footer_menu_list">
                    <a href="#about">About</a>
                </li>
                <li class="footer_menu_list">
                    <a href="#projects">Projects</a>
                </li>
                <li class="footer_menu_list">
                    <a href="#contact">Contact</a>
                </li>
            </ul>
        </div>
        <div class="footer-social-icons">
            <div class="icon"><i class="uil uil-instagram"></i></div>
            <div class="icon"><i class="uil uil-linkedin-alt"></i></div>
            <div class="icon"><i class="uil uil-dribbble"></i></div>
            <div class="icon"><i class="uil uil-github-alt"></i></div>
        </div>
        <div class="bottom-footer">
            <p>Copyright &copy; <a href="#home" style="text-decoration: none;">Ahmed Samir</a> - All rights reserved</p>
        </div>
    </footer>

    </div>




    <!-- ----- TYPING JS Link ----- -->
    <script src="https://unpkg.com/typed.js@2.0.16/dist/typed.umd.js"></script>

       <!-- ----- SCROLL REVEAL JS Link----- -->
    <script src="https://unpkg.com/scrollreveal"></script>

    <!-- ----- MAIN JS ----- -->
    <script src="assets/js/main.js"></script>
</body>
</html>
