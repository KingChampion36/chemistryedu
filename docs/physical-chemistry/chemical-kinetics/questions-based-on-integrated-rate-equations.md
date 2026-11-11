---
title: Chemical Kinetics | Questions Based on Integrated Rate Equations
description: In this article, we will solve some questions related to integrated rate equations and half-life of zero and first order reactions.
---

# [![ChemistryEdu Logo](../../images/favicon.svg){ align=left, width=3.8% }](../../index.md)  Chemical Kinetics | Questions Based on Integrated Rate Equations

In this article, we will solve some questions related to integrated rate equations and half-life of zero and first order reactions.

!!! tip "Formulas used"

    $$First\ order:\ k = {2.303 \over t} log{[R]_0 \over [R]}$$

    $$First\ order:\ t_{1/2} = {0.693 \over k}$$

    $$Zero\ order:\ k = {[R]_0 - [R] \over t},\ \ t_{1/2} = {[R]_0 \over 2k}$$

## Questions

!!! question "Calculate the half-life of a first order reaction from their rate constants given below: <br>(i) 200 s<sup>-1</sup> (ii) 2 min<sup>-1</sup> (iii) 4 years<sup>-1</sup>"

    $$(i)\ t_{1/2} = {0.693 \over 200\ s^{-1}} = 3.47 \times 10^{-3}\ s$$

    $$(ii)\ t_{1/2} = {0.693 \over 2\ min^{-1}} = 0.35\ min$$

    $$(iii)\ t_{1/2} = {0.693 \over 4\ years^{-1}} = 0.173\ years$$

!!! question "The half-life for radioactive decay of <sup>14</sup>C is 5730 years. An archaeological artifact containing wood had only 80% of the <sup>14</sup>C found in a living tree. Estimate the age of the sample."

    * Radioactive decay follows first order kinetics.

    $$k = {0.693 \over t_{1/2}} = {0.693 \over 5730}\ years^{-1}$$

    $$t = {2.303 \over k} log{[R]_0 \over [R]} = {2.303 \times 5730 \over 0.693} log{100 \over 80}$$

    $$t = {2.303 \times 5730 \over 0.693} \times 0.0969$$

    $$t = 1845\ years$$

!!! question "The experimental data for decomposition of N<sub>2</sub>O<sub>5</sub> [2N<sub>2</sub>O<sub>5</sub> &rarr; 4NO<sub>2</sub> + O<sub>2</sub>] in gas phase at 318 K are given below: <br>t/s: 0, 400, 800, 1200, 1600, 2000, 2400, 2800, 3200 <br>10<sup>2</sup> &times; [N<sub>2</sub>O<sub>5</sub>]/mol L<sup>-1</sup>: 1.63, 1.36, 1.14, 0.93, 0.78, 0.64, 0.53, 0.43, 0.35 <br>(i) Plot [N<sub>2</sub>O<sub>5</sub>] against t. (ii) Find the half-life period for the reaction. (iii) Draw a graph between log[N<sub>2</sub>O<sub>5</sub>] and t. (iv) What is the rate law? (v) Calculate the rate constant. (vi) Calculate the half-life period from k and compare it with (ii)."

    * (i) The plot of [N<sub>2</sub>O<sub>5</sub>] against t is a curve that falls steeply at first and then more slowly (an exponential decay).

    * (ii) Initial concentration = 1.63 &times; 10<sup>-2</sup> mol L<sup>-1</sup>. Half of it is 0.815 &times; 10<sup>-2</sup> mol L<sup>-1</sup>. From the graph, this concentration is reached at about **t<sub>1/2</sub> &asymp; 1440 s**.

    * (iii) Values of log[N<sub>2</sub>O<sub>5</sub>]:

    t/s | 0 | 400 | 800 | 1200 | 1600 | 2000 | 2400 | 2800 | 3200
    ----|---|-----|-----|------|------|------|------|------|-----
    log[N<sub>2</sub>O<sub>5</sub>] | -1.79 | -1.87 | -1.94 | -2.03 | -2.11 | -2.19 | -2.28 | -2.37 | -2.46

    The plot of log[N<sub>2</sub>O<sub>5</sub>] against t is a straight line with a negative slope.

    * (iv) Since log[N<sub>2</sub>O<sub>5</sub>] vs t is a straight line, the reaction is first order:

    $$Rate = k[N_2O_5]$$

    * (v) For a first order reaction, slope of log[R] vs t = -k/2.303:

    $$Slope = {-2.46 - (-1.79) \over 3200 - 0} = -2.09 \times 10^{-4}\ s^{-1}$$

    $$-{k \over 2.303} = -2.09 \times 10^{-4}$$

    $$k = 4.81 \times 10^{-4}\ s^{-1}$$

    * (vi) Half-life from k:

    $$t_{1/2} = {0.693 \over k} = {0.693 \over 4.81 \times 10^{-4}} = 1441\ s$$

    This agrees closely with the value of about 1440 s read from the graph in (ii).

!!! question "The rate constant for a first order reaction is 60 s<sup>-1</sup>. How much time will it take to reduce the initial concentration of the reactant to its 1/16<sup>th</sup> value?"

    $$t = {2.303 \over k} log{[R]_0 \over [R]} = {2.303 \over 60} log\ 16$$

    $$t = {2.303 \over 60} \times 1.2041$$

    $$t = 4.62 \times 10^{-2}\ s$$

    * Alternatively, 1/16 = (1/2)<sup>4</sup>, so the time needed is 4 half-lives: 4 &times; (0.693/60) = 4.62 &times; 10<sup>-2</sup> s.

!!! question "During nuclear explosion, one of the products is <sup>90</sup>Sr with half-life of 28.1 years. If 1 &mu;g of <sup>90</sup>Sr was absorbed in the bones of a newly born baby instead of calcium, how much of it will remain after 10 years and 60 years if it is not lost metabolically?"

    $$k = {0.693 \over 28.1} = 2.466 \times 10^{-2}\ years^{-1}$$

    * After 10 years:

    $$log{[R]_0 \over [R]} = {kt \over 2.303} = {2.466 \times 10^{-2} \times 10 \over 2.303} = 0.1071$$

    $${[R]_0 \over [R]} = 1.280$$

    $$[R] = {1 \over 1.280} = 0.7814\ &mu;g$$

    * After 60 years:

    $$log{[R]_0 \over [R]} = {2.466 \times 10^{-2} \times 60 \over 2.303} = 0.6425$$

    $${[R]_0 \over [R]} = 4.392$$

    $$[R] = {1 \over 4.392} = 0.2277\ &mu;g$$

!!! question "For a first order reaction, show that time required for 99% completion is twice the time required for the completion of 90% of reaction."

    * For 99% completion, [R] = 0.01[R]<sub>0</sub>:

    $$t_{99\%} = {2.303 \over k} log{[R]_0 \over 0.01[R]_0} = {2.303 \over k} log\ 100 = {2 \times 2.303 \over k}$$

    * For 90% completion, [R] = 0.1[R]<sub>0</sub>:

    $$t_{90\%} = {2.303 \over k} log{[R]_0 \over 0.1[R]_0} = {2.303 \over k} log\ 10 = {2.303 \over k}$$

    $${t_{99\%} \over t_{90\%}} = 2$$

    $$&Therefore;\ t_{99\%} = 2 \times t_{90\%}$$

!!! question "A first order reaction takes 40 min for 30% decomposition. Calculate t<sub>1/2</sub>."

    * After 30% decomposition, 70% of the reactant is left.

    $$k = {2.303 \over 40} log{100 \over 70} = {2.303 \over 40} \times 0.1549$$

    $$k = 8.918 \times 10^{-3}\ min^{-1}$$

    $$t_{1/2} = {0.693 \over k} = {0.693 \over 8.918 \times 10^{-3}}$$

    $$t_{1/2} = 77.7\ min$$

!!! question "For the decomposition of azoisopropane to hexane and nitrogen at 543 K, the following data are obtained: <br>t (sec): 0, 360, 720 <br>P (mm of Hg): 35.0, 54.0, 63.0 <br>Calculate the rate constant."

    * The reaction is:

    $$(CH_3)_2CHN=NCH(CH_3)_2 &rarr; C_6H_{14} + N_2$$

    * Let the pressure of azoisopropane decrease by x. Then hexane and nitrogen each increase by x.

    $$At\ t = 0:\ p_i,\ 0,\ 0$$

    $$At\ time\ t:\ p_i - x,\ x,\ x$$

    $$p_t = p_i + x,\ \ p_A = p_i - x = 2p_i - p_t$$

    * At t = 360 s:

    $$p_A = 2 \times 35.0 - 54.0 = 16.0\ mm\ Hg$$

    $$k = {2.303 \over 360} log{35.0 \over 16.0} = 2.175 \times 10^{-3}\ s^{-1}$$

    * At t = 720 s:

    $$p_A = 2 \times 35.0 - 63.0 = 7.0\ mm\ Hg$$

    $$k = {2.303 \over 720} log{35.0 \over 7.0} = 2.235 \times 10^{-3}\ s^{-1}$$

    $$Average\ k = {(2.175 + 2.235) \times 10^{-3} \over 2} = 2.20 \times 10^{-3}\ s^{-1}$$

!!! question "The following data were obtained during the first order thermal decomposition of SO<sub>2</sub>Cl<sub>2</sub> at a constant volume: SO<sub>2</sub>Cl<sub>2(g)</sub> &rarr; SO<sub>2(g)</sub> + Cl<sub>2(g)</sub> <br>At t = 0 s, total pressure = 0.5 atm; at t = 100 s, total pressure = 0.6 atm. <br>Calculate the rate of the reaction when total pressure is 0.65 atm."

    * The reaction is of the type A &rarr; B + C, so:

    $$p_{SO_2Cl_2} = 2p_i - p_t$$

    * At t = 100 s:

    $$p_{SO_2Cl_2} = 2 \times 0.5 - 0.6 = 0.4\ atm$$

    $$k = {2.303 \over 100} log{0.5 \over 0.4} = {2.303 \over 100} \times 0.0969$$

    $$k = 2.23 \times 10^{-3}\ s^{-1}$$

    * When total pressure is 0.65 atm:

    $$p_{SO_2Cl_2} = 2 \times 0.5 - 0.65 = 0.35\ atm$$

    $$Rate = k \times p_{SO_2Cl_2} = 2.23 \times 10^{-3} \times 0.35$$

    $$Rate = 7.8 \times 10^{-4}\ atm\ s^{-1}$$

!!! question "Consider a certain reaction A &rarr; Products with k = 2.0 &times; 10<sup>-2</sup> s<sup>-1</sup>. Calculate the concentration of A remaining after 100 s if the initial concentration of A is 1.0 mol L<sup>-1</sup>."

    * The unit of k is s<sup>-1</sup>, so this is a first order reaction.

    $$log{[A]_0 \over [A]} = {kt \over 2.303} = {2.0 \times 10^{-2} \times 100 \over 2.303} = 0.8684$$

    $${[A]_0 \over [A]} = 7.389$$

    $$[A] = {1.0 \over 7.389} = 0.135\ mol\ L^{-1}$$

!!! question "Sucrose decomposes in acid solution into glucose and fructose according to the first order rate law, with t<sub>1/2</sub> = 3.00 hours. What fraction of sample of sucrose remains after 8 hours?"

    $$k = {0.693 \over t_{1/2}} = {0.693 \over 3.00} = 0.231\ h^{-1}$$

    $$log{[R]_0 \over [R]} = {kt \over 2.303} = {0.231 \times 8 \over 2.303} = 0.8024$$

    $${[R]_0 \over [R]} = 6.345$$

    $${[R] \over [R]_0} = {1 \over 6.345} = 0.158$$

    * So, about 0.158 (15.8%) of the sucrose remains after 8 hours.
