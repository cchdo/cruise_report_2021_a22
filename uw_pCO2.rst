Underway |pCO2|
=========================================

PIs
  * Richard Feely (NOAA/PMEL)
Analysts
  * Andrew Collins (NOAA/PMEL)

The partial pressure of |CO2| (|pCO2|) in the surface ocean was measured throughout the duration of this expedition with a General Oceanics 8050 underway system. Uncontaminated seawater was continuously passed (~2.8 l/min) through a chamber where the seawater concentration of dissolved |CO2| was equilibrated with an overlying headspace gas. The |CO2| mole fraction of this headspace gas (xCO2) was measured approximately every three minutes via a non-dispersive infrared analyzer (Licor 7000). Roughly every three hours, the system measured four gas standards with known |CO2| concentrations certified by the NOAA Earth Science Research Laboratory in Boulder, CO ranging from ~300 – 900 ppm |CO2|. Additionally, a tank of 99.9995% ultra-high purity nitrogen gas was measured as a baseline 0% |CO2| standard. Following measurements of standard gases, six measurements of atmospheric xCO2 were made of air supplied through tubing fastened to the ships starboard jackstaff. Twice a day, the infrared analyzer was calibrated via a zero and span routine using the nitrogen gas and the highest concentration (872.6 ppm) |CO2| standard. In addition to measurements of seawater xCO2, atmospheric xCO2, and standard gases, several variables were monitored to evaluate system performance (e.g. gas and water flow rates, pump speeds, equilibrator pressures, etc). For more detail on the general design of this underway |pCO2| system, see [Pierrot2009]_.

A Seabird (SBE) 38 temperature sensor located at the ship's seawater intake provided measurements of in situ seawater temperature, while a SBE 45 thermosalinograph monitored temperature and salinity in the bow of the ship before the seawater reached the |pCO2| system. An Aanderaa 4330 optode plumbed in line with the |pCO2| system water supply measured dissolved oxygen (DO) continuously. Additionally, a modified SeaFET system was also plumbed in line which measured pH throughout the duration of the cruise.

A preliminary round of processing was performed on this dataset using Matlab routines developed by Denis Pierrot of the Atlantic Oceanic and Meteorological Lab in Miami, FL. In one brief (10 minute) instance, the underway system was shut down for minor maintenance to be performed. Two brief instances of data loss occurred when the ships data transmission dropped, resulting in the loss of position, temperature, salinity, etc data for 217 |pCO2| measurements. These measurements will be merged with the |pCO2| dataset during the next round of processing. Of 12,897 measurements, only 13 were assigned a WOCE quality flag of 4 (bad measurement), all of which were due to contamination of atmospheric measurements by exhaust from the ship. At this time, no measurements were assigned a quality flag of 3 (questionable measurement). Measurements of gas standards were within 1% of their certified value throughout the duration of the expedition, save for one brief initial period where the Licor demonstrated some drift (Figure 1). 

Preliminary review of collected data suggest that the main control on the surface seawater carbonate system was temperature (Figure 2). Excursions from thermodynamic controls on |pCO2|, pH and DO were measured in the northern section of the cruise on line W, where mild undersaturation (~320 ppm) relative to atmospheric values of |pCO2| were measured. Concomitant changes were observed in discrete measurements of pH, DO, DIC, and other variables. Fluorescence and chlorophyll data suggest the presence of a prolonged phytoplankton bloom, which likely explains these observations. However, further evaluation of these data and the supplementary suite of discrete surface CTD measurements that were collected is needed before the controls on |pCO2|, pH and DO can be fully elucidated. 

This dataset should be considered preliminary; additional quality control and quality assurance is needed before these data can be considered final. 

.. figure:: images/pCO2/offset.*

  Difference between measurements made by the non-dispersive infrared analyzer (Licor 7000) of gas standards and the known certified value of those standards (in ppm |CO2|).

.. figure:: images/pCO2/pCO2_surface.*

  Spatial distribution of relevant parameters (sea surface temperature [SST, ºC], sea surface salinity [PSU], fCO2 [ppm], air-sea fCO2 disequilibrium [ppm] and dissolved oxygen [µM]) measured by the underway |pCO2| system during the 2021 GO-SHIP A22 research expedition.


.. [Pierrot2009] Pierrot, D., Neill, C., Sullivan, K., Castle, R., Wanninkof, R.W., Lüger, H., Johannessen, T., Olsen, A., Feely, R.A., Cosca, C.E.;
    2009. Recommendations for autonomous underway pCO2 measuring systems and data-reduction routines. Deep-Sea Research II 56 (2009) 512–522 
