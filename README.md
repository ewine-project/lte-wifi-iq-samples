Readme:
This file provides a summary regarding the nature-of-collection and contents of the data samples linked in this space.

The provided data samples contain the raw I&Q samples collected over the air by Jerome Arokkiam, from commercial LTE and WiFi base stations. Data collection was carried out:
-in the CONNECT building (Dunlop Oriel House) in Dublin 2, in Ireland, in the 2nd floor, where CONNECT's testbed was located at the time of collecting the data.	
-using the B210 USRP from Ettus research. At the time of data collection, we had four B210s in our pocession, each having four antenna slots (sections A and B, each having a Tx/Rx and an Rx antenna slot)

Naming convention of the the data file is as follows:
technology-centreFrequency-antennaGain-sampleCaputuredRate-capturedBandwidth-captureInstance.bin
An example would be:
wifi-5660MHz-gain30dB-capturedRate15Msps-bandwidth15MHz-it1.bin, where the captured signal:
1. is received from a wifi base station
2. has a centre frquency of 5660MHz and a bandwidth of 15MHz
3. is sampled at a rate of 15Msps and with an antenna gain of 30dB
4. and is the first capture instance (it1) having the settings 1 to 3.
