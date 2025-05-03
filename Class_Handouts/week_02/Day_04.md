[comment]: render
[comment]: grid
# Section 5.4 Handout: Compound and Continuous Growth

## Introduction

In this section, we explore how compounding works at different intervals and how this leads to the concept of continuous compounding and the mathematical constant $e$.

We will:

- Build the compound interest formula step by step.
- Practice calculating compound interest with different compounding periods.
- Compare different compounding systems.
- Understand the limit of compounding frequency as it approaches continuous growth.
- Watch a Mathologer video to explore the origin of the number $e$.

---

## I. Building the Compound Interest Formula

### 1. Annual Compounding:
When interest is compounded once per year (annually), the formula is:

$$
A = P(1 + r)^t
$$

Where:

- $A$ is the amount of money accumulated after $t$ years, including interest.
- $P$ is the principal (the initial amount).
- $r$ is the annual interest rate (as a decimal).
- $t$ is the number of years.

### 2. More Frequent Compounding:
Interest is often compounded more than once per year—semiannually, quarterly, monthly, or even daily. When this happens:

- The annual interest rate $r$ is divided by $n$ (the number of compounding periods per year).
- Over $t$ years, the number of compounding periods is $n \times t$.

This leads to the compound interest formula:

$$
A = P\left(1 + \frac{r}{n}\right)^{nt}
$$

Using exponent rules, raising the growth factor to the power of $nt$ corresponds to applying the growth factor repeatedly for each compounding period.

\vspace{7cm}

## II. Compound Interest Practice

### Practice Problems:

1. You invest $\$1,000$ at 5% interest compounded:

   a. Annually for 10 years  
   b. Quarterly for 10 years  
   c. Monthly for 10 years  
   d. Daily for 10 years

2. A savings account offers 3.8% annual interest, compounded monthly. You deposit $\$2,500. How much will be in the account after 6 years?

3. A loan of $\$8,000$ grows at 6.25% compounded quarterly. How much is owed after 4 years?

4. Compare:

   - Bank A: 6.1% compounded quarterly
   - Bank B: 6.0% compounded daily
   
   Which one gives more after 8 years on a $\$10,000$ deposit?

5. If an investment doubles every 9 years, what is its approximate annual compound interest rate?

\vspace{15cm}

## III. Continuous Compounding and the Number $e$

We will watch the first 4 minutes of this video by Mathologer: [https://www.youtube.com/watch?v=-dhHrg-KbJ0](https://www.youtube.com/watch?v=-dhHrg-KbJ0)

While watching, pay attention to how compounding more frequently increases the total amount, but there is a limit to this process. That limit is described by the formula $A = P_0e^{rt}$, where $e$ represents the ultimate growth factor reached through continuous compounding.


As $n \to \infty$, the number of compounding periods becomes very large. In the limit, we define continuous compounding using the constant $e$, where:

$$
A = Pe^{rt}
$$

Here, $e \approx 2.71828$ is the base of natural exponential growth. It arises from the limit:

$$
\lim_{n \to \infty} \left(1 + \frac{1}{n}\right)^n = e
$$

### Mathologer Video:
We will watch this short video that explains where the number $e$ comes from using the example of 100% interest compounded continuously:
- [Mathologer: e as continuous compounding](https://www.youtube.com/watch?v=-dhHrg-KbJ0)

### Practice Problems:

6. How much will $\$1,000$ grow to after 10 years at 6% interest compounded continuously?

7. Compare the total growth of $\$5,000$ at 4.5%:
   - Compounded monthly for 20 years
   - Compounded continuously for 20 years

8. An investment of $\$700$ grows continuously at 3.2%. How much will it be worth after 10 years?

9. You are choosing between:

   - 5.8% compounded continuously
   - 6.0% compounded monthly
   
   Which is better over a 15-year period?

10. A bacteria population grows continuously at a rate of 22% per hour. Starting with 800 bacteria, how many will there be in 5 hours?

\vspace{12cm}

## IV. Challenge & Applications

11. A futuristic savings account offers 100% interest, compounded:

   - Once per year
   - Quarterly
   - Monthly
   - Daily
   - Continuously

   Compute the growth of $\$1,000$ for each method over 1 year.

12. A certificate of deposit offers two plans:

   - Plan A: 7% interest compounded monthly
   - Plan B: 6.9% compounded continuously

   Which gives a better return over 30 years?

13. A tumor grows exponentially. Its volume increases by 4% per day. Assuming continuous growth, how large will it be in 25 days if it starts at 2 cm$^3$?

14. Compare the effective annual rate (EAR) for:

   - 5.5% compounded quarterly
   - 5.3% compounded continuously

---

## Reflection:

- Why do we divide the annual rate $r$ when compounding more than once per year?
- How does the exponent $nt$ relate to the number of compounding periods?
- What happens to the compound interest formula as $n \to \infty$?
- Why is continuous compounding useful in biology, economics, and physics?
- What does the number $e$ represent in terms of growth?

