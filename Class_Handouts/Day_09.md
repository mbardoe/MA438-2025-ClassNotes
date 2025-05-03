[comment]: render
[comment]: grid
# Guided Notes: Logarithmic Functions and the Laws of Logarithms

## Part I: Characteristics of Logarithmic Functions

A logarithmic function is the inverse of an exponential function. The general form is:

$$
f(x) = \log_b(x)
$$

Where:

- $b$ is the **base** and must be greater than 0 and not equal to 1

- $x$ is the **input**, and must be greater than 0

### Domain and Range

- **Domain:** $(0, \infty)$ (we can only take logs of positive numbers)

- **Range:** $(-\infty, \infty)$

**Compare the domain and range to $f(x)=b^x$**

\vspace{3cm}

### Graph Characteristics
 
- Passes through the point $(1, 0)$ for all bases $b$

- Vertical asymptote at $x = 0$

- Increasing for $b > 1$, decreasing for $0 < b < 1$

**Compare these characteristics to $f(x)=b^x$**

\vspace{3cm}

### Natural Logarithm
The natural logarithm uses the base $e$ (approximately 2.718):

$$
\ln(x) = \log_e(x)
$$

It has the same domain and range as other logarithms and is especially important in calculus and science.

### Log base 10 is the standard

Because we often use log base 10 (because we are often interested in our decimal system). $\log_{10}$ is often more simply
written as $\log$. 

One easy way to think about logs is that, at least for log base 10, it roughly tells you how many digits a number is (if you round up).

For example,

- $\log_{10}(200)=2.30$
- $\log_{10}(3451)=3.54$
- $\log_{10}(4324254)=6.64$

### Comparing Graphs of Different Bases
- $\log_2(x)$ grows more quickly than $\ln(x)$, which grows more quickly than $\log_{10}(x)$
- The larger the base, the more gradually the curve rises

---

## Part II: Understanding Logarithms with Exponents

Remember: the logarithm tells us **how many copies of the base** must be multiplied to reach a certain number.

For example:

- $\log_2(8) = 3$ because $2 \cdot 2 \cdot 2 = 8$

- $\log_5(25) = 2$ because $5^2 = 25$

- $\log_9(3) = \dfrac{1}{2}$ because $\sqrt{9}=3$ and square root is the one-half power

Logarithms are the inverse of exponentials:

- $\log_b(b^x) = x$

- $b^{\log_b(x)} = x$

---

## Part III: Laws of Logarithms

The laws of logarithms come from the laws of exponents:

1. **Product Rule**  
   $$\log_b(MN) = \log_b(M) + \log_b(N)$$
   (Multiplying inside the log becomes addition outside)

2. **Quotient Rule**  
   $$\log_b\left(\frac{M}{N}\right) = \log_b(M) - \log_b(N)$$
   (Dividing inside the log becomes subtraction outside)

3. **Power Rule**  
   $$\log_b(M^p) = p \cdot \log_b(M)$$
   (An exponent inside the log becomes multiplication outside)

These are similar to the laws of exponents:

- $b^m \cdot b^n = b^{m+n}$ (Multiplying _______ the log becomes addition _______)

- $\frac{b^m}{b^n} = b^{m-n}$ (Dividing _________ the log becomes subtraction ________)

- $(b^m)^n = b^{mn}$ (An exponent ________ the log becomes multiplication _________)

---

## Part IV: Practice Problems

### A. Expand the Logarithmic Expression
Write each as a sum/difference of logs:

1. $\log_2(8x)$
2. $\log_5\left(\frac{x^3}{25}\right)$
3. $\ln(\sqrt{x}y)$
4. $\log_3 \left(\frac{27x^2}{y^6} \right)$
5. $\log_{10}(x^2y^3)$

### B. Combine the Logarithmic Expression
Write each as a single logarithm:

6. $\log_2(x) + \log_2(4)$
7. $\log_7(a) - \log_7(b)$
8. $2\ln(x) + \ln(3)$
9. $3\log_5(x) - \log_5(2)$
10. $\ln(x) + \ln(y) - \ln(z)$

### C. Mixed Logarithmic and Exponential Expressions

11. $\log_3(3^x)$
12. $2^{\log_2(x)}$
13. $\ln(e^5)$
14. $e^{\ln(2x-3)}$
15. $10^{\log_{10}(7x)}$

---

## Part V: Reflection

- What does a logarithm really measure?

- Why do the log laws work the way they do?

- How are the log laws connected to the exponent laws?

- How is $\log_b(b^x)$ related to the inverse nature of the functions?
