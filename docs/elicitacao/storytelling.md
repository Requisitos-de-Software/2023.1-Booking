# Storytelling

## Introdução

Storytelling é uma técnica de elicitação de requisitos que se baseia em histórias contadas por usuários ou clientes sobre suas experiências, necessidades e expectativas com relação a um software. Essas histórias podem ser gravadas, anotadas ou transcritas e servem como fonte de informação para os desenvolvedores entenderem melhor os requisitos do sistema.

Storytelling pode ser usada em processos de desenvolvimento ágil, como o extreme programming, para facilitar a comunicação entre os envolvidos no projeto e melhorar a qualidade do software. Storytelling também pode ser aplicada com o uso de personas, que são perfis fictícios de usuários típicos do sistema, para ilustrar cenários de uso e casos de teste.

## Metodologia

A partir das personas criadas, Lucas e Samuel elaboraram uma história que ilustra como esses perfis se relacionam com o uso do aplicativo. Assim, poderemos compreender melhor as expectativas e as necessidades dos usuários e criar requisitos que ofereçam uma experiência satisfatória e adequada para cada um deles.

## História

### Harry e o Booking: Uma Viagem para o Rio de Janeiro

Harry é um viajante europeu que gosta de conhecer novos lugares e culturas. Ele usa o aplicativo booking para pesquisar e reservar acomodações em diferentes destinos. Ele valoriza a praticidade, a segurança e o preço na hora de escolher onde ficar.

Um dia, ele decide viajar para o Rio de Janeiro e abre o aplicativo booking no seu celular. Ele digita o nome da cidade e as datas da viagem e clica em buscar. O aplicativo mostra uma lista de opções de hotéis, pousadas e apartamentos disponíveis, com fotos, avaliações, localização e preços.

Harry filtra os resultados por preço, distância do centro e nota dos hóspedes. Ele também usa o mapa para ver as acomodações mais próximas dos pontos turísticos que ele quer visitar. Ele seleciona algumas opções que lhe interessam e compara os detalhes de cada uma.

Ele escolhe um hotel que tem uma boa relação custo-benefício, uma ótima localização e boas recomendações. Ele clica em reservar e preenche seus dados pessoais e de pagamento. O aplicativo confirma a reserva e envia um e-mail com as informações do hotel e do cancelamento gratuito.

Harry fica satisfeito com a facilidade e a rapidez da reserva. Ele salva o hotel nos seus favoritos e compartilha o link com sua namorada pelo WhatsApp. Ele também acessa a seção de ofertas do aplicativo e encontra descontos em passeios e atividades no Rio de Janeiro. Ele reserva um city tour pelo aplicativo e recebe um voucher no seu e-mail.

Harry está pronto para viajar e aproveitar sua estadia no Rio de Janeiro. Ele confia no aplicativo booking para encontrar as melhores acomodações pelo melhor preço.

## Elicitação dos requisitos

### Requisitos funcionais

Na tabela 1, é possível encontrar os requisitos funcionais que foram obtidos a partir da história relatada pelo Harry, e que foram identificados como necessários para o desenvolvimento do sistema. Esses requisitos funcionais são uma lista abrangente de funcionalidades e recursos que o sistema deve possuir para atender às necessidades do usuário.

| ID    | Nome                         | Descrição                                                                                                                                                                          |
| ----- | ---------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| FST01 | Cadastro de conta            | o aplicativo deve permitir que os usuários se registrem fornecendo informações básicas, como nome, sobrenome, endereço de e-mail e senha.                                       |
| FST02 | Pesquisa de acomodações    | o aplicativo deve permitir que os usuários pesquisem acomodações com base em critérios específicos, como localização, datas de check-in e check-out, tipo de quarto e preço. |
| FST03 | Reserva de acomodações     | o aplicativo deve permitir que os usuários reservem acomodações selecionadas, inserindo as informações de pagamento e confirmando a reserva.                                    |
| FST04 | Cancelamento de reservas     | o aplicativo deve permitir que os usuários cancelem suas reservas de acomodação, desde que sejam feitas dentro dos termos e condições estabelecidos pela empresa.               |
| FST05 | Pesquisa de voos             | o aplicativo deve permitir que os usuários pesquisem voos com base em critérios específicos, como origem, destino, datas e número de passageiros.                                |
| FST06 | Reserva de voos              | o aplicativo deve permitir que os usuários reservem voos selecionados, inserindo as informações de pagamento e confirmando a reserva.                                             |
| FST07 | Aluguel de carros            | o aplicativo deve permitir que os usuários pesquisem e reservem carros de aluguel com base em critérios específicos, como localização, datas e tipo de veículo.                |
| FST08 | Gerenciamento de reservas    | o aplicativo deve permitir que os usuários gerenciem suas reservas existentes, incluindo a visualização de detalhes da reserva, alterações de datas e cancelamentos.            |
| FST09 | Avaliação de acomodações | o aplicativo deve permitir que os usuários avaliem acomodações após a conclusão da estadia, fornecendo uma classificação e feedback por escrito.                              |
| FST10 | Histórico de reservas       | o aplicativo deve permitir que os usuários visualizem seu histórico de reservas anteriores, incluindo informações como datas, acomodações e voos reservados.                   |

<div style="text-align: center">
<p> Tabela 1: Requisitos funcionais elicitados pela história do Harry. (Fonte: Autores, 2023). </p>
</div>

### Requisitos não funcionais

Na tabela 2, estão listados os requisitos não funcionais que foram identificados a partir da história do Harry, e que devem ser considerados no desenvolvimento do sistema. Esses requisitos não funcionais descrevem as características e propriedades do sistema que não estão relacionadas diretamente às suas funcionalidades, mas que são importantes para garantir sua qualidade e desempenho. Esses requisitos incluem aspectos como segurança, desempenho, usabilidade e compatibilidade, entre outros, e devem ser cuidadosamente considerados durante todo o processo de desenvolvimento do sistema.

| ID     | Nome            | Descrição                                                                                                     |
| ------ | --------------- | --------------------------------------------------------------------------------------------------------------- |
| NFST01 | Usabilidade     | o aplicativo deve ser fácil de usar, com interface intuitiva e navegação clara.                              |
| NFST02 | Desempenho      | o aplicativo deve ser rápido e responsivo, com tempo de carregamento mínimo e tempos de resposta rápidos.    |
| NFST03 | Disponibilidade | o aplicativo deve estar disponível para uso em todos os momentos, com tempos de inatividade mínimos.          |
| NFST04 | Segurança      | o aplicativo deve ser seguro, protegendo as informações dos usuários e garantindo a privacidade.             |
| NFST05 | Confiabilidade  | o aplicativo deve ser confiável, com alta disponibilidade e poucas falhas.                                     |
| NFST06 | Compatibilidade | o aplicativo deve ser compatível com uma ampla variedade de dispositivos, navegadores e sistemas operacionais. |
| NFST07 | Localização   | o aplicativo deve estar disponível em diferentes idiomas e adaptar-se a diferentes regiões e culturas.        |

<div style="text-align: center">
<p> Tabela 2: Requisitos não funcionais elicitados pela história do Harry. (Fonte: Autores, 2023). </p>
</div>

### Legendas

FST: Requisito funcional de Storytelling

NFST: Requisito NÃO funcional de Storytelling

## Bibliografia

Storytelling - Lichess. Disponível em: https://requisitos-de-software.github.io/2022.2-Lichess/elicitacao/storytelling/. Acesso em: 23 de abr. 2023.

Storytelling - Duolingo. Disponível em: https://requisitos-duolingo.github.io/duolingo/elicitacao/Storytelling/. Acesso em: 23 abr. 2023.

Utilização de storytelling como ferramenta de aquisição de requisitos em processo de desenvolvimento de software apoiados em modelos ágeis: o uso apoiado no extreme programming. Disponível em: https://revistas.unibh.br/dtec/article/view/440. Acesso em: 23 abr. 2023.

Storytelling - Guiabolso. Disponível em: https://fga-disciplinas.github.io/2019.1-Guia-Bolso/elicitacao-de-requisitos/storytelling/. Acesso em: 23 abr. 2023.

Storytelling - Guardiões da saúde. Disponível em: https://requisitos-de-software.github.io/2020.1-GuardioesdaSaude/elicitacao/elicitacao_tecnicas/storytelling/. Acesso em: 23 abr. 2023.

## Histórico de Versão

| Versão | Data       | Descrição            | Autor(es)      | Revisor(es) |
| ------- | ---------- | ---------------------- | -------------- | ----------- |
| 1.0     | 23/04/2023 | Criação do documento | Lucas e Samuel | Gabriel     |
