# Alpha_graphs

Written by Eva C. Herbst

Matlab to graph and export alpha shapes from joint range of motion data, as part of our paper on using alpha shapes along with digital marionettes in Maya to investigate limb configurations.

The code enabels plotting of mobility data (as Euler angles) and creation of alpha shapes from these points. A color-blind friendly palette is used for plotting.

An example from Herbst et al. 2022 is shown at the bottom of the README file.

Inputs: .csv file with Euler rotations as columns
Outputs: Matlab figure, .obj of alpha shape


:pencil:  Please read our [paper](https://doi.org/10.1093/icb/icac083), which I wrote with Armita R. Manafzadeh and John Hutchinson. If you use this method, please cite our paper (Herbst et al. 2022) [![DOI:10.1093/icb/icac083](http://img.shields.io/badge/DOI-10.1093/icb/icac083-GREEN.svg)](https://doi.org/10.1093/icb/icac083) and the doi of the most recent Github release:
[![DOI](https://zenodo.org/badge/495432627.svg)](https://zenodo.org/badge/latestdoi/495432627)

Our Maya code for our limb configuration tool can be found [here](https://bitbucket.org/xromm/xromm_other_mel_scripts/src/main). 



![](alpha_new_knee_order.png)
Figure 5 from Herbst et al. 2022. Alpha shapes illustrating osteological RoM for the E. megacephalus hip (A,B) and knee (C-H) joints. C-D) Knee spacing option A (tight
spacing); E,F) knee spacing option B (intermediate spacing); G,H) knee spacing option C (large spacing, same relative joint spacing as salamander in
null pose). Salamander joint poses used during key phases of the walking stride cycle are depicted as circles, replicated poses in E. megacephalus are
depicted as triangles. Purple: mid-swing, blue: toe-on, green: mid-stance, yellow: just before toe-off.
