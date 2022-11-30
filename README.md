# Initial algebra / Final coalgebra cheatsheet

Suggestions about terminology, a ways to organise this table and are welcome. Feel free to create a pull request.

Here we assume the base category $\mathbf{Set}$, and a $\mathbf{Set}$-enriched endofunctor, even though many of the constructions here are more general.


Base category | Endofunctor                     | Initial Algebra        | Final Coalgebra               |
:--------: | :------------:               | :-------------:         |:----------------:              |
$\mathbf{Set}$ | $\text{Const } A$           | $\emptyset$            | $A$                           |
$\mathbf{Set}$ | $X \mapsto X$               | $\emptyset$            | $1$                           |
$\mathbf{Set}$ | $X \mapsto A\times X$       | $\emptyset$            | $\text{Stream } A$            |
$\mathbf{Set}$ | $X \mapsto A + X$           | $A \times \mathbb{N}$  | ?                             |
$\mathbf{Set}$ | $X \mapsto 1 + X$           | $\mathbb{N}$           | ?                             |
$\mathbf{Set}$ | $X \mapsto [A, X]$           | $[A, \emptyset]$      | 1                             |
$\mathbf{Set}$ | $X \mapsto 1 + A \times X$           | List $A$      | Potentially infinite List $A$ |
$\mathbf{Set}$ | $X \mapsto 1 + A \times X^2$           | Finite binary tree with $A$-labelled nodes  | Potentially infinite binary tree with $A$-labelled nodes |
$\mathbf{Set}$ | $X \mapsto B + A \times X^n$           | Finite $n$-ary tree with $A$-labelled nodes and $B$-labelled leaves | Potentially infinite $n$-ary tree with $A$-labelled nodes with and $B$-labelled leaves|
$\mathbf{Set}$ | $X \mapsto O + [I, X]$           | $O \times [I, \emptyset ]$ | Potentially infinite Moore machine |
$\mathbf{Set}$ | $X \mapsto [I, O \times X]$           | ? | Potentially infinite Mealy machine |
$\mathbf{Set}$ | $X \mapsto X + X$           | ? | ? |
$\mathbf{Set}$ | $X \mapsto X \times X$           | $\emptyset$ | Infinite binary trees |
$\mathbf{Set}$ | $X \mapsto \mathcal{P}(X)$            | ? | ? |

