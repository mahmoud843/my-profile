<html lang="en">
     <meta. charset="UTF-8">
     <meta name="viewport" content="width=device-width, initial-scale=1.0">
     <title>my profile</title>
     <script src="script.js"></script>
        <style>
	/* Navigation Bar */
nav {
  background-color: blue;
  color: red;
  padding: 5px;
  text-align: center;
}
.logo {
  font-size: 40px;
  font-weight: bold;
  margin-right: 4px;

}
.nav-links {
  list-style-type: circle;
  margin: 10px;
  padding: 10px;
  text-align: center;
  margin-right: 4px;

}

.nav-links li {
  margin-right: 5px;
  display: inline ;
  text-align: center;
}

.nav-links li a {
  color: #131414;
  text-decoration: none;
  text-align: center;
}

/* Hero Section */
header {
  background-color: #f2f2f2;
  padding: 10px;
  text-align: center;
}

/* About Me Section */
#about {
  padding: 10px;
  text-align: center;
}

/* Skills Section */
#skills {
  padding: 10px;
  background-color: #f2f2f2;;
  text-align:center;
}

.skills-list {
  list-style-type: none;
  padding: 0;
}

.skills-list li {
  display: inline-block;
  margin: 0 10px;
}

/* Projects Section */
#projects {
  padding: 5px;
  text-align: center;
}

.project {
  margin-bottom: 20px;
}

.project a {
  display: block;
  margin-top: 10px;
}

/* Contact Section */
#contact {
  padding: 10px;
  text-align: center;
  background-color:  #f2f2f2;
}

#contact-form {
  display: flex;
  flex-direction: column;
  align-items: center;
  
}
#contact-form label {
  margin-bottom: 10px;
}

#contact-form input,
#contact-form textarea {
  width: 40%;
  padding: 10px;
  margin-bottom: 10px;
  box-sizing: border-box;
}

#contact-form button {
  background-color: #4b4747;
  padding: 10px 10px;
  cursor: pointer;
}

/* للتواصل معي section */
#للتواصل  {
  padding: 10px;
  text-align: left;
  background-color:  #182ace;
}

/* Footer */
footer {
  background-color: #8fb3f7;
  color: #0a0a0a;
  padding: 10px;
  text-align: left;
}

        </style>
    <nav>
        <div class="logo">mahmoud </div>
        <ul class="nav-links">
            <li><a href="#about">About</a></li>
            <li><a href="#skills">Skills</a></li>
            <li><a href="#projects">Projects</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>

    <header>
        <h1>Welcome my name is mahmoud</h1>
        <a href="https://imgur.com/A3tkwTF"><img src="https://i.imgur.com/A3tkwTF.jpg" title="source: imgur.com" width="50%"/></a>

        <p>some of my skills, projects, and achievements</p>
    </header>

    <section id="about">
        <h2><strong>About me</strong></h2>
        <div class="about-content">
            <p>I study commerce at Helwan University and I live in elMarg.</p>
        </div>
    </section>

    <section id="skills">
        <h2>Skills</h2>
        <ul class="skills-list">
            <ol>
                <li>HTML</li>
                <li>CSS</li>
                <li>JS</li>
            </ol>
        </ul>
    </section>

    <section id="projects">
        <h2>Projects</h2>
        <p>it is my first project</p>
        <div class="project">    
        </div>
    </section>

    <section id="contact">
        <h2>Contact with Me</h2>
        <form id="contact-form">
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>
            <label for="message">Message:</label>
            <textarea id="message" name="Name" required></textarea>
            <button type="submit">Send Message</button>
        </form>
          <section id="للتواصل معي"> 
            <h3>للتواصل معي</h3>
        <ul>
            <ol>
         <li><a href="https://www.facebook.com/profile.php?id=100024291725101&mibextid=ZbWKwL"> صفحتي علي فيسبوك</a></li>
         <li><a href="https://www.instagram.com/mahmoudmohamed_amer">اكونت الانستغرام</a></li>
           </ol>
        </ul>
    <footer>
        <p>&copy; 2023 mahmoud mohamed</p>
    </footer>
