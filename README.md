# MD simulations of *Arabidopsis thaliana* EPS1
## [Parameterization for ligands](./Parameterization)
- `xxx.pdb`: structure file of xxx.
- `xxx_CGenFF.str`: parameters originally given by the CGenFF server.
- `xxx_opt.par`: parameters refined by FFTK.
- `xxx_opt.top`: topologies refined by FFTK.
## [Simulated annealing of IGA-bound pose](./MD_wildtype-EPS1/holo-EPS1_IGA/simulated-annealing)
- `initial.gro`: initial structure from docking. (after energy minimization and equilibrations)
- `final_runi.gro`: final structure from the ith replica. (after energy minimization)
## [MD simulations of wildtype EPS1](./MD_wildtype-EPS1)
- `input`: input files for MD simulations.
- `xxx_initial.gro`: initial structure file of xxx. (after energy minimization and equilibrations)
- `xxx_runi-2μs.gro`: final structure file of xxx from the ith replica at 2μs.
- `cluster1_xxx.pdb`: centroid structure of the top cluster from the clustering of xxx.
## [MD simulations of mutant EPS1](./MD_mutant-EPS1)
- `input`: input files for MD simulations.
- `xxx_initial.gro`: initial structure file of xxx. (after energy minimization and equilibrations)
- `xxx_runi-2μs.gro`: final structure file of xxx from the ith replica at 2μs.
- `cluster1_xxx.pdb`: centroid structure of the top cluster from the clustering of xxx.
## [MD simulations of IGA in water](./MD_IGA-in-water)
- `input`: input files for MD simulations.
- `xxx_initial.gro`: initial structure file of xxx. (after energy minimization and equilibrations)
- `xxx_runi-2μs.gro`: final structure file of xxx from the ith replica at 2μs.
- `cluster1_xxx.pdb`: centroid structure of the top cluster from the clustering of xxx.
