Total Alkalinity
================

PIs
  * Andrew G. Dickson (SIO)
  * Frank J. Millero (RSMAS)
Technicians
  * Carmen Rodriguez (RSMAS)
  * Daniela Nestory (SIO)

Total Alkalinity
----------------
The total alkalinity of sea water is defined as the number of moles of hydrogen ion equivalent to the excess of proton acceptors (bases formed from weak acids with a dissociation constant K < 10E-4.5 at 25°C and zero ionic strength) over proton donors (acids with K > 10E-4.5) in 1 kilogram of sample.

Total Alkalinity Measurement System
-----------------------------------
*Sample Delivery System:*

Samples are dispensed using a Sample Delivery System (SDS) which has been calibrated for volume in the lab prior to the cruise. 
Its volume is confirmed immediately before use at sea to ensure a consistent volume will be delivered for each sample. 
The SDS consists of a volumetric pipette, various relay valves, an air pump, and is controlled by a program in LabVIEW 2012.

Before attaching a sample bottle to the SDS, the volumetric pipette is cleared of any residual solution. 
The pipette is then rinsed and filled with the sample. 
The sample overflows and time is allowed for the sample temperature to equilibrate. 

The sample bottle temperature is measured using a DirecTemp thermistor probe inserted into the sample bottle and the volumetric pipette temperature is measured using a DirecTemp surface probe placed directly on the pipette. 
These temperature measurements, along with the bottle salinity, are used to convert the sample volume to mass for analysis.

Samples are delivered into a 250-mL water-jacketed open cell for titration analysis. 
While one sample is undergoing titration, a second sample is prepared with the SDS and equilibrated to 20°C for analysis. 


*Open-Cell Titration:*

The total alkalinity is measured through an open-cell titration with a dilute hydrochloric acid titrant of known concentration. 
A Metrohm 876 Dosimat Plus is used for all standardized hydrochloric acid additions.

An initial aliquot of approximately 2.3-2.4 mL of standardized hydrochloric acid (~0.1M HCl in ~0.6M NaCl solution) is first delivered and the sample is stirred for 5 minutes while air is bubbled into at a rate of 200 scc/m to remove any liberated carbon dioxide gas.

After equilibration, ~19 aliquots of 0.035 ml are added. 
Between the pH range of 3.5 to 3.0, the progress of the titration is monitored using a pH glass electrode/reference electrode cell, and the total alkalinity is computed from the titrant volume and e.m.f. 
measurements using a non-linear least-squares approach (Dickson, 2007).

A Thermo Scientific Isotemp water bath is connected to the water-jacketed open cell to maintain a cell temperature of approximately 20oC. 
An Agilent 34970A Data Acquisition/Switch Unit with a 34901A multiplexer is used to read the voltage measurements from the electrode and monitor the temperatures from the sample, acid, and room. 

The calculations for this procedure are performed automatically using LabVIEW 2012. 


Sample Collection
-----------------
Alkalinity samples are drawn using silicone tubing connected to the Niskin bottles and collected into 250 mL Pyrex bottles. 
The sample bottles and Teflon-sleeved glass stoppers were rinsed at least twice before the final filling. 
A headspace of approximately 3 mL was removed and 0.05 mL of saturated mercuric chloride solution was added to each sample for preservation. 
The samples were equilibrated prior to analysis at approximately 20°C using a Thermo Scientific Isotemp water bath.

Samples for total alkalinity were taken at all stations during A22 (1-90). 
Except for a few instances, alkalinity samples were collected from each niskin where DIC and pH were collected, to over-characterize the CO2 system. 
The typical sample scheme of full collection on even-numbered stations (36 niskin bottles) and partial collection (~8-20 bottles) on odd-numbered stations was followed.

In order to evaluate the reproducibility of the alkalinity system, duplicate samples (two separate alkalinity bottles) were collected at a minimum of 10% of total samples. 
For instance, when all 36 niskins were sampled, 3 duplicate samples were collected for alkalinity. 
When alkalinity sampled a partial cast, one or two duplicate samples were collected. 


Problems and Troubleshooting
----------------------------
There were a few issues encountered at the start of the cruise which delayed sample processing but did not impede sample intake. 
It was determined that the SDS_A system, which had been used on Leg 1 (A20), was leaking and further use would be problematic for this leg. 
The spare system (SDS_B) was swapped in and extra time was needed to confirm the accuracy and stability of the replacement SDS. 
Surplus alkalinity bottles were available to stockpile samples so productivity was not impeded. 
Also at the start of the cruise, an error in the Labview program’s file creation resulted in configuration equations being omitted which had to be reinput by hand initially. 
A typo in the input equations was soon discovered and corrected. 

The SDS system occasionally freezes at different points in the procedure. 
However the technicians were alert to this issue and were able to save most samples when this occurred.

Although the temperature in the lab was very stable for the majority of the cruise, just before entering the Gulf Stream (starting at station 71), the room temperature dropped by approximately 2oC. 
The acid temperature dropped as well, causing errors in the calculations. 
The engineers of the R/V TG Thompson worked to increase and stabilize the room temperature. 
The cool climate continued for a couple of days, so time was spent to combat temperature instability. 
Samples were not run when the appropriate range in temperature could not be achieved.

Quality Control
---------------
Certified Reference Material (CRMs) and duplicate samples (two bottles collected from one niskin) were used to quality check the functioning of the total alkalinity system throughout the cruise. 

Dickson laboratory Certified Reference Material (CRM) Batches 178 and 192 were used to determine the accuracy of the total alkalinity analyses. 
The total alkalinity certified value for these batches are:

* Batch 178: 2216.53 ± 0.61 µmol/kg (132; 75)

* Batch 192 2213.70 ± 0.53 µmol/kg (132; 67)

The cited uncertainties represent the standard deviation. 

Figures in parentheses are the number of analyses made (total number of analyses; number of separate bottles analyzed).

A CRM sample was analyzed at a minimum frequency of once per every 20 runs, but more often once per every 15 runs. 
Because total alkalinity is not affected by gas-exchange, brand new CRM bottles were reserved for pH and DIC analysis. 
These pre-opened bottles were subsequently used for alkalinity analysis. 
264 reference material samples were analyzed on A22. 

The average measured total alkalinity value for each batch is:

* Batch 178: 2217.97 ± 1.99 µmol kg-1 (n = 132)

* Batch 192: 2214.40 ± 1.80 µmol kg-1 (n = 132)

Duplicate samples were also used to check the reproducibility of the system. 
The absolute value of the mean offset between duplicate samples and the standard deviation are given below.
Mean duplicate sample offset: 1.35 ± 1.03 µmol kg-1 (n = 161)

1884 total alkalinity values were submitted for A22. 

Further dilution corrections need to be applied to this data back onshore, therefore, this data is to be considered preliminary.
