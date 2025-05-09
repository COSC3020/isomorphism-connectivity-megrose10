# Isomorphism

Prove that if two graphs $A$ and $B$ are isomorphic they do *not* have to
be completely connected. I have started with the formal definition of
isomorphism below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.

When looking at two graphs, they can be isomorphic, even if they are not completely connected. To prove this, you must check if there is a one-to-one mapping. So, look at each vertex, and its corresponding degree, next check if there is another vertex from the second graph that it can be mapped to. While having the same degree sequence is a must, it cannot be the only evidence when declaring isomorphism. This means you must check all mappings to make sure they maintain the same structure. To show this in an example, we have two graphs each with 4 vertices. G1’s vertices are A (connected to B), B (connected to C), C (connected to D), and D. G2’s vertices are 1 (connected to 2), 2 (connected to 3), 3 (connected to 4), and 4. While these two graphs have different vertex names, A can be mapped to 1, B can be mapped to 2, C can be mapped to 3, and D can be mapped to 4. Since each vertex is mapped to a unique vertex in the second graph, they have the same structure, resulting in two graphs which are not completely connected being isomorphic.

I looked back on my isomorphism nodes connectivity exercise.

I certify that I have listed all sources used to complete this exercise, including the use of any Large Language Models. All of the work is my own, except where stated otherwise. I am aware that plagiarism carries severe penalties and that if plagiarism is suspected, charges may be filed against me without prior notice.
