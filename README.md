<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>declaring function</title>
    <style>
        .out{color: blue; font-weight: bold;}
    </style>
</head>
<body>
    <h2> Function with user-name</h2>
    <p id="demo1" class="out"></p>
    <script>
        let greet = function()
         {
            return "Hello Students, How are You!!";
        }
        document.getElementById("demo1").innerText=greet();
    </script>
</body>
</html>
