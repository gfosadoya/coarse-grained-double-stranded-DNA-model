We model double-stranded DNA (dsDNA) as made of two bead-spring polymers, each representing one single-stranded DNA (ssDNA). In order to couple the two strands into a double-helix, patches are attached to the beads and interaction potentials are assigned to reproduce the geometry of a B-DNA molecule. All these potentials are explained in detail in our soft matter paper (see below). 

Here you will find the minimal requirements (initial configurations and LAMMPS scripts) to get started with the simulations of:

    a)Linear and ring DNA molecules without explicit phosphates.
    b)Linear and ring DNA molecules with explicit phosphates.
    c)The protocols for denaturation of linear and DNA molecules (only for the case without explicit phosphates).
    d)Major groove binding proteins.

A brief explanation of the implementation in each of these cases is provided in the README files inside the corresponding folders.

For details in the model see our paper:
Y. A. G. Fosado, D. Michieletto, J. Allan, C. A. Brackley, O. Henrich and D. Marenduzzo "A single nucleotide resolution model for large-scale simulations of double stranded DNA" Soft Matter 12 9458-9470 (2016).

For details in the denaturation of linear and rind DNA molecules see:
Y. A. G. Fosado, D. Michieletto, and D. Marenduzzo "Dynamical Scaling and Phase Coexistence in Topologically Constrained DNA Melting" Phys. Rev. Lett. 119, 118002 (2017).

All the LAMMPS scripts have been tested using the current version of LAMMPS (22-Aug-2018). Please make sure that the ASPHERE, RIGID, MOLECULE and USER-MISC packages are installed. These are standard packages that come with LAMMPS, and can be enabled before compiling, e.g. with the command:

make yes-asphere
# coarse-grained-double-stranded-DNA-model
