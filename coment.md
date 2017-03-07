<!DOCTYPE html>
<html lang="pt_br">
	<head>
	<meta charset="UTF-8">
		<title>Relatório</title>
	</head>

	<body>
		<div>
		Nome:<input type="text" id="nome"/> 
		E-mail:<input type="email" id="email"/> 
		<button id="nome" onclick="nome()">Enviar</button>
		</div>
	</body>
	<script>
	function nome(){
		t=document.getElementById("nome").value;
		q=t.length;
		if(q<5){
		alert("Digite um nome valido!");
		}
		n = nome.search(t);
		alert("n");
		
		
		}


	</script>
</html> 
