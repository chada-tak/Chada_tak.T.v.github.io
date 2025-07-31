# Chada_tak.T.v.github.io
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>My Social Links</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      font-family: 'Arial', sans-serif;
      background: url('background.jpg') no-repeat center center fixed;
      background-size: cover;
      color: white;
    }

    .overlay {
      background-color: rgba(0, 0, 0, 0.6);
      min-height: 100vh;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      padding: 30px;
      text-align: center;
    }

    h1 {
      font-size: 2.5em;
      margin-bottom: 30px;
    }

    .card-container {
      display: flex;
      flex-direction: column;
      gap: 20px;
      width: 100%;
      max-width: 400px;
    }

    .card {
      display: flex;
      align-items: center;
      justify-content: flex-start;
      text-decoration: none;
      background-color: rgba(255, 255, 255, 0.1);
      padding: 15px 20px;
      border-radius: 12px;
      transition: background-color 0.3s;
    }

    .card:hover {
      background-color: rgba(255, 255, 255, 0.2);
    }

    .card img {
      width: 30px;
      height: 30px;
      margin-right: 15px;
    }

    .card span {
      font-size: 1.2em;
      color: white;
    }

    @media (max-width: 500px) {
      h1 {
        font-size: 2em;
      }
      .card span {
        font-size: 1em;
      }
    }
  </style>
</head>
<body>
  <div class="overlay">
    <h1>Connect with Me</h1>
    <div class="card-container">
      <a class="card" href="https://www.instagram.com/YOUR_USERNAME" target="_blank">
        <img src="https://img.icons8.com/ios-filled/50/ffffff/instagram-new.png" alt="Instagram"/>
        <span>Instagram</span>
      </a>
      <a class="card" href="https://www.facebook.com/YOUR_USERNAME" target="_blank">
        <img src="https://img.icons8.com/ios-filled/50/ffffff/facebook-new.png" alt="Facebook"/>
        <span>Facebook</span>
      </a>
      <a class="card" href="https://wa.me/YOUR_PHONE" target="_blank">
        <img src="https://img.icons8.com/ios-filled/50/ffffff/whatsapp.png" alt="WhatsApp"/>
        <span>WhatsApp</span>
      </a>
    </div>
  </div>
</body>
</html>
