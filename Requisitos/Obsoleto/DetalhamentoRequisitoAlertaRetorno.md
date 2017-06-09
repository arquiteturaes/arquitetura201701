# Requisito : Alerta de retorno
## Objetivo :
O requisito trata a necessidade de avisar ao paciente para que o mesmo não esquece que será necessário novo agendamento de consulta. Após a consulta médica, se avaliado que o paciente precise de uma nova consulta posterior, será enviado através do aplicativo ‘Whatsapp’ um alerta de retorno.
## Fluxo :
![fluxo](https://raw.githubusercontent.com/arquiteturaes/arquitetura201701/master/Imagens/fluxoAlertaRetorno.png)
## Casos de uso :
## Caso de uso Envio de alerta.:
## Pré-condição:
.O usuário deve estar logado no sistema  
.Deve existir a necessidade de agendamento da consulta
## Fluxos de eventos:
	.É identificado a necessidade de retorno do paciente
	.O sistema deve se comunicar com o wahtsapp
	.O sistema deve enviar o alerta ao paciente
## Caso de uso Não envio de alerta.:
## Pré-condição:
.O usuário deve estar logado no sistema  
.Não deve existir a necessidade de agendamento da consulta
## Fluxos de eventos:
	.Não é identificado a necessidade de retorno do paciente
	.O sistema não envia o alerta ao paciente
Obs.: Nenhum caso de uso exige pós-condição.
