# Requisito : Solicitação de Prótese

## Objetivo :
Após completada pelo menos uma consulta - a ser confirmada na ficha clínica em informaçoes médicas -, o paciente tem permissao de solicitar determinada prótese indicada pelo médico, que também estar detalhada na ficha clínica. 
A prótese deve ser consultada em sua disponibilidade no estoque da instituição, e solicitada se disponivel.
Se a prótese nao estiver disponivel em estoque, deve-se fazer pedido para fornecedores, enviando solicitaçao para fabricante.

## Fluxo [PARTE PENDENTE~ :
![fluxo](link fluxo bmpn)
- diagrama de sequencia
- casos de uso
- diagrama de classe


## Casos de uso :
## Caso de uso prótese disponivel em estoque:
## Pré-condição:
  .O administrador deve estar logado no sistema  
  .Deve existir a necessidade de solicitação de prótese advinda de consulta anterior

## Fluxos de eventos:
	.É passada para o paciente a necessidade de utilizaço de determinada prótese
	.O paciente contata administrador com poder para solicitar prótese, que faz consulta em estoque 
	.Solicita prótese para paciente 
  
 ## Pos-condição:
  .É adicionado à ficha do paciente as informações de modelo da prótese e validade
  
## Caso de uso nao disponivel em estoque:
## Pré-condição:
  .O administardor deve estar logado no sistema  
  .Deve existir a necessidade de solicitação de prótese advinda de consulta anterior

## Fluxos de eventos:
	.É passada para o paciente a necessidade de utilizaço de determinada prótese
	.O paciente contata administrador com poder para solicitar prótese, que faz consulta em estoque 
	.Identificando a não disponibilidade em estoque, faz-se pedido para fabricante
  
  ## Pos-condição:
  .É adicionado à ficha do paciente as informações da prótese encomendada, como previsao de chegada, modelo e validade

