# Z-Tek_Cubesat_ADCS
AD ASTRA PER ASPERA
-
Cubesat ADCS code written by Zarvan Movdawalla and Team, from MPSTME India.
-
Striving to develop a 3u+ Cubesat, with a rudimentary ADCS, and fail-tolerant architecture.

Primary Processor: RP2040, on Raspberry Pi Pico

Sensors:
MPU6050/LSM6x
XMC5883

PRIMARY SYSTEM ARCHITECTURE:
PRIMCOMP -> ADCS
         -> EPS
         -> RF-TRANSCVR

DATALINK VIA: SX1278 (custom PA/LNA)
