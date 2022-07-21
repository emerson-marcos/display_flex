# ESTRUTURA DE PASTA PARA O PROJETO

# NA PASTA PRINCIPAL DO PROJETO CRIAR OS ARQUIVOS DE:

# index.html
# style.css
# normalize.css
# root.css

_______________________________________________

# PARA AS DEMAIS PAGINAS CRIAR UMA PASTA, PARA CADA PAGINA, QUE CONTENHA OS ARQUIVOS index.html e style.css, QUE IRÃO CONTEM A ESTRUTURA HTML E O ESTILO DA PAGINA EM QUESTÃO
# EX: PASTA DisplaylFlex = REPRESENTA A PAGINA
# OBS: ANTENTAR AO NOME DA PASTA PARA MANDER UMA PADRONIZAÇÃO, SEGUINDO SEMPRE A PRIMEIRA PALAVRA COM LETRA MAIUSCULA E SEM ESPAÇOS

_______________________________________________

# ANTER A ORDEM DE CHAMADA DOS ARQUIVOS DE normaliza.css e root.css, eles devem seguir uma hirarquia, sendo ela: 
<link rel="stylesheet" href="root.css">  <!-- root.css SENDO CHAMADO EM PRIMEIRO SEMPRE -->
<link rel="stylesheet" href="normalize.css"> <!-- normalize.css SENDO CHAMADO EM SEGUNDO SEMPRE -->
<link rel="stylesheet" href="style.css"> <!-- OS DEMAIS ARQUIVOS DE ESTILIZAÇÃO PODE VIR DEPOIS DESSES DOIS DE CIMA -->

# TEM UM EXEMPLO DESSE NO index.html principal