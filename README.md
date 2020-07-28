<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  <link href="https://fonts.googleapis.com/css?family=Cormorant+Infant&display=swap" rel="stylesheet">
  <title>Fotos</title>
  <style>
    * {
  margin: 0;
  padding: 0;
}

body {
  background: linear-gradient(to right, #f0f0f0, #fafafa)
}

.logo {
  background: white;
  height: 100px;
  border-bottom: rgb(223, 223, 223) solid 1px;
}

.text {
  font-family: 'Cormorant Infant', serif;
  padding-top: 10px;
  font-size: 25px;
  padding: 40px;
  padding-left: 50px;
  padding-right: 50px;
}

.imagem {
  float: right;
}
img {
  max-width: 100%;
}

.slides {
  text-align: center;
  padding: 30px;
  
}

.slides li {
  overflow: hidden;
  padding: 20px;
}

.f{
  box-shadow: 1px 2px 4px  #000;
}
.footer {
  text-align: center;
  color: rgb(155, 155, 155);
  padding: 20px;
  font-family: 'Cormorant Infant', serif;
  font-size: 15px;
}
</style>
</head>
<body>
  <div class="logo">
    <div class="text">
      & | EloisaThales
      <div class="imagem">
        <a href="https://www.instagram.com/"><img src="img/logo.insta.png" width="30px"></a>
        <a href="https://www.facebook.com/"><img src="img/logo.face.png" width="30px"></a> 
        <a href="https://www.youtube.com/"><img src="img/logo.you.png" width="30px"></a>
      </div>
    </div>
  </div>

  <div class="flexslider">
      <ul class="slides">
        <li>
          <a href="img/Tm. E+T-152.jpg" target="_blank"><img class="f" src="img/Tm. E+T-152.jpg" width="900px" /></a>
        </li>
        <li>
          <a href="img/Tm. E+T-196.jpg" target="_blank"><img class="f" src="img/Tm. E+T-196.jpg" width="900px"/></a>
        </li>
        <li>
          <a href="img/Tm. E+T-22.jpg" target="_blank"><img class="f" src="img/Tm. E+T-22.jpg" width="900px"/></a>
        </li>
      </ul>
    </div>
    <div class="footer">
      Copyright@2020 Thales Peniche
    </div>
</body>
</html>
