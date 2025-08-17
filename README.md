# PKMv3
ProVerif model for PKMv3, including EAP-TLS1.3 authentication protocol.
Warning: ProVerif generates a large amount of input from protocol descriptions. Merging the two models, EAP-TLS1.3 and PKMv3, may result in excessively long execution times and unintended behavior. To successfully combine them into one single file, some modifications to the model will be required.
There are three ProVerif files in this repository:
1- EAP-TLS1.3.pv: contains the EAP-TLS1.3 protocol desciption.
2- PKMv3.pv: contains the PKMv3 protocol description (the EAP authentication phase not included).
3- PKMv3_Related_Work.pv: contains the PKMv3 protocol description found in related work.
