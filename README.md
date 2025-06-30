# Busca em A* (A-star) Search no mapa da Romenia

Este projeto implementa o algoritmo de busca A* (A-Star) para encontrar o caminho mais eficiente entre cidades no mapa da Romenia.

<div align"center">
<img src="https://github.com/user-attachments/assets/1cf7e612-18ec-4359-932a-3ea39e443d05" alt="Romenia_Mapa" width="500" height="400">
</div>

A busca A* é utilizada para encontrar o melhor caminho entre uma cidade de origem (Arad) e o destino (Bucharest), considerando:

g(n): custo real do caminho até o nó atual.<br>
h(n): heurística (estimativa do custo restante).<br>
f(n) = g(n) + h(n): avaliação total usada para escolha dos caminhos.<br>
