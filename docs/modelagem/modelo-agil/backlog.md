# Backlog

## Introdução

O backlog é um poderoso recurso de gerenciamento de projetos que permite às equipes manter o controle e a organização de suas atividades, garantindo que os objetivos sejam alcançados de forma eficiente.

Em sua essência, o backlog é uma lista priorizada de tarefas, itens ou requisitos que aguardam execução ou implementação. É uma ferramenta central no framework ágil, como o Scrum, e é amplamente utilizado em diversas áreas, desde desenvolvimento de software até marketing e gerenciamento de projetos.

O backlog é geralmente composto por [histórias de usuário](./historiasDeUsuario.md), tarefas, bugs, melhorias e qualquer outra demanda ou requisito que a equipe precisa realizar. Cada item do backlog é detalhado o suficiente para que seja compreendido e implementado pela equipe responsável. Além disso, o backlog é frequentemente organizado de acordo com sua prioridade, sendo que os itens mais importantes e urgentes são colocados no topo da lista.

## Metodologia

A criação do backlog do produto foi baseada na avaliação e verificação dos requisitos funcionais coletados, seguida pela organização desses requisitos em temas e épicos. Esses temas e épicos serviram como base para a definição das [histórias de usuário](./historiasDeUsuario.md) e consequentemente, a criação do backlog.

## Requisitos elicitados

Na Tabela 1 estão registrados todos os requisitos elicitados durante o processo de elicitação, juntamente com a rastreabilidade de cada requisito.

| ID   | Requisito                                                                                                                                                                            | Priorização                                                                                                                                             |
| ---- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------- |
| RF01 | O aplicativo deve permitir que os usuários se registrem fornecendo informações básicas, como nome, sobrenome, endereço de e-mail e senha.                                       | [FST01](../../elicitacao/storytelling.md) e [FOBS01](../../elicitacao/observacao.md)                                                                          |
| RF02 | O aplicativo deve permitir que os usuários pesquisem acomodações com base em critérios específicos, como localização, datas de check-in e check-out, tipo de quarto e preço. | [FST02](../../elicitacao/storytelling.md)                                                                                                                    |
| RF03 | O aplicativo deve permitir que os usuários reservem acomodações selecionadas, inserindo as informações de pagamento e confirmando a reserva.                                    | [FST03](../../elicitacao/storytelling.md), [FB03](../../elicitacao/brainstorm.md) e [FOBS06](../../elicitacao/observacao.md)                                      |
| RF04 | O aplicativo deve permitir que os usuários cancelem suas reservas de acomodação, desde que sejam feitas dentro dos termos e condições estabelecidos pela empresa.               | [FST04](../../elicitacao/storytelling.md) e [FB04](../../elicitacao/brainstorm.md)                                                                            |
| RF05 | O aplicativo deve permitir que os usuários pesquisem voos com base em critérios específicos, como origem, destino, datas e número de passageiros.                                | [FST05](../../elicitacao/storytelling.md)                                                                                                                    |
| RF06 | O aplicativo deve permitir que os usuários reservem voos selecionados, inserindo as informações de pagamento e confirmando a reserva.                                             | [FST06](../../elicitacao/storytelling.md) e [FOBS07](../../elicitacao/observacao.md)                                                                          |
| RF07 | O aplicativo deve permitir que os usuários gerenciem suas reservas existentes, incluindo a visualização de detalhes da reserva, alterações de datas e cancelamentos.            | [FST08](../../elicitacao/storytelling.md)                                                                                                                    |
| RF08 | O aplicativo deve permitir que os usuários visualizem seu histórico de reservas anteriores, incluindo informações como datas, acomodações e voos reservados.                   | [FST10](../../elicitacao/storytelling.md), [FB05](../../elicitacao/brainstorm.md) , [FB06](../../elicitacao/brainstorm.md) e [FOBS13](../../elicitacao/observacao.md) |
| RF09 | O sistema deve possuir escolha do método de pagamento                                                                                                                               | [FB02](../../elicitacao/brainstorm.md)                                                                                                                       |
| RF10 | Permitir que um grupo de pessoas reservem um local                                                                                                                                   | [FB07](../../elicitacao/brainstorm.md)                                                                                                                       |
| RF11 | Sincronizar as datas das reservas com o calendário do usuário                                                                                                                      | [FB09](../../elicitacao/brainstorm.md)                                                                                                                       |
| RF12 | Permitir visualização de imagens do local pelo usuário                                                                                                                            | [FB12](../../elicitacao/brainstorm.md)                                                                                                                       |
| RF13 | Permitir visualização de imagens do carro pelo usuário                                                                                                                            | [FB13](../../elicitacao/brainstorm.md)                                                                                                                       |
| RF14 | O sistema deve ser capaz de localizar o usuário se permitido                                                                                                                        | [FB22](../../elicitacao/brainstorm.md)                                                                                                                       |
| RF15 | O sistema deve sugerir hospedagens de acordo com a localização do usuário                                                                                                         | [FB23](../../elicitacao/brainstorm.md) e [FOBS04](../../elicitacao/observacao.md)                                                                             |
| RF16 | O sistema deve oferecer uma aba de perguntas                                                                                                                                         | [FB24](../../elicitacao/brainstorm.md)                                                                                                                       |
| RF17 | O sistema deve conter um bate-papo para contato com o locatário ou empresa em que foi feito a reserva                                                                               | [FB25](../../elicitacao/brainstorm.md)                                                                                                                       |
| RF18 | O sistema deve ter um sistema de pontuação ligada ao usuário                                                                                                                      | [FB26](../../elicitacao/brainstorm.md) e [FOBS03](../../elicitacao/observacao.md)                                                                             |
| RF19 | O usuário deve poder denunciar contas                                                                                                                                               | [FB27](../../elicitacao/brainstorm.md)                                                                                                                       |
| RF20 | Deve existir uma pesquisa por comando de voz                                                                                                                                         | [FB31](../../elicitacao/brainstorm.md)                                                                                                                       |
| RF21 | O usuário deve poder avaliar e comentar reservas                                                                                                                                    | [FB28](../../elicitacao/brainstorm.md) e [FST09](../../elicitacao/storytelling.md)                                                                            |
| RF22 | Deve ser possível filtrar as pesquisas.                                                                                                                                             | [FOBS05](../../elicitacao/observacao.md) e [FB30](../../elicitacao/brainstorm.md)                                                                             |
| RF23 | Deve ser possível alugar carros.                                                                                                                                                    | [FOBS08](../../elicitacao/observacao.md)                                                                                                                     |
| RF24 | O aplicativo deve ter mapa interativo.                                                                                                                                               | [FOBS10](../../elicitacao/observacao.md) e [FB14](../../elicitacao/brainstorm.md)                                                                             |
| RF25 | O aplicativo deve ter uma aba de favoritos.                                                                                                                                          | [FOBS12](../../elicitacao/observacao.md) e [FB10](../../elicitacao/brainstorm.md)                                                                             |
| RF26 | O aplicativo deve possuir uma central de ajuda ao usuário.                                                                                                                          | [FOBS14](../../elicitacao/observacao.md)                                                                                                                     |
| RF27 | O aplicativo deve possuir uma área administrativa da conta.                                                                                                                         | [FOBS15](../../elicitacao/observacao.md)                                                                                                                     |
| RF28 | O aplicativo deve apresentar as informações legais sobre o uso para o usuário.                                                                                                    | [FOBS20](../../elicitacao/observacao.md)                                                                                                                     |
| RF29 | O aplicativo deve permitir que o usuário saia da conta.                                                                                                                             | [FOBS22](../../elicitacao/observacao.md)                                                                                                                     |
| RF30 | o aplicativo deve permitir que os usuários pesquisem e reservem carros de aluguel com base em critérios específicos, como localização, datas e tipo de veículo.                | [FST07](../../elicitacao/storytelling.md)                                                                                                                    |
| RF31 | Enviar email sobre o status da reserva                                                                                                                                               | [FB08](../../elicitacao/brainstorm.md)                                                                                                                       |
| RF32 | O sistema deve possuir uma lista de desejos para aluguel de carro, hospedagem e voos                                                                                                 | [FB11](../../elicitacao/brainstorm.md)                                                                                                                       |
| RF33 | O sistema deve possuir uma carteira digital                                                                                                                                          | [FB15](../../elicitacao/brainstorm.md) e [FOBS16](../../elicitacao/observacao.md)                                                                             |
| RF34 | O sistema deve possuir uma moeda própria                                                                                                                                            | [FB18](../../elicitacao/brainstorm.md)                                                                                                                       |
| RF35 | O usuário deve poder comprar moedas do sistema                                                                                                                                      | [FB19](../../elicitacao/brainstorm.md)                                                                                                                       |
| RF36 | O sistema deve oferecer uma opção de conta premium                                                                                                                                 | [FB20](../../elicitacao/brainstorm.md)                                                                                                                       |
| RF37 | O usuário deve poder selecionar o idioma do sistema                                                                                                                                 | [FB21](../../elicitacao/brainstorm.md)                                                                                                                       |
| RF38 | O sistema deve notificar sobre ofertas                                                                                                                                               | [FB29](../../elicitacao/brainstorm.md) e [FOBS018](../../elicitacao/observacao.md)                                                                            |
| RF39 | O usuário deve poder adicionar itens ao aluguel do carro                                                                                                                            | [FB32](../../elicitacao/brainstorm.md)                                                                                                                       |
| RF40 | Deve ser possível contratar serviços de táxi.                                                                                                                                     | [FOBS09](../../elicitacao/observacao.md)                                                                                                                     |
| RF41 | Deve ser possível agendar visitas à atrações turísticas.                                                                                                                        | [FOBS11](../../elicitacao/observacao.md)                                                                                                                     |
| RF42 | O aplicativo deve possuir um sistema de configurações do aplicativo.                                                                                                               | [FOBS019](../../elicitacao/observacao.md)                                                                                                                    |
| RF43 | O sistema deve exibir dicas sobre os locais e carros                                                                                                                                 | [FB16](../../elicitacao/brainstorm.md)                                                                                                                       |
| RF44 | O sistema deve mostrar notícias relacionadas ao turismo                                                                                                                             | [FB17](../../elicitacao/brainstorm.md)                                                                                                                       |

<div style="text-align: center">
<p> Tabela 1: requisitos do backlog juntamente com sua rastreabilidade (Fonte: Autores, 2023). </p>
</div>

## Backlog

### Temas

Um tema é uma categoria de requisitos relacionados a uma área específica do sistema. Ele representa um conjunto amplo de requisitos relacionados, agrupados em torno de um tópico, ajudando a identificar áreas principais do sistema.

Os temas identificados no Booking foram:

- Estadia
- Voos
- Aluguel de carros
- Atrações turísticas
- Controle de conta
- Recomendação
- Contratação de táxi

### Épicos

Um épico representa uma funcionalidade muito grande. Devido a sua natureza complexa, ele é dividido em tarefas menores e mais gerenciáveis para facilitar o acompanhamento da evolução e desenvolvimento da demanda, com isso, na tabela 2 se encontra todos os épicos e seus temas.

Os épicos identificados no Booking foram:

#### EP01 - Realizar reserva de acomodações

Eu, como usuário, desejo reservar acomodações, para poder poder me hospedar.

#### EP02 - Realizar reserva de voos

Eu, como usuário, desejo reservar voos, para viajar.

#### EP03 - Recomendações do aplicativo

Eu, como usuário, desejo comparar preços de voos semelhantes, para realizar a melhor compra.

#### EP04 - Alugar carro

Eu, como usuário, desejo alugar um ou mais carros, para realizar minhas atividades e também desejo poder personalizar o carro alugada, com opcionais, como cadeira para crianças, adaptações para pessoas com necessidades especiais, para ter um veículo que me satisfaça..

#### EP05 - Informações sobre atrações turísticas

Eu, como usuário, desejo visualizar informações detalhadas sobre as atrações turísticas de um determinado lugar, para decidir quais atividades participar.

#### EP06 - Contratação de táxi

Eu, como usuário, desejo agendar táxis, para conseguir me locomover de forma rápida.

#### EP07 - Gestão financeira

Eu, como usuário, desejo gerir meus gastos no aplicativos, para ter controle sobre minhas finanças.

#### EP08 - Gestão de reservas

Eu, como usuário, desejo gerir minhas reservas, para ter controle sobre minhas atividades.

#### EP09 - Gestão de voos

Eu, como usuário, desejo gerir meus voos, para ter controle sobre minhas atividades.

#### EP10 - Gestão da conta

Eu, como usuário, desejo gerir minha conta.

#### EP11 - Questões legais

Eu, como usuário, gostaria de ser informado sobre as questões legais do aplicativo, para ter conhecimento sobre meus direitos.

<table>
<thead>
  <tr>
    <th colspan="5">Backlog do produto</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Tema</td>
    <td>Épico</td>
    <td>História de Usuário (US)</td>
    <td>ID</td>
    <td>Prioriedade</td>
  </tr>
  <tr>
    <td rowspan="12">Estadia</td>
    <td rowspan="6">EP01</td>
    <td>Eu, como usuário, desejo realizar uma reserva de hospedagem definindo quantas pessoas e acomodações, para poder realizar a reserva de um quarto</td>
    <td><a href="../historiasDeUsuario/#us-34-reserva-de-hospedagem">US 34</a></td>
    <td>Must</td>
  </tr>
  <tr>
    <td>Eu, como usuário, gostaria de poder ter um filtro de acomodações com base na localização, datas de check-in e check-out, tipo de quarto e preço para verificar acomodações para reservar</td>
    <td><a href="../historiasDeUsuario/#us-22-pesquisa-de-acomadacoes-especifica">US 22</a></td>
    <td>Must</td>
  </tr>
  <tr>
    <td>Eu, eu como usuário, gostaria de poder denunciar contas de locadores e empresas, para tornar ou avisar ao sistema quando alguma politica de reserva, algum serviço oferecido pelo Booking foi violada por algum locador ou empresa.</td>
    <td><a href="../historiasDeUsuario/#us-32-denuncia-de-contas">US 32</a></td>
    <td>Must</td>
  </tr>
  <tr>
    <td>Eu, como usuário, gostaria de pesquisa reserva feita ou em andamento por comando de voz, para tornar mais acessível o aplicativo</td>
    <td><a href="../historiasDeUsuario/#us-33-fitro-por-comando-de-voz">US 33</a></td>
    <td>Should</td>
  </tr>
  <tr>
    <td>Eu, como usuário, desejo realizar a atividade de gerenciamento de companheiros de viagem para facilitar e deixa previamente salvo as definições de quantidade e informações extras de pessoas a qual estarei acompanhado, para facilitar reservas e ter um bom uso do aplicativo</td>
    <td><a href="../historiasDeUsuario/#us-35-gerenciamento-de-companheiros-de-viagem">US 35</a></td>
    <td>Must</td>
  </tr>
  <tr>
    <td>Eu, como usuário, gostaria de um bate-papo com o locador ou empresa responsável pela reserva do local, para tirar dúvidas sobre a hospedagem, local e dados sobre a região</td>
    <td><a href="../historiasDeUsuario/#us-31-bate-papo-com-o-locador-ou-empresa">US 31</a></td>
    <td>Must</td>
  </tr>
  <tr>
    <td rowspan="6">EP09</td>
    <td>Como usuário do aplicativo, quero poder visualizar meu histórico de reservas para acompanhar minhas atividades passadas.</td>
    <td><a href="../historiasDeUsuario/#us-21-historico-de-reservas">US 21</a></td>
    <td>Must</td>
  </tr>
  <tr>
    <td>Como usuário do aplicativo, quero poder avaliar acomodações após a conclusão da minha estadia, fornecendo uma classificação e feedback por escrito.</td>
    <td><a href="../historiasDeUsuario/#us-16-avaliacao-de-acomodacoes-por-usuarios">US 16</a></td>
    <td>Must</td>
  </tr>
  <tr>
    <td>Como um usuário do sistema que realizou uma reserva de aluguel de carro, hospedagem ou voo, quero receber um email com informações sobre o status da minha reserva para que eu possa me manter atualizado e ter certeza de que tudo está correndo conforme o planejado.</td>
    <td><a href="../historiasDeUsuario/#us-15-envio-de-email-sobre-o-status-da-reserva">US 15</a></td>
    <td>Must</td>
  </tr>
  <tr>
    <td>Eu, como usuário desejo cancelar minha reserva, para que possa receber meu dinheiro de volta.</td>
    <td><a href="../historiasDeUsuario/#us-24-cancelamento-de-reserva">US 24</a></td>
    <td>Must</td>
  </tr>
  <tr>
    <td>Eu, como usuário gostaria de poder realizar as atividades de gerenciamento de reserva como  para a visualização de detalhes da reserva, alterações de datas e cancelamentos, para ser fácil de saber a existência das minhas reservas atuais.</td>
    <td><a href="../historiasDeUsuario/#us-27-gerenciamento-de-reservas">US 27</a></td>
    <td>Must</td>
  </tr>
  <tr>
    <td>Eu, como usuário, gostaria que o sistema filtrasse o histórico de reservas por categoria, nome ou data da reserva, para localizar melhor a reserva feitas</td>
    <td><a href="../historiasDeUsuario/#us-28-filtro-de-historico-de-reservas">US 28</a></td>
    <td>Must</td>
  </tr>
  <tr>
    <td rowspan="4">Voos</td>
    <td rowspan="2">EP02</td>
    <td>Eu, como usuário, gostaria de confirmar a reserva do voo inserindo informações de pagamento, para confirmar a reserva do voo.</td>
    <td><a href="../historiasDeUsuario/#us-26-reserva-de-voo">US 26</a></td>
    <td>Must</td>
  </tr>
  <tr>
    <td>Eu, como usuário, gostaria de realizar a reserva do voo, para pode realizar compras no aplicativo.</td>
    <td><a href="../historiasDeUsuario/#us-25-filtro-de-voo">US 25</a></td>
    <td>Must</td>
  </tr>
  <tr>
    <td rowspan="2">EP10</td>
    <td>Eu, como usuário desejo cancelar minha reserva, para que possa receber meu dinheiro de volta.</td>
    <td><a href="../historiasDeUsuario/#us-24-cancelamento-de-reserva">US 24</a></td>
    <td>Must</td>
  </tr>
  <tr>
    <td>Eu, como usuário, desejo reserva voos com origem e origem, data de ida em que irá ocorrer o voo, e volta se possível, e número de passagem e classes do voo, para conseguir realizar uma viagem de bom humor.</td>
    <td><a href="../historiasDeUsuario/#us-25-filtro-de-voo">US 25</a></td>
    <td>Must</td>
  </tr>
  <tr>
    <td rowspan="3">Aluguel de carros</td>
    <td rowspan="3">EP04</td>
    <td>Eu, como usuário desejo realizar um aluguel de carro com opção de devolver o carro ao mesmo local, o local da retirada do carro, da inicio e fim do aluguel e idade do condutor</td>
    <td><a href="../historiasDeUsuario/#us-36-aluguel-de-carros">US 36</a></td>
    <td>Must</td>
  </tr>
  <tr>
    <td>Como um usuário do aplicativo interessado em alugar um carro para minhas viagens, quero poder adicionar itens extras ao meu aluguel, como GPS, cadeirinha de bebê e seguro adicional, para que eu possa personalizar minha experiência de aluguel de acordo com minhas necessidades.</td>
    <td><a href="../historiasDeUsuari/#us-08-adicionar-itens-ao-aluguel-do-carro">US 08</a></td>
    <td>Must</td>
  </tr>
  <tr>
    <td>Como um usuário do sistema interessado em planejar minhas viagens, quero poder adicionar opções de aluguel de carro, hospedagem e voos à minha lista de desejos para que eu possa salvar minhas opções favoritas e acessá-las facilmente mais tarde.</td>
    <td><a href="../historiasDeUsuario/#us-13-lista-de-desejos-para-aluguel-de-carro-hospedagem-e-voos">US 13</a></td>
    <td>Could</td>
  </tr>
  <tr>
    <td>Atrações turísticas</td>
    <td>EP05</td>
    <td>Como um usuário do aplicativo interessado em planejar minhas viagens, quero poder agendar visitas a atrações turísticas diretamente pelo aplicativo para que eu possa garantir minha entrada e evitar filas.</td>
    <td><a href="../historiasDeUsuario/#us-06-agendamento-de-visitas-a-atracoes-turisticas">US 06</a></td>
    <td>Must</td>
  </tr>
  <tr>
    <td rowspan="3">Contratação de táxi</td>
    <td rowspan="3">EP06</td>
    <td>Como um usuário do aplicativo interessado em me locomover durante minhas viagens, quero poder contratar serviços de táxi diretamente pelo aplicativo para que eu possa me deslocar de maneira rápida e conveniente.</td>
    <td><a href="../historiasDeUsuario/#us-07-contratacao-de-servicos-de-taxi">US 07</a></td>
    <td>Must</td>
  </tr>
  <tr>
    <td>Como um usuário do aplicativo interessado em planejar minhas viagens, quero poder usar filtros de pesquisa ao procurar hospedagens, alugueis de carros e voos para que eu possa encontrar opções que atendam às minhas necessidades e preferências.</td>
    <td><a href="../historiasDeUsuario/#us-09-filtragem-de-pesquisa-de-hospedagens-alugueis-de-carros-voos-atracoes-e-taxi">US 09</a></td>
    <td>Must</td>
  </tr>
  <tr>
    <td>Como um usuário do sistema interessado em explorar destinos turísticos, quero ter acesso a um mapa interativo para que eu possa visualizar informações sobre diferentes locais e planejar minhas viagens de maneira mais eficiente.</td>
    <td><a href="../historiasDeUsuario/#us-12-mapa-interativo">US 12</a></td>
    <td>Must</td>
  </tr>
  <tr>
    <td rowspan="13">Controle de contas</td>
    <td>EP11</td>
    <td>Como um usuário do aplicativo interessado em gerenciar meus gastos, quero ter acesso a um sistema de carteira virtual para que eu possa adicionar fundos e realizar pagamentos diretamente pelo aplicativo.</td>
    <td><a href="../historiasDeUsuario/#us-05-carteira-virtual-no-aplicativo">US 05</a></td>
    <td>Must</td>
  </tr>
  <tr>
    <td></td>
    <td>Eu como usuário gostaria de poder escolher a forma de pagamento, para ter mais opções para pagar as reservas feitas</td>
    <td><a href="../historiasDeUsuario/#us-29-escolha-de-pagamento">US 29</a></td>
    <td>Must</td>
  </tr>
  <tr>
    <td></td>
    <td>Como um usuário do aplicativo interessado em economizar dinheiro, quero ter acesso a um sistema de ofertas para que eu possa encontrar e aproveitar descontos e promoções em produtos e serviços relacionados ao turismo.</td>
    <td><a href="../historiasDeUsuario/#us-04-sistema-de-ofertas">US 04</a></td>
    <td>Must</td>
  </tr>
  <tr>
    <td></td>
    <td>Como um usuário do sistema interessado em realizar transações dentro do sistema, quero poder comprar moedas do sistema para que eu possa usá-las para adquirir produtos e serviços oferecidos pelo sistema.</td>
    <td><a href="../historiasDeUsuario/#us-11-compra-de-moedas-do-sistema">US 11</a></td>
    <td>Could</td>
  </tr>
  <tr>
    <td></td>
    <td>Como um usuário do aplicativo, quero ter acesso a um sistema de configurações para que eu possa personalizar minha experiência de uso do aplicativo de acordo com minhas preferências.</td>
    <td><a href="../historiasDeUsuario/#us-03-sistema-de-configuracoes">US 03</a></td>
    <td>Must</td>
  </tr>
  <tr>
    <td></td>
    <td>Como um usuário do sistema interessado em ter acesso a recursos e benefícios exclusivos, quero poder assinar uma conta premium para que eu possa aproveitar ao máximo minha experiência de uso do sistema.</td>
    <td><a href="../historiasDeUsuario/#us-10-conta-premium-no-sistema">US 10</a></td>
    <td>Must</td>
  </tr>
  <tr>
    <td></td>
    <td>Como um usuário do sistema interessado em planejar minhas viagens, quero poder adicionar opções de aluguel de carro, hospedagem e voos à minha lista de favoritos para que eu possa salvar minhas opções preferidas e acessá-las facilmente mais tarde.</td>
    <td><a href="../historiasDeUsuario/#us-14-lista-de-favoritos-para-aluguel-de-carro-hospedagem-e-voos">US 14</a></td>
    <td>Must</td>
  </tr>
  <tr>
    <td></td>
    <td>Como usuário do aplicativo, quero poder sair da minha conta a qualquer momento.</td>
    <td><a href="../historiasDeUsuario/#us-17-sair-da-conta">US 17</a></td>
    <td>Must</td>
  </tr>
  <tr>
    <td></td>
    <td>Como usuário do aplicativo, quero poder acessar uma área administrativa da minha conta para gerenciar minhas informações e preferências.</td>
    <td><a href="../historiasDeUsuario/#us-19-area-administrativa-da-conta">US 19</a></td>
    <td>Must</td>
  </tr>
  <tr>
    <td></td>
    <td>Como usuário do aplicativo, quero poder acessar uma central de ajuda para obter informações e suporte sobre o uso do aplicativo.</td>
    <td><a href="../historiasDeUsuario/#us-20-central-de-ajuda-ao-usuario">US 20</a></td>
    <td>Must</td>
  </tr>
  <tr>
    <td></td>
    <td>Eu, como usuário, desejo deletar minha conta, para não deixar dados meus no aplicativo e por não ter mais uso para mim</td>
    <td><a href="../historiasDeUsuario/#us-37-deletar-conta">US 37</a></td>
    <td>Must</td>
  </tr>
  <tr>
    <td rowspan="2">EP12</td>
    <td>Como usuário do aplicativo, quero poder acessar as informações legais sobre o uso do aplicativo.</td>
    <td><a href="../historiasDeUsuario/#us-18-apresentacao-de-informacoes-legais">US 18</a></td>
    <td>Must</td>
  </tr>
  <tr>
    <td>Eu, como usuário, gostaria de participar de um chat para realizar perguntas sobre dúvidas que possuo, para poder responder dpuvidas que eu tenha sobre o aplicativo, ou as politicas de reservas feitas</td>
    <td><a href="../historiasDeUsuario/#us-30-perguntas-frequentes">US 30</a></td>
    <td>Must</td>
  </tr>
  <tr>
    <td rowspan="2">Recomendação</td>
    <td rowspan="2">EP03</td>
    <td>Como um usuário interessado em viagens e carros, quero ver dicas sobre locais e carros no sistema para que eu possa planejar minhas viagens e escolher o melhor carro para minhas necessidades.</td>
    <td><a href="../historiasDeUsuario/#us-02-dicas-sobre-locais-e-carros">US 02</a></td>
    <td>Must</td>
  </tr>
  <tr>
    <td>Como um usuário interessado em turismo, quero ver notícias relacionadas ao turismo no sistema para que eu possa me manter atualizado sobre os últimos acontecimentos e tendências do setor.</td>
    <td><a href="../historiasDeUsuario/#us-01-noticias-do-turismo">US 01</a>a</td>
    <td>Must</td>
  </tr>
</tbody>
</table>

<div style="text-align: center">
<p>
Tabela 2: Backlog do produto (Fonte: Autores, 2023).
</p>
</div>

## Bibliografia

Backlog - Lichess. Disponível em: [https://requisitos-de-software.github.io/2022.2-Lichess/modelagem/agil/backlog/](https://requisitos-de-software.github.io/2022.2-Lichess/modelagem/agil/backlog/). Acesso em: 21 jun. 2023.

‌Software Engineering Body of Knowledge (SWEBOK). Disponível em: [https://www.computer.org/education/bodies-of-knowledge/software-engineering](https://www.computer.org/education/bodies-of-knowledge/software-engineering). Acesso em: 21 jun. 2023.

## Histórico de Versão

| Versão | Data       | Descrição                                       | Autor(es)        | Revisor(es)     |
| ------- | ---------- | ------------------------------------------------- | ---------------- | --------------- |
| 1.0     | 24/05/2023 | Criação do documento                            | Lucas e Chaydson | Henrique        |
| 1.1     | 24/06/2023 | Concertando o que foi solicitado na verificação | Lucas            | Gabriel e Pedro |
| 1.2     | 27/06/2023 | Deletando requisitos repitidos                    | Lucas            | Gabriel e Pedro |
