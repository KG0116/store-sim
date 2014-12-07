

**Store-Sim**
===========
## Discrete-Event Simulation  ##
<sub>To run a simultion, Numpy and Tabulate must be installed. </sub>
<br />
<br />
**A simulation can be initiated by entering a terminal command of the following structure:**
<br />
python sim.py 'rate<sub>1</sub>,...,rate<sub>n</sub>'  time_factor(int) time_unit(h,d,m,y) 
<br />
<sub>where rate<sub>1</sub> through rate<sub>n</sub> represent the rate at which customers enter each of the n stores every hour, time_factor represents the number of specified time units, and time_unit can be an hour, day, month, or year. </sub>

<br />
**Sample simulation run:**
<br />
python sim.py '11, 12, 20' 10 day
<br />
<sub>The above command initiates a simulation for three stores with rate<sub>1</sub>=11, rate<sub>2</sub>=12, and rate<sub>3</sub>=20. time_factor=10, and the unit of time is day, so the program will simulate 10 days for the three stores.</sub>

<br />
**Sample output:**
<br />
![sample sim](https://dl.dropboxusercontent.com/s/d6jr7pr63kupe9v/sim.png?dl=0)
