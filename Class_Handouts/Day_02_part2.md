[comment]: render
# Section 5.3 – Exponential Equations and Doubling Time  
**Guided Notes**



## I. Building the Doubling Time Formula Step-by-Step

### Scenario:  
Bill invests \$500 in an account that doubles every 15 years.  
We want to find out how much money he will have in:

- 15 years  
- 30 years  
- 45 years



### Step 1: Think in Terms of Doubling  
If the account **doubles every 15 years**, then:

- After 15 years: it has doubled **once**
- After 30 years: it has doubled **twice**
- After 45 years: it has doubled **three times**



### Step 2: Use the Number of Doublings to Write Expressions

Let’s write an expression for each situation using just the numbers:  
**500, 2, 15, and the number of years**.

#### a) After 15 years:

One doubling:  

<br><br><br>

$A = \underline{\hspace{1.5cm}} \cdot \underline{\hspace{1.5cm}}^{\underline{\hspace{1.5cm}}}$  
→ $A = \underline{\hspace{1.5cm}}$

Also written using the time and doubling period:  

<br><br><br>

$A = \underline{\hspace{1.5cm}} \cdot \underline{\hspace{1.5cm}}^{\frac{\underline{\hspace{1.5cm}}}{\underline{\hspace{1.5cm}}}}$


#### b) After 30 years:

Two doublings:  

<br><br><br>

$A = \underline{\hspace{1.5cm}} \cdot \underline{\hspace{1.5cm}}^{\underline{\hspace{1.5cm}}}$  
→ $A = \underline{\hspace{1.5cm}}$

Also written using the time and doubling period:  

<br><br><br>

$A = \underline{\hspace{1.5cm}} \cdot \underline{\hspace{1.5cm}}^{\frac{\underline{\hspace{1.5cm}}}{\underline{\hspace{1.5cm}}}}$


#### c) After 45 years:

Three doublings:  

<br><br><br>

$A = \underline{\hspace{1.5cm}} \cdot \underline{\hspace{1.5cm}}^{\underline{\hspace{1.5cm}}}$  
→ $A = \underline{\hspace{1.5cm}}$

Also written using the time and doubling period:  

\vspace{2in}

$A = \underline{\hspace{1.5cm}} \cdot \underline{\hspace{1.5cm}}^{\frac{\underline{\hspace{1.5cm}}}{\underline{\hspace{1.5cm}}}}$


### Step 3: Write a General Equation

Let $t$ represent the number of years.  
Since the number of doublings is $\dfrac{t}{15}$, the general equation is:

$$
A =
$$

This is the **doubling time version** of an exponential function.

## II. Connecting to the Standard Exponential Equation

The **standard exponential growth equation** is:

$$
A = A_0(1 + r)^t
$$

We can rewrite the doubling time version in the same form.

Start with:  
$A = 500 \cdot 2^{t/15}$

Use the exponent rule:  
$a^{m/n} = (a^{1/n})^m$

So:
$$
A = 500 \cdot \left(2^{1/15}\right)^t
$$

Now compare:
- $A_0 = 500$
- $b = 2^{1/15}$  
This is your **effective growth factor per year**.

Thus, the doubling-time formula is just a special version of the standard exponential form.


## III. Practice

1. Jack invests \$800 in an account that doubles every 12 years.  
   a) Write an expression for how much he’ll have in 12, 24, and 36 years.  
   b) Write a general equation for $t$ years.

2. If $A = 1200 \cdot 2^{t/10}$,  
   a) How much is in the account after 10, 20, and 25 years?  
   b) Rewrite this equation in the form $A = A_0 b^t$.  
   What is the value of $b$?

3. Suppose a population doubles every 18 years.  
   a) Write an equation for the population $P$ after $t$ years if the current population is 1500.  
   b) What is the population after 54 years?  
   c) What is the annual growth factor (base $b$) in this case?


## IV. Reflection

- Why is it helpful to express exponential growth in terms of doubling time?

> _________________________________________________________________

- What is the advantage of expressing an exponential equation as $A = A_0 b^t$?

> _________________________________________________________________

- How can we use exponent rules to move between different forms of the same exponential equation?

> _________________________________________________________________

