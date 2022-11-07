<p align="center">
  <img src="https://github.com/MarcoMustacchi/MarcoMustacchi.github.io/blob/main/assets/img/icons/UniPD_logo.svg" width="150">
</p>

<h1 align="center">Robotics I - Homeworks Assignments <br> UniPd</h1>

<a href="https://github.com/MarcoMustacchi/Robotics1HW/raw/master/HW1/Marco_Mustacchi_Robotics_I_HW1.pdf">📄HW1-Paper</a>
<br>
<a href="https://github.com/MarcoMustacchi/Robotics1HW/raw/master/HW2/Marco_Mustacchi_Robotics_I_HW2.pdf">📄HW2-Paper</a>

## Software requirements
### HW1
* MATLAB
* Simulink

### HW2
* MATLAB
* Simulink
* CasAdi

## Installation
To install *CasADi* download the source files from the official <a href="https://web.casadi.org/get/">website</a>, extract the folder and update your MATLAB path adding the *CasADi* folder. (from the MATLAB IDE click on *Set Path*, *Add folder* and then select the folder extracted)

To check that everything went fine runt the following commands on the MATLAB workspace:
```
import casadi.*
x = SX.sym('x')
```
in the case the system returns an error, you probably need to check again the installation procedure.

<br>

> All MATLAB script files are protected 
