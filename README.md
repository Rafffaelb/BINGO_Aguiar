This repository contains experimental data collected by the UFCG's researchers Rafael Batista and Lucas Santana using spectrum analyzers at the BINGO Radio Telescope site, located in the city of Aguiar, Paraíba, Brazil.

For this experiment, we used the Antenna Module HE400UWB from ROHDE & SCHWARZ and two spectrum analyzers: the FPH from ROHDE & SCHWARZ and the FieldFox from Keysight Technologies. We used the FPH to collect the GPS data, while the FieldFox was used to measure the Clear/Write, Average, Minimum, and Maximum values of the signal.

As you can see in the FieldFox folder, we collected data at six points on the site: the Base (B), the Helipad (H), the secondary dish base (P1), the primary dish base (P3), the base of the horns (P5), and an external point located along the path to the base P1 (PEXT).

For each point, we pointed the antenna towards 4 cardinal points, 4 collateral points, and the zenith (AZ). The 4 cardinal points are North (Norte), South (Sul), East (Leste), and West (Oeste), represented in the dataset as N, S, L, and O, respectively. The 4 collateral points are Northeast (Nordeste), Southeast (Sudeste), Southwest (Sudoeste), and Northwest (Noroeste), represented in the dataset as NE, SE, SO, and NO, respectively.

All data mentioned above were collected in a frequency band from 50 MHz to 1.6GHz, with Resolution (RBW) and Video (VBW) Bandwidth of 2 MHz and 30 kHz, respectively.

Note: on the helipad, we pointed the antenna towards the base that has a wifi antenna. We observed the wifi signal without LNA, HWIFI.csv, and with the LNA connected, HWIFILNA.csv, both files are located in the FieldFox/H/ folder. To be able to see the Wifi signal, we collected the data in a frequency band from 2 GHz to 2.6 GHz.






