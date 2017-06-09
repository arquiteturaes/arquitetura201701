#Requisito : Acesso à agenda online, tanto pelo paciente quanto pelo odontólogo
##Objetivo :
O requisito trata a necessidade do acesso a agenda online atualizada de consultas tanto pelo paciente quanto ao odontólogo.

##Diagrama de Sequencia:
![casoUso](https://github.com/arquiteturaes/arquitetura201701/blob/master/Imagens/DiagramaSequenciaAgenda.PNG) 

## Casos de uso :

# Caso de uso Agendar consulta
## Pré-condição: 
	.O usuário deve estar logado no sistema .
## Objetivos: 
	.Cadastrar o agendamento com sucesso.
## Pós-condição:
	.O sistema deverá gravar a consulta.

#Caso de uso Alterar consulta
##Pré-condição: 
	.O usuário deve estar logado no sistema 
	.Deve existir pelo menos uma consulta agendada
##Objetivos: 
	.Alterar agendamento da consulta.
##Pós-condição:
	.O sistema deverá gravar a alteração da consulta.

#Caso de uso Excluir consulta
##Pré-condição: 
	.O usuário deve estar logado no sistema 
	.Deve existir pelo menos uma consulta agendada
##Objetivos: 
	.O usuário deve excluir consulta.
##Pós-condição:
	O sistema deverá excluir o cadastro da consulta.

#Caso de uso Consultar agenda online
##Pré-condição: 
	.O usuário deve estar logado no sistema 
##Objetivos: 
	.O sistema deve retornar a agenda atualiza tanto para paciente como odontólogo.
##Pós-condição:

