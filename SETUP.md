**LAMMPS Setup:** LAMMPS is the software used for the simulations.
1. First, setup Linux Shell in Windows using steps in this link: https://gist.github.com/pranjal-s/291b9efa29a8dc811a8bca98b72d9de3
2. In Windows, make the folders such that you have this path: C:\Files\Linux\sw\.
3. Copy mylammpsfiles folder and mylammps.sh to it. The mylammpsfiles folder is currently empty but you should still copy it along with the ‘.sh’ file.
4. Open that path in Linux Shell using ‘cd /mnt/c/Files/ Linux/sw/’
5. Follow the steps in header comments in mylammps.sh file.
6. Then run mylammps.sh itself and enter ‘y’ when asked to Download. Similarly enter ‘y’ to (Re)make.

**OVITO Setup:** OVITO is the software used for view the data from simulations to make animations and figures. \
The process for this is to simply download OVITO Basic (i.e. the free version) for Windows from their website at https://www.ovito.org/download/master/ovito-basic-3.7.7-win64.exe and follow the installation steps.

**Troubleshooting:**
If the ‘.sh’ file doesn’t run, the error can be because the file is native to Windows. The fix for this is very simple: 
1. Install dos2unix in Linux Shell using ‘sudo apt install dos2unix’.
2. Then make the file runnable in Linux Shell via ‘dos2unix filename.sh’
3. The file would still be directly editable in Windows using the VS Code
