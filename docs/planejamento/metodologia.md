# Introdução

Bem-vindo a página de metodologias e políticas, nela estão localizados as metologias que foram ou irão ser utilizadas durante o projeto, e as políticas para que o desenvolvimento ocorra com o melhor padrão possível para um gerar um bom projeto. Todos os itens abaixo podem ser acrescidos ou decrecidos de mais metodos utilizados , assim como a atualização das políticas, tudo isso para que se tenha uma padrão consistente no desenvolvimento do projeto.

## Metodologias

### Scrum

### Pair Programming

### Kanban

## Políticas

### Politicas de Issue

As issues devem seguir um padrão de acordo com o padrão localizado no ``.github`` lá a issue devem ser preenchidas a issue deve ter um título simples e direto, uma descrição sobre o que será feito,a data da atividade, marcar se o status da tarefa está em andamento ou foi concluída, e se possível adicionar tarefas para separar passo a passo em formato de tarefa sobre o que será feito e critérios de aceitação podem existir se necessário. 

### Politicas de Pull Request

As políticas de pull request definidas pelo grupo atualmente, são escrever no corpo do pull request o objetivo do pull request se possível, e obrigatoriamente um ``#resolve [número da issue]`` para fechar a issue aberta.

### Políticas de Branch

As políticas para se criar uma branch são foram decididas pelo grupo para ser criadas a partir de uma issue previamente definida o qual o nome para uma branch deve seguir o seguinte padrão: ``[NúmeroDaIssue]-[TituloSimplesSobreOProblemaResolvido]``. Exemplo: Criação de Página Exemplo sendo a issue 99, nome da branch ``99-PaginaExemplo``

### Política de Commit

Sobre a forma em como os commits serão feitos, eles devem ser escritos com poucas palavras resumindo a ação realizada, e caso aja ``co-authored`` é recomendado que se realize o commit no terminal pelo comando ``git commit -a`` que abrirá um editor de texto do terminal, nele você deve colocar o texto simples do commit pular algumas linhas e colocar as informações do co-autor da seguinte maneira: ``Co-authored-by: [Nome de usuário co-autor] <[Email do co-autor]>``, preenchendo a informações do co-autor no lugar do que está escrito no como exemplo, logo em seguida você deve salvar o arquivo e seguir o procedimento comum para realizar um ``git push``

## Bibliografia

## Histórico de Versão

| Versão | Data       | Descrição          | Autor(es) | Revisor(es) |
| ------- | ---------- | -------------------- | --------- | ----------- |
| 1.0     | 17/04/2023 | Criação da Página | Gabriel   | Henrique    |
