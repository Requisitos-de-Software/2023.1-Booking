# Verificação do Storytelling

## Introdução

O presente documento apresentará a verificação do artefato [Storytelling](../../elicitacao/storytelling.md), desenvolvido pela equipe. A técnica de inspeção será aplicada para verificar esse artefato, de acordo com o planejamento estabelecido. Na tabela 1, se encontra os metadados desse artefato, nas tabelas 2 e 3 se encontram as questões a serem avaliadas e no Gráfico 1, o quanto das exigências foram atendidas.
A tabela 1 a seguir representa os metadados do storytelling.

<center>

| Versão avaliada | Autor          | Revisor |
| ---------------- | -------------- | ------- |
| 1.0              | Lucas e Samuel | Gabriel |

</center>

<div style="text-align: center">
<p> Tabela 1: Dados do artefato Storytelling. (Fonte: Chaydson e Gabriel, 2023). </p>
</div>

| ID |                                   Questão                                   | Inspeção |
| :-: | :---------------------------------------------------------------------------: | :--------: |
| 1 |                   As legendas estão no padrão do projeto?                   |     🟢     |
| 2 |                    Possui links para os outros artefatos?                    |     🔴     |
| 3 |                     Existe uma introdução no artefato?                     |     🟢     |
| 4 |                  Existe tabela de versionamento padronizado?                  |     🟢     |
| 5 | Há referências bibliográficas, bibliografia ou referências no artefato? |     🟢     |
| 6 |   As tabelas e imagens possuem legenda, fonte e são introduzidas no texto?   |     🟢     |
| 7 |                           O artefato possui autor?                           |     🟢     |
| 8 |                          O artefato possui revisor?                          |     🟢     |

<div style="text-align: center">
<p> Tabela 2: Tabela de avaliação com as verificações gerais para todos os artefatos (Fonte: Chaydson e Gabriel, 2023). </p>
</div>

| ID |                                              Questão                                              | Inspeção |
| :-: | :-------------------------------------------------------------------------------------------------: | :--------: |
| 9 |               Para a realização do storytelling foi feita através de encenação?               |     🟢     |
| 10 |                            As histórias apresentam inicio, meio e fim?                            |     🟢     |
| 11 |         As ideias propostas nas histórias condizem os objetivos e interesses das personas?         |     🟢     |
| 12 |          As histórias possuem sentido e possuem ligação com o proposto pelo aplicativo?          |     🟢     |
| 13 |                              A causalidade das histórias faz sentido?                              |     🟢     |
| 14 |                              As histórias possuem algo único nelas?                              |     🟢     |
| 15 |                            Os personagens dessa histórias são citados?                            |     🟢     |
| 16 |                  Os requisitos elicitados apresentam ligação com as histórias?                  |     🟢     |
| 17 | Os personagens estão citados na elicitação de requisitos, ou existem algum que não foi citado? |     🟢     |

<div style="text-align: center">
<p> Tabela 3: Tabela de avaliação com as questões específicas do artefato (Fonte: Chaydson e Gabriel, 2023). </p>
</div>

<center>

### Tarefas

| ID Correção | Tarefa                                                                                          |
| ------------- | ----------------------------------------------------------------------------------------------- |
| IDC1          | Incluir link para personas, que é citada no texto                                              |
| IDC2          | Incluir uma persona Harry, no artefato de personas, para deixar mais detalhado o uso do booking |

<div style="text-align: center">
<p> Tabela 4: Tabela do que precisa ser ajustado (Fonte: Chaydson e Gabriel, 2023). </p>
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

- 16/17 exigências são atendidas;
- 0/17 exigências estão incompletas;
- 1/17 exigências estão erradas ou não foram realizadas.

onde x é a quantidade de exigências.

```vegalite
{
    "title": "Acompanhamento",
  "$schema": "https://vega.github.io/schema/vega-lite/v5.json",
  "description": "Dados de acompanhamento do Storytelling",
  "data": {
    "values": [
      {"legenda": "Completo", "value": 16},
      {"legenda": "Incompleto", "value": 0},
      {"legenda": "Errado", "value": 1}
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
<p> Gráfico 1: Gráfico de aproveitamento (Fonte: Gabriel e Chaydson, 2023). </p>
</div>

Portanto, com base na formula apresentada, pode-se dizer que o aproveitamento deste artefato está em 94,12% correto.

## Correção

### Ajustes

Na tabela 6, se encontra os ajustes que o autor do artefato realizou para arrumar o que foi pedido na tabela 4

| ID Correção | Ajuste                                                                   |
| ------------- | ------------------------------------------------------------------------ |
| IDC1          | Foi incluido o link para personas                                        |
| IDC2          | Foi alterado o nome do usuário para alguma persona criada anteriormente |

<div style="text-align: center">
<p> Tabela 6: Tabela de ajustes feitos (Fonte: Lucas e Samuel, 2023). </p>
</div>

</center>

Após as correções, a nova porcentagem de aproveitamento é de: 100% correto.

## Bibliografia

Barbosa, S. D. J.; Silva, B. S. da; Silveira, M. S.; Gasparini, I.; Darin, T.; Barbosa, G. D. J. (2021)
Interação Humano-Computador e Experiência do usuário. Autopublicação. ISBN: 978-65-00-19677-1

Santos, V. G., Daher N., Utilização de Storytelling como ferramenta de aquisição em processo de desenvolvimento de software apoiados em modelos ágeis: o uso apoiado no extreme programming, Belo Horizonte, 2008. 14 p., Artigo (Análise de Sistemas), e-tec UNI-BH, 2008. Disponível em : [https://revistas.unibh.br/dtec/article/view/440/238](https://revistas.unibh.br/dtec/article/view/440/238). Acesso em 20 de junho de 2023.

XAVIER, Adilson.  **Storytelling** : Histórias que deixam marca. 1. ed. Rio de Janeiro: Best.business, 2015. 306 p. v. 1. ISBN 978-85-7684-903-2.

## Histórico de Versão

| Versão | Data       | Descrição                                     | Autor(es)          |
| ------- | ---------- | ----------------------------------------------- | ------------------ |
| 1.0     | 20/06/2023 | Criação do documento de verificação         | Chaydson e Gabriel |
| 1.1     | 21/06/2023 | Adicionando nova porcentagem após a correção | Lucas e Samuel     |

‌
