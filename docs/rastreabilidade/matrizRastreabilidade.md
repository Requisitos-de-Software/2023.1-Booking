# BMatriz de Rastreabilidade

## Introdução

A matriz de rastreabilidade geral, tem como objetivo identificar os requisitos e suas origens, envolvendo a documentação de backward-from e foward-from. Para tal os requisitos e os artefatos que o ligam foram colocados na tabela.

## Metodologia

Consistindo em uma tabela que guardará as informações que de identificação(ID), uma descrição do requisito, de onde o mesmo foi elicitado, os artefatos que o compõe e sua implementação que consistirá em bolinhas de cores especificas de acordo com seu checklist. Através da checklist será preenchida se o requisito foi implementado no aplicativo em sua completude ou não, com base em diferentes classificações, que incluem:

- 🟢: Completo
- 🟡: Incompleto
- 🔴: Não implementado

Para a coluna dos artefatos a seguinte precedência será seguida: Rich > Cenários > Elicitação > Histórias de Usuários > Léxicos > NFR Framework > Especificações Suplementares > Casos de Usos

## Matriz de Rastreabilidade Geral

A Tabela 1 contém que contém a legenda para os acronônimos presentes na Tabela 2.

<center>

| Legenda  | Descrição                                    | Link para o Artefato                                                  |
| -------- | ---------------------------------------------- | --------------------------------------------------------------------- |
| RF       | Requisitos Funcionais                          | ---                                                                   |
| RNF      | Requisito Não-Funcionais                      | ---                                                                   |
| FST      | Requisito elicitado funcional do Storytelling | [Storytelling](../elicitacao/storytelling.md)                    |
| NFST     | Requisito não funcional do Storytelling       | [Storytelling](../elicitacao/storytelling.md)                    |
| FOBS     | Requisito funcional  da observação          | [Observação](../elicitacao/observacao.md)                      |
| NFOBS    | Requisito não funcional da observação       | [Observação](../elicitacao/observacao.md)                      |
| FB       | Requisito funcional do brainstorm              | [Brainstorm](../elicitacao/brainstorm.md)                        |
| NFB      | Requisito não funcional do brainstorm         | [Brainstorm](../elicitacao/brainstorm.md)                        |
| CONF     | Especificação Suplementar de Confiabilidade  | [Especificação Suplementar](../modelagem/especificacaoSuplementar.md)  |
| USAB     | Especificação Suplementar de Usabilidade     | [Especificação Suplementar](../modelagem/especificacaoSuplementar.md)  |
| PERF     | Especificação Suplementar de Performance     | [Especificação Suplementar](../modelagem/especificacaoSuplementar.md)  |
| SUPT     | Especificação Suplementar de Suportabilidade | [Especificação Suplementar](../modelagem/especificacaoSuplementar.md)  |
| IMPL     | Especificação Suplementar de Implementação | [Especificação Suplementar](../modelagem/especificacaoSuplementar.md)  |
| INTF     | Especificação Suplementar de Interface       | [Especificação Suplementar](../modelagem/especificacaoSuplementar.md)  |
| CSO      | Caso de Uso                                    | [Casos de Usos](../modelagem/casosDeUso.md)                      |
| C        | Cenário                                       | [Cenários](../modelagem/cenarios.md)                            |
| US       | História de Usuário                          | [Histórias de Usuário](../modelagem/modelo-agil/historiasDeUsuario.md) |
| NFR      | Non-Functional-Requirements Framework         | [NFR Framework](../modelagem/modelo-agil/nfrFramework.md)                |
| RC-FInal | Rich Picure Versão Final                      | [Rich Picture](../prePlanejamento/richPicture.md)                        |

<div style="text-align: center">
<p> Tabela 1: Legenda das tecnicas de elicitação.  (Fonte: Autores, 2023). </p>
</div>

</center>

Na Tabela 2, está contida a matriz de rastreabilidade geral, nela estão localizadas, todas os requisitos do projeto, e características que envonvem artefatos que tem envolvimento com o mesmo para definir de onde sua origem até onde chegou, e vice-versa.

| ID    | Descrição                                                                                                                                                                          | Elicitação                            | Artefatos                                                             | Implementação |
| ----- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | --------------------------------------- | --------------------------------------------------------------------- | :-------------: |
| RF01  | O aplicativo deve permitir que os usuários se registrem fornecendo informações básicas, como nome, sobrenome, endereço de e-mail e senha.                                       | Storytelling, Observação              | FST01, FOBS01, US01, L09,  SUPT01, CONF03, CSO01                   |       🟡       |
| RF02  | O aplicativo deve permitir que os usuários pesquisem acomodações com base em critérios específicos, como localização, datas de check-in e check-out, tipo de quarto e preço. | Storytelling                            | FST02, US09, L09, NFR01, USAB06, PERF02, CSO02                     |       🟢       |
| RF03  | O aplicativo deve permitir que os usuários reservem acomodações selecionadas, inserindo as informações de pagamento e confirmando a reserva.                                    | Storytelling, Brainstorm, Observação  | C03, FST03, FB03, FOBS06, US34, L15, NFR03, PERF01,  USAB01, CSO03 |       🟢       |
| RF04  | O aplicativo deve permitir que os usuários cancelem suas reservas de acomodação, desde que sejam feitas dentro dos termos e condições estabelecidos pela empresa.               | Storytelling, Brainstorm                | FST04, FB04, US24, L10, NFR03, USAB01                                |       🟢       |
| RF05  | O aplicativo deve permitir que os usuários pesquisem voos com base em critérios específicos, como origem, destino, datas e número de passageiros.                                | Storytelling                            | FST05, US09, L09, NFR03, USAB02, USAB04, CSO02                        |       🟢       |
| RF06  | O aplicativo deve permitir que os usuários reservem voos selecionados, inserindo as informações de pagamento e confirmando a reserva.                                             | Storytelling, Observação              | C02, FST06,FOBS07, US26, NFR03, USAB06, PERF02, CSO06                |       🟢       |
| RF07  | O aplicativo deve permitir que os usuários gerenciem suas reservas existentes, incluindo a visualização de detalhes da reserva, alterações de datas e cancelamentos.            | Storytelling                            | FST08, US27, L09, NFR01, USAB03, CONF04                               |       🟢       |
| RF08  | O aplicativo deve permitir que os usuários visualizem seu histórico de reservas anteriores, incluindo informações como datas, acomodações e voos reservados.                   | Storytelling, Brainstorm, Observação  | FST10, FB05, FB06, FOBS13, US27, L09, NFR01, USAB03, CONF04          |       🟢       |
| RF09  | O sistema deve possuir escolha do método de pagamento                                                                                                                               | Brainstorm                              | FB02, US29, L11, NFR03, CSO04                                         |       🟢       |
| RF10  | Permitir que um grupo de pessoas reservem um local                                                                                                                                   | Brainstorm                              | C03, FB07, US34, L15, NFR03, USAB01, SUPT01, CSO03                    |       🟡       |
| RF11  | Sincronizar as datas das reservas com o calendário do usuário                                                                                                                      | Brainstorm                              | FB09, NFR03, SUPT02, IMPL01                                           |       🔴       |
| RF12  | Permitir visualização de imagens do local pelo usuário                                                                                                                            | Brainstorm                              | C03, C04, FB12, L09, NFR03, USAB03, CONF04, PERF01                    |       🟢       |
| RF13  | Permitir visualização de imagens do carro pelo usuário                                                                                                                            | Brainstorm                              | C05, FB13, L09, NFR03, USAB03, CONF04, PERF01                         |       🟢       |
| RF14  | O sistema deve ser capaz de localizar o usuário se permitido                                                                                                                        | Brainstorm                              | FB22, L12, NFR01, USAB03, CONF03                                      |       🟢       |
| RF15  | O sistema deve sugerir hospedagens de acordo com a localização do usuário                                                                                                         | Brainstorm, Observação                | FB23 , FOBS04, US02, L04, NFR03, USAB03, USAB05, CSO03               |       🟢       |
| RF16  | O sistema deve oferecer uma aba de perguntas                                                                                                                                         | Brainstorm                              | FB24, US30, L13, NFR03, USAB04, PERF02                                |       🟢       |
| RF17  | O sistema deve conter um bate-papo para contato com o locatário ou empresa em que foi feito a reserva                                                                               | Brainstorm                              | C12, FB25, L13, NFR03, USAB04,  PERF02, CSO03                        |       🟢       |
| RF18  | O sistema deve ter um sistema de pontuação ligada ao usuário                                                                                                                      | Brainstorm, Observação                | C06, FB26, FOBS03, L07, NFR03                                        |       🟢       |
| RF19  | O usuário deve poder denunciar contas                                                                                                                                               | Brainstorm                              | FB27, US32, NFR03, USAB01, USAB04                                    |       🔴       |
| RF20  | Deve existir uma pesquisa por comando de voz                                                                                                                                         | Brainstorm                              | FB31, L09, NFR03, USAB02,  INTF01                                    |       🔴       |
| RF21  | O usuário deve poder avaliar e comentar reservas                                                                                                                                    | Brainstorm, Storytelling                | FB28 e FST09                                                          |       🟢       |
| RF22  | Deve ser possível filtrar as pesquisas.                                                                                                                                             | Observação, Brainstorm                | FOBS05, FB30, US09, NFR03, USAB01, PERF01, L15 e CSO05              |       🟢       |
| RF23  | Deve ser possível alugar carros.                                                                                                                                                    | Observação                            | C01, FOBS08, C01, US36, NFR03 e CSO05                                |       🟢       |
| RF24  | O aplicativo deve ter mapa interativo.                                                                                                                                               | Observação, Brainstorm                | FOBS10, FB14, US12, L12 e NFR03                                      |       🟢       |
| RF25  | O aplicativo deve ter uma aba de favoritos                                                                                                                                           | Observação, Brainstorm                | FOBS12, FB10, US14, L03 e NFR03                                     |       🟢       |
| RF26  | O aplicativo deve possuir uma central de ajuda ao usuário.                                                                                                                          | Observação                            | FOBS14, US20, L13 e NFR03                                            |       🟢       |
| RF27  | O aplicativo deve possuir uma área administrativa da conta.                                                                                                                         | Observação                            | C06, FOBS15, US20, L01 e NFR03                                       |       🟢       |
| RF28  | O aplicativo deve apresentar as informações legais sobre o uso para o usuário.                                                                                                    | Observação                            | C06, FOBS20, US18 e NFR03                                            |       🔴       |
| RF29  | O aplicativo deve permitir que o usuário saia da conta.                                                                                                                             | Observação                            | C06, FOBS22, US17 e NFR03                                            |       🟢       |
| RF30  | O aplicativo deve permitir que os usuários pesquisem e reservem carros de aluguel com base em critérios específicos, como localização, datas e tipo de veículo.                | Storytelling                            | FST07, FB08, US15 e L16                                              |       🟢       |
| RF31  | Enviar email sobre o status da reserva                                                                                                                                               | Brainstor                               | FB08, FB11, US13, L03 e NFR03                                        |       🟢       |
| RF32  | O sistema deve possuir uma lista de desejos para aluguel de carro, hospedagem e voos                                                                                                 | Brainstorm                              | FB11, FB15, FOBS16, US05, NFR03 e CSO04                             |       🟢       |
| RF33  | O sistema deve possuir uma carteira digital                                                                                                                                          | Brainstorm, Observação                | FB15, FB18, FOBS16, US11, L11 e NFR03                              |       🟢       |
| RF34  | O sistema deve possuir uma moeda própria                                                                                                                                            | Brainstorm                              | FB18, FB19, US11, L11 e NFR03                                        |       🟢       |
| RF35  | O usuário deve poder comprar moedas do sistema                                                                                                                                      | Brainstorm                              | FB19, FB20, US10, L05 e NFR03                                        |       🟢       |
| RF36  | O sistema deve oferecer uma opção de conta premium                                                                                                                                 | Brainstorm                              | C06, FB20, FB21, US03 e L06                                         |       🟢       |
| RF37  | O usuário deve poder selecionar o idioma do sistema                                                                                                                                 | Brainstorm                              | FB21, FB29, FOBS18, US04 e L04                                       |       🟢       |
| RF38  | O sistema deve notificar sobre ofertas                                                                                                                                               | Brainstorm, Observação                | C01, FB29, FB32, FOBS018, US08, CSO05                              |       🟢       |
| RF39  | O usuário deve poder adicionar itens ao aluguel do carro                                                                                                                            | Brainstorm                              | FB32, FOBS09, US06, NFR03                                            |       🔴       |
| RF40  | Deve ser possível contratar serviços de táxi.                                                                                                                                     | Observação                            | C05, FOBS09, FOBS11, US07 e NFR03                                   |       🟢       |
| RF41  | Deve ser possível agendar visitas à atrações turísticas.                                                                                                                        | Observação                            | C06, FOBS11, CFOBS019, US03, NFR01 e NFR03                          |       🟢       |
| RF42  | O aplicativo deve possuir um sistema de configurações do aplicativo.                                                                                                               | Observação                            | FOBS019, FOBS16, US02, L04 e NFR03                                  |       🟢       |
| RF43  | O sistema deve exibir dicas sobre os locais e carros                                                                                                                                 | Brainstorm                              | FB16, FOBS17, US01, L04                                             |       🟢       |
| RF44  | O sistema deve mostrar notícias relacionadas ao turismo                                                                                                                             | Brainstorm                              | FB17 e NFR03                                                         |       🟢       |
| RF45  | O aplicativo deve permitir o gerenciamento do companheiros de viagem, guardando as informações do companheiros para usar nas reservas                                              | Análise em Cenários                   | RC-Final, C08, US35                                                   |       🔴       |
| RF46  | O sistema deve permitir que o usuário delete sua conta através do aplicativo                                                                                                       | Análise em Cenários                   | RC-Final, C07, US37                                                  |       🔴       |
| RF47  | O aplicativo deve possuir um filtro de idade para a seção de atrações                                                                                                            | Análise em Cenários                   | C04, US38                                                            |       🔴       |
| RNF01 | O aplicativo deve ser fácil de usar, com interface intuitiva e navegação clara.                                                                                                   | Storytelling                            | NFST01                                                                |       🟢       |
| RNF02 | O aplicativo deve ser rápido e responsivo, com tempo de carregamento mínimo e tempos de resposta rápidos.                                                                         | Storytelling, Observação              | NFST02 e NFOBS01                                                      |       🟢       |
| RNF03 | O aplicativo deve estar disponível para uso em todos os momentos, com tempos de inatividade mínimos.                                                                               | Storytelling, Brainstorm                | NFST03 e NFB02                                                        |       🟢       |
| RNF04 | O aplicativo deve ser seguro, protegendo as informações dos usuários e garantindo a privacidade.                                                                                  | Storytelling, Observação, Brainstorm  | NFST04, NFOBS03 e NFB01                                               |       🟢       |
| RNF05 | O aplicativo deve ser confiável, com alta disponibilidade e poucas falhas.                                                                                                          | Storytelling                            | NFST05                                                                |       🟢       |
| RNF06 | O aplicativo deve ser compatível com uma ampla variedade de dispositivos, navegadores e sistemas operacionais.                                                                      | Storytelling, Observação, Brainstorm | NFST06, NFOBS02 e NFB05                                               |       🟢       |
| RNF07 | O aplicativo deve estar disponível em diferentes idiomas e adaptar-se a diferentes regiões e culturas.                                                                             | Storytelling                            | NFST07                                                                |       🟢       |
| RNF08 | Deve possuir acessibilidade.                                                                                                                                                         | Observação, Brainstorm                | NFOBS04 e NFB04                                                       |       🟢       |
| RNF09 | O sistema deve ter escalabilidade                                                                                                                                                    | Brainstorm, Observação                | NFB06 e NFOBS05                                                       |       🟢       |

<center>

<div style="text-align: center">
<p> Tabela 2: Matriz de Rastreabilidade.  (Fonte: Autores, 2023). </p>
</div>

</center>

## Bibiliografia

Barbosa, S. D. J.; Silva, B. S. da; Silveira, M. S.; Gasparini, I.; Darin, T.; Barbosa, G. D. J. (2021)
Interação Humano-Computador e Experiência do usuário. Autopublicação. ISBN: 978-65-00-19677-1.

Matriz de Rastreabilidade - MEI. Disponível em: https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/UserCases/. Acesso em: 28 junho 2023.

## Histórico de Versão

| Versão | Data       | Descrição                    | Autor(es)          | Revisor(es)    |
| ------- | ---------- | ------------------------------ | ------------------ | -------------- |
| 1.0     | 28/06/2023 | Criação da Página da Matriz | Gabriel e Chaydson | Lucas e Samuel |
