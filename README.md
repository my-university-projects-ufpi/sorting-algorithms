# 📚 Algoritmos de Ordenação — Projeto Acadêmico

Este repositório contém implementações de algoritmos clássicos de ordenação, desenvolvidas com fins acadêmicos para a disciplina de Estruturas de Dados e Algoritmos.

O objetivo do projeto é compreender o funcionamento, desempenho e aplicações de diferentes métodos de ordenação.

---

## 📌 Algoritmos Implementados

Atualmente, o projeto conta com os seguintes algoritmos:

- Bubble Sort
- Insertion Sort
- Merge Sort
- Quick Sort
- Heap Sort

---

## 🔹 Bubble Sort

O **Bubble Sort** funciona comparando elementos adjacentes e trocando-os de posição caso estejam fora de ordem.

O processo se repete até que nenhuma troca seja necessária, indicando que o vetor está ordenado.

### Características:
- Complexidade: `O(n²)`
- Estável: ✅
- Simples implementação
- Baixa performance em grandes volumes de dados

---

## 🔹 Insertion Sort

O **Insertion Sort** organiza os elementos inserindo-os na posição correta dentro da parte já ordenada do vetor.

Funciona de forma semelhante à organização de cartas na mão.

### Características:
- Complexidade: `O(n²)`
- Estável: ✅
- Bom desempenho para listas pequenas
- Eficiente em vetores quase ordenados

---

## 🔹 Merge Sort

O **Merge Sort** utiliza a estratégia de **Dividir para Conquistar**.

O vetor é dividido recursivamente em partes menores até conter apenas um elemento, e depois é reorganizado de forma ordenada.

### Características:
- Complexidade: `O(n log n)`
- Estável: ✅
- Alto consumo de memória
- Excelente para grandes conjuntos de dados

---

## 🔹 Quick Sort

O **Quick Sort** escolhe um elemento como pivô e reorganiza o vetor, colocando os menores à esquerda e os maiores à direita.

Após isso, aplica o mesmo processo recursivamente nas partições.

### Características:
- Complexidade Média: `O(n log n)`
- Pior caso: `O(n²)`
- Estável: ❌
- Muito rápido na prática

---

## 🔹 Heap Sort

O **Heap Sort** utiliza uma estrutura chamada **Heap Binário** para ordenar os elementos.

Primeiro, o vetor é transformado em um heap máximo. Em seguida, o maior elemento é removido e colocado na posição correta.

### Características:
- Complexidade: `O(n log n)`
- Estável: ❌
- Não utiliza memória extra
- Performance consistente

---

## 🚀 Objetivos do Projeto

- Praticar conceitos de algoritmos de ordenação
- Comparar desempenho entre métodos
- Desenvolver raciocínio lógico
- Aplicar teoria na prática
