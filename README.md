# CodeAlpha_Project_portfolio
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Portfolio</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: grey;
    }
    header {
      background-color: black;
      color: #fff;
      padding: 1rem 0;
      text-align: center;
    }
    header h1 {
      margin: 0;
    }
    .container {
      width: 90%;
      margin: auto;
      overflow: hidden;
    }
    .profile, .projects, .skills, .contact {
      padding: 2rem 0;
    }
    .profile img {
      width: 150px;
      height: 150px;
      border-radius: 50%;
      display: block;
      margin: 0 auto;
    }
    h2 {
      text-align: center;
      color: black;
    }
    .projects, .skills {
      display: flex;
      flex-wrap: wrap;
      justify-content: space-around;
    }
    .projects .project, .skills .skill {
      background-color: #fff;
      padding: 1rem;
      margin: 1rem;
      border-radius: 5px;
      width: 30%;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    }
    .contact form {
      max-width: 600px;
      margin: 0 auto;
      padding: 1rem;
      background-color: #fff;
      border-radius: 5px;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    }
    .contact input, .contact textarea {
      width: 100%;
      padding: 0.5rem;
      margin: 0.5rem 0;
      border-radius: 3px;
      border: 1px solid #ccc;
    }
    .contact button {
      display: block;
      width: 100%;
      padding: 0.7rem;
      background-color: #333;
      color: #fff;
      border: none;
      border-radius: 3px;
      cursor: pointer;
    }
    footer {
      text-align: center;
      padding: 1rem 0;
      background-color: #333;
      color: #fff;
    }
  </style>
</head>
<body>



<header>
  <div class="container">
    <h1>Protfolio</h1>
  </div>
</header>

<div class="container">
  <!-- Profile Section -->
  <section class="profile">




    <img src= "C:\Users\ASUS\Downloads\WhatsApp Image 2024-10-11 at 1.23.36 AM.jpeg"   alt="Profile Picture">



    <h2>Nandhana Santhosh</h2>
    <p>Hello!
I'm a web developer with experience in building modern web applications.</p>
  <h3>About me</h3>
  I am a driven individual passionate about the tech-business sector, currently pursuing a bachelor's degree in computer application, mathematics, and statistics (triple majors). My solid organizing, negotiating, and communication skills, along with prior teamwork experience, make me an excellent team member and leader. Through various volunteering experiences, I have developed a compassionate and thoughtful approach to problem-solving.

I have excelled in debating global issues, showcasing a deep understanding of governance, diplomacy, business development, and strategy. My expertise in Technology, Business, and Entrepreneurship positions me as an ideal candidate for roles such as Product Management, Innovation, Research and Strategy.</p>
  </section>

  <!-- Projects Section -->
  <section class="projects">
    <h2>Projects</h2>
    <div class="project">
      <h3>Web page on Rajastan</h3>
      <p>Included:<br>major attractions <br> heritage sites<br> Historyof Pink city </p>
    </div>
    <div class="project">
      <h3>Stopwatch</h3>
      <p>Created a working model of stopwatch with start, stop and reset button</p>
    </div>
    <div class="project">
      <h3>Tic-Tac-Toe</h3>
      <p> Made a web pagr where we can play Tic-Tac-Toe.</p>
    </div>
  </section>

  <!-- Skills Section -->
  <section class="skills">
    <h2>Skills</h2>
    <div class="skill">
      <h3>HTML & CSS</h3>
    </div>
    <div class="skill">
      <h3>JavaScript</h3>
    </div>
    <div class="skill">
      <h3>React</h3>
    </div>

  <div class="skill">
      <h3>C</h3>
    </div>
  <div class="skill">
      <h3>C++</h3>
    </div>


  </section>

  <!-- Contact Section -->
  <section class="contact">
    <h2>Contact Me</h2>
    <form action="#">
      <input type="text" name="name" placeholder="Your Name" required>
      <input type="email" name="email" placeholder="Your Email" required>
      <textarea name="message" rows="5" placeholder="Your Message" required></textarea>
      <button type="submit">Send Message</button>
    </form>
  </section>
</div>

<footer>
  <p>&copy; 2023 Your Name. All rights reserved.</p>
</footer>

</body>
</html>
