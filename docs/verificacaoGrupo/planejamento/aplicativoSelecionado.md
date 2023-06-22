# Verificação dos Aplicativo selecionado

## Introdução

O presente documento apresentará a verificação do artefato [Aplicativo selecionado](../../planejamento/aplicativoSelecionado.md), desenvolvidos pela equipe. A técnica de inspeção será aplicada para verificar esse artefato, de acordo com o planejamento estabelecido. Na tabela 1, se encontra os metadados desse artefato, nas tabelas 2 e 3 se encontram as questões a serem avaliadas.

<center>

| Versão avaliada | Autor        | Revisor     |
| ---------------- | ------------ | ----------- |
| 1.0              | Samuel Gomes | Lucas Lopes |

</center>

<div style="text-align: center">
<p> Tabela 1: Metadados do artefato (Fonte: Pedro Henrique, 2023). </p>
</div>

| ID |                                 Questão                                 | Inspeção |
| :-: | :-----------------------------------------------------------------------: | :--------: |
| 1 |                 As legendas estão no padrão do projeto?                 |     🟢     |
| 2 |                  Possui links para os outros artefatos?                  |     🟢     |
| 3 |                   Existe uma introdução no artefato?                   |     🟡     |
| 4 |                Existe tabela de versionamento padronizado?                |     🟢     |
| 5 |      Há referências bibliográficas ou referências no artefato?      |     🟡     |
| 6 | As tabelas e imagens possuem legenda, fonte e são introduzidas no texto? |     🟡     |
| 7 |                         O artefato possui autor?                         |     🟢     |
| 8 |                        O artefato possui revisor?                        |     🟢     |

<div style="text-align: center">
<p> Tabela 2: Tabela de avaliação com as gerais para todos os artefatos (Fonte: Pedro Henrique, 2023). </p>
</div>

| ID |                                                           Questão                                                           | Inspeção |
| :-: | :---------------------------------------------------------------------------------------------------------------------------: | :--------: |
| 9 |                                   O aplicativos não foi trabalhado no semestre anterior?                                   |     🟢     |
| 10 |          O aplicativo é do governo ou comunidade? (caso não seja deve ter uma forma de autorização da empresa)          |     🟢     |
| 11 |                                      É levado em consideração o acesso aos usuarios?                                      |     🔴     |
| 12 |                                       É descrito os motivos de escolha do aplicativo?                                       |     🟡     |
| 13 |                                            Foi feito o rich picture do aplicativo?                                            |     🟢     |
| 14 | O aplicativo selecionado para o projeto da disicplina está de acordo com os termos de uso da empresa responsavel pelo mesmo? |     🟢     |

<div style="text-align: center">
<p> Tabela 3: Tabela de avaliação com as questões específicas do artefato (Fonte: Pedro Henrique, 2023). </p>
</div>

<center>

### Tarefas

| ID Correção | Tarefa                                                                                               |
| ------------- | ---------------------------------------------------------------------------------------------------- |
| IDC1          | Introdução relativamente curta. Reescrever a introdução para especificar melhor o artefato.      |
| IDC2          | retirar [1] das referencias bibliograficas                                                          |
| IDC3          | Retirar "abaixo" dos referenciamentos das imagens no texto e substituir por "a seguir", por exemplo. |
| IDC4          | adicionar ao tópico "Por que foi escolhido o Booking?" que o acesso aos usuários foi considerado.  |

<div style="text-align: center">
<p> Tabela 4: Tabela do que precisa ser ajustado (Fonte: Pedro Henrique, 2023). </p>
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

- 9/14 exigências são atendidas;
- 4/14 exigências estão incompletas;
- 1/14 exigências estão erradas ou não foram realizadas.
- 0/14 não se aplica.

onde 14 é a quantidade de exigências.

```vegalite
{
    "title": "Acompanhamento",
  "$schema": "https://vega.github.io/schema/vega-lite/v5.json",
  "description": "A simple donut chart with embedded data.",
  "data": {
    "values": [
      {"legenda": "Completo", "value": 9},
      {"legenda": "Incompleto", "value": 4},
      {"legenda": "Errado", "value": 1},
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
        "domain": ["Completo", "Incompleto", "Errado", "Não se aplica"],
        "range": ["green", "yellow", "red", "blue"]
      }
    }
  }
}
```

<div style="text-align: center">
<p> Gráfico 1: Gráfico de aproveitamento (Fonte: Pedro Henrique, 2023). </p>
</div>

Portanto, com base na formula apresentada, pode-se dizer que o aproveitamento deste artefato está em 64,28% correto.

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
<p> Tabela 6: Tabela de ajustes feitos (Fonte: Pedro Henrique, 2023). </p>
</div>

</center>

## Bibliografia

Barbosa, S. D. J.; Silva, B. S. da; Silveira, M. S.; Gasparini, I.; Darin, T.; Barbosa, G. D. J. (2021) Interação Humano-Computador e Experiência do usuário. Autopublicação. ISBN: 978-65-00-19677-1.

## Histórico de versão

|    Data    | Versão |      Descrição      | Autor(es) |
| :--------: | :-----: | :--------------------: | :-------: |
| 20/06/2023 |   1.0   | Criação do documento |   Pedro   |
