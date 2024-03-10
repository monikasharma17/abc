<!DOCTYPE html>
<html>
<head>
  <title>Apology Link</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f4f4f4;
      text-align: center;
    }
    .container {
      max-width: 600px;
      margin: 0 auto;
      padding: 20px;
      background-color: #fff;
      border-radius: 8px;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    }
    h1 {
      color: #333;
    }
    p {
      color: #666;
      line-height: 1.6;
    }
    .apology-link {
      display: inline-block;
      padding: 10px 20px;
      background-color: #007bff;
      color: #fff;
      text-decoration: none;
      border-radius: 4px;
      transition: background-color 0.3s ease;
    }
    .apology-link:hover {
      background-color: #0056b3;
    }
  </style>
</head>
<body>

<div class="container">
  <h1>Apology Message</h1>
  <p>We regret the error and apologize for any inconvenience caused. Thank you for your understanding.</p>
  <a href="#" onclick="displayApology()" class="apology-link">Click here for apology</a>
</div>

<script>
  function displayApology() {
    var apologyDiv = document.getElementById('apologyMessage');
    apologyDiv.style.display = 'block';
  }
</script>

</body>
</html>

