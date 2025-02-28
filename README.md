<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Website Task</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, sans-serif;
        }

        body {
            background-color: #f3f3f3;
        }

        .header {
            background-color: #4caf50;
            color: white;
            text-align: center;
            padding: 20px;
            font-size: 24px;
            font-weight: bold;
        }

        .nav {
            display: flex;
            justify-content: center;
            background-color: #4caf50;
            padding: 10px 0;
        }

        .nav a {
            color: white;
            text-decoration: none;
            padding: 10px 20px;
            font-size: 18px;
        }

        .nav a:hover {
            text-decoration: underline;
        }

        .content {
            display: flex;
            justify-content: space-between;
            align-items: flex-start;
            flex-wrap: wrap;
            padding: 40px 20px;
            max-width: 1000px;
            margin: 0 auto;
        }

        .left-column, .right-column {
            display:flex;
             flex-direction: column; 
           

            gap: 20px;
        }

        .left-column {
            flex: 1;
        }

        .right-column {
            flex: 1;
            display: flex;
            justify-content: flex-end;
        }

        .card {
            background: white;
            border-radius: 10px;
            padding: 20px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            width: 300px;
        }

        .card h3 {
            color: #4caf50;
            margin-bottom: 10px;
        }

        .footer {
            background-color: #222;
            color: white;
            text-align: center;
            padding: 15px;
            font-size: 16px;
            margin-top: 40px;
        }

        .footer a {
            color: #4caf50;
            text-decoration: none;
            margin: 0 10px;
        }

        .footer a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>

    <div class="header">
        Welcome to Your Website Task
    </div>

    <div class="nav">
        <a href="#">Home</a>
        <a href="#">About</a>
        <a href="#">Contact</a>
    </div>

    <div class="content">
        <div class="left-column">
            <div class="card">
                <h3>About CSS</h3>
                <p>Cascading Style Sheets (CSS) allow you to style and layout your web pages, adding colors, spacing, and more.</p>
            </div>
            <div class="card">
                <h3>Responsive Design</h3>
                <p>Responsive design ensures your webpage looks great on all devices, from desktops to mobile phones.</p>
            </div>
        </div>
        <div class="right-column">
            <div class="card">
                <h3>Box Model</h3>
                <p>The CSS box model describes the rectangular boxes generated for elements. It includes margins, borders, padding, and the actual content.</p>
            </div>
        </div>
    </div>

    <div class="footer">
        Created by Suraj Gupta | Follow us on 
        <a href="#">Instagram</a> | 
        <a href="#">Twitter</a> | 
        <a href="#">LinkedIn</a>
    </div>

</body>
</html>
