# Fillit
[FR]
Un projet de 42.
Ce projet m'a permis de découvrir une problématique récurrente en programmation : la recherche d'une solution optimale parmis un très grand nombre de possibilités, dans un délais raisonable. Dans le cas de ce projet, il s'agit d'agencer des Tetriminos entre eux et de déterminer le plus petit carré possible pouvant les accuellir.

[EN]
A 42 project.
This project let me familiarize myself with a recurring problematic in programming : searching the optimal solution among a huge set of possibilities, in a respectable timing. In this particular project, I had to find a way to assemble a given Tetriminos set altogether in the smallest possible square.

Usage example:
test_map.txt : (you can use another test maps in the corresponding file)
.###
..#.
....
....

....
....
.##.
##..

....
.##.
.##.
....
-> ./fillit test_map.txt
-> .AAA
   CCA.
   CCBB
   .BB.
