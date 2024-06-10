# Molecule_random_walk
A random walk of molecules to circumvent shrinkage step in initialization of simulations. Creates a box of specified density according to the number and length of molecules. Molecules are assembled through a Monte-Carlo simulation which rolls back if issues are encountered. Output is an array of positions of atoms.

Working so far:
- 2D random walk for single and multiple molecules (*with* bond crossing if diagonal moves are allowed).
- Prevention of multiple molecules occupying the same site.

To do:
- Try to work on making a version of this that utilizes classes.
- Work on ensuring rollback is allowed instead of solely restarting.
- Prevent bonds from crossing.
- Get output of positions.