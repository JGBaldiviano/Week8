# Week8 - index.html
<!DOCTYPE html>
<html lang="em">
    <head>
        <link href="assets/style.css" rel="stylesheet" />
        <title>The Basic Language of the Web: HTML</title>
    </head>

    <body>
        <div>
            <header class="header-container">
              📘<h1>
                    THE CODE MAGAZINE
                    <nav>
                        <a class="links" href="Blog.html"> Blog</a> 
                        <a class="links" href="Challenges.html">Challenges</a> 
                        <a class="links" href="Flexbox.html">Flexbox</a> 
                        <a class="links" href="CSS.html">CSS Grid</a> 
                    </nav>
                </h1>
            </header>
                    
        <article class="article-container">
            <header>
                <button class="button1">TOP</button>

                <h2>The Basic Language of the Web: HTML</h2>
                    <p> 
                        <img src = "laura-jones.jpg" width="30" length="30"/>
                        <i>Posted by <strong>Laura Jones</strong> on Monday, June 21st 2027</i>
                    </p>
                    <p>
                        <img src = "post-img.jpg" width="500" length="200"/>
                        <p> </p>
                        All modern website and web application are built using three fundamental technologies: 
                        HTML, CSS, and JavaScript. These are the Languages of the web.
                    </p>
                    <p>
                        In this post, let's focus on HTML. We will learn what HTML is all about ,and why you too should learn it.
                    </p>

                <h3>What is HTML?</h3>
                    <p>
                        HTML, stands for <strong>H</strong>yper<strong>T</strong>ext <strong>M</strong>arkup <strong>L</strong>anguage. It is a markup language that web developers use to structure and describe the content of a webpage (not a programming language).
                        <p> </p>
                        HTML, consist of elements that describe different types of content: paragraphs, links, headings images, video, etc. Web Browser understand HTML and render HTML code as websites.
                        <p> </p>
                        In HTML, each elements id made up of 3 parts:
                        <ol>
                            <li>The opening tag</li>
                            <li>The closing tag</li>
                            <li>The actual element.</li>
                        </ol> 
                        You can learn more at <a style="text-decoration: none;" href="MDN Web Docs.html">MDN Web Docs.</a>
                    </p>

                <h3>Why should you learn HTML?</h3>
                    <p>
                        There are countless reasons for learning for learning the fundamental languages of the wed. Here are 5 of them:
                        <ul>
                            <li>To be able to use fundamental web dev language.</li>
                            <li>To hand-craft beautiful websites instead of relying on tools like Workpress or Wix.</li>
                            <li>To build web applications</li>
                            <li>To impress friends.</li>                                    
                            <li>To have fun 😁</li>
                        </ul>
                        Hopefully you learned something new here. See you next time!
                    </p>
            </header>
        </article>

        <aside class="aside-container">
            <header><h4>RELATED POSTS</h4></header>
                <ul>
                    <li class="li_noBullets"><img src = "related-1.jpg" width="50" length= "50" style="float: left; margin-right: 10%; margin-left: 10%;"/> 
                        <a  href="How to Learn Web Development.html" style="text-decoration: none; font-weight: bold;">How to Learn Web Development</a><p>By Jonas Schmedtmann</p>
                    </li> 
                    <li class="li_noBullets"><img src = "related-2.jpg"width="50" length="50" style="float: left; margin-right: 10%; margin-left: 10%;"/> 
                        <a href="The Unknown Power of CSS.html" style="text-decoration: none; font-weight: bold;">The Unknown Power of CSS</a><p>By Jim Dillon</p>
                    </li>
                    <li class="li_noBullets"><img src = "related-3.jpg"width="50" length="50" style= "float: left; margin-right: 10%; margin-left: 10%;"/> 
                        <a href="Why JavaScript is Awesome.html" style="text-decoration: none; font-weight: bold;">Why JavaScript is Awesome</a><p>By Matilda</p>
                    </li> 
                </ul>
        </aside>

        <footer class="footer-container">
            <p>Copyright @ 2027 by the Code Magazine</p>
        </footer>
        <button class="button2">❤ Like</button>
        </div>
    </body>
</html>


# Week8 - style.css
html {
  border: 5px solid;
  border-left: 0px;
  border-right: 0px;
  border-bottom: 0px;
  border-top-color: darkcyan;
}

body {
  font-family: sans-serif;
  max-width: 800px;
  margin: auto;
  font-size: 14px;
}

.header-container {
  max-width: 800px;
  margin: auto;
  float: center;
  background-color: whitesmoke;
  color: darkcyan;
  padding: 10px 10px;
  padding-left: 20px;
  padding-right: 20px;
}

h1 {
  font-style: italic;
  font-weight: bolder;
  font-size: 16px;
  display: inline;
}

nav {
  font-size: 14;
  float: right;
}

.links {
  margin-left: 20px;
  text-decoration: none;
}

a:link {
  color: darkcyan;
  font-size: 12px;
}

a:active {
  color: red;
}

a:hover {
  color: orange;
}

a:visited {
  color: green;
}

.article-container {
  position: relative;
  top: 20px;
  bottom: 50px;
  padding-left: 0px;
  padding-right: 0px;
  max-width: 500px;
  margin: auto;
  float: left;
  line-height: 1.5;
}

h2 {
  color: darkcyan;
  font-weight: bolder;
  font-size: 20px;
}

h3 {
  color: darkcyan;
  font-weight: bolder;
  font-size: 16px;
}

.button1 {
  float: right;
  border: none;
  margin: auto;
  color: black;
  padding: 2px 5px;
  font-weight: bold;
  font-size: 10px;
  background-color: gold;
}

.article-container li:first-child {
  font-weight: bold;
}

.article-container li:last-child {
  font-style: italic;
}

.aside-container {
  position: relative;
  top: 50px;
  padding-top: 20px;
  background-color: whitesmoke;
  border: 5px solid darkcyan;
  border-left: 0px;
  border-right: 0px;
  max-width: 250px;
  margin: auto;
  float: right;
}

h4 {
  font-weight: bolder;
  font-size: 16px;
  text-align: center;
}

.li_noBullets {
  text-decoration: none;
  list-style-type: none;
  padding: 0px 0px;
  font-size: 12px;
  margin-right: 15%;
  padding-bottom: 50px;
  line-height: 1;
  padding-block: 15;
}

.li_noBullets p {
  margin: 0;
  padding: 0;
  font-style: italic;
  font-size: 11px;
}

.footer-container {
  font-size: 10px;
  position: fixed;
  bottom: 0px;
  padding-left: 0px;
  padding-right: 0px;
  max-width: 500px;
  margin: auto;
  background-color: whitesmoke;
  padding: 0px 0px;
}

.button2 {
  position: fixed;
  bottom: 30px;
  right: 30px;
  float: right;
  padding: 5px 5px;
  font-weight: bold;
  font-size: 12px;
  background-color: whitesmoke;
}

.button2:hover {
  background-color: pink;
}
