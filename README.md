# Vacuum Energy and the Casimir Effect: A 1+1D Toy Model

A numerical and symbolic exploration of the Casimir Effect
using a simplified 1+1D Toy Model using Mathematica

## Overview

The Casimir effect is a measurable quantum mechanical force arising from the zero-point energy of the vacuum. 
This notebook explores the problem from: 
starting with a divergent sum, introducing a regularisation, deriving a closed-form vacuum energy, 
and arriving at a measurable, finite force between two plates. 

## Contents

1. Divergent Sum - visualising why the sum 1+2+3+... is divergent and cannot be evaluated directly

2. Regularisation - introducing a regulator and showing the famous numerical convergence result -1/12

3. Vacuum Energy - Deriving a closed form for E(d,a) through symbolic summation and differentiation,
then extracting the finite part through series expansion.

4. The Casimir Force - computing F(d)=-dEtot/dd through the combined limit vanishing regulator and infinite system size,
visualising the attractive 1/d^2 force.

5. Comparison to the real effect- Contrasting the 1D Toy Model with the real 3+1D electromagnetic Casimir Force (1/d^4)

## Tools Used

- Sum, Series, SeriesCoefficient, Limit, D for symbolic computation
- NestList, Table, N for precision controls for numerical computations
- ListLogLinearPlot, LogLogPlot, Plot for plotting

## Files

- casimireffect.nb - full Mathematica notebook
- casimireffect.pdf - exported PDF version
