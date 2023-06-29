# Matriz de Rastreabilidade

## Introdução


## Metodologia

Consistindo em uma tabela que guardará as informações que de identificação(ID), uma descrição do requisito, de onde o mesmo foi elicitado, os artefatos que o compõe e sua implementação que consistirá em bolinhas de cores especificas de acordo com seu checklist. Através da checklist será preenchida se o requisito foi implementado no aplicativo em sua completude ou não, com base em diferentes classificações, que incluem:

- 🟢: Completo
- 🟡: Incompleto
- 🔴: Não implementado

## Matriz de Rastreabilidade Geral

Na Tabela 2, está contida a matriz de rastreabilidade geral, nela estão localizadas, todas os requisitos do projeto, e características que envonvem artefatos que tem envolvimento com o mesmo para definir de onde sua origem até onde chegou, e vice-versa.

| ID    | Descrição                                                                                                                                                                          | Elicitação                            | Artefatos                  | Implementação |
| ----- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | --------------------------------------- | -------------------------- | :-------------: |
| RF01  | O aplicativo deve permitir que os usuários se registrem fornecendo informações básicas, como nome, sobrenome, endereço de e-mail e senha.                                       | Storytelling, Observação              | CSO01, L09, FST01 e FOBS01 |       🟡       |
| RF02  | O aplicativo deve permitir que os usuários pesquisem acomodações com base em critérios específicos, como localização, datas de check-in e check-out, tipo de quarto e preço. | Storytelling                            | FST02                      |       🟢       |
| RF03  | O aplicativo deve permitir que os usuários reservem acomodações selecionadas, inserindo as informações de pagamento e confirmando a reserva.                                    | Storytelling, Brainstorm, Observação  | FST03, FB03 e FOBS06       |       🟢       |
| RF04  | O aplicativo deve permitir que os usuários cancelem suas reservas de acomodação, desde que sejam feitas dentro dos termos e condições estabelecidos pela empresa.               | Storytelling, Brainstorm                | FST04 e FB04               |       🟢       |
| RF05  | O aplicativo deve permitir que os usuários pesquisem voos com base em critérios específicos, como origem, destino, datas e número de passageiros.                                | Storytelling                            | FST05                      |       🟢       |
| RF06  | O aplicativo deve permitir que os usuários reservem voos selecionados, inserindo as informações de pagamento e confirmando a reserva.                                             | Storytelling, Observação              | FST06 e FOBS07             |       🟢       |
| RF07  | O aplicativo deve permitir que os usuários gerenciem suas reservas existentes, incluindo a visualização de detalhes da reserva, alterações de datas e cancelamentos.            | Storytelling                            | FST08                      |       🟢       |
| RF08  | O aplicativo deve permitir que os usuários visualizem seu histórico de reservas anteriores, incluindo informações como datas, acomodações e voos reservados.                   | Storytelling, Brainstorm, Observação  | FST10, FB05, FB06 e FOBS13 |       🟢       |
| RF09  | O sistema deve possuir escolha do método de pagamento                                                                                                                               | Brainstorm                              | FB02                       |       🟢       |
| RF10  | Permitir que um grupo de pessoas reservem um local                                                                                                                                   | Brainstorm                              | FB07                       |       🟡       |
| RF11  | Sincronizar as datas das reservas com o calendário do usuário                                                                                                                      | Brainstorm                              | FB09                       |       🔴       |
| RF12  | Permitir visualização de imagens do local pelo usuário                                                                                                                            | Brainstorm                              | FB12                       |       🟢       |
| RF13  | Permitir visualização de imagens do carro pelo usuário                                                                                                                            | Brainstorm                              | FB13                       |       🟢       |
| RF14  | O sistema deve ser capaz de localizar o usuário se permitido                                                                                                                        | Brainstorm                              | FB22                       |       🟢       |
| RF15  | O sistema deve sugerir hospedagens de acordo com a localização do usuário                                                                                                         | Brainstorm, Observação                | FB23 e FOBS04              |       🟢       |
| RF16  | O sistema deve oferecer uma aba de perguntas                                                                                                                                         | Brainstorm                              | FB24                       |       🟢       |
| RF17  | O sistema deve conter um bate-papo para contato com o locatário ou empresa em que foi feito a reserva                                                                               | Brainstorm                              | FB25                       |       🟢       |
| RF18  | O sistema deve ter um sistema de pontuação ligada ao usuário                                                                                                                      | Brainstorm, Observação                | FB26 e FOBS03              |       🟢       |
| RF19  | O usuário deve poder denunciar contas                                                                                                                                               | Brainstorm                              | FB27                       |       🔴       |
| RF20  | Deve existir uma pesquisa por comando de voz                                                                                                                                         | Brainstorm                              | FB31                       |       🔴       |
| RF21  | O usuário deve poder avaliar e comentar reservas                                                                                                                                    | Brainstorm, Storytelling                | FB28 e FST09               |       🟢       |
| RF22  | Deve ser possível filtrar as pesquisas.                                                                                                                                             | Observação, Brainstorm                | FOBS05 e FB30              |       🟢       |
| RF23  | Deve ser possível alugar carros.                                                                                                                                                    | Observação                            | FOBS08                     |       🟢       |
| RF24  | O aplicativo deve ter mapa interativo.                                                                                                                                               | Observação, Brainstorm                | FOBS10 e FB14             |       🟢       |
| RF25  | O aplicativo deve ter uma aba de favoritos                                                                                                                                           | Observação, Brainstorm                | FOBS12 e FB10             |       🟢       |
| RF26  | O aplicativo deve possuir uma central de ajuda ao usuário.                                                                                                                          | Observação                            |                            |       🟢       |
| RF27  | O aplicativo deve possuir uma área administrativa da conta.                                                                                                                         | Observação                            |                            |       🟢       |
| RF28  | O aplicativo deve apresentar as informações legais sobre o uso para o usuário.                                                                                                    | Observação                            |                            |       🔴       |
| RF29  | O aplicativo deve permitir que o usuário saia da conta.                                                                                                                             | Observação                            |                            |       🟢       |
| RF30  | O aplicativo deve permitir que os usuários pesquisem e reservem carros de aluguel com base em critérios específicos, como localização, datas e tipo de veículo.                | Storytelling                            |                            |       🟢       |
| RF31  | Enviar email sobre o status da reserva                                                                                                                                               | Brainstorm                              |                            |       🟢       |
| RF32  | O sistema deve possuir uma lista de desejos para aluguel de carro, hospedagem e voos                                                                                                 | Brainstorm                              |                            |       🟢       |
| RF33  | O sistema deve possuir uma carteira digital                                                                                                                                          | Brainstorm, Observação                |                            |       🟢       |
| RF34  | O sistema deve possuir uma moeda própria                                                                                                                                            | Brainstorm                              |                            |       🟢       |
| RF35  | O usuário deve poder comprar moedas do sistema                                                                                                                                      | Brainstorm                              |                            |       🟢       |
| RF36  | O sistema deve oferecer uma opção de conta premium                                                                                                                                 | Brainstorm                              |                            |       🟢       |
| RF37  | O usuário deve poder selecionar o idioma do sistema                                                                                                                                 | Brainstorm                              |                            |       🟢       |
| RF38  | O sistema deve notificar sobre ofertas                                                                                                                                               | Brainstorm, Observação                |                            |       🟢       |
| RF39  | O usuário deve poder adicionar itens ao aluguel do carro                                                                                                                            | Brainstorm                              |                            |       🔴       |
| RF40  | Deve ser possível contratar serviços de táxi.                                                                                                                                     | Observação                            |                            |       🟢       |
| RF41  | Deve ser possível agendar visitas à atrações turísticas.                                                                                                                        | Observação                            |                            |       🟢       |
| RF42  | O aplicativo deve possuir um sistema de configurações do aplicativo.                                                                                                               | Observação                            |                            |       🟢       |
| RF43  | O sistema deve exibir dicas sobre os locais e carros                                                                                                                                 | Brainstorm                              |                            |       🟢       |
| RF44  | O sistema deve mostrar notícias relacionadas ao turismo                                                                                                                             | Brainstorm                              |                            |       🟢       |
| RF45  | O aplicativo deve permitir o gerenciamento do companheiros de viagem, guardando as informações do companheiros para usar nas reservas                                              | Análise em Cenários                   |                            |       🔴       |
| RF46  | O sistema deve permitir que o usuário delete sua conta através do aplicativo                                                                                                       | Análise em Cenários                   |                            |       🔴       |
| RF47  | O aplicativo deve possuir um filtro de idade para a seção de atrações                                                                                                            | Análise em Cenários                   |                            |       🔴       |
| RNF01 | O aplicativo deve ser fácil de usar, com interface intuitiva e navegação clara.                                                                                                   | Storytelling                            |                            |       🟢       |
| RNF02 | O aplicativo deve ser rápido e responsivo, com tempo de carregamento mínimo e tempos de resposta rápidos.                                                                         | Storytelling, Observação              |                            |       🟢       |
| RNF03 | O aplicativo deve estar disponível para uso em todos os momentos, com tempos de inatividade mínimos.                                                                               | Storytelling, Brainstorm                |                            |       🟢       |
| RNF04 | O aplicativo deve ser seguro, protegendo as informações dos usuários e garantindo a privacidade.                                                                                  | Storytelling, Observação, Brainstorm  |                            |       🟢       |
| RNF05 | O aplicativo deve ser confiável, com alta disponibilidade e poucas falhas.                                                                                                          | Storytelling                            |                            |       🟢       |
| RNF06 | O aplicativo deve ser compatível com uma ampla variedade de dispositivos, navegadores e sistemas operacionais.                                                                      | Storytelling, Observação, Brainstorm |                            |       🟢       |
| RNF07 | O aplicativo deve estar disponível em diferentes idiomas e adaptar-se a diferentes regiões e culturas.                                                                             | Storytelling                            |                            |       🟢       |
| RNF08 | Deve possuir acessibilidade.                                                                                                                                                         | Observação, Brainstorm                |                            |       🟢       |
| RNF09 | O sistema deve ter escalabilidade                                                                                                                                                    | Brainstorm, Observação                |                            |       🟢       |

## Bibiliografia

Barbosa, S. D. J.; Silva, B. S. da; Silveira, M. S.; Gasparini, I.; Darin, T.; Barbosa, G. D. J. (2021)
Interação Humano-Computador e Experiência do usuário. Autopublicação. ISBN: 978-65-00-19677-1.

Matriz de Rastreabilidade - MEI. Disponível em: https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/UserCases/. Acesso em: 28 junho 2023.

## Histórico de Versão

| Versão | Data       | Descrição                    | Autor(es)          | Revisor(es)    |
| ------- | ---------- | ------------------------------ | ------------------ | -------------- |
| 1.0     | 28/06/2023 | Criação da Página da Matriz | Gabriel e Chaydson | Lucas e Samuel |
