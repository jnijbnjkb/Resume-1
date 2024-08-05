<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Manav Lathiya</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Roboto', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }
        .container {
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
            background: #fff;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        .header, .section {
            padding: 20px;
            margin-bottom: 20px;
        }
        .header {
            background: #2c3e50;
            color: #ecf0f1;
            text-align: center;
        }
        .header h1 {
            margin: 0;
            font-size: 2em;
        }
        .header p {
            margin: 5px 0;
        }
        .nav {
            background: #34495e;
            overflow: hidden;
        }
        .nav a {
            float: left;
            display: block;
            color: #ecf0f1;
            text-align: center;
            padding: 14px 16px;
            text-decoration: none;
        }
        .nav a:hover {
            background-color: #2c3e50;
        }
        .section h2 {
            border-bottom: 2px solid #2c3e50;
            padding-bottom: 10px;
        }
        .row {
            display: flex;
            justify-content: space-between;
            margin: 10px 0;
        }
        .row div {
            flex: 1;
            padding: 10px;
        }
        .skills, .projects {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-between;
        }
        .skills div, .projects div {
            flex: 0 48%;
            background: #ecf0f1;
            margin: 1%;
            padding: 10px;
            box-shadow: 0 0 5px rgba(0, 0, 0, 0.1);
        }
        table {
            width: 100%;
            border-collapse: collapse;
            margin: 20px 0;
        }
        table, th, td {
            border: 1px solid #ddd;
            padding: 8px;
        }
        th {
            background: #34495e;
            color: #fff;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="header">
            <h1>Manav Lathiya</h1>
            <p>+91 8651475263</p>
            <p>manavlathiya@gmail.com</p>
        </div>
        <div class="nav">
            <a href="#about_me">About Me</a>
            <a href="#edu">Qualification</a>
            <a href="#tech">Skills</a>
            <a href="#skills">Hobbies</a>
            <a href="#projects">Projects</a>
        </div>
        <div class="section" id="about_me">
            <h2>About Me</h2>
            <p>
I am a dedicated and passionate individual currently pursuing a Bachelor's degree in Computer Applications (BCA). Alongside my academic pursuits, I am a content creator and entrepreneur, always eager to explore new ideas and bring them to life. My journey is driven by a commitment to change traditional medical system. I thrive in dynamic environments and am constantly seeking opportunities to grow and make a meaningful impact in society. Through my work and projects, I aim to inspire and connect with others, leveraging my skills and experiences to contribute to world.</p>
            <h3>Personal Information:</h3>
            <div class="row">
                <div><strong>Name:</strong> Manav Bipinbhai Lathiya</div>
                <div><strong>Age:</strong> 20</div>
            </div>
            <div class="row">
                <div><strong>Birth Date:</strong> 11 October, 2004</div>
                <div><strong>Nationality:</strong> Indian</div>
            </div>
            <div class="row">
                <div><strong>Languages:</strong> Gujarati, Hindi, English</div>
            </div>
        </div>
        <div class="section" id="edu">
            <h2>Qualification</h2>
            <table>
                <tr>
                    <th>No.</th>
                    <th>Exam Passed</th>
                    <th>Board/University</th>
                    <th>Marks/Grade</th>
                    <th>Year of Passing</th>
                </tr>
                <tr>
                    <td>1</td>
                    <td>S.S.C</td>
                    <td>GSEB</td>
                    <td>67%</td>
                    <td>2020</td>
                </tr>
                <tr>
                    <td>2</td>
                    <td>H.S.C</td>
                    <td>GSEB</td>
                    <td>75%</td>
                    <td>2022</td>
                </tr>
                <tr>
                    <td>3</td>
                    <td>BCA</td>
                    <td>VNSGU</td>
                    <td>Currently Pursuing</td>
                    <td>2022-2025</td>
                </tr>
            </table>
        </div>
        <div class="section" id="tech">
            <h2>Skills</h2>
            <div class="skills">
				<div>Problem Solving</div>
				<div>Product Building</div>
                <div>Data Analysis</div>
                <div>Leadership</div>
                <div>Team Management</div>
                <div>Communication Skills</div>
            </div>
        </div>
        <div class="section" id="skills">
            <h2>Hobbies</h2>
            <div class="skills">
                <div>Reading</div>
                <div>Cricket</div>
                <div>Travelling</div>
                <div>Writing</div>
                <div>Camping</div>
                <div>Yoga</div>
            </div>
        </div>
        <div class="section" id="projects">
            <h2>Projects</h2>
            <div class="projects">
                <div>
                    <h3>Community Connector</h3>
                    <p>Led a project aimed at enhancing community engagement and connectivity through various events and digital platforms. Successfully increased participation by 30% and fostered stronger community relationships.</p>
                </div>
                <div>
                    <h4>Safe Zone</h4>
					<p>Spearheaded an initiative to enhance safety in community areas through strategic planning and collaboration with local authorities. Developed and executed safety workshops and resources, significantly boosting public confidence</p>
                </div>
            </div>
        </div>
    </div>
</body>
</html>
