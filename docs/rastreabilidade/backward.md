# Backward From

## Introdução

A rastreabilidade é uma propriedade de sistemas que permite que os requisitos sejam claramente conectados às suas origens e aos artefatos criados durante o ciclo de vida do desenvolvimento do sistema. É importante notar que a produção desses artefatos é guiada pela linha de base dos requisitos. A rastreabilidade para trás estabelece a ligação dos requisitos com suas fontes em outros documentos ou pessoas. Este artefato tem como objetivo usar a técnica “Backward From” para documentar as conexões entre os requisitos, seus desenhos e sua implementação.

Elos de rastreabilidade referem-se à relação estabelecida entre artefatos ou elementos de um processo, sistema ou projeto ao longo de seu ciclo de vida. Esses elos são usados para rastrear e documentar as relações e dependências entre diferentes componentes, como requisitos.

Os elos de rastreabilidade são particularmente úteis em atividades de engenharia de software e gerenciamento de projetos, pois permitem que os profissionais acompanhem e compreendam as relações entre os elementos do sistema. Isso facilita a análise de impacto de mudanças, a verificação do cumprimento dos requisitos e a identificação de possíveis lacunas ou inconsistências ao longo do desenvolvimento.

## Metodologia

Usaremos o Meta-modelo de Toranzo, aplicado à rastreabilidade de requisitos, que inclui a classificação dos requisitos em quatro níveis: ambiental, organizacional, gerencial e desenvolvimento, onde cada nivel é apresentado na tabela 1. O meta-modelo é usado para identificar os tipos de ligações entre os requisitos, como: satisfação, recurso, responsabilidade, representação, alocação e agregação, onde os tipos de relações são melhor descritos na tabela 2.

| Classificação    | Descrição                                                                                                                                                            |
| ---------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Ambiental        | Congrega informações oriundas do contexto ambiental onde a organização está inserida e que podem afetar o sistema sendo desenvolvido.                                |
| Organizacional   | Reúne informações relacionadas à organização (missão, objetivos, metas e padrões) e que podem impactar os requisitos do sistema.                                     |
| Gerencial        | Agrega informações que permitem associar tarefas a requisitos, e que podem auxiliar a gerência do projeto.                                                           |
| Desenvolvimento. | abarca informações relacionadas aos diversos artefatos gerados no processo de desenvolvimento (documento de requisitos, diagramas, programas, casos de testes, ...). |

<div style="text-align: center">
<p> Tabela 1: Classificação dos requisitos de acordo com o Meta-modelo de Toranzo.  (Fonte: Pedro e Henrique, 2023). </p>
</div>

| Tipo de ligação  | descrição                                                                           |
| ---------------- | ----------------------------------------------------------------------------------- |
| Satisfação       | indica que a classe de origem tem dependência de satisfação com classe de destino   |
| Recurso          | indica que a classe de origem tem dependência de recurso com classe de destino      |
| Responsabilidade | registra a participação, responsabilidade e ação de pessoas sobre artefatos         |
| Representação    | captura a representação ou modelagem dos requisitos em outras linguagens            |
| Alocação         | classe de origem está relacionada à classe de destino, que representa um subsistema |
| Agregação        | indica composição de elementos.                                                     |

<div style="text-align: center">
<p> Tabela 2: Tipos de ligação entre requisitos de acordo com o Meta-modelo de Toranzo.  (Fonte: Pedro e Henrique, 2023). </p>
</div>

## Legenda

A seguir, na Tabela 3, estão listadas todas as siglas utilizadas no artefato, juntamente com seus significados. Essas siglas são empregadas nas Tabelas 3 e 4, bem como no tópico referente aos Elos Funcionais e Elos não Funcionais.

<center>

| Legenda | Descrição                  |
| ------- | -------------------------- |
| FST     | Funcional Storytelling     |
| NFST    | Não Funcional Storytelling |
| FOBS    | Funcional Observação       |
| NFOBS   | Não Funcional Observação   |
| FB      | Funcional Brainstorm       |
| NFB     | Não Funcional Brainstorm   |
| RF      | Requisitos Funcionais      |
| RNF     | Requisitos não Funcionais  |
| EF      | Elo Funcional              |
| ENF     | Elo Não Funcional          |

<div style="text-align: center">
<p> Tabela 3: Legenda das tecnicas de elicitação.  (Fonte: Pedro e Henrique, 2023). </p>
</div>

</center>

## Requisitos Funcionais

A seguir é apresentado na Tabela 4, a lista dos Requisitos Funcionais elicitados.

| ID   | Requisito                                                                                                                                                                    | Origem                                                                                                                                                    |
| ---- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------- |
| RF01 | O aplicativo deve permitir que os usuários se registrem fornecendo informações básicas, como nome, sobrenome, endereço de e-mail e senha.                                    | [FST01](../elicitacao/storytelling.md) e [FOBS01](../elicitacao/observacao.md)                                                                            |
| RF02 | O aplicativo deve permitir que os usuários pesquisem acomodações com base em critérios específicos, como localização, datas de check-in e check-out, tipo de quarto e preço. | [FST02](../elicitacao/storytelling.md)                                                                                                                    |
| RF03 | O aplicativo deve permitir que os usuários reservem acomodações selecionadas, inserindo as informações de pagamento e confirmando a reserva.                                 | [FST03](../elicitacao/storytelling.md), [FB03](../elicitacao/brainstorm.md) e [FOBS06](../elicitacao/observacao.md)                                       |
| RF04 | O aplicativo deve permitir que os usuários cancelem suas reservas de acomodação, desde que sejam feitas dentro dos termos e condições estabelecidos pela empresa.            | [FST04](../elicitacao/storytelling.md) e [FB04](../elicitacao/brainstorm.md)                                                                              |
| RF05 | O aplicativo deve permitir que os usuários pesquisem voos com base em critérios específicos, como origem, destino, datas e número de passageiros.                            | [FST05](../elicitacao/storytelling.md)                                                                                                                    |
| RF06 | O aplicativo deve permitir que os usuários reservem voos selecionados, inserindo as informações de pagamento e confirmando a reserva.                                        | [FST06](../elicitacao/storytelling.md) e [FOBS07](../elicitacao/observacao.md)                                                                            |
| RF07 | O aplicativo deve permitir que os usuários gerenciem suas reservas existentes, incluindo a visualização de detalhes da reserva, alterações de datas e cancelamentos.         | [FST08](../elicitacao/storytelling.md)                                                                                                                    |
| RF08 | O aplicativo deve permitir que os usuários visualizem seu histórico de reservas anteriores, incluindo informações como datas, acomodações e voos reservados.                 | [FST10](../elicitacao/storytelling.md), [FB05](../elicitacao/brainstorm.md) , [FB06](../elicitacao/brainstorm.md) e [FOBS13](../elicitacao/observacao.md) |
| RF09 | O sistema deve possuir escolha do método de pagamento                                                                                                                        | [FB02](../elicitacao/brainstorm.md)                                                                                                                       |
| RF10 | Permitir que um grupo de pessoas reservem um local                                                                                                                           | [FB07](../elicitacao/brainstorm.md)                                                                                                                       |
| RF11 | Sincronizar as datas das reservas com o calendário do usuário                                                                                                                | [FB09](../elicitacao/brainstorm.md)                                                                                                                       |
| RF12 | Permitir visualização de imagens do local pelo usuário                                                                                                                       | [FB12](../elicitacao/brainstorm.md)                                                                                                                       |
| RF13 | Permitir visualização de imagens do carro pelo usuário                                                                                                                       | [FB13](../elicitacao/brainstorm.md)                                                                                                                       |
| RF14 | O sistema deve ser capaz de localizar o usuário se permitido                                                                                                                 | [FB22](../elicitacao/brainstorm.md)                                                                                                                       |
| RF15 | O sistema deve sugerir hospedagens de acordo com a localização do usuário                                                                                                    | [FB23](../elicitacao/brainstorm.md) e [FOBS04](../elicitacao/observacao.md)                                                                               |
| RF16 | O sistema deve oferecer uma aba de perguntas                                                                                                                                 | [FB24](../elicitacao/brainstorm.md)                                                                                                                       |
| RF17 | O sistema deve conter um bate-papo para contato com o locatário ou empresa em que foi feito a reserva                                                                        | [FB25](../elicitacao/brainstorm.md)                                                                                                                       |
| RF18 | O sistema deve ter um sistema de pontuação ligada ao usuário                                                                                                                 | [FB26](../elicitacao/brainstorm.md) e [FOBS03](../elicitacao/observacao.md)                                                                               |
| RF19 | O usuário deve poder denunciar contas                                                                                                                                        | [FB27](../elicitacao/brainstorm.md)                                                                                                                       |
| RF20 | Deve existir uma pesquisa por comando de voz                                                                                                                                 | [FB31](../elicitacao/brainstorm.md)                                                                                                                       |
| RF21 | O usuário deve poder avaliar e comentar reservas                                                                                                                             | [FB28](../elicitacao/brainstorm.md) e [FST09](../elicitacao/storytelling.md)                                                                              |
| RF22 | Deve ser possível filtrar as pesquisas.                                                                                                                                      | [FOBS05](../elicitacao/observacao.md) e [FB30](../elicitacao/brainstorm.md)                                                                               |
| RF23 | Deve ser possível alugar carros.                                                                                                                                             | [FOBS08](../elicitacao/observacao.md)                                                                                                                     |
| RF24 | O aplicativo deve ter mapa interativo.                                                                                                                                       | [FOBS10](../elicitacao/observacao.md) e [FB14](../elicitacao/brainstorm.md)                                                                               |
| RF25 | O aplicativo deve ter uma aba de favoritos.                                                                                                                                  | [FOBS12](../elicitacao/observacao.md) e [FB10](../elicitacao/brainstorm.md)                                                                               |
| RF26 | O aplicativo deve possuir uma central de ajuda ao usuário.                                                                                                                   | [FOBS14](../elicitacao/observacao.md)                                                                                                                     |
| RF27 | O aplicativo deve possuir uma área administrativa da conta.                                                                                                                  | [FOBS15](../elicitacao/observacao.md)                                                                                                                     |
| RF28 | O aplicativo deve apresentar as informações legais sobre o uso para o usuário.                                                                                               | [FOBS20](../elicitacao/observacao.md)                                                                                                                     |
| RF29 | O aplicativo deve permitir que o usuário saia da conta.                                                                                                                      | [FOBS22](../elicitacao/observacao.md)                                                                                                                     |
| RF30 | o aplicativo deve permitir que os usuários pesquisem e reservem carros de aluguel com base em critérios específicos, como localização, datas e tipo de veículo.              | [FST07](../elicitacao/storytelling.md)                                                                                                                    |
| RF31 | Enviar email sobre o status da reserva                                                                                                                                       | [FB08](../elicitacao/brainstorm.md)                                                                                                                       |
| RF32 | O sistema deve possuir uma lista de desejos para aluguel de carro, hospedagem e voos                                                                                         | [FB11](../elicitacao/brainstorm.md)                                                                                                                       |
| RF33 | O sistema deve possuir uma carteira digital                                                                                                                                  | [FB15](../elicitacao/brainstorm.md) e [FOBS16](../elicitacao/observacao.md)                                                                               |
| RF34 | O sistema deve possuir uma moeda própria                                                                                                                                     | [FB18](../elicitacao/brainstorm.md)                                                                                                                       |
| RF35 | O usuário deve poder comprar moedas do sistema                                                                                                                               | [FB19](../elicitacao/brainstorm.md)                                                                                                                       |
| RF36 | O sistema deve oferecer uma opção de conta premium                                                                                                                           | [FB20](../elicitacao/brainstorm.md)                                                                                                                       |
| RF37 | O usuário deve poder selecionar o idioma do sistema                                                                                                                          | [FB21](../elicitacao/brainstorm.md)                                                                                                                       |
| RF38 | O sistema deve notificar sobre ofertas                                                                                                                                       | [FB29](../elicitacao/brainstorm.md) e [FOBS018](../elicitacao/observacao.md)                                                                              |
| RF39 | O usuário deve poder adicionar itens ao aluguel do carro                                                                                                                     | [FB32](../elicitacao/brainstorm.md)                                                                                                                       |
| RF40 | Deve ser possível contratar serviços de táxi.                                                                                                                                | [FOBS09](../elicitacao/observacao.md)                                                                                                                     |
| RF41 | Deve ser possível agendar visitas à atrações turísticas.                                                                                                                     | [FOBS11](../elicitacao/observacao.md)                                                                                                                     |
| RF42 | O aplicativo deve possuir um sistema de configurações do aplicativo.                                                                                                         | [FOBS019](../elicitacao/observacao.md)                                                                                                                    |
| RF43 | O sistema deve exibir dicas sobre os locais e carros                                                                                                                         | [FB16](../elicitacao/brainstorm.md)                                                                                                                       |
| RF44 | O sistema deve mostrar notícias relacionadas ao turismo                                                                                                                      | [FB17](../elicitacao/brainstorm.md)                                                                                                                       |

<div style="text-align: center">
<p> Tabela 4: Requisitos Funcionais (Fonte: Pedro e Henrique, 2023). </p>
</div>

## Requisitos Não Funcionais

A seguir é apresentado na Tabela 5, com a lista dos Requisitos Não Funcionais elicitados.

<center>

| Id    | Requisitos                                                                                                     | Origem                                                                                                                 |
| ----- | -------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| RNF01 | O aplicativo deve ser fácil de usar, com interface intuitiva e navegação clara.                                | [NFST01](../elicitacao/storytelling.md)                                                                                |
| RNF02 | O aplicativo deve ser rápido e responsivo, com tempo de carregamento mínimo e tempos de resposta rápidos.      | [NFST02](../elicitacao/storytelling.md) e [NFOBS01](../elicitacao/observacao.md)                                       |
| RNF03 | O aplicativo deve estar disponível para uso em todos os momentos, com tempos de inatividade mínimos.           | [NFST03](../elicitacao/storytelling.md) e [NFB02](../elicitacao/brainstorm.md)                                         |
| RNF04 | O aplicativo deve ser seguro, protegendo as informações dos usuários e garantindo a privacidade.               | [NFST04](../elicitacao/storytelling.md), [NFOBS03](../elicitacao/observacao.md) e [NFB01](../elicitacao/brainstorm.md) |
| RNF05 | O aplicativo deve ser confiável, com alta disponibilidade e poucas falhas.                                     | [NFST05](../elicitacao/storytelling.md)                                                                                |
| RNF06 | O aplicativo deve ser compatível com uma ampla variedade de dispositivos, navegadores e sistemas operacionais. | [NFST06](../elicitacao/storytelling.md), [NFOBS02](../elicitacao/observacao.md) e [NFB05](../elicitacao/brainstorm.md) |
| RNF07 | O aplicativo deve estar disponível em diferentes idiomas e adaptar-se a diferentes regiões e culturas.         | [NFST07](../elicitacao/storytelling.md)                                                                                |
| RNF08 | Deve possuir acessibilidade.                                                                                   | [NFOBS04](../elicitacao/observacao.md) e [NFB04](../elicitacao/brainstorm.md)                                          |
| RNF09 | O sistema deve ter escalabilidade                                                                              | [NFB06](../elicitacao/brainstorm.md) e [NFOBS05](../elicitacao/observacao.md)                                          |

<div style="text-align: center">
<p> Tabela 5: Requisitos Não Funcionais (Fonte: Pedro e Henrique, 2023). </p>
</div>

</center>

## Elos Funcionais

A seguir é apresentado todos os elos funcionais

### EF01

**Categoria:** Desenvolvimento

**Elementos Rastreáveis:**

* RF01

  * Storytelling: [FST01](../elicitacao/storytelling.md)
  * Observação: [FOBS01](../elicitacao/observacao.md)

**Elos**:

* Agregação: [FST01](../elicitacao/storytelling.md) agrega [FOBS01](../elicitacao/observacao.md)

### EF02

**Categoria:** Desenvolvimento

**Elementos Rastreáveis:**

* RF03

  * Storytelling: [FST03](../elicitacao/storytelling.md)
  * Observação: [FOBS06](../elicitacao/observacao.md)
  * Brainstorm: [FB03](../elicitacao/brainstorm.md)

**Elos**:

* Agregação: [FST03](../elicitacao/storytelling.md) agrega [FOBS06](../elicitacao/observacao.md)
* Agregação: [FST03](../elicitacao/storytelling.md) agrega [FB03](../elicitacao/brainstorm.md)
* Representação: [FB03](../elicitacao/brainstorm.md) representa [FOBS06](../elicitacao/observacao.md)

### EF03

**Categoria:** Desenvolvimento

**Elementos Rastreáveis:**

* RF04

  * Storytelling: [FST04](../elicitacao/storytelling.md)
  * Brainstorm: [FB04](../elicitacao/brainstorm.md)

**Elos**:

* Agregação: [FST04](../elicitacao/storytelling.md) agrega [FB04](../elicitacao/brainstorm.md)

### EF04

**Categoria:** Desenvolvimento

**Elementos Rastreáveis:**

* RF06

  * Storytelling: [FST06](../elicitacao/storytelling.md)
  * Observação: [FOBS07](../elicitacao/observacao.md)

**Elos**:

* Agregação: [FST06](../elicitacao/storytelling.md) agrega [FOBS07](../elicitacao/observacao.md)

### EF05

**Categoria:** Desenvolvimento

**Elementos Rastreáveis:**

* RF08

  * Storytelling: [FST10](../elicitacao/storytelling.md)
  * Observação: [FOBS13](../elicitacao/observacao.md)
  * Brainstorm: [FB05](../elicitacao/brainstorm.md)
  * Brainstorm: [FB06](../elicitacao/brainstorm.md)

**Elos**:

* Agregação: [FST10](../elicitacao/storytelling.md) agrega [FOBS13](../elicitacao/observacao.md)
* Agregação: [FST10](../elicitacao/storytelling.md) agrega [FB05](../elicitacao/brainstorm.md)
* Agregação: [FST10](../elicitacao/storytelling.md) agrega [FB06](../elicitacao/brainstorm.md)
* Representação: [FOBS13](../elicitacao/observacao.md) representa [FB05](../elicitacao/brainstorm.md)
* Agregação: [FOBS13](../elicitacao/observacao.md) agrega [FB06](../elicitacao/brainstorm.md)
* Agregação: Brainstorm: [FB06](../elicitacao/brainstorm.md) agrega [FB05](../elicitacao/brainstorm.md)

### EF06

**Categoria:** Desenvolvimento

**Elementos Rastreáveis:**

* RF15

  * Brainstorm: [FB23](../elicitacao/brainstorm.md)
  * Observação: [FOBS04](../elicitacao/observacao.md)

**Elos**:

* Agregação: [FB23](../elicitacao/brainstorm.md) agrega [FOBS04](../elicitacao/observacao.md)

### EF07

**Categoria:** Desenvolvimento

**Elementos Rastreáveis:**

* RF18

  * Brainstorm: [FB26](../elicitacao/brainstorm.md)
  * Observação: [FOBS03](../elicitacao/observacao.md)

**Elos**:

* Representação: [FB26](../elicitacao/brainstorm.md) representa [FOBS03](../elicitacao/observacao.md)

### EF08

**Categoria:** Desenvolvimento

**Elementos Rastreáveis:**

* RF21

  * Brainstorm: [FB28](../elicitacao/brainstorm.md)
  * Storytelling: [FST09](../elicitacao/storytelling.md)

**Elos**:

* Agregação: [FST09](../elicitacao/storytelling.md) agrega [FB28](../elicitacao/brainstorm.md)

### EF09

**Categoria:** Desenvolvimento

**Elementos Rastreáveis:**

* RF22

  * Observação: [FOBS05](../elicitacao/observacao.md)
  * Brainstrom: [FB30](../elicitacao/brainstorm.md)

**Elos**:

* Agregação: [FB30](../elicitacao/brainstorm.md) agrega [FOBS05](../elicitacao/observacao.md)

### EF10

**Categoria:** Desenvolvimento

**Elementos Rastreáveis:**

* RF24

  * Observação: [FOBS10](../elicitacao/observacao.md)
  * Brainstorm: [FB14](../elicitacao/brainstorm.md)

**Elos**:

* Representação: [FOBS10](../elicitacao/observacao.md) representa [FB14](../elicitacao/brainstorm.md)

### EF11

**Categoria:** Desenvolvimento

**Elementos Rastreáveis:**

* RF25

  * Observação: [FOBS12](../elicitacao/observacao.md)
  * Brainstorm: [FB10](../elicitacao/brainstorm.md)

**Elos**:

* Representação: [FB10](../elicitacao/brainstorm.md) representa [FOBS12](../elicitacao/observacao.md)

### EF12

**Categoria:** Desenvolvimento

**Elementos Rastreáveis:**

* RF33

  * Observação: [FOBS16](../elicitacao/observacao.md)
  * Brainstorm: [FB15](../elicitacao/brainstorm.md)

**Elos**:

* Representação: [FOBS16](../elicitacao/observacao.md) representa [FB15](../elicitacao/brainstorm.md)

### EF13

**Categoria:** Desenvolvimento

**Elementos Rastreáveis:**

* RF38

  * Observação: [FOBS18](../elicitacao/observacao.md)
  * Brainstorm: [FB29](../elicitacao/brainstorm.md)

**Elos**:

* Agregação: [FB29](../elicitacao/brainstorm.md) agrega [FOBS18](../elicitacao/observacao.md)

## Elos Não Funcionais

A seguir é apresentado os elos não funcionais.

### ENF01

**Categoria:** Desenvolvimento

**Elementos Rastreáveis:**

* RNF02

  * Storytelling: [NFST02](../elicitacao/storytelling.md)
  * Observação: [NFOBS01](../elicitacao/observacao.md)

**Elos**:

* Agregação: [NFST02](../elicitacao/storytelling.md) agrega [NFOBS01](../elicitacao/observacao.md)

### ENF02

**Categoria:** Desenvolvimento

**Elementos Rastreáveis:**

* RNF03

  * Storytelling: [NFST03](../elicitacao/storytelling.md)
  * Brainstorm: [NFB02](../elicitacao/brainstorm.md)

**Elos**:

* Agregação: [NFB02](../elicitacao/brainstorm.md) agrega [NFST03](../elicitacao/storytelling.md)

### ENF03

**Categoria:** Desenvolvimento

**Elementos Rastreáveis:**

* RNF04

  * Storytelling: [NFST04](../elicitacao/storytelling.md)
  * Brainstorm: [NFB01](../elicitacao/brainstorm.md)
  * Observação: [NFOBS03](../elicitacao/observacao.md)

**Elos**:

* Agregação: [NFOBS03](../elicitacao/observacao.md) agrega [NFST04](../elicitacao/storytelling.md)
* Agregação: [NFST04](../elicitacao/storytelling.md) agrega [NFST04](../elicitacao/storytelling.md)
* Representação: [NFB01](../elicitacao/brainstorm.md) representa [NFOBS03](../elicitacao/observacao.md)

### ENF04

**Categoria:** Desenvolvimento

**Elementos Rastreáveis:**

* RNF06

  * Storytelling: [NFST06](../elicitacao/storytelling.md)
  * Brainstorm: [NFB05](../elicitacao/brainstorm.md)
  * Observação: [NFOBS02](../elicitacao/observacao.md)

**Elos**:

* Agregação: [NFST06](../elicitacao/storytelling.md) agrega [NFOBS02](../elicitacao/observacao.md)
* Agregação: [NFST06](../elicitacao/storytelling.md) agrega [NFB05](../elicitacao/brainstorm.md)
* Representação: [NFB05](../elicitacao/brainstorm.md) representa [NFOBS02](../elicitacao/observacao.md)

### ENF05

**Categoria:** Desenvolvimento

**Elementos Rastreáveis:**

* RNF08

  * Brainstorm: [NFB04](../elicitacao/brainstorm.md)
  * Observação: [NFOBS04](../elicitacao/observacao.md)

**Elos**:

* Agregação: [NFB04](../elicitacao/brainstorm.md) agrega [NFOBS04](../elicitacao/observacao.md)

### ENF06

**Categoria:** Desenvolvimento

**Elementos Rastreáveis:**

* RNF09

  * Brainstorm: [NFB06](../elicitacao/brainstorm.md)
  * Observação: [NFOBS05](../elicitacao/observacao.md)

**Elos**:

* Agregação: [NFOBS05](../elicitacao/observacao.md) agrega [NFB06](../elicitacao/brainstorm.md)

## Bibliografia

SERRANO, Milene; SERRANO, Maurício. Requisitos (Aula 26): Elicitação, Modelagem e Análise. 2022. Apresentação de Power Point. 44 slides. color. Disponível no [link](https://aprender3.unb.br/pluginfile.php/1668237/mod_resource/content/1/Requisitos%20-%20Aula%20026.pdf). Acesso em: 27 jun. 2023.

SAYÃO Miriam, LEITE Julio. Rastreabilidade de Requisitos. 2005, PUC-RJ.

Backward-from - Grasshopper. Github.io. Disponível em: [https://requisitos-de-software.github.io/2022.2-Grasshopper/pos-rastreabilidade/backward-from/](https://requisitos-de-software.github.io/2022.2-Grasshopper/pos-rastreabilidade/backward-from/). Acesso em: 28 jun. 2023.

## Histórico de Versão

| Versão | Data       | Descrição                       | Autor(es)        | Revisor(es)    |
| ------ | ---------- | ------------------------------- | ---------------- | -------------- |
| 1.0    | 28/06/2023 | Criação do artefato             | Pedro e Henrique | Lucas e Samuel |
| 1.1    | 28/06/2023 | adicionando elos não funcionais | Pedro e Henrique | Lucas e Samuel |
