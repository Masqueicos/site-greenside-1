# site-greenside

## FAZ UM FORK E ADICIONA O QUE VOCÊ FEZ ;D

Link: https://masqueicos.github.io/site-greenside/

Link da apresentação:https://sesisenaispedu-my.sharepoint.com/:p:/g/personal/ollyver_osorio_portalsesisp_org_br/EYoF8NWrEKNLvwoARR-b3b0BBCo57Uajf2BT6aCa68dRiQ?e=qirCy5

link do figma: https://www.figma.com/file/I77eU3LgAvGkEHalgGVT64/GREENSIDE?node-id=0%3A1&t=88EB2Vr4RiTckIEf-1


*html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GreenSidePG1</title>
    <link rel="stylesheet" href="GreenSide.css">
</head>
<body>
    <div>


   <img class="img-inicial" src="./PG1ofc.png" alt="">
   
   <button class="meu-botao"><img src="./BtnMENU1.png" alt="" onclick="abrirmenu()">

   </button>
   
  

<div class="pesquisa-inicio">

    <form action="/pesquisar" method="get">
    <label for="pesquisa">Pesquisar:</label>
    <input type="text" id="pesquisa" name="q" placeholder="Digite sua pesquisa...">
    <button type="submit">Buscar</button>
    </form>

</div>


<div class="Lupa">

    <img src="LupaPesquisa.png" width="46px" height="46px">

</div>


   <button type="menu" class="consultebtn"><img src="Consulte-nos.png" alt="" width="260px" height="110px"></button>


  <button id="botao">Abrir imagem</button>


    </div>
</body>
</html>


*css

.html, body {
    margin: 0;
    padding: 0;
    height: 100%;
  }
  

  .img-inicial {width: 100%;
    height: 100%;
    object-fit: cover;
  }

  .meu-botao {
    background: none;
    border: none;
    position: absolute;
    top: 202px;
    left: 6.8%;
    transform: translateX(-50%);
    
  }

  .pesquisa-inicio {
    position: absolute;
    border-radius: 100%;
    top: 370px;
    left: 110px;
    font-size: 30px;
    font-family: monospace
  }

  
  input[type="text"] {
    border-radius: 25px;
    background-color: #f2f2f2;
    padding: 27px;
    width: 500px; /* ajuste a largura da barra de pesquisa como desejar */
    border: none;
    font-size: 27px;
  }

  button[type="submit"] {
    border-radius: 25px;
    background-color: #4CAF50;
    color: white;
    padding: 25px 33px;
    border: none;
    font-size: 27px;
    margin-left: 6px;
    cursor: pointer;
  }

  .Lupa{
    position: absolute;
    top: 390px;
    left: 62%;
   height: 200px;

  }

  .consultebtn { 
    position: absolute;
    top: 2110px;
    left: 505px;
    border: none;
    background: none;
    border-radius: 0%;
    stroke: none;

  }




  /*again*/

  .abrirmenu{

  }



