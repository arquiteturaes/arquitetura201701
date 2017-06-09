# Requisito : Solicitação de Prótese

## Objetivo :
Após completada pelo menos uma consulta - a ser confirmada na ficha clínica em informaçoes médicas -, o paciente tem permissao de solicitar determinada prótese indicada pelo médico, que também estar detalhada na ficha clínica. 
A prótese deve ser consultada em sua disponibilidade no estoque da instituição, e solicitada se disponivel.
Se a prótese nao estiver disponivel em estoque, deve-se fazer pedido para fornecedores, enviando solicitaçao para fabricante.

## Diagrama de sequencia


## Diagrama de classe


## Diagrama de Casos de Uso:
![casoUso](https://raw.githubusercontent.com/arquiteturaes/arquitetura201701/master/Imagens/CasoUso_Protese.png)

## Descriçao Casos de uso :
## Caso de uso prótese disponivel em estoque:
## Pré-condição:
  .O administrador deve estar logado no sistema  
  .Deve existir a necessidade de solicitação de prótese advinda de consulta anterior
  .É adicionado à ficha do paciente as informações de modelo da prótese

## Fluxos de eventos:
	.É passada para o paciente a necessidade de utilizaço de determinada prótese
	.O paciente contata administrador com poder para solicitar prótese, que faz consulta em estoque 
	.Solicita prótese para paciente 
  
 ## Pos-condição:
   .Dados de acompanhamento para retirada são acrescentados na ficha do paciente.
   
## Caso de uso nao disponivel em estoque:
## Pré-condição:
  .O administardor deve estar logado no sistema  
  .Deve existir a necessidade de solicitação de prótese advinda de consulta anterior
  .É adicionado à ficha do paciente as informações de modelo da prótese

## Fluxos de eventos:
	.É passada para o paciente a necessidade de utilizaço de determinada prótese
	.O paciente contata administrador com poder para solicitar prótese, que faz consulta em estoque 
	.Identificando a não disponibilidade em estoque, faz-se pedido para fabricante
  
  ## Pos-condição:
  .É adicionado à ficha do paciente dados de acompanhamento da prótese encomendada, como previsao de chegada.

