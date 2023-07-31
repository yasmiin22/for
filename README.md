<!DOCTYPE html>
<html>

	<head>
		<title>Formulário do HTML</title>
		<meta charset=“UTF-8”>
		<link rel="stylesheet" type="text/css" href="estilo.css">
		<style type="text/css">
		h2{text-align:center;}
		.para1{font-family:Comic Sans MS, Comic Sans, cursive}
		p{font-family:Comic Sans MS, Comic Sans, cursive}
		h2{font-family:Comic Sans MS, Comic Sans, cursive}
		h1{font-family:Comic Sans MS, Comic Sans, cursive}
		</style>
	</head>

	<body style="background-color:	#DCDCDC">
		<h1>Formulário do HTML </h1>
		<P> Um formulário HTML é usado para coletar a entrada do usuário. A entrada do usuário geralmente é enviada a um servidor para processamento.Os formulários HTML são compostos por diversos elementos, que compõem o formulário. Dessa forma, é necessário entender como e quando utilizar cada um deles;</p>
		<h2>Os elementos de formulários utilizados no HTML são: </h2>
		<ul>
		<li class="para1"><strong>Form</strong> – É usado para criar um formulário HTML para entrada do usuário. Elemento é um contêiner para diferentes tipos de elementos de entrada, como: campos de texto, caixas de seleção, botões de opção, botões de envio, etc;</li>
		<br>
		<li class="para1"> <strong>Input</strong> – Define um campo de entrada de dados.Um input elemento pode ser exibido de várias maneiras, dependendo do <strong>type</strong> atributo; </li>
		<br>
		<li class="para1"> A imagem a seguir mostra uma série de "INPUT TYPES" e o seu uso. Veja: </li>
		<br>
		<figure>
			<img src= https://pbs.twimg.com/media/FGYUQ7xVcAEoZKn?format=jpg&name=large width="460" height="290" alt="ex">
		</figure>
		<br>
		<p> <strong>Veja o seguir exemplo: Tipo e-mail  </strong></p>
		<form>
			E-mail: <input type="email" name="e-mail" placeholder="digite seu e-mail aqui">
		</form>
		<br>
		<p>  <strong> Exemplo: Tipo password </strong> </p>
		<form>
			<input type="password" name="senha" placeholder="Digite sua Senha">
		</form>
		<br>
		<li class="para1"><strong> Textarea</strong> – Define uma área de texto, podendo conter diversas linhas de texto. Diferente do input do tipo “text”, a tag textarea pode possuir várias linhas. Portanto, as áreas de texto podem conter um número ilimitado de caracteres. O tamanho de uma área de texto pode ser especificado pelos atributos cols e rows. Porém, o mais aduado na atualidade é utilizar as propriedades do CSS;  </li>
		<p> <strong>Veja o seguir exemplo </strong></p>
		<form>
			<textarea></textarea
			<textarea>Area de texto com um texto inicial dentro</textarea>
		</form>
		<br>
		<li class="para1"><strong>Button</strong> –  Botão para permitir que o usuário envie seus dados depois de ter preenchido o formulário;</li>
		<p> <strong>Veja a seguir um exemplo: o navegador irá renderizá o seguinte botão e após executará um alerta com a frase “Você clicou no botão!” </strong> </p>
		<form>
			<input type="button" value="Clique Aqui" onclick="msg()">
		</form>
		<script>
		function msg() {
			alert("Você clicou no botão!");
		}
		</script>
		<br>
		<li class="para1"><strong>checkbox</strong> – Define uma caixa de seleção. A caixa de seleção é mostrada como uma caixa quadrada que pode ser marcada quando é ativada. As caixas de seleção permitem que o usuário possa marcar uma ou mais opções;</li>
		<p> <strong>Veja a seguir um exemplo: </strong></p>
		<form>
			<input type="checkbox" name="veiculo1" value="bicicleta">Eu tenho uma bicicleta<br>
			<input type="checkbox" name="veiculo2" value="carro">Eu tenho um carro<br>
			<input type="checkbox" name="veiculo3" value="moto">Eu tenho uma moto
		</form>
		<br>
		<li class="para1"><strong>Optgroup</strong> – Cria um agrupamento de opções dentro do elemento select;</li>
		<p> <strong>Veja o seguir exemplo: </strong> </p>
		<select>
			<optgroup label="Grupo 1">
				<option>Opção 1.1</option>
			</optgroup>
			<optgroup label="Grupo 2">
				<option>Opção 2.1</option>
				<option>Opção 2.2</option>
			</optgroup>
		</select>
		<br>
		
		<li class="para1"><strong> Fieldset</strong> – Define um grupo de campos. A fieldset tag é usada para agrupar elementos relacionados em um formulário. A fieldset tag desenha uma caixa ao redor dos elementos relacionados;</li>
		<p> <strong>Veja o seguir exemplo:  </strong></p>
		<form action="test.php" method="post">
			<fieldset>
			<legend>Título-exemplo</legend>
			<input type="radio" id="radio"> <label for="radio">Click aqui</label>
			</fieldset>
		</form>
		<br>
		<li class="para1"><strong>Label</strong> – Define um rótulo ou legenda para um campo ou controle do formulário. O label elemento é útil para usuários de leitores de tela, porque o leitor de tela lerá o rótulo em voz alta quando o usuário focar no elemento de entrada. O elemento também ajuda os usuários que têm dificuldade em clicar em regiões muito pequenas (como botões de opção ou caixas de seleção) - porque quando o usuário clica no texto dentro do label elemento, ele alterna o botão de opção/caixa de seleção;</li>
		<p> <strong>Veja a seguir um exemplo: campos de entrada para texto: </strong> </p>
		<form>
			<label for="fname">Primeiro nome:</label><br>
			<input type="text" id="fname" name="fname"><br>
			<label for="lname">Segundo name:</label><br>
			<input type="text" id="lname" name="lname">
		</form>
		<br>
		<li class="para1"><strong> Legend</strong> - Define um título para o conjunto de campos;</li>
		<br>
		<li class="para1"><strong> Option</strong> – É usado para criar um controle que representa um item dentro de um elemento HTML5 select, optgroup ou datalist;</li>
		<br>
		<li class="para1"><strong>Select</strong> – Representa um controle que apresenta um menu de opções. As opções dentro do menu são representadas pelo elemento option, que podem ser agrupados por elementos optgroup. As opções podem ser pré-selecionadas para o usuário.</li>
		<br>
		</ul>

	</body>
</html>
