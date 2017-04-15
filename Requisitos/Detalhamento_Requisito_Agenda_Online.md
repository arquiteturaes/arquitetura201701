#Requisito : Acesso � agenda online, tanto pelo paciente quanto pelo odont�logo
##Objetivo :
O requisito trata a necessidade do acesso a agenda online atualizada de consultas tanto pelo paciente quanto ao odont�logo.

##Diagrama de Sequencia:
![casoUso](https://github.com/arquiteturaes/arquitetura201701/blob/master/Imagens/DiagramaSequenciaAgenda.PNG) 

## Casos de uso :

# Caso de uso Agendar consulta
## Pr�-condi��o: 
	.O usu�rio deve estar logado no sistema .
## Objetivos: 
	.Cadastrar o agendamento com sucesso.
## P�s-condi��o:
	.O sistema dever� gravar a consulta.

#Caso de uso Alterar consulta
##Pr�-condi��o: 
	.O usu�rio deve estar logado no sistema 
	.Deve existir pelo menos uma consulta agendada
##Objetivos: 
	.Alterar agendamento da consulta.
##P�s-condi��o:
	.O sistema dever� gravar a altera��o da consulta.

#Caso de uso Excluir consulta
##Pr�-condi��o: 
	.O usu�rio deve estar logado no sistema 
	.Deve existir pelo menos uma consulta agendada
##Objetivos: 
	.O usu�rio deve excluir consulta.
##P�s-condi��o:
	O sistema dever� excluir o cadastro da consulta.

#Caso de uso Consultar agenda online
##Pr�-condi��o: 
	.O usu�rio deve estar logado no sistema 
##Objetivos: 
	.O sistema deve retornar a agenda atualiza tanto para paciente como odont�logo.
##P�s-condi��o:

