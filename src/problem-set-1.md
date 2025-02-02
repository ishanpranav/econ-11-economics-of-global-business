# Problem Set 1

Ishan Pranav

February 11, 2025

Professor Pricila Maziero

ECON 11 Economics of Global Business

## Definitions

Let $X$ be a continuous variable. Then $\gamma_X$ denotes its growth rate for a
given period with $\gamma_X=\ln(X_1)-\ln(X_0)$, where $X_1$ and $X_0$ denote the
values of $X$.

## Question 1

> Suppose an economy produces aluminum, microchips and computers. The aluminum
> industry produces $320,000 in revenue, spends $60,000 on microchips, $55,000
> on computers, pays workers $95,000. The microchip industry produces $220,000
> in revenue, spends $60,000 on aluminum, $35,000 on computers and pays workers
> $90,000. The computer industry produces $190,000 in revenue, spends $60,000 on
> microchips, $55,000 on aluminum and pays workers $60,000. There is no
> government. Calculate gross domestic product (GDP) using the production and
> income approaches.

| Agent | Revenue ($ thousand) | Material cost ($ thousand) | Value added ($ thousand) | Labor cost ($ thousand) | Profit ($ thousand) |
|---|--:|--:|--:|--:|--:|
| Aluminum industry | $320$ | $60+55=115$ | $205$ | $95$ | $110$ |
| Microchip industry | $220$ | $60+35=95$ | $125$ | $90$ | $35$ |
| Computer industry | $190$ | $60+55=115$ | $75$ | $60$ | $15$ |
| __Total__ | $730$ | $325$ | $405$ | $245$ | $160$ |

__Production approach.__

We can measure GDP by computing the "value added" at each
step of production.

The value added by an industry is given by its revenue minus its material costs.
Summing the "value added" over all industries gives $405,000.

Thus, the GDP via the production approach is $405,000.

__Income approach.__

We can instead measure GDP by computing the total payments to
labor and capital.

An industry's payments to labor are given by its labor cost. The sum over all
industries is $245,000.

In this economy, profits account for the remainder of the income. An industry's
profits are given by its revenue minus its material and labor costs. Summing the
profits over all industries gives $160,000.

Together, the sum of income from labor and income from profits is $405,000.
Thus, the GDP via the income approach is also $405,000.

## Question 2

> Consider an economy that produces only two types of goods: apples and bananas.
> The production and price for the base year and the current year are as
> follows.

| Product | Base quantity (bags) | Base price ($/bag) | Current quantity (bags) | Current price ($/bag) |
|---|--:|--:|--:|--:|
| Apple | 10 | 2.00 | 12 | 2.50 |
| Banana | 18 | 1.00 | 22 | 1.50 |

Let $\rm{A}$ denote apples and $\rm{B}$ denote bananas. Let $p_x$ (respectively,
$q_x$) denote the price (respectively, quantity) of product $x$ in the current
year. Let ${p_x}_0$ (respectively, ${q_x}_0$) denote the price (respectively,
quantity) of product $x$ in the base year.

### Question 2 Part A

> Compute nominal gross domestic product (GDP) in the current year and in the
> base year. What is the percentage increase since the base year?

Let $Y'$ (respectively, $Y_0$) denote nominal GDP in the current year
(respectively, base year).

__Current year.__

By definition, nominal GDP is a measure of _output_, and is given by the
sum-product of prices and quantities.

$$\begin{align*}Y'
&=\sum_{x\in\{\rm{A},\rm{B}\}}{(p_x\cdot q_x)}\\
&=\left(\frac{\$2.50}{\rm bag}\times 12~\text{bags}\right)+\left(\frac{\$1.50}{\rm bag}\times 22~\text{bags}\right)\\
&=\$63.00.\end{align*}$$

The nominal GDP in the current year is $63.

__Base year.__

$$\begin{align*}Y_0
&=\sum_{x\in\{\rm{A},\rm{B}\}}{({p_x}_0\cdot{q_x}_0)}\\
&=\left(\frac{\$2.00}{\rm bag}\times 10~\text{bags}\right)+\left(\frac{\$1.00}{\rm bag}\times 18~\text{bags}\right)\\
&=\$38.00.\end{align*}$$

The nominal GDP in the base year was $38.

__Percentage increase.__

$$\frac{Y'}{Y_0}-1\approx 65.7895\dots\%.$$

$$\gamma_{Y'}=\ln(Y')-\ln(Y_0)\approx 50.5549\dots\%.$$

The increase since the base year is approximately 66 percent, or 51 percent
in a continuous model.

### Question 2 Part B

> Compute real gross domestic product (GDP) in the current year and in the base
> year. By what percentage does real GDP increase from the base year to the
> current year?

Let $Y$ denote real GDP in the current year.

__Current year.__

By definition, real GDP controls for variations in price by fixing prices to
that of the base year.

$$\begin{align*}Y
&=\sum_{x\in\{\rm{A},\rm{B}\}}{({p_x}_0\cdot q_x)}\\
&=\left(\frac{\$2.00}{\rm bag}\times 12~\text{bags}\right)+\left(\frac{\$1.00}{\rm bag}\times 22~\text{bags}\right)\\
&=\$46.00.\end{align*}$$

The real GDP in the current year is $46.

__Base year.__

Intuitively, $Y_0$ also represents real GDP in the base year. In the base year,
real GDP and nominal GDP are both equal to the sum-product of base-year prices
and base-year quantities.

So the real GDP in the base year is $38.

__Percentage increase.__

$$\frac{Y}{Y_0}-1\approx 21.0526\dots\%.$$

$$\gamma_Y=\ln(Y)-\ln(Y_0)\approx 19.1055\dots\%.$$

The increase since the base year is approximately 21 percent, or 19 percent
in a continuous model.

### Question 2 Part C

> Calculate the consumer price index (CPI) in both years and the inflation rate
> using the CPI.

__Axiom.__

> Assume that the expenditure base to compute the CPI is base-year quantities
> (${q_{\rm A}}_0$ and ${q_{\rm B}}_0$).

Let $P$ denote the CPI in the current year.

__Current year.__

By definition, the CPI controls for variations in quantity by fixing quantities
to the expenditure base (base-year quantities per our axiom).

$$\begin{align*}P
&=\sum_{x\in\{\rm{A},\rm{B}\}}{(p_x\cdot{q_x}_0)}\\
&=\left(\frac{\$2.50}{\rm bag}\times 10~\text{bags}\right)+\left(\frac{\$1.50}{\rm bag}\times 18~\text{bags}\right)\\
&=\$52.00.\end{align*}$$

The CPI in the current year is $52.

__Base year.__

Intuitively, $P_0=Y_0$ also represents the CPI in the base year. Per our axiom,
quantity produced and quantity expended are equal. In the base year, nominal GDP
and CPI are both equal to the sum-product of base-year prices and base-year
quantities.

So the CPI in the base year is $38.

__Inflation rate.__

$$\frac{P}{P_0}-1\approx 36.8421\dots\%.$$

$$\gamma_P=\ln(P)-\ln(P_0)\approx 31.3658\dots\%.$$

The inflation rate since the base year is approximately 37 percent, or 31
percent in a continuous model.

## Question 3

The following notes apply to all data in Question 3 and Question 4.

* For each date range, the lower bound is inclusive and the upper bound is
  exclusive. For example, "1990–2000" denotes the period of 10 consecutive
  calendar years including 1990 and 1999 but excluding 2000.
* Growth rates are continuous and annualized.
* Although the time series begins in 1990, data from 1989 are used to compute
  the growth rate for 1990.
* The number of significant figures is determined by the data.
* The compounding frequency is annual with end-of-period aggregation.

### Question 3 Part A

We will use the CPI: All urban consumers ([CPIAUCSL](https://fred.stlouisfed.org/series/CPIAUCSL)) from the U.S. Bureau of Labor Statistics and the GDP deflator ([GDPDEF](https://fred.stlouisfed.org/series/GDPDEF/)) from the U.S. Bureau of Economic Analysis, both available from FRED, the Federal Reserve Bank of St. Louis.

### Question 3 Part B

__Annual growth rates of CPI and GDP deflator indices.__

| Variable | 1990–2000 | 2000–2010 | 2010–2020 | 2010–2025 | 2025 |
|----------|----------:|----------:|----------:|----------:|------|
| Growth rate of CPI: all urban consumers ([CPIAUCSL](https://fred.stlouisfed.org/series/CPIAUCSL)) | 2.901% | 2.528% | 1.739% | 4.113% | – |
| Growth rate of GDP deflator ([GDPDEF](https://fred.stlouisfed.org/series/GDPDEF/)) | 2.1359% | 2.1515% | 1.6317% | 3.7736% | – |

![Annual growth rates of CPI and GDP deflator indices](../images/problem-set-1-3.png "Annual growth rates of CPI and GDP deflator indices")

### Question 3 Part C
