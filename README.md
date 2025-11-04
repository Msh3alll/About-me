<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>My Simple Website</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <h1>Welcome to My Website</h1>

    <h2>About Me</h2>
    <p>My name is Mashel Alotaibi. I am learning how to build websites using HTML and CSS.</p>

    <h2>My Interests</h2>
    <ul>
        <li>Reading</li>
        <li>Sports</li>
        <li>Music</li>
    </ul>
    <h2>My Weekly Schedule</h2>

<table>
    <tr>
        <th>Day</th>
        <th>Activity</th>
        <th>Time</th>
    </tr>
    <tr>
        <td>Monday</td>
        <td>Study HTML</td>
        <td>2:00 PM</td>
    </tr>
    <tr>
        <td>Wednesday</td>
        <td>Play Football</td>
        <td>5:00 PM</td>
    </tr>
    <tr>
        <td>Friday</td>
        <td>Watch a Movie</td>
        <td>8:00 PM</td>
    </tr>
</table>

body {
    font-family: Arial, sans-serif;
    background-color: #fafafa;
    color: #333;
    margin: 20px;
}

h1 {
    color: darkblue;
}

table {
    border-collapse: collapse;
    width: 60%;
}

th, td {
    border: 1px solid #333;
    padding: 8px;
    text-align: center;
}

th {
    background-color: #ddd;
}


img {
    border: 2px solid #333;
    border-radius: 5px;
}
