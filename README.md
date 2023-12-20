<!DOCTYPE html>
<html lang="ptbr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@100;200;300;400;500&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="style.css">
    <title>Arquitetura</title>
</head>

<body>
    <script src="index.js"></script>
  
    <!--- menu-superior --->
    <div id="menu-superior">
    <h1 id="titulo-menusuperior">Tradição em projetos e arquitetura </h1> 
   <p id="paragrafo-menusuperior">Arquitetura residencial e comercial</p>
  
  </div>
  
  <!--menu informativo-->
   <div id="menu-informativo">
    <h2>850</h2> 
    <h2>40</h2> 
    <h2>2,000,000</h2>
    <p>Empreendimentos contruídos </p>
    <p>Anos de mercado e experiência</p>
    <p>m² em projetos construídos</p>   
</div>

<!--info e imagem-->
<div id="info">
 <div id="info-texto">
  <h1>Arquitetos com História e Experiência</h1>
  <p>Nós realizamos desde 2002 projetos e gerenciamento de obras.<br>
     Com mais de 800 projetos e 2.000.000 de m² construídos, tendo<br>
     como principal proposta transformar em realidade os sonhos de<br>
     seus clientes, criando projetos personalizados, unindo a tradição<br>
     e a modernidade em nossos projeto</p>
 </div>
<img id="imagem" src="./imagens.img/foto.svg" alt="error">

</div>

<!--formulário-->
<div id="formulário">
  <h1 id="titulo-formulario">Conheça mais sobre nossos serviços:</h1>
 <form action="https://api.sheetmonkey.io/form/3DTaJJ5swUVzdT1FT1K9K7" method="post">
  <input type="text" placeholder="Nome" name="Name" required><br>
  <input type="email" placeholder="e-mail" name="Email" required><br>
  <input type="hidden" name="Created" value="x-sheetmonkey-current-date-time" />
  <button>Fale Conosco</button>
</form>
</div>
</body>
</html>
*{
   margin: 0px;
  padding: 0px;
  box-sizing: border-box;
    font-family: "inter";
}

#titulo-menusuperior{
    padding: 25px 50px 75px 100px;
  
}

#paragrafo-menusuperior{
    padding: 0px 5px 75px 100px;
 
    
}
#menu-superior{
    margin: 0px;
    background-color: #303030;
    color: white;
  
}

#menu-informativo{
  margin-top: 1rem;
    width: 100%;
    padding: 2rem;
    display: grid;
  grid-template-columns: repeat(3, 1fr);
  grid-column-gap: 10px;
  grid-row-gap: 1em;
}

#info{
   margin: 0px;
    padding: 150px 161px;
    display: grid;
    grid-auto-flow: column;
    columns: auto;
    
  }

  #imagen{
    Width: 510px
  
  }

  #formulário{
    background-color: #303030;
    padding-top: 140px;
    padding-right: 30px;
    padding-left: 700px;
    padding-bottom: 140px;

  }

  #titulo-formulario{
    margin: 25px;
    font-size: 25px;
    color: white;
  }

  input{
    margin: 15px;
    height: 41px;
    width: 400px;
    padding-left: 15px;
    border-radius: 5px;
    background-color: #FFFFFF; 
    border: 0px;
}    

button{
  margin-left: 80px;
      background-color: #C07212;
    width: 250px;
    height: 41px;
    font-weight: bolder;
    border: 0px;
    border-radius: 5px;
    cursor: pointer;
    color: #FFFFFF;
    box-shadow: 3px 2px 1px #b8884f;
}
 button:hover{
    background-color: #C07212;
    color: rgb(248, 245, 245);
    transform: translateY(-7px)
 }
