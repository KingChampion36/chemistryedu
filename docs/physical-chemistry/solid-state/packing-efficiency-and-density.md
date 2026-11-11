---
title: Solid State | Packing Efficiency and Density of Unit Cell
description: Packing efficiency is the percentage of total space filled by the constituent particles in a crystal. Knowing the unit cell dimensions, we can also calculate the density of a solid.
---

# [![ChemistryEdu Logo](../../images/favicon.svg){ align=left, width=3.8% }](../../index.md)  Solid State | Packing Efficiency and Density of Unit Cell

However the constituent particles are packed, there is always some free space left in the form of voids. **Packing efficiency** is the percentage of total space filled by the particles.

!!! tip ""

    $$Packing\ efficiency = {Volume\ occupied\ by\ spheres\ in\ unit\ cell \over Total\ volume\ of\ unit\ cell} \times 100\ \%$$

In each case below, 'a' is the edge length of the cubic unit cell and 'r' is the radius of each sphere (atom).

## 1. Packing Efficiency in hcp and ccp Structures

* Both hcp and ccp are equally efficient. We calculate it for the ccp (fcc) unit cell.
* In fcc, atoms touch each other along the **face diagonal**. Let the face diagonal be b.

!!! tip ""

    $$b^2 = a^2 + a^2 = 2a^2$$

    $$b = \sqrt{2}a$$

* The face diagonal contains one full sphere and two half spheres (from the corners), so its length is 4r.

!!! tip ""

    $$b = 4r = \sqrt{2}a$$

    $$a = {4r \over \sqrt{2}} = 2\sqrt{2}r \quad or \quad r = {a \over 2\sqrt{2}}$$

* A ccp unit cell has 4 atoms.

!!! tip ""

    $$Volume\ of\ 4\ spheres = 4 \times {4 \over 3}\pi r^3$$

    $$Volume\ of\ cube = a^3 = (2\sqrt{2}r)^3 = 16\sqrt{2}r^3$$

    $$Packing\ efficiency = {4 \times {4 \over 3}\pi r^3 \over 16\sqrt{2}r^3} \times 100 = {{16 \over 3}\pi r^3 \over 16\sqrt{2}r^3} \times 100$$

    $$Packing\ efficiency = 74\ \%$$

## 2. Packing Efficiency in Body-Centred Cubic (bcc) Structure

* In bcc, the atom at the body-centre touches the two corner atoms that lie along the **body diagonal**.
* Let the face diagonal be b and the body diagonal be c.

!!! tip ""

    $$b^2 = a^2 + a^2 = 2a^2$$

    $$c^2 = a^2 + b^2 = a^2 + 2a^2 = 3a^2$$

    $$c = \sqrt{3}a$$

* The three spheres along the body diagonal touch each other, so the body diagonal equals 4r.

!!! tip ""

    $$\sqrt{3}a = 4r$$

    $$a = {4r \over \sqrt{3}} \quad or \quad r = {\sqrt{3} \over 4}a$$

* A bcc unit cell has 2 atoms.

!!! tip ""

    $$Volume\ of\ 2\ spheres = 2 \times {4 \over 3}\pi r^3$$

    $$Volume\ of\ cube = a^3 = \left({4 \over \sqrt{3}}r\right)^3 = {64 \over 3\sqrt{3}}r^3$$

    $$Packing\ efficiency = {{8 \over 3}\pi r^3 \over {64 \over 3\sqrt{3}}r^3} \times 100 = {\sqrt{3}\pi \over 8} \times 100$$

    $$Packing\ efficiency = 68\ \%$$

## 3. Packing Efficiency in Simple Cubic Lattice

* In a simple cubic lattice, atoms are only at the corners and they touch each other along the **edge** of the cube.

!!! tip ""

    $$a = 2r$$

    $$Volume\ of\ cube = a^3 = (2r)^3 = 8r^3$$

* A simple cubic unit cell has only 1 atom.

!!! tip ""

    $$Volume\ of\ 1\ sphere = {4 \over 3}\pi r^3$$

    $$Packing\ efficiency = {{4 \over 3}\pi r^3 \over 8r^3} \times 100 = {\pi \over 6} \times 100$$

    $$Packing\ efficiency = 52.36\ \% \approx 52.4\ \%$$

!!! tip "Conclusion"

    | Structure | Relation between a and r | Atoms per unit cell | Coordination number | Packing efficiency |
    | --- | --- | --- | --- | --- |
    | Simple cubic | a = 2r | 1 | 6 | 52.4 % |
    | Body-centred cubic | $\sqrt{3}a = 4r$ | 2 | 8 | 68 % |
    | ccp / fcc and hcp | $\sqrt{2}a = 4r$ | 4 (fcc) | 12 | 74 % |

    ccp and hcp structures have the maximum packing efficiency.

## Density of a Unit Cell

From the unit cell dimensions, we can calculate the volume of the unit cell. Knowing the density, we can calculate the mass of atoms in the unit cell. This is also an accurate method of determining Avogadro's constant.

Let, for a cubic crystal:

* a = edge length of unit cell (found by X-ray diffraction)
* z = number of atoms in one unit cell
* M = molar mass of the substance
* N<sub>A</sub> = Avogadro's constant
* d = density of the substance

!!! tip ""

    $$Volume\ of\ unit\ cell = a^3$$

    $$Mass\ of\ one\ atom,\ m = {M \over N_A}$$

    $$Mass\ of\ unit\ cell = z \times m = {zM \over N_A}$$

    $$Density,\ d = {Mass\ of\ unit\ cell \over Volume\ of\ unit\ cell}$$

    $$d = {zM \over a^3 N_A}$$

* The density of the unit cell is the same as the density of the substance.
* Out of the five quantities d, z, M, a and N<sub>A</sub>, if any four are known, the fifth can be calculated.

!!! note "Note"

    Keep units consistent. If a is in pm, convert it to cm using 1 pm = 10<sup>-10</sup> cm (so that d comes in g cm<sup>-3</sup> with M in g mol<sup>-1</sup>), or to m using 1 pm = 10<sup>-12</sup> m (so that d comes in kg m<sup>-3</sup> with M in kg mol<sup>-1</sup>).

## Questions

!!! question "An element has a body-centred cubic (bcc) structure with a cell edge of 288 pm. The density of the element is 7.2 g/cm<sup>3</sup>. How many atoms are present in 208 g of the element?"

    $$Volume\ of\ unit\ cell = (288\ pm)^3 = (288 \times 10^{-10}\ cm)^3 = 2.39 \times 10^{-23}\ cm^3$$

    $$Volume\ of\ 208\ g\ element = {mass \over density} = {208 \over 7.2} = 28.88\ cm^3$$

    $$Number\ of\ unit\ cells = {28.88 \over 2.39 \times 10^{-23}} = 12.08 \times 10^{23}$$

    * Each bcc unit cell contains 2 atoms.

    $$Number\ of\ atoms = 2 \times 12.08 \times 10^{23} = 24.16 \times 10^{23}$$

!!! question "X-ray diffraction studies show that copper crystallises in an fcc unit cell with cell edge of 3.608 x 10<sup>-8</sup> cm. In a separate experiment, copper is determined to have a density of 8.92 g/cm<sup>3</sup>. Calculate the atomic mass of copper."

    * For an fcc lattice, z = 4.

    $$d = {zM \over a^3 N_A} \quad &Therefore; \quad M = {d N_A a^3 \over z}$$

    $$M = {8.92 \times 6.022 \times 10^{23} \times (3.608 \times 10^{-8})^3 \over 4}$$

    $$M = 63.1\ g\ mol^{-1}$$

    Hence, the atomic mass of copper is 63.1 u.

!!! question "Silver forms ccp lattice and X-ray studies of its crystals show that the edge length of its unit cell is 408.6 pm. Calculate the density of silver (Atomic mass = 107.9 u)."

    * For a ccp lattice, z = 4.

    $$M = 107.9\ g\ mol^{-1} = 107.9 \times 10^{-3}\ kg\ mol^{-1}$$

    $$a = 408.6\ pm = 408.6 \times 10^{-12}\ m$$

    $$d = {zM \over a^3 N_A} = {4 \times 107.9 \times 10^{-3} \over (408.6 \times 10^{-12})^3 \times 6.022 \times 10^{23}}$$

    $$d = 10.5 \times 10^3\ kg\ m^{-3} = 10.5\ g\ cm^{-3}$$

!!! question "An element with molar mass 2.7 x 10<sup>-2</sup> kg mol<sup>-1</sup> forms a cubic unit cell with edge length 405 pm. If its density is 2.7 x 10<sup>3</sup> kg m<sup>-3</sup>, what is the nature of the cubic unit cell?"

    $$z = {d a^3 N_A \over M}$$

    $$z = {2.7 \times 10^3 \times (405 \times 10^{-12})^3 \times 6.022 \times 10^{23} \over 2.7 \times 10^{-2}}$$

    $$z = {2.7 \times 10^3 \times 6.643 \times 10^{-29} \times 6.022 \times 10^{23} \over 2.7 \times 10^{-2}} = 4.0$$

    Since there are 4 atoms per unit cell, the unit cell is face-centred cubic (fcc) or ccp.
