# Cutomized-Mondrian-Picture

<p>This is among projects since I stared to learn programming using the HTML and CSS.</p>

<p>You can see live preview on: <a href="https://negrut112.github.io/personalized-mondrian-picture/">https://negrut112.github.io/personalized-mondrian-picture/</a></p>

<img src="https://i.imgur.com/rDq1M31.jpg">

## HTML

<p>On HTML I wrapped inside the body tags the id-s of each quadrilateral shape, along some classes to specify their color.</p>

<pre><code>&lt;body&gt;<br>
&lt;div id=“canvas”&gt;<br>
&lt;div id=“first-row” class=“brown”&gt;<br>
&lt;div id=“big-rectangle” class=“red right”&gt;&lt;/div&gt;<br>
&lt;div id=“first-divider” class=“black”&gt;&lt;/div&gt;<br>
&lt;div id=“first-column” class=“right”&gt;<br>
&lt;div id=“first-medium-rectangle”&gt;&lt;/div&gt;<br>
&lt;div id=“second-divider” class=“black”&gt;&lt;/div&gt;<br>
&lt;div id=“second-medium-rectangle”&gt;&lt;/div&gt;<br>
&lt;/div&gt;<br>
&lt;div id=“second-row” class=“black”&gt;&lt;/div&gt;<br>
&lt;/div&gt;<br>
&lt;div id=“third-row”&gt;<br>
&lt;div id=“third-divider” class=“black”&gt;<br>
&lt;div id=“right-top” class=“blue”&gt;&lt;/div&gt;<br>
&lt;div id=“fourth-divider” class=“black”&gt;&lt;/div&gt;<br>
&lt;div id=“right-bot” class=“yellow”&gt;&lt;/div&gt;<br>
&lt;/div&gt;<br>
&lt;div id=“last-column” &gt;&lt;/div&gt;<br>
&lt;div id=“fifth-divider” class=“black”&gt;&lt;/div&gt;<br>
&lt;/div&gt;<br>
&lt;/body&gt;</code></rep>

## CSS

<p>First id represent the surface where I’m working with following characteristics:</p>

<pre><code>#canvas {
width: 400px;<br>
height: 400px;<br>
background-color: ivory;<br>
margin: 0 auto;<br>
box-shadow: 15px 15px 10px gray;<br>
}</code></pre>

<p>Further for the rest of id-s I described the color, position and their sizes expressed in percents. For ex:</p>

<pre><code>#first-column {<br>
height: 100%;<br>
width: 22%;<br>
background-color: rgba(0, 146, 204, 0.9);<br>
}</code></pre>
