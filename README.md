# FW_Castelluccio_di_Norcia_2019
Shared files of the INGV ERT Fullwaver survey @Castelluccio di Norcia - 2019_05_13-23

This repository collects all the files for the ERT FullWaver geophysical survey held on May 13-23 2019 at the site of Pian Grande and Pian Piccolo at Castelluccio di Norcia (PG), Italy.
This is a research project by **INGV Rome**.

Files in this repository are organized as follows:

- the **field_data** folder contains the ERT resistivity and chargeability datasets acquired by using the IRIS Instruments Fullwaver system 
  (24 VFullwaver boxes, 15 and 200 meters MN dipoles) and a VIP5000 transmitter used to inject current at TX electrodes. The **raw** directory hosts the raw files acquired by the Fullwaver boxes, divided by the acquisition days and areas. The bin file contains the pre-processed measurements ready for processing. The conversion table txt file is used to translate the dummy coordinates of the raw datasets into the real positions.
- The **DTM** folder contains the xyz digital terrain file of the survey area.
- The **processing** folder contains the ERTLab data file with configuration before processing and the data file with resistivity/IP models 
after inversion. PNG files with inversion progress are included.
- The **topography** folder hosts the kml file with the sensor positions after the field topographic survey and a xlsx spreadsheet with the definitive coordinates of the receiving and transmitting electrodes in the UTM WGS84 coordinate system.
