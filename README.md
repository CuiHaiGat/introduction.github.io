<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>About Me</title>
  <style>
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      margin: 0;
      padding: 0;
      background: #f5f7fa;
      color: #333;
    }
    .container {
      max-width: 800px;
      margin: auto;
      padding: 2rem;
      text-align: center;
    }
    img.profile {
      width: 150px;
      height: 150px;
      object-fit: cover;
      border-radius: 50%;
      border: 4px solid #4f46e5;
      margin-bottom: 1rem;
    }
    h1 {
      font-size: 2.5rem;
      margin: 0.5rem 0;
    }
    h2 {
      font-size: 1.5rem;
      color: #4f46e5;
      margin-bottom: 1rem;
    }
    p.bio {
      font-size: 1rem;
      margin-bottom: 1.5rem;
    }
    .skills {
      background: #eef2ff;
      padding: 1rem;
      border-radius: 8px;
      margin-top: 1rem;
    }
    .skills span {
      display: inline-block;
      background: #6366f1;
      color: white;
      padding: 0.3rem 0.7rem;
      border-radius: 20px;
      margin: 0.3rem;
      font-size: 0.9rem;
    }
    .contact {
      margin-top: 2rem;
      font-size: 1rem;
    }
    .contact a {
      color: #4f46e5;
      text-decoration: none;
    }
    .project {
      margin-top: 2rem;
      padding: 1.5rem;
      background-color: #e0e7ff;
      border-radius: 8px;
    }
    .project h3 {
      margin-bottom: 0.5rem;
      color: #3730a3;
    }
    .project p {
      margin-bottom: 1rem;
    }
    .project a {
      display: inline-block;
      background: #4f46e5;
      color: white;
      text-decoration: none;
      padding: 0.5rem 1rem;
      border-radius: 5px;
      font-weight: bold;
    }
  </style>
</head>
<body>
  <div class="container">
    <img src="https://scontent.fhan18-1.fna.fbcdn.net/v/t39.30808-6/279299476_1127806838014221_7610389923075894422_n.jpg?_nc_cat=103&ccb=1-7&_nc_sid=6ee11a&_nc_ohc=c0w143LMKEIQ7kNvwE34pQs&_nc_oc=Adl2Qqj0stqUvqQXMR3TWuKT6m5ZB9WOtKnkZ9y8g2f-UvQWtkE6sV6ZhuZgXGZTlPhL9xQzGyoDs_bflk2ouN03&_nc_zt=23&_nc_ht=scontent.fhan18-1.fna&_nc_gid=PlwiUuUFO_bdu8ae0ErIYA&oh=00_AfRXB8jAp_s_AyiVqPzi0SIPniS4Bm-GXIxGGtN2mFinKA&oe=688424CE" alt="Profile Photo" class="profile" />
    <h1>Le Thanh</h1>
    <h2>Student</h2>
    <p class="bio">
      Hello! I'm Le Thanh, Year 4 EEE student from NTU Singapore. I am interested in IoT, AI and Robotics areas.
    </p>

    <div class="skills">
      <strong>Skills:</strong><br />
      <span>ESP32</span>
      <span>Arduino</span>
      <span>IoT</span>
      <span>ThingsBoard</span>
      <span>OLED Display</span>
      <span>C++</span>
      <span>WiFi Manager</span>
    </div>

    <div class="project">
      <h3>💡 Smart Socket Project</h3>
      <p>
        A smart power socket built with ESP32 that allows real-time monitoring and control via ThingsBoard, including local OLED display and manual relay control.
      </p>
      <a href="file:///C:/Users/thanh/Downloads/Project.html#hardware" target="_blank">View Project</a>
    </div>

    <div class="contact">
      📧 <a href="mailto: peterthanh261004@gmail.com">peterthanh261004@gmail.com</a><br />
    </div>
  </div>
</body>
</html>
