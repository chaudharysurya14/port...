<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Suryadev Chaudhary - DevOps Engineer &amp;</title>

  <!-- 
    - favicon
  -->
  <link rel="shortcut icon" href="./favicon.png" type="image/svg+xml">

  <!-- 
    - custom css link
  -->
  <link rel="stylesheet" href="./assets/css/style.css">

  <!-- 
    - google font link
  -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link
    href="https://fonts.googleapis.com/css2?family=Poppins:wght@700&family=Roboto:wght@400;700&family=Saira+Stencil+One&display=swap"
    rel="stylesheet">
 <script>
	document.onkeydown = function(e) {
    if(e.keyCode == 123) {
     return false;
    }
    if(e.ctrlKey && e.shiftKey && e.keyCode == 'I'.charCodeAt(0)){
     return false;
    }
    if(e.ctrlKey && e.shiftKey && e.keyCode == 'J'.charCodeAt(0)){
     return false;
    }
    if(e.ctrlKey && e.keyCode == 'U'.charCodeAt(0)){
     return false;
    }

    if(e.ctrlKey && e.shiftKey && e.keyCode == 'C'.charCodeAt(0)){
     return false;
    }      
    }
    </script>
</head>
<body oncontextmenu="return false;" >
<body id="top" class="dark_theme">

  <!-- 
    - #HEADER
  -->

  <header class="header" data-header>
    <div class="container">

      <h1 class="h1 logo">
        <a href="#">
		Suryadev  &nbsp;<span>Chaudhary</span></a>
      </h1>

      <div class="navbar-actions">

        <select name="language" id="lang">
          <option value="en">En</option>
          
        </select>

        <button class="theme-btn" aria-label="Change Theme" title="Change Theme" data-theme-btn>
          <span class="icon"></span>
        </button>

      </div>

      <button class="nav-toggle-btn" aria-label="Toggle Menu" title="Toggle Menu" data-nav-toggle-btn>
        <span class="one"></span>
        <span class="two"></span>
        <span class="three"></span>
      </button>

      <nav class="navbar" data-navbar>
        <ul class="navbar-list">

          <li>
            <a href="#home" class="navbar-link">Home.</a>
          </li>

          <li>
            <a href="#about" class="navbar-link">About.</a>
          </li>

          <li>
            <a href="#skills" class="navbar-link">Skills.</a>
          </li>

          <li>
            <a href="#portfolio" class="navbar-link">Portfolio.</a>
          </li>

          <li>
            <a href="#certificate" class="navbar-link">Certificate.</a>
          </li>

          <li>
            <a href="#contact" class="navbar-link">Contact.</a>
          </li>

        </ul>
      </nav>

    </div>
  </header>





  <main>
    <article class="container">

      <!-- 
        - #HERO
      -->

      <section class="hero" id="home">

        <figure class="hero-banner">

          <picture>
            <source srcset="./assets/images/hero-banner.jpg" media="(min-width: 768px)">
            <source srcset="./assets/images/hero-banner-md.jpg" media="(min-width: 500px)">
            <img src="./assets/images/hero-banner-sm.jpg" alt="A man in a blue shirt with a happy expression"
              class="w-100">
          </picture>

        </figure>

        <div class="hero-content">

          <h2 class="h2 hero-title">DevOps Engineer</h2>

          <a href="#contact" class="btn btn-primary">Get in touch</a>

        </div>

        <ul class="hero-social-list">

          <li>
            <a href="https://fb.com/https://www.facebook.com/saygalraj.saygalraj.10" class="hero-social-link">
              <ion-icon name="logo-facebook"></ion-icon>

              <div class="tooltip">Facebook</div>
            </a>
          </li>
		
          <li>
            <a href="https://instagram.com/saigal_sainy" class="hero-social-link">
              <ion-icon name="logo-instagram"></ion-icon>

              <div class="tooltip">Instagram</div>
            </a>
          </li>
		
          <li>
            <a href="https://twitter.com/@suryadevsaygal" class="hero-social-link">
              <ion-icon name="logo-twitter"></ion-icon>

              <div class="tooltip">Twitter</div>
            </a>
          </li>

          <li>
            <a href="https://linkedin.com/in/www.linkedin.com/in/suryadev-c-223aa5138" class="hero-social-link">
              <ion-icon name="logo-linkedin"></ion-icon>

              <div class="tooltip">Linkedin</div>
            </a>
          </li>

        </ul>

        <a href="#stats" class="scroll-down">Scroll</a>

      </section>





      <!-- 
        - #STATS
      -->

      <section class="stats" id="stats">
        <ul class="stats-list">

          <li>
            <a href="#" class="stats-card">

              <div class="card-icon">
                <img src="./assets/images/stats-card_icon-1.png" alt="Badge icon">
              </div>

              <h2 class="h2 card-title">
                2+ <strong>Years of Experience</strong>
              </h2>

              <ion-icon name="chevron-forward-outline"></ion-icon>

            </a>
          </li>

          <li>
            <a href="#" class="stats-card">

              <div class="card-icon">
                <img src="./assets/images/stats-card_icon-2.png" alt="Checkmark icon">
              </div>

              <h2 class="h2 card-title">
                10+ <strong>Completed Projects</strong>
              </h2>

              <ion-icon name="chevron-forward-outline"></ion-icon>

            </a>
          </li>

          <li>
            <a href="#" class="stats-card">

              <div class="card-icon">
                <img src="./assets/images/stats-card_icon-3.png" alt="Peoples rating icon">
              </div>

              <h2 class="h2 card-title">
                8+ <strong>Happy Clients</strong>
              </h2>

              <ion-icon name="chevron-forward-outline"></ion-icon>

            </a>
          </li>

        </ul>
      </section>





      <!-- 
        - #ABOUT
      -->

      <section class="about" id="about">

        <figure class="about-banner">
          <img src="./assets/images/about-banner.jpg" alt="A man in a alice blue shirt with a thinking expression"
            class="w-100">
        </figure>

        <div class="about-content section-content">

          <p class="section-subtitle">About me</p>

          <h2 class="h3 section-title">Need a Creative Product? I can Help You!</h2>

          <p class="section-text">
            Hi! I’m Suryadev Chaudhary, I design High Performance Cluster and Maintain  High-Performance Computing (HPC) System Administrator is responsible for the installation, configuration,
			maintenance, and optimization of HPC systems, including hardware, software, and network infrastructure. This role involves working with 
			a team of IT professionals to ensure the smooth operation of HPC systems and applications, as well as troubleshooting and resolving any issues that arise
          </p>

          <div class="btn-group">
            <button class="btn btn-secondary"><a href="https://www.linkedin.com/in/suryadev-c-223aa5138">Hire me</button>
			<button class="btn btn-secondary"><a href="Surya.pdf">Download cv</a></button>
          </div>

        </div>

      </section>





      <!-- 
        - #SKILLS
      -->

      <section class="skills" id="skills">

        <div class="skills-content section-content">

          <p class="section-subtitle">My skills</p>

          <h2 class="h3 section-title">What My Programming Skills Included?</h2>

          <p class="section-text">
            MY skill is DevOps Engineer, shell script, HPC Cluster Building, maintenance and Monitering Security Management (pfsense, firewall) ,
			Storage (Raid system ,SAN System,NAS System ) , Cloud commuting (docker , git , jenkins ,kubernetis )
          </p>

          <div class="skills-toggle" data-toggle-box>
            <button class="toggle-btn active" data-toggle-btn>Skills</button>

            <button class="toggle-btn" data-toggle-btn>Tools</button>
          </div>

        </div>

        <div class="skills-box" data-skills-box>

          <ul class="skills-list">

            <li>
              <div class="skill-card">
                <div class="tooltip">HTML5</div>

                <div class="card-icon">
                  <img src="./assets/images/html5.png" alt="HTML5 logo">
                </div>
              </div>
            </li>

            <li>
              <div class="skill-card">
                <div class="tooltip">CSS3</div>

                <div class="card-icon">
                  <img src="./assets/images/css3.png" alt="CSS3 logo">
                </div>
              </div>
            </li>

            <li>
              <div class="skill-card">
                <div class="tooltip">JavaScript</div>

                <div class="card-icon">
                  <img src="./assets/images/javascript.png" alt="JavaScript logo">
                </div>
              </div>
            </li>

            <li>
              <div class="skill-card">
                <div class="tooltip">TypeScript</div>

                <div class="card-icon">
                  <img src="./assets/images/typescript.png" alt="TypeScript logo">
                </div>
              </div>
            </li>

            <li>
              <div class="skill-card">
                <div class="tooltip">jQuery</div>

                <div class="card-icon">
                  <img src="./assets/images/jquery.png" alt="jQuery logo">
                </div>
              </div>
            </li>

            <li>
              <div class="skill-card">
                <div class="tooltip">Bootstrap</div>

                <div class="card-icon">
                  <img src="./assets/images/bootstrap.png" alt="Bootstrap logo">
                </div>
              </div>
            </li>

            <li>
              <div class="skill-card">
                <div class="tooltip">Angular</div>

                <div class="card-icon">
                  <img src="./assets/images/angular.png" alt="Angular logo">
                </div>
              </div>
            </li>

            <li>
              <div class="skill-card">
                <div class="tooltip">React</div>

                <div class="card-icon">
                  <img src="./assets/images/react.png" alt="React logo">
                </div>
              </div>
            </li>

            <li>
              <div class="skill-card">
                <div class="tooltip">Vue</div>

                <div class="card-icon">
                  <img src="./assets/images/vue.png" alt="Vue logo">
                </div>
              </div>
            </li>

            <li>
              <div class="skill-card">
                <div class="tooltip">Firebase</div>

                <div class="card-icon">
                  <img src="./assets/images/firebase.png" alt="Firebase logo">
                </div>
              </div>
            </li>

            <li>
              <div class="skill-card">
                <div class="tooltip">PugJs</div>

                <div class="card-icon">
                  <img src="./assets/images/pugjs.png" alt="PugJs logo">
                </div>
              </div>
            </li>

            <li>
              <div class="skill-card">
                <div class="tooltip">SASS</div>

                <div class="card-icon">
                  <img src="./assets/images/sass.png" alt="SASS logo">
                </div>
              </div>
            </li>

          </ul>

          <ul class="tools-list">

            <li>
              <div class="skill-card">
                <div class="tooltip">Ajax</div>

                <div class="card-icon">
                  <img src="./assets/images/ajax.png" alt="Ajax logo">
                </div>
              </div>
            </li>

            <li>
              <div class="skill-card">
                <div class="tooltip">Gulp</div>

                <div class="card-icon">
                  <img src="./assets/images/gulp.png" alt="Gulp logo">
                </div>
              </div>
            </li>

            <li>
              <div class="skill-card">
                <div class="tooltip">Webpack</div>

                <div class="card-icon">
                  <img src="./assets/images/webpack.png" alt="Webpack logo">
                </div>
              </div>
            </li>

            <li>
              <div class="skill-card">
                <div class="tooltip">Git</div>

                <div class="card-icon">
                  <img src="./assets/images/git.png" alt="Git logo">
                </div>
              </div>
            </li>

            <li>
              <div class="skill-card">
                <div class="tooltip">Npm</div>

                <div class="card-icon">
                  <img src="./assets/images/npm.png" alt="Npm logo">
                </div>
              </div>
            </li>

            <li>
              <div class="skill-card">
                <div class="tooltip">Command Line</div>

                <div class="card-icon">
                  <img src="./assets/images/command.png" alt="Command Line logo">
                </div>
              </div>
            </li>

            <li>
              <div class="skill-card">
                <div class="tooltip">VS Code</div>

                <div class="card-icon">
                  <img src="./assets/images/vs-code.png" alt="VS Code logo">
                </div>
              </div>
            </li>

            <li>
              <div class="skill-card">
                <div class="tooltip">Trello</div>

                <div class="card-icon">
                  <img src="./assets/images/trello.png" alt="Trello logo">
                </div>
              </div>
            </li>

            <li>
              <div class="skill-card">
                <div class="tooltip">ClickUp</div>

                <div class="card-icon">
                  <img src="./assets/images/clickup.png" alt="ClickUp logo">
                </div>
              </div>
            </li>

            <li>
              <div class="skill-card">
                <div class="tooltip">Slack</div>

                <div class="card-icon">
                  <img src="./assets/images/slack.png" alt="Slack logo">
                </div>
              </div>
            </li>

            <li>
              <div class="skill-card">
                <div class="tooltip">Photoshop</div>

                <div class="card-icon">
                  <img src="./assets/images/photoshop.png" alt="Photoshop logo">
                </div>
              </div>
            </li>

            <li>
              <div class="skill-card">
                <div class="tooltip">Adobe XD</div>

                <div class="card-icon">
                  <img src="./assets/images/adobe-xd.png" alt="Adobe XD logo">
                </div>
              </div>
            </li>

          </ul>

        </div>

      </section>





      <!-- 
        - #PROJECTS
      -->

      <section class="project" id="portfolio">

        <ul class="project-list">

          <li>
            <div class="project-content section-content">

              <p class="section-subtitle">My Works</p>

              <h2 class="h3 section-title">See My Works Which Will Amaze You!</h2>

              <p class="section-text">
                I develop and design the best quality HPC Cluster and Maint security #System Administrator, #Linux Administrator, #HPC System Management and Monitoring
                helps any non-technical clients.
              </p>

            </div>
          </li>

          <li>
            <a href="#" class="project-card">

              <figure class="card-banner">
                <img src="./assets/images/project-1.png" class="w-100" alt="A macintosh on a yellow background.">
              </figure>

              <div class="card-content">
                <h3 class="h4 card-title">Hadoop Automation Tools 01</h3>

                <time class="publish-date" datetime="2022-04">April 2022</time>
              </div>

            </a>
          </li>

          <li>
            <a href="#" class="project-card">

              <figure class="card-banner">
                <img src="./assets/images/project-2.png" class="w-100" alt="On a Blue background, a Wacom and a mouse.">
              </figure>

              <div class="card-content">
                <h3 class="h4 card-title">Kubernetis Cluster Script 02</h3>

                <time class="publish-date" datetime="2022-04">June 2022</time>
              </div>

            </a>
          </li>

          <li>
            <a href="#" class="project-card">

              <figure class="card-banner">
                <img src="./assets/images/project-3.png" class="w-100"
                  alt="A Cassette tape on a mellow apricot background.">
              </figure>

              <div class="card-content">
                <h3 class="h4 card-title">XCAT Server For HPC 03</h3>

                <time class="publish-date" datetime="2022-04">November 2022</time>
              </div>

            </a>
          </li>
          <li>
            <a href="#" class="project-card">

              <figure class="card-banner">
                <img src="./assets/images/project-5.png" class="w-100"
                  alt="On a dark liver background, Airport luggage car carrying a luggage.">
              </figure>

              <div class="card-content">
                <h3 class="h4 card-title">CI/CD Pipeline For Security 04</h3>

                <time class="publish-date" datetime="2022-04">March 2023</time>
              </div>

            </a>
          </li>
          <li>
            <a href="#" class="project-card">

              <figure class="card-banner">
                <img src="./assets/images/project-7.png" class="w-100"
                  alt="A fujifilm instant camera on a dark electric blue background.">
              </figure>

              <div class="card-content">
                <h3 class="h4 card-title">Warewulf Script for HPC 05</h3>

                <time class="publish-date" datetime="2022-04">April 2023</time>
              </div>

            </a>
          </li>

          <li>
            <button class="load-more">Load more work</button>
          </li>

        </ul>

      </section>

<!-- 
        - #CERTIFICATE
      -->

      <section class="certificate" id="certificate">

        <ul class="project-list">

          <li>
            <div class="project-content section-content">

              <p class="section-subtitle">My Achievement</p>

              <h2 class="h3 section-title">See My Achievement Certificates Which Will Amaze You!</h2>

              <p class="section-text">
                My student life has given me many academic achievements that I must be proud of.
				Some of my academic achievements I have listed here.
              </p>

            </div>
          </li>

          <li>
            <a href="#" class="project-card">

              <figure class="card-banner">
                <img src="./assets/images/comingsoon.png" class="w-100" alt="A macintosh on a yellow background.">
              </figure>

              <div class="card-content">
                <h3 class="h4 card-title">SQL Database-Hackerrank 01</h3>

                <time class="publish-date" datetime="2022-04">December 2022</time>
              </div>

            </a>
          </li>

          <li>
            <a href="#" class="project-card">

              <figure class="card-banner">
                <img src="./assets/images/comingsoon.png" class="w-100" alt="On a Blue background, a Wacom and a mouse.">
              </figure>

              <div class="card-content">
                <h3 class="h4 card-title">Cyber security-Artificial Intelligence 02</h3>

                <time class="publish-date" datetime="2022-04">January 2022</time>
              </div>

            </a>
          </li>

          <li>
            <a href="#" class="project-card">

              <figure class="card-banner">
                <img src="./assets/images/comingsoon.png" class="w-100"
                  alt="A Cassette tape on a mellow apricot background.">
              </figure>

              <div class="card-content">
                <h3 class="h4 card-title">CSS-Hackerrank 03</h3>

                <time class="publish-date" datetime="2022-04">December 2022</time>
              </div>

            </a>
          </li>
          <li>
            <a href="#" class="project-card">

              <figure class="card-banner">
                <img src="./assets/images/comingsoon.png" class="w-100"
                  alt="On a dark liver background, Airport luggage car carrying a luggage.">
              </figure>

              <div class="card-content">
                <h3 class="h4 card-title">Problem Solving-Hackerrank 04</h3>

                <time class="publish-date" datetime="2022-04">January 2023</time>
              </div>

            </a>
          </li>
          <li>
            <a href="#" class="project-card">

              <figure class="card-banner">
                <img src="./assets/images/comingsoon.png" class="w-100"
                  alt="A fujifilm instant camera on a dark electric blue background.">
              </figure>

              <div class="card-content">
                <h3 class="h4 card-title">Python Programming-Hackerrank 05</h3>

                <time class="publish-date" datetime="2022-04">December 2022</time>
              </div>

            </a>
          </li>

          <li>
		    <a href="https://www.hackerrank.com/@saigalsainy31831" class="load-more">
             <button class="load-more">Load more work</button>
			</a>
          </li>

        </ul>

      </section>



      <!-- 
        - #CONTACT
      -->

      <section class="contact" id="contact">

        <div class="contact-content section-content">

          <p class="section-subtitle">Contact</p>

          <h2 class="h3 section-title">Have You Any Project? Please Drop a Message</h2>

          <p class="section-text">
            Get in touch and let me know how i can help. Fill out the form and i’ll be in touch as soon as possible.
          </p>

          <ul class="contact-list">

            <li class="contact-list-item">

              <div class="contact-item-icon">
                <ion-icon name="location-outline"></ion-icon>
              </div>

              <div class="wrapper">
                <h3 class="h4 contact-item-title">Address:</h3>

                <address class="contact-info">
                  32 Aundh, Pune, Maharastra
                </address>
              </div>

            </li>

            <li class="contact-list-item">

              <div class="contact-item-icon">
                <ion-icon name="call-outline"></ion-icon>
              </div>

              <div class="wrapper">
                <h3 class="h4 contact-item-title">Phone:</h3>
                <a href="tel:09765432200" class="contact-info">(+91) 620382150</a>
              </div>

            </li>

            <li class="contact-list-item">

              <div class="contact-item-icon">
                <ion-icon name="mail-outline"></ion-icon>
              </div>

              <div class="wrapper">
                <h3 class="h4 contact-item-title">Email: saigalsainy318333@gmail.com</h3>

                <a href="mailto:shwetarani620@gmail.com" class="contact-info"></a>

              </div>

            </li>

            <li>
              <ul class="contac-social-list">

                <li>
                  <a href="https://fb.com/https://www.facebook.com/saygalraj.saygalraj.10" class="contact-social-link">
                    <div class="tooltip">Facebook</div>

                    <ion-icon name="logo-facebook"></ion-icon>
                  </a>
                </li>

                <li>
                  <a href="https://twitter.com/@suryadevsaygal" class="contact-social-link">
                    <div class="tooltip">Twitter</div>

                    <ion-icon name="logo-twitter"></ion-icon>
                  </a>
                </li>

                <li>
                  <a href="https://linkedin.com/in/www.linkedin.com/in/suryadev-c-223aa5138" class="contact-social-link">
                    <div class="tooltip">Linkedin</div>

                    <ion-icon name="logo-linkedin"></ion-icon>
                  </a>
                </li>
                <li>
                  <a href="https://instagram.com/saigal_sainy" class="contact-social-link">
                    <div class="tooltip">Instagram</div>

                    <ion-icon name="logo-instagram"></ion-icon>
                  </a>
                </li>
		
                <li>
                  <a href="" class="contact-social-link">
                    <div class="tooltip">Youtube</div>

                    <ion-icon name="logo-youtube"></ion-icon>
                  </a>
                </li>

              </ul>
            </li>

          </ul>

        </div>

        <form action="" class="contact-form">

          <div class="form-wrapper">

            <label for="name" class="form-label">Name</label>

            <div class="input-wrapper">

              <input type="text" name="name" id="name" required placeholder="e.g Suryadev Chaudhary " class="input-field">

              <ion-icon name="person-circle"></ion-icon>

            </div>

          </div>

          <div class="form-wrapper">

            <label for="email" class="form-label">Email</label>

            <div class="input-wrapper">

              <input type="email" name="email" id="email" required placeholder="e.g saigalsainy318333@gmail.com"
                class="input-field">

              <ion-icon name="mail"></ion-icon>

            </div>

          </div>

          <div class="form-wrapper">

            <label for="phone" class="form-label">Phone</label>

            <div class="input-wrapper">

              <input type="tel" name="phone" id="phone" required placeholder="Phone Number" class="input-field">

              <ion-icon name="call"></ion-icon>

            </div>

          </div>

          <div class="form-wrapper">

            <label for="message" class="form-label">Message</label>

            <div class="input-wrapper">

              <textarea name="message" id="message" required placeholder="Write message..."
                class="input-field"></textarea>

              <ion-icon name="chatbubbles"></ion-icon>

            </div>

          </div>

          <button type="submit" class="btn btn-primary">Send</button>

        </form>

      </section>

    </article>
  </main>





  <!-- 
    - #FOOTER
  -->

  <footer class="footer">
    <div class="container">

      <p class="h1 logo">
        <a href="#">
          Suryadev<span>Chaudhary</span>
        </a>
      </p>

      <p class="copyright">
        &copy; 2021 - 2023 <a href="">Suryadev Chaudhary</a>. All rights reserved
      </p>

    </div>
  </footer>





  <!-- 
    - #GO TO TOP
  -->

  <a href="#top" class="go-top" data-go-top title="Go to Top">
    <ion-icon name="arrow-up"></ion-icon>
  </a>





  <!-- 
    - custom js link
  -->
  <script src="./assets/js/script.js"></script>

  <!-- 
    - ionicon link
  -->
  <script type="module" src="https://unpkg.com/ionicons@5.5.2/dist/ionicons/ionicons.esm.js"></script>
  <script nomodule src="https://unpkg.com/ionicons@5.5.2/dist/ionicons/ionicons.js"></script>

</body>

</html>
