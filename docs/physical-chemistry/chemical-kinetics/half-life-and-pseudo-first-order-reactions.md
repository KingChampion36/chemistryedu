---
title: Chemical Kinetics | Half-Life and Pseudo First Order Reactions
description: The half-life of a reaction is the time in which the concentration of a reactant is reduced to one half of its initial concentration. It is represented as t1/2.
---

# [![ChemistryEdu Logo](../../images/favicon.svg){ align=left, width=3.8% }](../../index.md)  Chemical Kinetics | Half-Life and Pseudo First Order Reactions

## Half-Life of a Reaction

The half-life of a reaction is the time in which the concentration of a reactant is reduced to one half of its initial concentration. It is represented as t<sub>1/2</sub>.

### 1. Half-life of a zero order reaction

!!! tip ""

    $$k = {[R]_0 - [R] \over t}$$

    $$At\ t = t_{1/2},\ \ [R] = {1 \over 2}[R]_0$$

    $$k = {[R]_0 - {1 \over 2}[R]_0 \over t_{1/2}}$$

    $$t_{1/2} = {[R]_0 \over 2k}$$

* For a zero order reaction, t<sub>1/2</sub> is directly proportional to the initial concentration of reactant and inversely proportional to the rate constant.

### 2. Half-life of a first order reaction

!!! tip ""

    $$k = {2.303 \over t} log{[R]_0 \over [R]}$$

    $$At\ t = t_{1/2},\ \ [R] = {[R]_0 \over 2}$$

    $$k = {2.303 \over t_{1/2}} log{[R]_0 \over [R]_0/2}$$

    $$t_{1/2} = {2.303 \over k} log\ 2 = {2.303 \over k} \times 0.301$$

    $$t_{1/2} = {0.693 \over k}$$

* For a first order reaction, the half-life is constant, i.e. it does not depend on the initial concentration of the reactant.
* So t<sub>1/2</sub> can be found directly from k, and k from t<sub>1/2</sub>.
* After n half-lives, the amount of reactant left is (1/2)<sup>n</sup> of the initial amount.

!!! tip "Conclusion"

    * For a zero order reaction: t<sub>1/2</sub> &prop; [R]<sub>0</sub>

    * For a first order reaction: t<sub>1/2</sub> is independent of [R]<sub>0</sub>

## Summary of Integrated Rate Laws

Order | Reaction type | Differential rate law | Integrated rate law | Straight line plot | Half-life | Units of k
------|---------------|-----------------------|---------------------|--------------------|-----------|-----------
0 | R &rarr; P | d[R]/dt = -k | kt = [R]<sub>0</sub> - [R] | [R] vs t | [R]<sub>0</sub>/2k | mol L<sup>-1</sup>s<sup>-1</sup>
1 | R &rarr; P | d[R]/dt = -k[R] | [R] = [R]<sub>0</sub>e<sup>-kt</sup> or kt = ln([R]<sub>0</sub>/[R]) | ln[R] vs t | ln 2/k | s<sup>-1</sup>

## Pseudo First Order Reaction

* The order of a reaction is sometimes changed by the conditions. This happens when one reactant is present in large excess.
* Consider the acid hydrolysis of 0.01 mol of ethyl acetate with 10 mol of water:

!!! tip ""

    $$CH_3COOC_2H_5 + H_2O \xrightarrow{H^+} CH_3COOH + C_2H_5OH$$

Time | CH<sub>3</sub>COOC<sub>2</sub>H<sub>5</sub> | H<sub>2</sub>O | CH<sub>3</sub>COOH | C<sub>2</sub>H<sub>5</sub>OH
-----|------|------|------|------
t = 0 | 0.01 mol | 10 mol | 0 mol | 0 mol
t (completion) | 0 mol | 9.9 mol | 0.01 mol | 0.01 mol

* The amount of water hardly changes during the reaction. So [H<sub>2</sub>O] can be taken as constant:

!!! tip ""

    $$Rate = k'[CH_3COOC_2H_5][H_2O]$$

    $$Rate = k[CH_3COOC_2H_5],\ \ where\ k = k'[H_2O]$$

* The reaction is actually second order but behaves as a first order reaction. Such reactions are called **pseudo first order reactions**.
* Inversion of cane sugar is another pseudo first order reaction:

!!! tip ""

    $$\underset{Cane\ sugar}{C_{12}H_{22}O_{11}} + H_2O \xrightarrow{H^+} \underset{Glucose}{C_6H_{12}O_6} + \underset{Fructose}{C_6H_{12}O_6}$$

    $$Rate = k[C_{12}H_{22}O_{11}]$$

## Questions

!!! question "A first order reaction is found to have a rate constant, k = 5.5 &times; 10<sup>-14</sup> s<sup>-1</sup>. Find the half-life of the reaction."

    $$t_{1/2} = {0.693 \over k} = {0.693 \over 5.5 \times 10^{-14}\ s^{-1}}$$

    $$t_{1/2} = 1.26 \times 10^{13}\ s$$

!!! question "Show that in a first order reaction, time required for completion of 99.9% is 10 times of half-life (t<sub>1/2</sub>) of the reaction."

    * When the reaction is 99.9% complete:

    $$[R] = [R]_0 - 0.999[R]_0 = 0.001[R]_0$$

    $$t_{99.9\%} = {2.303 \over k} log{[R]_0 \over 0.001[R]_0} = {2.303 \over k} log\ 10^3$$

    $$t_{99.9\%} = {6.909 \over k}$$

    $$t_{1/2} = {0.693 \over k}$$

    $${t_{99.9\%} \over t_{1/2}} = {6.909 \over k} \times {k \over 0.693} = 10$$

!!! question "A first order reaction has a rate constant 1.15 &times; 10<sup>-3</sup> s<sup>-1</sup>. How long will 5 g of this reactant take to reduce to 3 g?"

    $$t = {2.303 \over k} log{[R]_0 \over [R]}$$

    $$t = {2.303 \over 1.15 \times 10^{-3}} log{5 \over 3}$$

    $$t = {2.303 \over 1.15 \times 10^{-3}} \times 0.2219$$

    $$t = 444\ s$$

!!! question "Time required to decompose SO<sub>2</sub>Cl<sub>2</sub> to half of its initial amount is 60 minutes. If the decomposition is a first order reaction, calculate the rate constant of the reaction."

    $$k = {0.693 \over t_{1/2}} = {0.693 \over 60\ min}$$

    $$k = 1.155 \times 10^{-2}\ min^{-1}$$

    $$k = {1.155 \times 10^{-2} \over 60} = 1.925 \times 10^{-4}\ s^{-1}$$

!!! question "Hydrolysis of methyl acetate in aqueous solution has been studied by titrating the liberated acetic acid against sodium hydroxide. The concentration of the ester at different times is given below.<br>t/min: 0, 30, 60, 90<br>C/mol L<sup>-1</sup>: 0.8500, 0.8004, 0.7538, 0.7096<br>Show that it follows a pseudo first order reaction, as the concentration of water remains nearly constant (55 mol L<sup>-1</sup>) during the course of the reaction. What is the value of k' in the equation Rate = k'[CH<sub>3</sub>COOCH<sub>3</sub>][H<sub>2</sub>O]?"

    * For a pseudo first order reaction, the reaction should be first order with respect to the ester when [H<sub>2</sub>O] is constant.

    $$k = {2.303 \over t} log{C_0 \over C},\ \ where\ k = k'[H_2O]$$

    $$At\ t = 30\ min:\ k = {2.303 \over 30} log{0.8500 \over 0.8004} = 2.004 \times 10^{-3}\ min^{-1}$$

    $$At\ t = 60\ min:\ k = {2.303 \over 60} log{0.8500 \over 0.7538} = 2.002 \times 10^{-3}\ min^{-1}$$

    $$At\ t = 90\ min:\ k = {2.303 \over 90} log{0.8500 \over 0.7096} = 2.005 \times 10^{-3}\ min^{-1}$$

    * Since k'[H<sub>2</sub>O] is constant (about 2.004 &times; 10<sup>-3</sup> min<sup>-1</sup>), the reaction is pseudo first order.

    $$k'[H_2O] = 2.004 \times 10^{-3}\ min^{-1}$$

    $$k' \times 55\ mol\ L^{-1} = 2.004 \times 10^{-3}\ min^{-1}$$

    $$k' = 3.64 \times 10^{-5}\ mol^{-1}L\ min^{-1}$$
