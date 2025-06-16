<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Learn Coding</title>
  <style>
    html {
      scroll-behavior: smooth;
    }
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background: linear-gradient(to bottom right, #f3e8ff, #ffffff);
      color: #333;
    }
    header {
      background: #6200ea;
      color: white;
      padding: 20px;
      text-align: center;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
    }
    nav {
      background: #3700b3;
      padding: 10px;
      display: flex;
      justify-content: center;
      gap: 20px;
      position: sticky;
      top: 0;
      z-index: 1000;
    }
    nav a {
      color: white;
      text-decoration: none;
      font-weight: bold;
      transition: color 0.3s;
    }
    nav a:hover {
      text-decoration: underline;
      color: #dcd6f7;
    }
    main {
      max-width: 800px;
      margin: auto;
      padding: 20px;
    }
    section {
      background: white;
      padding: 20px;
      border-radius: 12px;
      box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
      margin-bottom: 40px;
    }
    h2 {
      color: #6200ea;
    }
    .button-box {
      margin-top: 10px;
    }
    button {
      margin-right: 10px;
      padding: 10px 20px;
      background: #6200ea;
      color: white;
      border: none;
      border-radius: 5px;
      cursor: pointer;
      transition: transform 0.3s ease, background-color 0.3s ease;
    }
    button:hover {
      background: #3700b3;
      transform: scale(1.05);
    }
    footer {
      text-align: center;
      background: #eee;
      padding: 10px;
      margin-top: 40px;
    }
    img {
      max-width: 100%;
      height: auto;
      display: block;
      margin: 20px auto;
      border-radius: 10px;
    }
  </style>
</head>
<body>

<header>
  <h1>Welcome to Learn Coding</h1>
  <p>Your simple guide to understanding the world of code</p>
</header>

<nav>
  <a href="#why">Why Learn?</a>
  <a href="#languages">Languages</a>
  <a href="#start">Getting Started</a>
</nav>

<main>
  <img src="code.try1.PNG" alt="test image">

  <section id="why">
    <h2>1. Why Learn Coding?</h2>
    <p>So first we should know why we want to learn coding. People say that when a person is interested in coding, they will be better than those who learn coding just for fame or money. This is because when a person is interested in something, they don't give up easily. However, if they were not interested, they might stop whenever they encounter an error.</p>
    <p>Coding helps us solve problems, automate tasks, and build apps and websites. It's like learning how to talk to computers. It can be fun, challenging, and rewarding. It teaches logical thinking and lets you create things out of pure imagination—like websites, games, and even robots!</p>
  </section>

  <section>
    <h2>2. What is Coding?</h2>
    <p>Coding, also known as programming, is the process of writing instructions that a computer can understand and execute. These instructions, written in various programming languages like Python, Java, or C++, tell the computer how to perform specific tasks. Essentially, coding is how we communicate with computers to create software, websites, apps, and more.</p>
  </section>

  <section id="languages">
    <h2>3. Choosing Your First Coding Language</h2>
    <p>There are various types of programming languages, including:</p>
    <ul>
      <li>C Sharp</li>
      <li>Rust</li>
      <li>Swift</li>
      <li>Ruby</li>
      <li>SQL</li>
      <li>Lua</li>
      <li>C++, Java, PHP, HTML, Python</li>
    </ul>
    <p>The most common ones are C++, Java, PHP, HTML, and Python.</p>
  </section>

  <section>
    <h2>4. Types of Coding Paradigms</h2>
    <ul>
      <li><strong>Procedural programming</strong>: Languages follow a sequence of statements or commands to achieve a desired output (e.g., C, C++, Java, Pascal).</li>
      <li><strong>Functional programming</strong>: Focuses on the output of mathematical functions. Each function performs a specific task and returns a result.</li>
      <li><strong>Object-oriented programming (OOP)</strong>: Treats a program as a group of reusable objects with data and methods. Useful for complex, scalable projects.</li>
      <li><strong>Scripting languages</strong>: Used to automate tasks or manage dynamic content in apps (e.g., JavaScript, Python).</li>
      <li><strong>Logic programming</strong>: Uses facts and rules to tell the computer how to make decisions (e.g., Prolog).</li>
    </ul>
  </section>

  <section id="start">
    <h2>5. Getting Started</h2>
    <p>To begin, watch tutorials and read books to understand the basics. Then:</p>
    <ol>
      <li>Come up with a simple project idea.</li>
      <li>Get the software or code editor you'll need (e.g., VS Code, IntelliJ).</li>
    </ol>
    <p>Hello there, this is our coding service. Was it helpful?</p>
    <div class="button-box">
      <button onclick="alert('Great! Let\'s go!')">Yes</button>
      <button onclick="alert('No worries, maybe later!')">No</button>
      <button onclick="window.location.href='https://www.w3schools.com/'">Learn More</button>
<p style="margin-top:10px; font-size: 0.95em;">You can also visit <a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript' target='_blank' style='color: #6200ea; font-weight: bold;'>MDN Web Docs</a> for advanced tutorials and documentation.</p>
    </div>
    </section>

  <section id="problem-form">
    <h2>6. Tell Us Your Coding Problem</h2>
    <p>If you're facing any issues while learning or coding, feel free to tell us below:</p>
    <form action="https://formspree.io/f/xwkgykyl" method="POST">
      <textarea name="message" $1></textarea><br><br>
      <input type="email" name="email" placeholder="Your email (optional)" style="width: 100%; padding: 10px; border-radius: 8px; border: 1px solid #ccc;"><br><br>
      <button type="submit">Submit</button>
    </form>
  </section>
</main>

<footer>
  <p>&copy; 2025 by Liora. All rights reserved.</p>
</footer>

</body>
</html>
