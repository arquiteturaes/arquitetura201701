 ## Requisito : Solicitação de Exames

## Objetivo :
Após completada pelo menos uma consulta - a ser confirmada na ficha clínica em informaçoes médicas -, o paciente tem permissao de solicitar determinado exame indicado pelo médico e formalizado por um documento de encaminhamento de exame, que também estar detalhada na ficha clínica. 
O exame deve ser agendado de acordo com disponibilidade de infraestrutura e profissionais. 

## Diagrama de Casos de Uso:
![casoUso](https://raw.githubusercontent.com/arquiteturaes/arquitetura201701/master/Imagens/CasoUso_Exame.png)


## Descriçao Casos de uso :
## Casos de uso exames Radiografia Extrabucais:
## Caso de uso agendamento consulta:
## Pré-condição:
  .O administrador deve estar logado no sistema  
  .Deve existir o documento de encaminhamento para exame, advinda de consulta anterior

## Fluxos de eventos:
         .É identificada qual modalidade de exame o paciente deseja, podendo ser: 
    * Panorâmica da Face
    * Panorâmica com análise para Implantes
    * Carpal - Idade Óssea
    * ATM em norma Lateral
    * ATM em norma Frontal (Posterior/Anterior)
    * P.A. de Seio Maxilar - Watter’s
    * P.A. de MandíbulaAxial - Hirtz
    * Telerradiografia Frontal
    * Telerradiografia Lateral
    * Análise Cefalométrica Computadorizada
    
	.O administrador consulta agenda de disponibilidade para realizamento de exame buscando a data mais proxima possível
	.O administrador tambem checa a agenda online do profissional responsável por fazer o exame
	.O administrador agenda consulta para paciente
  
 ## Pos-condição:
  .É adicionado à ficha do paciente as informações de agendamento de exame, como: data, hora e local, assim como nome do profissional que ira atendê-lo.
  
  
  
## Caso de uso exames Radiografia Intrabucais:
## Pré-condição:
  .O administardor deve estar logado no sistema  
  .Deve existir o documento de encaminhamento para exame, advinda de consulta anterior

## Fluxos de eventos:
	.É identificada qual modalidade de exame o paciente deseja, podendo ser: 
    * Interproximais Posteriores (Bite-wing)
    * Localização Radiográfica
    * OclusalPeriapical Total - Check-up
    * Periapical de dentes indicados
    
	.O administrador consulta agenda de disponibilidade para realizamento de exame buscando a data mais proxima possível
	.O administrador tambem checa a agenda online do profissional responsável por fazer o exame
	.O administrador agenda consulta para paciente
  
 ## Pos-condição:
  .É adicionado à ficha do paciente as informações de agendamento de exame, como: data, hora e local, assim como nome do profissional que ira atendê-lo.




  
## Caso de uso exames Tomografia Computadorizada:
## Pré-condição:
  .O administardor deve estar logado no sistema 
  .O administrador tambem checa a agenda online do profissional responsável por fazer o exame
  .Deve existir o documento de encaminhamento para exame, advinda de consulta anterior

## Fluxos de eventos:
	.É identificada qual modalidade de exame o paciente deseja, podendo ser: 
    * ATM - Oclusão
    * Cistos-tumores
    * Dente Retido
    * Fratura Radicular
    * Implante Exerto Osseo
    * Periodontia
    * Reabsorções
    * Seios Paranasais
    * Traumatologia
    
	.O administrador consulta agenda de disponibilidade para realizamento de exame buscando a data mais proxima possível
	.O administrador tambem checa a agenda online do profissional responsável por fazer o exame
	.O administrador agenda consulta para paciente
  
 ## Pos-condição:
  .É adicionado à ficha do paciente as informações de agendamento de exame, como: data, hora e local, assim como nome do profissional que ira atendê-lo.




