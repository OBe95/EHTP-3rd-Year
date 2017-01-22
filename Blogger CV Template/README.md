#0BE95 CV Blogger Template
<p>The following description assumes that you have created a simple blogger blog</p>
<br>
<h2>Installation</h2>
<p>Simply go to <b>Template</b> -> <b>Edit HTML</b> -> Replace the existing code with the one in "0BE95 CV.xml" -> Finally <b>Save template</b>
<br>
<p>You'll get something like <a href="http://cvexporttest.blogspot.com/">CV Export Example</a></p>
<p>To get something like <a href="http://www.obentaleb.com/">Othmane BENTALEB CV</a>, please follow the next section.
<br><br>
<h2>Configuration</h2>
<h3>Edit personal photo</h3>
<p>Look for the following url and replace it by your photo url</p>
```
https://lh3.googleusercontent.com/-_v1GwLULv7c/V-plUAIJvnI/AAAAAAAABJs/7RcPDfc2Bxo-ZAjM2LvhRaI8GoCWcjDugCLcB/h1600/othmane_bentaleb.jpg
```
<br>
<h3>Personal informations block</h3>
```
<div class='row personal-info'>
	<div class='col-xs-12 col-sm-6 personal-info-img'/>
	<div class='col-xs-12 col-sm-6 personal-info-details'>
    	<div class='row personal-info-name'>First/Last Name</div>
	    <div class='row'>
	        <p class='personal-info-title'>Birth Date:</p><p>17-03-1995</p>
	    </div>
	</div>
</div>
```
####You can duplicate the personal-info-title line to add more informations

<br>
<h3>Links block</h3>
```
<div class='row links-container'>
	<div class='links'>
	    <a href='#accueil'>Accueil</a>
	    <a href='#formation'>Formation</a>
		<a href='#experiences'>Expériences</a>
		<a href='#connaissances'>Connaissances</a>
		<a href='#contact'>Contact</a>
	</div>
</div>
```
####Make sure that the href link matches the block id that you want to scroll to it by clicking the link

<br>
<h3>Formation block</h3>
```
<div class='row formation-details'>
  	<div class='col-xs-12 col-sm-3'><div class='formation-date fromLeft1'><span>2014</span></div></div>
	<div class='col-xs-12 col-sm-6 formation-detail'>Replace this paragraph with your formation details</div>
	<div class='col-xs-12 col-sm-3'><div class='formation-date fromRight1'><span>Now</span></div></div>
</div>
```
####You can duplicate this block as much as formations you need to add
####You may need to add the following line to insert an horizontal line between two successive block
```
<div class='row horizontal-line'/>
```

<br>
<h3>Experience block</h3>
```
<div class='row experiences-details'>
	<div class='col-xs-12'>
      	<span class='experience-date'>&#9830; June 2016 &#9830;</span>
		<div class='experience-container'>
            <span class='experience-title'>&#9733; Experience title</span> 
            <span class='experience-description'>A small description for your experience, internship, it's objectives, your realizations.</span>
          <span class='experience-tech'>Here goes the technologies used during the experience</span>
      	</div>
	</div>
</div>
```
####you can duplicate this block as much as experiences you have

<br>
<h3>Connaissance block</h3>
```
<div class='connaissance'>
    <span>Java</span>
    <span class='circle'/>
    <span class='fill-circle4'/>
    <span class='fill-circle3'/>
    <span class='fill-circle2'/>
    <span class='fill-circle1'/>
</div>
```
####You can duplicate this block as much as technologies you want to add
####Use "circle" for an empty circle or "fill-circleX" and replace the "X" whith the span number (descending count)

####There are two blocks for the "Connaissances" section
#####The first one
```
<div class='col-xs-12 col-sm-6 connaissances-left'>
  #here goes as much as you want of "Connaissance" block (as shown before) for the left side
</div>
```
#####The second one
```
<div class='col-xs-12 col-sm-6'>
  #here goes as much as you want of "Connaissance" block (as shown before) for the left side
</div>
```
