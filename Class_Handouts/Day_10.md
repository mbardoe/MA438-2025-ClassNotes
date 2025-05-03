[comment]: render
[comment]: grid
# Lesson: Solving Exponential Equations and Understanding Change of Base

## Part I: The Power of Logarithms — A Conceptual Bridge

To solve exponential equations, we often need to "undo" the exponent. Just as square roots undo squaring, **logarithms** undo exponentials. But what if our exponent involves a base like 2, and we only have access to a calculator that understands base 10 (common logs) or $e$ (natural logs)?

That’s where the **Change of Base Formula** comes in.

### Change of Base Formula

$$
\log_b(x) = \frac{\log_a(x)}{\log_a(b)}
$$

This lets you compute logarithms in any base using a base you’re familiar with (like 10 or $e$).

---

## Part II: Conceptual Analogy — Currency Exchange

Imagine you're traveling and your calculator only understands **Euros**, but you want to convert **100 US dollars** into **Japanese Yen**.

1. You find out that 100 USD is 90.91 Euros.
2. You also know that 1 Yen is 0.137 Euros.
3. To convert 100 USD into Yen:

$$
\frac{\text{\hspace{3cm} Euros}}{\text{\hspace{3cm} Euros per Yen}} \approx \text{\hspace{3cm} Yen}
$$

You used Euros as a **bridge** to get from dollars to yen.

Now apply that logic to logarithms:

- $\log_{10}(100) = 2$ (How many 10s make 100?)
- $\log_{10}(2) = 0.3010$ (How many 10s make 2?)

So:

$$
\log_2(100) = \frac{\log_{10}(100)}{\log_{10}(2)} = \frac{2}{0.3010} \approx 6.644
$$

Just like converting currencies, you're converting between number systems using a bridge you understand.

---

## Part III: Solving Exponential Equations with Logs

Solve for $x$ in each case. Use the change of base formula when needed.

1. $2^x = 17$

\vspace{3cm}

2. $5^{2x - 1} = 100$

\vspace{3cm}

3. $10^x = 0.002$

\vspace{3cm}

4. $e^{3x} = 50$

\vspace{3cm}

5. $4^{x+2} = 35$

\vspace{3cm}

6. $7^x = 2 \cdot 3^x$

\vspace{3cm}


### More Challenging Examples (Use Algebra + Logs)

7. $2^{x^2 - 5x + 6} = 1$

\vspace{3cm}

8. $3^{x^2 - 4} = 27$

\vspace{3cm}

9. $e^{x^2 + 3x} = e^4$

\vspace{3cm}


10. $5^{x^2 - x} = 25$

\vspace{3cm}



---

## Part IV: Word Problems – Exponential Growth and Decay

Use what you know about exponential functions to solve these.

### A. Growth and Decay

7. A population of bacteria doubles every 4 hours. If the population starts at 500, how long will it take before the 
population is 1 million?

\vspace{3cm}


8. A radioactive isotope decays by 8% each hour. If there are 100 grams at first, how many hours before there is 1 gram?

\vspace{3cm}


### B. Compound and Continuous Growth

9. An investment of $\$1,000$ earns 5% interest compounded annually. How long before the investment is worth $\$10,000$?

\vspace{3cm}


10. Another account earns 4.8% interest **compounded continuously**. How long will it take for the investment to be worth $\$12,000$?

\vspace{3cm}


11. Which investment (problem 9 or 10) is better in the long run?

\vspace{3cm}


### C. Half-Life and Doubling Time

12. A virus has a doubling time of 3 hours. How long before the virus population has been multiplied by 10?

\vspace{3cm}


13. A substance has a half-life of 24 days. How long will it take for substance has had its mass cut by a factor of 3?

\vspace{3cm}


---

## Part V: Reflection

- Why is the change of base formula useful?

\vspace{3cm}


- What connections can you see between logs and exponents?

\vspace{3cm}


- How does thinking in terms of "currency conversion" help you understand how and why we switch bases?

