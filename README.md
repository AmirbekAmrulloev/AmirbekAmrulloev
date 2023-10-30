
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        .button{
    color: rgb(0, 255, 76);
    background-image: linear-gradient(to right, rgb(134, 0, 0), rgb(255, 0, 0), rgb(255, 85, 85));
    width: 100px;
    height: 40px;
    border-radius: 30%;
    margin-top: 250px;
    margin-left: 880px;
    }
    
    
    .button :hover{
        color: #000;
    
    }
    
    .aa{
        color: aqua;
        text-decoration: none;
    }
body{
    margin: 0;
    padding: 0;
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 100vh;
    overflow-y: hidden;
    background-color: black;
}
.container{
    position: absolute;
    width: 550px;
    height: 550px;
    transform-style: preserve-3d;
    transform: perspective(600px) rotate(0deg);
}
.container span{
position: absolute;
display: block;
box-sizing: border-box;
border: 2px solid white;
margin: 10px;
box-shadow: 0 0 10px;
animation: span 50s ease-in-out infinite;
}
@keyframes span{
    0%{
        transform: rotate(0deg);
        border-radius: 0;
    }
    20%{
        box-shadow: 0 0 40px green;
    }
    50%{
        transform: rotate(360deg);
        background-color: black;
        box-shadow: 0 0 40px aqua;
        border-radius: 20%;
    }
    70%{
        box-shadow: 0 0 40px chocolate;
    }
    10%{
        transform: rotate(0deg);
    }
}

.container span:nth-child(1){
    top:  0;
    left:  0;
    right: 0;
    bottom:  0;
    animation-delay: 0.5s;
}

.container span:nth-child(2){
    top:  10px;
    left:  10px;
    right: 10px;
    bottom:  10px;
    animation-delay: 1s;
}

.container span:nth-child(3){
    top:  20px;
    left:  20px;
    right: 20px;
    bottom:  20px;
    animation-delay: 1.5s;
}

.container span:nth-child(4){
    top:  30px;
    left:  30px;
    right: 30px;
    bottom:  30px;
    animation-delay: 2s;
}

.container span:nth-child(5){
    top:  40px;
    left:  40px;
    right: 40px;
    bottom:  40px;
    animation-delay: 2.5s;
}

.container span:nth-child(6){
    top:   50px;
    left:  50px;
    right: 50px;
    bottom:50px;
    animation-delay: 3s;
}

.container span:nth-child(7){
    top:  60px;
    left:  60px;
    right: 60px;
    bottom:  60px;
    animation-delay: 3.5s;
}

.container span:nth-child(8){
    top:  70px;
    left:  70px;
    right: 70px;
    bottom:  70px;
    animation-delay: 4s;
}

.container span:nth-child(9){
    top:  80px;
    left:  80px;
    right: 80px;
    bottom:  80px;
    animation-delay: 4.5s;
}

.container span:nth-child(10){
    top:  90px;
    left:  90px;
    right: 90px;
    bottom:  90px;
    animation-delay: 5s;
}

.container span:nth-child(11){
    top:  100px;
    left:  100px;
    right: 100px;
    bottom:  100px;
    animation-delay: 5.5s;
}

.container span:nth-child(12){
    top:  110px;
    left:  110px;
    right: 110px;
    bottom:  110px;
    animation-delay: 6s;
}

.container span:nth-child(13){
    top:  120px;
    left: 120px;
    right: 120px;
    bottom:  120px;
    animation-delay: 6.5s;
}

.container span:nth-child(14){
    top:  130px;
    left:  130px;
    right: 130px;
    bottom:  130px;
    animation-delay: 7s;
}

.container span:nth-child(15){
    top:  140px;
    left:  140px;
    right: 140px;
    bottom:  140px;
    animation-delay: 7.5s;
}

.container span:nth-child(16){
    top:  150px;
    left:  150px;
    right: 150px;
    bottom:  150px;
    animation-delay: 8s;
}

.container span:nth-child(17){
    top:  160px;
    left:  160px;
    right: 160px;
    bottom:  160px;
    animation-delay: 8.5s;
}

.container span:nth-child(18){
    top:  170px;
    left:  170px;
    right: 170px;
    bottom:  170px;
    animation-delay: 9s;
}

.container span:nth-child(19){
    top:  180px;
    left:  180px;
    right: 180px;
    bottom:  180px;
    animation-delay: 9.5s;
}
.container span:nth-child(20){
    top:  190px;
    left:  190px;
    right: 190px;
    bottom:  190px;
    animation-delay: 10s;
}
    </style>
</head>
<link rel="stylesheet" href="animatsiya.css">
<body>
        <div class="container">
            <span></span>
            <span></span>
            <span></span>
            <span></span>
            <span></span>
            <span></span>
            <span></span>
            <span></span>
            <span></span>
            <span></span>
            <span></span>
            <span></span>
            <span></span>
            <span></span>
            <span></span>
            <span></span>
            <span></span>
        </div>
        <button class="button"><a href="animatsiya2.html" class="aa">1-animatsiya</a></button>
</body>
</html>
