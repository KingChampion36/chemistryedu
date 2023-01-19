---
title: Thermodynamics | Polytropic Process
description: In this article, we will discuss polytropic process. We will derive work done and molar heat capacity of a gas undergoing polytropic process.
---

# [![ChemistryEdu Logo](../../images/favicon.svg){ align=left, width=3.8% }](../../index.md)  Thermodynamics | Polytropic Process

## Polytropic Process

* Polytropic process is a process which follows the equation:

!!! tip ""

    $$PV^x = k$$

    where, x = polytropic index and k = constant

!!! note "Special Cases:"

    1. If x = 0 &#8658; P = constant &#8658; Isobaric process
    2. If x = 1 &#8658; PV = constant &#8658; Isothermal process
    3. If x = &gamma; &#8658; PV<sup>&gamma;</sup> = constant &#8658; Adiabatic process

## Work done in a polytropic process

For a reversible polytropic process, work done can be calculated as:

!!! tip ""

    $$W = - \int\limits_{V_1}^{V_2} P_{ext}dV$$

    $$W = - \int\limits_{V_1}^{V_2} P_{gas}dV$$

    $$W = - \int\limits_{V_1}^{V_2} {k \over V^x}dV$$

    $$W = {-k(V_2^{1-x} - V_1^{1-x}) \over 1-x}$$

## Calculation of molar heat capacity

* Molar heat capacity is defined as heat capacity per unit mole.

!!! tip ""

    $$C_m = {dq \over ndT}$$

    $$C_m = {dU - dW \over ndT}$$

    $$C_m = {dU - (-PdV) \over ndT}$$

    $$C_m = {dU \over ndT} + {PdV \over ndT}$$

    $$C_m = {nC_vdT \over ndT} + {PdV \over ndT}$$

    $$C_m = C_v + {PdV \over ndT}$$

* Let's calculate dV/dT so that it can be used in above expression.

!!! tip ""

    $$PV^x = k$$

    $$ {T \over V}V^x = k$$

    $$TV^{x-1} = k$$

    Differentiating both sides:

    $$V^{x-1}dT + T(x-1)V^{x-2}dV = 0$$

    $$ {dV \over dT} = {V \over T(1-x)}$$

    Putting in the expression of C<sub>m</sub>:

    $$C_m = C_v + {PV \over nT(1-x)}$$

    Since, PV = nRT (ideal gas equation), we can write:

    $$C_m = C_v + {nRT \over nT(1-x)}$$

    $$C_m = C_v + {R \over (1-x)}$$

## Questions based on Polytropic Process

??? question "For a monoatomic ideal gas, the ratio of pressure and square of volume is 3. How much heat should be supplied to increase the temperature of 5 moles of the gas by 50<sup>o</sup>C?"

    $$ {P \over V^2} = 3$$

    $$ PV^{-2} = constant$$

    This is a polytropic process with x = -2.

    Molar heat capacity is given by:

    $$C_m = C_v + {R \over (1-x)}$$

    $$C_m = C_v + {R \over (1-(-2))}$$

    $$C_m = {3R \over 2} + {R \over 3}$$

    $$C_m = {11R \over 6}$$

    Also, molar heat capacity is given by:

    $$C_m = {dq \over ndT}$$

    $$dq = nC_mdT$$

    $$q = \int\limits_{T_1}^{T_2} nC_mdT$$

    $$q = nC_m(T_2 - T_1)$$

    $$q = nC_m&Delta;T$$

    $$q = 5 \times {11R \over 6} \times 50$$

    $$q = {1375R \over 3}$$

    $$q = {1375 \times 8.314 \over 3}$$

    $$q = 3810.58\ J$$

??? question "The molar heat capacity of a gas (at room temperature) for which pressure and volume are equal is 7R/2. What will be the rotational degree of freedom for this gas? Also, predict the atomicity of gas."

    $$Given:\ P = V$$

    $$PV^{-1} = constant$$

    This is a polytropic process with x = -1.

    Molar heat capacity is given by:

    $$C_m = C_v + {R \over (1-x)}$$

    $$&#8658;{7R \over 2} = C_v + {R \over (1-(-1))}$$

    $$&#8658;{7R \over 2} = C_v + {R \over 2}$$

    $$&#8658;C_v = 3R$$

    Thus, it is a triatomic gas.

    $$C_v = {fR \over 2}$$

    $$&#8658;3R = {fR \over 2}$$

    $$&#8658;f = 6$$

    Thus, total degree of freedom = 6

    Let f<sub>tr</sub> = Translational degree of freedom and f<sub>r</sub> = Rotational degree of freedom. Then, At room temperature:

    $$f_{tr} + f_r = f$$

    $$3 + f_r = 6$$

    $$f_r = 3$$

    Thus, rotational degree of freedom is 3.

??? question "Calculate the molar heat capacity of monoatomic gas for which the ratio of pressure and volume is 1."

    $$Given:\ {P \over V} = 1$$

    $$PV^{-1} = constant$$

    This is a polytropic process with x = -1.

    Molar heat capacity is given by:

    $$C_m = C_v + {R \over (1-x)}$$

    Since, C<sub>v</sub> = 3R/2 for a monoatomic gas, we can write:

    $$C_m = {3R \over 2} + {R \over (1-(-1))} $$

    $$C_m = {3R \over 2} + {R \over 2}$$

    $$C_m = 2R$$
