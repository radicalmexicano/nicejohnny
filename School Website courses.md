<!doctype html>
<html>
<head>
<meta charset="UTF-8">
<title>School Website</title>
<style type="text/css">
	body{
		
	background-color: rgba(199,188,188,1.00)
		
		
	}
.title {
	height: 200px;
	width: 1000px;
	left: 12px;
	top: 0px;
}
.sideImage {
	position: absolute;
	height: 400px;
	width: 240px;
	left: 768px;
	top: 224px;
}
.bottomImage {
	position: absolute;
	height: 200px;
	width: 1000px;
	left: 10px;
	top: 846px;
}
.body1 {
	position: absolute;
	height: 486px;
	width: 756px;
	left: 6px;
	top: 352px;
}
.homeButton {
	position: absolute;
	height: 50px;
	width: 150px;
	left: 9px;
	top: 224px;
}
.coursesButton {
	position: absolute;
	height: 50px;
	width: 150px;
	left: 161px;
	top: 224px;
}
.aboutusButton {
	position: absolute;
	height: 50px;
	width: 150px;
	left: 313px;
	top: 224px;
}
.contactsButton {
	position: absolute;
	height: 50px;
	width: 150px;
	left: 465px;
	top: 224px;
}
.sourcesButton {
	position: absolute;
	height: 50px;
	width: 150px;
	left: 617px;
	top: 224px;
}
.heading {
	position: absolute;
	height: 50px;
	width: 200px;
	left: 286px;
	top: 289px; 
	text-align: center;	
	color: rgba(255,255,255,1.00);
	font-family:Gotham, "Helvetica Neue" Helvetica, Arial "sans-serif";
	font-size: 45px;
	text-decoration: underline
	}
	
.body1 {
	color:rgba(6,9,60,1.00);
	}
.computerImage {
	position: absolute;
	height: 200px;
	width: 200px;
	left: 792px;
	top: 633px;
}
</style>
<script type="text/javascript">
function MM_swapImgRestore() { //v3.0
  var i,x,a=document.MM_sr; for(i=0;a&&i<a.length&&(x=a[i])&&x.oSrc;i++) x.src=x.oSrc;
}
function MM_preloadImages() { //v3.0
  var d=document; if(d.images){ if(!d.MM_p) d.MM_p=new Array();
    var i,j=d.MM_p.length,a=MM_preloadImages.arguments; for(i=0; i<a.length; i++)
    if (a[i].indexOf("#")!=0){ d.MM_p[j]=new Image; d.MM_p[j++].src=a[i];}}
}

function MM_findObj(n, d) { //v4.01
  var p,i,x;  if(!d) d=document; if((p=n.indexOf("?"))>0&&parent.frames.length) {
    d=parent.frames[n.substring(p+1)].document; n=n.substring(0,p);}
  if(!(x=d[n])&&d.all) x=d.all[n]; for (i=0;!x&&i<d.forms.length;i++) x=d.forms[i][n];
  for(i=0;!x&&d.layers&&i<d.layers.length;i++) x=MM_findObj(n,d.layers[i].document);
  if(!x && d.getElementById) x=d.getElementById(n); return x;
}

function MM_swapImage() { //v3.0
  var i,j=0,x,a=MM_swapImage.arguments; document.MM_sr=new Array; for(i=0;i<(a.length-2);i+=3)
   if ((x=MM_findObj(a[i]))!=null){document.MM_sr[j++]=x; if(!x.oSrc) x.oSrc=x.src; x.src=a[i+2];}
}
</script>
</head>



<body onLoad="MM_preloadImages('Home(Overlay).png','Courses(Overlay).png','About us(Overlay).png','Contact(Overlay).png','Sources(Overlay).png')">


	
<div class="title" id="div1"><img src="TitleBar Image.jpg" width="1000" height="200" alt=""/></div>
	
<div class="sideImage" id="div2"><img src="Sidebarimage.jpg" width="240" height="400" alt=""/></div>
	
<div class="bottomImage" id="div3"><img src="Bottombarimage.jpg" width="1000" height="200" alt=""/></div>
	
<div class="body1" id="div4">
	<h1>Top 3 Programming Languages in 2019</h1>
	
	<p><a href="https://www.codecademy.com/learn/introduction-to-javascript" rel="noopener" target="_blank"><strong><em>Javascript</em></strong></a> often plays a major role in front-end development. Some of the major social media platforms believe that it provides an easy way to create interactive web pages smoothly  while also being career-driven. It's <strong>the most</strong> popular language among developers for 6 years, and around <strong>65%</strong> of them have used this language in the past year.</p>
	<p>&nbsp;</p>
	
	<p><a href="https://www.codecademy.com/learn/learn-python" rel="noopener" target="_blank"><strong><em>Python</em></strong></a> is a user-friendly programming language. Its syntax is clear, intuitive and in a way similar to the English language. The open source network makes it easy to learn while being versatile and powerful. Phtyon being so popular in areas like scientific computing, machine learning, and engineering, Python supports a style that uses simple functions without much interrogating in class definitions.</p>
	<p>&nbsp;</p>
	
	<p><a href="https://www.codecademy.com/learn/learn-java" rel="noopener" target="_blank"><strong><em>Java</em></strong></a> being the ruling programming language for the last 20 years, it's object-oriented and simplicity makes it the favorite for beginners. It is simpler than C++ because Java uses automatic memory allocation and garbage collection. Java forms the base for the Android operating system and opted around <a href="https://www.zipcodewilmington.com/blog/why-java-skills-matter-now-and-in-the-future" rel="noopener" target="_blank">90% fortune 500 companies</a> for making a variety of back-end applications. With so many good reasons and a wide range of business applications, it is definetly one of the best.</p>
	
	
</div>
	
	
	
<div class="homeButton" id="div5"><a href="School Website.html" onMouseOut="MM_swapImgRestore()" onMouseOver="MM_swapImage('Image4','','Home(Overlay).png',1)"><img src="Home.png" alt="" width="150" height="50" id="Image4"></a></div>
	
<div class="coursesButton" id="div6"><a href="School Website courses.html" onMouseOut="MM_swapImgRestore()" onMouseOver="MM_swapImage('Image5','','Courses(Overlay).png',1)"><img src="Courses.png" alt="" width="150" height="50" id="Image5"></a></div>
	
<div class="aboutusButton" id="div7"><a href="School Website About us.html" onMouseOut="MM_swapImgRestore()" onMouseOver="MM_swapImage('Image6','','About us(Overlay).png',1)"><img src="About us.png" alt="" width="150" height="50" id="Image6"></a></div>
	
<div class="contactsButton" id="div8"><a href="School Website Contacts.html" onMouseOut="MM_swapImgRestore()" onMouseOver="MM_swapImage('Image7','','Contact(Overlay).png',1)"><img src="Contact.png" alt="" width="150" height="50" id="Image7"></a></div>
		
<div class="sourcesButton" id="div9"><a href="School Website Sources.html" onMouseOut="MM_swapImgRestore()" onMouseOver="MM_swapImage('Image8','','Sources(Overlay).png',1)"><img src="Sources.png" alt="" width="150" height="50" id="Image8"></a></div>
	
<div class="heading"><strong> Courses </strong></div>

<div class="computerImage" id="div11"><img src="../../../../Downloads/11296.png" width="200" height="200" alt=""/></div>	
	

	
	
</body>
</html>
