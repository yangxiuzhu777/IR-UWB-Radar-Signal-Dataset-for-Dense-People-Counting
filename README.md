IR-UWB Radar Signal Dataset for Dense People Counting 
==
Overview
--
People counting is one of the hottest issues in sensing applications. The impulse radio ultra-wideband (IR-UWB) radar provides a device-free solution to count people without illumination and privacy concerns. However, the difficulty to acquire labeled radar data for the specific number of people limits the development of algorithms. 

This dataset consists of 376,000 impulse radio ultra-wideband (IR-UWB) radar signals from at most 20 people in three dense scenarios, including 0-20 people randomly walking in a constrained area with densities of 3 and 4 persons per square meter, and at most 15 people stand in a queue with an average distance of 10 centimeters.

Radar System  
--
The IR-UWB radar data from a select number of people in a space is acquired by a Novelda NVA-R661 radar module, shown in Fig. 1. 

![](https://github.com/yangxiuzhu777/IR-UWB-Radar-Signal-Dataset-for-Dense-People-Counting/raw/master/Fig1.png)  

Fig. 1: Novleda NVA-R661 radar module.

Parameters of the radar system are listed in Table 1.

Table 1: Setup of the NVA-R661 radar system.
![](https://github.com/yangxiuzhu777/IR-UWB-Radar-Signal-Dataset-for-Dense-People-Counting/raw/master/Table1.png)


Experimental Setup
--
The radar data is acquired in an open lobby, where the radar is installed at a height of 1.8 meters, with the detecting range of 5 meters and a central angle of 90 degrees. 

The dataset consists of three dense scenarios.

`Scenarios 1 and 2  (Fig. 2)`

0-20 people randomly walking in a constrained area with densities of 3 and 4 persons per square meter respectively. 

`Scenario 3  (Fig. 3)`

At most 15 people stand in a queue with an average distance of 10 centimeters.

`44 testers` participate in experiments for acquiring diverse data from different people.

![](https://github.com/yangxiuzhu777/IR-UWB-Radar-Signal-Dataset-for-Dense-People-Counting/raw/master/Fig2.png) <br>
Fig. 2: Experimental setup in scenarios 1 and 2.      

![](https://github.com/yangxiuzhu777/IR-UWB-Radar-Signal-Dataset-for-Dense-People-Counting/raw/master/Fig3.png) <br>
Fig. 3: Experimental setup in scenario 3.

Dataset Description
--
For a specific number of people in each scenario, 8000 radar signals are collected, where 200 received signals are recorded for each measurement. Each signal in a radar sample contains 1280 sampling points representing the 5 meters detection range (for the spatial resolution of 0.0039 meter). 248,000 radar signals are generated in scenarios 1 and 2, with a total of 128,000 radar signals in scenario 3. The dataset is in `.mat format` with each measurement, the dataset is described as Table 2.

Table 2: Dataset Description.
![](https://github.com/yangxiuzhu777/IR-UWB-Radar-Signal-Dataset-for-Dense-People-Counting/raw/master/Table2.png)


Reference
--
[1] X. Yang, W. Yin, L. Li and L. Zhang, "Dense People Counting Using IR-UWB Radar with a Hybrid Feature Extraction Method," arXiv preprint arXiv:1806.06629. 
