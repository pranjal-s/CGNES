# assembly: assembly module

Date:               10-Apr-22
Version:            0.9.0

### Description of files in this directory
README.md           this file
param/*             calculations of model parameters
gen/*               generates initial configuration of nuclear components
sim/*               assembly of nuclear components
viz/*               visualization of the assembled structure
data/*              storage of numerical data
fig/*               save visualizations

### Usage

1. Experimentally guided calculation of simulation units and model parameters
   is done in param/param.ods. The parameters have already been input into the
   files downstream.

2. The gen/README.md has instructions on generating the initial configuration
   (data/ne.data).

3. Next, the sim/README.md has instructions on simulating assembly of NE.

4. Finally, the viz/README.md has instructions on visualization of the
   assembly of NE.

5. The data/* directory (created at runtime) stores all numerical output. A
   description of files expected to be output in this directory is included
   below.

6. The visualizations can be saved to fig directory (created at runtime).

### Description of files in ./data/
ne.data             initially generated NE structure
init.out            LAMMPS log output during assembly simulation
init.lammpstrj      particle positions during assembly simulation
init.dump_local     bond topology during assembly simulation
init.data           assembled structure (also called CGNE structure)
init.restart        restart file to initialize post-assembly simulations
equil.txt           equilibrium temperatures, energies and lateral tension.
ne2.data            initial structure processed for visualization
