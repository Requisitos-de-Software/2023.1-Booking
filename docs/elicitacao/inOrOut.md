## Introdução

A priorização de requisitos desempenha um papel fundamental no desenvolvimento de projetos, pois permite tomar decisões claras sobre quais requisitos devem ser incluídos ou descartados em cada fase. Dentre as diversas abordagens existentes, destaca-se o método "Dentro ou Fora" ou "In or Out" devido à sua simplicidade e eficácia. Nessa técnica, um grupo de partes interessadas trabalha em conjunto, avaliando individualmente cada requisito e tomando uma decisão binária: ele deve ser incluído no escopo do projeto ou excluído? Essa escolha é guiada pelos objetivos de negócio do projeto, visando reduzir a lista de requisitos para o mínimo necessário no primeiro lançamento. À medida que a implementação desse lançamento avança, é possível reavaliar os requisitos previamente excluídos e repetir o processo para as próximas etapas. Essa abordagem direta permite que a equipe se concentre nos requisitos essenciais, garantindo a entrega de valor e a evolução contínua do produto ou serviço. Mais detalhes sobre a aplicação dessa técnica de priorização podem ser encontrados no tópico "Metodologia".

## Metodologia

Para aplicar a técnica "In or Out" na priorização de requisitos funcionais e não-funcionais, elicitados nos artefatos de [Observação](https://chat.openai.com/elicitacao/observacao.md), [Brainstorm](https://chat.openai.com/elicitacao/brainstorm.md) e [Storytelling](https://chat.openai.com/elicitacao/storytelling.md). Os integrantes da equipe do projeto Pedro Henrique Rodrigues e Samuel Gomes se reuniram na plataforma TEAMS com o usuário Yan Werlley de Freitas Paulo, seguindo o cronograma apresentado na tabela 1. Durante a reunião, Yan, como convidado especializado, avaliou cada requisito de forma binária, decidindo se ele deveria ser considerado prioritário no projeto. Essa avaliação foi baseada em critérios pré-estabelecidos, como impacto no negócio, esforço de implementação e outros fatores relevantes.

### Cronograma

| Local | Dia        | Horário | Entrevistadores               | Entrevistado |
| ----- | ---------- | ------- | ----------------------------- | ------------ |
| TEAMS | 28/04/2023 | 21:00   | Pedro Henrique e Samuel Gomes | Yan Werlley  |

<div style="text-align: center">
<p> Tabela 1: Cronograma planejado para entrevista com usuário do aplicativo (Fonte: autores, 2023). </p>
</div>

## Papel dos Participantes

Durante a reunião, Pedro Henrique Rodrigues e Samuel Gomes assumiram os papéis de facilitadores na aplicação da técnica "In or Out", enquanto Yan Werlly, representando o usuário, analisava cada requisito apresentado por Pedro para determinar sua prioridade como "In" ou "Out". Enquanto isso, Samuel, como membro da equipe do projeto da disciplina, registrava anotações importantes para fins de documentação futura.

## Preparação do material

Antes do processo de priorização , foi realizado preparo do material necessário para garantir uma experiência adequada aos participantes da reunião. Foram utilizados os seguintes recursos:

- Computador desktop para cada participante: Cada participante teve acesso a um computador desktop para proporcionando um ambiente de trabalho individualizado e confortável para a realização das tarefas no aplicativo.
- Fones de ouvido com microfone: Foram utilizados três conjuntos de fones de ouvido com microfone, permitindo que os participantes pudessem se comunicar facilmente durante a reunião e garantindo uma captação clara e nítida do áudio.
- Utilização do Teams: A reunião foi conduzida na plataforma Teams, que oferece suporte para a gravação de reuniões. Esse recurso foi fundamental para registrar todas as opiniões do participante.

## Resultados

A tabela 2 a seguir apresenta a lista dos Requisitos Funcionais elicitados, organizados por prioridade.

### Requisitos Funcionais

| Id      | Requisitos                                                                                            | Técnica      | Prioridade |
| ------- | ----------------------------------------------------------------------------------------------------- | ------------ | ---------- |
| FOBS01  | Deve ser possível criar uma conta com o google, facebook ou email pessoal.                            | Observação   | in         |
| FOBS02  | Deve ser possível realizar pesquisas.                                                                 | Observação   | in         |
| FOBS03  | Histórico de reservas                                                                                 | Observação   | in         |
| FOBS04  | Deve possuir um sistema de informações e recomendações.                                               | Observação   | in         |
| FOBS05  | Deve ser possível filtrar as pesquisas.                                                               | Observação   | in         |
| FOBS06  | Deve ser possível agendar hospedagem.                                                                 | Observação   | in         |
| FOBS07  | Deve ser possível agendar voos.                                                                       | Observação   | in         |
| FOBS08  | Deve ser possível alugar carros.                                                                      | Observação   | in         |
| FOBS09  | Deve ser possível contratar serviços de táxi.                                                         | Observação   | out        |
| FOBS010 | O aplicativo deve ter mapa interativo.                                                                | Observação   | in         |
| FOBS011 | Deve ser possível agendar visitas à atrações turísticas.                                              | Observação   | in         |
| FOBS012 | O aplicativo deve ter uma aba de favoritos.                                                           | Observação   | in         |
| FOBS013 | O aplicativo deve possuir um histórico de reservas.                                                   | Observação   | in         |
| FOBS014 | O aplicativo deve possuir uma central de ajuda ao usuário.                                            | Observação   | in         |
| FOBS015 | O aplicativo deve possuir uma área administrativa da conta.                                           | Observação   | in         |
| FOBS016 | O aplicativo deve possuir sistema de carteira virtual.                                                | Observação   | out        |
| FOBS017 | Deve ser possível entrar em contato com o responsável pelo serviço.                                   | Observação   | in         |
| FOBS018 | O aplicativo deve possuir um sistema de ofertas.                                                      | Observação   | in         |
| FOBS019 | O aplicativo deve possuir um sistema de configurações do aplicativo.                                  | Observação   | out        |
| FOBS020 | O aplicativo deve apresentar as informações legais sobre o uso para o usuário.                        | Observação   | in         |
| FOBS021 | O aplicativo deve permitir que o usuário cadastre uma propriedade.                                    | Observação   | in         |
| FOBS022 | O aplicativo deve permitir que o usuário saia da conta.                                               | Observação   | in         |
| FOBS023 | Deve ser possivel comprar um pacote de viagens(hospedagens, voos e etc).                              | Observação   | out        |
| FB01    | O sistema deve permitir que o usuário possa cadastrar uma conta                                       | Brainstorm   | in         |
| FB02    | O sistema deve possuir escolha do método de pagamento                                                 | Brainstorm   | in         |
| FB03    | Possibilitar o cadastro de reserva(s) pelo usuário                                                    | Brainstorm   | in         |
| FB04    | Permitir o cancelamento de reserva pelo usuário                                                       | Brainstorm   | in         |
| FB05    | Permitir que o usuário acesse o histórico de suas reservas                                            | Brainstorm   | in         |
| FB06    | Permitir a pesquisa de reserva pelo usuário                                                           | Brainstorm   | in         |
| FB07    | Permitir que um grupo de pessoas reservem um local                                                    | Brainstorm   | out        |
| FB08    | Enviar email sobre o status da reserva                                                                | Brainstorm   | in         |
| FB09    | Sincronizar as datas das reservas com o calendário do usuário                                         | Brainstorm   | out        |
| FB10    | O sistema deve possuir uma lista de favoritos para aluguel de carro, hospedagem e voos                | Brainstorm   | out        |
| FB11    | O sistema deve possuir uma lista de desejos para aluguel de carro, hospedagem e voos                  | Brainstorm   | out        |
| FB12    | Permitir visualização de imagens do local pelo usuário                                                | Brainstorm   | in         |
| FB13    | Permitir visualização de imagens do carro pelo usuário                                                | Brainstorm   | in         |
| FB14    | O sistema deve possuir um mapa interativo                                                             | Brainstorm   | in         |
| FB15    | O sistema deve possuir uma carteira digital                                                           | Brainstorm   | out        |
| FB16    | O sistema deve exibir dicas sobre os locais e carros                                                  | Brainstorm   | out        |
| FB17    | O sistema deve mostrar notícias relacionadas ao turismo                                               | Brainstorm   | out        |
| FB18    | O sistema deve possuir uma moeda própria                                                              | Brainstorm   | out        |
| FB19    | O usuário deve poder comprar moedas do sistema                                                        | Brainstorm   | out        |
| FB20    | O sistema deve oferecer uma opção de conta premium                                                    | Brainstorm   | out        |
| FB21    | O usuário deve poder selecionar o idioma do sistema                                                   | Brainstorm   | in         |
| FB22    | O sistema deve ser capaz de localizar o usuário se permitido                                          | Brainstorm   | in         |
| FB23    | O sistema deve sugerir hospedagens de acordo com a localização do usuário                             | Brainstorm   | in         |
| FB24    | O sistema deve oferecer uma aba de perguntas                                                          | Brainstorm   | in         |
| FB25    | O sistema deve conter um bate-papo para contato com o locatário ou empresa em que foi feito a reserva | Brainstorm   | in         |
| FB26    | O sistema deve ter um sistema de pontuação ligada ao usuário                                          | Brainstorm   | out        |
| FB27    | O usuário deve poder denunciar contas                                                                 | Brainstorm   | in         |
| FB28    | O usuário deve poder avaliar e comentar reservas                                                      | Brainstorm   | in         |
| FB29    | O sistema deve notificar sobre ofertas                                                                | Brainstorm   | in         |
| FB30    | O sistema deve ter filtragem de pesquisa de hospedagens, alugueis de carros e voos                    | Brainstorm   | in         |
| FB31    | Deve existir uma pesquisa por comando de voz                                                          | Brainstorm   | in         |
| FB32    | O usuário deve poder adicionar itens ao aluguel do carro                                              | Brainstorm   | out        |
| FST01   | Cadastro de conta                                                                                     | Storytelling | in         |
| FST02   | Pesquisa de acomodações                                                                               | Storytelling | in         |
| FST03   | Reserva de acomodações                                                                                | Storytelling | in         |
| FST04   | Cancelamento de reservas                                                                              | Storytelling | in         |
| FST05   | Pesquisa de voos                                                                                      | Storytelling | in         |
| FST06   | Reserva de voos                                                                                       | Storytelling | in         |
| FST07   | Aluguel de carros                                                                                     | Storytelling | in         |
| FST08   | Gerenciamento de reservas                                                                             | Storytelling | in         |
| FST09   | Avaliação de acomodações                                                                              | Storytelling | in         |
| FST10   | Deve possuir um sistema de fidelidade.                                                                | Storytelling | in         |

<div style="text-align: center">
<p> Tabela 2: Requisitos Funcionais (Fonte: Autor, 2023). </p>
</div>

A lista dos Requisitos Não Funcionais elicitados, organizados por prioridade, é apresentada na tabela 3 a seguir.

### Requisitos Não Funcionais

| Id      | Requisitos                                                            | Técnica      | Prioridade |
| ------- | --------------------------------------------------------------------- | ------------ | ---------- |
| NFOBS01 | A inteface deve ser responsiva.                                       | Observação   | in         |
| NFOBS02 | O sistema deve rodar nas principais plataformas mobile Android e iOS. | Observação   | in         |
| NFOBS03 | O sistema deve ser seguro.                                            | Observação   | in         |
| NFOBS04 | Deve possuir acessibilidade.                                          | Observação   | in         |
| NFOBS05 | Deve ser escalável.                                                   | Observação   | in         |
| NFB01   | O sistema deve ser seguro                                             | Brainstorm   | in         |
| NFB02   | O sistema deve ter um suporte que funciona 24 horas                   | Brainstorm   | in         |
| NFB03   | O sistema deve garantir a privacidade e segurança dos clientes        | Brainstorm   | in         |
| NFB04   | O sistema deve ter acessibilidade para pessoas cegas                  | Brainstorm   | in         |
| NFB05   | O sistema deve ser multiplataforma: Android e iOS                     | Brainstorm   | in         |
| NFB06   | O sistema deve ter escalabilidade                                     | Brainstorm   | in         |
| NFST01  | Usabilidade                                                           | Storytelling | in         |
| NFST02  | Desempenho                                                            | Storytelling | in         |
| NFST03  | Disponibilidade                                                       | Storytelling | in         |
| NFST04  | Segurança                                                             | Storytelling | in         |
| NFST05  | Confiabilidade                                                        | Storytelling | in         |
| NFST06  | Compatibilidade                                                       | Storytelling | in         |
| NFST07  | Localização                                                           | Storytelling | in         |

<div style="text-align: center">
<p> Tabela 3: Requisitos Não Funcionais (Fonte: Autor, 2023). </p>
</div>

### Legendas

A seguir, na Tabela 4, são apresentadas as legendas das tabelas de priorização.

| ID    | Descrição                               |
| ----- | --------------------------------------- |
| FB    | Requisito Funcional Brainstorm          |
| NFB   | Requisito Não Funcional Brainstorm      |
| FST   | Requisito funcional de Storytelling     |
| NFST  | Requisito NÃO funcional de Storytelling |
| FOBS  | Requisito funcional da Observação       |
| NFOBS | Requisito não funcional da Observação   |

<div style="text-align: center">
<p> Tabela 4: Legenda das tabelas de priorização. (Fonte: Pedro Henrique e Samuel Gomes, 2023). </p>
</div>

## Video da entrevista

A seguur no video 1, apresenta-se a gravação da entrevista realizada para priorizar os requisitos elicitados.

<iframe width="560" height="315" src="https://www.youtube.com/embed/PMOJM1eJptY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

<div style="text-align: center">
<p> Video 1: Gravação da entrevista. (Fonte: Pedro Henrique e Samuel Gomes, 2023). </p>
</div>

## Termo de consentimento

No link a seguir, está disponível o termo de consentimento assinado tanto pelos condutores da reunão quanto pelo usuário, com todas as cláusulas e informações necessárias para garantir a transparência e proteção dos envolvidos durante o processo de priorização. É importante ressaltar a importância desse documento para assegurar o cumprimento de direitos e estabelecer um ambiente de confiança mútua.

[Termo de consentimento](<../assets/pdfs/termo%20de%20consentimento%20(1)%20-%20Clicksign.pdf>)

## Bibliografia

Wiegers, K. E., & Beatty, J. (2013). Software Requirements (3rd ed.). Microsoft Press.

In or Out - Grasshopper. Disponível em: [https://requisitos-de-software.github.io/2022.2-Grasshopper/elicitacao/priorizacao/in-or-out/](). Acesso em: 24 abr. 2023.

## Histórico de versão

| Versão | Data       | Descrição                                                  | Autor(es)              | Revisor(es) |
| ------ | ---------- | ---------------------------------------------------------- | ---------------------- | ----------- |
| 1.0    | 24/04/2023 | Criação da página do In or Out                             | Pedro Henrique, Samuel | Lucas       |
| 1.1    | 28/04/2023 | Atualização da priorização com o usuário                   | Pedro Henrique, Samuel | Lucas       |
| 1.2    | 21/06/2023 | Aplicando correções apontadas pela verificação             | Pedro Henrique, Samuel | Lucas       |
| 1.3    | 04/07/2023 | Correção de textos genéricos para textos mais explicativos | Pedro Henrique, Samuel | Lucas       |
