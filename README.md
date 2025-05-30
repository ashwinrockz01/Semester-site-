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
      background-color: #000000; /* full black background */
      color: white;
      text-align: center;
    }

    h1 {
      background: #111;
      padding: 20px;
      margin: 0;
      color: white;
      font-size: 2em;
      box-shadow: 0 4px 10px rgba(255, 255, 255, 0.05);
    }

    .subject-list {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 20px;
      padding: 20px;
    }

    .subject {
      background: #111111;
      border: 1px solid #333;
      border-radius: 12px;
      padding: 20px;
      transition: transform 0.2s ease, background 0.3s;
    }

    .subject:hover {
      transform: scale(1.05);
      background: #1a1a1a;
    }

    .subject h2 {
      background: linear-gradient(90deg, #ff9a9e, #fad0c4, #a18cd1);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
      font-weight: bold;
      font-size: 1.4em;
      margin-bottom: 12px;
    }

    a.button {
      display: inline-block;
      padding: 10px 15px;
      background-color: #000;
      color: white;
      text-decoration: none;
      border: 1px solid #fff;
      border-radius: 8px;
      font-weight: bold;
      transition: background 0.3s ease;
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
</body>
</html>
