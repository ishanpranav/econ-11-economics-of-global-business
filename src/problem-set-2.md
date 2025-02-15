# Problem Set 2

Ishan Pranav

February 25, 2025

Professor Pricila Maziero

ECON 11 Economics of Global Business

## Question 1: Labor market

> Consider an economy with production function given by $Y=AK^{0.5}L^{0.5}$,
> where $A$ is the total factor productivity, $K$ is the capital stock, and $L$
> is the labor input. For simplicity, assume capital is fixed: $K=1$ unit.
> Assume $A=100$.

### Question 1 Part A

> Write the firm’s problem of choosing labor demand. Derive the demand for labor
> as a function of the real wage.

In equilibrium, the firm chooses labor demand such that the marginal product of
labor is equal to the real wage: this is quantity demanded for labor that
maximizes output $Y$.

We can use this property to derive an expression for the optimal demand for
labor $L^\ast$ as a function of the real wage $W/P$, where $P$ represents
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

For $A=100$ and $K=1$ unit, we have:

$$L^\ast=0.25\cdot 100^2\cdot 1^2\cdot\left(\frac{W}{P}\right)^{-2}=2500\left(\frac{W}{P}\right)^{-2}.$$

### Question 1 Part B

> Assume labor supply is inelastic and fixed at $L=100$ units. Find the
> equilibrium values of the wage and the employment level for this economy.
> Display graphically the labor supply and the labor demand curves.

Using our expression for the real wage, we can solve for $W/P$, the real wage,
for a given labor supply; for $L=100$ units, we have:

$$\begin{align*}
\frac{W}{P}&=0.5\cdot 100\cdot 1\cdot (100)^{-0.5}=5.\\
\end{align*}$$

Thus, the equilibrium real wage is 5 units and the equilibrium labor supply is
100 units.

__Market for labor: marginal product of labor (demand) *vs.* labor supply.__

![Market for labor](https://github.com/ishanpranav/econ-11-economics-of-global-business/blob/master/images/problem-set-2-1-2.png?raw=true "Market for labor")

The downward-sloping demand curve is given in red; the vertical supply curve is
given in blue.

### Question 1 Part C

> Suppose the economy faces a positive productivity shock and total factor
> productivity is now $A'=200$. Display graphically the new labor demand
> function. What are the equilibrium values of employment and the real wage?

For $A=200$ and $L=100$ units, we have:

$$\begin{align*}
\frac{W}{P}&=0.5\cdot 200\cdot 1\cdot (100)^{-0.5}=10.\\
\end{align*}$$

Thus, the new equilibrium real wage is 10 units and the equilibrium labor supply
remains 100 units.

__Market for labor: marginal product of labor (modified *vs.* original) *vs.* labor supply.__

![Market for labor, adjusted](https://github.com/ishanpranav/econ-11-economics-of-global-business/blob/master/images/problem-set-2-1-3.png?raw=true "Market for labor, adjusted")

The downward-sloping demand curves are given in red (the solid line marks the
modified demand curve); the vertical supply curve is given in blue.

### Question 1 Part D

> Compute the total output when $A=100$ and when $A=200$. What is the output’s
> growth rate? Compare that growth rate with the growth rate of $A$. How does
> the growth rate of output per capita compare to the growth rate of $A$?

We can derive an expression for $Y$ as a function of $A$.

$$\begin{align*}
Y&=AK^{0.5}L^{0.5},\\
&=A\cdot(1)^{0.5}(100)^{0.5},\\
&=10A.
\end{align*}$$

We assume that the labor force comprises the entire population, so that per
capita and per worker are equivalent.

For $A=100$, we have $Y=10\cdot 100=1000$ units of account. Output per capita
$\frac{Y}{L}=\frac{1000}{100}=10$ units of account.

For $A=200$, we have $Y=10\cdot 200=2000$ units of account. Output per capita
$\frac{Y}{L}=\frac{2000}{100}=20$ units of account.

We observe that a 100-percent increase in $A$ corresponds to a 100-percent
increase in $Y$, indicating constant returns to scale and consistent with our
understanding of total factor productivity.

Of course, with labor constant, the same constant-returns-to-scale relationship
also holds between total factor productivity and output per capita.

### Question 1 Part E

> Now, suppose that Congress, concerned about the welfare of the working class,
> passes a law setting the minimum wage that is 10 percent above the equilibrium
> wage you just derived (in the case where $A=100$). Assuming that Congress
> cannot dictate how many workers are hired at the mandated wage, what are the
> effects of this law? Specifically, calculate what happens to the real wage,
> the employment, the output, and the total amount earned by workers.

The government has introduced an effective wage floor at 10 percent above the
current equilibrium real wage of 5 units. This means that the effective real
wage increases to 5.5 units.

For a real wage of 5.5 units, we have:

$$L'=2500\cdot(5.5)^{-2}\approx 82.6446\dots~\approx 82.$$

Thus, the new quantity of labor demanded, $L'$, is about 82 units. The reduction
in labor input causes output to decline.

$$\begin{align*}
Y&=AK^{0.5}L^{0.5},\\
&\approx 100\cdot(1)^{0.5}\cdot(82.6446\dots)^{0.5},\\
&\approx 909.\overline{09}.
\end{align*}$$

The new output is about 909.09 units of account, down from 1000.00 units of
account before the minimum wage.

The total amount earned by workers is labor'sshare of output, or $0.5Y$ in this
model.

$$0.5Y\approx 0.5\cdot 909.\overline{09}\approx 454.\overline{54}.$$

The total amount earned by workers is about 454.54 units of account, down from
500.00 before the minimum wage.

### Question 1 Part F

> Does Congress succeed in its goal of helping the working class?

No, the proposed minimum wage intends to benefit the working class but reduces
the total amount earned by workers from 500.00 units of account to about 454.54
units of account.

Although the real wage increases, the number of employed workers decreases, so
the collective working class is worse off. In this case, the minimum wage
contributes to unemployment and prioritizes individual workers' outcomes at the
expense of the working class and the broader economy.

### Question 1 Part G

> Do you think the analysis provides a good way of thinking about a minimum-wage
> law? Why or why not?

Yes, this analysis offers a framework for demonsrtating how a minimum wage can
be destructive to the economy and counterproductive to its aims.

However, like any model, the Cobb–Douglas production function is a product of,
and thus limited by, its assumptions. No decision should be made using a single
model, and our Cobb–Douglas-based analysis fails to capture frictions in the
labor market and may overestimate how easily labor can be replaced or
eliminated.

## Question 2: Supply and demand in the neoclassical economy

> Consider an economy in which the consumption, investment and production
> functions are as follows, where $C$ denotes consumption, $I$ denotes
> investment, $r$ denotes the real interest rate, and $F$ denotes the production
> function. Let capital supply $K=100$ units, labor supply $L=100$ units, total
> factor productivity $A=10$, government expenditure $G=200$ units of account,
> and government tax revenue $T=200$ units of account.

$$C=90+0.7(Y −T).$$

$$I=250−20r.$$

$$F(K,L)=AK^{\frac{1}{2}}L^{\frac{1}{2}}.$$

> Compute the equilibrium values of output, overall labor income, consumption,
> public savings, national savings, investment, and the interest rate.

Total output is given by the production function.

$$Y=F(K,L)=10\cdot(100)^{\frac{1}{2}}\cdot(100)^{\frac{1}{2}}=1000.$$

In this model, labor's share of income is one-half, so labor income is $\frac{1}{2}Y=\frac{1}{2}(1000)=500$ units of account.

Consumption is given by the consumption function.

$$C=90+0.7(1000-200)=650.$$

Private savings $Y-T-C$ is given by earnings retained after taxes and
consumption.

$$Y-T-C=1000-200-650=150.$$

Public savings $T-G$ is given by government tax receipts after expenditures.

$$T-G=200-200=0.$$

Since $T=G$, private savings comprise all national savings. In equilibrium,
savings equals investment, so $I=150$.

$$I=150=250-20r\Rightarrow r=5\%.$$

In equilibrium, output is 1000 units of account, overall labor income is 500
units of account, consumption is 650 units of account, public savings is 0,
national savings is 150 units of account, investment is 150 units of account,
and the real interest rate is 5 percent.

> Suppose now government spending increases to $G=250$ units of account
> *Caeteris paribus*, what happens to output, consumption, savings, investment
> and the interest rate?

Total output, labor income, consumption, and private savings do not depend on
$G$: They are unchanged.

Public savings $T-G$ is given by government tax receipts after expenditures.

$$T-G=200-250=-50.$$

Since $T<G$, national savings is private savings, offset by public deficit:
$150-50=100$. In equilibrium, savings equals investment, so $I=100$.

$$I=100=250-20r\Rightarrow r=7.5\%.$$

After the increase in government spending, output remains 1000 units of account,
overall labor income remains 500 units of account, consumption remains 650 units
of account, public savings falls to -50 units of account, national savings falls
to 100 units of account, investment falls to 100 units of account, and the real
interest rate rises to 7.5 percent.

## Question 3: Emerging market forecasting and growth accounting

> What drives gross domestic product growth in Brazil and China? How do they
> compare to each other? Assume that, in both countries, payments to labor
> $1-\alpha=\frac{2}{3}$.

For each period $t$, we use real gross domestic product $Y_t$ and real capital
stock $K_t$ at constant prices (2017), and employment, number of persons engaged
$L_t$—both datasets by Robert C. Feenstra, Robert Inklaar and Marcel P. Timmer,
and available from the
[Penn World Table 10.01](https://www.rug.nl/ggdc/productivity/pwt/?lang=en).

### Question 3 Part A

> How has gross domestic product per worker evolved in the two countries?

__Gross domestic product (GDP) per worker for Brazil and China, 1980–2019.__

![GDP per worker for Brazil and China, 1980–2019.](https://github.com/ishanpranav/econ-11-economics-of-global-business/blob/master/images/problem-set-2-3-1.png?raw=true "GDP per worker for Brazil and China, 1980–2019")

__Interpretation.__

Whereas GDP per worker has accelerated in China, it has remained somewhat
constant in Brazil.

### Question 3 Part B

For each period $t$, the total factor productivity $A_t$ is derived from the
Cobb–Douglas production function.

$$\begin{align*}
Y_t=A_tK_t^{\alpha}L_t^{1-\alpha}.\\
A_t=Y_tK_t^{-\alpha}L_t^{\alpha-1},\\
A_t=Y_tK_t^{-\frac{1}{3}}L_t^{-\frac{2}{3}}.
\end{align*}$$

__Total factor productivity index for Brazil and China, 1980–2019, where 1980=100.__

![Total factor productivity index for Brazil and China, 1980–2019, where 1980=100.](https://github.com/ishanpranav/econ-11-economics-of-global-business/blob/master/images/problem-set-2-3-2.png?raw=true "Total factor productivity index for Brazil and China, 1980–2019, where 1980=100")
