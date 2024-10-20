<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" type="text/css" href="assets/styles.css">
  <title>Programming Projects</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      line-height: 1.6;
      margin: 20px;
      padding: 0;
    }
    
    nav {
      margin-bottom: 20px;
    }

    nav ul {
      list-style-type: none;
      padding: 0;
    }

    nav ul li {
      display: inline-block;
      margin-right: 15px;
    }

    nav ul li ul {
      display: none;
      position: absolute;
      background-color: white;
      box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
      padding: 10px;
      z-index: 1;
    }

    nav ul li:hover ul {
      display: block;
    }

    h1 {
      font-size: 2em;
      margin-bottom: 10px;
    }

    hr {
      margin: 20px 0;
    }

    .project {
      margin-bottom: 30px;
      display: flex;
      align-items: center;
    }

    .project-img {
      max-width: 150px;
      margin-right: 20px;
      border-radius: 8px;
    }

    h3 {
      margin: 0;
      font-size: 1.5em;
    }

    p {
      margin: 5px 0 0;
    }

    a {
      color: #007bff;
      text-decoration: none;
    }

    a:hover {
      text-decoration: underline;
    }

  </style>
</head>
<body>

<nav>
  <ul>
    <li><a href="index.html">Home</a></li>
    <li>
      <a href="programming.html">Programming Projects</a>
      <ul>
        <li><a href="project1.html">Project 1</a></li>
        <li><a href="project2.html">Project 2</a></li>
        <!-- Add more projects as needed -->
      </ul>
    </li>
    <li>
      <a href="audio-video.html">Video/Audio Projects</a>
      <ul>
        <li><a href="video1.html">Video 1</a></li>
        <li><a href="audio1.html">Audio 1</a></li>
        <!-- Add more projects as needed -->
      </ul>
    </li>
    <li><a href="resume.html">Resume</a></li>
  </ul>
</nav>

<h1>Programming Projects</h1>
<hr>

<div class="project">
  <img src="/assets/ParticleProject.png" alt="Particle System" class="project-img">
  <div>
    <h3><a href="Programming/ParticleSystem.md">2021 - Particle System</a></h3>
    <p>A custom-built particle system written in C. A project for a class to learn about how to spawn individual particles and manipulate them in a 2D space.</p>
  </div>
</div>

<div class="project">
  <img src="/assets/RayTrace.png" alt="Ray Tracer" class="project-img">
  <div>
    <h3><a href="Programming/RayTracer.md">2021 - DIY Ray Tracer</a></h3>
    <p>A custom-built ray tracer written in Java. A project made to learn about computer graphics to manually make a ray tracer that would render a 3D scene with different geometries.</p>
  </div>
</div>

<div class="project">
  <img src="path-to-learning-languages-photo.jpg" alt="Learning Languages" class="project-img">
  <div>
    <h3>2022 - Learning 8 Programming Languages in 3 Months</h3>
    <p>Documented learning 8 different programming languages. [Mention the languages and insights].</p>
  </div>
</div>

<div class="project">
  <img src="path-to-maze-solving-photo.jpg" alt="AI Maze-Solving Robot" class="project-img">
  <div>
    <h3>2023 - AI Maze-Solving Robot</h3>
    <p>Designed an AI to navigate through mazes autonomously. Used different algorithms to find the pattern of the maze and race through it. [Link to project code/video].</p>
  </div>
</div>

<div class="project">
  <img src="/assets/CMPT401 ESP32.jpg" alt="ESP32 Projects" class="project-img">
  <div>
    <h3>2024 - ESP32 Learning Projects</h3>
    <p>Created a series of projects to learn about the ESP32 microcontroller. Link to the website with the projects is <a href="https://adastorm.github.io/CMPT401_TWU/">here</a>.</p>
  </div>
</div>

<div class="project">
  <img src="/assets/GuitarPedal.png" alt="DIY Guitar Pedal" class="project-img">
  <div>
    <h3>2024 - DIY Guitar Pedal Adventures</h3>
    <p>Designed and built custom guitar pedals for fun using different methods. [Details on design and sound samples].</p>
  </div>
</div>

<div class="project">
  <img src="/assets/PinyataPulse.png" alt="Pinyata Rhythm Game" class="project-img">
  <div>
    <h3>2024 - GameJam: Pinyata Rhythm Game</h3>
    <p>A rhythm game made in Unity. Worked on a team of 4 to create a rhythm game where the player hits a pinata to the beat of the music. Project had all original code, art, and music. Source code can be found <a href="https://github.com/adastorm/GameJamGame">here</a>. Itch.io page can be found <a href="https://adastorm.itch.io/pinata">here</a>.</p>
  </div>
</div>

<div class="project">
  <img src="path-to-vr-campus-tour-photo.jpg" alt="VR Campus Tour" class="project-img">
  <div>
    <h3>2024 - Making a VR Campus Tour App</h3>
    <p>Designed and built custom guitar pedals. [Details on design and sound samples].</p>
  </div>
</div>

<div class="project">
  <img src="path-to-vr-campus-tour-photo.jpg" alt="VR Campus Tour" class="project-img">
  <div>
    <h3>2024 - Making a Spotify Record Player</h3>
    <p>Designed and built custom guitar pedals. [Details on design and sound samples].</p>
  </div>
</div>

<hr>
<a href="index.md">Back to Main Page</a>

</body>
</html>
