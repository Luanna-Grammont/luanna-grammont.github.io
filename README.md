<!DOCTYPE html><!-- Declaramos que iremos usar o HTML 5 -->
<html lang="pt-br">	<!-- Inicia ciclo de Programação HTML com idioma da página em PT-BR-->
	<head>			<!-- Inicia a parte das configurações -->
		<meta charset="utf-8"><!--Este elemento define o tipo da codificação dos caracteres SEMPRE BOM COLOCAR-->
		<meta name="viewport" content="width=device-width, initial-scale=1.0"><!-- Enxerga o tamanho da tela do dispositivo-->
		<link href="https://fonts.googleapis.com/css?family=Alata|Dancing+Script&display=swap" rel="stylesheet">
		<title>LuannaGrammont_Ilustradora</title> <!-- o título da página que é exibido na barra de títulos dos navegadores -->
<!-- Criamos os estilos em CSS -->
	<style>
		.item1 { grid-area: cabeca;}
		.item2 { grid-area: trab;}
		.item3 { grid-area: logo; }
		.item4 { grid-area: tecn; }
		.item5 { grid-area: forma; }
		.item6 { grid-area: curri; }
		.item7 { grid-area: jornal;}
		.item8 { grid-area: pe;	}

		/* Cria estilo de Grid container*/
		.grid-container {
		/* um elemento HTML se torna um Grid */
			display: grid;
		/* Tamanho das Colunas das células */  
		    grid-template-columns:  20% 20% 20% 20% 20%;
		/* Tamanho das Linhas das células */  
			grid-template-rows: 25% 40% 25% 10%;	
		/* Declara grid-area de cada célula dentro de Linhas e Colunas */	
			grid-template-areas:
			'cabeca cabeca cabeca cabeca cabeca'
			'trab logo tecn forma curri'
			'jornal jornal jornal jornal jornal'
			'pe pe pe pe pe';
		/* Espaço horizontal entre as células*/	
			grid-gap: 2px;
		/* Cor de fundo das células*/	
			background-color: #00FFFF;
		/* Espaço Vertical entre as células*/	
			padding: 0.25vw;
		}

		/* Cada célula do Grid */
		.grid-container > div {
		  background-color: #FFC0CB;
		  text-align: center;
		  padding: 20px 0;
		  color: white;
		  font-family: 'Alata', sans-serif;
		  font-size: 30px;
		}
		
		.imagem { width: 100% }
		  .imagem:hover { /* cresce */ 
			-webkit-transform: scale(1.2);
            -ms-transform: scale(1.2);
            transform: scale(1.2); }
			
			 .imagem:active { /* cresce */ 
			-webkit-transform: scale(1.4);
            -ms-transform: scale(1.4);
            transform: scale(1.4); }
		
		p  {
			color: black;
			font-family: 'Dancing Script', cursive;
			font-size: 6vw;
			 }
		.p1  {
			color: black;
			font-family: 'Dancing Script', cursive;
			font-size: 3vw;
			 }
	</style>
</head>

	<body>

		 
		 <!-- Conteúdo das células de acordo com a área -->
			<div class="grid-container">
			
			  <div class="item1" style="background-color:#FFFFFF;">
			          <p style="float:left;"><strong>Luanna Grammont - 
					  <br>Ilustadora</br> </strong></p> <!-- -->
					  <img src="Capa.png" alt="Capa" style="width:40%;position: absolute; right: 0px">
			  </div>
			  
			  <div class="item2"><strong>Trabalhos</strong> <a href="Trabalhos_Grid.html"> 
			   <img src="Imagem1.jpg" class="imagem"alt="Trabalhos" style="width:100%; position: relative; right: 0px">
			   </a>
			   </div>
			   
			  <div class="item3"><strong>Logos</strong> <a href="Logos_Grid.html"> 
			   <img src="Imagem2.png" class="imagem"alt="Logos" style="width:100%; position: relative; right: 0px">
			   </a>
			  </div>  
			  
			  <div class="item4"> 
			  <strong>Técnicas</strong> <a href="Tecnicas_Grid.html"> 
			   <img src="Imagem3.jpg" class="imagem"alt="Técnicas" style="width:100%; position: relative; right: 0px">
			   </a>  
			  </div>
			  
			  <div class="item5"><strong>Formações</strong> <a href="Formações_Grid.html">
			   <img src="Imagem4.jpg" class="imagem"alt="Formações" style="width:100%; position: relative; right: 0px">
			   </a>
			  </div>
			  
			  <div class="item6"><strong>Currículo</strong> <a href="Curriculo_Grid.html">
			   <img src="Imagem5.jpg" class="imagem"alt="Currículo" style="width:100%; position: relative; right: 0px">
			   </a>
			   </div>
			   
			  <div class="item7" style="background-color:white;">
				  <p> Atualizações </p>
				 <p class="p1"  > 28-01: Trabalhos: Ilustrações para Campanha Colégio Sistemas </p>
			  </div>
			  
			  <div class="item8">Contato: luannagram@gmail.com</div>
			</div>
			
	<script type="text/javascript" src="/inc-ss/injectga.js"></script><script type="text/javascript" src="/inc-ss/injectga.js"></script></body>
</html>

