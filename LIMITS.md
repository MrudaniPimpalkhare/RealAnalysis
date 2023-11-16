# Limits 
## List of Theorems and Properties
### Cluster point:
Let A $\subseteq$ R. A point c in$ R is a cluster point of A if for every d > 0 there exists at least one point x $\in$ A; x $\ne$ c such that | x - c | < $\delta$

### Limit: Definition -
Let A $\subseteq$F R, and let c be a cluster point of A. For a function f : A $\rightarrow$ R, a real number L is said to be a limit of f at c if, given any $\epsilon$ > 0, there exists a $\delta$ > 0 such that if x $\in$ A and 0 < |x - c| < $\delta$, then |f(x)- L| < $\epsilon$.
1. The value of $\delta$ generally depends on $\epsilon$.
2. This limit is obviously unique. (uniqueness of limits)

### Sequential Criterion for limits:
Let D $\subseteq$ f:A $\rightarrow$ R. Let c be a limit point of D and l $\in$ R. Then $lim _{x \to c}$ $f(x)$= $L$ iff for every sequence {x_{n}} in D-{c} converging to c, the sequence {$f(x_{n})$} converges to l.

### Boundedness in limits
Let D $\subseteq$ f:A $\rightarrow$ R be a function, Let c $\in$ D'. If $f$ has a limit $l$ $\in$ R at c then f is bounded on $N(c)bigcapD$ for some $N(c)$ of c.

### Algebra in limits
1. Addition
2. Multiplication
3. Division as long as denominator is not 0

###
Let D $\subseteq$R and f and g be fucntion functions on D to R. Let
c $\in$ D'. If f is boundedd on N'(c) $\bigcap$ D for some deleted neighbourhood 
N'(c) of c and $\lim _{x \to c}$ $g(x)$= $0$ then $\lim _{x \to c}$ $f(x).g(x)$= $0$ 

### Inequalities
If the function is greater than or equal to a certain value in the domain(not inclusive of the point c), then the limit tending to c, also follows the same inequality.

### Sandwich theorem:
Let D $\subseteq$ R. and $f,g,h$ be functions on D $\rightarrow$ R. Let c $\in$ D'. 
If $f(x) <=  g(x) <= h(x)$ for all x $\in$ $D- {c}$and if $\lim _{x \to c}$ $f(x)$ = $\lim _{x \to c}$ $h(x)$= $l$ then $\lim _{x \to l}$ $g(x)$= $l$

### Important concepts:
1. Right hand limit
2. Left hand limit
3. Limit at +, - infinity
4. Limits tending to infinity
5. Sequencial criterion for 3. and 4. are similar to that of regular limits.
ez.

### Cauchy criterion for limits
1. Let $D subseteq R$ and $f : D rightarrow R$ be a function. Let (c, $\infty$) $\subseteq$ D for some c $\in$ R Then $\lim _{x \to c}$ $f(x)$ = $l$ ($\in R$) if and only if for a pre-assigned positive $\epsilon$ there exists a positive $G > c$ such that $|f(x') - f(x")|$ < $\epsilon$. For every pair of points $x', x" > G$ . 

### Theorem for reciprocals:
Let $g : D rightarrow R$ be a function on $D$ and $(-infty, c) subseteq D$ 
for some $c \in R$. 
Then $\lim _{x \to -\infty}$ $g(x)$= $l$ if and only if $\lim _{x \to 0^-}$ $g(\frac 1 x)$ = $l$   

Similarly,
Let $g : D \rightarrow R$ be a function on $D$ and $(c,\infty) \subseteq D$ 
for some $c \in R$. 
Then $\lim _{x \to \infty}$ $g(x)$= $l$ if and only if $\lim _{x \to 0^+}$ $g(\frac 1 x)$ = $l$ 


## Important limits

1. $\lim _{x \to infty}$ $(1+ \frac 1 x)^x$= $e$

2. $\lim _{x \to -\infty}$ $(1+ \frac 1 x)^x$= $e$

3. $\lim _{x \to 0}$ $(1+ x)^\frac 1 x$= $e$

