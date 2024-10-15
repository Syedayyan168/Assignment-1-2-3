# Assignment-1-2-3
<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<title>Navigation Bar</title>
    <link href="contact.html" >
    <link href="gallerypage.html">
	<style type="text/css">
		*{
			text-decoration: none;
		}
		.navbar{
			background: lightgreen; font-family: calibri; padding-right: 15px;padding-left: 15px;
		}
		.navdiv{
			display: flex; align-items: center; justify-content: space-between;
		}
		.logo a{
			font-size: 35px; font-weight: 600; color: white;
		}
		li{
			list-style: none; display: inline-block;
		}
		li a{
			color: white; font-size: 18px; font-weight: bold; margin-right: 25px;
		}
		button{
			background-color: black; margin-left: 10px; border-radius: 10px; padding: 10px; width: 90px;
		}
		button a{
			color: white; font-weight: bold; font-size: 15px;
		}
        .SMIT img{
            width: 100px;
            height: 75px;
        }
	</style>
</head>
<body>
	<nav class="navbar">
		<div class="navdiv">
            <nav class="SMIT">
                <img src="https://arman-assignment1.netlify.app/logo-OpazD70S.png" alt="SMIT Logo">
          
            </nav>
			
			<ul>
				<li><a href="#">Home</a></li>
                <button>
				<li><a href="gallerypage.html">Gallery page</a></li>
            </button>
                <button>
				<li><a href="contact.html">Contact</a></li>
            </button>
				<button><a href="#">SignIn</a></button>
				<button><a href="#">SignUp</a></button>
			</ul>
		</div>
	</nav>
</body>
</html>
