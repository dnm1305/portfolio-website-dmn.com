# portfolio-website-dmn.com
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>DMN portfolio</title>
    <link rel="stylesheet" href="sytle.css">
    <script src="https://kit.fontawesome.com/b01dcd3cc3.js" crossorigin="anonymous"></script>
</head>
<body>
    <div id="header">
        <div class="container">
            <nav>
                <img src="mush.jpg" class="logo">
                <ul id="sidemenu">
                    <li><a href="#header">Home</a></li>
                    <li><a href="#about">About</a></li>
                    <li><a href="#services">Services</a></li>
                    <li><a href="#portfolio">Portfolio</a></li>
                    <li><a href="#contact">Contact</a></li>
                    <i class="fa-solid fa-x" onclick="closemenu()"></i>
                </ul>
                <i class="fa-solid fa-bars" onclick="openmenu()"></i>
            </nav>
            <div class="header-text">
                <p>Hello :></p>
                <h1>My name is<br><span>TJ Olaguera</span></h1>
            </div>
        </div>
    </div>
    <!-----About------->
    <div id="about">
        <div class="container">
            <div class="row">
                <div class="about-col-1">
                    <img src="her.jpg">
                </div>
                <div class="about-col-2">
                    <h1 class="sub-title">About me</h1>
                    <p>Hi, welcome to my Portfolio Website,<br>
                         my name DMN and I'm a Gaming video creator/streamer <br>
                         and I started after I quit my previous job (Customer Service Representative)<br>
                         currently I'm pursuing my career at the same the time in Virtual Assistant Industry<br>
                         Lets work and grow together!</p>

                         <div class="tab-titles">
                            <p class="tab-links  active-link" onclick="opentab('skills')">Skills</p>
                           <!---not working
                            <p class="tab-links" onclick="opentab('experience')">Experience</p>
                            <p class="tab-links" onclick="opentab('education')">Education</p> ---->
                         </div>
                         <div class="tab-contents active-tab" id="skills">
                            <ul>
                                <li><span>Google workspace</span><br>Google calendar/</li>
                                <li><span>Social Media Management</span><br>Content Creation</li>
                                <li><span>Email Management</span><br>Customer support</li>
                            </ul>
                         </div>
                         <div class="tab-contents" id="experience">
                            <ul>
                                <li><span>Donna Mae C. Nacion</span><br>I love you</li>
                                <li><span>Donna Mae C. Nacion</span><br>I love you</li>
                                <li><span>Donna Mae C. Nacion</span><br>I love you</li>
                            </ul>
                         </div>
                         <div class="tab-contents" id="education">
                            <ul>
                                <li><span>Donna Mae C. Nacion</span><br>I love you</li>
                                <li><span>Donna Mae C. Nacion</span><br>I love you</li>
                                <li><span>Donna Mae C. Nacion</span><br>I love you</li>
                            </ul>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <!---Services----->
    <div id="services">
        <div class="container">
            <h1 class="sub-title">My services</h1>
            <div class="services-list">
                <div>
                    <h2>Social Management</h2>
                    <p><i class="fa-brands fa-facebook"></i>
                        <i class="fa-brands fa-pinterest"></i>
                        <i class="fa-brands fa-youtube"></i>
                        <i class="fa-brands fa-instagram"></i>
                        <i class="fa-brands fa-tiktok"></i></p>
                    <a href="#">Learn more</a>
                </div>
                <div>
                    <h2>Email Management</h2>
                    <p><i class="fa-brands fa-google-drive"></i>
                        <i class="fa-sharp fa-solid fa-envelope-dot"></i>
                        <i class="fa-solid fa-tag"></i></p>
                    <a href="#">Learn more</a>
                </div>
                <div>
                    <h2>Email Marketing</h2>
                    <p><i class="fa-regular fa-envelope"></i>
                        <i class="fa-solid fa-hand-holding-dollar"></i></p>
                    <a href="#">Learn more</a>
                </div>
            </div>
        </div>
    </div>
    <!--------------portfolio--------------->
    <div id="port">
        <div class="container">
            <h1 class="sub-title">My page</h1>
            <div class="work-list">
                <div class="work">
                    <img src="page.png">
                    <div class="layer">
                        <h3>Here is my link</h3>
                        <p>This page is for Dota 2 play</p>
                        <a href="https://www.facebook.com/Metrodank"><i class="fa-solid fa-link"></i></a>
                    </div>
                </div>
                <div class="work">
                    <img src="page2.png">
                    <div class="layer">
                        <h3>Here is my link</h3>
                        <p>This page is for Valorant play</p>
                        <a href="https://www.facebook.com/Susssages"><i class="fa-solid fa-link"></i></a>
                    </div>
                </div>
                <div class="work">
                    <img src="3k.png">
                    <div class="layer">
                        <h3>Here is my link</h3>
                        <p>For my first 3k plus views on my clip</p>
                        <a href="https://business.facebook.com/latest/insights/content/?asset_id=117099317942369&video_id=165180886480131"><i class="fa-solid fa-link"></i></a>
                    </div>
                </div>
            </div>
            <a href="#" class="btn"> See more</a>
        </div>
    </div>
<!-------------Contact------------>
    <div id="contact">
        <div class="container">
            <div class="row">
                <div class="contact-left">
                   <h1 class="sub-title">Contact Me</h1> 
                   <p><i class="fa-regular fa-paper-plane"></i> emailme.@gmail.com</p>
                   <p><i class="fa-solid fa-phone"></i>012345678910</p>
                   <div class="social-icons">
                        <a href="https://facebook.com/"><i class="fa-brands fa-facebook"></i></a>
                        <a href=""><i class="fa-brands fa-instagram"></i></i></a>
                        <a href=""><i class="fa-brands fa-linkedin"></i></a>
                        <a href=""><i class="fa-brands fa-twitter"></i></a>
                   </div>
                   <a href="final resume2.docx" download class="btn btn2">Download CV</a>
                </div>
                <div class="contact-right">
                    <form action="">
                        <input type="text" name="Name" placeholder="Your name" required>
                        <input type=" email" name="Email" placeholder="Your email" required>
                        <textarea name="Message" rows="6" placeholder="Your message" required></textarea>
                        <button type="submit" class="btn btn2"> Submit</button>
                    </form>
                </div>
            </div>
        </div>
        <div class="copyright">
            <p>Copyright © TJ Olaguera <i class="fa-regular fa-heart"></i></p>
        </div>
    </div>




    <script>

        var tablinks = document.getElementsByClassName("tab-links");
        var tabcontents = document.getElementsByClassName("tab-contents");

        function opentab(tabname){
            for(tablink of tablinks){
                tablink.classList.remove("active-link");
            }
            for(tabcontent of tabcontents){
                tabcontent.classlist.remove("active-tab");
            }
            event.currentTarget.classList.add("active-link");
            document.getElementById(tabname).classList.add("active-tab");
        }
    </script>
    <script>

        var sidemenu = document.getElementById("sidemenu");
        function openmenu(){
            sidemenu.style.right = "0";
        }
        function closemenu(){
            sidemenu.style.right = "-200px";
        }
    </script>
</body>
</html>
