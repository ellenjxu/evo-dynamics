 # Evolutionary dynamics of neuroevolution (NEAT)

> A problem set I wrote for [APPPHYS 237](https://bgoodlab.github.io/courses/apphys237/): Quantitative evolutionary dynamics

Evolution is nature's best optimization scheme. Neuroevolution uses evolutionary algorithms to optimize artificial systems to solve complex tasks.

[NEAT](https://nn.cs.utexas.edu/downloads/papers/stanley.ec02.pdf) proposed a method of evolving neural network topologies along with weights, resulting in faster convergence and greater success rate on the double pole balance RL task. The following key insights:
1) homologous recombination for crossover of different topologies
2) protecting structural innovation using speciation, and
3) "complexifying", or evolving from a simple, homogeneous initial population.

In each problem, we focus on a specific innovation from NEAT. _How can we apply insights from evolutionary dynamics to analyze neural network evolution?_
