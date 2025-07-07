<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Happy Birthday Preety 🎂</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      background: linear-gradient(to bottom right, #ffccff, #ffe6e6);
      font-family: 'Segoe UI', sans-serif;
      text-align: center;
      overflow-x: hidden;
    }
    h1 {
      color: #d6336c;
      margin-top: 20px;
      font-size: 2rem;
    }
    .container {
      display: flex;
      justify-content: center;
      align-items: center;
      flex-wrap: wrap;
      padding: 20px;
    }
    .photo {
      width: 140px;
      height: 140px;
      object-fit: cover;
      margin: 10px;
      border: 3px solid #fff;
      border-radius: 15px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.2);
      touch-action: none;
    }
    .drop-zone {
      width: 280px;
      height: 280px;
      margin: 20px auto;
      background: #fff0f5;
      border: 4px dashed #ff69b4;
      border-radius: 20px;
      position: relative;
    }
    .drop-zone::before {
      content: "Drop a memory here 🎁";
      color: #ff1493;
      font-size: 1.2rem;
      position: absolute;
      top: 50%;
      left: 50%;
      transform: translate(-50%, -50%);
    }
    #message {
      color: #880e4f;
      font-size: 1.4rem;
      margin: 30px 15px;
      padding: 15px;
      background: #ffe4ec;
      border-radius: 12px;
      display: none;
      box-shadow: 0 4px 12px rgba(0,0,0,0.1);
    }
    .balloon {
      position: absolute;
      width: 50px;
      animation: float 6s ease-in-out infinite;
    }
    @keyframes float {
      0% { transform: translateY(0); }
      50% { transform: translateY(-20px); }
      100% { transform: translateY(0); }
    }
  </style>
</head>
<body>
  <audio autoplay loop>
    <source src="https://www.bensound.com/bensound-music/bensound-smile.mp3" type="audio/mpeg">
    Your browser does not support the audio element.
  </audio>

  <h1>Happy Birthday ❤️ Preety</h1>
  <div class="container">
    <img src="1000061840.jpg" class="photo" draggable="true" id="photo1" alt="Preety 1">
    <img src="1000061834.jpg" class="photo" draggable="true" id="photo2" alt="Preety 2">
    <img src="1000061794.jpg" class
