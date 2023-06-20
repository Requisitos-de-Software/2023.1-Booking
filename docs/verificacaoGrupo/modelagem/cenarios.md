# Verificação do cenário

## Introdução

O presente documento apresentará a verificação do artefato [Cenários](https://requisitos-de-software.github.io/2023.1-VLC/#/modelagem/cenarios), desenvolvido pela equipe 3, VLC. A técnica de inspeção será aplicada para verificar esse artefato, de acordo com o planejamento estabelecido, na tabela 1, se encontra os metadados desse artefato, nas tabelas 2 e 3 se encontram as questões a serem avaliadas.

<center>

| Versão avaliada | Autor                      | Revisor     |
| ---------------- | -------------------------- | ----------- |
| 1.0              | Bruno Ribeiro e Igor Penha | Lucas Gobbi |

</center>

<div style="text-align: center">
<p> Tabela 1: Versão avaliada. (Fonte: Chaydson e Samuel, 2023). </p>
</div>

| ID |                                 Questão                                 | Inspeção | Observações                 |
| :-: | :-----------------------------------------------------------------------: | :--------: | ----------------------------- |
| 1 |                 As legendas estão no padrão do projeto?                 |     🟢     |                               |
| 2 |                  Possui links para os outros artefatos?                  |    N/A    |                               |
| 3 |                   Existe uma introdução no artefato?                   |     🟢     |                               |
| 4 |                Existe tabela de versionamento padronizado?                |     🟢     |                               |
| 5 |      Há referências bibliográficas ou referências no artefato?      |     🟡     | A referência está duplicada |
| 6 | As tabelas e imagens possuem legenda, fonte e são introduzidas no texto? |     🟢     |                               |
| 7 |                         O artefato possui autor?                         |     🟢     |                               |
| 8 |                        O artefato possui revisor?                        |     🟢     |                               |

<div style="text-align: center">
<p> Tabela 2: Tabela de avaliação com as verificações gerais para todos os artefatos (Fonte: Chaydson e Samuel, 2023). </p>
</div>

| ID |                                                    Questão                                                    | Inspeção | Observações                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
| :-: | :------------------------------------------------------------------------------------------------------------: | :--------: | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 9 |       Os cenários contam com título, objetivos, contexto, ator(es), recursos, exceção e episódios?       |     🔴     | O cenário C08 não tem o campo recursos                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| 10 |                             Os cenários foram escritos de forma clara e concisa?                             |            |                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
| 11 |                      Os cenários foram construídos a partir de requisitos do sistema?                      |     🟢     |                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
| 12 |                       Os campos objetivo descrevem como o objetivo deve ser alcançado?                       |     🟢     |                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
| 13 |              Os campos contexto contam com pré-condições, o local e o tempo onde ele ocorre?              |     🟢     |                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
| 14 |          Os campos ator(es) representam um indivíduo ou organização que tem um papel no cenário?          |     🔴     | O cenário C15 restrige os atores a professores e alunos, porém outros tipos de usuários podem se interessar por essa funcionalidade.                                                                                                                                                                                                                                                                                                                                   |
| 15 |                Os campos recursos identificam os objetos que estão em contato com os atores?                |     🔴     | Como o cenário C08 não apresenta o campo recursos, logo o contato com os atores não ocorrerá.<br />Além disso no cenário C12 um dos recursos definidos é ter acesso a um vídeo, porém em nenhum momento no episódio é necessário interagir com o vídeo.                                                                                                                                                                                                      |
| 16 | Os campos episódios representam uma ação realizada por atores que utilizam recursos previamente definidos? |     🔴     | Como o cenário C08 não apresenta o campo recursos, logo não há recursos previamente definidos para esse cenário.                                                                                                                                                                                                                                                                                                                                                     |
| 17 |                    Os campos exceção descrevem restrições relacionadas ao cenário?                    |     🔴     | No cenário C03 a falta de conexão com a internet é citada como uma exceção, porém não é definida como recurso.<br />No cenário 07 a internet é citada como recurso,  entretanto não há exceção relacionada a falta dela.<br />No cenário 09 a internet é citada como recurso,  entretanto não há exceção relacionada a falta dela.<br />No cenário 10 a internet é citada como recurso,  entretanto não há exceção relacionada a falta dela. |

<div style="text-align: center">
<p> Tabela 3: Tabela de avaliação com as questões específicas do artefato (Fonte: Chaydson e Samuel, 2023). </p>
</div>

## Comentários

O cenário C10 tem como título "Só acessa com a senha". Esse título meio informal, seria bom escrever de uma forma mais profissional.

## Resultados

Para saber a porcentagem de aproveitamento do artefato, será utilizado a expressão:

((100/QntExigencias) * Acertos) + (((100/QntExigencias) * Incompletos)/2)

Através dos checklists realizados podemos observar que:

- 9/17 exigências são atendidas;
- 1/17 exigências estão incompletas;
- 5/17 exigências estão erradas ou não foram realizadas.

Portanto, com base no cálculo apresentado, pode-se dizer que o aproveitamento deste artefato está em 55,88%.

## Bibliografia

Cenários - Rastreamento de Cenários. Disponível em: [http://www-di.inf.puc-rio.br/~julio/bnncap3.pdf](http://www-di.inf.puc-rio.br/~julio/bnncap3.pdf) Acesso em: 10 de maio de 2023.

## Histórico de Versão

| Versão | Data       | Descrição                             | Autor(es)         |
| ------- | ---------- | --------------------------------------- | ----------------- |
| 1.0     | 14/06/2023 | Criação do documento de verificação | Chaydson e Samuel |
