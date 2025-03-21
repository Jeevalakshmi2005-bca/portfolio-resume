<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Profile - Jeeva Lakshmi K</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f9;
            color: #333;
        }
        header {
            background-color: #4CAF50;
            color: white;
            padding: 20px;
            text-align: center;
        }
        section {
            padding: 20px;
            margin: 20px;
            background-color: white;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        h2 {
            color: #4CAF50;
        }
        img {
            border-radius: 50%;
            margin-bottom: 20px;
        }
        ul {
            list-style-type: none;
            padding: 0;
        }
        li {
            padding: 5px 0;
        }
        strong {
            color: #333;
        }
        .portfolio {
            display: flex;
            flex-wrap: wrap;
        }
        .portfolio-item {
            width: 45%;
            margin: 10px;
            padding: 10px;
            background-color: #f1f1f1;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        .todo-list {
            margin-top: 20px;
        }
        .todo-list input {
            margin-right: 10px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to Jeeva Lakshmi K's Profile</h1>
    </header>

    <section>
        <h2>About Me</h2>
        <img src="profile pic.png" alt="Jeeva Lakshmi K's Profile Picture" width="150">
        <p>My name is <strong>Jeeva Lakshmi K</strong>.</p>
    </section>
    
    <section>
        <h2>Education</h2>
        <p>I have completed a <strong>Bachelor of Computer Application (BCA)</strong> from <strong>Anna Adarsh College for Women</strong>.</p>
    </section>

    <section>
        <h2>Skills</h2>
        <ul>
            <li><strong>Java</strong></li>
            <li><strong>Python</strong></li>
            <li><strong>C++</strong></li>
            <li><strong>HTML</strong></li>
            <li><strong>CSS</strong></li>
            <li><strong>JavaScript</strong></li>
        </ul>
    </section>

    <!-- Project Portfolio Section -->
    <section>
        <h2>Project Portfolio</h2>
        <div class="portfolio">
            <div class="portfolio-item">
                <h3>Project 1: Website Development</h3>
                <p>Developed a responsive website using HTML, CSS, and JavaScript. Implemented dynamic features with JavaScript and optimized for mobile devices.</p>
            </div>
            <div class="portfolio-item">
                <h3>Project 2: Python Automation Script</h3>
                <p>Created a Python script to automate file management tasks, including organizing files and directories based on their types.</p>
            </div>
            <div class="portfolio-item">
                <h3>Project 3: Java-based Banking System</h3>
                <p>Built a Java-based banking system with features like account creation, balance checking, and fund transfers using object-oriented principles.</p>
            </div>
            <div class="portfolio-item">
                <h3>Project 4: C++ Console Application</h3>
                <p>Developed a C++ console application that simulates a library management system, including functionalities like book borrowing and return tracking.</p>
            </div>
        </div>
    </section>

    <!-- To-Do List Section -->
    <section class="todo-list">
        <h2>To-Do List</h2>
        <ul>
            <li><input type="checkbox"> Complete Java project documentation</li>
            <li><input type="checkbox"> Study for Python interview</li>
            <li><input type="checkbox"> Update portfolio with new projects</li>
            <li><input type="checkbox"> Practice C++ algorithms</li>
        </ul>
    </section>
    
</body>
</html>
