---
layout: layouts/base.njk
eleventyNavigation:
key: About Me
order: 3
---
# About Me

I am a person that writes stuff.

I shall add a simple table and a form on this page and then I shall
experiment with the use of Bootstrap for some of my other pages.

<h2>A Simple Table.</h2>

Date: <time datetime="2024-05-19">May 19, 2024</time>
<br>
<table>
<caption style= "caption-side:bottom; text-align:right"> Primary and
secondary colours </caption>
<tr>
<th>Colours</th>
<th>Red</th>
<th>Yellow</th>
<th>Blue</th>
</tr>
<tr>
<th>Red</th>
<td>- </td>
<td>Orange</td>
<td>Purple</td>
</tr>
<tr>
<th>Yellow</th>
<td>Orange</td>
<td> - </td>
<td>Green</td>
</tr>
<tr>
<th>Blue</th>
<td>Purple</td>
<td>Green</td>
<td>-</td>
</tr>
</table>
<br>
<br>
<table>
<th> A simple table with a caption set on the bottom right.</table>



<h2>A Simple Form</h2>
<form action = "">
<fieldset>
<legend>Personal data</legend>
<p>
<label>Name</label>
<input type = "text"/>
</p>
<p>
<label>Address</label>
<input type = "text"/>
</p>
<p>
<label>Phone</label>
<input type = "text"/>
</p>
</fieldset>

A form that we are going to attempt to use with Bootstrap and Flex Grids soon.


Here is a screenshot of the table we created using html and css stylesheet in our course for a challenge.

{% image "./Table-Challenge.png", "A Table-Challenge screenshot" %}
