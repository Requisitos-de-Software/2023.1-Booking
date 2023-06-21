# Verificação do Brainstorm

## Introdução

O presente documento apresentará a verificação do artefato [Brainstorm](../../elicitacao/brainstorm.md), desenvolvido pela equipe. A técnica de inspeção será aplicada para verificar esse artefato, de acordo com o planejamento estabelecido. Na tabela 1, se encontra os metadados desse artefato, nas tabelas 2 e 3 se encontram as questões a serem avaliadas e no Gráfico 1, o quanto das exigências foram atendidas.

A tabela 1 a seguir representa os dados do artefato Brainstorm.

<center>

| Versão avaliada | Autor            | Revisor  |
| ---------------- | ---------------- | -------- |
| 1.0              | Gabriel e Samuel | Henrique |

</center>

<div style="text-align: center">
<p> Tabela 1: Dados do artefato Brainstorm. (Fonte: Henrique, 2023). </p>
</div>

| ID |                                   Questão                                   | Inspeção |
| :-: | :---------------------------------------------------------------------------: | :--------: |
| 1 |                   As legendas estão no padrão do projeto?                   |     🟡     |
| 2 |                    Possui links para os outros artefatos?                    |     🟢     |
| 3 |                     Existe uma introdução no artefato?                     |     🟢     |
| 4 |                  Existe tabela de versionamento padronizado?                  |     🟢     |
| 5 | Há referências bibliográficas, bibliografia ou referências no artefato? |     🟢     |
| 6 |   As tabelas e imagens possuem legenda, fonte e são introduzidas no texto?   |     🟢     |
| 7 |                           O artefato possui autor?                           |     🟢     |
| 8 |                          O artefato possui revisor?                          |     🟢     |

<div style="text-align: center">
<p> Tabela 2: Tabela de avaliação com as verificações gerais para todos os artefatos (Fonte: Henrique, 2023). </p>
</div>

| ID |                               Questão                               | Inspeção |
| :-: | :------------------------------------------------------------------: | :--------: |
| 9 |    Foram documentados todos os requisitos propostos no brainstorm    |     🟢     |
| 10 |        Todos os requisitos possuem um ID de rastreabilidade?        |     🟢     |
| 11 | Foi documentada informações sobre a reunião? (Data, hora e local) |     🟢     |
| 12 |           Está documentado o papel de cada participante?           |     🟡     |
| 13 |  O Brainstorm possui um moderador e um relator em sua realização?  |     🟢     |
| 14 |       Disponível a gravação da realização do Brainstorm?       |     🟢     |
| 15 |              O brainstorm abordou conceitos do sistema?              |     🟢     |

<div style="text-align: center">
<p> Tabela 3: Tabela de avaliação com as questões específicas do artefato (Fonte: Henrique, 2023). </p>
</div>

<center>

### Tarefas

| ID Correção | Tarefa                                                                                               |
| ------------- | ---------------------------------------------------------------------------------------------------- |
| IDC1          | Arrumar centralização da legenda das tabelas 1,2 e 4, para padronizar com o restante do documento. |
| IDC2          | É necessario estar documentado na tabela de participantes, o papel de cada um dentro do Brainstorm  |

<div style="text-align: center">
<p> Tabela 4: Tabela do que precisa ser ajustado (Fonte: Henrique, 2023). </p>
</div>

</center>

## Acompanhamento

Para saber a porcentagem de aproveitamento do artefato, será utilizado a expressão da Figura 1, no qual a Tabela 5 apresenta o significado dessa legendas.

<div style="text-align: center">
<img src="../../../images/formulaCalculoAproveitamento.png"  alt="legenda da fórmula da figura 1"/>

<p> Figura 1: Fórmula para calcular aproveitamento (Fonte: Henrique, 2023). </p>
</div>

<center>

| Acrônimo | Descrição                     |
| --------- | ------------------------------- |
| QTDE      | Quantidade Total de Exigências |
| EC        | Exigências Completas           |

<div style="text-align: center">
<p> Tabela 5: Legenda da Figura 1 (Fonte: Henrique, 2023). </p>
</div>

</center>

### Porcentagem

Nos checklists realizados e que serão descritos, podemos observar que:

- 13/15 exigências são atendidas;
- 2/15 exigências estão incompletas;
- 0/15 exigências estão erradas ou não foram realizadas;

```vegalite
{
    "title": "Acompanhamento",
  "$schema": "https://vega.github.io/schema/vega-lite/v5.json",
  "description": "Dados de acompanhamento do Storytelling",
  "data": {
    "values": [
      {"legenda": "Completo", "value": 13},
      {"legenda": "Incompleto", "value": 2},
      {"legenda": "Errado", "value": 0}
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

Portanto, com base na formula apresentada, pode-se dizer que o aproveitamento deste artefato está em 86,66% correto.

## Correção

### Ajustes

Na tabela 6, se encontra os ajustes que o autor do artefato realizou para arrumar o que foi pedido na tabela 4

| ID Correção | Ajuste                       |
| ------------- | ---------------------------- |
| IDC1          | Foi ajustado x realizando... |
| IDC2          | Foi incluido x em ...        |

<div style="text-align: center">
<p> Tabela 6: Tabela de ajustes feitos (Fonte: Gabriel e Samuel, 2023). </p>
</div>

</center>

Após as correções, a nova porcentagem de aproveitamento é de: p% correto.

## Bibliografia

BARBOSA, Simone Diniz Junqueira; DA SILVA, Bruno Santana. Interação Humano - Computador. Rio de janeiro: Elsevier, 2010.

SEMRUSH. Guia para fazer brainstorming. Disponível em: [https://pt.semrush.com/blog/guia-para-fazer-brainstorming/?kw=&cmp=BR_POR_SRCH_DSA_Blog_PT&label=dsa_pagefeed&Network=g&Device=c&utm_content=641182636752&kwid=dsa-1930213679728&cmpid=19241772885&agpid=147326211351&BU=Core&extid=64625807523&adpos=&gclid=CjwKCAjwv8qkBhAnEiwAkY-ahkn32w-55mqIA8poBz-XJLB15uJCkWiUTF2DjWSxwLK4T0sfOvfuDhoCNiwQAvD_BwE](https://pt.semrush.com/blog/guia-para-fazer-brainstorming/?kw=&cmp=BR_POR_SRCH_DSA_Blog_PT&label=dsa_pagefeed&Network=g&Device=c&utm_content=641182636752&kwid=dsa-1930213679728&cmpid=19241772885&agpid=147326211351&BU=Core&extid=64625807523&adpos=&gclid=CjwKCAjwv8qkBhAnEiwAkY-ahkn32w-55mqIA8poBz-XJLB15uJCkWiUTF2DjWSxwLK4T0sfOvfuDhoCNiwQAvD_BwE). Acesso em: 21 jun. 2023.

BARBOSA, Simone et al. Identificação de Necessidades dos Usuários e Definição dos Requisitos de IHC: brainstorming de necessidades e desejos dos usuários. In: BARBOSA, Simone et al. Interação Humano-Computador e Experiência do Usuário. Rio de Janeiro: Autopublicação, 2021. Cap. 7. p. 152-155.

REQUISITOS DE SOFTWARE. Brainstorming 2. Disponível em: [https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/verificacao/grupo2/entrega2/brainstorm2/#FTF1](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/verificacao/grupo2/entrega2/brainstorm2/#FTF1). Acesso em: [data de acesso].


## Histórico de Versão

| Versão | Data       | Descrição                             | Autor(es)         |
| ------- | ---------- | --------------------------------------- | ----------------- |
| 1.0     | 20/06/2023 | Criação do documento de verificação | Henrique e Samuel |

‌
