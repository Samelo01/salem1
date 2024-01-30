<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Restaurant List</title>

  <!-- Add your CSS styling if needed -->
  <style>
    body {
      font-family: 'Arial', sans-serif;
      text-align: center;
      margin: 20px;
    }
  </style>
</head>
<body>

  <h1>Welcome to Our Restaurant List</h1>
  <p>Scan the QR code below to access the list of restaurants:</p>

  <!-- Replace 'YOUR_RESTAURANT_LIST_URL' with the actual URL of your restaurant list -->
  <a href="YOUR_RESTAURANT_LIST_URL" target="_blank">
    <img src="https://api.qrserver.com/v1/create-qr-code/?data=YOUR_RESTAURANT_LIST_URL&amp;size=150x150" alt="QR Code">
  </a>

  <p>Click on the QR code to view the restaurant list.</p>

  <!-- Additional content or information can be added here -->

</body>
</html>
