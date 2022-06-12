# frying-pan-sauteing-mechanism
Single DoF frying pan sauteing mechanism

## Kinematic Synthesis
Captured the movement of the sauteing pan movement with a camera. Analyised it with *Tracker* software. Chosed 4 precision points which we used to gather the x and y values of the end effector and oriantation of the coupler link. *Objective function* is obtained and then *body guidance synthesis method* with *polynomial approximation* then used to obtain the construction parameters of the four-bar mechanism.

## Kinematic and Dynamical Analysis
Calculated required torque to supply the motion and reaction forces on bearings for 360 degrees of rotation for crank angle and plotted the results.
### Notes
-Excel File Kinematic Analysis.xlsx is where we first logged data and took first numerical derivatives

-accAnalysisFiltered.mat is results of Kinematics.mlx file

-datacode.m is there for converting excel files into matlab code, we saved these datas onto KinematicData.mat file

-accfilter.mat is result of filtering in data_plotting.mlx

-matrixForm.mlx is for dynamical analysis, it's results are in DynamicalData.mat file

-lastly we obtained final graphs from draw_results.mlx
