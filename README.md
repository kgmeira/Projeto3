# Projeto3

# README – Exercícios de Estruturas de Dados em Python

Este repositório apresenta três programas desenvolvidos em Python com o objetivo de aplicar conceitos fundamentais de programação, especialmente o uso de estruturas de dados lineares, como listas, pilhas (LIFO) e filas (FIFO).

---

## 1. Sistema de Votação

### Problema que resolve

O programa permite o registro de votos para três candidatos (Ana, Bruno e Carlos), realizando a contagem automática e determinando o vencedor ou possíveis situações de empate.

### Estruturas utilizadas

* Lista (`list`) para armazenamento dos votos
* Método `count()` para contagem de ocorrências
* Estruturas condicionais (`if`, `elif`, `else`) para análise dos resultados

### Como executar

1. Executar o programa em um ambiente Python
2. Inserir os votos informando o nome de um dos candidatos (`ana`, `bruno` ou `carlos`)
3. Digitar `fim` para encerrar a entrada de dados

### Exemplo

**Entrada:**

```id="yco0b0"
ana
bruno
ana
fim
```

**Saída:**

```id="8gcz6r"
Resultado da votação:
Ana: 2
Bruno: 1
Carlos: 0

Resultado final:
Vencedor: Ana
```

---

## 2. Editor de Texto com Funcionalidade de Desfazer (Pilha)

### Problema que resolve

O programa simula um editor de texto simples que permite inserir palavras, desfazer a última ação realizada e visualizar o conteúdo atual.

### Estruturas utilizadas

* Lista como estrutura de pilha (LIFO – Last In, First Out)
* Método `append()` para inserção de elementos
* Método `pop()` para remoção do último elemento inserido

### Como executar

1. Executar o programa
2. Selecionar uma das opções disponíveis no menu:

   * 1: Inserir palavra
   * 2: Desfazer última palavra
   * 3: Exibir texto atual
   * 4: Encerrar programa

### Exemplo

**Entrada:**

```id="c5u50o"
1 → ola
1 → mundo
3
2
3
```

**Saída:**

```id="vkgdck"
Texto atual: ola mundo
Palavra removida: mundo
Texto atual: ola
```

---

## 3. Sistema de Fila – Secretaria Acadêmica

### Problema que resolve

O programa simula o atendimento de alunos em uma secretaria acadêmica, organizando-os em uma fila conforme a ordem de chegada.

### Estruturas utilizadas

* Lista como estrutura de fila (FIFO – First In, First Out)
* Método `append()` para inserção no final da fila
* Método `pop(0)` para remoção do primeiro elemento da fila

### Como executar

1. Executar o programa
2. Selecionar uma das opções:

   * 1: Inserir aluno na fila
   * 2: Chamar próximo aluno
   * 3: Exibir fila atual
   * 4: Encerrar programa

### Exemplo

**Entrada:**

```id="x1fiyz"
1 → João
1 → Maria
2
```

**Saída:**

```id="puzx11"
Chamando aluno: João
```

---

## Considerações Finais

Os programas apresentados permitem a aplicação prática de conceitos essenciais da programação, tais como:

* Manipulação de listas
* Validação de dados de entrada
* Estruturas condicionais
* Implementação de estruturas clássicas:

  * Pilha (LIFO)
  * Fila (FIFO)

Esses exercícios são fundamentais para o desenvolvimento do raciocínio lógico e para a compreensão de estruturas de dados básicas em Python.
