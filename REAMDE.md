# Various polynomial approximations for the wave propagation in hollow cicular cylinder

## Introduction
This repository contains Maxima files to perform the symbolic calculation of various polynomial approximations for the (longitudinal) wave propagation in a hollow cicular cylinder.

This comes along with a paper being prepared for publication.

The `.mac` files are the Maxima inputs. The `.m` files are the ouput files.

## Jacobi modes approximation
See the detailed equations in:

Brizard, D., E. Jacquelin, et S. Ronel. 2019. ‘**Polynomial mode approximation for longitudinal wave dispersion in circular rods**’. *Journal of Sound and Vibration* 439 (january): 388‑97. https://doi.org/10.1016/j.jsv.2018.09.062.

Getting the results for the hollow circular cylinder is only a matter of changing the lower bound for the integral in the set of equations for the plain circular cylinder.

## Mirsky approximate theories

The three Maxima files for Mirsky approximate theories correspond to the following articles:

Herrmann, G., and I. Mirsky. 1956. ‘**Three-Dimensional and Shell-Theory Analysis of Axially Symmetric Motions of Cylinders**’. *Journal of Applied Mechanics* 23 (4): 563–68.

Mirsky, I. 1964. ‘**Vibrations of Orthotropic, Thick, Cylindrical Shells**’. *The Journal of the Acoustical Society of America* 36 (1): 41. https://doi.org/10.1121/1.1918910.

Mirsky, I., and G. Herrmann. 1958. ‘**Axially Symmetric Motions of Thick Cylindrical Shells**’. *Journal of Applied Mechanics* 25 (1).

These Maxima files are intended to rewrite the given equations with variables W (dimensionless circular frequency) and C (dimensionless velocity).

## Naghdi and Cooper

Naghdi, P. M., and R. M. Cooper. 1956. ‘**Propagation of Elastic Waves in Cylindrical Shells, Including the Effects of Transverse Shear and Rotatory Inertia**’. *The Journal of the Acoustical Society of America* 28 (1): 56–63. https://doi.org/10.1121/1.1908222.

The equations provided by Naghdi and Cooper use the variables $\delta=h/\Lambda$ and $c$. The Maxima file ouputs the polynomial with variables $c$ and $\omega$.

## Lin and Morgan

Lin, T.C., et G.W. Morgan. 1956. ‘**A Study of Axisymmetric Vibrations of Cylindrical Shells as Effected by Rotatory Inertia and Shear**’. *Journal of Applied Mechanics* 23 (january).

The approximate theory from Lin and Morgan already provides the equations with dimensionaless variables $\omega$ and $c$. 

It can therefore be directly programmed from the article.

