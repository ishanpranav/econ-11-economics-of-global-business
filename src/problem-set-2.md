# Problem Set 2

Ishan Pranav

February 11, 2025

Professor Pricila Maziero

ECON 11 Economics of Global Business

## Question 1

> Consider an economy with production function given by $Y=AK^{0.5}L^{0.5}$,
> where $A$ is the total factor productivity, $K$ is the capital stock, and $L$
> is the labor input. For simplicity, assume capital is fixed: $K=1$.
> Assume $A=100$.

### Question 1 Part A

> Write the firm’s problem of choosing labor demand. Derive the demand for labor
> as a function of the real wage.

In equilibrium, the firm chooses labor demand such that the marginal product of
labor is equal to the real wage: this is quantity demanded for labor that
maximizes output ($Y$).

We can use this property to derive an expression for the optimal demand for
labor ($L^\ast$) as a function of the real wage ($W/P$), where $P$ represents
the price of goods in the economy.

$$\begin{align*}
\frac{W}{P}&=\frac{\partial Y}{\partial L},\\
&=\frac{\partial}{\partial L}\left(AK^{0.5}L^{0.5}\right),\\
&=AK\cdot 0.5L^{0.5-1},\\
&=0.5AKL^{-0.5}.
\end{align*}$$

Using this expression for the real wage, we can solve for $L^*$, the optimal
labor demand.

$$\begin{align*}
0.5AK{L^\ast}^{-0.5}&=\frac{W}{P},\\
{L^\ast}^{-0.5}&=2A^{-1}K^{-1}\cdot\frac{W}{P},\\
L^\ast&=\left(2A^{-1}K^{-1}\cdot\frac{W}{P}\right)^{-2},\\
L^\ast&=0.25A^{2}K^{2}\left(\frac{W}{P}\right)^{-2}.\\
\end{align*}$$

For $A=100,K=1$, we have:

$$L^\ast=0.25\cdot 100^2\cdot 1^2\cdot\left(\frac{W}{P}\right)^{-2}=2500\left(\frac{W}{P}\right)^{-2}.$$

### Question 1 Part B

> Assume labor supply is inelastic and fixed at $L=100$. Find the equilibrium
> values of the wage and the employment level for this economy. Display
> graphically the labor supply and the labor demand curves.

Using our expression for the real wage, we can solve for $W/P$, the real wage,
for a given labor supply; for $L=100$, we have:

$$\begin{align*}
\frac{W}{P}&=0.5\cdot 100\cdot 1\cdot (100)^{-0.5}=5.\\
\end{align*}$$

Thus, the real wage is 5 units.
