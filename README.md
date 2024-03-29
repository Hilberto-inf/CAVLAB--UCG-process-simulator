# About CAVLAB
CAVLAB is MATLAB's version of the Cavity Simulation Model (CAVSIM), which was originally written in FORTRAN. CAVSIM is a 3-D and 
axissymmetric model that can simulate an Underground Coal Gasification (UCG) process. It has the capability to predict the growth 
of cavity from the start of coal combustion to its complete exhaustion. The model can handle a range of gas injection flow patterns 
or compositions and is applicable to nonswelling coals with any seam thickness.

CAVLAB now offers additional features
to CAVSIM, such as input signals can easily be designed in MATLAB, inputs and outputs are observable in runtime, a controllable
structure wherein the controller design process has become streamlined. Moreover, unlike CAVSIM, CAVLAB is user-friendly
to operate: no compilation, no debugging is required; it is simply plug and play. 


Enjoy simulating the UCG!

### Pre-requisites


- Hardware requirements: Any Intel or AMD x86-64 processor, 4 GB RAM.
- Program language: MATLAB
- Software required: MATLAB/SIMULINK 2019 or higher


## Steps to run CAVLAB: 
                      
 Save the folder CAVLAB anywhere on your hard-drive.
 
 
 Run MATLAB and change its working directory to the folder where you have stored the files in step 1.
 
 
 In MATLAB, in the 'Current Folder' window, double click on the file 'CAVLAB.slx'—This will open the SIMULINK file containing the UCG simulator.
There are two inputs to the UCG plant, I) Steam to oxygen ration, and II) flow rate of gases. Similarly, there are two outputs, I) heating value, and II) flow rate.

 You can run 'CAVLAB.slx' at its default settings and view the UCG simulation results.
 
 
OR


 You can paramatrize the UCG by defining your own inputs, and changing the properties of coal reactor by editing the variables
in 'in.INP' file.

You can also change the time-step information at which the numerical computation of simulation are carried out by editing the:
Simulation---> Configuration Parameters---> Solver details---> Fixed-step size.


#### NOTE: Please don't make changes to any editable files except the ones mentioned above.

#### If you use CAVLAB for your research or teaching purposes, please cite it using the following reference:

Ahmed, A., Javed, S. B., Uppal, A. A., & Iqbal, J. (2023). Development of CAVLAB—A Control-Oriented MATLAB Based Simulator for an Underground Coal Gasification Process. Mathematics, 11(11), 2493. doi: 10.3390/math11112493


