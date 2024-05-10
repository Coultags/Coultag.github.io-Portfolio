<html>
    <!-- Head -->
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width"/>
        <title>Coulton Taggart</title>
        <link rel="stylesheet" type="text/css" href="Portfolio.css">
    </head>

    <!-- This is the body-->
    <body class="background">

        <!--Navbar Section-->
        <div class="Navbar">
            <a class="active" href="#Home">Home</a>
            <a href="#About">About</a>
            <a href="#GitHub">GitHub</a>
            <a href="#Contact">Contact</a>
        </div>

        <!--Added breaks to space the Navbar and heading one-->
        <br>
        <br>

        <!--Background Video Insert-->
        <div id="Home"
            <video autoplay muted loop id="game">
                <source src="/Images/Videos/game.mp4" type="video/mp4">
                <!--Display message if video does not run-->
                Your browser does not support HTML5 Video
            </video>
        </div>

        <!--Video text-->
        <div class="Video_Text">
            <h1 class="white-text">Coulton Taggart's Protfolio</h1>
            <b>
                <p class="center"></p>
                <q>The courge to walk into the Darkness, but strength to return to the light</q>
                <br>- Parables of the allspring
                <br>
                <br> My name is Coulton. Welcome to my portfolio website. I will share a bit of my background and my experiences.
                <br>
                <br>Thanks for reading and enjoy!
            </b>
        </div>    

        <!--This is the About Section-->
        <div class="Row" id="About">
            <!--L column-->
            <div class="Column_2">
                <img src="CSS/Images/Music.jpg" alt="Music Concert Picture">
            </div>
            <!--R column-->
            <div class="Column_1">
                <h1>About</h1>
                <p>I was raised in beautiful Alberta. In my free time I can been seen playing video games and listening to music.
                    <br>
                    <br> I am currently a student at <a href="https://www.academyoflearning.com/" target="_blank">Academy of Learning Career College'</a>s Software and Web Development course.
                    <br>
                    <br> I have currently worked with HTML, CSS, and Visual Studio Code. I look forward to learning so much more and developing my skills in coding and programming. 
                    I would love to help you with your future projects. <a herf="#Contact">Contact</a> me below!
                </p>
            </div>
        </div>

        <!--Github Link-->
        <div class="Row" id="GitHub">
            <!--Left Column-->
            <div class="Column_1">
                <h1>GitHub</h1>
                <p>
                    My projects can be viewed on my GitHub profile here:
                    <br>
                    <p class="center"><a herf="https://github.com/Coultags" target="_blank">Coultag's Github</a></p>
                </p>
            </div>
            <!--Right Column-->
            <div class="Column_2">
                <a href="https://github.com/Coultags" target="_blank"><img src="CSS/Images/Github.jpg" alt="GitHub Logo"></a>
            </div>
        </div>

        <!--Contact section-->
        <div class="Row" id="Contact">
            <!--Image for Contact in the left Column-->
            <div class="Column_2 Column_tall">
                <img src="CSS/Images/Contact.jpg" alt="Contact_Picture">
            </div>
            <!--Contact form in the Right Column-->
            <div class="Column_1 Column_tall">
                <h1>Contact</h1>
                <form action="" meathod="https://formspree.io/f/xbjnwela">
                    <label>Name:</label>
                        <input type="text" placeholder="Please enter your name here">
                    <label>Email:</label>
                        <input type="text" id="Email" name="Email" placeholder="Please enter your email here">
                    <label>Message:</label>
                        <input text="text" id="Message" name="Message" placeholder="Please enter your message here">
                        <input type="submit" value="SUBMIT">
                </form>
            </div>
        </div>

        <!--Footer Section-->
        <footer>
            <p>
                <p class="center">&copy Coultag's portfolio., <a herf="https://github.com/Coultags" target="_blank">Coultag's Github</a></p>
                <br>
            </p>
        </footer>
    </body>
</html>


/* General Settings */
/* Body */
body {
    margin: 0%  
}

h1 {
    text-transform: uppercase; 
    font-family: Verdana, Geneva, Tahoma, sans-serif;
    text-align: center; 
    margin-top: 3%; 
    color: #1a1a1a; 
}


h1:hover {
    filter: grayscale(5%); 
    transform: scale(1.1); 
    transition: transform 1s; 
}


.white-text {
    color: #fff; 
}


p {
    font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
    text-align: justify; 
    letter-spacing: 1px; 
    font-size: 19px;
    padding-left: 20px; 
    padding-right: 20px; 
}

/* Paragraph element hover effect */
p:hover {
    transition: transform 1s; 
	transform: scale(1.01); 
}


.center {
    text-align: center; 
}


.center:hover {
    transition: transform 2s; 
    transform: scale(1.1); 
}

/* Anchor elements */
a {
    color: blue; 
}

/* Quotation elements */
q {
    font-style: italic; 
}

/* Image elements */
img {
    filter: grayscale(75%);
    border-radius: 8px; 
    max-width: 100%; 
    height: 340px; 
    display: block; 
    margin-left: auto; 
    margin-right: auto;
}

/* Image element hover effects */
img:hover {
	filter: grayscale(5%);  
    transition: transform 1s; 
	transform: scale(1.1); 
}


@media screen and (max-width: 576px) {
    img {
        height: 100px;
        margin-top: 150px;
    }
}

/* Styling for footer element */
footer {
    padding: 2%; 
    background-color: white;
}
/* General Settings */

/**** Navbar Settings ****/
.Navbar {
    overflow: hidden; 
    background-color: black; 
    position: fixed; 
    top: 0; 
    width: 100%; 
    z-index: 1; 
    -webkit-animation: moveNav 5s; 
    animation: moveNav 5s; 
}

@keyframes moveNav {
    from {left: -100vw;} 
    to {left: 0vw;} 
}

/* Navbar links */
.Navbar a {
    float: left; 
    display: block; 
    color: white; 
    padding: 14px 16px; 
    text-decoration: none; 
    font-family:'Times New Roman', Times, serif; 
    font-size: 20px; 
    text-align: center; 
    position: relative; 
    -webkit-animation: moveNavText 5.75s; 
    animation: moveNavText 5.75s; 
}


@keyframes moveNavText {
    from {top: -100vw;} 
    to {top: 0vw;} 
}


@media screen and (max-width: 576px) {
    .Navbar a{
        width: 25%; 
        font-size: 12px;
    }
}

/* Hover effects */
.Navbar a:hover {
    background-color: red; 
    color: black; 
    font-weight: bold; 
}

/* Navbar home button */
.Navbar a.active { 
    background-color: darkgray;
}
/***** End of Navbar Settings *****/

/***** Video Settings *****/

#game {
    position: fixed; 
    right: 0; 
    bottom: 0; 
    min-width: 100%; 
    z-index: 1; 
}


@media screen and (max-width: 576px) {
    #game {
        display: none;
    }
}

/* Texts over the video */
.Video_Text {
    background: rgba(0, 0, 0, 0.5); 
    color: white; 
    width: 100%;
    padding: 20px; 
    position: relative; 
    -webkit-animation: moveVideoText 5.75s;
    animation: moveVideoText 5.75s;
}


@keyframes moveVideoText {
    from {top: -100vw;} 
    to {top: 0vw;} 
}
/***** End of Video Settings *****/

/***** Column and Rows sytling *****/
* { 
    box-sizing: border-box; 
} 

.Column_1 {
    float: left;
    width: 50%; 
    padding: 10px;
    padding-top: 3%; 
    height: 400px; 
    background-color: deepskyblue; 
}


@media screen and (max-width: 576px) {
    .Column_1 {
        overflow: auto;
    }
}

.Column_2 {
    float: left;
    width: 50%;
    padding: 10px;
    padding-top: 1.9%;
    height: 400px;
    background-color:teal
}


.Column_tall {
    padding-top: 3.5%;
    height: 450px;
}


.Row:after {
	content: ""; 
	display: table; 
	clear: both; 
}
/***** End of Columns and Rows *****/

/***** CONTACT FORM STYLING *****/

input[type=text] {
    width: 100%; 
    padding: 12px; 
    border: 1px solid #ccc; 
    border-radius: 4px; 
    box-sizing: border-box; 
    margin-top: 6px; 
    margin-bottom: 16px; 
    resize: vertical; 
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
}

input[type=text]:hover {
    box-shadow: 0 0 5px #00004d inset; 
}

input[type=submit] {
    background-color: black; 
    color: white; 
    font-weight: bold; 
    padding: 12px 20px;
    border: none; 
    border-radius: 4px; 
    cursor: pointer; 
    display: block; 
    margin-left: auto; 
    margin-right: auto;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
}

input[type=submit]:hover {
    background-color: white; 
    color: black; 
    transform: scale(1.5); 
    transition: transform 1.5s; 
}

form {
    border-radius: 5px; 
    background-color: #f2f2f2; 
    padding: 10px; 
    font-family: "Trebuchet MS", Optima;
}
/***** End of form and contact *****/
