<!DOCTYPE html>
<html>
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1">
        <title>Darco Murja</title>
        <link rel="stylesheet" href="https://unpkg.com/aos@next/dist/aos.css" />
        <link href="https://fonts.googleapis.com/css?family=Scheherazade&display=swap" rel="stylesheet">
        <link href="https://fonts.googleapis.com/css?family=Cinzel&display=swap" rel="stylesheet"> 
        <link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.7.2/css/all.css" integrity="sha384-fnmOCqbTlWIlj8LyTjo7mOUStjsKC4pOpQbqyi7RrhN7udi9RwhKkMHpvLbHG9Sr" crossorigin="anonymous">
        <link rel="stylesheet" href="main.css">
    </head> 
    <body>
        <header>
            <div class="menu-toggler">
                <div class="bar half start"></div>
                <div class="bar"></div>
                <div class="bar half end"></div>
            </div>
            <nav class="top-nav">
                <ul class="nav-list">
                    <li>
                        <a href="index.html" class="nav-link">Home</a>
                    </li>
                    <li>
                        <a href="#about" class="nav-link">About</a>
                    </li>
                    <li>
                        <a href="#services" class="nav-link">Services</a>
                    </li>
                    <li>
                        <a href="#potfolio" class="nav-link">Portfolio</a>
                    </li>
                    <li>
                        <a href="#experience" class="nav-link">Experience</a>
                    </li>
                    <li>
                        <a href="#contact" class="nav-link">Contact</a>
                    </li>
                </ul>
            </nav>

            <div class="landing-text">
                <h1>Darco Murja</h1>
                <h6>Mobile apps | Design | Computer Science student </h6>
            </div>
        </header>

    <section class="about" id="about">
        <div class="container">
            <div class="progile-img" data-aos="fade-right" data-aos-delay="300">
                <img src="profile_picture.jpg" alt="">
            </div>
            <div class="about-details" data-aos="fade-left" data-aos-delay="600">
                <div class="about-heading">
                    <h1>About</h1>
                    <h6>Myself</h6>
                </div>
                <p>
                    Young and driven Computer Science student from Timisoara, Romania
                </p>
                <p>
                    I am looking to gain proffesional experience in mobile development and software engineering.
                </p>
                    <div class="social-media">
                        <ul class="nav-list">
                            <li>
                                <a href="https://www.facebook.com/darco.murja" target="_blank" class="icon-link">
                                    <i class="fab fa-facebook-square"></i>
                                </a>
                            </li>
                            <li>
                                <a href="https://github.com/darco918" target="_blank" class="icon-link">
                                    <i class="fab fa-github"></i>
                                </a>
                            </li>
                            <li>
                                <a href="https://www.instagram.com/darco_paul/" target="_blank" class="icon-link">
                                    <i class="fab fa-instagram"></i>
                                </a>
                            </li>
                        </ul>
                    </div>
            </div>
        </div>
    </section>

    <section class="services" id="services">
        <div class="container">
            <div class="section-heading">
                <h1>Interests</h1>
                <h6>What I like to do</h6>
            </div>
            <div class="my-skills">
                <div class="skill" data-aos="fade-in" data-aos-delay="300">
                    <div class="icon-container">
                        <i class="fab fa-android"></i>
                    </div>
                    <h1>Android Development</h1>
                    <p>Lorem ipsum dolor sit amet consectetur
                     </p>
                </div>
            </div>
            <div class="my-skills">
                <div class="skill" data-aos="fade-in" data-aos-delay="600">
                    <div class="icon-container">
                        <i class="fas fa-file-code"></i>
                    </div>
                    <h1>Web Development</h1>
                    <p>Lorem ipsum dolor sit amet consectetur</p>
                </div>
            </div>
            
        </div>
    </section>

    <section class="portfolio" id="portfolio">
        <div class="container">
            <div class="section-heading">
                <h1>Portfolio</h1>
                <h6>View some of my recent work</h6>
            </div>
            <div class="portfolio-item">
                <div class="portfolio-img has-margin-right" data-aos="fade-right" data-aos-delay="300">
                    <img src="osut_screenshots.png" alt="">
                </div>
                <div class="portfolio-description" data-aos="fade-left" data-aos-delay="700">
                    <h6>Android</h6>
                    <h1>OSUT Companion</h1>
                    <h3>Description</h3>
                    <p>OSUT is a non-profit organisation from the Western University of Timisoara with hundreds of volunteers who advocate for students' rights in Romania.
                        They organise workshops and local events to improve the quality of life on campus.
                    </p>
                    <h3>Challenge</h3>
                    <p> Osut needed a way to organise the volunteers' contact information and
                        to communicate future events plans easily.
                    </p>
                    <h3>My role</h3>
                    <p>I listened to the leaders' needs and came up with a model to fulfill them. I designed and developed the app myself.
                    </p>
                    <h3>Technologies used</h3>
                    <p> Designed in Adobe XD.</p>
                    <p> Built in Android Studio using Kotlin and Firebase Authentification and Realtime Database.</p>

                 <!---- <a href="#" class="cta">View Details</a> -->
                </div>
            </div>
            <div class="portfolio-item">
                <div class="portfolio-description" data-aos="fade-right" data-aos-delay="900">
                    <h6>Android</h6>
                    <h1>Tip Calculator </h1>
                    <h3>Description</h3>
                    <p>Tip Calculator is a personal project I started with a friend. The main goal behind was to improve my skills and get familiar
                        with Firebase and Adobe XD.
                    </p>
                    <h3>Challenge</h3>
                    <p> The app computes the tip from a bill based on the user's country. It is a travelling aid app that will help you in restaurants, bars, hotels or taxis.
                    </p>
                    <h3>My role</h3>
                    <p>I built around simplicity with an intuitive UI. I created the tip calculator itself and the country selector connected to a realtime database.
                        I have also researched the customs from over 25 countries   </p>
                    <h3>Technologies used</h3>
                    <p> Designed in Adobe XD.</p>
                    <p>The app was created in Kotlin in Android Studio, connected to Firebase and designed in Adobe XD.</p>

                    <a href="#" class="cta">View Details</a>
                </div>
                <div class="portfolio-img" data-aos="fade-left" data-aos-delay="1200">
                    <img src="portitem2.jpeg" alt="">
                </div>
            </div>
            <div class="portfolio-item">
                <div class="portfolio-img has-margin-right" data-aos="fade-right" data-aos-delay="1500">
                    <img src="portitem3.jpeg" alt="">
                </div>
                <div class="portfolio-description" data-aos="fade-left" data-aos-delay="1800">
                    <h6>Web Design</h6>
                    <h1>Product Sketch</h1>
                    <p>Lorem ipsum dolor sit amet consectetur
                        adipiscing elit, dui quis non nec sagittis curabitur,
                         sociosqu posuere potenti porta at senectus.</p>
                    <a href="#" class="cta">View Details</a>
                </div>
            </div>
        </div>
    </section>

    <section class="experience" id="experience">
        <div class="container">
            <div class="section-heading">
                <h1>Work Experience</h1>
                <h6>Past and current jobs</h6>
            </div>
            <div class="timeline" data-aos="fade-down" data-aos-delay="300">
                <ul>
                    <li class="date" data-date="2019 - Present">
                        <h1>Google</h1>
                        <p>   Lorem ipsum dolor sit amet consectetur adipiscing elit,</p>
                    </li>
                    <li class="date" data-date="2021 - Present">
                        <h1>Facebook</h1>
                        <p>   Lorem ipsum dolor sit amet consectetur adipiscing elit,</p>
                    </li>
                    <li class="date" data-date="2022 - Present">
                        <h1>  EA Sports</h1>
                        <p>       Lorem ipsum dolor sit amet consectetur adipiscing elit,</p>
                    </li>
                </ul>
            </div>
        </div>
     </section>


     <section class="contact" id="contact">
        <div class="container">
            <div class="section-heading">
                <h1>contact</h1>
                <h6>Let's work together</h6>
            </div>
           
        </div>
    </section>

    <footer class="copyright">
        <div class="up" id="up">
            <i class="fas fa-chevron-up"></i>
        </div>
        <p>&copy 2020 Darco Murja</p>
    </footer>

        <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>
        <script src="https://unpkg.com/aos@next/dist/aos.js"></script>
        <script src="main.js"></script>

    

    </body>
</html>
