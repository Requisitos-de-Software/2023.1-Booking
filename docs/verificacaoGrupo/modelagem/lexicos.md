# Verificação dos Léxicos

## Introdução

O presente documento apresentará a verificação do artefato [Léxicos](../../modelagem/lexicos.md), desenvolvido pela equipe. A técnica de inspeção será aplicada para verificar esse artefato, de acordo com o planejamento estabelecido. Na tabela 1, se encontra os metadados desse artefato, nas tabelas 2 e 3 se encontram as questões a serem avaliadas e no Gráfico 1, o quanto das exigências foram atendidas.

A tabela 1 a seguir representa os dados do artefato Léxicos.

<center>

| Versão avaliada | Autor          | Revisor |
| ---------------- | -------------- | ------- |
| 1.0              | Pedro e Samuel | Lucas   |

</center>

<div style="text-align: center">
<p> Tabela 1: Dados do artefato Léxicos (Fonte: Henrique, 2023). </p>
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

| ID |                                                Questão                                                | Inspeção |
| :-: | :----------------------------------------------------------------------------------------------------: | :--------: |
| 9 |              As referências para outros termos dentro do LAL são feitas com hyperlinks?              |     🔴     |
| 10 |                            O princípio circular foi devidamente propagado?                            |     🔴     |
| 11 |                         Os termos são relevantes para o domínio em questão?                         |     🟢     |
| 12 |                          Os termos foram definidos de forma clara e concisa?                          |     🟢     |
| 13 |                           Os símbolos são descritos com noção e impacto?                           |     🟢     |
| 14 |                                Os símbolos tem pelo menos uma noção?                                |     🟢     |
| 15 |                                Os símbolos tem pelo menos um impacto?                                |     🟢     |
| 16 |                 Se existir símbolos com sinônimos, isso foi devidamente documentado?                 |     🟢     |
| 17 |                                       Os símbolos possuem tipo?                                       |     🟢     |
| 18 |                   Os símbolos pertencem a somente um tipo(VERBO, OBJETO ou ESTADO)?                   |     🟢     |
| 19 |    O campo noção dos símbolos do tipo VERBO seguem o modelo "Quem? Quando? Quais procedimento?"?    |     🟢     |
| 20 |              O campo impacto dos símbolos do tipo VERBO explicam os reflexos da ação?              |     🟢     |
| 21 |             O campo noção dos símbolos do tipo OBJETO contém uma definição do mesmo?             |     🟢     |
| 22 |      O campo impacto dos símbolos do tipo OBJETO descrevem as ações que aquele objeto realiza?      |     🟢     |
| 23 |       O campo noção dos símbolos do tipo ESTADO o significado e quando aquele estado ocorre?       |     🟢     |
| 24 | O campo impacto dos símbolos do tipo ESTADO mostram quais são os estado decorrentes do estado atual? |     🟢     |

<div style="text-align: center">
<p> Tabela 3: Tabela de avaliação com as questões específicas do artefato (Fonte: Henrique, 2023). </p>
</div>

<center>

### Tarefas

| ID Correção | Tarefa                                                                                                         |
| ------------- | -------------------------------------------------------------------------------------------------------------- |
| IDC1          | Arrumar ordem das legendas das tabelas que não está em oredem.                                               |
| IDC2          | Se um léxico é citado em um outro léxico, ele precisa ter uma ligação com o léxico dele por um hyperlink |

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

- 21/24 exigências são atendidas;
- 1/24 exigências estão incompletas;
- 2/24 exigências estão erradas ou não foram realizadas;

```vegalite
{
    "title": "Acompanhamento",
  "$schema": "https://vega.github.io/schema/vega-lite/v5.json",
  "description": "Dados de acompanhamento do Storytelling",
  "data": {
    "values": [
      {"legenda": "Completo", "value": 21},
      {"legenda": "Incompleto", "value": 1},
      {"legenda": "Errado", "value": 2}
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

Portanto, com base na formula apresentada, pode-se dizer que o aproveitamento deste artefato está em 87,50% correto.

## Correção

### Ajustes

Na tabela 6, se encontra os ajustes que o autor do artefato realizou para arrumar o que foi pedido na tabela 4

| ID Correção | Ajuste                       |
| ------------- | ---------------------------- |
| IDC1          | Foi ajustado x realizando... |
| IDC2          | Foi incluido x em ...        |

<div style="text-align: center">
<p> Tabela 6: Tabela de ajustes feitos (Fonte: Pedro e Samuel, 2023). </p>
</div>

</center>

Após as correções, a nova porcentagem de aproveitamento é de: p% correto.

## Bibliografia

Requisitos Aula 10 - Serrano Milene, Serrano Maurício. Disponível em: [https://aprender3.unb.br/pluginfile.php/2523091/mod_resource/content/1/Aula%2010.pdf](https://aprender3.unb.br/pluginfile.php/2523091/mod_resource/content/1/Aula%2010.pdf). Acesso em: 21 jun. 2023.

LEITE, Julio Cesar. Léxico Ampliado da Linguagem, 2012. Disponível em: [https://www-di.inf.puc-rio.br/~julio/lal.pdf](https://www-di.inf.puc-rio.br/~julio/lal.pdf). Acesso em: 21 jun. 2023.

REQUISITOS DE SOFTWARE. Léxicos. Disponível em: [https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/verificacao/grupo2/entrega3/lexicos/](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/verificacao/grupo2/entrega3/lexicos/). Acesso em: 21 jun. 2023.

## Histórico de Versão

| Versão | Data       | Descrição                             | Autor(es)           |
| ------- | ---------- | --------------------------------------- | ------------------- |
| 1.0     | 21/06/2023 | Criação do documento de verificação | Henrique e Chaydson |

‌
