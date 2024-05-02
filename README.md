# Scientific.Number
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Scientific Number Checker</title>
<link rel="stylesheet" href="styles.css">
</head>
<body>
<header>
    <h1>Scientific Number Checker</h1>
</header>
<nav>
    <ul>
        <li><a href="#home">Home</a></li>
        <li><a href="#about">About Us</a></li>
        <li><a href="#upload">Upload</a></li>
        <li><a href="#edit">Edit</a></li>
        <li><a href="#run">Run</a></li>
    </ul>
</nav>
<div class="container" id="home">
    <form id="scientificForm">
        <label for="scientificNumber">Enter a scientific number or string:</label>
        <input type="text" id="scientificNumber" name="scientificNumber" required>
        <button type="submit">Check</button>
    </form>
    <div id="result"></div>
</div>
<div class="container" id="about">
    <h2>About Us</h2>
    <p>This is the about us page. You can add information about your team here.</p>
</div>
<div class="container" id="upload">
    <h2>Upload File</h2>
    <!-- Form for uploading files -->
</div>
<div class="container" id="edit">
    <h2>Edit File</h2>
    <!-- Form for editing files -->
</div>
<div class="container" id="run">
    <h2>Run File</h2>
    <!-- Button to run the file -->
</div>
<footer>
    <p>&copy; 2024 Scientific Number Checker</p>
</footer>
<script src="script.js"></script>
</body>
</html>

