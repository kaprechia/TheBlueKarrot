<!DOCTYPE<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>The Blue Karrot</title>
  <style>
    body {
      font-family: 'Helvetica Neue', sans-serif;
      background: #f9f9f9;
      color: #1a1a1a;
      margin: 0;
      padding: 0 20px;
    }
    header {
      text-align: center;
      padding: 40px 0 20px;
      background-color: #002855; /* Deep Blue */
      color: #d4af37; /* Gold */
    }
    header img {
      max-width: 120px;
      margin-bottom: 15px;
    }
    header h1 {
      margin: 0;
      font-size: 3em;
      font-weight: 700;
      letter-spacing: 1.5px;
    }
    header h2 {
      margin: 5px 0 0;
      font-size: 1.3em;
      font-weight: 400;
      color: #fff;
      opacity: 0.8;
    }
    main {
      max-width: 600px;
      margin: 40px auto;
      background: gold;
      padding: 30px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
      border-radius: 8px;
    }
    h3 {
      color: #002855;
      margin-bottom: 20px;
      text-align: center;
    }
    form label {
      display: round;
      margin-bottom: 6px;
      font-weight: 600;
      color: #333;
    }
    form input[type="text"],
    form input[type="email"],
    form input[type="tel"],
    form input[type="date"],
    form textarea {
      width: 100%;
      padding: 8px 10px;
      margin-bottom: 18px;
      border: 1.5px solid #ccc;
      border-radius: 4px;
      font-size: 1em;
      resize: vertical;
    }
    form input[type="submit"] {
      background-color: #d4af37; /* Gold */
      border: none;
      padding: 12px 25px;
      font-size: 1.1em;
      color: #002855;
      font-weight: bold;
      cursor: pointer;
      border-radius: 5px;
      transition: background-color 0.3s ease;
      display: block;
      margin: 0 auto;
    }
    form input[type="submit"]:hover {
      background-color: #b38f13;
    }
    footer {
      text-align: center;
      padding: 20px 10px;
      font-size: 0.9em;
      color: #666;
    }
  </style>
</head>
<body>

<header>
![Uploading image.png…]()

  <img src="logo.png" alt="The Blue Karrot Logo" />
  <h1>The Blue Karrot</h1>
  <h2>Catering</h2>
</header>

<main>
  <h3>Contact Us</h3>
  <form action="mailto:bluecarrotcatering@gmail.com" method="POST" enctype="text/plain">
    <label for="name">Full Name:</label>
    <input type="text" id="name" name="name" required />

    <label for="email">Email Address:</label>
    <input type="email" id="email" name="email" required />

    <label for="phone">Phone Number:</label>
    <input type="tel" id="phone" name="phone" />

    <label for="event">Event Date:</label>
    <input type="date" id="event" name="event" />

    <label for="message">Tell us about your event:</label>
    <textarea id="message" name="message" rows="5" placeholder="Type your message here..."></textarea>

    <input type="submit" value="Send Inquiry" />
  </form>
</main>

<footer>
  &copy; 2025 The Blue Karrot | All Rights Reserved
</footer>

</body>
</html>
