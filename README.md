# apsara10.github.io
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8" />
        <meta name="viewport" content="width=device-width, initial-scale=1.0" />
        <meta http-equiv="X-UA-Compatible" content="ie=edge" />
        <meta name="keywords" content="Document" />
        <meta name="description" content="Your Description..." />
        <title>Document</title>
        <link
            rel="stylesheet"
            href="resources/swiper js/swiper-bundle.min.css"
        />
        <link
            rel="stylesheet"
            href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.2/css/all.min.css"
        />
        <link rel="stylesheet" href="resources/css/loader.css" />
        <link rel="stylesheet" href="resources/css/hamburger.css" />
        <link rel="stylesheet" href="resources/css/home.css" />
        <link rel="stylesheet" href="resources/css/about.css" />
        <link rel="stylesheet" href="resources/css/services.css">
        <link rel="stylesheet" href="resources/css/portfolio.css" />
        <link rel="stylesheet" href="resources/css/blog.css" />
        <link rel="stylesheet" href="resources/css/contact.css" />
        <link href="resources/mapbox-gl/mapbox-gl.css" rel="stylesheet" />
        <link rel="stylesheet" href="resources/css/style.css" />
        <link
            rel="shortcut icon"
            href="resources/img/favicon.ico"
            type="image/x-icon"
        />
    </head>
    <body onload="loaded()">
        <div class="loader">
            <div class="c c1"></div>
            <div class="c c2"></div>
            <div class="c c3"></div>
            <div class="c c4"></div>
            <div class="c c5"></div>
            <div class="c c6"></div>
        </div>
        <script>
            let loader = document.querySelector(".loader");
            function loaded() {
                loader.classList.add("remove");
                setTimeout(() => {
                    loader.style.display = "none";
                }, 1000);
            }
        </script>
        <!-- HAMBURGER MENU BUTTON (responsively visible) -->
        <div class="hamburger">
            <div class="bar1"></div>
            <div class="bar2"></div>
            <div class="bar3"></div>
        </div>

        <!-- THE REAL NAVIGATION -->
        <nav class="navigation">
            <h1>
                Shuvro
                <div></div>
                <div></div>
            </h1>
            <ul>
                <li><a href="#" onclick="home()">home</a></li>
                <li>
                    <a
                        href="#"
                        onclick="about(); animate3.play(); animate4.play();"
                        >about</a
                    >
                </li>
                <li><a href="#" onclick="services(); animate6.play();">services</a></li>
                <li><a href="#" onclick="portfolio()">portfolio</a></li>
                <li><a href="#" onclick="blog()">blog</a></li>
                <li>
                    <a href="#" onclick="contact(); animate5.play()">contact</a>
                </li>
            </ul>
            <p>&copy; 2021 Shuvro.</p>
        </nav>

        <div class="container">
            <div class="layer layer1 active">
                <div class="home main">
                    <div class="canvas_container">
                        <canvas></canvas>
                    </div>
                    <div class="content-for-home">
                        <div class="img-container"></div>
                        <h1 align="center">Shirshen Das Gupta Shuvro</h1>
                        <div class="social-icons">
                            <div class="s-icon">
                                <a href="#">
                                    <i class="fab fa-facebook"></i>
                                </a>
                                <div class="s-name">Facebook</div>
                            </div>
                            <div class="s-icon">
                                <a href="#">
                                    <i class="fab fa-twitter"></i>
                                </a>
                                <div class="s-name">Tweeter</div>
                            </div>
                            <div class="s-icon">
                                <a href="#">
                                    <i class="fab fa-github"></i>
                                </a>
                                <div class="s-name">GitHub</div>
                            </div>
                            <div class="s-icon">
                                <a href="#">
                                    <i class="fab fa-codepen"></i>
                                </a>
                                <div class="s-name">CodePen</div>
                            </div>
                            <div class="s-icon">
                                <a href="#">
                                    <i class="fab fa-instagram"></i>
                                </a>
                                <div class="s-name">Instagram</div>
                            </div>
                            <div class="s-icon">
                                <a href="#">
                                    <i class="fas fa-envelope"></i>
                                </a>
                                <div class="s-name">Email</div>
                            </div>
                        </div>

                        <div class="side-nav">
                            <button
                                onclick="about(); animate3.play(); animate4.play();"
                            >
                                <span class="w">W</span>
                                <span class="tooltip"> why you? </span>
                            </button>
                            <button onclick="services(); animate6.play();">
                                <span class="w">W</span>
                                <span class="tooltip"> what do you do? </span>
                            </button>
                            <button onclick="portfolio()">
                                <span class="w">W</span>
                                <span class="tooltip">
                                    what have you done?
                                </span>
                            </button>
                            <button onclick="blog()">
                                <span class="w">W</span>
                                <span class="tooltip"> what others say? </span>
                            </button>
                            <button onclick="contact(); animate5.play()">
                                <span class="w">W</span>
                                <span class="tooltip"> where are you? </span>
                            </button>
                        </div>

                        <div class="titles-for-side-nav">
                            <span></span>
                        </div>
                    </div>
                </div>
            </div>
            <div class="layer layer2">
                <div class="about main">
                    <!-- SEGMENT FOR STYLING. -->
                    <div class="styling">
                        <div class="absolute box"></div>
                        <div class="absolute circle"></div>
                        <div class="absolute triangle"></div>
                        <div class="absolute dots">
                            <div class="dot dot1"></div>
                            <div class="dot dot2"></div>
                            <div class="dot dot3"></div>
                            <div class="dot dot4"></div>
                            <div class="dot dot5"></div>
                            <div class="dot dot6"></div>
                            <div class="dot dot7"></div>
                            <div class="dot dot8"></div>
                            <div class="dot dot9"></div>
                            <div class="dot dot10"></div>
                            <div class="dot dot11"></div>
                            <div class="dot dot12"></div>
                            <div class="dot dot13"></div>
                            <div class="dot dot14"></div>
                            <div class="dot dot15"></div>
                            <div class="dot dot16"></div>
                            <div class="dot dot17"></div>
                            <div class="dot dot18"></div>
                            <div class="dot dot19"></div>
                            <div class="dot dot20"></div>
                            <div class="dot dot21"></div>
                            <div class="dot dot22"></div>
                            <div class="dot dot23"></div>
                            <div class="dot dot24"></div>
                        </div>

                        <svg
                            class="wave absolute"
                            xmlns="http://www.w3.org/2000/svg"
                            viewBox="0 0 1450 320"
                        >
                            <path
                                fill-opacity="1"
                                d="M0,320L48,277.3C96,235,192,149,288,122.7C384,96,480,128,576,165.3C672,203,768,245,864,234.7C960,224,1056,160,1152,112C1248,64,1344,32,1392,16L1440,0L1440,320L1392,320C1344,320,1248,320,1152,320C1056,320,960,320,864,320C768,320,672,320,576,320C480,320,384,320,288,320C192,320,96,320,48,320L0,320Z"
                            ></path>
                        </svg>

                        <svg
                            class="wave absolute opposite"
                            xmlns="http://www.w3.org/2000/svg"
                            viewBox="0 0 1450 320"
                        >
                            <path
                                fill-opacity="1"
                                d="M0,224L48,213.3C96,203,192,181,288,192C384,203,480,245,576,218.7C672,192,768,96,864,64C960,32,1056,64,1152,101.3C1248,139,1344,181,1392,202.7L1440,224L1440,320L1392,320C1344,320,1248,320,1152,320C1056,320,960,320,864,320C768,320,672,320,576,320C480,320,384,320,288,320C192,320,96,320,48,320L0,320Z"
                            ></path>
                        </svg>
                    </div>

                    <!-- REAL CONTENT -->
                    <div class="wrapper">
                        <div class="face face1">
                            <div class="content">
                                <p>Hello,</p>
                                <h1>I'm Shuvro</h1>
                                <p class="text">
                                    I am a Web Developer, and I'm very
                                    passionate and dedicated to my work With 10
                                    years experience as a professional Web
                                    Developer, I have acquired the skills and
                                    knowledge necessary to make your project a
                                    success I enjoy every step of the design
                                    process, from discussion and collaboration.
                                </p>
                                <a
                                    class="button download"
                                    href="resources/img/bg1.png"
                                    download="shuvro_cv"
                                    >Download CV</a
                                >
                                <a
                                    class="button hire"
                                    href="#"
                                    class="hire"
                                    onclick="contact(); animate5.play()"
                                    >Hire Me.</a
                                >
                            </div>
                        </div>
                        <div class="face face2"></div>
                    </div>

                    <!-- THE NAVIGATION OF ABOUT -->
                    <nav class="about_nav">
                        <ul>
                            <li>
                                <a class="active" href="#" data-text="one"
                                    >Skills</a
                                >
                            </li>
                            <li>
                                <a href="#" data-text="two">Experience</a>
                            </li>
                            <li>
                                <a href="#" data-text="three">Education</a>
                            </li>
                        </ul>
                    </nav>

                    <div class="about_container">
                        <!-- SKILL BOX -->
                        <div class="skills">
                            <div class="skill">
                                <div class="name">HTML5</div>
                                <div class="value" style="left: 90%">90%</div>
                                <div class="percent">
                                    <div
                                        class="progress"
                                        style="width: 90%"
                                    ></div>
                                </div>
                            </div>
                            <div class="skill">
                                <div class="name">CSS3</div>
                                <div class="value" style="left: 75%">75%</div>
                                <div class="percent">
                                    <div
                                        class="progress"
                                        style="width: 75%"
                                    ></div>
                                </div>
                            </div>
                            <div class="skill">
                                <div class="name">JavaScript</div>
                                <div class="value" style="left: 65%">65%</div>
                                <div class="percent">
                                    <div
                                        class="progress"
                                        style="width: 65%"
                                    ></div>
                                </div>
                            </div>
                            <div class="skill">
                                <div class="name">PHP</div>
                                <div class="value" style="left: 50%">50%</div>
                                <div class="percent">
                                    <div
                                        class="progress"
                                        style="width: 50%"
                                    ></div>
                                </div>
                            </div>
                            <div class="skill">
                                <div class="name">Jquery</div>
                                <div class="value" style="left: 45%">45%</div>
                                <div class="percent">
                                    <div
                                        class="progress"
                                        style="width: 45%"
                                    ></div>
                                </div>
                            </div>
                            <div class="skill">
                                <div class="name">C++</div>
                                <div class="value" style="left: 55%">55%</div>
                                <div class="percent">
                                    <div
                                        class="progress"
                                        style="width: 55%"
                                    ></div>
                                </div>
                            </div>
                        </div>

                        <!-- EXPERIENCE -->
                        <div class="experience">
                            <div class="middle_line"></div>
                            <div class="cover">
                                <i class="job_box fas fa-briefcase"></i>
                                <i class="date">Sep 2020 - Present</i>
                                <h2>Full Stack Developer</h2>
                                <i class="name_company">Company Name</i>
                                <article class="text_hidden">
                                    Lorem ipsum dolor sit amet consectetur
                                    adipisicing elit. Ut sint magnam ipsam
                                    eveniet omnis nemo commodi dolorum neque
                                    fugiat, soluta tempora vitae error magni.
                                    Lorem ipsum dolor sit amet consectetur
                                    adipisicing elit. Quaerat est amet
                                    voluptatibus, nam perferendis provident
                                    veritatis cum, dolorum eaque voluptates
                                    asperiores, nostrum voluptatum. Autem
                                    incidunt praesentium tempora, minus suscipit
                                    fugiat?
                                </article>
                            </div>
                            <div class="whitespace"></div>
                            <div class="whitespace"></div>
                            <div class="cover">
                                <i class="job_box fas fa-briefcase"></i>
                                <i class="date">Apr 2020 - Jan 2019</i>
                                <h2>Full Stack Developer</h2>
                                <i class="name_company">Company Name</i>
                                <article class="text_hidden">
                                    Lorem ipsum dolor sit amet consectetur
                                    adipisicing elit. Ut sint magnam ipsam
                                    eveniet omnis nemo commodi dolorum neque
                                    fugiat, soluta tempora vitae error magni.
                                </article>
                            </div>
                            <div class="cover">
                                <i class="job_box fas fa-briefcase"></i>
                                <i class="date">Feb 2018 - Apr 2020</i>
                                <h2>Full Stack Developer</h2>
                                <i class="name_company">Company Name</i>
                                <article class="text_hidden">
                                    Lorem ipsum dolor sit amet consectetur
                                    adipisicing elit. Ut sint magnam ipsam
                                    eveniet omnis nemo commodi dolorum neque
                                    fugiat, soluta tempora vitae error magni.
                                </article>
                            </div>
                            <div class="whitespace"></div>
                            <div class="whitespace"></div>
                            <div class="cover">
                                <i class="job_box fas fa-briefcase"></i>
                                <i class="date">Aug 2014 - Feb 2018</i>
                                <h2>Full Stack Developer</h2>
                                <i class="name_company">Company Name</i>
                                <article class="text_hidden">
                                    Lorem ipsum dolor sit amet consectetur
                                    adipisicing elit. Ut sint magnam ipsam
                                    eveniet omnis nemo commodi dolorum neque
                                    fugiat, soluta tempora vitae error magni.
                                </article>
                            </div>
                        </div>
                        <div class="education">
                            <div class="middle_line"></div>
                            <div class="cover">
                                <i class="job_box fas fa-book-reader"></i>
                                <i class="date">2019 - 2019</i>
                                <h2>Completed Graphics Designing</h2>
                                <i class="name_company">Google LLC.</i>
                                <article class="text_hidden">
                                    Lorem ipsum dolor sit amet consectetur
                                    adipisicing elit. Ut sint magnam ipsam
                                    eveniet omnis nemo commodi dolorum neque
                                    fugiat, soluta tempora vitae error magni.
                                </article>
                            </div>
                            <div class="whitespace"></div>
                            <div class="whitespace"></div>
                            <div class="cover">
                                <i class="job_box fas fa-book-reader"></i>
                                <i class="date">2018 - 2019</i>
                                <h2>Completed Web Designing Course</h2>
                                <i class="name_company">Wixframe Inc.</i>
                                <article class="text_hidden">
                                    Lorem ipsum dolor sit amet consectetur
                                    adipisicing elit. Ut sint magnam ipsam
                                    eveniet omnis nemo commodi dolorum neque
                                    fugiat, soluta tempora vitae error magni.
                                </article>
                            </div>
                            <div class="cover">
                                <i class="job_box fas fa-book-open"></i>
                                <i class="date">2016 - 2018</i>
                                <h2>Masters In Science</h2>
                                <i class="name_company">BUET, Bangladesh</i>
                                <article class="text_hidden">
                                    Lorem ipsum dolor sit amet consectetur
                                    adipisicing elit. Ut sint magnam ipsam
                                    eveniet omnis nemo commodi dolorum neque
                                    fugiat, soluta tempora vitae error magni.
                                </article>
                            </div>
                            <div class="whitespace"></div>
                            <div class="whitespace"></div>
                            <div class="cover">
                                <i class="job_box fas fa-book-open"></i>
                                <i class="date">2012 - 2016</i>
                                <h2>Bachelor In Science</h2>
                                <i class="name_company">BUET, Bangladesh.</i>
                                <article class="text_hidden">
                                    Lorem ipsum dolor sit amet consectetur
                                    adipisicing elit. Ut sint magnam ipsam
                                    eveniet omnis nemo commodi dolorum neque
                                    fugiat, soluta tempora vitae error magni.
                                </article>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            <div class="layer layer3">
                <div class="services main">
                    <!-- <section class="background">
                        <div class="bg_wrapper"></div>
                    </section> -->
                    <div class="hero">
                        <span class="typography">
                            <span class="t_dummy">We know how to</span> <br />
                            <span class="t-box">
                                <span class="box-side box-front"
                                    >take risk</span
                                >
                                <span class="box-side box-top"
                                    >take a side</span
                                >
                                <span class="box-side box-back"
                                    >be different</span
                                >
                                <span class="box-side box-bottom"
                                    >be innovative</span
                                >
                            </span>
                        </span>
                        <p class="hero-text">
                            Shuvro is an excellent web designer and faultless
                            technician. He’s a pleasure to work with, great
                            value for money and will always go the extra mile
                            when necessary.
                        </p>
                    </div>
                    <div class="capabilities left move-little-down">
                        <img src="resources/img/elements/web_bg.png" alt="" />
                        <p class="c_content">
                            <span class="c_title">Web</span>
                            His creative journey started with Web Design. To
                            code his own designs, he learned how to code and has
                            since then worked hard to stay relevant in both
                            fields. For smooth collaboration with clients he is
                            now-a-days using programing languages for designing
                            and prototyping.
                            <br />
                            <a href="#">Learn More</a>
                            <i class="far fa-arrow-alt-circle-right"></i>
                        </p>
                    </div>
                    <div class="capabilities right">
                        <p class="c_content">
                            <span class="c_title">Graphics</span>
                            With a designers eye for details, Shuvro is
                            passionate about implementing designed into highly
                            interactive experience by paying close attention to
                            details, animations and performances.
                            <br />
                            <a href="#">Learn More</a>
                            <i class="far fa-arrow-alt-circle-right"></i>
                        </p>
                        <img
                            src="resources/img/elements/graphics_bg.png"
                            alt=""
                        />
                    </div>
                    <div class="capabilities left">
                        <img
                            src="resources/img/elements/seo_bg.png"
                            alt=""
                            style="
                                background: #2929292f;
                                backdrop-filter: blur(4px);
                                border-radius: 40px;
                            "
                        />
                        <p class="c_content">
                            <span class="c_title">SEO</span>
                            With 1+ years of experience in the Digital industry,
                            he proved that the combination of strategic thinking
                            and expertise will create a fascinating digital
                            experience.
                            <br />
                            <a href="#">Learn More</a>
                            <i class="far fa-arrow-alt-circle-right"></i>
                        </p>
                    </div>
                    <div class="foot">
                        <h2>Works:</h2>
                        <div class="foot-link">
                            <a href="#" onclick="portfolio()">Profile World</a>
                            <i class="far fa-arrow-alt-circle-right"></i>
                            <img
                                src="resources/img/portfolios/app/2.jpg"
                                alt="portfolio"
                            />
                        </div>
                        <div class="foot-link">
                            <a href="#" onclick="portfolio()">Art Director</a>
                            <i class="far fa-arrow-alt-circle-right"></i>
                            <img
                                src="resources/img/portfolios/card/2.jpg"
                                alt="portfolio"
                            />
                        </div>
                        <div class="foot-link">
                            <a href="#" onclick="portfolio()">Lora Website</a>
                            <i class="far fa-arrow-alt-circle-right"></i>
                            <img
                                src="resources/img/portfolios/web/1.jpg"
                                alt="portfolio"
                            />
                        </div>
                    </div>
                </div>
            </div>
            <div class="layer layer4">
                <div class="portfolio main">
                    <div class="tip main">
                        <div class="allContent">
                            <div class="description" style="display: none">
                                <div class="pro_intro">
                                    <div class="nameplate">
                                        <h1>Wedding Couple</h1>
                                        <span
                                            >Category:
                                            <span style="color: #999"
                                                >Web Design</span
                                            ></span
                                        >
                                    </div>
                                    <div class="other_text">
                                        <h2>Project Brief:</h2>
                                        <p
                                            class="pro_brief"
                                            style="
                                                color: #999;
                                                padding-left: 15px;
                                            "
                                        >
                                            Lorem ipsum, dolor sit amet
                                            consectetur adipisicing elit. At
                                            corrupti modi perferendis iure
                                            corporis dolores minus asperiores
                                            nemo debitis veritatis id placeat,
                                            similique eum recusandae ipsa quia
                                            cum earum nam?
                                        </p>
                                    </div>
                                </div>
                                <div class="pro_info">
                                    <h2>Project Info</h2>
                                    <p class="Date">
                                        <b>Date: </b>
                                        <span style="color: #999">2020</span>
                                    </p>
                                    <p class="client">
                                        <b>Client: </b>
                                        <span style="color: #999">xyz</span>
                                    </p>
                                    <p>
                                        <b>Tools: </b>
                                        <span style="color: #999"
                                            >HTML, CSS, JavaScript</span
                                        >
                                    </p>
                                    <p class="link">
                                        <b>Web: </b>
                                        <span style="color: #999"
                                            ><a href="#"
                                                >www.domain.com</a
                                            ></span
                                        >
                                    </p>
                                </div>
                            </div>

                            <button class="closeButton">
                                <span>Project Details</span>
                                <div class="icon"></div>
                            </button>
                            <button class="exitButton">&times;</button>

                            <div class="port_content">
                                <div class="swiper-container-2">
                                    <div class="swiper-wrapper">
                                        <div class="swiper-slide">
                                            <img src="#" alt="web design" />
                                        </div>
                                        <div class="swiper-slide">
                                            <img src="#" alt="web design" />
                                        </div>
                                        <div class="swiper-slide">
                                            <img src="#" alt="web design" />
                                        </div>
                                        <div class="swiper-slide">
                                            <img src="#" alt="web design" />
                                        </div>
                                        <div class="swiper-slide">
                                            <img src="#" alt="web design" />
                                        </div>
                                        <div class="swiper-slide">
                                            <img src="#" alt="web design" />
                                        </div>
                                        <div class="swiper-slide">
                                            <img src="#" alt="web design" />
                                        </div>
                                        <div class="swiper-slide">
                                            <img src="#" alt="web design" />
                                        </div>
                                        <div class="swiper-slide">
                                            <img src="#" alt="web design" />
                                        </div>
                                    </div>
                                    <!-- Add Pagination -->
                                    <div class="swiper-scrollbar"></div>
                                    <!-- Add Arrows -->
                                    <div class="swiper-button-next"></div>
                                    <div class="swiper-button-prev"></div>
                                </div>
                            </div>
                        </div>
                    </div>
                    <nav class="about_nav padding_top">
                        <ul>
                            <li>
                                <a
                                    class="filter active"
                                    href="#"
                                    data-filter="all"
                                    >All</a
                                >
                            </li>
                            <li>
                                <a class="filter" href="#" data-filter=".web"
                                    >Web Design</a
                                >
                            </li>
                            <li>
                                <a class="filter" href="#" data-filter=".logo"
                                    >Logo</a
                                >
                            </li>
                            <li>
                                <a class="filter" href="#" data-filter=".card"
                                    >Cards</a
                                >
                            </li>
                            <li>
                                <a class="filter" href="#" data-filter=".app"
                                    >Apps</a
                                >
                            </li>
                            <li>
                                <a class="filter" href="#" data-filter=".icon"
                                    >Icons</a
                                >
                            </li>
                        </ul>
                    </nav>
                    <div class="mymixcont">
                        <div class="mix web">
                            <img
                                src="resources/img/portfolios/web/1.jpg"
                                alt=""
                            />
                            <span class="title">Lora Website</span>
                            <span class="port_link">View Project</span>
                        </div>
                        <div class="mix icon">
                            <img
                                src="resources/img/portfolios/icon/5.jpg"
                                alt=""
                            />
                            <span class="title">Water World</span>
                            <span class="port_link">View Project</span>
                        </div>
                        <div class="mix card">
                            <img
                                src="resources/img/portfolios/card/1.jpg"
                                alt=""
                            />
                            <span class="title">Brand Photography</span>
                            <span class="port_link">View Project</span>
                        </div>
                        <div class="mix web">
                            <img
                                src="resources/img/portfolios/web/2.jpg"
                                alt=""
                            />
                            <span class="title">Student Guide</span>
                            <span class="port_link">View Project</span>
                        </div>
                        <div class="mix app">
                            <img
                                src="resources/img/portfolios/app/1.jpg"
                                alt=""
                            />
                            <span class="title">World View</span>
                            <span class="port_link">View Project</span>
                        </div>
                        <div class="mix card">
                            <img
                                src="resources/img/portfolios/card/2.jpg"
                                alt=""
                            />
                            <span class="title">Art Director</span>
                            <span class="port_link">View Project</span>
                        </div>
                        <div class="mix web">
                            <img
                                src="resources/img/portfolios/web/3.jpg"
                                alt=""
                            />
                            <span class="title">Web App Pro</span>
                            <span class="port_link">View Project</span>
                        </div>
                        <div class="mix card">
                            <img
                                src="resources/img/portfolios/card/3.jpg"
                                alt=""
                            />
                            <span class="title">Reauty</span>
                            <span class="port_link">View Project</span>
                        </div>
                        <div class="mix web">
                            <img
                                src="resources/img/portfolios/web/4.jpg"
                                alt=""
                            />
                            <span class="title">Sonor Design</span>
                            <span class="port_link">View Project</span>
                        </div>
                        <div class="mix card">
                            <img
                                src="resources/img/portfolios/card/4.jpg"
                                alt=""
                            />
                            <span class="title">Richard Tan</span>
                            <span class="port_link">View Project</span>
                        </div>
                        <div class="mix logo">
                            <img
                                src="resources/img/portfolios/logo/1.jpg"
                                alt=""
                            />
                            <span class="title">Kitty Pic</span>
                            <span class="port_link">View Project</span>
                        </div>
                        <div class="mix icon">
                            <img
                                src="resources/img/portfolios/icon/4.jpg"
                                alt=""
                            />
                            <span class="title">Domine</span>
                            <span class="port_link">View Project</span>
                        </div>
                        <div class="mix app">
                            <img
                                src="resources/img/portfolios/app/2.jpg"
                                alt=""
                            />
                            <span class="title">Profile World</span>
                            <span class="port_link">View Project</span>
                        </div>
                        <div class="mix logo">
                            <img
                                src="resources/img/portfolios/logo/2.jpg"
                                alt=""
                            />
                            <span class="title">Specialisterne</span>
                            <span class="port_link">View Project</span>
                        </div>
                        <div class="mix logo">
                            <img
                                src="resources/img/portfolios/logo/3.jpg"
                                alt=""
                            />
                            <span class="title">Native Design</span>
                            <span class="port_link">View Project</span>
                        </div>
                        <div class="mix card">
                            <img
                                src="resources/img/portfolios/card/5.jpg"
                                alt=""
                            />
                            <span class="title">Sriram Mohan</span>
                            <span class="port_link">View Project</span>
                        </div>
                        <div class="mix logo">
                            <img
                                src="resources/img/portfolios/logo/4.jpg"
                                alt=""
                            />
                            <span class="title">Book Worm</span>
                            <span class="port_link">View Project</span>
                        </div>
                        <div class="mix icon">
                            <img
                                src="resources/img/portfolios/icon/2.jpg"
                                alt=""
                            />
                            <span class="title">Football FC</span>
                            <span class="port_link">View Project</span>
                        </div>
                        <div class="mix logo">
                            <img
                                src="resources/img/portfolios/logo/5.jpg"
                                alt=""
                            />
                            <span class="title">Free Notes</span>
                            <span class="port_link">View Project</span>
                        </div>
                        <div class="mix icon">
                            <img
                                src="resources/img/portfolios/icon/1.jpg"
                                alt=""
                            />
                            <span class="title">Insta Genre</span>
                            <span class="port_link">View Project</span>
                        </div>
                        <div class="mix logo">
                            <img
                                src="resources/img/portfolios/logo/6.jpg"
                                alt=""
                            />
                            <span class="title">Movie Sock</span>
                            <span class="port_link">View Project</span>
                        </div>
                        <div class="mix logo">
                            <img
                                src="resources/img/portfolios/logo/7.jpg"
                                alt=""
                            />
                            <span class="title">Village Community Church</span>
                            <span class="port_link">View Project</span>
                        </div>
                        <div class="mix app">
                            <img
                                src="resources/img/portfolios/app/3.jpg"
                                alt=""
                            />
                            <span class="title">Weathery</span>
                            <span class="port_link">View Project</span>
                        </div>
                        <div class="mix icon">
                            <img
                                src="resources/img/portfolios/icon/3.jpg"
                                alt=""
                            />
                            <span class="title">Fav Shop</span>
                            <span class="port_link">View Project</span>
                        </div>
                    </div>
                </div>
            </div>
            <div class="layer layer5">
                <div class="testimonial">
                    <h1>
                        <span>See What My Clients Say about Me.</span>
                    </h1>
                    <div class="swiper-container">
                        <div class="swiper-wrapper">
                            <div class="swiper-slide">
                                <img src="resources/img/favicon.ico" alt="" />
                                <h4>Erik Lasher</h4>
                                <div class="rating">
                                    <label>&starf;</label>
                                    <label>&starf;</label>
                                    <label>&starf;</label>
                                    <label>&starf;</label>
                                    <label>&starf;</label>
                                </div>
                                <p>
                                    <span>&ldquo;</span>
                                    Shuvro is an excellent web designer and
                                    faultless technician. He’s a pleasure to
                                    work with, great value for money and will
                                    always go the extra mile when necessary.
                                </p>
                            </div>
                            <div class="swiper-slide">
                                <img src="resources/img/favicon.ico" alt="" />
                                <h4>Erik Lasher</h4>
                                <div class="rating">
                                    <label>&starf;</label>
                                    <label>&starf;</label>
                                    <label>&starf;</label>
                                    <label>&starf;</label>
                                    <label>&starf;</label>
                                </div>
                                <p>
                                    <span>&ldquo;</span>
                                    Shuvro is an excellent web designer and
                                    faultless technician. He’s a pleasure to
                                    work with, great value for money and will
                                    always go the extra mile when necessary.
                                </p>
                            </div>
                            <div class="swiper-slide">
                                <img src="resources/img/favicon.ico" alt="" />
                                <h4>Erik Lasher</h4>
                                <div class="rating">
                                    <label>&starf;</label>
                                    <label>&starf;</label>
                                    <label>&starf;</label>
                                    <label>&starf;</label>
                                    <label>&starf;</label>
                                </div>
                                <p>
                                    <span>&ldquo;</span>
                                    Shuvro is an excellent web designer and
                                    faultless technician. He’s a pleasure to
                                    work with, great value for money and will
                                    always go the extra mile when necessary.
                                </p>
                            </div>
                            <div class="swiper-slide">
                                <img src="resources/img/favicon.ico" alt="" />
                                <h4>Erik Lasher</h4>
                                <div class="rating">
                                    <label>&starf;</label>
                                    <label>&starf;</label>
                                    <label>&starf;</label>
                                    <label>&starf;</label>
                                    <label>&starf;</label>
                                </div>
                                <p>
                                    <span>&ldquo;</span>
                                    Shuvro is an excellent web designer and
                                    faultless technician. He’s a pleasure to
                                    work with, great value for money and will
                                    always go the extra mile when necessary.
                                </p>
                            </div>
                            <div class="swiper-slide">
                                <img src="resources/img/favicon.ico" alt="" />
                                <h4>Erik Lasher</h4>
                                <div class="rating">
                                    <label>&starf;</label>
                                    <label>&starf;</label>
                                    <label>&starf;</label>
                                    <label>&starf;</label>
                                    <label>&starf;</label>
                                </div>
                                <p>
                                    <span>&ldquo;</span>
                                    Shuvro is an excellent web designer and
                                    faultless technician. He’s a pleasure to
                                    work with, great value for money and will
                                    always go the extra mile when necessary.
                                </p>
                            </div>
                            <div class="swiper-slide">
                                <img src="resources/img/favicon.ico" alt="" />
                                <h4>Erik Lasher</h4>
                                <div class="rating">
                                    <label>&starf;</label>
                                    <label>&starf;</label>
                                    <label>&starf;</label>
                                    <label>&starf;</label>
                                    <label>&starf;</label>
                                </div>
                                <p>
                                    <span>&ldquo;</span>
                                    Shuvro is an excellent web designer and
                                    faultless technician. He’s a pleasure to
                                    work with, great value for money and will
                                    always go the extra mile when necessary.
                                </p>
                            </div>
                        </div>
                        <!-- Add Pagination -->
                        <div class="swiper-pagination"></div>
                        <div class="swiper-button-next"></div>
                        <div class="swiper-button-prev"></div>
                    </div>
                </div>
            </div>
            <div class="layer layer6">
                <div class="contact_us">
                    <div id="map"></div>
                    <address class="info_container">
                        <div class="info info1">
                            <i class="fas fa-phone-alt"></i>
                            <span class="iname">Phone</span>
                            <a href="tel:+8800000000000">+8800000000000</a>
                            <a href="tel:+8811111111111">+8811111111111</a>
                        </div>
                        <div class="info info2">
                            <i class="fas fa-home"></i>
                            <span class="iname">Address</span>
                            <a
                                href="https://www.google.com/maps/place/Sherpur+Town+Hall/@25.0136644,90.0140045,355m/data=!3m1!1e3!4m5!3m4!1s0x3757d6136d793499:0x8c22620664dc6a37!8m2!3d25.0156371!4d90.0168872"
                            >
                                <h3>Govt. Girls' School Road</h3>
                                <span>Kharampur, Sherpur</span><br />
                                <span>Bangladesh</span>
                            </a>
                        </div>
                        <div class="info info3">
                            <i class="fas fa-envelope"></i>
                            <span class="iname">Email</span>
                            <a href="mailto:email1.gmail.com"
                                >shuvro1@gmail.com</a
                            >
                            <a href="mailto:email2.gmail.com"
                                >shuvro2@gmail.com</a
                            >
                        </div>
                    </address>

                    <form action="#" method="post">
                        <h1>Get In Touch</h1>
                        <div class="inp_field">
                            <i class="fas fa-user"></i>
                            <input
                                type="text"
                                name="name"
                                class="fname"
                                id="fname"
                                placeholder="Full Name"
                                required
                            />
                        </div>
                        <div class="inp_field">
                            <i class="fas fa-envelope"></i>
                            <input
                                type="email"
                                name="email"
                                class="email"
                                id="email"
                                placeholder="Email"
                                required
                            />
                        </div>
                        <div class="inp_field">
                            <i class="fas fa-angle-double-right"></i>
                            <input
                                type="text"
                                name="subject"
                                class="subject"
                                id="subject"
                                placeholder="Subject"
                                required
                            />
                        </div>
                        <textarea
                            name="message"
                            cols="30"
                            rows="5"
                            class="message"
                            id="message"
                            placeholder="Message"
                            required
                        ></textarea>
                        <button class="submit" id="submit">Submit</button>
                    </form>
                </div>
            </div>
        </div>

        <!-----------------JQUERY {https://jquery.com/} [USED IN portfolio.js]----------------->
        <script src="resources/js/jquery.min.js"></script>
        <!-----------------MIX IT UP {https://www.kunkalabs.com/mixitup/} [USED IN portfolio.js]----------------->
        <script src="resources/js/mixitup.min.js"></script>
        <!-----------------SWIPER JS {https://swiperjs.com/} [USED IN portfolio.js, blog.js]----------------->
        <script src="resources/swiper js/swiper-bundle.min.js"></script>
        <!-----------------MAPBOX GL {https://www.mapbox.com/} [USED IN contact.js]----------------->
        <script src="resources/mapbox-gl/mapbox-gl.js"></script>
        <!-----------------EMAIL JS {https://www.emailjs.com/} [USED IN contact.js]----------------->
        <script src="resources/js/email.min.js"></script>
        <!-----------------ADDITIONAL SCRIPT FOR EMAIL JS----------------->
        <script type="text/javascript">
            (function () {
                emailjs.init("user_5OMETIDQ2Nm9qBMtaFNz4");
            })();
        </script>
        <!-----------------VANILLA TILT JS {https://micku7zu.github.io/vanilla-tilt.js/}----------------->
        <script src="resources/js/vanilla-tilt.min.js"></script>
        <!-----------------ANIME JS {https://animejs.com/} [USED LOCALLY.]----------------->
        <script src="resources/js/anime.min.js"></script>
        <!-----------------LOCAL (HOME)----------------->
        <script src="resources/js/home.js"></script>
        <!-----------------LOCAL (ABOUT)----------------->
        <script src="resources/js/about.js"></script>
        <!-----------------LOCAL (SERVICES)----------------->
        <script src="resources/js/services.js"></script>
        <!-----------------LOCAL (PORTFOLIO)----------------->
        <script src="resources/js/portfolio.js"></script>
        <!-----------------LOCAL (BLOG)----------------->
        <script src="resources/js/blog.js"></script>
        <!-----------------LOCAL (CONTACT)----------------->
        <script src="resources/js/contact.js"></script>
        <!-----------------LOCAL (MAIN FILE)----------------->
        <script src="resources/js/main.js"></script>

        <!-----------------LOCAL (MAIN FILE { USED TO ANIMATE WEBPAGE.})----------------->
        <script>
            const animate1 = anime.timeline({
                targets: ".circle",
                loop: true,
                duration: 2000,
                direction: "alternate",
                easing: "easeInOutQuad",
            });
            animate1.add({
                translateX: 350,
            });

            let dot = document.querySelectorAll(".dot");
            for (let i = 0; i < dot.length; i++) {
                const ind = dot[i];
                const animate2 = anime.timeline({
                    targets: ind,
                    loop: true,
                    direction: "alternate",
                    delay: i * 100,
                });
                animate2.add({
                    scale: 2,
                });
            }

            let span = document.querySelectorAll(".content .text span");
            const animate3 = anime.timeline({
                targets: span,
                easing: "easeInOutExpo",
                delay: anime.stagger(20, { direction: "reverse" }),
                direction: "reverse",
                autoplay: false,
            });

            animate3.add({
                rotate: () => {
                    return anime.random(-360, 360);
                },
                translateX: () => {
                    return anime.random(-500, 500);
                },
                translateY: () => {
                    return anime.random(-500, 500);
                },
                duration: 3000,
            });

            const animate4 = anime({
                targets: ".button",
                scale: [0, 1],
                delay: anime.stagger(200, { start: 7000 }),
                autoplay: false,
            });

            const animate5 = anime({
                targets: [
                    document.querySelectorAll(".info"),
                    document.querySelectorAll(".inp_field"),
                    ".message",
                    ".submit",
                ],
                translateY: [50, 0],
                rotateX: [90, 0],
                opacity: [0, 1],
                delay: anime.stagger(300, { start: 1000 }),
                duration: 750,
                autoplay: false,
                easing: "easeOutQuint",
            });
            
            const animate6 = anime({
                targets: ['.services .t_dummy', '.services .hero-text'],
                duration: 1000,
                scaleX: [0, 1],
                delay: anime.stagger(300, {start: 1000}),
                autoplay: false,
            });

            function resize() {
                if (window.innerWidth <= 632) {
                    animate5.play();
                    animate3.play();
                    animate4.play();
                    animate6.play();
                }
            }
            resize();
            window.addEventListener("resize", resize);
        </script>
    </body>
</html>
