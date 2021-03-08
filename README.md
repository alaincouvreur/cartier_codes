# cartier_codes
Magma programs to compute Cartier codes
----------------------------------
Author : Alain Couvreur

Contact : alain.couvreur@inria.fr
----------------------------------


copy these files in your current folder, open Magma and 
> load "CartierCode.mgm";

Then, create a Cartier code Car(P, G) over F_{p^r} with P a list of
places of degree 1 and G a divisor on a curve by:

> CartierCode(D, G, r);
