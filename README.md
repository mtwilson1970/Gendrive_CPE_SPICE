# Gendrive_CPE_SPICE
12-day battery driving sequence for CPE-SPICE article

This is a link to the  data sequence used for the 12-day driving of the battery in Section 3 of
the paper M.T. Wilson et al. "Rapid time-domain simulation of fractional capacitors with
SPICE" (2024) in Journal of Computational Electronics.  See Figure 9 of the paper.

Data is too large for github but the link here is to the data on a OneDrive account hosted by 
the University of Waikato
https://waikatouniversitynz-my.sharepoint.com/:f:/g/personal/marcus_wilson_waikato_ac_nz/ElykGoB_HVZKuVGMWztEJUEBnPBAxHAAaXtiSLfuip1HMw?e=3Xdkc8


The file is provided in two formats. The first, labeled .tvi,  is a .csv file, consisting of three columns:
Column 1: Time since experiment start (s)
Column 2: Terminal voltage (V)
Column 3: Current (A)

The second file is the same data, provided as a matlab .mat data file. There is one variable, consisting of three 
columns as described above. 

Any further questions, do ask me. 

The CPE-Spice model code itself (for generating the CPE model in SPICE),
written by Vance Farrow and Logan Cowie, is available at https://github.com/Rockscanfly/Fractional_Capacitor_SPICE 

