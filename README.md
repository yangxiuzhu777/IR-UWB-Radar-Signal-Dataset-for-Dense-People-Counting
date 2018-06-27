IR-UWB Radar signal dataset for dense people counting 
Overview
People counting is one of the hottest issues in sensing applications. The impulse radio ultra-wideband (IR-UWB) radar provides a device-free solution to count people without illumination and privacy concerns. However, the difficulty to acquire labeled radar data for the specific number of people limits the development of algorithms. 
This dataset consists of 376,000 impulse radio ultra-wideband (IR-UWB) radar signals from at most 20 people in three dense scenarios, including 0-20 people randomly walking in a constrained area with densities of 3 and 4 persons per square meter, and at most 15 people stand in a queue with an average distance of 10 centimeters.

Radar System  
The IR-UWB radar data from a select number of people in a space is acquired by a Novelda NVA-R661 radar module, shown in Fig. 1. 

Fig. 1 : Novleda NVA-R661 radar module
Parameters of the radar system are listed in Table 1.
Table 1 Setup of the NVA-R661 radar system
Output pulse center frequency	Bandwidth, -10 dB	Sampling frequency in the receiver
6.8 GHz	2.3 GHz	39 GHz

Experimental Setup
The radar data is acquired in an open lobby, where the radar is installed at a height of 1.8 meters, with the detecting range of 5 meters and a central angle of 90 degrees. The dataset consists of three dense scenarios.
Scenarios 1 and 2  (Fig. 2)
0-20 people randomly walking in a constrained area with densities of 3 and 4 persons per square meter respectively. 
Scenario 3  (Fig. 3)
At most 15 people stand in a queue with an average distance of 10 centimeters.
44 testers participate in experiments for acquiring diverse data from different people.
        
Fig. 2: Experimental setup in scenarios 1 and 2      Fig. 3: Experimental setup in scenario 3

Dataset Description
For a specific number of people in each scenario, 8000 radar signals are collected, where 200 received signals are recorded for each measurement. Each signal in a radar sample contains 1280 sampling points representing the 5 meters detection range (for the spatial resolution of 0.0039 meter). 248,000 radar signals are generated in scenarios 1 and 2, with a total of 128,000 radar signals in scenario 3. The dataset is in .mat format with each measurement, the dataset is described as Table 2.
Table 2 Dataset Description
Scenario 1	Scenario 2	Scenario 3 
0-10 people randomly walking in a constrained area, for a total of 88,000 radar signals (440 measurements)
Dataset part 1	
0-15 people people stand in a queue with an average distance of 10 centimeters, for a total of 128,000 radar signals (640 measurements)
Dataset part 4
11-20 people with density of 3 persons per square meter, for a total of 80,000 radar signals (400 measurements)
Dataset part 2	11-20 people with density of 4 persons per square meter, for a total of 80,000 radar signals (400 measurements)
Dataset part 3	


Reference:
[1] 
