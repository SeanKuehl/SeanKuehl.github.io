
<!--
this is for a vertical scrolling thing, will need some modification for my uses
style:
div.ex1 {
  background-color: lightblue;
  height: 40px;
  width: 200px;
  overflow-y: scroll;
}

use in body:
<div class="ex1">Lorem ipsum dolor sit amet, consectetur adipiscing elit. 
Etiam semper diam at erat pulvinar, at pulvinar felis blandit. Vestibulum 
volutpat tellus diam, consequat gravida libero rhoncus ut.</div>


also explore this:
https://blog.hubspot.com/website/html-dropdown

-->


<html lang="en"> <!-- Set this to the main language of your site -->
<head>
    <meta charset="utf-8">

    <title>Sean Kuehl</title>

    <!-- Enter a brief description of your page -->
    <meta name="description" content="Welcome to my page!">

<style>


section {
  float: left;
}


div {
  margin-bottom: 200px;
}

p {
  font-size: 25px;
  font-family: "Trebuchet MS", sans-serif;

}

li {
  font-size: 25px;
  font-family: "Trebuchet MS", sans-serif;
  margin-bottom: 20px;
}

<!-- I'll seperate things with witespace by using divs, couldn't find a better option-->
<!-- I need to flesh out, stylize elements and complete the page but I have the basics down-->
</style>

    
</head>
<body>




<!-- this is the title and paragraph that will introduce me and what the website has to offer-->
<div align="center">

<section>
<h1> Sean Kuehl </h1>
</section>

<section>
<a href="HomePage.html">
<button>Blogs</button>
</a>
</section>

</div>



<div align = "center">
<p> Here is an example of a game I made. It's a puzzle game where you have to find bugs in code. Try it out!</p>

<!-- I got this embed code from itch.io itself under the distribute->embed. This worked like a charm!-->
<iframe src="https://itch.io/embed-upload/5284568?color=333333" allowfullscreen="" width="640" height="380" frameborder="0"><a href="https://seankuehl.itch.io/spot-the-bug">Play Spot The Bug! on itch.io</a></iframe>

</div>


<div align = "center">
<!-- maybe put a header hear to mark "about me"-->
<img src="MeForWebsite.jpg" alt="Picture of me">

<p> From a young age I was hooked on video games, and it's what got me interested in programming and technology.
Now I'm pursuing a Bachelors degree in Computer Science at Conestoga College, learning a lot and doing my best.
I still find time to work on my own projects and learn new technologies to keep my mind and my skills sharp.
I'm constantly exploring and looking to create new opportunities, which is part of the reason I'm hosting my own website.
Strategy games, digital art and writing are some of my other hobbies that I explore outside of personal projects.</p>

</div>


<div align = "center">
<h1> Contact/Portfolio </h1>
<!-- itchio, github, linkedin, official gmail, phone, say preferred method is email-->

<h2> Portfolio </h2>
<ul>
<li> Check out my <a href="https://seankuehl.itch.io/">Itch.io</a> </li>
<li> Check out my <a href="https://github.com/SeanKuehl">Github</a> </li>
</ul>

<h2> Contact </h2>
<ul>
<li> I prefer to be reached by email at <a href="seanliamkuehl@gmail.com">seanliamkuehl@gmail.com</a> </li>
<li> I can also be reached by phone at <a href="tel:+519-210-0874">519-210-0874</a> although someone else or no one may answer</li>
<li> You can find my LinkedIn profile <a href="https://www.linkedin.com/in/sean-kuehl-720611219/"> Here</a> </li>
</ul>


</div>




</body>
</html>
