# Isomorphism

Prove that if two graphs $A$ and $B$ are isomorphic they do *not* have to
be completely connected. I have started with the formal definition of
isomorphism below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.

Negation: Two graphs $A$ and $B$ are isomorphic and completely connected. 

Let there exist two graphs $A$ and $B$ that are isomorphic. So, $A$ = [V: {a, b, c}, E: {(a, b), (b, c)}] and $B$ = [V: {d, e, f}, E: {(d, e), (e, f)}] where a, b, c, d, e, f are vertices. This particular case modules that $A$ and $B$ are isomorphic as they follow the above definition of isomorphism. However, neither of the graphs are completely connected as there are only two edges and three vertices for both of the graphs. This contradicts the assumption that the two isomorphic graphs are completely connected. Therefore, if two graphs are isomorphic, they do not have to be completely connected. 

### Sources and Plagiarism 

I certify that I have listed all sources used to complete this exercise, including the use of any Large Language Models. All of the work is my own, except where stated otherwise. I am aware that plagiarism carries severe penalties and that if plagiarism is suspected, charges may be filed against me without prior notice.
