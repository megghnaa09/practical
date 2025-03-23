# My Project

## Introduction
Hello there! we decided to create this project because we think it is necessary for people out there.
This project will also help us increasing out techniques and experience.

## Features
1. User Friendly
2. Interactive elements to enhance user experience.

## languages used
1. Html
2. CSS
3. JavaScript

## code
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Job Portal</title>
    <style>* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: Arial, sans-serif;
}

body {
    background-color: #17304b;
}
html,
body {
  scroll-behavior: smooth;
}
nav {
    display: flex;
    justify-content: space-between;
    align-items: center;
    background: rgba(0, 0, 0, 0.7);
    padding: 15px 30px;
    color: white;
}
.nav-links {
    list-style: none;
    display: flex;
    gap: 20px;
}
.nav-links li a {
    color: white;
    text-decoration: none;
}
.top {
    height: 300px;
    background-image: url("top.jpeg"); /* Background image */
    background-size: cover;
    background-position: center;
    display: flex;
    align-items:baseline;
    justify-content: center;
    color: #404650;
    text-align: center;
    position: relative;
}

.top::after {
    content: "";
    position: absolute;
    width: 100%;
    height: 100%;
    background: rgba(0, 0, 0, 0.3);
    top: 0;
    left: 0;
}

.top-content {
    position: relative;
    z-index: 2;
}
.top h1 {
    font-size: 40px;
}

.job-sections {
    display: flex;
    justify-content: space-around;
    align-items: center;
    background: white;
    padding: 40px;
    margin: 20px auto;
    width: 80%;
    border-radius: 10px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

.job-img img {
    width: 100%;
    max-width: 400px;
    border-radius: 10px;
}

.start-btn {
    margin-top: 10px;
    padding: 10px 15px;
    border: none;
    cursor: pointer;
    background: black;
    color: white;
    border-radius: 15px;
}



.login-btn {
    background: #640d14;
    color: white;
    margin-top: 1px;
    padding: 5px 5px;
    border:black;
    cursor: pointer;
    font-size: 16px;
    border: none;
    border-radius: 25px;
    transition: 0.3s;
}

</style>
</head>
<body>
    <!-- header -->
    <header>
        <nav>
            <div class="logo"><img src="logo.jpeg" length="80px" width="80px"></div>
            <ul class="nav-links">
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About Us</a></li>
                <li><a href="#contact">Contact Us</a></li>
                <li><button class="login-btn">Login/Sign Up</button></li>
            </ul>
        </nav>
        <!-- name and tagline-->
        <section class="top">
            <div class="top-content">
                <h1>Bridge~Able</h1>
                <p>Connecting abilities to opportunities</p>
            </div>
        </section><br><br><br>
    
    <!-- applying and hiring section -->
    <section class="job-sections" id="home">
        <div class="job-seeker" >
            <h2>Looking for a job?</h2><hr><br>
            <p>Click below to fill in your personal details and get verified by us.</p>
            <button class="start-btn">START</button>
            <img src="">
        </div>
        <div class="job-img">
            <img src="seeker.jpg" alt="Image related to job seeking">
        </div>
    </section>

    <section class="job-sections">
        <div class="job-seeker">
            <h2>Want to hire?</h2><hr><br>
            <p>We got you! Click below to fill in your personal details and get verified by us.</p>
            <button class="start-btn">START</button>
            <img src="">
        </div>
        <div class="job-img">
            <img src="boss.jpg" alt="Image related to job seeking">
        </div>
    </section>
</body>
</html> 

