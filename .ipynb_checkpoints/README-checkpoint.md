# Molecule_random_walk
A random walk of molecules to circumvent shrinkage step

Working so far:
- 2D random walk for single and multiple molecules (*with* bond crossing if diagonal moves are allowed).
- Prevention of multiple molecules occupying the same site.

To do:
- Try to work on making a version of this that utilizes classes.
- Work on ensuring rollback is allowed instead of solely restarting.
- Prevent bonds from crossing