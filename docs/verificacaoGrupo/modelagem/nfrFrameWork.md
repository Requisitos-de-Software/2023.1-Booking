# Verificação do NFR Framework

## Introdução

O presente documento apresentará a verificação do artefato [NFR Framework
](../../modelagem/modelo-agil/nfrFramework.md), desenvolvido pela equipe. A técnica de inspeção será aplicada para verificar esse artefato, de acordo com o planejamento estabelecido. Na tabela 1, se encontra os metadados desse artefato, nas tabelas 2 e 3 se encontram as questões a serem avaliadas e no Gráfico 1, o quanto das exigências foram atendidas.

A tabela 1 a seguir representa os dados do artefato Especificação Suplementar.

<center>

| Versão avaliada | Autor             | Revisor  |
| ---------------- | ----------------- | -------- |
| 1.0              | Henrique e Samuel | Chaydson |

</center>

<div style="text-align: center">
<p> Tabela 1: Dados do artefato Especificação Suplementar. (Fonte: Lucas e Chaydson, 2023). </p>
</div>

| ID |                                   Questão                                   | Inspeção |
| :-: | :---------------------------------------------------------------------------: | :--------: |
| 1 |                   As legendas estão no padrão do projeto?                   |     🟢     |
| 2 |                    Possui links para os outros artefatos?                    |     🟢     |
| 3 |                     Existe uma introdução no artefato?                     |     🟡     |
| 4 |                  Existe tabela de versionamento padronizado?                  |     🟢     |
| 5 | Há referências bibliográficas, bibliografia ou referências no artefato? |     🟡     |
| 6 |   As tabelas e imagens possuem legenda, fonte e são introduzidas no texto?   |     🔴     |
| 7 |                           O artefato possui autor?                           |     🟢     |
| 8 |                          O artefato possui revisor?                          |     🟢     |

<div style="text-align: center">
<p> Tabela 2: Tabela de avaliação com as verificações gerais para todos os artefatos (Fonte: Chaydson e Lucas, 2023). </p>
</div>

| ID |                                                                                Questão                                                                                | Inspeção |
| :-: | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------: | :--------: |
| 9 |                                                           O NFR está focado nos requisitos não-funcionais?                                                           |     🟢     |
| 10 |                                             Os NFR Softgoals são representados por uma nuvem desenhada com linhas finas?                                             |     🟢     |
| 11 |                                                        Os NFR Softgoals representam requisitos não funcionais?                                                        |     🟢     |
| 12 |                                                                Os NFR Softgoals possuem tipo e tópico?                                                                |     🔴     |
| 13 |                                      Os Operationalizing Softgoals são representados por uma nuvem desenhada com linhas grossas?                                      |     🟢     |
| 14 |                                                       Os Operationalizing Softgoals representam funcionalidades?                                                       |     🔴     |
| 15 |                                               Os Claim Softgoals são representados por uma nuvem com linha pontilhada?                                               |    N/A    |
| 16 |                                         Os Claim Softgoals representam uma anotação sobre um ponto específico da modelagem?                                         |    N/A    |
| 17 |                                          Os Contributions foram aplicados no diagrama? Eles foram usados de maneira correta?                                          |     🔴     |
| 18 |                                              As Labels foram aplicadas no diagrama? Elas foram usadas de maneira correta?                                              |     🟢     |
| 19 |                                               O diagrama apresenta Decompositions? Eles foram usados de maneira correta?                                               |     🟢     |
| 20 |                                                       A propagação de impactos foi realizada de forma correta?                                                       |     🟢     |
| 21 |                                                             Os requisitos não-funcionais são testáveis?                                                             |     🟢     |
| 22 | Os Cartões de especificação possui Número do Requisito, Descrição, Justificativa, Origem, Critério de Ajuste, Dependências, prioridade, conflitos e história? |     🔴     |

<div style="text-align: center">
<p> Tabela 3: Tabela de avaliação com as questões específicas do artefato (Fonte: Chaydson e Lucas, 2023). </p>
</div>

<center>

### Tarefas

| ID Correção | Tarefa                                                                                  |
| ------------- | --------------------------------------------------------------------------------------- |
| IDC1          | Explicar melhor sobre a aplicação do NFR Framework no projeto                        |
| IDC2          | Corrigir referência fora do padrão. Silva era para ser SILVA.                       |
| IDC3          | Chamar Tabela 1 no texto.                                                               |
| IDC4          | Remover duplicação do nome Tabela 2                                                   |
| IDC5          | Chamar a Tabela 2 e a futura Tabela 3 no texto                                          |
| IDC6          | Adicionar tópicos aos NFR Softgoals                                                   |
| IDC7          | Ajustar Operationalizing Softgoals que estão representados requisitos não-funcionais |
| IDC8          | Colocar Contributions no padrão                                                       |
| IDC9          | Adicionar dependências, conflitos e história nos Cartões de especificação         |
| IDC10         | Revisar se realmente não precisa de nenhum Claim Softgoals                            |

</center>

## Acompanhamento

Para saber a porcentagem de aproveitamento do artefato, será utilizado a expressão da Figura 1, no qual a Tabela 5 apresenta o significado dessa legendas.

<div style="text-align: center">
<img src="../../../images/formulaCalculoAproveitamento.png"  alt="legenda da fórmula da figura 1"/>

<p> Figura 1: Fórmula para calcular aproveitamento (Fonte: Chaydson e Lucas, 2023). </p>
</div>

<center>

| Acrônimo | Descrição                     |
| --------- | ------------------------------- |
| QTDE      | Quantidade Total de Exigências |
| EC        | Exigências Completas           |

<div style="text-align: center">
<p> Tabela 5: Legenda da Figura 1 (Fonte: Chaydson e Lucas, 2023). </p>
</div>

</center>

### Porcentagem

Nos checklists realizados e que serão descritos, podemos observar que:

- 13/22 exigências são atendidas;
- 2/22 exigências estão incompletas;
- 5/22 exigências estão erradas ou não foram realizadas;
- 2/22 exigências não se aplicam ao artefato;

```vegalite
{
    "title": "Acompanhamento",
  "$schema": "https://vega.github.io/schema/vega-lite/v5.json",
  "description": "Dados de acompanhamento do Storytelling",
  "data": {
    "values": [
      {"legenda": "Completo", "value": 13},
      {"legenda": "Incompleto", "value": 2},
      {"legenda": "Errado", "value": 5}
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
<p> Gráfico 1: Gráfico de aproveitamento (Fonte: Chaydson e Lucas, 2023). </p>
</div>

Portanto, com base na formula apresentada, pode-se dizer que o aproveitamento deste artefato está em 59,1% correto.

## Correção

### Ajustes

Na tabela 6, se encontra os ajustes que o autor do artefato realizou para arrumar o que foi pedido na tabela 4

| ID Correção | Ajuste |
| ------------- | ------ |
| IDC1          |        |
| IDC2          |        |
| IDC3          |        |
| IDC4          |        |
| IDC5          |        |
| IDC6          |        |
| IDC7          |        |
| IDC8          |        |
| IDC9          |        |
| IDC10         |        |

<div style="text-align: center">
<p> Tabela 6: Tabela de ajustes feitos (Fonte: Lucas e Chaydson, 2023). </p>
</div>

</center>

Após as correções, a nova porcentagem de aproveitamento é de: p% correto.

## Bibliografia

SILVA, Reinaldo. NFR4ES: Um Catálogo de Requisitos Não-Funcionais para Sistemas Embarcados. Centro de Informática UFPE, Recife, 2019. Disponível em: [https://repositorio.ufpe.br/handle/123456789/34150](https://repositorio.ufpe.br/handle/123456789/34150) Acesso em: 21/06/2023.

MESQUITA, Renato. Engenharia dos requisitos de software. UFMG, Belo Horizonte, 2019. Disponível em: [https://www.cin.ufpe.br/~if716/arquivos20152/experimentoBruno/Aula2/Aula2-Parte2-NFR%20Framework.pdf](https://www.cin.ufpe.br/~if716/arquivos20152/experimentoBruno/Aula2/Aula2-Parte2-NFR%20Framework.pdf) Acesso em: 21/06/2023.

SERRANO, Milene; SERRANO, Maurício. Requisitos - Aula 17. UnB, Brasília, 2023. Disponível em: [https://aprender3.unb.br/pluginfile.php/2580553/mod_resource/content/2/Requisitos%20-%20Aula%2007.pdf](https://aprender3.unb.br/pluginfile.php/2580553/mod_resource/content/2/Requisitos%20-%20Aula%2007.pdf) Acesso em: 21/06/2023.

## Histórico de Versão

| Versão | Data       | Descrição                             | Autor(es)        |
| ------- | ---------- | --------------------------------------- | ---------------- |
| 1.0     | 21/06/2023 | Criação do documento de verificação | Chaydson e Lucas |

‌
