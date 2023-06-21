# Verificação da observação

## Introdução

O presente documento apresentará a verificação do artefato observação, desenvolvidos pela equipe. A técnica de inspeção será aplicada para verificar esse artefato, de acordo com o planejamento estabelecido. Na tabela 1, se encontra os metadados desse artefato, nas tabelas 2 e 3 se encontram as questões a serem avaliadas.

<center>

| Versão avaliada | Autor                    | Revisor |
| ---------------- | ------------------------ | ------- |
| 1.1              | Pedro Henrique, Chaydson | Samuel  |

</center>

<div style="text-align: center">
<p> Tabela 1: Metadados do artefato (Fonte: Lucas Frazão e Chaydson Ferreira, 2023). </p>
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
<p> Tabela 2: Tabela de avaliação com as gerais para todos os artefatos (Fonte: Lucas Frazão e Chaydson Ferreira, 2023). </p>
</div>

| ID |                                             Questão                                             | Inspeção |
| :-: | :-----------------------------------------------------------------------------------------------: | :--------: |
| 9 |            Possui um cronograma com local, data, hora, entrevistadores e entrevistado?            |     🟡     |
| 10 |                               Possui a gravação da observação?                               |     🟢     |
| 11 |                          Possui o papel empenhado por cada participante?                          |     🔴     |
| 12 | Teve o mínimo de interferência possível por parte dos entrevistadores em cima do entrevistado? |     🟢     |
| 13 |           Os requisitos levantados foram colocados em uma tabela com seu respectivo id?           |     🟢     |
| 14 |                                 Possui um termo de consentimento?                                 |     🟢     |

<div style="text-align: center">
<p> Tabela 3: Tabela de avaliação com as questões específicas do artefato (Fonte: Lucas Frazão e Chaydson Ferreira, 2023). </p>
</div>

<center>

### Tarefas

| ID Correção | Tarefa                                                                              |
| ------------- | ----------------------------------------------------------------------------------- |
| IDC1          | Adicionar legenda ao vídeo e referenciá-la                                        |
| IDC2          | Transformar "Legendas" em tabela                                                    |
| IDC3          | Adicionar entrevistadores e entrevistado no cronograma                              |
| IDC4          | Adicionar uma tabela com os nomes dos participantes e o papel empenhado por cada um |

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

- 10/13 exigências são atendidas;
- 2/13 exigências estão incompletas;
- 1/13 exigências estão erradas ou não foram realizadas.

onde x é a quantidade de exigências.

```vegalite
{
    "title": "Acompanhamento",
  "$schema": "https://vega.github.io/schema/vega-lite/v5.json",
  "description": "A simple donut chart with embedded data.",
  "data": {
    "values": [
      {"legenda": "Completo", "value": 10},
      {"legenda": "Incompleto", "value": 2},
      {"legenda": "Errado", "value": 1},
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
        "domain": ["Completo", "Incompleto", "Errado", "Não se aplica"],
        "range": ["green", "yellow", "red", "blue"]
      }
    }
  }
}
```

<div style="text-align: center">
<p> Gráfico 1: Gráfico de aproveitamento (Fonte: Samuel, 2023). </p>
</div>

Portanto, com base na formula apresentada, pode-se dizer que o aproveitamento deste artefato está em 76,92% correto.

## Correção

### Ajustes

Na tabela 6, se encontra os ajustes que o autor do artefato realizou para arrumar o que foi pedido na tabela 4

| ID Correção | Ajuste                                                                                                     |
| ------------- | ---------------------------------------------------------------------------------------------------------- |
| IDC1          | Foi adicionado legenda ao video e referenciado no texto                                                    |
| IDC2          | As legendas não são mais textos e sim uma tabela                                                         |
| IDC3          | Foi adicionado entrevistadores e entrevistado na tabela do cronograma                                      |
| IDC4          | Foi criado um tópico com o texto explicando quem são os participantes e o papel desempenhado por cada um |

<div style="text-align: center">
<p> Tabela 6: Tabela de ajustes feitos (Fonte: Lucas, 2023). </p>
</div>

</center>

## Bibliografia

- BARBOSA, Simone Diniz Junqueira; DA SILVA, Bruno Santana. Interação Humano - Computador. Rio de janeiro: Elsevier, 2010.

## Histórico de versão

|    Data    | Versão |      Descrição      | Autor(es) |
| :--------: | :-----: | :--------------------: | :-------: |
| 20/06/2023 |   1.0   | Criação do documento |   Lucas   |
| 21/06/2023 |   1.1   | Aplicando correções no artefato |   Pedro e Chaydson   |
