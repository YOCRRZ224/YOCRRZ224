
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My README</title>
    <link rel="stylesheet" href="style.css">
    <link href="https://fonts.googleapis.com/icon?family=Material+Icons" rel="stylesheet">  <!-- Material Icons -->
</head>
<body>
    <div class="container">
        <div class="profile">
            <i class="material-icons large animated-icon">person</i>  <!-- Animated Icon -->
            <h1>Your Name</h1>
            <p>Your Email: your.email@example.com</p>
            <p>Passion:  Web Development</p>
        </div>
        <div class="skills">
            <h2>Skills</h2>
            <ul>
                <li><i class="material-icons">code</i> HTML</li>
                <li><i class="material-icons">code</i> CSS</li>
                <li><i class="material-icons">code</i> JavaScript</li>
                <!-- Add more skills here -->
            </ul>
        </div>
        <div class="projects">
            <h2>Projects</h2>
            <!-- Add your project links/descriptions here -->
            <p>Coming soon!</p>
        </div>
    </div>
    <script src="script.js"></script>
</body>
</html>
<style>
body {
    font-family: 'Roboto', sans-serif; /* Material Design font */
    margin: 0;
    background-color: #f4f4f4;
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 100vh;
}

.container {
    background-color: #fff;
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
    text-align: center;
}

.profile {
    margin-bottom: 20px;
}

.profile h1 {
    margin-top: 0;
}

.profile .material-icons {
    font-size: 6em;
    color: #007bff; /* Blue color */
    margin-bottom: 10px;
}

.skills ul {
    list-style: none;
    padding: 0;
}

.skills ul li {
    margin-bottom: 10px;
    display: flex;
    align-items: center;
}

.skills ul li .material-icons {
    margin-right: 10px;
    color: #3f51b5; /* Purple color */
}

/* Animation */
.animated-icon {
    animation: rotate 2s linear ;
    color: gray;
    transition: .3s;
}

@keyframes rotate {
    from {
        transform: rotate(0deg);
        color: black;
    }
    to {
        transform: rotate(360deg);
        color: gray;
    }
}
// You can add more complex animations or interactions here if needed.  This file is currently empty as the primary animation is in CSS.
</style>