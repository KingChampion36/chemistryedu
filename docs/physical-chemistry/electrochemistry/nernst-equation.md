---
title: Electrochemistry | Nernst Equation
description: Nernst Equation can be used to calculate EMF of a cell.
---

# [![ChemistryEdu Logo](../../images/favicon.svg){ align=left, width=3.8% }](../../index.md)  Electrochemistry | Nernst Equation

## Nernst Equation

* Nernst Equation is used to calculate EMF of a cell.

!!! tip "Nernst Equation derivation"

    At temperature T, change in Gibbs Free Energy is given by:

    $$ &Delta;G = &Delta;G^0 + RTlnQ $$

    where, Q = Reaction quotient, R = Universal Gas Constant<br>

    We know that:

    $$&Delta;G^0 = -nFE^0_{cell}$$

    $$&Delta;G = -nFE_{cell}$$

    Putting these two values in above equation:

    $$ -nFE_{cell} = -nFE^0_{cell} + RTlnQ $$

    $$ E_{cell} = E^0_{cell} - {RT \over {nF}}lnQ $$

    $$ E_{cell} = E^0_{cell} - {2.303RT \over {nF}}logQ $$

    This equation is known as Nernst Equation.

    If T = 298 K and putting the values of F and R in the given equation:

    $$ E_{cell} = E^0_{cell} - {0.0591 \over n}logQ $$

    Here, n = Number of electrons exchanged during cell reaction

## How to apply Nernst Equation?

* Calculate E<sup>0</sup><sub>cell</sub> = E<sup>0</sup><sub>cathode</sub> - E<sup>0</sup><sub>anode</sub>
* Write oxidation half and reduction half reactions.
* Add oxidation half and reduction half reactions to obtain net cell reaction.
* Find number of electrons exchanged, n.
* Calculate reaction quotient of the net cell reaction.
* Use Nernst Equation to find E<sub>cell</sub>:

!!! tip ""

    $$ E_{cell} = E^0_{cell} - {0.0591 \over n}logQ $$

## Nernst Equation during Equilibrium

* At equilibrium, we know that change in Gibbs Free Energy is zero.

!!! tip ""

    $$&Delta;G = 0$$

    $$-nFE_{cell} = 0$$

    $$E_{cell} = 0$$

* Also, at equilibrium: $Q = K_c$

* Therefore, at equilibrium, Nernst equation can be written as:

!!! tip ""

    $$ E_{cell} = E^0_{cell} - {0.0591 \over n}logQ $$

    $$ 0 = E^0_{cell} - {0.0591 \over n}logK_c $$

    $$ E^0_{cell} = {0.0591 \over n}logK_c $$

## Nernst Equation For Half Cell Reactions

* Nernst Equation is applicable for half cell as well as complete cell.

* For oxidation half cell, we can write:

!!! tip ""

    $$ E_{ox} = E^0_{ox} - {0.0591 \over n}logQ_1 $$

* For reduction half cell, we can write:

!!! tip ""

    $$ E_{red} = E^0_{red} - {0.0591 \over n}logQ_2 $$

* Adding oxidation and reduction half cell reaction, we get net cell reaction and Nernst equation of cell can be written as:

!!! tip ""

    $$ E_{ox} + E_{red} = E^0_{ox} + E^0_{red} - {0.0591 \over n}log(Q_1Q_2) $$

    We know that: $E_{ox} + E_{red} = E_{cell}$

    $$E_{cell} = E^0_{cell} - {0.0591 \over n}log(Q)$$

## Electrochemical cell and Gibbs Energy of a Reaction

* Change in Gibbs Free Energy is given by:

!!! tip ""

    $$&Delta;G = -nFE_{cell}$$

* Standard Change in Gibbs Free Energy is given by:

!!! tip ""

    $$&Delta;G^0 = -nFE^0_{cell}$$

    Also,

    $$&Delta;G^0 = -RTlnK_c$$
