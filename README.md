# Isomorphism

Prove that if two graphs $A$ and $B$ have the same number of nodes and are
completely connected, they must be isomorphic. I have started with the formal
definition of isomorphism below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.

Let two graphs $A$ and $B$ have the same number of nodes and be completely connected. By definition, completely connected means that there is an edge between every pair of nodes. Therefore, each vertex is connected to every other vertex. 

As the graphs have the same number of nodes, it would follow that they therefore have the same number of edges and degree sequences because they are both completely connected. 

Consider $f: A \rightarrow B$ to be a bijection, so that $f$ is one-to-one and onto. This means that every vertex in A is matched with a unique vertex in B, and every vertex in B is matched with a unique vertex in A. 

As A and B are completely connected graphs, every distinct pair of vertices has an edge such that for every edge in A there is an edge is B and for every edge in B there is an edge in A. 

The bijection preserves the structure and edge relationship of A and B, making them isomorphic. Therefore two graphs of the same number of nodes and are completely connected must be isomorphic. 

### Sources and Plagiarism 

I certify that I have listed all sources used to complete this exercise, including the use of any Large Language Models. All of the work is my own, except where stated otherwise. I am aware that plagiarism carries severe penalties and that if plagiarism is suspected, charges may be filed against me without prior notice.
