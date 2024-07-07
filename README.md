# Mock-MMA

This is an attempt to port the *Rubi* integrator to MockMMA (LISP + Mathematica parser + evaluator + pattern matcher). 

Rubi seemingly depends heavily on many bespoke features of Mathematica, in particular its simplification, factorisation, and numerical evaluation (e.g. PossibleZeroQ). So we can only hope for a (possibly small) subset of the Rubi rules to run successfully in MockMMA. 
