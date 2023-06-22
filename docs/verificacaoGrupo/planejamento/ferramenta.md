# Verificação das ferramentas

## Introdução

O presente documento apresentará a verificação do artefato [Ferramentas](../../planejamento/ferramentas.md), desenvolvido pela equipe. A técnica de inspeção será aplicada para verificar esse artefato, de acordo com o planejamento estabelecido, na tabela 1, se encontra os metadados desse artefato, nas tabelas 2 e 3 se encontram as questões a serem avaliadas.

<center>

| Versão avaliada | Autor          | Revisor  |
| ---------------- | -------------- | -------- |
| 1.4              | Pedro Henrique | Chaydson |

<div style="text-align: center">
<p> Tabela 1: Versão avaliada. (Fonte: Samuel, 2023). </p>
</div>

| ID |                                 Questão                                 | Inspeção |
| :-: | :-----------------------------------------------------------------------: | :--------: |
| 1 |                 As legendas estão no padrão do projeto?                 |     🟡     |
| 2 |                  Possui links para os outros artefatos?                  |    N/A    |
| 3 |                   Existe uma introdução no artefato?                   |     🟢     |
| 4 |                Existe tabela de versionamento padronizado?                |     🟢     |
| 5 |      Há referências bibliográficas ou referências no artefato?      |     🟢     |
| 6 | As tabelas e imagens possuem legenda, fonte e são introduzidas no texto? |     🟢     |
| 7 |                         O artefato possui autor?                         |     🟢     |
| 8 |                        O artefato possui revisor?                        |     🟢     |

<div style="text-align: center">
<p> Tabela 2: Tabela de avaliação com as verificações gerais para todos os artefatos (Fonte: Samuel, 2023). </p>
</div>

| ID | Questão                                                                                | Inspeção |
| -- | --------------------------------------------------------------------------------------- | ---------- |
| 9  | A introdução está correta?                                                           | 🟢         |
| 10 | Todas as ferramentas são acompanhadas por uma descrição que descreve sua finalidade. | 🟢         |
| 11 | O nome, logo e descrição das ferramentas estão corretos?                            | 🟡         |
| 12 | As ferramentas estão atualizadas?                                                      | 🟢         |

<div style="text-align: center">
<p> Tabela 3: Tabela de avaliação com as questões específicas do artefato (Fonte: Samuel, 2023). </p>
</div>

### Tarefas

| ID Correção | Tarefa                           |
| ------------- | -------------------------------- |
| IDC1          | Colocar nome do autor da tabela. |
| IDC2          | Colocar nome das ferramentas.    |

<div style="text-align: center">
<p> Tabela 4: Tabela do que precisa ser ajustado (Fonte: Samuel, 2023). </p>
</div>

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

- 9/12 exigências são atendidas;
- 2/12 exigências estão incompletas;
- 0/12 exigências estão erradas ou não foram realizadas.
- 1/12 não se aplica.

```vegalite
{
    "title": "Acompanhamento",
  "$schema": "https://vega.github.io/schema/vega-lite/v5.json",
  "description": "A simple donut chart with embedded data.",
  "data": {
    "values": [
      {"legenda": "Completo", "value": 9},
      {"legenda": "Incompleto", "value": 2},
      {"legenda": "Errado ou não feito", "value": 0},
      {"legenda": "Não se aplica", "value": 1}
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

Portanto, com base na formula apresentada, pode-se dizer que o aproveitamento deste artefato está em 83,33% correto.

## Correção

### Ajustes

Na tabela 6, se encontra os ajustes que o autor do artefato realizou para arrumar o que foi pedido na tabela 4

<center>

| ID Correção | Ajuste                       |
| ------------- | ---------------------------- |
| IDC1          | Foi ajustado x realizando... |
| IDC2          | Foi incluido x em ...        |
| IDC3          | Foi removido x ...           |
| IDC4          | X foi especificaod melhor... |

<div style="text-align: center">
<p> Tabela 6: Tabela de ajustes feitos (Fonte: Lucas, 2023). </p>
</div>

</center>
Portanto, com base no cálculo apresentado, pode-se dizer que o aproveitamento deste artefato está em 81,81%.

## Bibliografia

WHEELER, Alina. Design de identidade de marca. Porto Alegre: Bookman, 2013.

## Histórico de Versão

| Versão | Data       | Descrição                             | Autor(es) |
| ------- | ---------- | --------------------------------------- | --------- |
| 1.0     | 21/06/2023 | Criação do documento de verificação | Samuel    |
