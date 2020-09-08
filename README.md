# LFR-formally-verified

# Requirements
 1. Linux-like OS (currently tested on Ubuntu 16.04)
 2. Prototype Verification System (PVS), downloadable [here](http://pvs.csl.sri.com/cgi-bin/downloadlic.cgi?file=pvs-6.0-ix86_64-Linux-allegro.tgz) after acceptance of the license
 3. PVSio-web, downloadable [here](https://github.com/pvsioweb/pvsio-web)
 4. INTO-CPS Application, downloadable [here](https://github.com/INTO-CPS-Association/into-cps-application/releases/download/v4.0.0/into-cps-app-4.0.0-linux-x64.zip)
 
# Instructions for co-simulation

 1. Copy the PVS folder `pvs-6.0-ix86_64-Linux-allegro` in the following directories:
    1. models/Attacked_control/resources/
    2. models/Extended_attack/resources/
    3. FMUS/extended_robot.fmu{/resources}
    4. FMUS/line_following_robot_atacked.fmu{/resources}
    
...these last 2 directories are within the zip file of the fmu.

 2. Launch the INTO-CPS application and open the `INTO-CPS_linear_displacement_project` project

 3. If not already done, download the coe from the download manager of the INTO-CPS application (this is a one time only operation)

 4. Expand the `LFR_attacked` Multi-Model (+ button) and open the `experiment` scenario

 5. Launch the coe and then start the simulation
