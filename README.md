# Initial algebra / Final coalgebra cheatsheet

Suggestions about terminology, a ways to organise this table and are welcome. Feel free to create a pull request.

Here we assume the base category $\mathbf{Set}$, and a $\mathbf{Set}$-enriched endofunctor, even though many of the constructions here are more general.


| Endofunctor                     | Initial Algebra        | Final Coalgebra               |
| :------------               | :------------:         |:---------------:              |
| $\text{Const } A$           | $\emptyset$            | $A$                           |
| $X \mapsto X$               | $\emptyset$            | $1$                           |
| $X \mapsto A\times X$       | $\emptyset$            | $\text{Stream } A$            |
| $X \mapsto A + X$           | $A \times \mathbb{N}$  | ?                             |
| $X \mapsto 1 + X$           | $\mathbb{N}$           | ?                             |
| $X \mapsto [A, X]$           | $[A, \emptyset]$      | 1                             |
| $X \mapsto 1 + A \times X$           | List $A$      | Potentially infinite List $A$ |
| $X \mapsto 1 + A \times X^2$           | Finite binary tree with $A$-labelled nodes  | Potentially infinite binary tree with $A$-labelled nodes |
| $X \mapsto B + A \times X^n$           | Finite $n$-ary tree with $A$-labelled nodes and $B$-labelled leaves | Potentially infinite $n$-ary tree with $A$-labelled nodes with and $B$-labelled leaves|
| $X \mapsto O + [I, X]$           | $O \times [I, \emptyset ]$ | Potentially infinite Moore machine |
| $X \mapsto [I, O \times X]$           | ? | Potentially infinite Mealy machine |
| $X \mapsto \Sigma_{k : \mathbb{N}} a_k \times X^k$           | ? | ? |
| $X \mapsto X + X$           | ? | ? |
| $X \mapsto X \times X$           | $\emptyset$ | Infinite binary trees |
| $X \mapsto \mathcal{P}(X)$            | ? | ? |

