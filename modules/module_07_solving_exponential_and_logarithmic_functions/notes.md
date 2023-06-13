# Module 7 - Solving Exponential and Logarithmic Functions

<!-- TOC -->
* [Module 7 - Solving Exponential and Logarithmic Functions](#module-7---solving-exponential-and-logarithmic-functions)
* [General Notes](#general-notes)
  * [Change of Base Formula Video](#change-of-base-formula-video)
* [Logarithms](#logarithms)
* [Logarithmic Functions](#logarithmic-functions)
  * [Properties of Exponents](#properties-of-exponents)
  * [Examples of Logarithmic Functions](#examples-of-logarithmic-functions)
* [Rules of Logarithms](#rules-of-logarithms)
  * [More Examples of Logarithmic Functions](#more-examples-of-logarithmic-functions)
    * [Logarithmic Function 1](#logarithmic-function-1)
    * [Logarithmic Function 2](#logarithmic-function-2)
  * [Generalized Rules for Logarithmic Functions](#generalized-rules-for-logarithmic-functions)
    * [Logarithm Rule One](#logarithm-rule-one)
      * [Examples for Rule One](#examples-for-rule-one)
    * [Logarithm Rule Two](#logarithm-rule-two)
    * [Logarithm Rule Three](#logarithm-rule-three)
      * [Examples for Rule Three](#examples-for-rule-three)
    * [Logarithm Rule Four](#logarithm-rule-four)
      * [Examples for Rule Four](#examples-for-rule-four)
    * [Logarithm Rule Five](#logarithm-rule-five)
      * [Examples for Rule Five](#examples-for-rule-five)
    * [All Rules of Logarithms](#all-rules-of-logarithms)
* [Solving an Exponential Equation Using Logarithms](#solving-an-exponential-equation-using-logarithms)
* [Common and Natural Logarithms](#common-and-natural-logarithms)
  * [Change of Base Formula](#change-of-base-formula)
* [Solving an Exponential Equation](#solving-an-exponential-equation)
* [Common Errors with Logarithms](#common-errors-with-logarithms)
<!-- TOC -->

# General Notes

## Change of Base Formula Video

[![](assets/video_change_of_base_001.png)](https://www.youtube.com/watch?v=OkFdDqW9xxM)

# Logarithms

Given the table and matching graph:

![](assets/graph_log_001.png)

| Years Since<br/>2005<br/>t | Population<br/>(in millions)<br/>p(t) |
|----------------------------|---------------------------------------|
| 0                          | 141.8                                 |
| 10                         | 169.5                                 |
| 20                         | 202.6                                 |
| 30                         | 242.2                                 |
| 40                         | 289.5                                 |
| 50                         | 346.0                                 |

Assuming you want to find the year that the population will equal 250 million,
you need to find the inverse of the exponential function
that models the above table:<br/>**p(t) = 141.8(1.018)<sup>t</sup>**.

If you have a table, one method is to flip the values _(if you don't want to
solve algebraically)_:

![](assets/graph_log_002.png)

| Population<br/>(in millions)<br/>p(t) | Years Since<br/>2005<br/>t |
|---------------------------------------|----------------------------|
| 141.8                                 | 0                          |
| 169.5                                 | 10                         |
| 202.6                                 | 20                         |
| 242.2                                 | 30                         |
| 289.5                                 | 40                         |
| 346.0                                 | 50                         |

You can then visually identify when the population will be 250 million, but it
is best to algebraically solve for the inverse function:

1. **p(t) = 141.8(1.018)<sup>t</sup>**
2. **250 = 141.8(1.018)<sup>t</sup>**
3. **<sup>250</sup>&frasl;<sub>141.8</sub> = (1.018)<sup>t</sup>**
4. **1.763 = (1.018)<sup>t</sup>**
5. Convert to logarithm:
    1. **t** is the exponent that goes on **1.018** to get to 1.763
    2. Using this logic, **t = log<sub>1.018</sub>(1.763)**
6. This is read as **"t equals log base 1.018 of 1.763"**
7. **t &approx; 31.785**
8. **1.018<sup>31.785</sup> &approx; 1.763**

# Logarithmic Functions

- **log** is short for **logarithm**
- **y = log<sub>b</sub>(x)**
    - Ways to think of it:
        - **_"y equals log base b of x"_**
        - **_"y is the exponent we place on b to get x"_**
        - **_"What exponent on b is necessary to get x?"_**
        - **y** is the number that makes the equation **b<sup>y</sup> = x**
          true.

![](assets/def_log_001.png)

- A logarithmic function is the inverse of an exponential function
    - So if **x** is the independent variable and **y** is the dependent
      variable for a _**logarithmic function**_, then **y** is the independent
      variable and **x** is the dependent variable for the
      _**exponential function**_.

![](assets/def_log_002.png)

## Properties of Exponents

![](assets/def_log_003.png)

## Examples of Logarithmic Functions

1. Given **y = log<sub>3</sub>(81)** &rarr; **y = 4** because **3<sup>4</sup> =
   81**
2. Given **y = log<sub>4</sub>(5)** &rarr; **y is between 2 and 3** because
   **4<sup>2</sup> = 16** and **4<sup>3</sup> = 64**

# Rules of Logarithms

1. **Logarithms are exponents**
    - The rules of logarithms come from the properties of exponents
2. **Any number may be written as an exponential of any base**
    - Consider that both **3<sup>4</sup>** and **9<sup>2</sup>** equal 81
        - Either number may be substituted in any equation or formula that
          contains the number **81**.

## More Examples of Logarithmic Functions

### Logarithmic Function 1

Given **y = log<sub>3</sub>(81)** &rarr; **y = 4** because
**3<sup>4</sup> = 81**

Another way to write this is: **y = log<sub>3</sub>(3<sup>4</sup>)**

- Now the question is **"What exponent on 3 is necessary to get
  3<sup>4</sup>?"**, which is the obvious answer of **4**.

### Logarithmic Function 2

Given **y = log<sub>9</sub>(81)** &rarr; **y = 2**
because **9<sup>2</sup> = 81**

Another way to write this is: **y = log<sub>9</sub>(9<sup>2</sup>)**

- Now the question is **"What exponent on 9 is necessary to get
  9<sup>2</sup>?"**, which is the obvious answer of **2**.

## Generalized Rules for Logarithmic Functions

### Logarithm Rule One

> **log<sub>b</sub>(b<sup>m</sup>) = m**

From rule one, there are two things that are true:

1. **log<sub>b</sub>1 = 0**
2. **log<sub>b</sub>b = 1**

Because **b<sup>0</sup> = 1** when **b > 0** and **b<sup>1</sup> = b** for all
values:

- **log<sub>b</sub>(b<sup>m</sup>) = m**
- **log<sub>b</sub>(b<sup>0</sup>) = 0**
- **log<sub>b</sub>(1) = 0**

#### Examples for Rule One

Given:

1. **y = log<sub>100</sub>(0.01)**
    1. **= log<sub>100</sub>(<sup>1</sup>&frasl;<sub>100</sub>)**
        - Since **0.01 = <sup>1</sup>&frasl;<sub>100</sub>**
    2. **= log<sub>100</sub>(100<sup>-1</sup>)**
        - Since **<sup>1</sup>&frasl;<sub>x<sup>n</sup></sub> = x<sup>
          &minus;n</sup>**
    3. **= -1**
        - Log Rule 1
2. **y = log<sub>2</sub>(0.25)**
    1. **= log<sub>2</sub>(<sup>1</sup>&frasl;<sub>4</sub>)**
        - Since **0.25 = <sup>1</sup>&frasl;<sub>4</sub>**
    2. **= log<sub>2</sub>(<sup>1</sup>&frasl;<sub>2<sup>2</sup></sub>)**
        - Since **4 = 2<sup>2</sup>**
    3. **= log<sub>2</sub>(2<sup>-2</sup>)**
        - Since **<sup>1</sup>&frasl;<sub>x<sup>n</sup></sub> = x<sup>
          &minus;n</sup>**
    4. **= -2**
        - Log Rule 1

### Logarithm Rule Two

> **b<sup>log<sub>b</sub>(m)</sup> = m**

- **b<sup>y</sup> = m**
- **b<sup>log<sub>b</sub>(m)</sup> = m**    _&larr; since y = log<sub>b</sub>(
  m)_

### Logarithm Rule Three

> **log<sub>b</sub>(mn) = log<sub>b</sub>(m) + log<sub>b</sub>(n)**

#### Examples for Rule Three

Given:

1. **y = log<sub>2</sub>(16 * 64)**  _&larr; Method 1_
    1. **= log<sub>2</sub>(1024)**   _&larr; Multiply 16 * 24_
    2. **= log<sub>2</sub>(2<sup>10</sup>)**   _&larr; Substitute 2<sup>10</sup>
       for 1024._
    3. **= 10**   _&larr; Log Rule 1_
2. **y = log<sub>2</sub>(16 * 64)**    &larr; Method 2
    1. **= log<sub>2</sub>(2<sup>4</sup> * 2<sup>6</sup>)**   _&larr; Substitute
       2<sup>4</sup> for 16 and 2<sup>6</sup> for 64_
    2. **= log<sub>2</sub>(2<sup>4 + 6</sup>)**   _&larr; Exponent property 2:
       **x<sup>a</sup> * x<sup>b</sup> = x<sup>a + b</sup>**_
    3. **= 4 + 6**   _&larr; Log Rule 1_

Before adding the numbers, consider where the numbers **4** and **6** came from:

1. **4** came from **2<sup>4</sup> = 16** &rarr; so, **4 = log<sub>2</sub>(16)**
2. **6** came from **2<sup>6</sup> = 64** &rarr; so, **6 = log<sub>2</sub>(64)**
3. In other words: **log<sub>2</sub>(16 * 64) = log<sub>2</sub>(16) +
   log<sub>2</sub>(64)** &rarr; **6 + 4 = 10**

To generalize this:

1. **y = log<sub>b</sub>(m * n)**
2. **b<sup>y</sup> = m * n**    &larr; _Relationship between logs and
   exponentials_
3. **b<sup>y</sup> = (b<sup>log<sub>b</sub>m</sup>)(b<sup>log<sub>b</sub>
   n</sup>)**    &larr; _Log Rule 2_
4. **b<sup>y</sup> = (b<sup>log<sub>b</sub>m + log<sub>b</sub>n</sup>)**
   &larr; _Exponent
   Property: **x<sup>a</sup> * x<sup>b</sup> = x<sup>a + b</sup>**_
5. **y = log<sub>b</sub>(m) + log<sub>b</sub>(n)**    &larr; _Equal exponentials
   with same bases have equal exponents._

### Logarithm Rule Four

> **log<sub>b</sub>(<sup>m</sup>&frasl;<sub>n</sub>) = log<sub>b</sub>(m)
&minus; log<sub>b</sub>(n)**

#### Examples for Rule Four

Given:

> **y = log<sub>2</sub>(<sup>64</sup>&frasl;<sub>16</sub>)**

- Although you could divide them, it is easier to rewrite them as exponents.

To solve:

1. **y = log<sub>2</sub>(<sup>64</sup>&frasl;<sub>16</sub>)**
2. **=
   log<sub>2</sub>(<sup>2<sup>6</sup></sup>&frasl;<sub>2<sup>4</sup></sub>)**
3. **= log<sub>2</sub>(2<sup>6</sup> * 2<sup>&minus;4</sup>)**
4. **= log<sub>2</sub>(2<sup>6</sup>) + log<sub>2</sub>(2<sup>&minus; 4</sup>)**
   &larr; _Log Rule 3_
5. **= log<sub>2</sub>(2<sup>6</sup>) + (&minus;4)**    &larr; _Log Rule 1_
6. **= log<sub>2</sub>(2<sup>6</sup>) &minus; (4)**
7. **= log<sub>2</sub>(2<sup>6</sup>) - log<sub>2</sub>(2<sup>4</sup>)**
   &larr; _Log Rule 1_

The important part to remember is that:

> **log<sub>2</sub>(<sup>2<sup>6</sup></sup>&frasl;<sub>2<sup>4</sup></sub>)**
> is equal to **log<sub>2</sub>(2<sup>6</sup>) &minus; log<sub>2</sub>(2<sup>
4</sup>)**

### Logarithm Rule Five

> **log<sub>b</sub>(m<sup>n</sup>) = n log<sub>b</sub>(m)**

#### Examples for Rule Five

Given:

> **log<sub>3</sub>(8<sup>5</sup>)**

1. **log<sub>3</sub>(8<sup>5</sup>)** &rarr; **log<sub>3</sub>(8 * 8 * 8 * 8 *
   8)**
2. **log<sub>3</sub>(8) + log<sub>3</sub>(8) + log<sub>3</sub>(8) + log<sub>
   3</sub>(8) + log<sub>3</sub>(8)** &larr; _Log Rule 3_
3. **5 log<sub>3</sub>(8)** &larr; _There are **5 log<sub>3</sub>8** terms_

### All Rules of Logarithms

![](assets/def_log_rules_001.png)

# Solving an Exponential Equation Using Logarithms

The problem:

> _"The total annual health-related costs in the United States in billions of
> dollars may be modeled by the function **H(t) = 30.917(1.1013)<sup>t</sup>**,
> where t is the number of years since 1960. (Source: Statistical Abstract of
> the United States, 2007, Table 120) According to the model, when will
> health-related costs in the United States reach 250 billion dollars?"_

The solution:

![](assets/fun_log_002.png)

# Common and Natural Logarithms

![](assets/def_com_nat_log_001.png)

## Change of Base Formula

It is also possible to change the _base_ of any logarithm to make it a common or
natural logarithm:

![](assets/def_change_of_base_001.png)

# Solving an Exponential Equation

The problem:

> _"The populations of India, I, and China, C (in thousands), can be modeled
using the functions **I(t) = 1,103,371(1.015)<sup>t</sup>**
and **C(t) = 1,323,345(1.007)<sup>t</sup>**, where t is in years since 2005.
According to these models, when will the populations of the two countries be
equal?"_

The solution:

![](assets/fun_log_003.png)

# Common Errors with Logarithms

![](assets/def_log_errors_001.png)