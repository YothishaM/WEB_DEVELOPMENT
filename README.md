## code

```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Portfolio</title>
  <style>
    * {
        margin: 0;
        padding: 0;
        box-sizing: border-box;
        font-family: Arial, sans-serif;
        
    }
    
    body {
        line-height: 1.6;
        background-color: #f9f9f9;
        color: #333;
    }
    
    nav {
        background-color: #222;
        padding: 10px 0;
    }
    
    nav ul {
        list-style: none;
        display: flex;
        justify-content: center;
    }
    
    nav ul li {
        margin: 0 20px;
    }
    
    nav ul li a {
        color: #fff;
        text-decoration: none;
        font-weight: bold;
    }

    header {
        text-align: center;
        padding: 40px 20px;
        background-color: blue;
        color: white;
    }
    
    section {
        padding: 40px 20px;
        max-width: 800px;
        margin: 0 auto;
    }
    
    .project {
        background-color: #fff;
        color: black;
        padding: 15px;
        margin: 10px 0;
        border-left: 4px solid #333;
    }
    
    form {
        display: flex;
        flex-direction: column;
    }
    
    form input,
    form textarea {
        margin-bottom: 15px;
        padding: 10px;
        border: 1px solid #ccc;
        border-radius: 4px;
    }

    form button {
        width: 100px;
        padding: 10px;
        background-color: #333;
        color: #fff;
        border: none;
        border-radius: 4px;
        cursor: pointer;
    }
    
    form button:hover {
        background-color: #555;
    }

    .foot {
        background-color: blue;
        color: white;
        padding: 20px;
        text-align: center;
        margin-top: 20px;
    }
  </style>
</head>
<body>

  <nav>
    <ul>
      <li><a href="#home">Home</a></li>
      <li><a href="#about">About Me</a></li>
      <li><a href="#projects">Projects</a></li>
      <li><a href="#contact">Contact</a></li>
    </ul>
  </nav>

  <header id="home">
    <h1>Welcome to My Portfolio</h1>
    <p>I'm a passionate web developer. Here's my work!</p>
  </header>

  <section id="about">
    <h2>About Me</h2>
    <p>I'm a web developer with experience in HTML, CSS, JavaScript, and more. I build beautiful, functional websites.</p>
  </section>

  <div class="foot">
    <section id="projects">
      <h2>My Projects</h2>
      <div class="project">
        <h3>Project 1</h3>
        <p>A brief description of my first project.</p>
      </div>
      <div class="project">
        <h3>Project 2</h3>
        <p>A brief description of my second project.</p>
      </div>
    </section>

    <section id="contact">
      <h2>Contact Me</h2>
      <form>
        <input type="text" placeholder="Your Name" required>
        <input type="email" placeholder="Your Email" required>
        <textarea placeholder="Your Message" rows="5" required></textarea>
        <button type="submit">Submit</button>
      </form>
    </section>
  </div>

</body>
</html>
```
## Output
