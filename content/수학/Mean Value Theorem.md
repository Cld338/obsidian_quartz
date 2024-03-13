## Fermat's Theorem
함수 $f(x)$가 $x=a$에서 극값을 갖고, 미분 가능하면 $f'(a)=0$이다.
1) $f(a)$가 극대값인 경우
$f(a):\exists \delta\quad(s.t. f(x)\leq f(a),\forall x \in (a-\delta,a+\delta)\subset X)$
$$
\begin{align}
&f'(a)=\lim_{ x \to a } \frac{f(x)-f(a)}{x-a}=\begin{cases}
\lim_{ x \to a+ } \frac{f(x)-f(a)}{x-a}\leq0 \\
\lim_{ x \to a- } \frac{f(x)-f(a)}{x-a}\geq0
\end{cases} \\
&\therefore f'(a)=0
\end{align}
$$
2) $f(a)$가 극소값인 경우
위와 동일

## Rolle's Theorem
$f\in C[a,b]$, 개구간 $(a,b)$에서 미분가능하고 $f(a)=0=f(b)$이면 $f'(c)=0$을 만족하는 $c \in (a,b)$가 존재한다.
### Generalized Rolle's Theorem
$f\in C[a,b]$, 개구간 $(a,b)$에서 미분가능하고 $f(a)=f(b)$이면 $f'(c)=0$을 만족하는 $c \in (a,b)$가 존재한다.

## Mean Value Theorem

$f\in C([a,b])$이고 개구간 $(a,b)$에서 미분 가능하면
$$
\begin{align}
\frac{f(b)-f(a)}{b-a}=f'(c)
\end{align}
$$
를 만족하는 $c \in (a,b)$가 존재한다.
### Cauchy's mean value Throrem
$f,g\in C([a,b])$이고 개구간 $(a,b)$에서 미분 가능하며, $\forall x\in(a,b)$에 대해 $g'(x)\neq 0$이면
$$
\frac{f(b)-f(a)}{f()}
$$