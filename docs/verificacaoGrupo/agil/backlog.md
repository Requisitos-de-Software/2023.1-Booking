# Verificação do Backlog

## Introdução

O presente documento apresentará a verificação do artefato [Backlog](../../modelagem/modelo-agil/backlog.md), desenvolvido pela equipe. A técnica de inspeção será aplicada para verificar esse artefato, de acordo com o planejamento estabelecido. Na tabela 1, se encontra os metadados desse artefato, nas tabelas 2 e 3 se encontram as questões a serem avaliadas e no Gráfico 1, o quanto das exigências foram atendidas.

A tabela 1 a seguir representa os dados do artefato Backlog.

<center>

| Versão avaliada | Autor            | Revisor  |
| ---------------- | ---------------- | -------- |
| 1.0              | Lucas e Chaydson | Henrique |

</center>

<div style="text-align: center">
<p> Tabela 1: Dados do artefato Backlog. (Fonte: Gabriel e Pedro, 2023). </p>
</div>

| ID |                                   Questão                                   | Inspeção |
| :-: | :---------------------------------------------------------------------------: | :--------: |
| 1 |                   As legendas estão no padrão do projeto?                   |     🟢     |
| 2 |                    Possui links para os outros artefatos?                    |     🔴     |
| 3 |                     Existe uma introdução no artefato?                     |     🟢     |
| 4 |                  Existe tabela de versionamento padronizado?                  |     🟢     |
| 5 | Há referências bibliográficas, bibliografia ou referências no artefato? |     🔴     |
| 6 |   As tabelas e imagens possuem legenda, fonte e são introduzidas no texto?   |     🟡     |
| 7 |                           O artefato possui autor?                           |     🟢     |
| 8 |                          O artefato possui revisor?                          |     🟢     |

<div style="text-align: center">
<p> Tabela 2: Tabela de avaliação com as verificações gerais para todos os artefatos (Fonte: Gabriel e Pedro, 2023). </p>
</div>

| ID |                                                       Questão                                                       | Inspeção |
| :-: | :-------------------------------------------------------------------------------------------------------------------: | :--------: |
| 9 |                                      Os épicos estão priorizados e ordenados?                                      |     🔴     |
| 10 |                                           O backlog possui rastreabilidade?                                           |     🔴     |
| 11 |                                      O backlog atende a necessidade do usuário?                                      |     🟢     |
| 12 |                                     O backlog foi validado com o usuário ou PO?                                     |     🔴     |
| 13 |                     As historias de usuário tem relação com o épico no qual estão contidas?                     |     🟡     |
| 14 | Os épicos possuem historias de usuarios suficientes e condizentes para levar mais de uma sprint para ser concluída? |     🟡     |
| 15 |                   Os eṕicos estão granularizados o suficiente para gerar historias de usuários?                   |     🟢     |

<div style="text-align: center">
<p> Tabela 3: Tabela de avaliação com as questões específicas do artefato (Fonte: Gabriel e Pedro, 2023). </p>
</div>

### Tarefas

| ID Correção | Tarefa                                                                                                                                                                                                                                                    |
| ------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| IDC1          | Adicionar na parte da metologia o link para a história de usuário citado no texto                                                                                                                                                                       |
| IDC2          | Adicionar na Tabela 1 na coluna 'priorização' em todos que são os requisitos elicitados citados os links para a sua respectiva página de priorização                                                                                                |
| IDC3          | Adicionar na Tabela 2 na coluna 'ID' em todas as histórias de usuário os links da página de usuário                                                                                                                                                   |
| IDC4          | Adicionar referências ou bibliografias do artefato.                                                                                                                                                                                                     |
| IDC5          | Adicionar a chamada de texto da Tabela 2, tanto no texto de épicos, quanto no de temas                                                                                                                                                                  |
| IDC6          | Os épicos apresentam priorização, entretanto não estão ordenados                                                                                                                                                                                     |
| IDC7          | Apesar de demonstrar os requisitos em formato de acrônimo, o mesmo não apresenta uma legenda ou link para ir até o link e poder entender de onde ele veio ou para onde vai no caso de histórias de usuários                                         |
| IDC8          | Gravar uma validação com um usuário validando os épicos e backlog                                                                                                                                                                                     |
| IDC9          | Existem histórias de usuários faltantes a serem adicionadas, 'Épico 11' apresenta história de usuário repetida 'US11' e com prioridade diferente em cada uma das repetições, as histórias de usuário 13 e 31, não estão presentes nos épicos |
| IDC10         | Unir épico 04 e 05 em somente um para levar mais de uma sprint                                                                                                                                                                                           |

</center>

## Acompanhamento

Para saber a porcentagem de aproveitamento do artefato, será utilizado a expressão da Figura 1, no qual a Tabela 5 apresenta o significado dessa legendas.

<div style="text-align: center">
<img src="../../../images/formulaCalculoAproveitamento.png"  alt="legenda da fórmula da figura 1"/>

<p> Figura 1: Fórmula para calcular aproveitamento (Fonte: Gabriel, 2023). </p>
</div>

<center>

| Acrônimo | Descrição                     |
| --------- | ------------------------------- |
| QTDE      | Quantidade Total de Exigências |
| EC        | Exigências Completas           |

<div style="text-align: center">
<p> Tabela 5: Legenda da Figura 1 (Fonte: Gabriel, 2023). </p>
</div>

</center>

### Porcentagem

Nos checklists realizados e que serão descritos, podemos observar que:

- 7/15 exigências são atendidas;
- 3/15 exigências estão incompletas;
- 5/15 exigências estão erradas ou não foram realizadas;

```vegalite
{
    "title": "Acompanhamento",
  "$schema": "https://vega.github.io/schema/vega-lite/v5.json",
  "description": "Dados de acompanhamento do Storytelling",
  "data": {
    "values": [
      {"legenda": "Completo", "value": 7},
      {"legenda": "Incompleto", "value": 3},
      {"legenda": "Errado", "value": 5}
    ]
  },
  "mark": {"type": "arc", "innerRadius": 50, "tooltip": true},
  "encoding": {
    "theta": {"field": "value", "type": "quantitative"},
    "color": {
      "field": "legenda",
      "type": "nominal",
      "scale": {
        "domain": ["Completo", "Incompleto", "Errado"],
        "range": ["green", "yellow", "red"]
      }
    }
  }
}
```

<div style="text-align: center">
<p> Gráfico 1: Gráfico de aproveitamento (Fonte: Gabriel e Pedro, 2023). </p>
</div>

Portanto, com base na formula apresentada, pode-se dizer que o aproveitamento deste artefato está em 46,67% correto.

## Correção

### Ajustes

Na tabela 6, se encontra os ajustes que o autor do artefato realizou para arrumar o que foi pedido na tabela 4

| ID Correção | Ajuste |
| ------------- | ------ |
| IDC1          |        |
| IDC2          |        |
| IDC3          |        |
| IDC4          |        |
| IDC5          |        |
| IDC6          |        |
| IDC7          |        |
| IDC8          |        |
| IDC9          |        |
| IDC10         |        |

<div style="text-align: center">
<p> Tabela 6: Tabela de ajustes feitos (Fonte: Lucas e Chaydson, 2023). </p>
</div>

</center>

Após as correções, a nova porcentagem de aproveitamento é de: p% correto.

## Bibliografia

Backlog de produto 101: Principais conselhos de especialistas ágeis. Smartsheet. Disponível em: [https://pt.smartsheet.com/best-advice-scrum-and-agile-experts-managing-your-product-backlog](https://pt.smartsheet.com/best-advice-scrum-and-agile-experts-managing-your-product-backlog). Acesso em: 21 jun. 2023.

Fonseca, Bruna. Granularidade do Backlog. Disponível em: [https://www.linkedin.com/pulse/granularidade-do-backlog-bruna-fonseca-/?trk=pulse-article_more-articles_related-content-card&amp;originalSubdomain=pt](https://www.linkedin.com/pulse/granularidade-do-backlog-bruna-fonseca-/?trk=pulse-article_more-articles_related-content-card&originalSubdomain=pt). Acesso em: 21 jun. 2023.

MESQUITA SOARES, Renato. 1 Introdução. In: MESQUITA SOARES, Renato. Product Backlog Orientado a Metas em Projetos Scrum para Fundamentar as Tomadas de Decisões do Product Owner. Orientador: Dra. Márcia Jacyntha Nunes Rodrigues Lucena. 2020. Trabalho de Conclusão Curso (Bacharelado em Engenharia de Software) - Universidade Federal do Rio Grande do Norte, Natal-RN, 2020. p. 17. Disponível em: [https://repositorio.ufrn.br/bitstream/123456789/32354/1/Productbacklogorientado_Soares_2020.pdf](https://repositorio.ufrn.br/bitstream/123456789/32354/1/Productbacklogorientado_Soares_2020.pdf). Acesso em: 21 jun. 2023.

## Histórico de Versão

| Versão | Data       | Descrição                             | Autor(es)       |
| ------- | ---------- | --------------------------------------- | --------------- |
| 1.0     | 21/06/2023 | Criação do documento de verificação | Gabriel e Pedro |

‌
