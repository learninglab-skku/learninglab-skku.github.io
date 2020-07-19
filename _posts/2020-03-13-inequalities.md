---
title: Inequalities
date: 2020-03-13
comment: true
categories: 
- Math
tags:
---

### Markov inequality
Let $X$ be a non-negative random variable and suppose that $ \mathbb{E}  [X] $ exists.  For any $ c \> 0 $, we have

$$
\mathbb{P}  \left\{ X \ge c \right\} \le \frac{ \mathbb{E}  [X] }{ c }.
$$

The equality holds when $ X = 0 $ or $ X = c $.

_proof._  Note that 

$$  c \cdot 1 \_{ X \ge c } \le X. $$

 By taking expectation both sides, we get

$$
\mathbb{E}  [c \cdot 1 \_{ X \> c } ] = c \, \mathbb{E}  [1 \_{ X \> c } ] = c \, \mathbb{P}  \left\{ X \> c \right\} \le \mathbb{E}  [X].
$$

$$\tag\*{$\blacksquare$}$$

### Chebyshev inequality  
Let $ \mu = \mathbb{E}  [X] $ and $ \sigma ^2 = \mathbb{E}  [|X - \mu | ^2 ] $.  Then,

$$
\mathbb{P}  \left\{ |X - \mu |  \ge c  \right\} \le \frac{ \sigma ^2 }{ c ^2 } .
$$

_proof._  Using the Markov inequality, we can show that

$$
\mathbb{P}  \left\{ |X - \mu |  \ge c  \right\} = \mathbb{P}  \left\{ |X - \mu | ^2   \ge c ^2   \right\} \le \frac{ \mathbb{E}  [|X - \mu | ^2 ]}{ c ^2 } = \frac{ \sigma ^2 }{ c ^2 } .
$$

$$\tag\*{$\blacksquare$}$$

### Jensen inequality
If $f$ is convex, then

$$
\mathbb{E}  [f(X)] \ge f(\mathbb{E}[X]).
$$

_proof._ Let 
### Gibb's (information) inequality

### Cauchy-Schawartz inequality