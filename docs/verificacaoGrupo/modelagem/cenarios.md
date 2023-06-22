# Verificação do cenário

## Introdução

O presente documento apresentará a verificação do artefato [Cenários](../../verificacaoGrupo/modelagem/cenarios.md), desenvolvido pela equipe. A técnica de inspeção será aplicada para verificar esse artefato, de acordo com o planejamento estabelecido, na tabela 1, se encontra os metadados desse artefato, nas tabelas 2 e 3 se encontram as questões a serem avaliadas.

<center>

| Versão avaliada | Autor           | Revisor  |
| ---------------- | --------------- | -------- |
| 1.0              | Lucas e Gabriel | Chaydson |

</center>

<div style="text-align: center">
<p> Tabela 1: Versão avaliada. (Fonte: Chaydson e Samuel, 2023). </p>
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
<p> Tabela 2: Tabela de avaliação com as verificações gerais para todos os artefatos (Fonte: Chaydson e Samuel, 2023). </p>
</div>

| ID |                                                    Questão                                                    | Inspeção |
| :-: | :------------------------------------------------------------------------------------------------------------: | :--------: |
| 9 |       Os cenários contam com título, objetivos, contexto, ator(es), recursos, exceção e episódios?       |     🟢     |
| 10 |                             Os cenários foram escritos de forma clara e concisa?                             |     🟢     |
| 11 |                                  O contexto dos cenários está bem definido?                                  |     🟡     |
| 12 |                             O título deixa claro sobre o que se trata o cenário?                             |     🟡     |
| 13 |                      Os cenários foram construídos a partir de requisitos do sistema?                      |     🟢     |
| 14 |                       Os campos objetivo descrevem como o objetivo deve ser alcançado?                       |     🟢     |
| 15 |              Os campos contexto contam com pré-condições, o local e o tempo onde ele ocorre?              |     🟢     |
| 16 |          Os campos ator(es) representam um indivíduo ou organização que tem um papel no cenário?          |     🟢     |
| 17 |                Os campos recursos identificam os objetos que estão em contato com os atores?                |     🟢     |
| 18 | Os campos episódios representam uma ação realizada por atores que utilizam recursos previamente definidos? |     🟢     |
| 19 |                    Os campos exceção descrevem restrições relacionadas ao cenário?                    |     🟢     |

<div style="text-align: center">
<p> Tabela 3: Tabela de avaliação com as questões específicas do artefato (Fonte: Chaydson e Samuel, 2023). </p>
</div>

### Tarefas

| ID Correção | Tarefa                                                                                                                                                                                                                                                                                                                                                                                      |
| ------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| IDC1          | O contexto dos cenários fornece algumas informações irrelevantes. Por exemplo, o cenário de configuração de perfil inclui o contexto de tempo nublado, sendo que segundo Barbosa e Silva[1], o contexto ou ambiente deve conter "detalhes da situação que motivam ou explicam os objetivos, ações e reações<br />dos atores do cenário". Coloque um contexto mais relevante. |
| IDC2          | Em recursos, poderia ser adicionado o tempo disponível para o alcance do objetivo, como sugere a Tabela 8.3 de Barbosa e Silva[1].                                                                                                                                                                                                                                                         |
| IDC3          | Deixe o título do cenário 6 mais claro e específico ou divida em outros cenários, "Configuração de Perfil" não consegue representar totalmente o objetivo proposto.                                                                                                                                                                                                                  |

<div style="text-align: center">
<p> Tabela 4: Tabela do que precisa ser ajustado (Fonte: Chaydson e Samuel, 2023). </p>
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

- 16/19 exigências são atendidas;
- 3/19 exigências estão incompletas;
- 0/19 exigências estão erradas ou não foram realizadas.
- 1/19 não se aplica.

```vegalite
{
    "title": "Acompanhamento",
  "$schema": "https://vega.github.io/schema/vega-lite/v5.json",
  "description": "A simple donut chart with embedded data.",
  "data": {
    "values": [
      {"legenda": "Completo", "value": 16},
      {"legenda": "Incompleto", "value": 3},
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

Portanto, com base na formula apresentada, pode-se dizer que o aproveitamento deste artefato está em 84,21% correto.

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

## Referências Bibliográfica

[1] Barbosa, S. D. J.; Silva, B. S. da; Silveira, M. S.; Gasparini, I.; Darin, T.; Barbosa, G. D. J. (2021) Interação Humano-Computador e Experiência do usuário. Autopublicação. ISBN: 978-65-00-19677-1.

## Bibliografia

Cenários - Rastreamento de Cenários. Disponível em: [http://www-di.inf.puc-rio.br/~julio/bnncap3.pdf](http://www-di.inf.puc-rio.br/~julio/bnncap3.pdf) Acesso em: 21 de maio de 2023.

## Histórico de Versão

| Versão | Data       | Descrição                             | Autor(es)         |
| ------- | ---------- | --------------------------------------- | ----------------- |
| 1.0     | 21/06/2023 | Criação do documento de verificação | Chaydson e Samuel |
