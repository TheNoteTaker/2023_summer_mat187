# Module 5 - Percent Change and Radicals with Higher Order Radicals

<!-- TOC -->
* [Module 5 - Percent Change and Radicals with Higher Order Radicals](#module-5---percent-change-and-radicals-with-higher-order-radicals)
* [General Notes](#general-notes)
* [Radical Expressions With Higher Roots](#radical-expressions-with-higher-roots)
  * [Radical Simplification Example One](#radical-simplification-example-one)
  * [Radical Simplification Example Two](#radical-simplification-example-two)
* [Percent Change](#percent-change)
  * [Patterns of Growth](#patterns-of-growth)
  * [Exponential Functions](#exponential-functions)
    * [Exponential Function Definition](#exponential-function-definition)
  * [Finding Change Factors](#finding-change-factors)
    * [Visual Guide to Find Change Factors](#visual-guide-to-find-change-factors)
  * [Percentage Change Versus Change Factor](#percentage-change-versus-change-factor)
  * [Exponential Growth and Decay](#exponential-growth-and-decay)
<!-- TOC -->

# General Notes

# Radical Expressions With Higher Roots

[![](assets/video_radical_expressions.png)](https://www.youtube.com/watch?v=iX7ivCww2ws)

When dealing with radicals, if you need to figure out what it is to a larger
degree, you can transform it by factoring it and then converting it to a
fractional power if needed.

---

## Radical Simplification Example One

![](assets/demon_radicals_001.png)

1. The radical was factored out
2. The factored-out radical was converted to a fractional power
3. The fractional power was simplified based on **2 &times; 3<sup><sup>1</sup>
   &frasl;<sub>3</sub></sup>** going into the factored-out form **5** times,
   leaving **2 <sup>5</sup>&radic;<span style="text-decoration:overline">
   3</span>**

---

## Radical Simplification Example Two

![](assets/demon_radicals_002.png)

- Both of the answers are valid and equivalent

---

# Percent Change

## Patterns of Growth

> - The phrase _"is increasing at a rate of 100 people per month"_ describes
    growth using an average rate of change.
> - The phrase "is increasing at 0.019% per year"_ describes growth as a percent
    change.

- The first one is a **linear function** because it has a _constant rate of
  change_.
- The second is an **exponential function** because it has a _constant
  percentage rate of change_.

Given the table:

Here's the given information converted into a markdown table:

| Years<br/>Since<br/>1971 | Number of <br/>Transistors<br/>T | First<br/>Differences<br/>&Delta;T | Second<br/>Differences<br/>&Delta;(&Delta;T) |
|:------------------------:|:--------------------------------:|:----------------------------------:|:--------------------------------------------:|
|            0             |               2300               |                2300                |                     2300                     |
|            2             |               4600               |                4600                |                     4600                     |
|            4             |               9200               |                9200                |                     9200                     |
|            6             |              18,400              |               18,400               |                    18,400                    |
|            8             |              36,800              |               36,800               |                                              |
|            10            |              73,600              |                                    |                                              |

- Neither the **first differences** nor the **second differences** are constant,
  so the growth is <u>neither linear nor quadratic</u>.

The next step is to calculate the ratio (quotient) instead of the first and
second difference:

| Years<br/>Since 1971<br/>x | Number of <br/>Transistors<br/>T<sub>x</sbu> | Ratio<br/><sup>T<sub>x</sub>+2</sup>&frasl;<sub>T<sub>x</sub> | 
|:--------------------------:|:--------------------------------------------:|:-------------------------------------------------------------:|
|             0              |                     2300                     |      **<sup>4600</sup>&frasl;<sub>2300</sub> &rarr; 2**       |
|             2              |                     4600                     |      **<sup>9200</sup>&frasl;<sub>4600</sub> &rarr; 2**       |
|             4              |                     9200                     |     **<sup>18,400</sup>&frasl;<sub>9200</sub> &rarr; 2**      |
|             6              |                    18,400                    |    **<sup>36,800</sup>&frasl;<sub>18,400</sub> &rarr; 2**     |
|             8              |                    36,800                    |    **<sup>73,600</sup>&frasl;<sub>36,800</sub> &rarr; 2**     |
|             10             |                    73,600                    |                                                               |

Assuming the same pattern continues, we can extrapolate the table further past
**10**

| Years<br/>Since 1971<br/>x | Number of <br/>Transistors<br/>T<sub>x</sbu> | Ratio<br/><sup>T<sub>x</sub>+2</sup>&frasl;<sub>T<sub>x</sub> |
|:--------------------------:|:--------------------------------------------:|:-------------------------------------------------------------:|
|             12             |                   147,200                    |   **<sup>294,400</sup>&frasl;<sub>147,200</sub> &rarr; 2**    |
|             14             |                   294,400                    |   **<sup>588,800</sup>&frasl;<sub>294,400</sub> &rarr; 2**    |
|             16             |                   588,800                    |                                                               |

## Exponential Functions

Using the table above, to interpolate, you need to create a function.
The following pattern can be found:

![](assets/func_exponential_001.png)

The function is: **&fnof;(x) = 2300(2<sup><sup>1</sup>&frasl;<sub>2</sub>
x</sup>)**

- **x** being the years after 1971.

![](assets/func_exponential_002.png)

To create the exponential function:

![](assets/func_exponential_003.png)

### Exponential Function Definition

![](assets/def_exponential_func_001.png)

## Finding Change Factors

Given: **y = ab<sup>x</sup>**

1. Calculate the ratio of the output values<br/>![](assets/demon_cf_001.png)
2. The rules of rational exponents state that **(x<sup>n</sup>)<sup><sup>1</sup>
   &frasl;<sub>n</sub></sup> = x**, so raise each side of the power of the
   inverse of the exponent, which is **<sup>1</sup>&frasl;<sub>x<sub>2</sub> -
   x<sub>1</sub></sub>** to solve for **b**:<br/>![](assets/demon_cf_002.png)
3. _Summarized:_ The change factor is the ratio of the outputs raised to **1**
   over the difference in the inputs.
4. Remember that:
    1. **b &times; b &times; b &times; b &times; b = b<sup>5</sup>**
    2. Assume **b<sup>5</sup> = 1.236**
    3. **<sup>5</sup>&radic;<span style="text-decoration:overline">b</span><sup>
       5</sup> = <sup>5</sup>&radic;<span style="text-decoration:overline">
       1.236</span>**
    4. **b = 1.043**

### Visual Guide to Find Change Factors

![](assets/def_cf_001.png)

## Percentage Change Versus Change Factor

![](assets/def_cf_vs_pc.png)

## Exponential Growth and Decay

![](assets/def_growth_and_decay.png)

- **r** is used for **growth** and **decay** percentages.
