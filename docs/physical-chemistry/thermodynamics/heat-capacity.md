---
title: Thermodynamics | Heat Capacity
description: Heat capacity is the amount of heat required to raise the temperature of a substance by 1 Kelvin.
---

# [![ChemistryEdu Logo](../../images/favicon.svg){ align=left, width=3.8% }](../../index.md)  Thermodynamics | Heat Capacity

## Heat Capacity

* We can define heat capacity as the amount of heat required to raise the temperature of a given mass of substance by 1 Kelvin (or 1 &#8451;).
* It is denoted by C and is an extensive property, ie, it depends on the amount of matter present in the substance.

!!! tip ""

    $$C = {dq \over dT}$$

    $$where,\ q = heat\ and\ T = temperature$$

## Specific Heat Capacity

* Specific heat capacity is defined as the amount of heat required to raise the temperature of 1 gram of a substance by 1 K.
* It can also be defined as the heat capacity per unit gram of mass.
* It is an intensive property because it does not depend on amount of matter present in the substance (it is expressed as per unit gram of mass).
* It is denoted by the symbol S.

!!! tip ""

    $$S = {C \over m}$$

    $$where,\ C = Heat\ capacity\ and\ m = mass\ in\ gram$$

    $$S = {dq \over mdT}$$

## Molar Heat Capacity

* Molar heat capacity is defined as the amount of heat required to raise the temperature of 1 mole of a substance by 1 K.
* It is defined as heat capacity per unit mole.
* It is an intensive property, ie it does not depend on amount of matter present in the substance.
* It is denoted by C<sub>m</sub>.

!!! tip ""

    $$C_m = {C \over n}$$

    $$where,\ C = heat\ capacity\ and\ n = moles$$

    $$C_m = {dq \over ndT}$$

    $$Also,\ dq = nC_mdT$$

    Let's put substitute values in the equation of C<sub>m</sub>.

    $$C_m = {dq \over ndT}$$

    Using first law of thermodynamics, dq = dU - dW:

    $$C_m = {(dU - dW) \over ndT}$$

    $$C_m = {dU \over ndT} - {dW \over ndT}$$

    $$C_m = {nC_vdT \over ndT} - {(-PdV) \over ndT}$$

    $$C_m = C_v + {PdV \over ndT}$$

* Molar heat capacity at constant volume is denoted by C<sub>v</sub>.
* Molar heat capacity at constant pressure is denoted by C<sub>p</sub>.

## Relation between C<sub>p</sub> and C<sub>v</sub>

* The relation between C<sub>p</sub> and C<sub>v</sub> is given as:

!!! tip ""

    $$C_p - C_v = R$$

* Let's try to prove this relation.

* At constant pressure:

!!! tip ""

    $$dH = dU + PdV$$

    $$dH = dU - dW$$

    $$dU = dH + dW$$

    $$By\ first\ law\ of\ thermodynamics:$$

    $$dU = dq + dW$$

    $$Hence,\ at\ constant\ pressure,\ we\ can\ write:$$

    $$dq = dH$$

    $$dq = nC_pdT\ (Since,\ dH = nC_pdT)$$

* Also, we know that:

!!! tip ""

    $$dU = nC_vdT$$

* Applying first law of thermodynamics at constant pressure:

!!! tip ""

    $$dU = dq + dW$$

    $$nC_vdT = nC_pdT - PdV$$

    $$n(C_v - C_p) dT = -PdV$$

    $$n(C_v - C_p) dT = -nRdT$$

    $$C_v - C_p = -R$$

    $$C_p - C_v = R$$

## Poisson's Ratio

Poisson's ratio is defined as the ratio of molar heat capacity at constant pressure (C<sub>p</sub>) to molar heat capacity at constant volume (C<sub>v</sub>).

!!! tip ""

    $$&gamma; = {C_p \over C_v}$$

## Calculation of molar heat capacity and Poisson's ratio for a mixture of gases

* Let us consider a container containing a mixture of three gases A, B and C whose moles are n<sub>1</sub>, n<sub>2</sub> and n<sub>3</sub> respectively. Let their molar heat capacity at constant volume be C<sub>v1</sub>,
  C<sub>v2</sub> and C<sub>v3</sub> respectively.

* We can calculate C<sub>v(mix)</sub> of mixture of these gases as:

!!! tip ""

    $$C_{v(mix)} = {n_1C_{v1} + n_2C_{v2} + n_3C_{v3} \over n_1 + n_2 + n_3}$$

* C<sub>p(mix)</sub> can be calculated as:

!!! tip ""

    $$C_{p(mix)} = C_{v(mix)} + R$$


* Poisson's ratio, &gamma;<sub>mix</sub> is given by:

!!! tip ""

    $$&gamma;_{mix} = {C_{p(mix)} \over C_{v(mix)}}$$


!!! tip "Important formula to remember from this article"

    * dU = nC<sub>v</sub>dT

    * dq = nC<sub>p</sub>dT

    * C<sub>p</sub> - C<sub>v</sub> = R

    * &gamma; = C<sub>p</sub> / C<sub>v</sub>

    Here, U = internal energy, C<sub>v</sub> = molar heat capacity at constant volume, C<sub>p</sub> = molar heat capacity at constant pressure, n = moles, q = heat, T = temperature, &gamma; = Poisson's ration
