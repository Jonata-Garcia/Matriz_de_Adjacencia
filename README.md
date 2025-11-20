# 🌐 Matriz de Adjacência – Representação de Grafos

Este notebook demonstra como representar grafos em Python usando a **matriz de adjacência**, uma forma matricial de armazenar relações entre vértices.

---

## 📌 Conteúdo

1. **Introdução à Matriz de Adjacência**  
   Explicação teórica sobre o que é uma matriz de adjacência e como ela representa conexões entre vértices. :contentReference[oaicite:0]{index=0}  

2. **Criação de uma Matriz de Adjacência**  
   Definição de vértices (nós) e arestas; construção da matriz quadrada onde cada entrada indica se há ou não uma aresta entre pares de vértices.

3. **Matriz Simétrica**  
   Demonstração de grafos não direcionados, onde a matriz é simétrica (A[i][j] = A[j][i]). :contentReference[oaicite:1]{index=1}  

4. **Representação de Grafos Direcionados**  
   Possibilidade de construção de uma matriz onde a existência de uma aresta depende da direção entre os vértices.

5. **Análise de Complexidade**  
   Discussão sobre o custo espacial da matriz (O(n²) para grafos com n vértices). :contentReference[oaicite:2]{index=2}  
   
6. **Aplicações e Vantagens**  
   - Verificar rapidamente se dois vértices estão conectados (acesso O(1)). :contentReference[oaicite:3]{index=3}  
   - Boa estrutura para grafos densos.  
   
7. **Desvantagens**  
   - Consumo elevado de memória para grafos esparsos.  
   - Representação ineficiente para alguns tipos de grafos ou grandes quantidades de vértices.

---

## 🚀 Tecnologias Utilizadas  
- Python  
- NumPy (para manipular a matriz)  

---

## 🎯 Objetivo  
Entender de forma prática e teórica como representar grafos por meio de uma **matriz de adjacência**, avaliando os trade-offs da estrutura e suas aplicações em algoritmos de grafos.

---

## ▶️ Como Executar  
1. Clone este repositório.  
2. Abra o notebook `Matriz_de_Adjacência.ipynb` no **Google Colab** ou **Jupyter Notebook**.  
3. Execute as células em sequência para ver a construção da matriz, exemplos e análise.

---

✍️ Autor: **Jonata Pablo Garcia**
