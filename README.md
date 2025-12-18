<!DOCTYPE html>
<html>
    <head>
        <title>Dynamic website Example</title>     
</head>
<body>

    <h2>Dynamic Website Example</h2>
    
    <label>Enter your name:</label>
    <input type="text" id="username">
    <button onclick="showMessage()">Sumbit</button>

    <p id="output"></p>

    <script>
        function showMessage() {
            var name = document.getElementById("username").ValueMax
            document.getElementById("output").innerHTML = 
            "Hello " + name + "! Welcome to our dynamic website.";
        }
    </script>

</body>
</html>
