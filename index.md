<!-- index.html -->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <link rel="stylesheet" type="text/css" href="assets/styles.css"> <!-- Optional if you want styles on this page too -->
</head>
<body>
    <div id="header"></div>
    
    <script>
        // Fetch the header content
        fetch('header.html')
            .then(response => response.text())
            .then(data => {
                document.getElementById('header').innerHTML = data;
            })
            .catch(error => console.error('Error loading header:', error));
    </script>

    <div style="display: flex; align-items: flex-start;">
        <div style="flex: 1;">
            <p>Hey! My name is Jonah Watts, and I have traveled the world and worked on a variety of projects in the fields of programming, audio, and video. I am passionate about creating and learning new things, and I am always looking for new opportunities to collaborate and grow.</p>
            
            <p>I have grown up in Canada, France, and Burundi, and I have a passion for storytelling, sustainability, and technology. I have finished my degree in Computer Science at Trinity Western University, and I am currently working on a variety of projects. Check them out below!</p>

            <h2>Explore My Work</h2>
            <ul>
                <li><a href="programming.md">Programming Projects</a></li>
                <li><a href="audio-video.md">Video/Audio Projects</a></li>
                <li><a href="resume.md">Resume</a></li>
            </ul>
            
            <p>Feel free to explore my work and reach out if you'd like to collaborate or learn more about any projects!</p>
        </div>
        
        <div style="flex: 0 0 200px; margin-left: 20px;">
            <img src="assets/Jonah.png" alt="Jonah Watts" style="width: 100%; border-radius: 8px;">
        </div>
    </div>
</body>
</html>
