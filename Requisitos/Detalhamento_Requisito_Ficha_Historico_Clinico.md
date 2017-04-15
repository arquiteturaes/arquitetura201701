#Requisito : Cadastro de paciente 
##Objetivo :
O requisito trata a necessidade de inserir na ficha de cadastro do cliente sua ficha e hist�rico cl�nico. Desta forma, al�m das informa��e b�sicas como endere�o, foto, nome completo, documentos a ficha dever� tamb�m conter a informa��es cl�nicas.

##Diagrama de Classes:
![casoUso](https://github.com/arquiteturaes/arquitetura201701/blob/master/Imagens/DiagramaClassesFicha.png) 

##Diagrama de Sequencia:
![casoUso](https://github.com/arquiteturaes/arquitetura201701/blob/master/Imagens/DiagramaSequenciaFicha.png) 

## Casos de uso :

# Caso de uso Cadastrar informa��es na ficha cl�nica
## Pr�-condi��o: 
	.O usu�rio deve estar logado no sistema 
## Objetivos: 
	.Na primeira consulta m�dica, ap�s a an�lise do m�dico � inserida informa��es no cadastro.
## P�s-condi��o:
	.O sistema dever� gravar no cadastro do cliente as informa��es da ficha cl�nica.

#Caso de uso Alterar ficha cl�nica
##Pr�-condi��o: 
	.O usu�rio deve estar logado no sistema 
	.A ficha cl�nica deve conter alguma informa��es
##Objetivos: 
	.Alterar informa��es que est�o na ficha cl�nica do cliente.
##P�s-condi��o:
	.O sistema dever� gravar a altera��o no cadastro do cliente as informa��es da ficha cl�nica.

#Caso de uso Cadastrar nova informa��o na ficha
##Pr�-condi��o: 
	.O usu�rio deve estar logado no sistema 
	.A ficha cl�nica deve conter alguma informa��es
##Objetivos: 
	.O usu�rio deve cadastrar nova informa��o na ficha sem alterar as informa��es antigas
##P�s-condi��o:
	O sistema dever� gravar a nova informa��o sem afetar as outras informa��es.

#Caso de uso Hist�rico
##Pr�-condi��o: 
	.O usu�rio deve estar logado no sistema 
	. A ficha cl�nica deve conter alguma informa��es
##Objetivos: 
	. O sistema deve conter o hist�rico das altera��es na ficha.
	.O usu�rio deve visualizar o hist�rico das altera��es na ficha.
##P�s-condi��o:

