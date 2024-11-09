

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Profile Card</title>
    <style>
*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 100vh;
    background-color:#f9f9f9;
    font-family: Arial, sans-serif;
}

.profile-card {
    background-color:#c0c0c0;
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
    text-align: center;
    max-width: 300px;
    width: 100%;
}

.profile-pic {
    width: 100px;
    height: 100px;
    border-radius: 50%;
    margin-bottom: 15px;
}

.name {
    font-size: 24px;
    color: blue;
    margin-bottom: 5px;
}

.title {
    font-size: 18px;
    color: blue;
    margin-bottom: 10px;
}

.description {
    font-size: 18px;
    color: black;
    margin-bottom: 20px;
}
    
 .desc{
    font-size: 18px;
    color: black;
     
   margin-bottom: 20px;
 }

.social-links {
    display: flex;
    justify-content: center;
    gap: 10px;
}

.social-link {
    padding: 10px 15px;
    background-color: #0073e6;
    color: #fff;
    border-radius: 5px;
    text-decoration: none;
    font-size: 14px;
    transition: background-color 0.3s;
}

.social-link:hover {
    background-color: #005bb5;
}
</style>    



</head>
<body>
    <div class="profile-card">
        <img src="https://via.placeholder.com/150" alt="Profile Picture" class="profile-pic">
        <h2 class="name">shehnaj</h2>
        <p class="title">Web Developer</p>
        <p class="description">Passionate about building responsive and engaging websites.</p>
        <p class="desc">Enthusiatic to work with companies and get a work experience</p>
        <div class="social-links">  
            <a href="https://www.linkedin.com/in/shehnajshehnaj" target="_blank"class="social-link">LinkedIn Profile</a>
        </div>
    </div>
</body>
</html>



