---
title: Chemical Kinetics | Questions Based on Arrhenius Equation
description: In this article, we will solve some questions related to the Arrhenius equation, activation energy and the effect of temperature on rate constant.
---

# [![ChemistryEdu Logo](../../images/favicon.svg){ align=left, width=3.8% }](../../index.md)  Chemical Kinetics | Questions Based on Arrhenius Equation

In this article, we will solve some questions related to the Arrhenius equation, activation energy and the effect of temperature on rate constant.

!!! tip "Formulas used"

    $$k = A\ e^{-E_a/RT}$$

    $$log\ k = log\ A - {E_a \over 2.303RT}$$

    $$log{k_2 \over k_1} = {E_a \over 2.303R}\left[{T_2 - T_1 \over T_1T_2}\right]$$

    $$R = 8.314\ J\ K^{-1}mol^{-1}$$

## Questions

!!! question "The rate constant for the decomposition of N<sub>2</sub>O<sub>5</sub> at various temperatures is given below: <br>T/&deg;C: 0, 20, 40, 60, 80 <br>10<sup>5</sup> &times; k/s<sup>-1</sup>: 0.0787, 1.70, 25.7, 178, 2140 <br>Draw a graph between ln k and 1/T and calculate the values of A and E<sub>a</sub>. Predict the rate constant at 30&deg; and 50&deg;C."

    * Converting the data:

    T/K | 273 | 293 | 313 | 333 | 353
    ----|-----|-----|-----|-----|----
    10<sup>3</sup>/T (K<sup>-1</sup>) | 3.663 | 3.413 | 3.195 | 3.003 | 2.833
    ln k | -14.06 | -10.98 | -8.27 | -6.33 | -3.84

    * The plot of ln k against 1/T is a straight line. Its slope (from the best fit line) is:

    $$Slope = -{E_a \over R} = -1.21 \times 10^4\ K$$

    $$E_a = 1.21 \times 10^4 \times 8.314 = 1.006 \times 10^5\ J\ mol^{-1} &asymp; 100.6\ kJ\ mol^{-1}$$

    * The intercept of the line gives ln A:

    $$ln\ A = 30.29$$

    $$A = 1.43 \times 10^{13}\ s^{-1}$$

    * Rate constant at 30 &deg;C (303 K):

    $$ln\ k = 30.29 - {1.21 \times 10^4 \over 303} = -9.65$$

    $$k &asymp; 6.4 \times 10^{-5}\ s^{-1}$$

    * Rate constant at 50 &deg;C (323 K):

    $$ln\ k = 30.29 - {1.21 \times 10^4 \over 323} = -7.18$$

    $$k &asymp; 7.6 \times 10^{-4}\ s^{-1}$$

    Values read from a hand-drawn graph may differ slightly.

!!! question "The rate constant for the decomposition of hydrocarbons is 2.418 &times; 10<sup>-5</sup> s<sup>-1</sup> at 546 K. If the energy of activation is 179.9 kJ/mol, what will be the value of pre-exponential factor?"

    $$log\ A = log\ k + {E_a \over 2.303RT}$$

    $$log\ A = log(2.418 \times 10^{-5}) + {179900 \over 2.303 \times 8.314 \times 546}$$

    $$log\ A = -4.6166 + 17.2082 = 12.5916$$

    $$A = 3.9 \times 10^{12}\ s^{-1}$$

!!! question "The decomposition of hydrocarbon follows the equation k = (4.5 &times; 10<sup>11</sup> s<sup>-1</sup>) e<sup>-28000 K/T</sup>. Calculate E<sub>a</sub>."

    * Comparing with the Arrhenius equation k = Ae<sup>-E<sub>a</sub>/RT</sup>:

    $${E_a \over R} = 28000\ K$$

    $$E_a = 28000 \times 8.314 = 232792\ J\ mol^{-1}$$

    $$E_a = 232.8\ kJ\ mol^{-1}$$

!!! question "The rate constant for the first order decomposition of H<sub>2</sub>O<sub>2</sub> is given by the following equation: log k = 14.34 - 1.25 &times; 10<sup>4</sup> K/T. Calculate E<sub>a</sub> for this reaction and at what temperature will its half-period be 256 minutes?"

    * Comparing with log k = log A - E<sub>a</sub>/(2.303RT):

    $${E_a \over 2.303R} = 1.25 \times 10^4\ K$$

    $$E_a = 1.25 \times 10^4 \times 2.303 \times 8.314 = 239339\ J\ mol^{-1}$$

    $$E_a = 239.3\ kJ\ mol^{-1}$$

    * When t<sub>1/2</sub> = 256 min:

    $$k = {0.693 \over 256 \times 60\ s} = 4.51 \times 10^{-5}\ s^{-1}$$

    $$log\ k = log(4.51 \times 10^{-5}) = -4.346$$

    $$-4.346 = 14.34 - {1.25 \times 10^4 \over T}$$

    $$T = {1.25 \times 10^4 \over 18.686} = 669\ K$$

!!! question "The decomposition of A into product has value of k as 4.5 &times; 10<sup>3</sup> s<sup>-1</sup> at 10&deg;C and energy of activation 60 kJ mol<sup>-1</sup>. At what temperature would k be 1.5 &times; 10<sup>4</sup> s<sup>-1</sup>?"

    $$k_1 = 4.5 \times 10^3\ s^{-1},\ T_1 = 283\ K,\ k_2 = 1.5 \times 10^4\ s^{-1},\ E_a = 60000\ J\ mol^{-1}$$

    $$log{k_2 \over k_1} = {E_a \over 2.303R}\left[{1 \over T_1} - {1 \over T_2}\right]$$

    $$log{1.5 \times 10^4 \over 4.5 \times 10^3} = {60000 \over 2.303 \times 8.314}\left[{1 \over 283} - {1 \over T_2}\right]$$

    $$0.5229 = 3133.6\left[{1 \over 283} - {1 \over T_2}\right]$$

    $${1 \over T_2} = 3.5336 \times 10^{-3} - 1.6686 \times 10^{-4} = 3.3667 \times 10^{-3}$$

    $$T_2 = 297\ K = 24\ &deg;C$$

!!! question "The time required for 10% completion of a first order reaction at 298 K is equal to that required for its 25% completion at 308 K. If the value of A is 4 &times; 10<sup>10</sup> s<sup>-1</sup>, calculate k at 318 K and E<sub>a</sub>."

    * For a first order reaction, t = (2.303/k) log([R]<sub>0</sub>/[R]).

    $$At\ 298\ K:\ t = {2.303 \over k_{298}} log{100 \over 90}$$

    $$At\ 308\ K:\ t = {2.303 \over k_{308}} log{100 \over 75}$$

    * Since the times are equal:

    $${k_{308} \over k_{298}} = {log(100/75) \over log(100/90)} = {0.1249 \over 0.0458} = 2.73$$

    * Calculation of E<sub>a</sub>:

    $$log\ 2.73 = {E_a \over 2.303 \times 8.314}\left[{308 - 298 \over 298 \times 308}\right]$$

    $$E_a = {2.303 \times 8.314 \times 0.4362 \times 298 \times 308 \over 10}$$

    $$E_a = 76664\ J\ mol^{-1} &asymp; 76.7\ kJ\ mol^{-1}$$

    * Calculation of k at 318 K:

    $$log\ k = log\ A - {E_a \over 2.303RT} = log(4 \times 10^{10}) - {76664 \over 2.303 \times 8.314 \times 318}$$

    $$log\ k = 10.602 - 12.591 = -1.989$$

    $$k = 1.02 \times 10^{-2}\ s^{-1}$$

!!! question "The rate of a reaction quadruples when the temperature changes from 293 K to 313 K. Calculate the energy of activation of the reaction assuming that it does not change with temperature."

    $${k_2 \over k_1} = 4,\ T_1 = 293\ K,\ T_2 = 313\ K$$

    $$log\ 4 = {E_a \over 2.303 \times 8.314}\left[{313 - 293 \over 293 \times 313}\right]$$

    $$0.6021 = {E_a \over 19.147} \times 2.181 \times 10^{-4}$$

    $$E_a = 52860\ J\ mol^{-1} = 52.86\ kJ\ mol^{-1}$$
