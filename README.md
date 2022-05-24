# TDD - Engenharia de Software

Essa tarefa tem por objetivo praticar o Desenvolvimento Orientado (ou Dirigido) a Testes (do inglês, *Test Driven Development*) como parte do conteúdo programático da disciplina de Engenharia de Software.

Para cada um dos problemas abaixo, sua tarefa é criar o código para resolver o problema juntamente com uma **suíte de testes unitários** capaz de testar a sua solução. A suíte de testes deverá ser executada de maneira automatizada.

### Suíte de Testes
Para a confecção da suíte de testes, busque incluir casos em que seu código pode falhar, como extremos, valores vazios, entre outros. Quanto mais testes, mais resiliente está sua implementação - e provavelmente melhor será sua nota. ;)

> Dica: busque frameworks para construção desses testes. Exemplos: `jest`, `pytest`, `JUnit`, etc...

### Qual linguagem devo escolher?
Para a resolução dessa tarefa, é ideal que escolha uma dessas linguagens: `Python`, `JavaScript`, `TypeScript` ou `Java`. Qualquer implementação em outra linguagem deverá ser comunicada e aprovada previamente pelo professor sob pena de invalidar sua submissão.

### Envio
Para envio da sua resposta, você deverá criar um repositório **público** no GitHub com o seu código da sua solução. Após a criação do repositório, envie o link do seu repositório como um comentário [nessa issue](https://github.com/cavalcantigor/eng-software-tdd/issues/1).

Só serão aceitos envios realizados até o dia 30/05/2022.

## Tarefas

### Soma de um array
Dado um array de inteiros, encontre a soma de seus elementos.
> Exemplo: para o array [1, 2, 3] o resultado de sua soma é 6, uma vez que 1 + 2 + 3 = 6.

Para essa tarefa, considere um array de tamanho n, onde 0 < n <= 1000.

### Diferença Diagonal
Dada uma matriz quadrada de tamanho **n**, calcule a diferença absoluta da soma de suas diagonais.

 Exemplo: 
```
1 2 3
4 5 6
9 8 9
```
A diferença diagonal absoluta para essa matriz é:
- 1 + 5 + 9 = 15 (diagonal da esquerda para a direita)
- 3 + 5 + 9 = 17 (diagonal da direita para a esquerda)
- Diferença absoluta: |15 - 17| = 2 (diferença em módulo)

Para esse problema, considere 2 < n <= 1000 e cada elemento da matriz como um inteiro -100 < `m[i][j]` <= 100.

### Palíndromo
Dada uma string de tamanho variável **n**, determine se essa string é um palíndromo.

Exemplos:
- "ABBA" é um palíndromo.
- "SOCORRAM ME SUBI NO ONIBUS EM MARROCOS" é um palíndromo (perceba que para essa verificação os espaços em branco não são levados em consideração).
- "ABCDCBA" é um palíndromo.
- "ABAB" **não** é um palíndromo.


Para essa tarefa considere 0 < n <= 1000.
