Homepage
<html>
<head>
<linkrel="stylesheet "href="rate1.css" >
<scriptsrc="https://ajax.googleapis.com/ajax/libs/jquery/3. 4.1/jquery . min. js"></script>
</head>
<body>
<header>
<navid="main" >
<ul>
<img class="logo" src="eedit1.jpg" alt="logo"
style="width:100;height : 45;"padding="5px;" > <img class="logo1" src="logoo1.jpg"
alt="logo"style="width:100;height : 45;"padding="5px;" >
<!--divclass="search" >
<form>
<inputtype="text "placeholder="Search.." >
<button>search</button>
</form>
</div->
</ul>
</nav>
</header>
<divclass="image" >
<imgsrc="collage2.jpg"alt="Snow"style="width:100%;height : 250%;" >
</div>
<divclass="bix" >
<divclass="sticky " >
<nav>
<ul>
<li><ahref="index.html " >Home</a></li>
<li><ahref="books.html " >Books</a></li>
<li><ahref="restaurant . html " >Restaurants</a></li>
<li><ahref="theatre.html " >Theatre</a></li>
<li><ahref="About . html " >About</a></li>
</ul>
</nav>
</div>
<script>
$(function(){
$( 'a[href*=\\#]:not([href=\\#]) ' ). on('click' , function(){
vartarget=$(this.hash);
target=target . length?target: $( ' [ name='+this.hash.substr ( 1)+' ] ' );
if(target . length){
$('html , body' ). animate({
scrollTop:target . offset().top
},1000);
returnfalse;
}
});
});
</script>
<divclass="box1"></div>
<divclass="box2" >
<imgsrc="god.jpg"width="370"height="300" >
</div>
<divclass="box3" >
<imgsrc="theatre.jpg"width="370"height="300" >
</div>
<divid="box4"class="box4" >
<h1style="font size:200%;">Aboutus</h1>
<p>Thisisabasicreviewwebsiteforbook
TheatresandRestaurants.Thiswebsiteis
doneby3collegematesastheirproject .
</p>
</div>
</div>
</div>
</body>
</html

Bookspage
<html>
<head>
<linkrel="stylesheet "href="books.css" >
<scriptsrc="https://ajax.googleapis.com/ajax/libs/jquery/3. 4.1/jquery . min. js"></script>
</head>
<body>
<navid="main" >
<ul>
<img class="logo" src="eedit1.jpg" alt="logo"
style="width:100;height : 45;"padding="5px;" >
<img class="logo1" src="logoo1.jpg" alt="logo"
style="width:100;height : 45;"padding="5px;" >
</ul>
</nav>
<divclass="image" >
<imgsrc="collage2.jpg"alt="Snow"style="width:100%;height : 250%;" >
</div>
<divclass="bix" >
<divclass="sticky " >
<nav>
<ul>
<li><ahref="index.html " >Home</a></li>
<li><ahref="books.html " >Books</a></li>
<li><ahref="restaurant . html " >Restaurants</a></li>
<li><ahref="theatre.html " >Theatre</a></li>
<li><ahref="index.html#box4">About</a></li>
</ul>
</nav>
</div>
<script>
$(function(){
$( 'a[href*=\\#]:not([href=\\#]) ' ). on('click' , function(){
vartarget=$(this.hash);
target=target . length?target: $( ' [ name='+this.hash.substr ( 1)+' ] ' );
if(target . length){
$('html , body' ). animate({
scrollTop:target . offset().top
},1000);
returnfalse;
}
});
});
</script>
<divclass="box1" >
<divclass="pic" >
<imgsrc="harry1.jpg"height="220;">
<li><ahref="harrypotter . html " ></a></li>
</div>
<divclass="content " >
<h1onclick="location.href='harrypotter . html' ;"style="cursor :pointer ;" >HarryPotterand
theGobletofFire</h1>
<pre>
ByJ. K.Rowling
Partof : HarryPotter
Category : fantasy|action&adventure|
summary
</pre>
</div>
</div>
<divclass="box2" >
<divclass="pic" >
<imgsrc="blowout . jpg"height="200" >
</div>
<divclass="content1" >
<h1onclick="location.href='blowout . html' ;"style="cursor : pointer ;" >Blowout</h1>
<pre>
ByRachelMaddow
Category : Thriller|mystery
</pre>
</div>
<divclass="box3" >
<divclass="pic" >
<imgsrc="guts.jpg"height="210" >
</div>
<divclass="content2" >
<h1onclick="location.href='guts.html' ;"style="cursor : pointer ;" >Guts</h1>
<pre>
ByRainaTelgemeier
Category : Non-fiction|Adventure
</pre>
</div>
</div>
<divclass="box4" >
<divclass="pic" >
<imgsrc="waterdancer . jpg"height="210" >
</div>
<divclass="content3" >
<h1 onclick="location.href='waterdancer . html' ;" style="cursor : pointer ;" >The
Waterdancer</h1>
<pre>
ByTa-NehisiCoates
Category : Fantasy
</pre>
</div>
</div>
<divclass="box5" >
<divclass="pic" >
<imgsrc="dogman.jpg"height="210" >
</div>
<divclass="content4" >
<h1onclick="location.href='dogman.html' ;"style="cursor : pointer ;" >Dogman</h1>
<pre>
ByDavPilkey
Category : Fiction
</pre>
</div>
</div>
</body
  
  SUMMARYPAGE
<html>
<head>
<linkrel="stylesheet "href="harrypotter . css" >
</head>
<body>
<header>
<navid="main" >
<ul>
<img class="logo" src="eedit1.jpg" alt="logo"
style="width:100;height : 45;"padding="5px;" >
<img class="logo1" src="logoo1.jpg" alt="logo"
style="width:100;height : 45;"padding="5px;" >
</ul>
</nav>
</header>
<divclass="image" >
<imgsrc="collage2.jpg"alt="Snow"style="width:100%;height : 80%;" >
</div>
<divclass="bix" >
<divclass="sticky " >
<nav>
<ul>
<li><ahref="index.html " >Home</a></li>
<li><ahref="books.html " >Books</a></li>
<li><ahref="restaurant . html " >Restaurants</a></li>
<li><ahref="theatre.html " >Theatre</a></li>
<li><ahref=" #">About</a></li>
</ul>
</nav>
</div>
<divclass="pic" >
<imgsrc="harry1.jpg"height="310;" >
<divclass="content " >
<h1>HarryPotterandtheGobletofFire</h1>
<h2>Summary</h2>
<p>ThenextmorningHarry'sUncleVernonreceivesaletterfrom theWeasleysasking
Harryto
jointhemattheQuidditchWorldCup,andVernongrudginglyagreestoletHarrygo.The
followingday ,
theWeasleysarriveintheDursleys'
boarded-upfireplacetopickupHarry .TheWeasleytwins"accidentally "leaveatrick
toffeeontheground,whichDudleyeats,
causinghistonguetoengorgeitself .
TheDursleyspanicandthrowthingsatMr .WeasleyastheWeasleyboysandHarryexit
throughthefireplace.
HarryarrivesatTheBurrow,theWeasleyhousehold,
andtherehemeetsforthetwoeldestWeasleybrothers,
BillandCharlie,andthere,Mrs.WeasleyberatesthetwinsformakingWeasleys'Wizard
WheezesandgivingthemtoDudley .
</p>
<ahref="https://www.flipkart . com/harry potter goblet fire/p/itmfc4qpuznyhmvr " >Goto
site</a>
</div>
</div>
</div>
<divid="disqus_thread"></div>
<script>
/**
* RECOMMENDED CONFIGURATION VARIABLES:EDIT AND UNCOMMENT THE
SECTIONBELOWTOINSERTDYNAMICVALUESFROMYOURPLATFORMORCMS.
* LEARN WHY DEFINING THESE VARIABLES IS IMPORTANT:
https://disqus.com/admin/universalcode/#configuration-variables*/
vardisqus_config=function(){
this.page.url="https://pratt . github.io/rate_it ";//ReplacePAGE_URLwithyour
page'scanonicalURLvariable
this.page.identifier= 120;//Replace PAGE_IDENTIFIER with yourpage's unique
identifiervariable
};
( function(){//DON'TEDITBELOWTHISLINE
vard=document , s=d.createElement ( 'script' );
s.src='https://pratt-var githubio-rateit . disqus.com/embed.js' ;
s.setAttribute('data-timestamp' , +newDate());
( d.head||d.body).appendChild( s);
})();
</script>
<noscript>Please enable JavaScript to view the <a
href="https://disqus.com/ ? ref_noscript " >commentspoweredbyDisqus.</a></noscript>
</body>
</html>
  
  
Databaseoperations-Disqus
<divid="disqus_thread"></div>
<script>
https://disqus.com/admin/universalcode/#configuration-variables*/
vardisqus_config=function(){
this.page.url="https://pratt . github.io/rate_it ";//ReplacePAGE_URLwith
yourpage'scanonicalURLvariable
this.page.identifier=120;//ReplacePAGE_IDENTIFIERwithyourpage'sunique
identifiervariable
};
( function(){
vard=document , s=d.createElement ( 'script' );
s.src='https://pratt-var githubio-rateit . disqus.com/embed.js' ;
s.setAttribute('data-timestamp' , +newDate());
( d.head||d.body).appendChild( s);
})();
</script>
<noscript>Please enable JavaScript to view the <a
href="https://disqus.com/ ? ref_noscript " >commentspoweredbyDisqus.</a></noscript>
Homepage-css . image{
filter : blur ( 3px);
top:50px;
}
. bix{
background-image:url ( try1.jpg);
background-color : pink;
padding:555px450px;
position:absolute;
width:125;
height : 300;
top:130%;
left : 625;
transform:translate(-50%,-50%);
}
. sticky {
overflow:hidden;
background-color : #333;
opacity : 0. 4;
position:fixed;
top: 0;
width:100%;
left : 0;
}
. stickya{
float : left ;
color : #f2f2f2;
text align:center ;
padding:14px16px;
text decoration:none;
font size:17px;
}
. stickya:hover{
background-color : #ddd;
color : black;
}
. stickya.active{
background-color : #4CAF50;
color : white;
}
. box1{
background-image:url ( books1.jpg);
background-color : pink;
background-repeat : no-repeat ;
padding:150px350px;
position:absolute;
top:100;
left : 165;
}
. box2{
object fit : cover ;
background-repeat : no-repeat ;
background-color : darkorange;
position:absolute;
top:530;
left : 160;
}
. box3{
background-repeat : no-repeat ;
background-color : darkred;
position:absolute;
top:530;
left : 540;
}
. box4{
background-color : orange;
color : black;
font family : 'TimesNewRoman' , Times,serif ;
font size:20;
background-repeat : no-repeat ;
padding:10px15px;
height : 230;
width:650;
position:absolute;
top:1030;
left : 180;
}
/TODISPLAYINSTRAIGHTLINE/
ul {
list style-type:none;
margin: 0;
padding: 0;
opacity : 0. 7;
}
