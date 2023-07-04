# Léxicos

## Introdução

O léxico desempenha um papel fundamental na compreensão precisa das necessidades e funcionalidades de um sistema, pois é usado para descrever os símbolos de uma linguagem. O objetivo dos engenheiros de requisitos é identificar frases e símbolos do domínio da aplicação, criando um vocabulário anotado com conceitos importantes para estabelecer uma linguagem comum. Isso melhora a comunicação entre o usuário e o analista, evitando requisitos mal formulados ou incompletos. Essa abordagem garante um entendimento compartilhado sobre os termos e conceitos essenciais relacionados ao software em questão. Os léxicos podem ser classificados em três tipos: Estado, Verbo e Objeto. O Estado envolve palavras que indicam um estado ou condição. O Verbo representa palavras que expressam ação ou processo. No texto fornecido, exemplos de Verbos são "desempenha", "buscar" e "procurando". O Objeto se refere às palavras que recebem a ação do verbo ou são afetadas por ele. No texto dado, exemplos de Objetos podem incluir "papel" e "necessidades".

## Metodologia

A partir da identificação e priorização dos requisitos, juntamente com o uso do aplicativo Booking, foram elicitados léxicos que podem ser observados nas Tabelas 2 a 17. Na descrição desses léxicos, adotaremos o princípio do vocabulário mínimo, buscando uma descrição clara e concisa. Além disso, seguiremos o princípio circular, incentivando a referência a outros léxicos na descrição.

O modelo a ser seguido na apresentação dos léxicos será exemplificado na Tabela 1.

<center style="max-width: 500px; margin: auto; align-items: center;">

| **LXX**             | _Nome do Léxico._                                     |
| :------------------------ | :------------------------------------------------------- |
| **Autor**           | _Autor do Léxico_                                     |
| **Classificação** | _Classificação do léxico (estado, objeto ou verbo)_ |
| **Sinônimos**      | _Sinônimos do léxico no contexto_                    |
| **Noção**         | _Noções do léxico_                                  |
| **Impacto**         | _Impacto do léxico na aplicação_                    |
| **Rastro**          | XX00                                                     |

<div style="text-align: center">
    <p> Tabela 1: Exemplificação dos léxicos. (Fonte: Autores. 2023).</p>
</div>

</center>

## Léxicos

<center style="max-width: 500px; margin: auto; align-items: center;">

### L01 - Acessar

| **L03**             | Acessar                                                                      |
| :------------------------ | :--------------------------------------------------------------------------- |
| **Autor**           | Pedro Henrique                                                               |
| **Classificação** | Verbo                                                                        |
| **Sinônimos**      | Entrar, ingressar                                                            |
| **Noção**         | *O [usuário](#usuario) acessa o Booking ou suas funcionalidades*             |
| **Impacto**         | *Os [usuários](#usuario) podem ter acesso a qualquer função do aplicativo* |
| **Rastro**          | [OBS05](../elicitacao/brainstorm.md)                                            |

<div style="text-align: center">
    <p> Tabela 2: Léxico 01. (Fonte: Autores. 2023).</p>
</div>

### L02 - Agendamento de voos

| L02                       | Agendamento de voos                                                                                                                                                                                                                                                                                                           |
| ------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Ator**            | Samuel Gomes                                                                                                                                                                                                                                                                                                                  |
| **Classificação** | Objeto                                                                                                                                                                                                                                                                                                                        |
| **Sinônimos**      | Reserva de voos, marcação de passagens aéreas, agendamento de viagens aéreas                                                                                                                                                                                                                                              |
| **Noção**         | Opção de agendamento de voos no aplicativo, onde os [usuários](#usuario) podem encontrar e [reservar](#reservar) passagens aéreas para diferentes destinos e datas.                                                                                                                                                              |
| **Impacto**         | O agendamento de voos é uma das principais opções de viagem para muitos [usuário](#usuario) e sua inclusão no aplicativo pode torná-lo mais completo e útil para seus [usuários](#usuario). Além disso, pode aumentar o número de reservas de outros serviços relacionados, como aluguel de carros e reservas de hotéis. |
| **Rastro**          | [FOBS07](../elicitacao/observacao.md)                                                                                                                                                                                                                                                                                            |

<div style="text-align: center">
    <p> Tabela 3: Léxico 02. (Fonte: Autores. 2023).</p>
</div>

### L03 - Favoritos

| **L03**             | _Favoritos_                                                                                                                          |
| :------------------------ | :------------------------------------------------------------------------------------------------------------------------------------- |
| **Autor**           | Pedro Henrique                                                                                                                         |
| **Classificação** | Estado                                                                                                                                 |
| **Sinônimos**      | _Preferido, querido, estimado_                                                                                                       |
| **Noção**         | Classificação dos melhores lugares feita pelo usuario.                                                                               |
| **Impacto**         | _Os [usuários](#usuario) têm acesso rápido aos melhores lugares (hoteis,  pousadas e etc) que o mesmo classificou como favorito._ |
| **Rastro**          | [OBS010](../elicitacao/brainstorm.md)                                                                                                     |

<div style="text-align: center">
    <p> Tabela 4: Léxico 03. (Fonte: Autores. 2023).</p>
</div>

### L04 - Dicas

| **L04**             | Dicas                                                                                                                                                            |
| :------------------------ | :--------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Autor**           | Pedro Henrique                                                                                                                                                   |
| **Classificação** | _Objeto_                                                                                                                                                       |
| **Sinônimos**      | _Indicação, orientação, conselho_                                                                                                                          |
| **Noção**         | São informações diversas para o [usuário](#usuario), desde como usar o aplicativo até a quais lugares são recomendados para visitar e realizar uma hospedagem. |
| **Impacto**         | O [usuário](#usuario) é informado sobre funcionalidades do aplicativo e sobre lugares novos para poder visitar.                                                    |
| **Rastro**          | [OBS016](../elicitacao/brainstorm.md)                                                                                                                               |

<div style="text-align: center">
    <p> Tabela 5: Léxico 04. (Fonte: Autores. 2023).</p>
</div>

### L05 - Premium

| **L05**             | Premium                                                                                                                         |
| :------------------------ | :------------------------------------------------------------------------------------------------------------------------------ |
| **Autor**           | Pedro Henrique                                                                                                                  |
| **Classificação** | Estado                                                                                                                          |
| **Sinônimos**      | _Diferenciado, Especial_                                                                                                      |
| **Noção**         | É uma condição que o [usuário](#usuario) pode comprar para ter acesso a funcionalidade exclusivas ou prioridade no aplicativo  |
| **Impacto**         | _Os [usuários](#usuario) que são especiais podem ter acesso a funcionalidade exclusivas ou prioridade em relação aos demais_ |
| **Rastro**          | [OBS020](../elicitacao/brainstorm.md)                                                                                              |

<div style="text-align: center">
    <p> Tabela 6: Léxico 05. (Fonte: Autores. 2023).</p>
</div>

### L06 - Idioma

| **L06**             | Idioma                                                                                  |
| :------------------------ | :-------------------------------------------------------------------------------------- |
| **Autor**           | Pedro Henrique                                                                          |
| **Classificação** | _Objeto_                                                                              |
| **Sinônimos**      | _Língua, dialeto, linguagem_                                                         |
| **Noção**         | Opção para mudar a linguagem do aplicativo                                            |
| **Impacto**         | _O aplicativo se torna acessivel aos [usuários](#usuario) que falam diferentes idiomas_ |
| **Rastro**          | [OBS021](../elicitacao/brainstorm.md)                                                      |

<div style="text-align: center">
    <p> Tabela 7: Léxico 06. (Fonte: Autores. 2023).</p>
</div>

### L07 - Pontuação

| **L07**             | Pontuação                                                                                         |
| :------------------------ | :-------------------------------------------------------------------------------------------------- |
| **Autor**           | Pedro Henrique                                                                                      |
| **Classificação** | _Objeto_                                                                                          |
| **Sinônimos**      | Placar, contagem, escore                                                                            |
| **Noção**         | São números acumulativos fornecidos ao [usuário](#usuario)                                           |
| **Impacto**         | _Os [usuários](#usuario) podem acumular pontos para trocar por descontos em reservas no aplicativo_ |
| **Rastro**          | [OBS026](../elicitacao/brainstorm.md)                                                                  |

<div style="text-align: center">
    <p> Tabela 8: Léxico 07. (Fonte: Autores. 2023).</p>
</div>

### L08 - Avaliar

| **L08**             | Avaliar                                                                                  |
| :------------------------ | :--------------------------------------------------------------------------------------- |
| **Autor**           | Pedro Henrique                                                                           |
| **Classificação** | Verbo                                                                                    |
| **Sinônimos**      | Julgar, criticar                                                                         |
| **Noção**         | Campo destinado para o [usuário](#usuario) avaliar o sua experiência com a hospedagem.    |
| **Impacto**         | _Os [usuários](#usuario) tem acesso a opinião de outros usuarios sobre o a hospedagem._ |
| **Rastro**          | [OBS28](../elicitacao/brainstorm.md)                                                        |

<div style="text-align: center">
    <p> Tabela 9: Léxico 08. (Fonte: Autores. 2023).</p>
</div>

</center>

<center style="max-width: 500px; margin: auto; align-items: center;">

### L09 - Busca

| L09                       | Busca                                                                                                                                                                                             |
| ------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Autor**           | Samuel Gomes                                                                                                                                                                                      |
| **Classificação** | Verbo                                                                                                                                                                                             |
| **Sinônimos**      | Procurar, pesquisar, investigar                                                                                                                                                                   |
| **Noção**         | Ação de buscar por acomodações ou atividades disponíveis no aplicativo.                                                                                                                      |
| **Impacto**         | A busca é a primeira etapa para que o [usuário](#usuario) possa encontrar e [reservar](#reservar) acomodações ou atividades de interesse, portanto, é fundamental para a usabilidade do aplicativo. |
| **Rastro**          | [FOBS02](../elicitacao/observacao.md)                                                                                                                                                                |

<div style="text-align: center">
    <p> Tabela 10: Léxico 09. (Fonte: Autores. 2023).</p>
</div>

### L10 - Cancelamento

| L10                       | Cancelamento                                                                                                                                                                   |
| ------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| **Autor**           | Samuel Gomes                                                                                                                                                                   |
| **Classificação** | Verbo                                                                                                                                                                          |
| **Sinônimos**      | Desmarcar, anular, rescindir                                                                                                                                                   |
| **Noção**         | Ação de cancelar uma reserva previamente feita.                                                                                                                              |
| **Impacto**         | O cancelamento pode ter impacto financeiro na plataforma e também afetar a experiência do [usuário](#usuario), sendo importante que o processo seja claro e fácil de realizar. |
| **Rastro**          | [FB04](../elicitacao/brainstorm.md)                                                                                                                                               |

<div style="text-align: center">
    <p> Tabela 11: Léxico 10. (Fonte: Autores. 2023).</p>
</div>

### L11 - Pagamento

| L11                       | Pagamento                                                                                                                                                          |
| ------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| **Ator**            | Samuel Gomes                                                                                                                                                       |
| **Classificação** | Verbo                                                                                                                                                              |
| **Sinônimos**      | Quitar, pagar, liquidar                                                                                                                                            |
| **Noção**         | Ação de realizar o pagamento pela acomodação ou atividade reservada.                                                                                           |
| **Impacto**         | O pagamento é uma etapa importante da reserva e deve ser seguro e fácil para o [usuário](#usuario), a fim de evitar problemas e garantir a satisfação do cliente. |
| **Rastro**          | [FB02](../elicitacao/brainstorm.md)                                                                                                                                   |

<div style="text-align: center">
    <p> Tabela 12: Léxico 11. (Fonte: Autores. 2023).</p>
</div>

### L12 - Mapa

| L12                       | Mapa                                                                                                                                                                                |
| ------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Ator**            | Samuel Gomes                                                                                                                                                                        |
| **Classificação** | Objeto                                                                                                                                                                              |
| **Sinônimos**      | Localizador, guia, roteiro                                                                                                                                                          |
| **Noção**         | Ferramenta de visualização das acomodações, atividades e atrações disponíveis em determinada região.                                                                        |
| **Impacto**         | O mapa é importante para ajudar os [usuários](#usuario) a localizarem as opções disponíveis e também para oferecer uma visão geral da oferta disponível em determinada região. |
| **Rastro**          | [FOBS010](../elicitacao/observacao.md)                                                                                                                                                 |

<div style="text-align: center">
    <p> Tabela 13: Léxico 12. (Fonte: Autores. 2023).</p>
</div>

### L13 - Ajuda

| L13                       | Ajuda                                                                                                                                                                               |
| ------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Ator**            | Samuel Gomes                                                                                                                                                                        |
| **Classificação** | Objeto                                                                                                                                                                              |
| **Sinônimos**      | Suporte, assistência, orientação                                                                                                                                                 |
| **Noção**         | Seção de ajuda no aplicativo, onde os [usuários](#usuario) podem encontrar respostas para suas dúvidas e soluções para problemas técnicos.                                     |
| **Impacto**         | A seção de ajuda é fundamental para garantir que os [usuários](#usuario) possam utilizar o aplicativo de forma eficiente e também para reduzir a sobrecarga de suporte ao cliente. |
| **Rastro**          | [FOBS014](../elicitacao/observacao.md)                                                                                                                                                 |

<div style="text-align: center">
    <p> Tabela 14: Léxico 13. (Fonte: Autores. 2023).</p>
</div>

### L14 - Aluguel de carros

| L14                       | Aluguel de carros                                                                                                                                                                                                 |
| ------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Ator**            | Samuel Gomes                                                                                                                                                                                                      |
| **Classificação** | Objeto                                                                                                                                                                                                            |
| **Sinônimos**      | Locação de veículos                                                                                                                                                                                            |
| **Noção**         | Opção de aluguel de carros no aplicativo, onde os [usuários](#usuario) podem encontrar e [reservar](#reservar) veículos disponíveis em diferentes locais e datas.                                                 |
| **Impacto**         | O aluguel de carros é uma opção importante para muitos [usuários](#usuario) que precisam se deslocar durante suas viagens e sua inclusão no aplicativo pode aumentar a atratividade e a utilidade da plataforma. |
| **Rastro**          | [FOBS08](../elicitacao/observacao.md)                                                                                                                                                                                |

<div style="text-align: center">
    <p> Tabela 15: Léxico 14. (Fonte: Autores. 2023).</p>
</div>

### <p id="reservar"> L15 - Reservar </p>

| **L24**             | Reservar                                                                                                          |
| :------------------------ | :---------------------------------------------------------------------------------------------------------------- |
| **Autor**           | Pedro Henrique                                                                                                    |
| **Classificação** | _Verbo_                                                                                                         |
| **Sinônimos**      | Agendar, marcar, solicitar                                                                                        |
| **Noção**         | _O [usuário](#usuario) reserva um hotel, pousada ou qualquer local disponivel no aplicativo para se estabelecer._ |
| **Impacto**         | _Os [usuários](#usuario) pode escolher qualquer lugar disponivel para se estabelecer quando for viajar._          |
| **Rastro**          | [OBS03](../elicitacao/brainstorm.md)                                                                                 |

<div style="text-align: center">
    <p> Tabela 16: Léxico 15. (Fonte: Autores. 2023).</p>
</div>

### L16 - Status

| **L25**             | Status                                                                                       |
| :------------------------ | :------------------------------------------------------------------------------------------- |
| **Autor**           | Pedro Henrique                                                                               |
| **Classificação** | Estado                                                                                       |
| **Sinônimos**      | _Estado, situação, condição_                                                           |
| **Noção**         | É uma informação a respeito da situação da reserva feita pelo [usuário](#usuario)        |
| **Impacto**         | _Os [usuários](#usuario) são informados da situação de suas reservas feitas pelo Booking_ |
| **Rastro**          | [OBS08](../elicitacao/brainstorm.md)                                                            |

<div style="text-align: center">
    <p> Tabela 17: Léxico 16. (Fonte: Autores. 2023).</p>
</div>

### <p id="usuario"> L17 - Usuário </p>

| **L26**             | _Usuário_                                                                 |
| :------------------------ | :--------------------------------------------------------------------------- |
| **Autor**           | Pedro Henrique                                                               |
| **Classificação** | _Objeto_                                                                   |
| **Sinônimos**      | _Consumidor, utilizador, cliente_                                          |
| **Noção**         | São pessoas que utilizam o Booking                                          |
| **Impacto**         | _Os [usuários](#usuario) têm acesso a todas as funcionalidades do Booking_ |
| **Rastro**          | [OBS01](../elicitacao/brainstorm.md)                                            |

<div style="text-align: center">
    <p> Tabela 18: Léxico 17. (Fonte: Autores. 2023).</p>
</div>

</center>

<center style="max-width: 500px; margin: auto; align-items: center;">

</center>

## Conclusão

Foi apresentado os lexicos que descrevem os principais símbolos e conceitos relacionados ao aplicativo booking. Esses lexicos servem para facilitar a comunicação entre os envolvidos no projeto e para documentar as características e funcionalidades do software. Cada lexico possui uma noção, que explica o que ele significa no domínio da aplicação, um impacto, que indica como ele afeta ou é afetado pela aplicação, um sinônimo, que é outra forma de se referir ao mesmo símbolo, uma classificação, que indica se ele é um objeto, um verbo ou um estado, e um rastro, que mostra a origem do lexico.

## Bibliografia

Léxicos - MEI. Disponível em: [https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/Lexicos/](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/Lexicos/). Acesso em: 14 maio. 2023.

Requisitos Aula 10 - Serrano Milene, Serrano Maurício. Disponível em: [https://aprender3.unb.br/pluginfile.php/2523091/mod_resource/content/1/Aula%2010.pdf](https://aprender3.unb.br/pluginfile.php/2523091/mod_resource/content/1/Aula%2010.pdf). Acesso em: 14 maio. 2023.

## Histórico de versão

| Versão |    Data    |      Descrição      |     Autor     | Revisor |
| :-----: | :--------: | :--------------------: | :------------: | :-----: |
|   1.0   | 14/05/2023 | Criação do documento | Pedro e Samuel |  Lucas  |
