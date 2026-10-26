# 2x2-Rubik-distribution
Distribution of the cases a 2x2 Rubik's Cube. Traverses the graph with BFS until all the states are explored.
Inspired from `Import Math` [video](https://www.youtube.com/watch?v=4mja0aMUX_Y).

## How to use:
$ python main.py > 2x2_states.txt (or your file name)

## Contains:
- 2x2_distribution.txt: number of states in each layer (generated with calculos.distribucion)
- main.py: currently generates the scrambles of all the states per layer
- It adds the time it takes to generate them

## TODO:
- Translate to English
- Document
- Optimize run-time
- Generate both files at the same time
- Use large files
