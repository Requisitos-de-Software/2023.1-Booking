# Verificação do perfil de usuário

## Introdução

O presente documento apresentará a verificação do artefato observação, desenvolvidos pela equipe. A técnica de inspeção será aplicada para verificar esse artefato, de acordo com o planejamento estabelecido. Na tabela 1, se encontra os metadados desse artefato, nas tabelas 2 e 3 se encontram as questões a serem avaliadas.

<center>

| Versão avaliada | Autor                     | Revisor |
| ---------------- | ------------------------- | ------- |
| 1.1              | Henrique e Pedro Henrique | Samuel  |

</center>

<div style="text-align: center">
<p> Tabela 1: Metadados do artefato (Fonte: Lucas Frazão e Chaydson Ferreira, 2023). </p>
</div>

| ID |                                 Questão                                 | Inspeção |
| :-: | :-----------------------------------------------------------------------: | :--------: |
| 1 |                 As legendas estão no padrão do projeto?                 |     🟢     |
| 2 |                  Possui links para os outros artefatos?                  |    N/A    |
| 3 |                   Existe uma introdução no artefato?                   |     🟢     |
| 4 |                Existe tabela de versionamento padronizado?                |     🟢     |
| 5 |      Há referências bibliográficas ou referências no artefato?      |     🟢     |
| 6 | As tabelas e imagens possuem legenda, fonte e são introduzidas no texto? |     🟢     |
| 7 |                         O artefato possui autor?                         |     🟢     |
| 8 |                        O artefato possui revisor?                        |     🟢     |

<div style="text-align: center">
<p> Tabela 2: Tabela de avaliação com as gerais para todos os artefatos (Fonte: Lucas Frazão, 2023). </p>
</div>

| ID |                                              Questão                                              | Inspeção |
| :-: | :-------------------------------------------------------------------------------------------------: | :--------: |
| 9 |               O perfil do usuário segue os atributos definidos por Hackos e Redish?               |     🔴     |
| 10 |               É explicitado a(s) técnicas(s) de elicitação do perfil do usuário?               |     🟢     |
| 11 |                  O perfil de usuário foi traçado? Com no mínimo 2 variações?                  |     🟡     |
| 12 |                       Os dados levantados fazem sentido no escopo do projeto?                       |     🟢     |
| 13 |                Os dados foram coletados por meio de entrevistas ou outra técnica?                |     🟢     |
| 14 |                     Possui termo de consentimento esclarecedor e bem descrito?                     |     🔴     |
| 15 |         Possui e considera aspectos éticos de toda e qualquer pesquisa envolvendo pessoas?         |     🔴     |
| 16 | Foi levantado a experiência do usuário sobre o aplicativo ou semelhantes e as tarefas realizadas? |     🟡     |
| 17 |            Foi levantado as atitudes (tecnófilos, tecnófobos) dos perfis de usuários?            |     🔴     |

<div style="text-align: center">
<p> Tabela 3: Tabela de avaliação com as questões específicas do artefato (Fonte: Lucas Frazão e Chaydson, 2023). </p>
</div>

<center>

### Tarefas

| ID Correção | Tarefa                                                                                                                                                                   |
| ------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| IDC1          | Não foi levantado os atributos definidos por Hackos e Redish, seria interessante levantar esses dados demográficos, assim teriamos um perfil de usuário mais conciso |
| IDC2          | Seria interessante colocar o perfil de usuário traçado em forma de tabela, para melhor vizualização, semelhante ao que foi feito na matéria de IHC                  |
| IDC3          | Adicionar o termo de consentimento utilizado no questionário e explicitar os aspectos éticos.                                                                          |
| IDC4          | Adicionar a quantidade de tempo que o usuário utiliza o booking ou semelhante                                                                                           |
| IDC5          | Na tabela do perfil de usuário, explicitar a atitude dele, tecnófilos, tecnófobos.                                                                                  |

<div style="text-align: center">
<p> Tabela 4: Tabela do que precisa ser ajustado (Fonte: Lucas e Chaydson, 2023). </p>
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

- 10/16 exigências são atendidas;
- 2/16 exigências estão incompletas;
- 4/16 exigências estão erradas ou não foram realizadas.

onde x é a quantidade de exigências.

```vegalite
{
    "title": "Acompanhamento",
  "$schema": "https://vega.github.io/schema/vega-lite/v5.json",
  "description": "A simple donut chart with embedded data.",
  "data": {
    "values": [
      {"legenda": "Completo", "value": 10},
      {"legenda": "Incompleto", "value": 4},
      {"legenda": "Errado ou não feito", "value": 2},
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

Portanto, com base na formula apresentada, pode-se dizer que o aproveitamento deste artefato está em 62,5% correto.

## Correção

### Ajustes

Na tabela 6, se encontra os ajustes que o autor do artefato realizou para arrumar o que foi pedido na tabela 4

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

## Bibliografia

BARBOSA, Simone Diniz Junqueira; DA SILVA, Bruno Santana. Interação Humano - Computador. Rio de janeiro: Elsevier, 2010.

Hackos e Redish, 1998; Courage e Baxter, 2005

## Histórico de versão

|    Data    | Versão |      Descrição      |    Autor(es)    |
| :--------: | :-----: | :--------------------: | :--------------: |
| 20/06/2023 |   1.0   | Criação do documento | Lucas e Chaydson |
