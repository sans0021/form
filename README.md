<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Contact Form</title>
  <link rel="shortcut icon" href="circle.png">
  <body>
      <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    }

    body {
      height: 100vh;
      background:linear-gradient(rgba(255, 0, 0, 0.616),rgb(209, 20, 251)) ;
      display: block;
      align-items: center;
      justify-content: center;
      backdrop-filter: blur(5px);
    }

    .glass-form {
      background: rgba(255, 242, 0, 0.463);
      border-radius: 10px;
      padding: 30px;
      width: 100%;
      max-width: 400px;
      box-shadow: 0 8px 32px rgba(0, 0, 0, 0.332);
      backdrop-filter: blur(15px);
      border: 5px solid rgba(255, 255, 255, 0.2);
      color: #ffffff;
    }

    .glass-form h2 {
      margin-bottom: 20px;
      text-align: center;
    }

    .glass-form input,
    .glass-form textarea {
      width: 100%;
      margin-bottom: 15px;
      padding: 10px 15px;
      border: none;
      border-radius: 10px;
      background: rgba(255, 255, 255, 0.2);
      color: #ffffff;
      resize: none;
    }

    .glass-form input::placeholder,
    .glass-form textarea::placeholder {
      color: #000000;
    }

    .glass-form button {
      width: 100%;
      padding: 12px;
      border: none;
      border-radius: 10px;
      background: rgba(255, 255, 255, 0.3);
      color: #000000;
      font-size: 16px;
      cursor: pointer;
      transition: background 0.4s ease;
    }

    .glass-form button:hover {
      background: rgba(255, 255, 255, 0.667);
    }
  </style>
</head>
<body>
    <img src="call.png" alt="" style="width: 150px;">

  <form action="https://formsubmit.co/pandeysanskar211@gmail.com" method="POST"  class="glass-form">
    <h2>Contact Us</h2>
    <input type="text" name="name" placeholder="Your Name" required />
    <input type="contact" name="contact" placeholder="Your contact number" required />
    <textarea name="message" rows="5" placeholder="Your Message / plans" required></textarea>
    <button type="submit">Send Message</button>
  </form>

</body>
</html>
