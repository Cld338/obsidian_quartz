$$
\forall \epsilon>0,\exists \delta>0,0<|x-a|<\delta \Rightarrow |f(x)-L|<\epsilon
$$
모든 $\epsilon$에 대하여 어떤 $\delta$가 존재하여 $0<|x-a|<\delta \Rightarrow |f(x)-L|<\epsilon$을 만족시킬 수 있다 극한값 $\lim_{ x \to a }f(x)=L$이라고 할 수 있다.^[$\epsilon$이 아무리 작을지라도 이를 만족시키는 어떤 $\delta$를 항상 제시할 수 있다면, $\lim_{ x \to a } f(x)$는 $L$에 한없이 가까워진다.]


## 1 연산
### 1.1 덧셈
$$
\begin{align}
\lim_{ x \to c } f(x)=L, \lim_{ x \to c } g(x)=M \implies \lim_{ x \to c }  \{f(x)+g(x)\}=L+M
\end{align}
$$

$$
\begin{align}
&\lim_{ x \to c } f(x)=L,\lim_{ x \to c } g(x)=M \text{일 때}\\
&\forall \epsilon>0 \\
&\exists \delta_{1} > 0\quad\left( s.t.~0<|x-c|<\delta_{1} \implies |f(x)-L| < \frac{\epsilon}{2} \right) \\
&\exists \delta_{2} > 0\quad\left( s.t.~0<|x-c|<\delta_{2} \implies |g(x)-M|< \frac{\epsilon}{2}\right) \\
&let~\delta_{0}=min(\delta_{1},\delta_{2}) \\
&0<|x-c|<\delta_{0} \implies |f(x)+g(x)-L-M|\leq|f(x)-L|+|g(x)-M| < \epsilon
\end{align}
$$

### 1.2 곱셈
$$
\begin{align}
\lim_{ x \to c } f(x)=L, \lim_{ x \to c } g(x)=M \implies \lim_{ x \to c }  \{f(x)g(x)\}=LM
\end{align}
$$
$$
\begin{align}
&\lim_{ x \to c } f(x)=L,\lim_{ x \to c } g(x)=M \text{일 때}\\
&\forall \epsilon > 0\\
&\exists \delta_{1}>0\quad\left( s.t.~0<|x-c|<\delta_{1} \implies |f(x)-L|< \frac{\epsilon}{2|M|+2}\right) \\
&\exists \delta_{2}>0\quad\left( s.t.~0<|x-c|<\delta_{2} \implies |g(x)-M|< \frac{\epsilon}{2|L|+2}\right) \\ 
&\exists \delta_{3}>0\quad\left( s.t.~0<|x-c|<\delta_{3} \implies |f(x)|<|L|+1 \right) \\ 
&let~\delta=min(\delta_{1},\delta_{2}, \delta_{3}) \\
&0<|x-c|<\delta_{0}  \\
&\implies |f(x)g(x)-LM|=|f(x)g(x)-f(x)M+f(x)M-LM| \\
&\leq|f(x)||g(x)-M|+|M||f(x)-L|\leq(|L|+1)|g(x)-M|+|M||f(x)-L|<\frac{|L|+1}{2|L|+2}\epsilon + \frac{|M|}{2|M|+1}\epsilon<\epsilon \\
&\therefore \lim_{ x \to c } f(x)g(x)=LM
\end{align}
$$
### 1.3 나눗셈
$$
\begin{align}
\lim_{ x \to c } f(x)=L, \lim_{ x \to c } g(x)=M \implies \lim_{ x \to c }  \left\{ \frac{f(x)}{g(x)} \right\}= \frac{L}{M}
\end{align}
$$

$$
\begin{align}
&\lim_{ x \to c } f(x)=L,\lim_{ x \to c } g(x)=M \text{일 때} \\
&\forall \epsilon > 0 \\
&\exists\delta_{1}>0(0<|x-c|<\delta_{1} \implies |f(x)-L|<1) \\
&\implies |f(x)|<|L|+1\\
&\exists\delta_{2}>0(0<|x-c|<\delta_{1} \implies |g(x)-M|<1) \\
&\implies |g(x)|>|M|-1\\
&\exists\delta_{3}>0\left( 0<|x-c|<\delta_{2} \implies |f(x)-L|< \frac{|M|-1}{2} \epsilon \right) \\
&\exists\delta_{4}>0\left( 0<|x-c|<\delta_{3} \implies |g(x)-M|< \frac{|M|(|M|-1)}{2(|L|+1)} \epsilon \right) \\
&\operatorname{let}~\delta_{0}=\operatorname{min}(\delta_{1},\delta_{2},\delta_{3},\delta_{4}) \\
&0<|x-c|<\delta_{0} \\
&\implies \left| \frac{f(x)}{g(x)} - \frac{L}{M} \right|=\frac{|f(x)M-g(x)L|}{g(x)M}\leq \frac{|f(x)-L|}{|g(x)|}+\frac{|L||M-g(x)|}{|g(x)||M|}< \frac{|f(x)-L|}{|M|-1}+\frac{(|L|+1)|M-g(x)|}{(|M|-1)|M|}< \frac{\epsilon}{2}+\frac{\epsilon}{2}=\epsilon\\
\end{align}
$$
## 2 연속
$$
\begin{align}
&\lim_{ x \to c^{+} } f(x)=L, \lim_{ x \to c^{-} } f(x)=L \Rightarrow \lim_{ x \to c }=L \\
&\forall \epsilon>0 \\
&\exists \delta_{1}>0 \left( c<x<c+\delta \implies |f(x)-L|< \frac{\epsilon}{2} \right)\quad(\because \lim_{ x \to c^{+} } =L) \\
&\exists \delta_{2}>0 \left( c-\delta<x<c \implies |f(x)-L|< \frac{\epsilon}{2} \right)\quad(\because \lim_{ x \to c^{-} } =L) \\
&0<|x-c|<\delta\implies|f(x)-L|<\epsilon
\end{align}
$$
**극한은 하나의 값으로 수렴하는가?**

$$
\begin{align}
&\lim_{ x \to c } f(x)=L, \lim_{ x \to c } f(x)=m \Rightarrow l=M \\ \\
&\text{suppose}~L\neq M \\
&\text{let}~0<|L-M|<\epsilon \\
&\forall \epsilon>0 \\
&\exists \delta_{1}>0 \left( 0<|x-c|<\delta_{1} \implies |f(x)-L|< \frac{\epsilon}{2} \right)\quad(\because \lim_{ x \to c^{+} } =L) \\
&\exists \delta_{2}>0 \left( 0<|x-c|<\delta_{2} \implies |f(x)-L|< \frac{\epsilon}{2} \right)\quad(\because \lim_{ x \to c^{-} } =L) \\
&\text{let}~x_{0}=c+\frac{\operatorname{min}(\delta_{1},\delta_{2})}{2} \\
&\epsilon=|L-M|\leq|f(x)-L|+|g(x)-M|< \frac{\epsilon}{2} + \frac{\epsilon}{2} = \epsilon \quad(\rightarrow\leftarrow)
\end{align}
$$