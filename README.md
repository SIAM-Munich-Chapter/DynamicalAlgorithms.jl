# DynamicalAlgorithms.jl

The principal goal of mathematical modelling is to find the most apposite set of equations that consisitently describes a physical phenomena. Examples of such systems abound in the scientific literature ranging from ordinary differential equations to complex integro-algebraic-differential equations arising in quantum field theory.

A recurring theme of solutions to these problems is to recast them in terms of iterative algorithms known as the Dwarfs of Computing - https://web.stanford.edu/class/ee380/Abstracts/070131-BerkeleyView1.7.pdf . 

For better or worse there does not exist a single unifying framework that allows one to analyze all the dwarfs. Fortunately, iterative algorithms and discrete dynamical systems are duals -- meaning one can be translated to another; enabling one to convieniently analyse iterative algorithms in a dynamical systems framework.

This repository is a collection of some prominent scientific-computing routines and their duals expressed as dynamical systems (discrete and discretized-versions of continuous dynamical systems.)
