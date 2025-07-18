<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>HTML with CSS and JavaScript</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f4f4f4;
      margin: 0;
      padding: 20px;
      text-align: center;
    }

    h1 {
      color: #333;
    }

    button {
      background-color: #007bff;
      color: white;
      padding: 12px 24px;
      font-size: 16px;
      border: none;
      border-radius: 8px;
      cursor: pointer;
      transition: background-color 0.3s ease;
    }

    button:hover {
      background-color: #0056b3;
    }
  </style>
</head>
<body>

  <h1>Welcome to My Web Page</h1>
  <p>Click the button below to see some JavaScript in action.</p>
  <button onclick="showMessage()">Click Me</button>

  <script>
    function showMessage() {
      alert("Hello! This is a message from JavaScript.");
    }
  </script>

</body>
</html>

