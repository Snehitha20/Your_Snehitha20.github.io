# Your_Snehitha20.github.io
WEB-DEV BOOTCAMP SHAPEAI



<html>
<head>
	<title>The Rock Resume</title>
	<link href="newstyle.css" rel="stylesheet" type="text/css" />
	<style>
		*
{
	box-sizing: border-box;
}
body
{
	margin:0px;
	padding:0px;
	font:poppins;

}
#main
{
	width: 100%;
	height: 60vh;
	position: relative;
}
nav
{
	display: flex;
	justify-content: space-around;
	align-items: center;
	position: fixed;
	top:0;
	left: 0;
	width: 100%;
	background-color: white;
	box-shadow: 5px 10px 30px rgba(0,0,0,0.2);
	z-index: 1;
	}
	.logo img
	{
         height:45px;


	}
	.menu
	{
      list-style: none;
       display: flex;
	}

	.menu li a

{
	height: 40px;
	line-height:43px; 
	margin:3px;
	padding:0px 22px; 
	display:flex;
	font-size: 0.8em;
	text-transform: uppercase;
	font-weight: 500;
	letter-spacing: 1px;
	color: grey;

}
.hey
{
color:#39bfbd;
font-weight: 500;
font-size:0.9em;
border-bottom: 2px solid #39bfbd;
}

	ul
	{
		list-style: none;
		display: flex;
     }
	a
	{
		text-decoration: none;
	}
.image
{
	width:420px;
	height: 420px;

}

.image img
{
	width:100%;
	height:100%;
	object-fit: contain;
}
.content
{
	display: flex;
	width: 90%;
	justify-content: space-around;
	align-items: center;
	position: absolute;
	left: 45%;
	right:50%;
	transform: translate(-50%,-50%);
}
.main-text
{
	width: 500px;
}

.main-text h1
{
	font-size:3.5em;
	color: #1c3548;
	margin:0px 0px 10px 0px;
	line-height: 60px;

}
.main-text p
{
	color:grey;
}
.resume-btn
{
	width: 190px;
	height: 44px;
	display: flex;
	justify-content: center;
	align-items: center;
	color:white;
	background-color: #1db096;
	border-radius: 20px;
	box-shadow: 5px 10px 30px rgba(0,0,0,0.2);
}

.resume-btn:hover{
	background-color: #23cdaf;
	transition: all ease 0.2s;
}
.menu li a:hover{
	background-color: #23cdaf;
	color:white;
	box-shadow: 5px 10px 30px rgba(0,0,0,0.2);
	transition: all ease 0.2s;

}
	</style>

</head>
<body>
	<section id="main">
	<nav>
		<a href="#" class="logo">
		
		<img src="data:image/png;base64,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" alt="the logo of project">

		</a>
		<span class="menuspace"></span>
<ul class="menu">
	<li><a href="#">Home</a></li>
	<li><a href="#">skills</a></li>
	<li><a href="#">recent</a></li>
	<li><a href="#">client</a></li>
	<li><a href="#">contact</a></li>

</ul>
<a href="#" class="hey"> <strong>Say Hi !</strong></a>
	</nav>
</section>
<section class="content">
	<div class="image">
		<img src="data:image/jpeg;base64,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" alt="Wrestler">

	</div>
	<div class="main-text">
		<h1>Hello, I am the <br> CEO </h1>
		<p>Hey, In this video I will be showing you guys how to build website using HTML and CSS
		</p>
		<a href="#" class="resume-btn"> See My Resume</a>
</div>
</section> 
</body>
</html>
