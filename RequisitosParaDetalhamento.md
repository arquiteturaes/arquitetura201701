# Arquitetura detalhada dos requisitos

## Agendamento
- Enviar SMS, receber SMS, relatório de enviados/recebidos: detalhar integração
- Alerta de retorno (WhatsApp): detalhar integração

## Financeiro e faturamento
- Gerenciar convênios: Dependência de sistema de plano de saúde
- Emissão de boleto e de recibos
- Integração com cielo e pagseguro
- Operadora de plano: Dependência de sistema de plano de saúde

## Fluxo de paciente
- Cadastro de paciente: buscar se os tipos de informações cadastrais impactam na construção/manutenção do BD

## Atenção à saúde
- Cadastro de paciente com fotos, Fotografias: detalhar fluxo e impacto no BD, image hosting
- Solicitação de exames: detalhar fluxo de comunicação
- Solicitação de próteses: detalhar fluxo de comunicação

## Produtos
- Requisição de produtos: detalhar comunicação com sistema externo (fornecedor)

## Pessoal
- Comunicação interna: detalhar processo e fluxos de comunicação das instâncias (entre PCs)
- Chat com colaboradores da clínica: detalhar processo e fluxos de comunicação das instâncias (entre PCs)
- Controle de ponto: avaliar necessidades operacionais (ex.: ter biometria) e legais (ex.: lei exige que certas informações sejam armazenadas de formas específicas para fins de fiscalização)

## Software e hardware
- Acesso à agenda online, tanto pelo paciente quanto pelo odontólogo: avaliar fluxos de autenticação e comunicação com BD
- Pode ser implantado em "nuvem": Levantar necessidades
- Suporte para múltiplos idiomas
- O SISB deve estar em conformidade com o Manual de Certificação da SBIS. Não conformidades deverão ser aprovadas pelo patrocinador.
- Manutenção corretiva deve ser feita em no máximo 2 dias: detalhar como será feito o processo de manutenção e implantação de atualização
- O SISB deve ser capaz de se manter em operação por um peíodo ininterrupto de 30 dias: verificar necessidade do framework utilizado (ou do próprio SISB) de ser reiniciado para manutenção
- O cenário típico de uso do SISB é uma instalação que atende 10 usuários. Outros cenários devem contemplar 50, 200, 1.000 e 10.000 usuários.
- O SISB deve estar apto para armazenar dados para 5000, 100.000 e 10.000.000 de pacientes.
- O cycle time do SISB deve ser de, no máximo, 2 horas.

# Requisitos não conhecidos/Não foi possível classificar

## Agendamento
- Mala direta: Conceito desconhecido
- Três tipos diferentes de agenda: Quais tipos?

## Financeiro e faturamento
- Comissões, NFSe: Conceito desconhecido
- Controle de faturamento de múltiplos convênios: Conceito desconhecido
- Faturamente TISS: Erro de digitação? Conceito desconhecido

## Fluxo de paciente
- Botão de pânico: Conceito desconhecido
- Importação de paciente: Interna e/ou externa? Por arquivo?

## Atenção à saúde
- Alertas: Que tipo de alerta? Paciente e/ou Médico?
- Odontograma gráfico: Conceito desconhecido, verificar necessidade de comunicar com sistema externo ou equipamento médico
- Planejamento: Possível necessidade de automação de procedimentos
- Medicamentos: informações em BD do SISB ou externo?
- CID-10: Conceito desconhecido

## Produtos
-

## Pessoal
-

## Software e hardware
- Qualidade interna. A interação de clientes (interface com o usuário) e os serviços oferecidos será projetado em conformidade com as diretrizes contidas no [API Design Guid](https://cloud.google.com/apis/design/).
- O SISB deve estar em conformidade com os padrões adotado pelo Brasil para interoperabilidade semântica: Significado dos conceitos ou também de nome de serviços e atributos?
