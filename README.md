<!DOCTYPE html>
<html>
<head>
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

0%% {filter: grayscale(100%);}
25% {filter: grayscale(0%);}
75% {filter: grayscale(0%);}
100% {filter: grayscale(100%);}
}

img.test:hover {
width: 500;
height: 500;
animation-name: animations;
animation-duration: 2s;
}
</style>
</head>
<body>


<img class="test" src="6be753e3-6f5b-46d1-97a9-cf82e1b2b7f1 (2).jpg" alt="image">

</body>
</html>
