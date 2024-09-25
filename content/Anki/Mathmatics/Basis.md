TARGET DECK
Mathematics::Basis


prove that $$\lim_{ n \to \infty } \frac{r^{n}}{n!}\quad(r>0)$$ is convergent.;;$$\begin{align}&let~N>0\quad(s.t~n\geq N\geq r^{2}) \\&\frac{r^{n}}{n!}=\frac{r^{N}}{N!}\times \frac{r^{n-N}}{n(n-1)\cdots(N+1)} \\&n\geq N \geq r^{2}\implies \frac{{1}}{N}\leq \frac{1}{r^{2}} \implies \frac{r}{N}\leq \frac{1}{r} \\&\therefore 0<\lim_{ n \to \infty } \frac{r^{n}}{n!}\leq \frac{r^{N}}{N!}\left( \frac{1}{r} \right)^{n-N}=0\end{align}$$
<!--ID: 1717843735621-->

prove that $$\begin{align}\lim_{ x \to \infty } \frac{x^{p}}{r^{x}} \quad(p>0,r>1)\end{align}$$ is convergent.;;$$\begin{flalign}&let~N>p\\&\lim_{ x \to \infty } \frac{p(p-1)\cdots(p-N+1)x^{p-N}}{r^{n}(\ln r)^{N}} =0 \\&\implies\lim_{ x \to \infty } \frac{p(p-1)\cdots(p-N+2)x^{p-N+1}}{r^{x}(\ln r)^{n-1}}=0\\&\quad\vdots\\&\implies\lim_{ x \to \infty } \frac{px^{p-1}}{r^{x}\ln r}=0\tag{L'Hopital's rule}\end{flalign}$$
<!--ID: 1717843838979-->

prove that $\\lim_{ n \to \infty } \left| \frac{a_{n+1}}{a_{n}} \right|=\rho>1$ converges absolutely;;
<!--ID: 1718945090423-->
