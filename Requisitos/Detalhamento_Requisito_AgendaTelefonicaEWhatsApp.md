# Requisito : Agenda Telefônica e de WhatsApp

## Objetivo :
O administrador deve cadastrar o número de telefone que possui integraçao com a aplicativo WhatsApp na ficha do paciente.
Com isso, esse telefone é armazenado, tanto na ficha do paciente, quanto em uma agenda que reune o contato de todos os cadastrados.

## Diagrama de Casos de Uso:
![casoUso](https://raw.githubusercontent.com/arquiteturaes/arquitetura201701/master/Imagens/DiagramaSequencia_AgendaWpp.png)

# Descriçao Casos de uso :
## Caso de uso Cadastrar WhatsApp
## Pré-condição:
  .O administrador deve estar logado no sistema  
  .O cliente nao deve possuir nenhum número cadastrado

## Fluxos de eventos:
	.O administrador solicita inserção de número de telefone na ficha do paciente.
  .O administrador insere o número corretamente no campo.
  .Caso nao esteja com o número de algarismos corretos, o administrador é impedido de confirmar os dados.
  .O administrador confirma os dados e este número é armazenado na ficha do paciente e em uma agenda que reúne todos os contatos dos pacientes cadastrados.
  
 ## Pos-condição:
   .Ficha do paciente e agenda com todos os números dos pacientes cadastrados são atualizadas. 
 
 
 ## Caso de uso Atualizar WhatsApp
## Pré-condição:
  .O administrador deve estar logado no sistema  
  .O cliente deve possuir nenhum número cadastrado

## Fluxos de eventos:
	.O administrador solicita modificação de número de telefone na ficha do paciente.
  .O administrador insere o número corretamente no campo.
  .Caso nao esteja com o número de algarismos corretos, o administrador é impedido de confirmar os dados.
  .O administrador confirma os dados e este número é substituído - excluindo o outro - na ficha do paciente e em uma agenda que reúne todos os contatos dos pacientes cadastrados.
  
 ## Pos-condição:
   .Ficha do paciente e agenda com todos os números dos pacientes cadastrados são atualizadas. 
 
