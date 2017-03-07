//The best way of creating the smoothest hover animation is to create a parent and child element, and animate the child. This ensures that there is no jittering in the hover state… example below. 
<!doctype html>
<html>

<head>
    <style>
        .trigger {
            Width: 200px;
            height: 200px: border: 20px solid #ccc;
        }
        
        .box {
            display: inline-block;
            Background-color: pink;
            width: 200px;
            height: 200px;
            transition: transform 300ms ease-in-out;
            pointer-events: none;
        }
        
        .trigger:hover .box {
            transform: translate(200px, 150px) rotate(20deg);
        }
    </style>
</head>

<body>
    <div class="trigger">
        <div class="box">sss</div>
    </div>


</body>

</html>
