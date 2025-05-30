<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Semester Subjects</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      text-align: center;
      background-color: #121212; /* dark tone background */
      color: white;
    }

    h1 {
      background: rgba(0, 0, 0, 0.8);
      padding: 20px;
      margin: 0;
      color: white;
      font-size: 2em;
    }

    .subject-list {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 20px;
      padding: 20px;
    }

    .subject {
      background: rgba(255, 255, 255, 0.05);
      border-radius: 12px;
      box-shadow: 0 4px 12px rgba(255, 255, 255, 0.1);
      padding: 20px;
      transition: transform 0.2s ease;
      color: white;
    }

    .subject:hover {
      transform: scale(1.05);
      background: rgba(255, 255, 255, 0.12);
      box-shadow: 0 6px 18px rgba(255, 255, 255, 0.3);
    }

    .subject h2 {
      background: linear-gradient(90deg, #ff9a9e, #fad0c4, #a18cd1);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
      font-weight: bold;
      font-size: 1.4em;
      margin: 0 0 10px 0;
    }

    a.button {
      display: inline-block;
      margin-top: 10px;
      padding: 10px 15px;
      background-color: #000;
      color: white;
      text-decoration: none;
      border-radius: 8px;
      font-weight: bold;
      box-shadow: 0 2px 5px rgba(255, 255, 255, 0.3);
      transition: background-color 0.3s ease;
    }

    a.button:hover {
      background-color: #222;
    }
  </style>
</head>
<body>
  <h1>📚 Semester Subjects</h1>
  <div class="subject-list">
    <div class="subject">
      <h2>🤖 Machine Learning</h2>
      <a class="button" href="https://drive.google.com/drive/folders/1oLUef5G8f99SUjiTD-3YOy2LDzirVhP8" target="_blank">📂 View Notes</a>
    </div>

    <div class="subject">
      <h2>📐 FDSA</h2>
      <a class="button" href="https://drive.google.com/drive/folders/1oLUef5G8f99SUjiTD-3YOy2LDzirVhP8" target="_blank">📂 View Notes</a>
    </div>

    <div class="subject">
      <h2>🌐 Computer Networks</h2>
      <a class="button" href="https://drive.google.com/drive/folders/1oT2Jb45a-aLcGSqm2HSz29s8CceGQbTN" target="_blank">📂 View Notes</a>
    </div>

    <div class="subject">
      <h2>🌱 EVS</h2>
      <a class="button" href="https://drive.google.com/drive/folders/1oWiKRiglHRq-xlh_V605W9gD-ooDCoSY" target="_blank">📂 View Notes</a>
    </div>

    <div class="subject">
      <h2>🖥️ Operating System</h2>
      <a class="button" href="https://drive.google.com/drive/folders/1oYbd0_RUF8-vCw27UJN_lWCkLeFwDFuj" target="_blank">📂 View Notes</a>
    </div>

    <div class="subject">
      <h2>📊 Probability and Statistics</h2>
      <a class="button" href="https://drive.google.com/drive/folders/1oYeHDHFzIjgWz8FCFWzCyhGiRlsOMxz0" target="_blank">📂 View Notes</a>
    </div>
  </div>
  <link rel="stylesheet" href="style.css" />
<script src="script.js"></script>

</body>
</html>
