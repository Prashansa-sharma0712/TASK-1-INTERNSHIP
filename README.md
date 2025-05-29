<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>WEB DEVELOPMENT</title>
  <style>
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background-color: beige;
      color:black;
      margin: 0;
      padding: 20px;
      line-height: 1.5;
    }

    header {
      background-color: rgb(140, 140, 50);
      color: white;
      padding: 20px;
      text-align: center;
    }

    img {
      max-width: 50%;
      height: auto;
      border-radius: 3px;
    }

    .container {
      max-width: 800px;
      margin: auto;
      padding: 20px;
      background-color: white;
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }

    a {
      color: #4a90e2;
      text-decoration: none;
      font-weight: bold;
    }

    button {
      background-color: #4a90e2;
      color: white;
      border: none;
      padding: 10px 20px;
      margin-top: 20px;
      border-radius: 5px;
      cursor: pointer;
      font-size: 16px;
    }

    button:hover {
      background-color: #357abd;
    }
  </style>
</head>
<body>

  <header>
    <h1> WEB DEVELOPMENT</h1>
       Welcome to My Simple Web Page</h1>
  </header>

  <div class="container">
    <h2>About This Page</h2>
    <p>This is a basic example of a webpage created using HTML, styled with CSS, and made interactive using JavaScript.</p>

    <h2>Image Section</h2>
    <p>Here is a sample image to make this page more visually appealing:</p>
    <a href=https://shorturl.at/ihRYQ" target="_blank">
    <img src="https://shorturl.at/ihRYQ" alt="Web Development Image">
    </a>


    <h2>Visit a Useful Link</h2>
    <p>To learn more about web development, visit 
      <a href="https://www.geeksforgeeks.org">geeksforgeeks</a>.
    </p>

    <h2>Click the Button</h2>
    <p>Click below to see a message:</p>
    <button onclick="showAlert()">Click Me!</button>
  </div>

  <script>
    function showAlert() {
      alert("Hello! You're awesome! 🎉 Thanks for visiting this page.");
    }
  </script>

</body>
</html>
