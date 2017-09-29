Readme:
This file briefly describe the nature-of-collection and contents of the data samples provided (linked) in this space.

SCOPE:
The unlicesend band is faced with the new challenge of LTE-WiFi co-existence, with the recent standardisation of LTE for the operation in the unlicensed band (LTE-LAA, LTE-U), and the listen-before-talk behaviour of the soft-incumbent, WiFi, in the unlicensed band. Since the unlicesned band has a large chunk of 'free' bandwidth in the 5GHz in addition to the saturated 2.4GHz, channel selection has been proposed as one of the techniques to enable fair usage of the unlicensed band by the dominant (heavily used) LTE and WiFi technologies.

We have proposed machine learning based classification to identify the incumbent technology (between WiFi and LTE) at a given time at a given frequency in the unlisenced band. In order to validate a machine learning model for accuracy at different channel conditions between LTE and WiFi, a substantial amount of data samples are required for training and cross-validating the machine learning model.

This space provides some sample data sample files collected:
  1. is received from a wifi base station
a. in the CONNECT building (Dunlop Oriel House) in Dublin 2, in Ireland, in the 2nd floor, where CONNECT's testbed was located at the time of collecting the data
  b. using the B210 USRP from Ettus research. At the time of data collection, we had four B210s in our pocession, each having four antenna slots (sections A and B, each having a Tx/Rx and an Rx antenna slot)
  c. by Jerome Arokkiam, as transmitted by commercial LTE and WiFi base stations.


Naming convention of the the data file is as follows:
technology-centreFrequency-antennaGain-sampleCaputuredRate-capturedBandwidth-captureInstance.bin
An example would be:
wifi-5660MHz-gain30dB-capturedRate15Msps-bandwidth15MHz-it1.bin, where the captured signal:
1. is received from a wifi base station
2. has a centre frquency of 5660MHz and a bandwidth of 15MHz
3. is sampled at a rate of 15Msps and with an antenna gain of 30dB
4. and is the first capture instance (it1) having the settings 1 to 3.
