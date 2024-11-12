# Instructions

Example macros for running Pandora particle flow algorithm on CLD geometry with noble liquid calorimeter barrel plugged in. The geometry description can be found in [CLD_o4_v05](https://github.com/key4hep/k4geo/tree/main/FCCee/CLD/compact/CLD_o4_v05).

Caveat: Local changes in repository https://github.com/faltovaj/k4geo needed. To be pushed in the official branch.

- Step 0: setup the key4hep SW
```
source /cvmfs/sw.hsf.org/key4hep/setup.sh
```

- Step 1: run the simulations (example with ddsim)
```
source run_ddsim.sh
```

- Step 2: run the digitization and reconstruction with Pandora
```
fccrun runPandora.py
```
