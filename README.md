<!DOCTYPE html>
<html lang="pl">
<head>
    <meta charset="UTF-8">
    <title>zadanie js</title>
</head>
<body>

    <h2>JS Przyciski</h2>
<table>
    <tr><td>move the mouse on the button</td><td>click the button</td></tr>
    <tr><td><button onmouseover = "b1()">+</button></td><td><button onclick = "b2()">-</button></td></tr>
    <tr><td>click on the button</td><td>click off the button</td></tr>
    <tr><td><button onmousedown = "b3()">/</button></td><td> <button onmouseup = "b4()">*</button></td></tr>
    <tr><td ><div id = "x">0</div></td></tr>
</table>
    
    
    
   
    



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
            x = x/2;
            addx.innerHTML = x;
        }

        function b4()
        {
            var addx = document.getElementById("x");
            x = x*2;
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
            text-align:center;
            background-color: rgb(44, 44, 44);
            color: white;
        }

        table
        {
            border-collapse: collapse;
            margin: auto;
            background-color: rgb(83, 83, 83);
            border: 3px solid white;
            height: 30%;
        }
        td, th
        {
            text-align: center;
            height: 40px;
            border: 1px solid white;
        }
        

    </style>
    
</body>
</html>

</html>
