# Problem Set 4

Ishan Pranav

May 8, 2025

Professor Pricila Maziero

ECON 11 Economics of Global Business

## Question 1: The Taylor Rule

> As a junior bond trader at Goldman Sachs, you have been asked by your boss to
> explain the Taylor Rule and how it can be a helpful guide to how the Federal
> Reserve sets monetary policy. Write a short report summarizing your findings.
> Your report should contain the following pieces of information:

We will use real gross domestic product
([GDPC1](https://fred.stlouisfed.org/series/GDPC1)) and personal consumption
expenditures, chain-type price index less food and energy
([JCXFE](https://fred.stlouisfed.org/series/JCXFE)) from the U.S. Bureau of
Economic Analysis. We will also use real potential gross domestic product
([GDPPOT](https://fred.stlouisfed.org/series/GDPPOT)) from the U.S.
Congressional Budget Office. Finally, we will use the federal funds effective
rate ([FEDFUNDS](https://fred.stlouisfed.org/series/FEDFUNDS))
from the Board of Governors of the Federal Reserve System. All are available
from FRED, the Federal Reserve Bank of St. Louis.

__The Taylor rule and the federal funds (1971–2025).__

![The Taylor rule and the federal funds rate over time.](https://github.com/ishanpranav/econ-11-economics-of-global-business/blob/master/images/problem-set-4-1.png?raw=true "The Taylor rule and the federal funds rate over time")

__Model.__

We use the Taylor rule to estimate the nominal interest rate over time,
comparing it to the actual federal funds rate:

$$i_t=r^{\ast}+\pi_t+a_1(\pi_t-\pi^{\ast})+a_2(y_t-y_t^{\ast}).$$

* Let $i_t$ represent the short-term nominal inflation rate in period $t$, as
  estimated by the Taylor rule;
* let $r^{\ast}*$ be the long-term real interest rate (we assume
  $r^{\ast}=2\%$);
* let $\pi_t$ be the inflation rate in period $t$;
* let $a_1$ be the sensitivity of the interest rate to inflation (we assume
  $a_1=0.5$);
* let $\pi^{\ast}$ be the target inflation rate (we assume $\pi^{\ast}=2\%$);
* let $a_2$ be the sensitivity of the interest rate to output (we assume
  $a_2=0.5$);
* let $y_t$ be the real output (logarithmic) in period $t$;
* and let $y_t^{\ast}$ be the potential real output (logarithmic).

 __Interpretation.__

* During the 1970s, the American economy experienced major inflationary
  pressures. Over this period, the federal funds rate was lower than the
  interest rate estimated by the Taylor rule.
  * This suggests that, despite already-high nominal interest rates, the Federal
    Reserve should have gone further.
  * Even so, it is possible that the target inflation level was different than
    the 2-percent figure used in our model, or that the Taylor rule is not able
    to explain Federal Reserve behavior during this early crisis period.

