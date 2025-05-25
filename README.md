<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Class 6 - AdnanKhanAligYT</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      margin: 0;
      padding: 0;
      background: url("images/ganita-prakash.jpg") no-repeat center center fixed;
      background-size: cover;
    }

    .overlay {
      background-color: rgba(255, 255, 255, 0.92);
      min-height: 100vh;
      padding: 30px 20px;
      display: flex;
      flex-direction: column;
      align-items: center;
    }

    .header {
      text-align: center;
      color: #d81b60;
      margin-bottom: 30px;
    }

    .header h1 {
      margin-bottom: 8px;
    }

    .buttons {
      display: flex;
      flex-direction: column;
      gap: 20px;
      width: 100%;
      max-width: 400px;
    }

    .buttons a {
      text-decoration: none;
      padding: 15px;
      border-radius: 30px;
      font-weight: bold;
      text-align: center;
      box-shadow: 2px 2px 10px rgba(0,0,0,0.1);
      transition: 0.3s ease;
    }

    .buttons a:hover {
      transform: scale(1.05);
    }

    .ncert { background-color: #fce4ec; color: #ad1457; }
    .notes { background-color: #f3e5f5; color: #6a1b9a; }
    .others { background-color: #e1f5fe; color: #0277bd; }

    footer {
      margin-top: auto;
      text-align: center;
      padding: 12px;
      color: #6d214f;
      background-color: #ffe4e1;
      border-top-left-radius: 30px;
      border-top-right-radius: 30px;
      width: 100%;
    }

    @media (min-width: 768px) {
      .buttons {
        flex-direction: row;
        justify-content: center;
      }
      .buttons a {
        flex: 1;
      }
    }
  </style>
</head>
<body>

  <div class="overlay">
    <div class="header">
      <h1>Class 6 Resources</h1>
      <p>Select your study material below</p>
    </div>

    <div class="buttons">
      <a href="ncert-book.html" class="ncert">NCERT Book</a>
      <a href="#" class="notes">Notes</a>
      <a href="#" class="others">Others</a>
    </div>

    <footer>
      © 2025 AdnanKhanAligYT | Class 6 Section
    </footer>
  </div>

</body>
</html>
