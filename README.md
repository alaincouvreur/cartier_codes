# cartier_codes
************************************
Author : Alain Couvreur
Contact : alain.couvreur@inria.fr
************************************

************************************
Description
************************************
Magma programs to compute Cartier codes
as introduced in the article:

Alain Couvreur. Codes and the Cartier Operator.
Proc. Amer. Math. Soc. 142(6), 1983-1996, 2014. 
************************************


Open Magma and 
> load "CartierCode.mgm";

Then, create a Cartier code Car(P, G) over F_{p^r} with P a list of
places of degree 1 and G a divisor on a curve by:

> CartierCode(D, G, r);


You can run an example presented in the article
by running:

> load "Klein.mgm";