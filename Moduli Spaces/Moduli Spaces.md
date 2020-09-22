# Moduli Spaces

Jenia Tevelev: mail: tevelev@math.umass.edu

## Introduction

#### Example

$M_g=${moduli space of smooth algebraic curves (=compact Riemmann surfaces) of genus g}

### Thm(Deligne-Maniford)

$M_g$ is connected, any 2 algebraic curves are deformation equivalent.

#### Grassmannian

G(r,n) parametrizes r-dimensional linear subspaces of $\mathbb{C}^n$

G(1,n):= Lines passing through the origin = $\mathbb{P}^{n-1}$

G(n,n-1):= Hyperplanes in $\mathbb{C}^n$ ($a_1x_1+\dots+a_nx_n=0$) = $(\mathbb{P}^{n-1})^*$

G(2,4):= ?

A point of G(r,n) is $U\subset\mathbb{C}^n,\dim U=r$. $L=\mathbb{P}U\subset\mathbb{P}^{n-1}$.

G(r,n)={(r-1)-dim projective subspaces in $\mathbb{P}^{n-1}$

G(2,4):={lines in $\mathbb{P}^3$}

### Def (Complex Manifold)

Is a topological space (second-countable and Hausdorff) with a finite covering by open sets "charts".

- We have homomorphism $\psi_i:X_i$ coordinates of $\mathbb{C}^n$ restricted to $X_i$ are called local coordinates.
- On the overlaps $X_i\cap X_j$ we have 2 systems of local coordinates (through $\psi_i,\psi_j$), $\psi_j\circ\psi_i^{-1}$ "transition function" are holomorphic

#### Examples
$\mathbb{P}^{n-1}$ is covered by charts $X_i=\{[x_1:\dots:x_n]|x_i\neq0\}=\mathbb{A}^{n-1}$. The structure of the topological space is uniquely determined by this data, $V\subset\mathbb{P}^{n-1}$ is open iff $\psi_i(V\cap X_i)\subset\mathbb{A}^{n-1}$ is open.

G(r,n) as a complex manifold. Every r-dim subspace $U\subset\mathbb{C}^n$ is a row space of a rxn matrix of rank r.

$[n]=\{1,\dots,n\}$, for every $I\subset [n]$ of cardinality r. $A_I$ is the rxr submatrix of A with columns indexed by I. $P_I=\det(A_I)$ "Plücker coordinates on G(r,n)", $P_I\neq0$ for at least one I (rk(A)=r iff at least one $A_I$ is invertible).

### Lem/Def
G(r,n) is a complex manifold of dimension r(n-r) covered by $\binom{n}{r}$ charts $X_I$, indexed $I\subset [n]$ or cardinality r, where $X_I=\{u\in G(r,n), P_I\neq0\}\simeq\mathbb{C}^{r(n-r)}$, U=Row space of a matrix A such that $A_I=Id_r$. Local coordinates on $X_I$ are the remaining $r-n-r^2=r(n-r)$ matrix entries of A. Indeed, transition functions are holomorphic (see notes).
