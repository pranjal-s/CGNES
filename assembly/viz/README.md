# viz: visualization sub-module

Date:               09-Jul-22
Version:            0.9.0

### Description of files in this directory
README.md             this file
viz.sh                processing structure file for visualization (viz)
viz.ovito             viz of ne.data and init.lammpstrj in ../data/

### Usage
1. Run the viz.sh to process ../data/combined.data.
2. On first time run, the OVITO file may require manual reloading of
   ne.data and init.lammpstrj from ../data/ into the 'Data source' and the
   'Load trajectory' in the 'Modifications' pipeline respectively.
