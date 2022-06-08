<!DOCTYPE html>

<html>
<head>
    <title>SSB Home Work</title>

    <style>
        aside {
          width: 30%;
          padding-left: 15px;
          margin-left: 15px;
          float: right;
          font-style: italic;
          background-color: lightgray;
        }


        table, th, td {
        border: 1px solid black;
        }
        </style>

</head>
<body style="background-color: aqua;">

<h1>The a element</h1>

<a href="https://www.w3schools.com">Visit W3Schools.com!</a>

<h1>The abbr element</h1>

<p>The <abbr title="World Health Organization">WHO</abbr> was founded in 1948.</p>

<address>
    Written by <a href="mailto:webmaster@example.com">Jon Doe</a>.<br>
    Visit us at:<br>
    Example.com<br>
    Box 564, Disneyland<br>
    USA
    </address>
    <br><br>

    <h1>The map and area elements</h1>

<p>Click on the computer, the phone, or the cup of coffee to go to a new page and read more about the topic:</p>

<img src="london.jpg" alt="Workplace" usemap="#workmap" width="400" height="379">

<map name="workmap">
  <area shape="rect" coords="34,44,270,350" alt="Computer" href="computer.htm">
  <area shape="rect" coords="290,172,333,250" alt="Phone" href="phone.htm">
  <area shape="circle" coords="337,300,44" alt="Cup of coffee" href="coffee.htm">
</map>
<br><br><br><br>

<h1>The article element</h1>

<article>
  <h2>Google Chrome</h2>
  <p>Google Chrome is a web browser developed by Google, released in 2008. Chrome is the world's most popular web browser today!</p>
</article>

<article>
  <h2>Mozilla Firefox</h2>
  <p>Mozilla Firefox is an open-source web browser developed by Mozilla. Firefox has been the second most popular web browser since January, 2018.</p>
</article>

<article>
  <h2>Microsoft Edge</h2>
  <p>Microsoft Edge is a web browser developed by Microsoft, released in 2015. Microsoft Edge replaced Internet Explorer.</p>
</article>
<br><br><br>


<h1>The aside element</h1>

<p>My family and I visited The Epcot center this summer. The weather was nice, and Epcot was amazing! I had a great summer together with my family!</p>

<aside>
  <h4>Epcot Center</h4>
  <p>Epcot is a theme park at Walt Disney World Resort featuring exciting attractions, international pavilions, award-winning fireworks and seasonal special events.</p>
</aside>
<br><br><br>

<h1>The base element</h1>

<p><img src="images/stickman.gif" width="24" height="39" alt="Stickman"> - Notice that we have only specified a relative address for the image. Since we have specified a base URL in the head section, the browser will look for the image at "https://www.w3schools.com/images/stickman.gif".</p>

<p><a href="tags/tag_base.asp">HTML base tag</a> - Notice that the link opens in a new window, even if it has no target="_blank" attribute. This is because the target attribute of the base element is set to "_blank".</p>



<div>
    <h1>The audio element</h1>

<p>Click on the play button to play a sound:</p>

<audio controls>
  <source src="horse.ogg" type="audio/ogg">
  <source src="horse.mp3" type="audio/mpeg">
  Your browser does not support the audio element.
</audio>
</div>

<a href="https://www.w3schools.com/html/" accesskey="h">HTML tutorial</a><br>
<a href="https://www.w3schools.com/css/" accesskey="c">CSS tutorial</a>

<p>The accesskey attribute specifies a shortcut key to activate/focus an element.</p>
<p><strong>Note:</strong> The shortcut is varying in different browsers:</p>
<ul>
    <li>Edge, IE, Chrome, Safari, Opera 15+: [ALT] + <em>accesskey</em></li>
    <li>Opera prior version 15: [SHIFT] [ESC] + <em>accesskey</em></li>
    <li>Firefox: [ALT] [SHIFT] + <em>accesskey</em></li>
</ul>

    <br><br><br>

    <h1>The map and area elements</h1>

<p>Click on the computer, the phone, or the cup of coffee to go to a new page and read more about the topic:</p>

<img src="workplace.jpg" alt="Workplace" usemap="#workmap" width="400" height="379">

<map name="workmap">
  <area shape="rect" coords="34,44,270,350" alt="Computer" href="computer.htm">
  <area shape="rect" coords="290,172,333,250" alt="Phone" href="phone.htm">
  <area shape="circle" coords="337,300,44" alt="Cup of coffee" href="coffee.htm">
</map>

<br><br><br>

<h1>The b element</h1>

<p>This is normal text - <br>
    <b>and this is bold text</b>.</p

    <h1>The bdi element</h1>

<p>In the example below, usernames are shown along with the number of points in a contest. If the bdi element is not supported in the browser, the username of the Arabic user would confuse the text (the bidirectional algorithm would put the colon and the number "90" next to the word "User" rather than next to the word "points").</p>

<ul>
 <li>User <bdi>hrefs</bdi>: 60 points</li>
 <li>User <bdi>jdoe</bdi>: 80 points</li>
 <li>User <bdi>إيان</bdi>: 90 points</li>
</ul>

<h1>The bdo element</h1>

<p>This paragraph will go left-to-right.</p>  
<p><bdo dir="rtl">This paragraph will go right-to-left.</bdo></p>  

<br><br><br>
<h1>The blockquote element</h1>

<p>Here is a quote from WWF's website:</p>

<blockquote cite="http://www.worldwildlife.org/who/index.html">
For 50 years, WWF has been protecting the future of nature. The world's leading conservation organization, WWF works in 100 countries and is supported by 1.2 million members in the United States and close to 5 million globally.
</blockquote>

<br><br><br>
<h1>The button Element</h1>

<button type="button" onclick="alert('Hello world!')">Click Me!</button>

<br><br><br>

<h1>The canvas element</h1>

<canvas id="myCanvas">Your browser does not support the canvas tag.</canvas>

<script>
var c = document.getElementById("myCanvas");
var ctx = c.getContext("2d");
ctx.fillStyle = "#FF0000";
ctx.fillRect(10, 5,90, 100);
</script>
<br><br>

<h1>The col element</h1>

<table>
  <colgroup>
    <col span="2" style="background-color:red">
    <col style="background-color:yellow">
  </colgroup>
  <tr>
    <th>ISBN</th>
    <th>Title</th>
    <th>Price</th>
  </tr>
  <tr>
    <td>3476896</td>
    <td>My first HTML</td>
    <td>$53</td>
  </tr>
  <tr>
    <td>5869207</td>
    <td>My first CSS</td>
    <td>$49</td>
  </tr>
</table>

<table style="width:100%">
    <tr>
      <th>ISBN</th>
      <th>Title</th>
      <th>Price</th>
    </tr>
    <tr>
      <td>3476896</td>
      <td>My first HTML</td>
      <td style="text-align:right">$53</td>
    </tr>
    <tr>
      <td>2489604</td>
      <td>My first CSS</td>
      <td style="text-align:right">$47</td>
    </tr>
  </table>
  <br><br><br>
  <h1>The var element</h1>

<p>The area of a triangle is: 1/2 x <var>b</var> x <var>h</var>, where <var>b</var> is the base, and <var>h</var> is the vertical height.</p>
<br><br>
<h1>The cite element</h1>

<img src="img_the_scream.jpg" width="220" height="277" alt="The Scream">
<p><cite>The Scream</cite> by Edward Munch. Painted in 1893.</p>
<br><br><br>

<h1>The caption element</h1>

<table>
  <caption>Monthly savings</caption>
  <tr>
    <th>Month</th>
    <th>Savings</th>
  </tr>
  <tr>
    <td>January</td>
    <td>$100</td>
  </tr>
  <tr>
    <td>February</td>
    <td>$50</td>
  </tr>
</table>

</body>
</html>
