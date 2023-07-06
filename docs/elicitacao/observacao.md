## Introdução

Por meio do uso de métodos de observação, o avaliador é capaz de coletar informações sobre as situações em que os participantes realizam suas atividades, tanto com quanto sem o auxílio da tecnologia computacional. Ao registrar e analisar esses dados, é possível identificar os desafios reais enfrentados pelos participantes, em contraste com problemas hipotéticos previstos apenas pelo avaliador durante uma avaliação por inspeção.

No âmbito dos métodos de avaliação por observação, Simone (2010) destaca três abordagens principais: teste de usabilidade, método de avaliação de comunicabilidade e prototipação em papel. Neste caso, optaremos pelo método de avaliação de comunicabilidade para este artefato específico. Os detalhes da execução desse método serão explicados na seção "Metodologia".

## Metodologia

Após um processo de convite e esclarecimento dos direitos, Yan Werlley, um representante dos usuários, realizou um conjunto de tarefas no aplicativo Booking em um ambiente controlado. As experiências do usuário foram minuciosamente observadas e registradas em formato de vídeo, disponível na seção "Vídeo da reunião"". Durante o encontro, os avaliadores Pedro Henrique Rodrigues de Carvalho e Chaydson Ferreira da Aparecida registraram as interações do usuário com o sistema em avaliação, com o objetivo de compreender a experiência do convidado. O cronograma detalhado da reunião pode ser encontrado no tópico "Cronograma".

### Cronograma

| Local | Dia        | Horário | Entrevistadores                    | Entrevistado |
| ----- | ---------- | -------- | ---------------------------------- | ------------ |
| TEAMS | 30/04/2023 | 14:00    | Pedro Henrique e Chaydson Ferreira | Yan Werlley  |

<div style="text-align: center">
<p> Tabela 1: Cronograma planejado para entrevista com usuário do aplicativo (Fonte: Autores, 2023). </p>
</div>

## Papel dos participantes

Durante a reunião, Pedro Henrique Rodrigues e Chaydson Ferreira desempenharam o papel de observadores, enquanto Yan Werlly (o convidado) utilizava as funcionalidades do aplicativo com as quais estava mais familiarizado. Enquanto isso, os observadores faziam anotações para posteriormente levantar os requisitos necessários.

## Preparação do material para observar e Registrar o uso

Antes do processo de observação e registro do uso do aplicativo Booking, foi realizado preparo do material necessário para garantir uma experiência adequada aos participantes da reunião. Foram utilizados os seguintes recursos:

- Computador desktop para cada participante: Cada participante teve acesso a um computador desktop para proporcionando um ambiente de trabalho individualizado e confortável para a realização das tarefas no aplicativo.
- Fones de ouvido com microfone: Foram utilizados três conjuntos de fones de ouvido com microfone, permitindo que os participantes pudessem se comunicar facilmente durante a reunião e garantindo uma captação clara e nítida do áudio.
- Cabo USB para conexão de dispositivo Android: Com o objetivo de espelhar a tela de dispositivos Android no computador, foi utilizado um cabo USB adequado para conectar os dispositivos móveis ao computador. Essa conexão permitiu que o convidado compartilhasse suas interações e demonstrassem o uso do aplicativo Booking. Para essa finalidade, utilizou-se o software SCRCPY, que possibilita o espelhamento da tela do dispositivo Android no computador.
- Utilização do Teams: A reunião foi conduzida na plataforma Teams, que oferece suporte para a gravação de reuniões. Esse recurso foi fundamental para registrar todas as interações do participante, permitindo uma análise mais detalhada posteriormente.

## Resultados

Utilizando a técnica de Observação, foram elicitados os requisitos funcionais na Tabela 2 e requisitos não funcionais na Tabela 3.

### Requisitos Funcionais

A Tabela 2 a seguir contém os Requisitos funcionais elicitados através da Observação.

| Id      | Requisitos                                                                        |
| ------- | --------------------------------------------------------------------------------- |
| FOBS01  | Deve ser possível criar uma conta com o google, facebook ou email pessoal.       |
| FOBS02  | Deve ser possível realizar pesquisas.                                            |
| FOBS03  | Deve possuir um sistema de fidelidade.                                            |
| FOBS04  | Deve possuir um sistema de informações e recomendações.                       |
| FOBS05  | Deve ser possível filtrar as pesquisas.                                          |
| FOBS06  | Deve ser possível agendar hospedagem.                                            |
| FOBS07  | Deve ser possível agendar voos.                                                  |
| FOBS08  | Deve ser possível alugar carros.                                                 |
| FOBS09  | Deve ser possível contratar serviços de táxi.                                  |
| FOBS010 | O aplicativo deve ter mapa interativo.                                            |
| FOBS011 | Deve ser possível agendar visitas à atrações turísticas.                     |
| FOBS012 | O aplicativo deve ter uma aba de favoritos.                                       |
| FOBS013 | O aplicativo deve possuir um histórico de reservas.                              |
| FOBS014 | O aplicativo deve possuir uma central de ajuda ao usuário.                       |
| FOBS015 | O aplicativo deve possuir uma área administrativa da conta.                      |
| FOBS016 | O aplicativo deve possuir sistema de carteira virtual.                            |
| FOBS017 | Deve ser possível entrar em contato com o responsável pelo serviço.            |
| FOBS018 | O aplicativo deve possuir um sistema de ofertas.                                  |
| FOBS019 | O aplicativo deve possuir um sistema de configurações do aplicativo.            |
| FOBS020 | O aplicativo deve apresentar as informações legais sobre o uso para o usuário. |
| FOBS021 | O aplicativo deve permitir que o usuário cadastre uma propriedade.               |
| FOBS022 | O aplicativo deve permitir que o usuário saia da conta.                          |
| FOBS023 | Deve ser possivel comprar um pacote de viagens(hospedagens, voos e etc).          |

<div style="text-align: center">
<p> Tabela 2: Requisitos Funcionais utilizando a técnica Observação (Fonte: Autor, 2023). </p>
</div>

### Requisitos Não Funcionais

A Tabela 3 a seguir contém os Requisitos não funcionais elicitados através da Observação.

| Id      | Requisitos                                                            |
| ------- | --------------------------------------------------------------------- |
| NFOBS01 | A inteface deve ser responsiva.                                       |
| NFOBS02 | O sistema deve rodar nas principais plataformas mobile Android e iOS. |
| NFOBS03 | O sistema deve ser seguro.                                            |
| NFOBS04 | Deve possuir acessibilidade.                                          |
| NFOBS05 | Deve ser escalável.                                                  |

<div style="text-align: center">
<p> Tabela 3: Requisitos não Funcionais utilizando a técnica Observação (Fonte: Autor, 2023). </p>
</div>

### Legendas

A seguir na tabela 4, as legendas das tabelas de requisitos

<center>

| ID    | descrição                              |
| ----- | ---------------------------------------- |
| FOBS  | Requisito funcional da Observação      |
| NFOBS | Requisito não funcional da Observação |

<div style="text-align: center">
<p> Tabela 4: Legenda das tabelas de requisitos. (Fonte: Pedro e Chaydson, 2023). </p>
</div>

</center>

## Video da reunião

A seguir, disponibilizamos o vídeo 1, que apresenta a gravação da reunião na íntegra.

<center>

<iframe width="560" height="315" src="https://www.youtube.com/embed/UBXR9S4XcyQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

<div style="text-align: center">
<p> Video 1: Reunião da execução da Observação. (Fonte: Pedro e Chaydson, 2023). </p>
</div>

</center>

## Termo de consentimento

No link a seguir, está disponível o termo de consentimento assinado tanto pelos observadores quanto pelo usuário, com todas as cláusulas e informações necessárias para garantir a transparência e proteção dos envolvidos durante o processo de observação. É importante ressaltar a importância desse documento para assegurar o cumprimento de direitos e estabelecer um ambiente de confiança mútua.

[Termo de consentimento](../assets/pdfs/termo%20de%20consentimento%20observacaoAssinado.pdf)

## Bibliografia

Observação - Grasshopper. Disponível em: [https://requisitos-de-software.github.io/2022.2-Grasshopper/elicitacao/observacao/](https://requisitos-de-software.github.io/2022.2-Grasshopper/elicitacao/observacao/). Acesso em: 23 abr. 2023.

Barbosa, S. D. J.; Silva, B. S. da; Silveira, M. S.; Gasparini, I.; Darin, T.; Barbosa, G. D. J. (2021) Interação Humano-Computador e Experiência do usuário. Autopublicação. ISBN: 978-65-00-19677-1.

## Histórico de versão

| Versão | Data       | Descrição                                        | Autor(es)                | Revisor(es) |
| ------- | ---------- | -------------------------------------------------- | ------------------------ | ----------- |
| 1.0     | 23/04/2023 | Criação da página de Observação               | Pedro Henrique, Chaydson | Samuel      |
| 1.1     | 30/04/2023 | Refazendo os requisitos com o usuário             | Pedro Henrique, Chaydson | Samuel      |
| 1.2     | 21/06/2023 | Aplicando correções apontadas pela verificação | Pedro Henrique, Chaydson | Samuel      |
| 1.3     | 04/07/2023 | Aplicando correções com base no livro da Simone  | Pedro Henrique, Chaydson | Samuel      |
