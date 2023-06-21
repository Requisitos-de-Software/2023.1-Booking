# Three Level-Scale

## Introdução

A Three-Level Scale é uma técnica de priorização que divide os requisitos em três categorias: alta, média e baixa. Essas categorias se baseiam na importância e na urgência de cada requisito para o produto, mas não são precisas e podem mudar conforme o contexto. Por isso, é importante que os desenvolvedores e os stakeholders definam os critérios de priorização antes de usar essa técnica.

Uma forma de estimar a prioridade dos requisitos é usar uma matriz de quatro quadrantes, que considera a importância e a urgência de cada um. Os requisitos podem ser classificados como:

- Importantes e urgentes: são os de alta prioridade, que devem ser feitos no próximo lançamento;
- Importantes mas não urgentes: são os de média prioridade, que podem ser feitos em um lançamento futuro;
- Não importantes e não urgentes: são os de baixa prioridade, que não trazem muito valor ao produto e podem ser eliminados ou revisados.

## Metodologia

Será utilizado o aplicativo Lucidchart para a criação da matriz de priorização, onde será divido em 4 quadrantes, como mostrado na figura 1, sendo eles:

- Importantes e urgentes: são os de alta prioridade, que devem ser feitos no próximo lançamento;
- Importantes mas não urgentes: são os de média prioridade, que podem ser feitos em um lançamento futuro;
- Não importantes e não urgentes: são os de baixa prioridade, que não trazem muito valor ao produto e podem ser eliminados ou revisados.
- Não importantes mas urgentes: são os de baixa prioridade, que não trazem muito valor ao produto e podem ser eliminados ou revisados.

<img src="../../images/threeLevelScale/lucidchart.png">

<div style="text-align: center">
<p> Figura 1: Matriz montada no aplicativo LucidChart (Fonte: Autores, 2023). </p>
</div>

Para a aplicação do three-level scale, será utilizada a ténica de interpretação, encontrada na tabela 1, onde os participantes irão interpretar alguma das [personas](../elicitacao/personas.md)
 criadas anteriormente, e assim, irão definir quais são os requisitos mais importantes e urgentes para a persona interpretada.

| Participante | Papel interpretado                             |
| ------------ | ---------------------------------------------- |
| Lucas        | Intermediador                                  |
| Henrique     | [Paulo](../elicitacao/personas.md) (Persona)      |
| Gabriel      | [Sebastião](../elicitacao/personas.md) (Persona) |

<div style="text-align: center">
<p> Tabela 1: Participante da encenação e sua respectiva persona (Fonte: Autores, 2023). </p>
</div>

## Resultados

No fim do Three Level-Scale, obtimos o seguinte resultado encontrado na figura 2, vale ressaltar que por mais que alguns requisitos, na gravação foram colocadas como não importante e não urgente, na finalização, foram movidos estes requisitos para o terceiro quadrante, você consegue acessar esse arquivo em: [LucidChart](https://lucid.app/lucidspark/dd8cc0ff-db66-442f-bbb2-f3ff08a9e4e0/edit?viewport_loc=-2726%2C-2007%2C6405%2C3357%2C0_0&invitationId=inv_70208c40-ba78-49d5-85f0-ccbb38edb092)

### Entrevista com o usuário

Conforme indicado na Tabela 1, os membros do projeto realizaram a análise das necessidades dos usuários, por meio de uma reunião no teams, conforme descrito na Tabela 2, o que permitiu definir a seguinte ordem de prioridade, conforme descrito no Vídeo 1:

| Localização | Data       | Hora          |
| ------------- | ---------- | ------------- |
| Teams         | 24/04/2023 | 20:00 - 20:35 |

Tabela 2: Horário do Brainstorm. (Fonte: Autores, 2023).

<iframe width="560" height="315" src="https://www.youtube.com/embed/4dyfl386uHo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

<div style="text-align: center">
<p>Vídeo 1 - Gravação com participantes do Three Level-Scale (Fonte: Autores, 2023). </p>
</div>

<img src="../../images/threeLevelScale/lucidchartPronto.png"/>
<div style="text-align: center">
<p>Figura 2 - Resultados do Three Level-Scale (Fonte: Autores, 2023). </p>
</div>

### Alta prioridade

A partir da priorização Three Level-Scale, foi obtido como requisitos de alta prioridade os seguintes requisitos descritos na Tabela 33.

| ID                                   | requisito                                                                                                                                                                            |
| ------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| [FST01](../elicitacao/storytelling.md)  | o aplicativo deve permitir que os usuários se registrem fornecendo informações básicas, como nome, sobrenome, endereço de e-mail e senha.                                       |
| [FST02](../elicitacao/storytelling.md)  | o aplicativo deve permitir que os usuários pesquisem acomodações com base em critérios específicos, como localização, datas de check-in e check-out, tipo de quarto e preço. |
| [FST03](../elicitacao/storytelling.md)  | o aplicativo deve permitir que os usuários reservem acomodações selecionadas, inserindo as informações de pagamento e confirmando a reserva.                                    |
| [FST04](../elicitacao/storytelling.md)  | o aplicativo deve permitir que os usuários cancelem suas reservas de acomodação, desde que sejam feitas dentro dos termos e condições estabelecidos pela empresa.               |
| [FST05](../elicitacao/storytelling.md)  | o aplicativo deve permitir que os usuários pesquisem voos com base em critérios específicos, como origem, destino, datas e número de passageiros.                                |
| [FST06](../elicitacao/storytelling.md)  | o aplicativo deve permitir que os usuários reservem voos selecionados, inserindo as informações de pagamento e confirmando a reserva.                                             |
| [FST08](../elicitacao/storytelling.md)  | o aplicativo deve permitir que os usuários gerenciem suas reservas existentes, incluindo a visualização de detalhes da reserva, alterações de datas e cancelamentos.            |
| [FST10](../elicitacao/storytelling.md)  | o aplicativo deve permitir que os usuários visualizem seu histórico de reservas anteriores, incluindo informações como datas, acomodações e voos reservados.                   |
| [NFST01](../elicitacao/storytelling.md) | o aplicativo deve ser fácil de usar, com interface intuitiva e navegação clara.                                                                                                   |
| [NFST02](../elicitacao/storytelling.md) | o aplicativo deve ser rápido e responsivo, com tempo de carregamento mínimo e tempos de resposta rápidos.                                                                         |
| [NFST03](../elicitacao/storytelling.md) | o aplicativo deve estar disponível para uso em todos os momentos, com tempos de inatividade mínimos.                                                                               |
| [NFST04](../elicitacao/storytelling.md) | o aplicativo deve ser seguro, protegendo as informações dos usuários e garantindo a privacidade.                                                                                  |
| [NFST05](../elicitacao/storytelling.md) | o aplicativo deve ser confiável, com alta disponibilidade e poucas falhas.                                                                                                          |
| [NFST06](../elicitacao/storytelling.md) | o aplicativo deve ser compatível com uma ampla variedade de dispositivos, navegadores e sistemas operacionais.                                                                      |
| [NFST07](../elicitacao/storytelling.md) | o aplicativo deve estar disponível em diferentes idiomas e adaptar-se a diferentes regiões e culturas.                                                                             |
| [FB01](../elicitacao/brainstorm.md)     | O sistema deve permitir que o usuário possa cadastrar uma conta                                                                                                                     |
| [FB02](../elicitacao/brainstorm.md)     | O sistema deve possuir escolha do método de pagamento                                                                                                                               |
| [FB03](../elicitacao/brainstorm.md)     | Possibilitar o cadastro de reserva(s) pelo usuário                                                                                                                                  |
| [FB07](../elicitacao/brainstorm.md)     | Permitir que um grupo de pessoas reservem um local                                                                                                                                   |
| [FB09](../elicitacao/brainstorm.md)     | Sincronizar as datas das reservas com o calendário do usuário                                                                                                                      |
| [FB12](../elicitacao/brainstorm.md)     | Permitir visualização de imagens do local pelo usuário                                                                                                                            |
| [FB13](../elicitacao/brainstorm.md)     | Permitir visualização de imagens do carro pelo usuário                                                                                                                            |
| [FB22](../elicitacao/brainstorm.md)     | O sistema deve ser capaz de localizar o usuário se permitido                                                                                                                        |
| [FB23](../elicitacao/brainstorm.md)     | O sistema deve sugerir hospedagens de acordo com a localização do usuário                                                                                                         |
| [FB24](../elicitacao/brainstorm.md)     | O sistema deve oferecer uma aba de perguntas                                                                                                                                         |
| [FB25](../elicitacao/brainstorm.md)     | O sistema deve conter um bate-papo para contato com o locatário ou empresa em que foi feito a reserva                                                                               |
| [FB26](../elicitacao/brainstorm.md)     | O sistema deve ter um sistema de pontuação ligada ao usuário                                                                                                                      |
| [FB27](../elicitacao/brainstorm.md)     | O usuário deve poder denunciar contas                                                                                                                                               |
| [FB31](../elicitacao/brainstorm.md)     | Deve existir uma pesquisa por comando de voz                                                                                                                                         |
| [FB04](../elicitacao/brainstorm.md)     | Permitir o cancelamento de reserva pelo usuário                                                                                                                                     |
| [FB05](../elicitacao/brainstorm.md)     | Permitir que o usuário acesse o histórico de suas reservas                                                                                                                         |
| [FB06](../elicitacao/brainstorm.md)     | Permitir a pesquisa de reserva pelo usuário                                                                                                                                         |
| [FB28](../elicitacao/brainstorm.md)     | O usuário deve poder avaliar e comentar reservas                                                                                                                                    |
| [FOBS01](../elicitacao/observacao.md)   | Deve ser possível criar uma conta com o google, facebook ou email pessoal.                                                                                                          |
| [FOBS02](../elicitacao/observacao.md)   | Deve ser possível realizar pesquisas.                                                                                                                                               |
| [FOBS03](../elicitacao/observacao.md)   | Deve possuir um sistema de fidelidade.                                                                                                                                               |
| [FOBS04](../elicitacao/observacao.md)   | Deve possuir um sistema de informações e recomendações.                                                                                                                          |
| [FOBS05](../elicitacao/observacao.md)   | Deve ser possível filtrar as pesquisas.                                                                                                                                             |
| [FOBS06](../elicitacao/observacao.md)   | Deve ser possível agendar hospedagem.                                                                                                                                               |
| [FOBS07](../elicitacao/observacao.md)   | Deve ser possível agendar voos.                                                                                                                                                     |
| [FOBS08](../elicitacao/observacao.md)   | Deve ser possível alugar carros.                                                                                                                                                    |
| [FOBS10](../elicitacao/observacao.md)   | O aplicativo deve ter mapa interativo.                                                                                                                                               |
| [FOBS12](../elicitacao/observacao.md)   | O aplicativo deve ter uma aba de favoritos.                                                                                                                                          |
| [FOBS13](../elicitacao/observacao.md)   | O aplicativo deve possuir um histórico de reservas.                                                                                                                                 |
| [FOBS14](../elicitacao/observacao.md)   | O aplicativo deve possuir uma central de ajuda ao usuário.                                                                                                                          |
| [FOBS15](../elicitacao/observacao.md)   | O aplicativo deve possuir uma área administrativa da conta.                                                                                                                         |
| [FOBS20](../elicitacao/observacao.md)   | O aplicativo deve apresentar as informações legais sobre o uso para o usuário.                                                                                                    |
| [FOBS22](../elicitacao/observacao.md)   | O aplicativo deve permitir que o usuário saia da conta.                                                                                                                             |
| [NFOBS01](../elicitacao/observacao.md)  | A inteface deve ser responsiva.                                                                                                                                                      |
| [NFOBS02](../elicitacao/observacao.md)  | O sistema deve rodar nas principais plataformas mobile Android e iOS.                                                                                                                |
| [NFOBS03](../elicitacao/observacao.md)  | O sistema deve ser seguro.                                                                                                                                                           |
| [NFOBS04](../elicitacao/observacao.md)  | Deve possuir acessibilidade.                                                                                                                                                         |
| [NFB01](../elicitacao/brainstorm.md)    | O sistema deve ser seguro                                                                                                                                                            |
| [NFB02](../elicitacao/brainstorm.md)    | O sistema deve ter um suporte que funciona 24 horas                                                                                                                                  |
| [NFB03](../elicitacao/brainstorm.md)    | O sistema deve garantir a privacidade e segurança dos clientes                                                                                                                      |
| [NFB04](../elicitacao/brainstorm.md)    | O sistema deve ter acessibilidade para pessoas cegas                                                                                                                                 |
| [NFB05](../elicitacao/brainstorm.md)    | O sistema deve ser multiplataforma: Android e iOS                                                                                                                                    |

<div style="text-align: center">
<p> Tabela 3: Requisitos de alta prioridade. (Fonte: Autores, 2023). </p>
</div>

### Requisitos de Média Prioridade

A partir da priorização Three Level-Scale, foi obtido como requisitos de média prioridade os seguintes requisitos descritos na Tabela 4.

| ID                                  | Requisitos                                                                                                                                                            |
| ----------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [FST07](../elicitacao/storytelling.md) | o aplicativo deve permitir que os usuários pesquisem e reservem carros de aluguel com base em critérios específicos, como localização, datas e tipo de veículo. |
| [FST09](../elicitacao/storytelling.md) | o aplicativo deve permitir que os usuários avaliem acomodações após a conclusão da estadia, fornecendo uma classificação e feedback por escrito.               |
| [FB08](../elicitacao/brainstorm.md)    | Enviar email sobre o status da reserva                                                                                                                                |
| [FB10](../elicitacao/brainstorm.md)    | O sistema deve possuir uma lista de favoritos para aluguel de carro, hospedagem e voos                                                                                |
| [FB11](../elicitacao/brainstorm.md)    | O sistema deve possuir uma lista de desejos para aluguel de carro, hospedagem e voos                                                                                  |
| [FB14](../elicitacao/brainstorm.md)    | O sistema deve possuir um mapa interativo                                                                                                                             |
| [FB15](../elicitacao/brainstorm.md)    | O sistema deve possuir uma carteira digital                                                                                                                           |
| [FB18](../elicitacao/brainstorm.md)    | O sistema deve possuir uma moeda própria                                                                                                                             |
| [FB19](../elicitacao/brainstorm.md)    | O usuário deve poder comprar moedas do sistema                                                                                                                       |
| [FB20](../elicitacao/brainstorm.md)    | O sistema deve oferecer uma opção de conta premium                                                                                                                  |
| [FB21](../elicitacao/brainstorm.md)    | O usuário deve poder selecionar o idioma do sistema                                                                                                                  |
| [FB29](../elicitacao/brainstorm.md)    | O sistema deve notificar sobre ofertas                                                                                                                                |
| [FB30](../elicitacao/brainstorm.md)    | O sistema deve ter filtragem de pesquisa de hospedagens, alugueis de carros e voos                                                                                    |
| [FB32](../elicitacao/brainstorm.md)    | O usuário deve poder adicionar itens ao aluguel do carro                                                                                                             |
| [FOBS01](../elicitacao/observacao.md)  | Deve ser possível criar uma conta com o google, facebook ou email pessoal.                                                                                           |
| [FOBS09](../elicitacao/observacao.md)  | Deve ser possível contratar serviços de táxi.                                                                                                                      |
| [FOBS11](../elicitacao/observacao.md)  | Deve ser possível agendar visitas à atrações turísticas.                                                                                                         |
| [FOBS16](../elicitacao/observacao.md)  | O aplicativo deve possuir sistema de carteira virtual.                                                                                                                |
| [FOBS18](../elicitacao/observacao.md)  | O aplicativo deve possuir um sistema de ofertas.                                                                                                                      |
| [FOBS19](../elicitacao/observacao.md)  | O aplicativo deve possuir um sistema de configurações do aplicativo.                                                                                                |

<div style="text-align: center">
    <p> Tabela 4 - Tabela de Requisitos de média prioridade. (Fonte: Autores. 2023).</p>
</div>

### Requisitos de Baixa Prioridade

A partir da priorização Three Level-Scale, foi obtido como requisitos de baixa prioridade os seguintes requisitos descritos na Tabela 5.

| ID                                  | Requisitos                                               |
| ----------------------------------- | -------------------------------------------------------- |
| [FB16](../elicitacao/brainstorm.md)    | O sistema deve exibir dicas sobre os locais e carros     |
| [FB17](../elicitacao/brainstorm.md)    | O sistema deve mostrar notícias relacionadas ao turismo |
| [NFB06](../elicitacao/brainstorm.md)   | O sistema deve ter escalabilidade                        |
| [NFOBS05](../elicitacao/observacao.md) | Deve ser escalável.                                     |

<div style="text-align: center">
    <p> Tabela 5 - Tabela de Requisitos de média prioridade. (Fonte: Autores. 2023).</p>
</div>

A seguir, na tabela 6, estão listadas todas as siglas com seus respectivos significados.

| Sigla | Significado                              |
| ----- | ---------------------------------------- |
| FST   | Requisito funcional de Storytelling      |
| NFST  | Requisito NÃO funcional de Storytelling |
| FB    | Requisito Funcional Brainstorm           |
| NFB   | Requisito Não Funcional Brainstorm      |
| FOBS  | Requisito funcional da Observação      |
| NFOBS | Requisito não funcional da Observação |

<div style="text-align: center">
<p> Tabela 6: Tabela de siglas com seus respectivos significados. (Fonte: Autores, 2023). </p>
</div>

## Bibliografias

SOUZA, D. 5 técnicas de priorização: Organize seu backlog. #EmpiricusTech, 2021. Disponível em:
https://medium.com/empiricustech/5-t%C3%A9cnicas-de-prioriza%C3%A7%C3%A3o-organize-seu-backlog-e636d97222e4. Acesso em: 23 abr. 2023.

ROCK CONTENT. Priorização de Projetos: conheça os 6 melhores métodos. Rock Content, 2018. Disponível em: https://rockcontent.com/br/blog/priorizacao-de-projetos/. Acesso em: 23 abr. 2023.

Projeto Grasshopper do github de requisitos de software - disponível [aqui](https://requisitos-de-software.github.io/2022.2-Grasshopper/elicitacao/priorizacao/threeLevel-Scale/), Acessado em: 24 de abril de 2023.

## Histórico de Versão

| Versão | Data       | Descrição                                 | Autor(es)        | Revisor(es) |
| ------- | ---------- | ------------------------------------------- | ---------------- | ----------- |
| 1.0     | 23/04/2023 | Criação do documento                      | Henrique e Lucas | Pedro       |
| 1.1     | 24/04/2023 | Resultados do Three Level-Scale             | Henrique e Lucas | Pedro       |
| 1.2     | 21/06/2023 | Arrumando o que foi pedido na verificação | Lucas e Henrique | Pedro       |
