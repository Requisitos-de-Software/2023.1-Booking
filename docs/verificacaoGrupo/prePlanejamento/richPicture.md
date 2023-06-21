# Verificação do Rich Picture

## Introdução

O presente documento apresentará a verificação do artefato [Rich Picture](../../prePlanejamento/richPicture.md), desenvolvido pela equipe. A técnica de inspeção será aplicada para verificar esse artefato, de acordo com o planejamento estabelecido. Na tabela 1, se encontra os metadados desse artefato, nas tabelas 2 e 3 se encontram as questões a serem avaliadas e no Gráfico 1, o quanto das exigências foram atendidas.

A tabela 1 a seguir representa os dados do artefato Rich Picture.

<center>

| Versão avaliada | Autor           | Revisor |
| ---------------- | --------------- | ------- |
| 1.1              | Gabriel e Lucas | Pedro   |

</center>

<div style="text-align: center">
<p> Tabela 1: Dados do artefato Rich Picture. (Fonte: Henrique, 2023). </p>
</div>

| ID |                                   Questão                                   | Inspeção |
| :-: | :---------------------------------------------------------------------------: | :--------: |
| 1 |                   As legendas estão no padrão do projeto?                   |     🟢     |
| 2 |                    Possui links para os outros artefatos?                    |     🟢     |
| 3 |                     Existe uma introdução no artefato?                     |     🟢     |
| 4 |                  Existe tabela de versionamento padronizado?                  |     🟢     |
| 5 | Há referências bibliográficas, bibliografia ou referências no artefato? |     🟡     |
| 6 |   As tabelas e imagens possuem legenda, fonte e são introduzidas no texto?   |     🟢     |
| 7 |                           O artefato possui autor?                           |     🟢     |
| 8 |                          O artefato possui revisor?                          |     🟢     |

<div style="text-align: center">
<p> Tabela 2: Tabela de avaliação com as verificações gerais para todos os artefatos (Fonte: Henrique, 2023). </p>
</div>

| ID |                                      Questão                                      | Inspeção |
| :-: | :---------------------------------------------------------------------------------: | :--------: |
| 9 | O Rich Picture possui várias versoẽs atualizadas e aprimoradas ao longo do tempo? |     🟢     |
| 10 |                      O Rich Picture possui uma legenda clara?                      |     🟢     |
| 11 |          O Rich Picture possui operações e armazenamentos bem definidos?          |     🟢     |
| 12 |                            O desenho possui fronteiras?                            |     🟢     |
| 13 |                         Os atores estão fora da fronteira?                         |     🟢     |
| 14 |           O Rich Picture mostra as principais funcionalidades do sistema?           |     🟢     |
| 15 |                           O artefato está bem desenhado?                           |     🟡     |

<div style="text-align: center">
<p> Tabela 3: Tabela de avaliação com as questões específicas do artefato (Fonte: Henrique, 2023). </p>
</div>

<center>

### Tarefas

| ID Correção | Tarefa                                                                                                  |
| ------------- | ------------------------------------------------------------------------------------------------------- |
| IDC1          | Um aprimoramento no desenho do segundo rich picture, podderá trazer um melhor entendimento sobre ele. |
| IDC2          | Em bibliografia, retirar os números ([1][2][3]) antes das citações.                                  |
| IDC3          | Adicionar uma metodologia, explicitando as técnicas utilizadas na elaboração.                        |

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
| IDC3          | Foi removido x ...           |

<div style="text-align: center">
<p> Tabela 6: Tabela de ajustes feitos (Fonte: Gabriel e Lucas, 2023). </p>
</div>

</center>

Após as correções, a nova porcentagem de aproveitamento é de: p% correto.

## Bibliografia

Software Development Project: Introducing Rich Pictures. Disponível em: [https://aprender3.unb.br/pluginfile.php/2523045/mod_resource/content/2/1_5145791542719414573.pdf](https://aprender3.unb.br/pluginfile.php/2523045/mod_resource/content/2/1_5145791542719414573.pdf). Acesso em: 20 jun. 2023.

MONK, Andrew; HOWARD, Steve. The Rich Picture: A Tool for Reasoning About Work Context. Interactions, [S.l.], v. 5, n. 2, p. 21-30, mar. 1998. Disponível em: [https://www.ics.uci.edu/~wscacchi/Software-Process/Readings/RichPicture.pdf](https://www.ics.uci.edu/~wscacchi/Software-Process/Readings/RichPicture.pdf) . Acesso em: 20 jun. 2023.

## Histórico de Versão

| Versão | Data       | Descrição                             | Autor(es)           |
| ------- | ---------- | --------------------------------------- | ------------------- |
| 1.0     | 20/06/2023 | Criação do documento de verificação | Henrique e Chaydson |

‌
