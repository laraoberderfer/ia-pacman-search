# Artificial Intelligence Game Pacman Search tests

O trabalho foi desenvolvido na disciplina de Inteligência artificial da UFSC, por mim e mais 3 colegas.
O objetivo deste trabalho foi implementar e experimentar resoluções de problemas com abordagens de buscas.
A implementação foi baseada no projeto da Berkeley (https://inst.eecs.berkeley.edu/~cs188/sp20/projects/)
Aplicamos diversos algoritmos de buscas como DFS, BFS, A* sem heurística, A* com Manhattan, A* com Euclidiana.

## Discussões e considerações

Para a análise de custo, o algoritmo DFS custa mais para todos os dois dos três
tipos de labirintos, o pequeno e o médio. Os demais algoritmos se mostraram com o mesmo
custo para os três tamanhos de labirintos.
Para a análise de nodos expandidos pode-se perceber que o algoritmo DFS pode
encontrar uma solução em poucos nodos, mas não necessariamente é a melhor solução. O
algoritmo que se destacou foi o DFS para o maior labirinto explorado.
Referente a análise do tempo, o algoritmo mais rápido para o médio e grande
labirinto para encontrar a solução foi o A* com a heurística euclidiana.
Como não detectamos uma variância significativa nas heurísticas escolhidas,
decidimos realocar a “comida” para outro ponto do labirinto para testar o custo, nodos
expandidos e tempo de execução.

# Reinforcement learning
Utilizando a mesma modelagem para o espaço de estados e transições da modelagem do
problema de busca e adotando o Score como value function, seria possível aplicar uma abordagem
de Reinforcement Learning.

-------------------------------------------------------------------------------------------------
#### Autora
- Professora Lara Popov Zambiasi Bazzi Oberderfer
- Docente de Informática - Câmpus Chapecó
- Acadêmica do Doutorado de Automação e Sistemas da UFSC 2021  
- Instituto Federal de Santa Catarina - Câmpus Chapecó
- IFSC: http://www.chapeco.ifsc.edu.br
-------------------------------------------------------------------------------------------------
