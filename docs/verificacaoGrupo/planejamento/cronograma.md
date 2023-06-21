# Verificação da observação

## Introdução

O presente documento apresentará a verificação do artefato observação, desenvolvidos pela equipe. A técnica de inspeção será aplicada para verificar esse artefato, de acordo com o planejamento estabelecido. Na tabela 1, se encontra os metadados desse artefato, nas tabelas 2 e 3 se encontram as questões a serem avaliadas.

<center>

| Versão avaliada | Autor    | Revisor |
| --------------- | -------- | ------- |
| 1.7             | Henrique | Samuel  |

</center>

<div style="text-align: center">
<p> Tabela 1: Metadados do artefato (Fonte: Lucas Frazão e Chaydson Ferreira, 2023). </p>
</div>

| ID  |                                 Questão                                  | Inspeção |
| :-: | :----------------------------------------------------------------------: | :------: |
|  1  |                 As legendas estão no padrão do projeto?                  |    🟡    |
|  2  |                  Possui links para os outros artefatos?                  |   N/A    |
|  3  |                    Existe uma introdução no artefato?                    |    🟢    |
|  4  |               Existe tabela de versionamento padronizado?                |    🟢    |
|  5  |        Há referências bibliográficas ou referências no artefato?         |    🟢    |
|  6  | As tabelas e imagens possuem legenda, fonte e são introduzidas no texto? |    🟡    |
|  7  |                         O artefato possui autor?                         |    🟢    |
|  8  |                        O artefato possui revisor?                        |    🟢    |

<div style="text-align: center">
<p> Tabela 2: Tabela de avaliação com as gerais para todos os artefatos (Fonte: Lucas Frazão, 2023). </p>
</div>

| ID  |                                  Questão                                   | Inspeção |
| :-: | :------------------------------------------------------------------------: | :------: |
|  9  |               Para cada tarefa existe um revisor associado?                |    🟡    |
| 10  |                Para cada tarefa existe um autor associado?                 |    🟢    |
| 11  | O cronograma executado é alterado de acordo com a realização das tarefas?  |    🟢    |
| 12  | As tarefas do cronograma foram distribuidas entre os todos os integrantes? |    🟢    |
| 13  |              Os revisores são pessoas diferentes dos autores?              |    🟢    |
| 14  |            As tarefas do cronograma possuem nomes condizentes?             |    🟢    |
| 15  |   O cronograma foi feito em tabelas? Se sim, elas possuem fonte e nome?    |    🟢    |

<div style="text-align: center">
<p> Tabela 3: Tabela de avaliação com as questões específicas do artefato (Fonte: Lucas Frazão, 2023). </p>
</div>

## Preparação dos ajustes

Por fim, o avaliador deve fazer uma série de planejamentos para melhorar o artefato analisado.

<center>

### Tarefas

| ID Correção | Tarefa                                                       |
| ----------- | ------------------------------------------------------------ |
| IDC1        | Remover os projetos utilizados como base do cronograma geral |
| IDC2        | Centralizar a legenda da tabela 1                            |
| IDC3        | Introduzir a tabela 1                                        |
| IDC4        | Entrega 5.1 não possui revisores                             |

<div style="text-align: center">
<p> Tabela 4: Tabela do que precisa ser ajustado (Fonte: Lucas, 2023). </p>
</div>

</center>

## Acompanhamento

Para saber a porcentagem de aproveitamento do artefato, será utilizado a expressão da Figura 1, no qual a Tabela 5 apresenta o significado dessa legendas.

<div style="text-align: center">
<img src="../../../images/formulaCalculoAproveitamento.png"  alt="legenda da fórmula da figura 1"/>

<p> Figura 1: Fórmula para calcular aproveitamento (Fonte: Gabriel, 2023). </p>
</div>

<center>

| Acrônimo | Descrição                      |
| -------- | ------------------------------ |
| QTDE     | Quantidade Total de Exigências |
| EC       | Exigências Completas           |

<div style="text-align: center">
<p> Tabela 5: Legenda da Figura 1 (Fonte: Gabriel, 2023). </p>
</div>

</center>

### Porcentagem

Nos checklists realizados e que serão descritos, podemos observar que:

- 12/15 exigências são atendidas;
- 3/15exigências estão incompletas;
- 0/15 exigências estão erradas ou não foram realizadas.

onde x é a quantidade de exigências.

```vegalite
{
    "title": "Acompanhamento",
  "$schema": "https://vega.github.io/schema/vega-lite/v5.json",
  "description": "A simple donut chart with embedded data.",
  "data": {
    "values": [
      {"legenda": "Completo", "value": 12},
      {"legenda": "Incompleto", "value": 3},
      {"legenda": "Errado ou não feito", "value": 0},
      {"legenda": "Não se aplica", "value": 0}
    ]
  },
  "mark": {"type": "arc", "innerRadius": 50, "tooltip": true},
  "encoding": {
    "theta": {"field": "value", "type": "quantitative"},
    "color": {
      "field": "legenda",
      "type": "nominal",
      "scale": {
        "domain": ["Completo", "Incompleto", "Errado ou não feito", "Não se aplica"],
        "range": ["green", "yellow", "red", "blue"]
      }
    }
  }
}
```

<div style="text-align: center">
<p> Gráfico 1: Gráfico de aproveitamento (Fonte: Samuel, 2023). </p>
</div>

Portanto, com base na formula apresentada, pode-se dizer que o aproveitamento deste artefato está em p% correto.

## Correção

### Ajustes

Na tabela 6, se encontra os ajustes que o autor do artefato realizou para arrumar o que foi pedido na tabela 4

| ID Correção | Ajuste                       |
| ----------- | ---------------------------- |
| IDC1        | Foi ajustado x realizando... |
| IDC2        | Foi incluido x em ...        |
| IDC3        | Foi removido x ...           |
| IDC4        | X foi especificaod melhor... |

<div style="text-align: center">
<p> Tabela 6: Tabela de ajustes feitos (Fonte: Lucas, 2023). </p>
</div>

</center>

## Bibliografia

## Histórico de versão

|    Data    | Versão |      Descrição       | Autor(es) |
| :--------: | :----: | :------------------: | :-------: |
| 20/06/2023 |  1.0   | Criação do documento |   Lucas   |
