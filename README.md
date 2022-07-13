# Mod2_Solution
Coursera Assignment
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@200;300;400;500;600;700;800;900&display=swap"
        rel="stylesheet" />
    <link href="stylesheet.css" rel="stylesheet">
    <title>First Website Challenge</title>
</head>

<body>
    <!--header-->
    <header class="header">
        <h1 class="header-logo">PIASTECH</h1>
        <div class="header-menu">
            <a href="#" class="header-menu_item">HOME</a>
            <a href="#about" class="header-menu_item">ABOUT</a>
            <a href="#contact" class="header-menu_item">CONTACT</a>
            <a href="#login" class="header-menu_item">LOGIN</a>
        </div>
    </header>
    <!--hero section -->
    <section class="hero">
        <div>
            <p class="hero-header">PIASTECH</p>
            <p class="hero-para">Welcome to My Tech World</p>
            <button onclick="myFunction()">Welcome</button>

            <p id="demo"></p>

            <script>
                function myFunction() {
                    var greeting;
                    var time = new Date().getHours();
                    if (time < 10) {
                        greeting = "Good morning";
                    } else if (time < 20) {
                        greeting = "Good day";
                    } else {
                        greeting = "Good evening";
                    }
                    document.getElementById("demo").innerHTML = greeting;
                }
            </script>
        </div>
    </section>
    <!-- services -->
    <section class="services">
        <h2 class="services-header">SERVICES</h2>
        <div class="services-item">
            <div class="services-item_content">
                DATA ANALYSIS<br />
                AND<br />
                MACHINE LEARNING
            </div>
            <div class="services-item_content">WEB DEVELOPMENT</div>
            <div class="services-item_content">
                BLOCKCHAIN<br />
                AND<br />
                CLOUD COMPUTING
            </div>
        </div>
    </section>
    <!-- about -->
    <section class="about">
        <h2 class="about-header">PIASTECH</h2>
        <div class="about-item">
            <img src="https://images.unsplash.com/photo-1531297484001-80022131f5a1?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxzZWFyY2h8Mnx8dGVjaHxlbnwwfHwwfHw%3D&auto=format&fit=crop&w=500&q=60"
                alt="macbook" />
            <p>
                In Piastech, our sole focus is to bring the latest technological
                trends to the teaming youths all over the world who are interested in
                getting into the tech eco system. In Piastech, our sole focus is to
                bring the latest technological trends to the teaming youths all over
                the world who are interested in getting into the tech eco system. In
                Piastech, our sole focus is to bring the latest technological trends
                to the teaming youths all over the world who are interested in getting
                into the tech eco system. In Piastech, our sole focus is to bring the
                latest technological trends to the teaming youths all over the world
                who are interested in getting into the tech eco system. In Piastech,
                our sole focus is to bring the latest technological trends to the
                teaming youths all over the world who are interested in getting into
                the tech eco system. In Piastech, our sole focus is to bring the
                latest technological trends to the teaming youths all over the world
                who are interested in getting into the tech eco system. In Piastech,
                our sole focus is to bring the latest technological trends to the
                teaming youths all over the world who are interested in getting into
                the tech eco system.
            </p>
        </div>
    </section>
    <!-- contact & login -->
    <section class="login-contact">
        <!-- contact form -->
        <form class="contact-form">
            <h2>CONTACT US</h2>
            <input type="text" class="contact-input" placeholder="Name" />
            <input type="email" class="contact-input" placeholder="Email" />
            <input type="number" class="contact-input" placeholder="Phone Number" />
            <input type="text" class="contact-input" placeholder="Subject" />
            <textarea name="message" id="message" rows="8" placeholder="Message"></textarea>
            <button type="submit">Send Message</button>
        </form>
        <!-- search & login -->
        <div class="search-login">
            <!-- search -->
            <div class="search-group">
                <input type="search" id="searchTerm" placeholder="Search" />
                <button type="submit" class="searchButton">Search</button>
            </div>
            <!-- login -->
            <form class="login-form">
                <h2 id="login">LOGIN</h2>
                <input type="text" class="login-input" placeholder="username/email" />
                <input type="password" class="login-input" placeholder="password" />
                <div>
                    <input type="checkbox" class="login-checkbox" placeholder="Remember me" /><span>Remeber Me</span>
                </div>
                <button type="submit">Log in</button>
            </form>
        </div>
    </section>

    <!--footer-->
    <footer class="footer">
        <p class="footer-copyright">&copy; HAREDROP 2022</p>
    </footer>
</body>

</html>
