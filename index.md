<!DOCTYPE html>
<html lang="en"> <!-- Set this to the main language of your site -->
<head>
    <meta charset="utf-8">

    <title>Sean Kuehl's Website</title>

    <!-- Enter a brief description of your page -->
    <meta name="description" content="Welcome to my page!">

<style>
.button {
  background-color: #4CAF50;
  border: none;
  color: white;
  padding: 15px 32px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  font-size: 16px;
  margin: 4px 2px;
  cursor: pointer;
}

.button:hover {
  background-color: #3e8e41;
}

.button:active {
  background-color: #3e8e41;
  box-shadow: 0 5px #666;
  transform: translateY(4px);
}

.button1 {background-color: #4CAF50;} /* Green */
.button2 {background-color: #008CBA;} /* Blue */


img {
  
  
  margin-top: 100px;
 
  
}

h1 {text-align: center;}
p {text-align: center;}
div {text-align: center;}
audio {text-align: center;}

html, body {
  width: 100%;
  height:100%;
}

body {
    background: linear-gradient(-45deg, #ee7752, #5b965a, #23a6d5, #23d5ab);
    background-size: 400% 400%;
    animation: gradient 15s ease infinite;
}

@keyframes gradient {
    0% {
        background-position: 0% 50%;
    }
    50% {
        background-position: 100% 50%;
    }
    100% {
        background-position: 0% 50%;
    }
}

@keyframes example {
  from {background-color: red;}
  to {background-color: yellow;}
}

<!--
@keyframes example {
  0%   {background-color: red;}
  25%  {background-color: yellow;}
  50%  {background-color: blue;}
  100% {background-color: green;}
}
-->
 /* Dropdown Button */
.dropbtn {
  background-color: #04AA6D;
  color: white;
  padding: 16px;
  font-size: 16px;
  border: none;
}

/* The container <div> - needed to position the dropdown content */
.dropdown {
  position: relative;
  display: inline-block;
}

/* Dropdown Content (Hidden by Default) */
.dropdown-content {
  display: none;
  position: absolute;
  background-color: #f1f1f1;
  min-width: 160px;
  box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
  z-index: 1;
}

/* Links inside the dropdown */
.dropdown-content a {
  color: black;
  padding: 12px 16px;
  text-decoration: none;
  display: block;
}

/* Change color of dropdown links on hover */
.dropdown-content a:hover {background-color: #ddd;}

/* Show the dropdown menu on hover */
.dropdown:hover .dropdown-content {display: block;}

/* Change the background color of the dropdown button when the dropdown content is shown */
.dropdown:hover .dropbtn {background-color: #3e8e41;} 


/* Place the navbar at the bottom of the page, and make it stick */
.navbar {
  background-color: #333;
  overflow: hidden;
  position: fixed;
  width: 100%;
  vertical-align: top;
  margin-top: 0px;
}

/* Style the links inside the navigation bar */
.navbar a {
  float: left;
  display: block;
  color: #f2f2f2;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
  font-size: 17px;
}

/* Change the color of links on hover */
.navbar a:hover {
  background-color: #ddd;
  color: black;
}

/* Add a color to the active/current link */
.navbar a.active {
  background-color: #04AA6D;
  color: white;
}


</style>

    
</head>
<body>
<div align="center">
 <div class="navbar">
  <a href="#home" class="active">Home</a>
  <a href="#news">News</a>
  <a href="#contact">Contact</a>
</div> 
 <button class="button button1">Click Me!</button> 
 <button class="button button1">Click Me!</button> 
 <button class="button button1">Click Me!</button> 
 <button class="button button1">Click Me!</button> 
 
 <div class="dropdown">
  <button class="dropbtn">Dropdown</button>
  <div class="dropdown-content">
    <a href="https://github.com/SeanKuehl">Link 1</a>
    <a href="https://github.com/SeanKuehl">Link 2</a>
    <a href="https://github.com/SeanKuehl">Link 3</a>
  </div>
</div> 
 </div>


<h1> Welcome To Sean Kuehl's Website!</h1>
<p id="time"></p>

<p> This website has ambiance music, press play to enable it</p>



<div align="center">
<audio controls autoplay loop>
<source src="doodle.mp3">
Your browser does not support the audio tag.
</audio>
</div>

<div align="center">
<img src="me.jpg"></img>
</div>

<!-- music attribution: https://opengameart.org/content/doodle-menu-like-song -->

<p>Hello, my name is Sean Kuehl, a software and tech enthusiast currently working towards my bachelors in computer science at Conestoga College.<br>
   For me, it all began when at a young age I thought about what I wanted to do for a living. The saying "if you do what you love, <br>
   you'll never work a day in your life" came to mind. I thought to myself "well, I love video games but a video game tester isn't a full-time job,<br>
   so instead I'll make video games!".
</p>

<img src="Drago.png" id = "test"></img>

<script>
<!-- javascript is asynchronus, so if there's something after the wait it will do it while waiting, doesn't wait for last command-->
<!-- this is a basic, rudamentary "animation", once I get real images I can make something neat-->
var listOfImages = ["Dan.png", "Background.png", "Drago.png"];
var index = 0;

function testFunc(){
	
	document.getElementById("test").src = listOfImages[index];
	index += 1;
	
	if (index > 2){
		index = 0;
	}
	
	setTimeout(testFunc, 2000);
	
}

testFunc();




</script>


<script>
class HelloMessage extends React.Component {
  render() {
    return React.createElement(
      "div",
      null,
      "Hello ",
      this.props.name
    );
  }
}

ReactDOM.render(React.createElement(HelloMessage, { name: "Taylor" }), document.getElementById('hello-example'));


</script>

<script>
<!-- this code will run on 'startup', if I want something to happen on a button press -->
<!--I would have to add 'onclick="java script or just func call"' to do it -->

document.getElementById("time").innerHTML = "Accessed on: "+Date();
</script>

 <!--<a href="https://github.com/SeanKuehl" class="button button">My Github</a>-->
<!-- also have a button that goes to my LinkedIn-->
<!-- give the image a top margin of something, easiest supported way to do spacing-->


</body>
</html>
