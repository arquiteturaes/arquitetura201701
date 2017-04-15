#Requisito : Cadastro de paciente 
##Objetivo :
O requisito trata a necessidade de inserir na ficha de cadastro do cliente sua ficha e histórico clínico. Desta forma, além das informaçõe básicas como endereço, foto, nome completo, documentos a ficha deverá também conter a informações clínicas.

##Diagrama de Classes:
![casoUso](https://github.com/arquiteturaes/arquitetura201701/blob/master/Imagens/DiagramaClassesFicha.png) 

##Diagrama de Sequencia:
![casoUso](https://github.com/arquiteturaes/arquitetura201701/blob/master/Imagens/DiagramaSequenciaFicha.png) 

## Casos de uso :

# Caso de uso Cadastrar informações na ficha clínica
## Pré-condição: 
	.O usuário deve estar logado no sistema 
## Objetivos: 
	.Na primeira consulta médica, após a análise do médico é inserida informações no cadastro.
## Pós-condição:
	.O sistema deverá gravar no cadastro do cliente as informações da ficha clínica.

#Caso de uso Alterar ficha clínica
##Pré-condição: 
	.O usuário deve estar logado no sistema 
	.A ficha clínica deve conter alguma informações
##Objetivos: 
	.Alterar informações que estão na ficha clínica do cliente.
##Pós-condição:
	.O sistema deverá gravar a alteração no cadastro do cliente as informações da ficha clínica.

#Caso de uso Cadastrar nova informação na ficha
##Pré-condição: 
	.O usuário deve estar logado no sistema 
	.A ficha clínica deve conter alguma informações
##Objetivos: 
	.O usuário deve cadastrar nova informação na ficha sem alterar as informações antigas
##Pós-condição:
	O sistema deverá gravar a nova informação sem afetar as outras informações.

#Caso de uso Histórico
##Pré-condição: 
	.O usuário deve estar logado no sistema 
	. A ficha clínica deve conter alguma informações
##Objetivos: 
	. O sistema deve conter o histórico das alterações na ficha.
	.O usuário deve visualizar o histórico das alterações na ficha.
##Pós-condição:

