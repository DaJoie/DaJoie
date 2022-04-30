<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="./style.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.1.1/css/all.min.css" integrity="sha512-KfkfwYDsLkIlwQp6LFnl8zNdLGxu9YAA1QvwINks4PhcElQSvqcyVLLD9aMhXd13uQjoXtEKNosOWaZqXgel0g==" crossorigin="anonymous" referrerpolicy="no-referrer" />
    <title>Document</title>
</head> 
<body>
    <nav>
        <div class="logo">
            <img src="./img/logo-white.png" alt="logo">
        </div>
        <div class="menu">
            <div class="menu-item">
                <i class="fa-solid fa-magnifying-glass"></i>
            </div>
            <div class="menu-item">
                <i class="fa fa-film"></i>
            </div>
            <div class="menu-item">
                <i class="fa fa-bars"></i>
            </div>
        </div>
    </nav>
</body>
</html>
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
css:
*{
    margin: 0px;
    padding: 0px;
    box-sizing: border-box;
}
body{
    background-color: #1d1d1d;
}
nav{
    width: 100%;
    height: 61px;
    display: flex;
    justify-content: space-between;
    border-bottom: 1px solid #393939;
}
nav .logo{
    width: 15%;
    height: 100%;
}
nav .logo .img{
    width: 100%;
    height: 100%;
    object-fit: contain;
    padding-left: 10px;
}
nav .menu{
    width: 15%;
    height: 100%;
    display: flex;
}
nav .menu .menu-item{
    width: 33%;
    height: 100%;
    border-left: 1px solid #393939;
    display: flex;
    align-items: center;
    justify-content: center;
}
nav .menu .menu-item{
    color: #666;
    font-size: 20px;
}
