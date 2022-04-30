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
    <div class="big"> 
        <div class="header">
            <div class="a1"><img src="./img/bf_19_m.png" alt=""></div>
            <div class="a2"><img src="./img/bf_20_m.png" alt=""></div>
            <div class="a3"><img src="./img/bf_21_m.jpg" alt=""></div>
            <div class="a4"><img src="./img/bf_22_m.jpg" alt=""></div>
        </div>
        <div class="middle">
            <div class="b1"><img src="./img/bf_23_m.jpg" alt=""></div>
            <div class="b2"><img src="./img/bf_24_m.jpg" alt=""></div>
            <div class="b3"><img src="./img/hoos.jpg" alt=""></div>
            <div class="b4"><img src="./img/komi_13_m.jpg" alt=""></div>
        </div>
        <div class="bottom">
            <div class="c1"><img src="./img/bf_16_m.jpg" alt=""></div>
            <div class="c2"><img src="./img/Summer Time Rendering_02_m.jpg" alt=""></div>
            <div class="c3"><img src="./img/bf_17_m.jpg" alt=""></div>
            <div class="c4"><img src="./img/bf_18_m.jpg" alt=""></div>
        </div>
    </div>
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
nav .logo img{
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
.big{
    width: 100%;
    max-height: 600px;
}
.big .header{
    display: flex;
    width: 100%;
    height: 200px;
    gap: 10px;
    margin-bottom: 10px;
    justify-content: space-around;
    align-items: center;
}
.big .middle{
    width: 100%;
    height: 200px;
    display: flex;
    gap: 10px;
    margin-top: 20px;
    margin-bottom: 20px;
    justify-content: space-around;
    align-items: center;
}
.big .bottom{
    width: 100%;
    height: 200px;
    display: flex;
    gap: 10px;
    margin-top: 20px;
    justify-content: space-around;
    align-items: center;
}
.big .header .a1{
    width: 25%;
    height: 200px;
}
.big .header .a2{
    width: 25%;
    height: 200px;
}
.big .header .a3{
    width: 25%;
    height: 200px;
}
.big .header .a4{
    width: 25%;
    height: 200px;
}
.big .header .a1 img{
    width: 100%;
    height: 200px;
    object-fit: contain;
}
.big .header .a2 img{
    width: 100%;
    height: 200px;
    object-fit: contain;
}
.big .header .a3 img{
    width: 100%;
    height: 200px;
    object-fit: contain;
}
.big .header .a4 img{
    width: 100%;
    height: 200px;
    object-fit: contain;
}
.big  .middle .b1{
    width: 25%;
    height: 200px;
}
.big  .middle .b2{
    width: 25%;
    height: 200px;
}
.big  .middle .b3{
    width: 25%;
    height: 200px;
}
.big  .middle .b4{
    width: 25%;
    height: 200px;
}
.big .middle .b1 img{
    width: 100%;
    height: 200px;
    object-fit: contain;
}
.big .middle .b2 img{
    width: 100%;
    height: 200px;
    object-fit: contain;
}
.big .middle .b3 img{
    width: 100%;
    height: 200px;
    object-fit: contain;
}
.big .middle .b4 img{
    width: 100%;
    height: 200px;
    object-fit: contain;
}
.big .bottom .c1{
    width: 25%;
    height: 200px;
}
.big .bottom .c2{
    width: 25%;
    height: 200px;
}
.big .bottom .c3{
    width: 25%;
    height: 200px;
}
.big .bottom .c4{
    width: 25%;
    height: 200px;
}
.big .bottom .c1 img{
    width: 100%;
    height: 200px;
    object-fit: contain;
}
.big .bottom .c2 img{
    width: 100%;
    height: 200px;
    object-fit: contain;
}
.big .bottom .c3 img{
    width: 100%;
    height: 200px;
    object-fit: contain;
}
.big .bottom .c4 img{
    width: 100%;
    height: 200px;
    object-fit: contain;
}
