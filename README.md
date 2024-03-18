<!DOCTYPE html>
<html lang="pl">
<head>
    <meta charset="UTF-8">
    <title>zadanie js</title>
</head>
<body>

    <h2>JS Przyciski</h2>

    <button onmouseover = "b1()">+(move the mouse on the button)</button>
    <button onclick = "b2()">-(click the button)</button>
    <button onclick = "b2()">-(click the button)</button>
    <button onclick = "b2()">-(click the button)</button>
    <div id = "x">0</div>



    <script type="text/javascript">
        var x = 0;

        function b1()
        {
            var addx = document.getElementById("x");
            x += 1;
            addx.innerHTML = x;
        }
        function b2()
        {
            var addx = document.getElementById("x");
            x -= 5;
            addx.innerHTML = x;
        }
        function b3()
        {
            var addx = document.getElementById("x");
            x -= 5;
            addx.innerHTML = x;
        }
        function b4()
        {
            var addx = document.getElementById("x");
            x -= 5;
            addx.innerHTML = x;
        }
    </script>

    <style>
        button
        {
            background-color: black;
            color: white;
            border:2px white solid;
            font-size: large;
        }
        html
        {
            background-color: rgb(44, 44, 44);
            color: white;
        }

    </style>
    
</body>
</html>

</html>
