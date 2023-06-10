# Verificação do Backlog

## Introdução

O presente documento apresentará a verificação do artefato [Backlog](https://requisitos-de-software.github.io/2023.1-VLC/#/modelagem/agil/backlog), desenvolvidos pela equipe 3, VLC. A técnica de inspeção será aplicada para verificar esse artefato, de acordo com o planejamento estabelecido, na tabela 1, se encontra os metadados desse artefato, nas tabelas 2 e 3 se encontram as questões a serem avaliadas.

A tabela 1 a seguir representa os dados do artefato Especificação Suplementar.

| Versão avaliada | Autor             | Revisor     |
| ---------------- | ----------------- | ----------- |
| 1.1              | Giovanni Alvissus | Lucas Gobbi |

<div style="text-align: center">
<p> Tabela 1: Dados do artefato Especificação Suplementar. (Fonte: Pedro e Gabriel, 2023). </p>
</div>

| ID |                                   Questão                                   | Inspeção | Observações                                                                      |
| :-: | :---------------------------------------------------------------------------: | :--------: | ---------------------------------------------------------------------------------- |
| 1 |                   As legendas estão no padrão do projeto?                   |     🟢     |                                                                                    |
| 2 |                    Possui links para os outros artefatos?                    |     🟡     | Esta faltando o link para o artefato das historias de usuários.                   |
| 3 |                     Existe uma introdução no artefato?                     |     🟢     |                                                                                    |
| 4 |                  Existe tabela de versionamento padronizado?                  |     🟢     |                                                                                    |
| 5 | Há referências bibliográficas, bibliografia ou referências no artefato? |     🟡     | A bibliografia, na verdade como foi implementada é uma referência bibliografica. |
| 6 |   As tabelas e imagens possuem legenda, fonte e são introduzidas no texto?   |     🟡     | Não possui legenda para os acrônimos das rastreabilidades.                       |
| 7 |                           O artefato possui autor?                           |     🟢     |                                                                                    |
| 8 |                          O artefato possui revisor?                          |     🟢     |                                                                                    |

<div style="text-align: center">
<p> Tabela 2: Tabela de avaliação com as verificações gerais para todos os artefatos (Fonte: Pedro e Gabriel, 2023). </p>
</div>

| ID |                                                       Questão                                                       | Inspeção | Obersevação                                                                                                                                                                                                    |
| :-: | :-------------------------------------------------------------------------------------------------------------------: | :--------: | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1 |                                      Os épicos estão priorizados e ordenados?                                      |     🟡     | A US09 com prioridade Must esta abaixo de US08, US07, US06 que tem prioridade Could                                                                                                                           |
| 2 |                                           O backlog possui rastreabilidade?                                           |     🔴     |                                                                                                                                                                                                                  |
| 3 |                                      O backlog atende a necessidade do usuário?                                      |     🟡     | O fato de uma historia de usuário com prioridade Must estar abaixo de uma história com prioridade Could afeta em funcionalidades que serão desenvolvidas para o usuário que podem ser urgentes para o mesmo. |
| 4 |                                     O backlog foi validado com o usuário ou PO?                                     |     🔴     |                                                                                                                                                                                                                  |
| 5 |                     As historias de usuário tem relação com o épico no qual estão contidas?                     |     🔴     |                                                                                                                                                                                                                  |
| 6 | Os épicos possuem historias de usuarios suficientes e condizentes para levar mais de uma sprint para ser concluída? |     🟡     | O épico 3 pode ser concluído em uma única sprint, o que tornaria ela uma história de usuário.                                                                                                               |
| 7 |                   Os eṕicos estão granularizados o suficiente para gerar historias de usuários?                   |     🔴     |                                                                                                                                                                                                                  |

<div style="text-align: center">
<p> Tabela 3: Tabela de avaliação com as questões específicas do artefato (Fonte: Pedro e Gabriel, 2023). </p>
</div>

## Comentários

ID 2 - O backlog possui rastreabilidade?

Apesar de ter links para outros artefatos a fim de realizar o rastreamento, o mesmo não indica de qual requisito de dentro da priorização ele veio. Ademais, também não existe rastro através de links dificultando em fases posteriores o backward-from e forward-from.

ID 4 - O backlog foi validado com o usuário ou PO?

Só as histórias de usuário foram validadas, porém o backlog não para garantir que o mesmo estava ordenado da maneira que deveria estar em sua opinião.

ID 5 - As historias de usuário tem relação com o épico no qual estão contidas?

As histórias de usuário não tem relação com os épicos.

ID 7 - Os eṕicos estão granularizados o suficiente para gerar historias de usuários?

Não estão granularizados o suficiente e podem ser melhor organizados.

## Resultados

Para saber a porcentagem de aproveitamento do artefato, será utilizado a expressão:

((100/QntExigencias) _ Acertos) + (((100/QntExigencias) _ Incompletos)/2)

Através dos checklists realizados podemos observar que:

- 5/15 exigências são atendidas;
- 6/15 exigências estão incompletas;
- 4/15 exigências estão erradas ou não foram realizadas.
- 0/15 não se aplica.

onde 15 é a quantidade de exigências.

Portanto, com base no cálculo apresentado, pode-se dizer que o aproveitamento deste artefato está em 53,33%.

## Bibliografia

Backlog de produto 101: Principais conselhos de especialistas ágeis. Smartsheet. Disponível em: [https://pt.smartsheet.com/best-advice-scrum-and-agile-experts-managing-your-product-backlog](https://pt.smartsheet.com/best-advice-scrum-and-agile-experts-managing-your-product-backlog). Acesso em: 8 jun. 2023.

Fonseca, Bruna. Granularidade do Backlog. Disponível em: [https://www.linkedin.com/pulse/granularidade-do-backlog-bruna-fonseca-/?trk=pulse-article_more-articles_related-content-card&amp;originalSubdomain=pt](https://www.linkedin.com/pulse/granularidade-do-backlog-bruna-fonseca-/?trk=pulse-article_more-articles_related-content-card&originalSubdomain=pt). Acesso em: 8 jun. 2023.

MESQUITA SOARES, Renato. 1 Introdução. In: MESQUITA SOARES, Renato. Product Backlog Orientado a Metas em Projetos Scrum para Fundamentar as Tomadas de Decisões do Product Owner. Orientador: Dra. Márcia Jacyntha Nunes Rodrigues Lucena. 2020. Trabalho de Conclusão Curso (Bacharelado em Engenharia de Software) - Universidade Federal do Rio Grande do Norte, Natal-RN, 2020. p. 17. Disponível em: [https://repositorio.ufrn.br/bitstream/123456789/32354/1/Productbacklogorientado_Soares_2020.pdf](https://repositorio.ufrn.br/bitstream/123456789/32354/1/Productbacklogorientado_Soares_2020.pdf). Acesso em: 8 jun. 2023.

## Histórico de Versão

| Versão | Data       | Descrição                             | Autor(es)       |
| ------- | ---------- | --------------------------------------- | --------------- |
| 1.0     | 07/06/2023 | Criação do documento de verificação | Pedro e Gabriel |

‌
