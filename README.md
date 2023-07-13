# Octanet_JULY_task2
To-Do List
The to-do list app is a simple and intuitive web application built using HTML, CSS, and JavaScript. It allows users to create and manage their tasks effectively. The interface is designed with a clean and modern layout using CSS for styling. JavaScript is used to handle user interactions, such as adding, editing, and deleting tasks dynamically. The app provides a seamless user experience for organizing and prioritizing daily tasks.

# HTML File

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>To-Do List</title>
    <link rel="stylesheet" href="Style1.css">
</head>

<body>
<div class="container">
    <div class="todo-app">
        <h2>To-Do List <img src="images/icon.png"></h2>
        <div class="row">
            <input type="text" id="input-box" placeholder="Add your text">
            <button onclick="addTask()">Add</button>
        </div>
        <ul id="list-container">
            <!-- <li class="checked">Task 1</li>
            <li>Task 2</li>
            <li>Task 3</li>
            <li>Task 4</li> -->

        </ul>
    </div>
</div>
<script src="script.js"></script>
</body>

</html>
