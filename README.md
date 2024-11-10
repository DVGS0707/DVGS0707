<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Vishwa Gaurav Shukla | Software Developer</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/normalize/8.0.1/normalize.min.css" integrity="sha512-NhSC1YmyruXifcj/KFRWoC561YpHPCv14NxphZmPFgvesO9K8KCRnYQfFmG4PvX5+6aJlwwx2lBq2X1tnoXb+g==" crossorigin="anonymous" referrerpolicy="no-referrer" />
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.1.1/css/all.min.css" integrity="sha512-KfkfwYDsLkIlwQp6LFnl8zNdLGxu9YAA1QvwINks4PhcElQSvqcyVLLD9aMhXd13uQjoXtEKNosOWaZqXgel0g==" crossorigin="anonymous" referrerpolicy="no-referrer" />
    <style>
body {
    font-family: 'Roboto', sans-serif;
    background-color: #f5f5f5;
    color: #333;
}
.header-container{
    box-shadow: 6px 6px 6px rgba(0, 3, 51, 0.75);
}

.header-container, .skills ul {
    display: flex;
    justify-content: space-evenly;
    align-items: center;
    background-color: #fff;
    border-radius: 0.5rem;
    transition: box-shadow 0.3s ease, transform 0.3s ease;
    padding: 2rem;
}

.header-container:hover {
    transform: scale(0.95);
    box-shadow: 10px 10px 10px rgba(0, 3, 51, 1);
}
.skills ul:hover{
    transform: scale(1.2);
}

.header-container h1 {
    font-size: 2.5rem;
    font-weight: bold;
    margin: 0;
}

.about-me, .social-links {
    max-width: 800px;
    margin: 0 auto;
    padding: 2rem;
}

.about-me ul {
    list-style: none;
    padding: 0;
    margin: 0 1rem 0.5rem 1rem;
}

.about-me ul::before {
    content: "\2022";
    color: #007bff;
    margin-right: 0.5rem;
}

.skills {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-around;
    margin: 2rem 0;
}

.skills ul {
    padding: 1rem;
    border-radius: 0.75rem;
    font-weight: 600;
}

.social-links {
    display: flex;
    justify-content: space-around;
    margin-bottom: 2rem;
}

.social-links a {
    color: #333;
}

.github-box, .html, .css3, .javascript, .reactjs, .laravel, .mysql, .mongodb, .php, .linkedin, .instagram, .github {
    transition: box-shadow 0.3s ease, transform 0.3s ease, filter 0.3s ease;
}

.github-box {
    filter: drop-shadow(6px 6px 6px rgba(0, 3, 51, 0.75));
}
.github-box:hover {
    transform: scale(1.05);
    filter: drop-shadow(8px 8px 8px rgba(0, 3, 51, 1));
}
.html { 
   box-shadow:6px 6px 6px rgba(255, 105, 0, 0.75);
transition: filter 0.3s ease; 
}
.html:hover { box-shadow:8px 8px 8px rgba(255, 105, 0, 1); }
.css3 { 
    box-shadow:6px 6px 6px rgba(0, 0, 255, 0.75); 
    transition: filter 0.3s ease; 
}
.css3:hover { box-shadow:8px 8px 8px rgba(0, 0, 255, 1); }
.javascript {
    box-shadow:6px 6px 6px rgba(255, 255, 0, 0.5); 
    transition: filter 0.3s ease; 
}
.javascript:hover {box-shadow:8px 8px 8px rgba(255, 255, 0, 1); }
.reactjs { 
    box-shadow:6px 6px 6px rgba(173, 216, 230, 0.75);
    transition: filter 0.3s ease; 
}
.reactjs:hover { box-shadow:8px 8px 8px rgba(173, 216, 230, 1); }
.laravel { 
    box-shadow:6px 6px 6px rgba(255, 0, 0, 0.75);
    transition: filter 0.3s ease; 
}
.laravel:hover { box-shadow:8px 8px 8px rgba(255, 0, 0, 1); }
.mysql {
    box-shadow: 6px 6px 6px rgba(0, 117, 143, 0.5), 8px 8px 8px rgba(242, 145, 17, 0.5);
    transition: filter 0.3s ease; 
}
.mysql:hover {
    transform: scale(1.05);
    box-shadow: 8px 8px 8px rgba(242, 145, 17, 1), 8px 8px 8px rgba(0, 117, 143, 1);
}
.mongodb {
    box-shadow: 6px 6px 6px rgba(77, 179, 61, 0.75);
    transition: filter 0.3s ease; 
}
.mongodb:hover {
    transform: scale(1.05);
    box-shadow: 8px 8px 8px rgba(77, 179, 61, 1);
}
.php {
    box-shadow: 6px 6px 6px rgba(174, 178, 213, 0.75);
    transition: filter 0.3s ease; 
}
.php:hover {
    transform: scale(1.05);
    box-shadow: 8px 8px 8px rgba(174, 178, 213, 1);
}
.linkedin {
    box-shadow: 6px 6px 6px rgba(0, 119, 181, 0.75);
}
.linkedin:hover {
    box-shadow: 6px 6px 6px rgba(0, 119, 181, 1);
}

.instagram {
    box-shadow: 6px 6px 6px rgba(225, 48, 108, 0.75);
}
.instagram:hover {
    box-shadow: 6px 6px 6px rgba(225, 48, 108, 1);
}

.github {
    box-shadow: 6px 6px 6px rgba(0, 3, 51, 0.75);
}
.github:hover {
    box-shadow: 6px 6px 6px rgba(0, 3, 51, 1);
}
.social-links img:hover{
    transform: scale(1.25);
}
    </style>
</head>
<body>
    <div class="header-container">
        <img src="https://i.giphy.com/media/v1.Y2lkPTc5MGI3NjExcHk5d3ByYjE5eWVzNWxhMGdodWM3NHpzb2xjNXc2b3ZkdGNtYWxudyZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/78XCFBGOlS6keY1Bil/giphy.gif" width="150" height="120" alt="Welcome gif" class="github-box"> 
        <h1>Vishwa Gaurav Shukla</h1>
           <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=DVGS0707&theme=github_dark&layout=compact" alt="Top Languages Used" width="280" height="200" class="github-box">
    </div>
    <div class="about-me" align="center" >
        <p>
            I'm a passionate software developer with experience in both front-end and back-end technologies. I'm excited to work on projects that make a positive impact on people's lives.
        </p>
        <ul>
            <ul>I hold a degree in <strong>B.Tech Mechanical Engineering</strong>, but I’m passionate about software development.</ul>
            <ul>I'm experienced in <strong>Full Stack Development</strong>, with expertise in both front-end and back-end technologies.</ul>
        </ul>
        <p>
            <em>As a software developer, I am passionate about creating scalable, efficient, and high-performance applications. I enjoy working with modern frameworks and databases to deliver robust solutions. I am always eager to learn new technologies and improve my skills.</em>
        </p>
          <a href="https://git.io/streak-stats">
            <img src="http://github-readme-streak-stats.herokuapp.com?user=DVGS0707&hide_border=true&border_radius=15&date_format=j%20M%5B%20Y%5D&mode=weekly&stroke=24025F&ring=24025F&fire=24025F&currStreakNum=24025F&sideNums=24025F&sideLabels=24025F&dates=24025F" class="github-box"/>
        </a>
    </div>
    <div class="skills">
        <ul class="html"><i class="fab fa-html5 "></i> HTML5</ul>
        <ul class="css3"><i class="fab fa-css3-alt " ></i> CSS3</ul>
        <ul class="javascript"><i class="fab fa-js-square "></i> JavaScript</ul>
        <ul class="reactjs"><i class="fab fa-react "></i> ReactJS</ul>
        <ul class="laravel"><i class="fab fa-laravel "></i> Laravel</ul>
        <ul class="mysql"><i class="fab fa-mysql "></i> MySQL</ul>
        <ul class="mongodb"><i class="fab fa-mongodb "></i> MongoDB</ul>
        <ul class="php"><i class="fab fa-php "></i> PHP</ul>
    </div>

<div class="social-links" align="center">
    <a href="https://www.linkedin.com/in/vgs-profile/" target="_blank" >
         <img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn Profile" class="linkedin"/>
    </a>
    <a href="https://www.instagram.com/iamkingvgs/" target="_blank" >
        <img src="https://img.shields.io/badge/instagram-%23E4405F.svg?&style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram Profile"class="instagram" />
    </a>
    <a href="https://github.com/DVGS0707?tab=followers" target="_blank" >
         <img src="https://img.shields.io/github/followers/DVGS0707?label=Followers&style=for-the-badge" alt="GitHub Followers" class="github"/>
    </a>
</div>

</body>
</html>

