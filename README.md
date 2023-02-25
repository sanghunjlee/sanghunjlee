<style>
ul.tasks {
    padding: 0px;
    width: 80%;
    margin: 0px auto;
}
ul li {
    border-radius: 4px;
    padding: 2px 8px;
}
ul li:hover {
    background-color: rgba(150, 150, 150, 0.5);
}
li.cancel {
    text-decoration: line-through;
}

select {
    cursor: grab;
    background-color: inherit;
    color: inherit;
    font-size: inherit;
    font-family: inherit;
    font-weight: inherit;
    padding: 2px;
    border: none;
    border-radius: 4px;
    text-align: center;
}
option {
    background-color: inherit;
    color: inherit;
}
img {
    border-radius: 8px;
}
div.kws {
    display: flex;
    align-content: center;
    justify-content: center;
    font-size: normal;
    height: 2em;
    transition: all 0.5s ease-out 0.2s;
}
div.kws:hover {
    height: 7em;
    transition: all 0.5s ease-out 0.2s;
}

div.kw,
div.kw-prog,
div.kw-art,
div.kw-trash {
    display: inline-block;
    width: 10em;
    background-color: rgba(150, 150, 150, 0.5);
    padding: 4px 8px;
    margin: 8px;
    height: 1.2em;
    font-size: 14px;
    border-radius: 4px;
    transition: all 0.5s ease-out 0.2s;
    overflow: clip;
}
div.kw-content {
    display: block;
    margin-top: 8px;
    padding: 8px;
    border-top: 2px solid white;
    width: inherit;
    font-size: 12px;
    box-sizing: border-box;
}
div.kw:hover {
    height: 8em;
    transition: all 0.5s ease-in 0.2 s;
}
div.kw-prog:hover {
    height: 8em;
    background-color: rgba(50, 250, 250, 0.5);
}
div.kw-art:hover {
    height: 6em;
    background-color: rgba(250, 50, 250, 0.5);
}
div.kw-trash:hover {
    height: 10em;
    background-color: rgba(255, 255, 255, 0.5);
}
div.keys {
    display: inline-block;
}
div.key {
    display: inline-block;
    text-align: center;
    font-size: 8px;
    border-radius: 4px;
    background-color: rgba(150, 150, 150, 0.5);
    padding: 2px 4px;
}
* {
    cursor: default;
}
</style>

<div align="center">
<div style="margin-bottom:-1em;">
<img src="img/trashbunicon.gif" height="64px">
<img src="img/trashbunicon.gif" height="64px">
<img src="img/trashbunicon.gif" height="64px">
<img src="img/trashbunicon.gif" height="64px">
<img src="img/trashbunicon.gif" height="64px">
</div>
<h1 style="margin-bottom:-1em;">Hello there 👋</h1>
<h2>I'm
<select>
<option> Sanghun </option>
<option> Joseph </option>
<option> Kyo </option>
</select>
</h2>
<hr>
<h4>
I am a(n): 
<div class="kws">
<div class="kw-prog">programmer
<div class="kw-content">
Python<br>
Django<br>
C-Sharp<br>
Go-lang<br>
HTML/CSS<br>
</div>
</div>
<div class="kw-art">artist
<div class="kw-content">
Ceramics<br>
Webtoon<br>
Illustration<br>
</div>
</div>
<div class="kw-trash">trashbunny
<div class="kw-content">
<img src="img/trashbuns.gif" title="trashbunny (noun): a trash bag with its handle ends tied up into a bunny's ears shape.">
</div>
</div>
</div>
</h4>

</div>

<hr>
#### I'm currently occupied with:
<ul class="tasks">
<li> Learning more about CSS and javascript for web design</li>
<li> Delevoping a collection of apps to practice better organization and archetecture of codes </li>
<li> Making a whole brand out of trashbunny</li>
</ul>
</div>
<div>
 