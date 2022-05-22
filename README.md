# Mini-Project-1
Mini Project #1

<!DOCTYPE html>
<html lang="en">
<head>
<title>Mini Project #1</title>
</head>
    <body>
        <h1>
        My Favorite Cat is 
            <span id="catname">Zephyr</span>
        </h1>
         
        <script>
        var catname = document.getElementById("catname");
            var zephyr = catname.innerText;
            var cats = zephyr+" and Henary";
            catname.innerHTML=cats;
            
        </script>
    </body>
</html>
