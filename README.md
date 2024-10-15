# Assignment-1-2-3
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>gallery page</title>
</head>
<style>
    body {
        background-color: black;
    }
    .container {
        margin: 100px 0 0 200px;
        width: 70%;
        height: 450px;
        display: flex;
        justify-content: center;
        gap: 10px;

    }
    .container img{
        width: 10%;
        height: 100%;
        object-fit: cover;
        border-radius: 10px;
        border: 2px solid rgb(214, 206, 177);
        transition: all ease-in-out 0.5s;
    }
    .container img:hover{
        width: 25%;
    }

</style>
<body>
    <div class="container" >
     <img src="https://m.media-amazon.com/images/I/71yTB-66VXL._AC_UF894,1000_QL80_.jpg">
     <img src="https://m.media-amazon.com/images/M/MV5BNzBjN2ZkNjEtODgxNS00NWQwLWJmNjAtYmQ5NWRlMDA0ZDhlXkEyXkFqcGc@._V1_.jpg">
     <img src="https://m.media-amazon.com/images/M/MV5BM2QxNjZlYTEtOWVkNC00OGUxLTgwNjMtN2Y4Y2ZjMzcwZjIxXkEyXkFqcGc@._V1_.jpg">
     <img src="https://cdn1.epicgames.com/offer/3ddd6a590da64e3686042d108968a6b2/EGS_GodofWar_SantaMonicaStudio_S2_1200x1600-fbdf3cbc2980749091d52751ffabb7b7_1200x1600-fbdf3cbc2980749091d52751ffabb7b7">
     <img src="https://www.venturegames.com.pk/cdn/shop/files/GodofWarRagnarok.jpg?v=1706608799">
        </div>
    
</body>
</html>
