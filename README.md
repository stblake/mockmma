# Mock-MMA

This is an attempt to port the *Rubi* integrator to MockMMA (LISP + Mathematica parser + evaluator + pattern matcher). 

Rubi seemingly depends heavily on many bespoke features of Mathematica, in particular its simplification, factorisation, and numerical evaluation (e.g. PossibleZeroQ). So we can only hope for a (possibly small) subset of the Rubi rules to run successfully in MockMMA. 

Mock-MMA was written by Richard Fateman from the University of California, Berkeley in 1990. 

## Prerequisites for Mock-MMA

A Common LISP interpreter. Mock-MMA was implemented with Allegro Common LISP which is proprietry software. However, it seemingly runs fine under CLISP (https://en.wikipedia.org/wiki/CLISP). 

## Running Mock-MMA

Run CLISP

$ clisp

;; Load Mock-MMA files:

[1]> (load "init.lisp")
:
;; Compile and load Mock-MMA

[2]> (compile-mma)

[3]> (load-mma)

;; Start the Mock-MMA repl:

MMA[4]> (tl)

Mock-Mma  11:43 Monday, Jul 8, 2024  

In[1] := 1+1
Out[2] = 2

## Loading Rubi

UNDER CONSTRUCTION...

# Requirements of Mock-MMA to run (even a subset of) Rubi



