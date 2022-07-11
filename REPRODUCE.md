### viz.gif
1. Get LAMMPS from https://github.com/lammps/lammps
2. Get Fluidmembrane Package from https://doi.org/10.17632/4v53nkv5hc.1
3. Place the .cpp and .h files from Fluidmembrane Package into src of LAMMPS
4. Compile LAMMPS. (Modify the Fluidmembrane files if using new LAMMPS version.)
4. Install NumPy for Python 3 from https://numpy.org
5. Run ./ne.sh in assembly/gen/ne_make/
6. Run ./run.sh in assembly/sim/
7. Run ./viz.sh in assembly/viz/
8. Install OVITO Basic from https://www.ovito.org/
9. Open viz.ovito, reload ne.data and init.lammpstrj and init.dump_local files,
   and export animation as viz.gif.
