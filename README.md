<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
   

 <title>Your Name - Personal Website</title>
    <link rel="stylesheet" href="Faizan.css">
</head>
<body>
    <header>
        <h1>Faizans Website</h1>
        <p>AP/ITEC4020 A - Internet Client-Server Systems</p>
    </header>
    <nav>
        <ul>
            <li><a href="#about">About Me</a></li>
            <li><a href="#education">Education</a></li>
            <li><a href="#experience">Experience</a></li>
            <li><a href="#awards">Awards</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>
    <section id="about">
             <style>
        .center-container {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh; 
        }

                .center-gif {
            max-width: 100%;
            max-height: 100%;
        }
    </style>
</head>
<body>
    <div class="center-container">
        <img class="center-gif" src="cat.gif" alt="Centered GIF">
    </div>
 <h2>About Me</h2>
        <p>Hi my names Faizan Shaikh,I was born in Toronto, Canada, and grew up in, and still live in Brampton. </p>
<br>
<p> My hobbies include
<ol>
  <li>Sports <img src="haikyuu.gif" alt="Example GIF"" width="150" height="150">
</li>
  <li>Watching anime <img src="dbz.gif" alt="Example GIF"" width="150" height="150">
</li>
  <li>Gaming <img src="game.gif" alt="Example GIF"" width="150" height="150">

</li>
</ol> 
</p>

       <div class="photo-container">
  <img src="myself.jpg" width="200" height="200"> 
        <button id="changePhoto">Change Photo</button>
<br>
  <a href="https://www.facebook.com/">
        <img src="facebook.jpg" " width="50" height="50"> 
    </a>
<a href="https://www.instagram.com/">
        <img src="instagram.jpg" " width="50" height="50"> 
    </a>
<a href="https://ca.linkedin.com/">
        <img src="Linkedin.jpg" " width="50" height="50"> 
    </a>

    </section>
    <section id="education">
        <h2>Education</h2>
        <strong>HighSchool </strong>
<a href="https://centralpeel.peelschools.org">Central Peel Secondary School</a>(2015-2019) <br>
<a href="https://centralpeel.peelschools.org/">
        <img src="highschool.jpg" " width="150" height="150"> 
    </a>

<br>
            <strong>Post-Secondary:</strong> <a href="https://www.yorku.ca/">York University</a>(2019-2023)
<br>
<a href="https://www.yorku.ca/">
        <img src="yorku.jpg" " width="150" height="150"> 
    </a>

        </p>
    </section>
    <section id="experience">
        <h2>Experience</h2>

        <p>
        <strong>Work:</strong> Fortinos (Part-Time, Since 2021))
<br>
<img src="picture7.jpg" width="150" height="150"> 
<br>
<br>
<strong>iFixit:</Strong> I participated in a project done for Ifix it where I fixed a vacuum and explained how 
<br>

<strong> <img src="picture1.jpg" width="100" height="100"> <img src="picture2.jpg" width="100" height="100"> <img src="picture3.jpg" width="100" height="100"> <img src="picture4.jpg" width="100" height="100"> <img src="picture5.jpg" width="100" height="100"> <img src="picture6.jpg" width="100" height="100"> <img src="picture8.jpg" width="100" height="100">
 </strong> 
        </p>
<br>
<a href="https://www.ifixit.com/Guide/Vacuum+Bissell+2610E+Brush+Roll+Replacement./147636">
        <img src="ifixit.jpg" " width="150" height="150"> 
    </a> <p> ^-- Click picture for link to the iFixit project </p>
<br>
<strong> My Website Project Wix: </strong> <a href="https://fshaikh18.wixsite.com/my-site">Faizans Wix Project </a>(For A course I did)

    </section>
    <section id="awards">
        <h2>Awards</h2>
        <p>
            <strong>Honoral Recipient:</strong> High School (All 4 Years)
        </p>
    </section>
    <section id="contact">
        <h2>Contact</h2>
            <h3>Contact Me:</h3> <p>Faizan12@my.yorku.ca</p> <br> <h3> Leave your Contact</h3>
    <form action="submit_form.php" method="post">
        <label for="name">Name:</label>
        <input type="text" id="name" name="name" required><br>

        <label for="email">Email:</label>
        <input type="email" id="email" name="email" required><br>

        <label for="message">Message:</label>
        <textarea id="message" name="message" rows="4" required></textarea><br>

        <input type="submit" value="Submit">
    </form>
    </section>
</body>
</html>
