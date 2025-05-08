# Isomorphism

Prove that if two graphs $A$ and $B$ are isomorphic they do *not* have to
be completely connected. I have started with the formal definition of
isomorphism below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.

For two graphs to be isomorphic do not have to be completely connected. However, each vertex must
have another corresponding vertex to map to. So, you must look at the degree in which a vertex has, and 
find a corresponding vertex that matches. You must tell all mappings and compare to make sure they are isomorphic.
Each vertex cannot be paired to all vertices, however each vertex must be able to match to another vertex.
