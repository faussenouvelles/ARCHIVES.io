<html>
    <body>
<body class="text-right">
<body style="height:100%;background-color:#fcfcf7;display:flex;color:#2F4F4F;font-family:'PT Sans Caption', sans-serif;text-shadow:0 .05rem .1rem rgba(187, 7, 160, 0.5);box-shadow:inset 0 0 5rem rgba(250, 248, 250, 0.5);background:url('00.jpg') no-repeat center center fixed;-webkit-background-size:cover;-moz-background-size:cover;background-size:cover;-o-background-size:cover;">
<link style="padding: .25rem 0;font-weight: 700;color: rgba(133, 79, 141, 0.675);background-color: transparent;border-bottom: .25rem solid transparent">
    <div class="cover-container d-flex w-100 h-100 p-3 mx-auto flex-column">
  <header class="masthead mb-auto text-center">
    <div class="inner">
      <h1 class="masthead-brand">Massachusettes Institute of Technology · Archives 2022 · </h1>
      <br>
      <nav class="nav nav-masthead justify-content-center">
        <a class="nav-link active" href="https://faussenouvelles.github.io/PORTFOLIO.io/">MAIN</a>
        <a class="nav-link" href="https://faussenouvelles.github.io/PROJECTS.io/">PROJECTS</a>
        <a class="nav-link" href="https://faussenouvelles.github.io/ARCHIVES.io/">ARCHIVES</a>
      </nav>
    </div>
  </header>
  <br>
<p><em>This web document is comprised of the code archives assigned to design & develop in accordance to the activities & practices alongside the Women's Coding Certificate at Massachusettes Institute of Technology 2022. </em></p>
<p><em>We have been working towards better developing with Javascript ( JS ), Hypertext Markup Language ( HTML ), and Cascading Style Sheets ( CSS )</em></p>
<br>
<br>
<h2 id="table-of-contents">· Table of Contents · </h2>
<ol style="float:right; text-align:right; list-style:none;">
    <li><a href="#CSS Files">CSS Files</a> · </li>
    <li><a href="#Pacman">Pacman Factory</a> · </li>
    <li><a href="#Eyes">Eye Movement Activity</a> · </li>
</ol>
<br>
<br>
<h3 id="CSS Files"> · CSS FILES · </h3>
<br>
<ul style="float:right; text-align:right; list-style:none;">
    <li>
        <h5>Stylized Coffeeshop Menu Codes</h5>
        <br>
<html>
 <head>
    <style>
    {
        box-sizing: border-box;
    }
    /* Set additional styling options for the columns*/
    .column {
    float: left;
    width: 50%;
    border-style: solid;
    border-width: 7px;
    border-color: #aee8f742;
    border-top-style: none;
  border-right-style: solid;
  border-bottom-style: none;
  border-left-style: dotted;
  border-left-width: 1.5px;
  border-left-color: #02083074;
    }

    .row:after {
    content: "";
    display: table;
    clear: both;
    }
    </style>
 </head>
 <body>
    <div class="row">
        <div class="column" style="background-color:#aee8f774;">

            <p style="font-size: 14">embedding CSS to HTML Files · </p>
                <p style="font-size: 10"> < html > 
                <br> < head >
                <br> < link rel="stylesheet" href="./Introducing Styles to HMTL.css" >
                <br> < /head > 
            <br> < /html > 
        </p>
            <p style="font-size: 14">styling links within HTML · </p>
            <p style="font-size: 10"> < div class="content" > 
            <br> < p > CSS brings HTML to life. You can even style this
            <br> < a href="#"> link < /a > ! < /p >
            <br> < /div >
        <br> < /html > 
        <br>        
        <br> the use of the "#" is to refer, though you may 
        <br> replace "#" · coding your link within this space.
        </p>
        <p style="font-size: 14">styling lists within HTML · </p>
        <p style="font-size: 10"> < h3 > This list can be styled as well: < /h3 >
            <br> < ul >
            <br> < li > Drink Coffee < /li >
            <br> < li class="active" > Code < /li>
            <br> < li > Drink Coffee < /li >
            <br> < li > Repeat < /li >
            <br> < /ul > 
        </p>
         


        </div>
        <div class="column" style="background-color:#aee8f774;">
            <p style="font-size: 14">stylizing web documents with CSS · </p>
            <p style="font-size: 10">h1 {   
                    <br>    color: #0170FF }
                    <br>  
                    <br>  a {
                        <br>    color: #FF0101 }
                        <br>  
                        <br>  li {
                            <br>    border-left: 5px solid #005cfc;
                            <br>    background-color: #f1f1f1;
                            <br>    list-style-type: none;
                            <br>    padding: 10px 20px;}
                            <br>  
                            <br>  .content {
                                <br>    padding: 20px;
                                <br>    margin: 10px;
                                <br>    background-color: #424EDC;
                                <br>    color: #fff;
                                <br>    font-style: italic; }
                                <br>  
                                <br>  .active {
                                    <br>    border-left: 5px solid #01e4FF;}
                                    <br>  
                                    <br>  .footer {
                                        <br>    padding: 20px;
                                        <br>    margin: 10px;
                                        <br>   background-color: #424EDC;
                                        <br>    color: #fff;
                                        <br>    text-align: center;}
            </p>
        </div>
    </div>
 </body>
</html>
        <p>This has been adapted from MIT Week 8 · Working With CSS & HTML </p>
        <p>Below is the direct link to Github Codes</p>
        <h6>
            <a href="https://github.com/faussenouvelles/stylized-coffee-shop.io/blob/main/Introducing%20Styles%20to%20HTML.html"> ❧ STYLIZED COFFEE MENU.HTML</a>
 · <a href="https://github.com/faussenouvelles/stylized-coffee-shop.io/blob/main/Introducing%20Styles%20to%20HMTL.css"> ❧ STYLIZED COFFEE MENU.CSS</a></h6>
    </li>
<br>
<br>
    <li>
        <h5>Holy Grail · Web Developer Basics</h5>
        <br>
        <html>
            <head>
               <style>
               {
                   box-sizing: border-box;
               }
               /* Set additional styling options for the columns*/
               .column {
               float: left;
               width: 50%;
               border-style: solid;
               border-width: 7px;
               border-color: #aee8f742;
               border-top-style: none;
             border-right-style: solid;
             border-bottom-style: none;
             border-left-style: dotted;
             border-left-width: 1.5px;
             border-left-color: #02083074;
               }
           
               .row:after {
               content: "";
               display: table;
               clear: both;
               }
               </style>
            </head>
            <body>
               <div class="row">
                   <div class="column" style="background-color:#aee8f774;">
           
                       <p style="font-size: 14">how to create the Holy Grail format in HTML · </p>
                           <p style="font-size: 10">< html >
                            <br>
                            <br>< head >
                            <br>    < link rel="stylesheet" href="./Holy Grail.css" >
                            <br>< /head >
                            <br>
                            <br>< body id="main" >
                            <br>    < div class="wrapper" >
                            <br>        < div class="box header" > Header < /div >
                            <br>        < div class= "box sidebar" > Sidebar < /div>
                            <br>        < div class= "box content" > Content
                            <br>            < br/ > This is the main area for content < /div >
                            <br>        < div class="box footer" > Footer < /div >
                            <br>    < /div >
                            <br>< /body >
                            <br>
                            <br>< /html >
                   </p>
                    
           
           
                   </div>
                   <div class="column" style="background-color:#aee8f774;">
                       <p style="font-size: 14">stylizing web documents with CSS · </p>
                       <p style="font-size: 10">h1 {   
                               <br>    color: #0170FF }
                               <br>  
                               <br>  a {
                                   <br>    color: #FF0101 }
                                   <br>  
                                   <br>  li {
                                       <br>    border-left: 5px solid #005cfc;
                                       <br>    background-color: #f1f1f1;
                                       <br>    list-style-type: none;
                                       <br>    padding: 10px 20px;}
                                       <br>  
                                       <br>  .content {
                                           <br>    padding: 20px;
                                           <br>    margin: 10px;
                                           <br>    background-color: #424EDC;
                                           <br>    color: #fff;
                                           <br>    font-style: italic; }
                                           <br>  
                                           <br>  .active {
                                               <br>    border-left: 5px solid #01e4FF;}
                                               <br>  
                                               <br>  .footer {
                                                   <br>    padding: 20px;
                                                   <br>    margin: 10px;
                                                   <br>   background-color: #424EDC;
                                                   <br>    color: #fff;
                                                   <br>    text-align: center;}
                       </p>
                   </div>
               </div>
            </body>
           </html>
           <br>
        <p>This has been adapted from MIT Week 8 · Working With CSS & HTML</p>
        <p>Below is the direct link to Github Codes</p>
        <h6>
            <a href="https://github.com/faussenouvelles/holy-grail.io/blob/main/Holy%20Grail.html"> ❧ HOLY GRAIL.HTML</a>
 · <a href="https://github.com/faussenouvelles/holy-grail.io/blob/main/Holy%20Grail.css"> ❧ HOLY GRAIL FORMAT.CSS</a></h6>
    </li>
</ul>
<br>
<br>
<h3 id="Pacman"> · Pacman Factory · </h3>
<br>
<ul style="float:right; text-align:right; list-style:none;">
    <li>
        <h5>Pacman Factory · Javascript & HTML Codes</h5>
        <br>
        <html>
            <head>
               <style>
               {
                   box-sizing: border-box;
               }
               /* Set additional styling options for the columns*/
               .column {
               float: left;
               width: 50%;
               border-style: solid;
               border-width: 7px;
               border-color: #aee8f742;
               border-top-style: none;
             border-right-style: solid;
             border-bottom-style: none;
             border-left-style: dotted;
             border-left-width: 1.5px;
             border-left-color: #02083074;
               }
           
               .row:after {
               content: "";
               display: table;
               clear: both;
               }
               </style>
            </head>
            <body>
               <div class="row">
                   <div class="column" style="background-color:#aee8f774;">
           
                        <p style="font-size: 14">Pacman Factory Javascript · </p>
                           <p style="font-size: 10"> let pos = 0;
                               <br>const pacArray = [
                               <br>['./images/PacMan1.png', './images/PacMan2.png'],
                               <br>['./images/PacMan3.png', './images/PacMan4.png'],
                               <br>];
                               <br>let direction = 0;
                               <br>const pacMen = []; // This array holds all the pacmen
                               <br>function setToRandom(scale) {
                               <br>return {
                               <br>x: Math.random() * scale,
                               <br>y: Math.random() * scale,
                               <br>};
                               <br>}
                               <br>function makePac() {
                               <br>// returns an object with random values scaled {x: 33, y: 21}
                               <br>let velocity = setToRandom(10); // {x:?, y:?}
                               <br>let position = setToRandom(200);
                               <br>let game = document.getElementById('game');
                               <br>let newimg = document.createElement('img');
                               <br>newimg.style.position = 'absolute';
                               <br>newimg.src = './images/PacMan1.png';
                               <br>newimg.width = 100;
                               <br>
                       <br>newimg.style.left = position.x;
                       <br>newimg.style.top = position.y;
                       <br>game.appendChild(newimg);
                       <br>return {
                       <br>position,
                       <br>velocity,
                       <br>newimg,
                       <br>};
                       <br>}
                       <br>function update() {
                        <br>pacMen.forEach((item) => {
                        <br>checkCollisions(item);
                        <br>item.position.x += item.velocity.x;
                        <br>item.position.y += item.velocity.y;
                        <br>item.newimg.style.left = item.position.x;
                        <br>item.newimg.style.top = item.position.y;
                        <br>});
                        <br>setTimeout(update, 20);
                        <br>}
                   </p>
                   </div>
                   <div class="column" style="background-color:#aee8f774;">
                    <p style="font-size: 10">
                        <br>
                        <br>
                        <br>function checkCollisions(item) {
                        <br>if(
                        <br>item.position.x + item.velocity.x + item.newimg.width > window.innerWidth
                        <br>||
                        <br>item.position.x + item.velocity.x < 0
                        <br>)
                        <br>item.velocity.x = -item.velocity.x;
                        <br>if (
                        <br>item.position.y + item.velocity.y + item.newimg.height > window.innerHeight
                        <br>||
                        <br>item.position.y + item.velocity.y < 0
                        <br>)
                        <br>item.velocity.y = -item.velocity.y;
                        <br>}
                        <br>function makeOne() {
                        <br>pacMen.push(makePac()); // add a new PacMan
                        <br>}
                        <br>if (typeof module !== 'undefined') {
                        <br>module.exports = { checkCollisions, update, pacMen };
                        <br>}
                        </p>
                        <br>
                        <p style="font-size: 14">Pacman Factory HTML · </p>
                        <p style="font-size: 10">< html >
                         <br>< head >
                         <br>    < title > Pacmen < /title >
                         <br>< /head >
                         <br>< body >
                         <br>    < div id='game' >
                         <br>       < button onclick='makeOne()' width='200' height='30'>Add PacMan< /button >
                         <br>       < button onclick='update()' width='200' height='30'>Start Game< /button >
                         <br>    < /div >
                         <br>    < script src="./pacmen.js" >< /script >
                         <br> < /body >
                         <br>< /html >
                     </p>
                   </div>
               </div>
            </body>
           </html>
           <br>
        <p>This style guide has been adapted from MIT Week 7 · Pacman Factory</p>
        <h6><a href="https://github.com/faussenouvelles/pacman-factory.io/blob/main/week%207%20-%20pacman%20factory.js"> ❧ PACMAN FACTORY. JS</a>
        · <a href="https://github.com/faussenouvelles/pacman-factory.io/blob/main/week%207%20-%20pacman%20factory.html"> ❧ PACMAN FACTORY.HTML</a></h6>
<br>
        <h6><a href="https://faussenouvelles.github.io/pacman-factory.io/"> ❧ PACMAN FACTORY · ❧ VIDEOGAME</a></h6>
    </li>
</ul>
<br>
<h3 id="Eyes"> · Eye Movement Activity · </h3>
<ul style="float:right; text-align:right; list-style:none;">
    <li>
        <html>
            <head>
               <style>
               {
                   box-sizing: border-box;
               }
               /* Set additional styling options for the columns*/
               .column {
               float: left;
               width: 50%;
               border-style: solid;
               border-width: 7px;
               border-color: #aee8f742;
               border-top-style: none;
             border-right-style: solid;
             border-bottom-style: none;
             border-left-style: dotted;
             border-left-width: 1.5px;
             border-left-color: #02083074;
               }
           
               .row:after {
               content: "";
               display: table;
               clear: both;
               }
               </style>
            </head>
            <body>
               <div class="row">
                   <div class="column" style="background-color:#aee8f774;">
           
                       <p style="font-size: 14">Eye Movement Javascript Code · </p>
                           <p style="font-size: 10">const balls = document.getElementsByClassName('ball');
                            <br>
                            <br>document.onmousemove = (event) => {
                                <br>  const x = (event.clientX * 100) / window.innerWidth + '%';
                                <br>  const y = (event.clientY * 100) / window.innerHeight + '%';
                                <br>
                                <br>  for (let i = 0; i < 2; i++) {
                                    <br>  balls[0].style.left = x;
                                    <br>  balls[0].style.top = y;
                                    <br>  balls[0].transform = 'translate(-' + x + ',-' + y + ')';
                                    <br>  }
                                    <br>};
                        </p>
                            <p style="font-size: 14">Eye Movement HTML Code · </p>
                            <p style="font-size: 10"> < html >
                            <br>    < head >
                            <br>        < link rel="stylesheet" type="text/css" href="./styles.css" >
                            <br>    < /head >
                            <br>    < body >
                            <br>        < div class="eyes" >
                            <br>            < div class="eye" >
                            <br>                < div class="ball" > < /div >
                            <br>            < /div >
                            <br>           < div class="eye" >
                            <br>                < div class="ball" > < /div >
                            <br>            < /div >
                            <br>       < /div >
                            <br>        < script src="./eyes.js" > < /script. >
                            <br>    < /body >
                            <br>< /html >
                            </p>
                   </div>
                   <div class="column" style="background-color:#aee8f774;">
                    <p style="font-size: 14">Eye Movement CSS Code · </p>
                    <p style="font-size: 10">body {
                    <br>    margin: 0;
                    <br>    padding: 0;
                    <br>    background: #14495e;
                    <br>  }
                    <br>  .eyes {
                    <br>    position: absolute;
                    <br>    top: 50%;
                    <br>    transform: translateY(-50%);
                    <br>    width: 100%;
                    <br>    text-align: center;
                    <br>  }
                    <br>  .eye {
                    <br>    width: 240px;
                    <br>    height: 120px;
                    <br>    background: #fff;
                    <br>    display: inline-block;
                    <br>    margin: 40px;
                    <br>    border-radius: 50%;
                    <br>    position: relative;
                    <br>    overflow: hidden;
                    <br>  }
                    <br>  .ball {
                    <br>    width: 80px;
                    <br>    height: 80px;
                    <br>    background: #000;
                    <br>    position: absolute;
                    <br>    top: 50%;
                    <br>    left: 50%;
                    <br>    transform: translate(-50%, -50%);
                    <br>    border-radius: 50%;
                    <br>  }
                       </p>
                   </div>
               </div>
            </body>
           </html>
        <br>>
        <p>This style guide has been adapted from MIT Week 8 · Eyes Movement Exercise</p>
        <h6><a href="https://github.com/faussenouvelles/eyes-movement.io/blob/main/eyes.js"> ❧ Eye Movement. JS</a>
            · <a href="https://github.com/faussenouvelles/eyes-movement.io/blob/main/index.html"> ❧ Eye Movement.HTML</a> · 
            <a href="https://github.com/faussenouvelles/eyes-movement.io/blob/main/styles.css"> ❧ Eye Movement.CSS</a></h6>
    </li>
</ul>
<br>
      <h2 id="-"><strong>function returnHome <a href="https://faussenouvelles.github.io/PORTFOLIO.io/">{ Main }</a></strong></h2>
<br>
<br>
<footer class="mastfoot mt-auto">
  <div class="inner">
    <p>Web Design for Massachusettes Institute of Technology Women's Coding Certificate Course <a href="https://executive-ed.xpro.mit.edu/professional-certificate-coding-womens-cohort"> MIT 2022</a>, by <a href="https://github.com/faussenouvelles">eletheia_sweet</a>.</p>
    <br>
    <br>
    <br>
    <br>      
    <p>
      MIT License

Copyright (c) 2022 fausse_nouvelles

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
</p>
      
    </div>
  </footer>
  </div>
<html>
