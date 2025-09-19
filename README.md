# SPH-DEM-and-SSF-Rendering
This repository provides an implementation of a coupled SPH-DEM model for solid–liquid interaction and a screen-space fluid rendering (SSF) method for real-time visualization. It is designed to support research on debris flow and other geohazard simulations by integrating physical computation with interactive visualization

# Hardware requirements
GPU with at least 8GB of memory.

# Software required
Unreal Engine 5.3.2
Niagara Plugin
NiagaraFluids Plugin
<img width="798" height="477" alt="56d0d85c-7c84-47ab-80d4-a082eb102889" src="https://github.com/user-attachments/assets/255e6346-4d2b-4ebb-98aa-e02996ac13d2" />

# Project File Description
## SPH-DEM-Model.uasset：This project implements an optimized neighbor particle search algorithm together with the coupled solid–liquid model, with the overall design illustrated in the figure below.
<img width="1218" height="836" alt="QQ_1758275699640" src="https://github.com/user-attachments/assets/8641238a-4891-4184-9814-1fd83e0a4ea5" />

## Simulation scenarios and results
<img width="865" height="402" alt="image" src="https://github.com/user-attachments/assets/82ebaa61-1d2a-4918-9233-e37ea1cbf50b" />

## SPH-DEM-Model.uasset
include a deep texture calculation module
<img width="1083" height="744" alt="QQ_1758276450859" src="https://github.com/user-attachments/assets/6afaf0ca-d134-492e-9689-55da808d5926" />

## normal.uasset & normal_Inst.uasset
A method based on local depth variation estimation was implemented to compute normal maps.
<img width="1982" height="656" alt="QQ_1758276684725" src="https://github.com/user-attachments/assets/a270e610-b230-46b7-8be4-90c2e47c2cf4" />

## finalUpdateRt.uasset & finalUpdateRtBefore.uasset
Output the effects of smoothed and unsmoothed depth maps.

## M_SPHWater.uasset & M_SPHWater_Inst.uasset
Material Creation Module
<img width="1664" height="838" alt="QQ_1758276908862" src="https://github.com/user-attachments/assets/0b5ce42e-19bd-496b-a001-3dca534c6e26" />

# Note
Due to GitHub's repository size limitations, the implementations of the SPH-DEM model and the SSF algorithm have been submitted. The experimental scenarios and the field scene used in the final result figures have been uploaded to Mendeley Data.
Download link: https://data.mendeley.com/preview/c2wphd9kkp?a=9700f6ca-c2b7-4003-af1f-917a1f286bdc





