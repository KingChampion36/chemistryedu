---
title: Chemical Kinetics | Rate Law, Order and Molecularity
description: Rate law is the expression in which reaction rate is given in terms of molar concentration of reactants with each term raised to some power, which may or may not be the same as the stoichiometric coefficient.
---

# [![ChemistryEdu Logo](../../images/favicon.svg){ align=left, width=3.8% }](../../index.md)  Chemical Kinetics | Rate Law, Order and Molecularity

## Factors Influencing Rate of a Reaction

The rate of a reaction depends on the experimental conditions such as:

* Concentration of reactants (pressure in case of gases)
* Temperature
* Catalyst

## Rate Law and Rate Constant

* The rate of a reaction decreases with time as the concentration of reactants decreases. Conversely, rates generally increase when reactant concentrations increase. So, rate depends on the concentration of reactants.
* The representation of rate of reaction in terms of concentration of reactants is called the **rate law**. It is also called the rate equation or rate expression.
* Consider a general reaction:

!!! tip ""

    $$aA + bB &rarr; cC + dD$$

    $$Rate &prop; [A]^x [B]^y$$

    $$Rate = k[A]^x [B]^y$$

    $$-{d[R] \over dt} = k[A]^x [B]^y$$

* The last form is called the **differential rate equation**.
* Here, k is a proportionality constant called the **rate constant**. The exponents x and y may or may not be equal to the stoichiometric coefficients a and b.
* When [A] = [B] = 1 mol L<sup>-1</sup>, rate = k. So the rate constant is the rate of reaction when the concentration of each reactant is unity. It is also called the **specific reaction rate**.

!!! tip "Rate Law"

    Rate law is the expression in which reaction rate is given in terms of molar concentration of reactants with each term raised to some power, which may or may not be the same as the stoichiometric coefficient of the reacting species in a balanced chemical equation.

### Determining a Rate Law from Experiment

* Consider the reaction:

!!! tip ""

    $$2NO_{(g)} + O_{2(g)} &rarr; 2NO_{2(g)}$$

* The initial rate is measured by changing the concentration of one reactant while keeping the other constant:

Experiment | Initial [NO] / mol L<sup>-1</sup> | Initial [O<sub>2</sub>] / mol L<sup>-1</sup> | Initial rate of formation of NO<sub>2</sub> / mol L<sup>-1</sup>s<sup>-1</sup>
-----------|------|------|------
1          | 0.30 | 0.30 | 0.096
2          | 0.60 | 0.30 | 0.384
3          | 0.30 | 0.60 | 0.192
4          | 0.60 | 0.60 | 0.768

* Experiments 1 and 2: [NO] is doubled, [O<sub>2</sub>] is constant. Rate increases four times (0.096 to 0.384). So rate depends on [NO]<sup>2</sup>.
* Experiments 1 and 3: [O<sub>2</sub>] is doubled, [NO] is constant. Rate doubles. So rate depends on [O<sub>2</sub>]<sup>1</sup>.

!!! tip ""

    $$Rate = k[NO]^2[O_2]$$

    $$-{d[R] \over dt} = k[NO]^2[O_2]$$

* Here the exponents happen to equal the stoichiometric coefficients. This is not always so:

Reaction | Experimental rate expression
---------|------------------------------
CHCl<sub>3</sub> + Cl<sub>2</sub> &rarr; CCl<sub>4</sub> + HCl | Rate = k[CHCl<sub>3</sub>][Cl<sub>2</sub>]<sup>1/2</sup>
CH<sub>3</sub>COOC<sub>2</sub>H<sub>5</sub> + H<sub>2</sub>O &rarr; CH<sub>3</sub>COOH + C<sub>2</sub>H<sub>5</sub>OH | Rate = k[CH<sub>3</sub>COOC<sub>2</sub>H<sub>5</sub>]<sup>1</sup>[H<sub>2</sub>O]<sup>0</sup>

!!! note "Note"

    The rate law for any reaction cannot be predicted just by looking at the balanced chemical equation. It must be determined experimentally.

## Order of a Reaction

* In the rate law Rate = k[A]<sup>x</sup>[B]<sup>y</sup>, x and y show how sensitive the rate is to a change in concentration of A and B.
* x is the order with respect to A and y is the order with respect to B.
* The sum of powers of the concentration of the reactants in the rate law expression is called the **order** of that chemical reaction.

!!! tip ""

    $$Overall\ order = x + y$$

* Order can be 0, 1, 2, 3 and even a fraction or negative.
* A **zero order** reaction means that the rate is independent of the concentration of reactants.

!!! example "Example"

    $$Rate = k[A]^{1/2}[B]^{3/2}:\ \ Order = {1 \over 2} + {3 \over 2} = 2\ (second\ order)$$

    $$Rate = k[A]^{3/2}[B]^{-1}:\ \ Order = {3 \over 2} + (-1) = {1 \over 2}\ (half\ order)$$

## Elementary and Complex Reactions

* A balanced chemical equation rarely shows how a reaction actually takes place, since very few reactions are completed in one step.
* Reactions taking place in one step are called **elementary reactions**.
* When a sequence of elementary reactions (called the **mechanism**) gives the products, the reaction is called a **complex reaction**.
* Complex reactions may be:
    * Consecutive reactions, e.g. oxidation of ethane to CO<sub>2</sub> and H<sub>2</sub>O passes through alcohol, aldehyde and acid as intermediates.
    * Reverse reactions.
    * Side reactions, e.g. nitration of phenol gives both o-nitrophenol and p-nitrophenol.

## Units of Rate Constant

For a reaction of order n, Rate = k[A]<sup>x</sup>[B]<sup>y</sup> with x + y = n:

!!! tip ""

    $$k = {Rate \over [A]^x[B]^y} = {concentration \over time} \times {1 \over (concentration)^n}$$

    $$Units\ of\ k = (mol\ L^{-1})^{1-n}\ s^{-1}$$

Reaction | Order | Units of rate constant
---------|-------|------------------------
Zero order | 0 | mol L<sup>-1</sup>s<sup>-1</sup>
First order | 1 | s<sup>-1</sup>
Second order | 2 | mol<sup>-1</sup>L s<sup>-1</sup>
Third order | 3 | mol<sup>-2</sup>L<sup>2</sup>s<sup>-1</sup>

* So the order of a reaction can be identified just from the units of its rate constant.

!!! example "Example"

    * k = 2.3 &times; 10<sup>-5</sup> L mol<sup>-1</sup>s<sup>-1</sup> represents a second order reaction.
    * k = 3 &times; 10<sup>-4</sup> s<sup>-1</sup> represents a first order reaction.

## Molecularity of a Reaction

The number of reacting species (atoms, ions or molecules) taking part in an elementary reaction, which must collide simultaneously in order to bring about a chemical reaction, is called the **molecularity** of the reaction.

### 1. Unimolecular reaction

One reacting species is involved. Example, decomposition of ammonium nitrite:

!!! tip ""

    $$NH_4NO_2 &rarr; N_2 + 2H_2O$$

### 2. Bimolecular reaction

Two species collide simultaneously. Example, dissociation of hydrogen iodide:

!!! tip ""

    $$2HI &rarr; H_2 + I_2$$

### 3. Trimolecular (termolecular) reaction

Three species collide simultaneously. Example:

!!! tip ""

    $$2NO + O_2 &rarr; 2NO_2$$

* The chance of more than three molecules colliding at the same moment is very small. So molecularity greater than three is not observed.
* Hence, a reaction whose balanced equation has more than three molecules on the reactant side must take place in more than one step.

!!! example "Example"

    $$KClO_3 + 6FeSO_4 + 3H_2SO_4 &rarr; KCl + 3Fe_2(SO_4)_3 + 3H_2O$$

    This reaction looks like it should be of tenth order, but it is actually a second order reaction. This shows that it takes place in several steps.

## Rate Determining Step

* In a relay race, the chance of a team winning depends on its slowest runner. Similarly, the overall rate of a complex reaction is controlled by its slowest step, called the **rate determining step**.
* Consider the decomposition of H<sub>2</sub>O<sub>2</sub> catalysed by iodide ion in alkaline medium:

!!! tip ""

    $$2H_2O_2 \xrightarrow[Alkaline\ medium]{I^-} 2H_2O + O_2$$

    $$Rate = -{d[H_2O_2] \over dt} = k[H_2O_2][I^-]$$

* The reaction is first order with respect to both H<sub>2</sub>O<sub>2</sub> and I<sup>-</sup>. It takes place in two steps:

!!! tip ""

    $$Step\ 1\ (slow):\ H_2O_2 + I^- &rarr; H_2O + IO^-$$

    $$Step\ 2\ (fast):\ H_2O_2 + IO^- &rarr; H_2O + I^- + O_2$$

* Both steps are bimolecular elementary reactions.
* IO<sup>-</sup> is called an **intermediate** because it is formed during the reaction but does not appear in the overall balanced equation.
* The first step is slow, so it is the rate determining step. The rate of formation of the intermediate decides the rate of the overall reaction.

## Order vs Molecularity

Order | Molecularity
------|-------------
It is the sum of powers of concentration terms in the rate law. | It is the number of species colliding simultaneously in an elementary step.
It is an experimental quantity. | It is a theoretical concept.
It can be zero, a fraction or even negative. | It is always a whole number (1, 2 or 3). It cannot be zero or a fraction.
It applies to both elementary and complex reactions. | It applies only to elementary reactions. For complex reactions it has no meaning.
For a complex reaction, it is given by the slowest step. | Generally, molecularity of the slowest step equals the order of the overall reaction.

## Questions

!!! question "For a reaction, A + B &rarr; Product, the rate law is given by r = k[A]<sup>1/2</sup>[B]<sup>2</sup>. What is the order of the reaction?"

    $$Order = {1 \over 2} + 2 = {5 \over 2} = 2.5$$

!!! question "The conversion of molecules X to Y follows second order kinetics. If concentration of X is increased to three times, how will it affect the rate of formation of Y?"

    $$Rate_1 = k[X]^2$$

    $$Rate_2 = k(3[X])^2 = 9k[X]^2$$

    $$Rate_2 = 9 \times Rate_1$$

    So, the rate of formation of Y will increase 9 times.

!!! question "Identify the reaction order from each of the following rate constants: <br>(i) k = 2.3 &times; 10<sup>-5</sup> L mol<sup>-1</sup>s<sup>-1</sup> <br>(ii) k = 3 &times; 10<sup>-4</sup> s<sup>-1</sup>"

    * (i) The unit of a second order rate constant is L mol<sup>-1</sup>s<sup>-1</sup>. Hence, it is a **second order** reaction.
    * (ii) The unit of a first order rate constant is s<sup>-1</sup>. Hence, it is a **first order** reaction.
