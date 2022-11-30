# Initial algebra / Final coalgebra cheatsheet
List of initial algebras and final coalgebras of functors


Suggestions about terminology, a ways to organise this table and are welcome. Feel free to create a pull request.


| Functor                     | Initial Algebra        | Final Coalgebra               |
| :------------               | :------------:         |:---------------:              |
| $\text{Const } A$           | $\emptyset$            | $A$                           |
| $X \mapsto X$               | $\emptyset$            | $1$                           |
| $X \mapsto A\times X$       | $\emptyset$            | $\text{Stream } A$            |
| $X \mapsto A + X$           | $A \times \mathbb{N}$  | ?                             |
| $X \mapsto A + X$           | $\mathbb{N}$           | ?                             |
| $X \mapsto [A, X]$           | $[A, \emptyset]$      | 1                             |
| $X \mapsto 1 + A \times X$           | List $A$      | Potentially infinite List $A$ |
| $X \mapsto 1 + A \times X^2$           | Finite binary tree with $A$-labelled nodes  | Potentially infinite binary tree with $A$-labelled nodes |
| $X \mapsto B + A \times X^2$           | Finite binary tree with $A$-labelled nodes and $B$-labelled leaves | Potentially infinite binary tree with $A$-labelled nodes and $B$-labelled leaves|
| $X \mapsto 1 + A \times X^3$           | Finite ternary tree with $A$-labelled nodes  | Potentially infinite ternary tree with $A$-labelled nodes |
| $X \mapsto B + A \times X^3$           | Finite ternary tree with $A$-labelled nodes and $B$-labelled leaves | Potentially infinite ternary tree with $A$-labelled nodes with and $B$-labelled leaves|

