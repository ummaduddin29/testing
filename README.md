<html>
<head>
<script>
       setTimeout(function(){
           location.reload();
       },7000);
    </script>
<style>
body {
 background-color: #000000;
}

img.test {
width: 500;
height: 500;
filter: grayscale(100%)
}

@keyframes animations
{
from {filter: grayscale(100%);}
to {filter: grayscale(0%);}
}

img.test:hover {
width: 500;
height: 500;
animation-name: animations;
animation-duration: 2s;
filter: grayscale(0%);
}

h3.white1
{
color: #ffffff;
}

h3.white2
{
color: #ffffff;
}

</style>
</head>
<body>

<h3 class="white2" >Click Image To Colorize.</h3>
<h3 class="white2" >Picture will go back to black and white in 5 seconds.</h3>
<h3 class="white2" >Then click again to colorize.</h3>

<img class="test" src="6be753e3-6f5b-46d1-97a9-cf82e1b2b7f1 (2).jpg" alt="image">

</body>
</html>
