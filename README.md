 # Evolutionary dynamics of neuroevolution (NEAT)

> A problem set I wrote for [APPPHYS 237](https://bgoodlab.github.io/courses/apphys237/): Quantitative evolutionary dynamics
> 
> Some background a student might need: basic understanding of neural nets, probability/counting, and content from the course such as branching process and barcode lineages. Problem 1 doesn't require any bio background and can be tackled by anyone with knowledge of basic mathematics.
>
> feedback much appreciated!

## overview

Evolution is nature's best optimization scheme. **Can evolution be used to optimize artificial systems?**

Neuroevolution uses evolutionary algorithms to generate neural networks to solve complex tasks.

[NEAT](https://nn.cs.utexas.edu/downloads/papers/stanley.ec02.pdf) proposed a method of evolving neural network topologies along with weights, resulting in faster convergence and greater success rate on the double pole balance RL task. The following key insights:
1) homologous recombination for crossover of different topologies
2) protecting structural innovation using speciation, and
3) "complexifying", or evolving from a simple, homogeneous initial population.

![image](https://github.com/ellenjxu/quant-evolutionary-dynamics/assets/56745453/320c218c-5f50-444b-90c3-20c08479cb2d)


In each problem, we focus on a specific innovation from NEAT. We apply evolutionary dynamics to provide insights on neural network evolution.
