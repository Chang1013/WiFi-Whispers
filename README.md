CSI Collect Tool
====
*PicoScenes [link]: https://ps.zpj.io/scenarios.html <br>
In our experiment, we use the Intel AX 200 network interface card.<br>

Environment settings
====
* Two laptop os are Ubuntu 20.04 <br>
* Install Matlab R2022b to plot the signal waveform image<br>

Hardware Setup
====
* Two laptop and one wifi device<br>
* Transmitter (TX) : D-link DIR-X1560 AX1500 <br>
* Receiver (RX) : ASUS VivoBook S510UN laptop<br>
* Attacker : DELL Vostro 5410 laptop<br>

Dataset
===
* Two experimenter: Person A and Person B<br>
* Each Person has four dataset (door path1, door path2, wall path1 and wall path2)<br>
  * door mean RX placed behind the door<br>
  * wall mean RX placed behind the wall<br>
* Training set: only use person B<br>
* Test set: only use person A<br>



Human Activity Recognition Accuracy
====
| case          | walking       | empty  |
|:-------------:|:-------------:|:-------------:|
| door path1    | 100%          | 100%          |
| door path2    | 100%          | 100%          |
| wall path1    | 100%          | 100%          |
| wall path2    | 100%          | 100%          |
