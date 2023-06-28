# Especificação Suplementar

## Introdução

A especificação suplementar tem como objetivo definir requisitos adicionais que não são abordados pela especificação principal. Esses requisitos complementam os aspectos de desempenho, segurança, usabilidade e outras características de qualidade do sistema. Através da especificação suplementar, são estabelecidas restrições, metas de desempenho, requisitos de segurança e usabilidade. Essa documentação detalhada garante que todos os requisitos não funcionais sejam adequadamente identificados e atendidos.

Sendo assim, nesse documento contemplará a especificação suplementar do Booking, definindo seus requisitos não funcionais por meio da metodologia FURPS+.

## Metodologia

O FURPS+ é um sistema de classificação de requisitos que utiliza um acrônimo para representar diferentes categorias e atributos de Qualidade de Software. Essas categorias e atributos são amplamente utilizados na definição de requisitos.

No nosso projeto, cada categoria do acrônimo - Funcionalidade, Usabilidade, Confiabilidade, Desempenho, Suportabilidade e outros atributos adicionais - foi cuidadosamente considerada e avaliada durante o processo de definição de requisitos. Isso permitiu que a equipe identificasse os aspectos principais do sistema.

- F - Funcionalidade: engloba todos os aspectos funcionais do software, ou seja, quais ações o usuário vai poder realizar no sistema.
- U - Usabilidade: facilidade com que um sistema, produto ou interface pode ser usado por seus usuários para atingir seus objetivos de forma eficaz, eficiente e satisfatória.
- R - Confiabilidade: diz respeito à integridade, conformidade e interoperabilidade do software. Os requisitos nessa categoria podem incluir a frequência e a gravidade de falhas, o tempo médio entre falhas, a possibilidade de recuperação, etc.
- P - Performance: avalia os requisitos de desempenho do software, podendo usar como medida vários aspectos, como tempo de resposta, consumo de recursos, disponibilidade da aplicação, etc.
- S - Suportabilidade: os requisitos de suportabilidade agrupam várias características, como testabilidade, adaptabilidade, manutenibilidade, compatibilidade, escalabilidade, localizabilidade, etc.
- "+": este símbolo do acrônimo abrange outros requisitos não funcionais que devem ser lembrados, como por exemplo:
- Requisitos de design: frequentemente chamado de restrição de design; um exemplo seria o uso de ferramentas específicas de desenvolvimento.
- Requisitos de implementação: um requisito de implementação especifica ou restringe o código ou a construção de um sistema; por exemplo, padrões obrigatórios ou linguagens de implementação.
- Requisitos de interface: especifica ou restringe as funcionalidades inerentes à interface do sistema com o usuário.
- Requisitos físicos: especifica uma limitação física pelo hardware utilizado, por exemplo: material, forma, tamanho ou peso.

## Especificação Suplementar

### 1. Funcionalidades

As funcionalidades já foram definidas nos outros documentos de modelagem.

### 2. Usabilidade

Na Tabela 1 estão registrados os requisitos de usabilidade

| ID    | Descrição                                                                                                                        |
|-------|----------------------------------------------------------------------------------------------------------------------------------|
| USAB01 | o sistema deve ser intuitivo.                                                                                                    |
| USAB02 | o sistema deve ser facilmente aprendido pelo usuário.                                                                            |
| USAB03 | o sistema deve deve dar feedbacks ao usuário sobre o que está acontecendo enquanto ele está realizando ações no software.        |
| USAB04 | as tarefas devem ser realizadas rapidamente e com poucos cliques e etapas.                                                       |
| USAB05 | o software proporciona uma experiência agradável, intuitiva, feedback adequado e sensação de controle sobre as ações realizadas. |
| USAB06 | o software deve ser capaz de atender pessoas com necessidades especiais de uso.                                                  |

<div style="text-align: center">
    <p> Tabela 1: Requisitos de Usabilidade. (Fonte: Autores. 2023).</p>
</div>

### 3. Confiabilidade

Na Tabela 2 estão registrados os requisitos de confiabilidade


| ID     | Descrição                                                                                                |
|--------|----------------------------------------------------------------------------------------------------------|
| CONF01 | o sistema deve manter os dados seguros de ataques.                                                       |
| CONF02 | o sistema deve garantir a integridade dos dados, ou seja, não permitir que modificações não autorizadas. |
| CONF03 | O sistema deve estar em conformidade com as leis e regulamentações de privacidade de dados aplicáveis.   |
| CONF04 | o sistema deve estar disponível todos os dias em todas as horas do dia.                                  |

<div style="text-align: center">
    <p> Tabela 2: Requisitos de Confiabilidade. (Fonte: Autores. 2023).</p>
</div>

### 4. Performance

Na Tabela 3 estão registrados os requisitos de performance


| ID     | Descrição                                                                                                           |
|--------|---------------------------------------------------------------------------------------------------------------------|
| PERF01 | o sistema não deve ter um tempo de resposta maior que 2 segundos.                                                   |
| PERF02 | o sistema não deve sobrecarregar o processador do dispositivo.                                                      |
| PERF03 | o sistema deve ser capaz de suportar um aumento de 100% na média de usuários simultâneos sem degradar o desempenho. |
| PERF04 | o sistema deve ter um baixo consumo energético.                                                                     |

<div style="text-align: center">
    <p> Tabela 3: Requisitos de Performance. (Fonte: Autores. 2023).</p>
</div>

### 5. Suportabilidade

Na Tabela 4 estão registrados os requisitos de suportabilidade


| ID     | Descrição                                                                                         |
|--------|---------------------------------------------------------------------------------------------------|
| SUPT01 | o aplicativo deve ser compatível com uma ampla variedade de dispositivos e sistemas operacionais. |
| SUPT02 | O sistema deve rodar nas principais plataformas mobile Android e iOS.                             |
| SUPT03 | O sistema deve possuir uma responsividade para os diferentes tipos de aparelhos e dispositivos.   |

<div style="text-align: center">
    <p> Tabela 4: Requisitos de Suportabilidade. (Fonte: Autores. 2023).</p>
</div>

### 6. Design

Na Tabela 5 estão registrados os requisitos de design


| ID     | Descrição                                                                                                                                                                                                          |
|--------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| DSGN01 | O sistema deve seguir um conjunto consistente de diretrizes visuais, incluindo a escolha de cores, tipografia, ícones e outros elementos de design pré-estabelecidos pela equipe de design.                        |
| DSGN02 | O sistema deve refletir a marca da empresa ou organização que o desenvolveu. Para isso, deve-se incluir a escolha de cores e estilos de design que estejam alinhados com a marca e a identidade visual da empresa. |

<div style="text-align: center">
    <p> Tabela 5: Requisitos de Design. (Fonte: Autores. 2023).</p>
</div>

### 7. Implementação

Na Tabela 6 estão registrados os requisitos de implementação


| ID     | Descrição                                                                                                 |
|--------|-----------------------------------------------------------------------------------------------------------|
| IMPL01 | O aplicativo deve ser construído seguindo o padrão proposto pela empresa que o desenvolve.                |
| IMPL02 | O aplicativo deve seguir o padrão de arquitetura proposto pela equipe de arquitetura presente no projeto. |

<div style="text-align: center">
    <p> Tabela 6: Requisitos de Implementação. (Fonte: Autores. 2023).</p>
</div>

### 8. Requisitos de Interface

Na Tabela 7 estão registrados os requisitos de interface


| ID     | Descrição                                                                                                                       |
|--------|---------------------------------------------------------------------------------------------------------------------------------|
| INTF01 | O aplicativo deve ter uma interface intuitiva, com uma navegação clara e objetiva.                                              |
| INTF02 | A interface do usuário deve ter uma hierarquia visual clara e fornecer feedback imediato para as ações realizadas pelo usuário. |

<div style="text-align: center">
    <p> Tabela 7: Requisitos de Interface. (Fonte: Autores. 2023).</p>
</div>

### 9. Requisitos Físicos

Na Tabela 8 estão registrados os requisitos de físicos


| ID     | Descrição                                                       |
|--------|-----------------------------------------------------------------|
| FISC01 | O dispositivo Android deve estar em uma versão 5.5 ou superior. |
| FISC02 | O dispositivo iOS deve estar em uma versão 6.x ou superior.     |

<div style="text-align: center">
    <p> Tabela 8: Requisitos de Físicos. (Fonte: Autores. 2023).</p>
</div>

## Bibliografia

YOUNG, Ralph. Requirements Engineering Handbook. Norwood, US: Artech House Books, 2003.

FURPS+. [S. l.], 10 jul. 2008. Disponível em: https://qualidadebr.wordpress.com. Acesso em: 13 maio 2023.

GRASSHOPPER. Fevereiro de 2023. Disponível em: https://requisitos-de-software.github.io/2022.2-Grasshopper/modelagem/especificao-suplementar/. Acesso em: 13 maio 2023.

## Histórico de versão

| Versão |    Data    |      Descrição      |        Autor        | Revisor |
| :-----: | :--------: | :--------------------: | :-----------------: | :-----: |
|   1.0   | 13/05/2023 | Criação do documento | Henrique e Chaydson |  Pedro  |
|   1.1   | 28/06/2023 | Colocando os requisitos em tabelas | Henrique e Chaydson |  Pedro  |
