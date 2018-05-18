# GA
Algoritmo Genético

Código para Disciplina MAI5030  - Introdução aos Sistemas Evolutivos

Os Algoritmos Genéticos (GA) foram utilizados na escolha da melhor
combinação entre cinco Scores avaliados com cinco diferentes
regras. O problema possuía um espaço de busca de (25−1)∗5 = 155)
possibilidades e objetivo era encontrar a melhor regra final de decisão.
Foi utilizada uma base dados com 153.400 clientes rotulados de
forma binária como 1 aquele propensos a um direcionamento para
atendimento diferenciado no Call Center e 0 caso contrário. A avaliação
do fitness do modelo foi o VP (verdadeiro positivo) obtido via
o ponto de corte dos 50.000 clientes com maiores Score final. Foram
realizadas simulações de probabilidade de Crossover e Mutação e
a seleção foi feita via elitismo, mantendo na população sempre os
indivíduos mais aptos. A combinação final encontrada apresentou
fitness superior à técnica benchmark de mercado.
