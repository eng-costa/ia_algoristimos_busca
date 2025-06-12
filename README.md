
## UNIVERSIDADE FEDERAL DO MARANHÃO
Disciplina: Inteligência Artificial

Discente: Lucas Silva Costa


## ⚙️ Desafios Apresentados e Algoritmos Implementados

### 1. Problema do Troco (Coin Change)

Três abordagens são implementadas para resolver o problema de encontrar o número mínimo de moedas para um determinado valor.

-   **Abordagem Gulosa (Recursiva e Iterativa)**:
    -   **Estratégia**: Sempre escolhe a moeda de maior valor possível que não ultrapasse o valor restante.
    -   **Característica**: Rápida e simples, mas **não garante a solução ótima** para todos os conjuntos de moedas (falha em sistemas não-canônicos).

-   **Abordagem com Programação Dinâmica (DP)**:
    -   **Estratégia**: Constrói a solução de baixo para cima, calculando o troco ótimo para valores pequenos e usando esses resultados para resolver problemas maiores.
    -   **Característica**: É a abordagem que **garante a solução ótima** para qualquer conjunto de moedas, apesar de ser computacionalmente mais intensiva que a gulosa.

### 2. Algoritmo A*

Duas versões são apresentadas para encontrar o caminho mais curto em um grafo, ilustrando o impacto da escolha da estrutura de dados.

-   **Versão 1 (Original com Lista)**: Abordagem didática que usa uma lista Python e a ordena a cada passo (`list.sort()`). É mais fácil de entender, mas menos eficiente.
-   **Versão 2 (Otimizada com Fila de Prioridade)**: Implementação padrão que utiliza uma fila de prioridade (`heapq`) para gerenciar os nós abertos, resultando em uma performance muito superior, especialmente em grafos grandes.

