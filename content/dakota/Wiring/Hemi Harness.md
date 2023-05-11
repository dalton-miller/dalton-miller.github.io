---
title: Factory Hemi Harness Pinouts
type: docs
weight: 3
---

Bench harness info can be found at [[Bench Pinouts]].
# C130
Hemi C130 engine side pinout  
![Hemi C130 Connector](/images/hemi-c130.png)
| Pin | Circuit | Fn |
| --- | ------- | -- |
| 1 | D15 18WT/DG | SCI Transmit (TCM) |
| 2 | D16 18WT/OR | SCI Receive (TCM) |
| 3 | K66 18DB/WT | P/S Switch Sig |
| 4 | K342 16BR/WT | ASD Relay Output |
| 5 | G31 18VT/LG | Ambient Air Sig |
| 6 | K106 18VT/LB | Evap Sol Ctrl |
| 7 | K107 18VT/WT | Evap Switch Sig |
| 8 | L1 18WT/LG | Backup Light Feed |
| 9 | T41 20YL/DB | TRS (Park/Neutral) - in N |
| 10 | L10 18WT/GY | Ignition Switch Run (12V+ Key On) |
| 11 | A919 20RD | Battery + |
| 12 | C3 20DB/YL | A/C Clutch Relay Output |
| 13 | F202 20PK/GY | Ignition Switch Run/Start (12V+ Key On) |
| 14 | D20 20WT/LG | SCI Receive (PCM) |
| 15 | D21 20WT/BR | SCI Transmit (PCM) |
| 16 | T16 18YL/OR | Trans Ctrl Relay Output |
| 17 | - | |
| 18 | T6 18DG | Tow/Haul OD-off Switch Sense |
| 19 | K900 20DB/DG | Sensor Ground |
| 20 | T515 20YL/DB | Trans Ctrl Relay Ctrl |
| 21 | K399 18BR/GY | O2 2/2 Heater | Delete |
| 22 | B22 18DG/YL | VSS #1 |
| 23 | - | |
| 24 | D25 18WT/VT | PCI Bus |
| 25 | - | |
| 26 | T751 16YL | Ignition Switch Start (Starter Sw) |
| 27 | K299 18BR/WT | O2 1/2 Heater |
| 28 | F855 18PK/YL | 5V+ |
| 29 | B222 20DG/WT | VSS #2 |
| 30 | F856 18YL/PK | 5V+ |
| 31 | - | |
| 32 | T525 18YL/DB (5.7 Off Road?) | T-case Return |
| 33 | K77 18BR/WT (NGC MTC?) | T-case Position Sense |
| 34 | F1 16PK/WT | Ignition Switch Off/Run/Start (Constant 12V+) |

# PCM
Hemi ECU connectors
C1 = Black: ECU power, diag, coil/inj 7/8
C2 = Orange: remaining coils, injectors, monitoring
C3 = White: aux connections
C4 = Green: tranny connections

![Hemi C1 ECU Connector](/images/hemi-c1.png)

## C1
C1 pinout
| Pin | Circuit | Fn |
| --- | ------- | -- |
| 1 | K98 18DB/YL | Coil #8 |
| 2 | - |
| 3 | K97 18BR | Coil #7 |
| 4 | K28 18BR/LB | Injector #8 |
| 5 | K26 18BR/YL | Injector #7 |
| 6 | - |
| 7 | - |
| 8 | B222 20DG/WT | VSS #2 |
| 9 | Z130 16BK/BR | Ground |
| 10 | - |
| 11 | F202 20PK/GY | 12V+ Key On |
| 12 | F1 16PK/WT | 12V+ Constant |
| 13 | B22 20DG/YL | VSS #1 |
| 14 | - |
| 15 | - |
| 16 | - |
| 17 | - |
| 18 | Z131 16BK/DG | Ground |
| 19 | - |
| 20 | G6 18VT/GY | Oil Pressure |
| 21 | C918 18BK/LB | A/C Pressure |
| 22 | G31 18VT/LG | Ambient Air Temp |
| 23 | - |
| 24 | - |
| 25 | D20 20WT/LG | SCI Rec (PCM) |
| 26 | D16 18WT/OR | SCI Rec (TCM) |
| 27 | F856 18YL/PK | 5V+ |
| 28 | - |
| 29 | A919 20RD | Battery+ |
| 30 | T751 16YL | Ign Sw Out (Start) |
| 31 | K141 18DB/YL | O2 1/2 |
| 32 | K902 18BR/DG | O2 Upstream |
| 33 | K243 18BR | O2 2/2 |
| 34 | - |
| 35 | - |
| 36 | D21 20WT/BR | SCI Tr (PCM) |
| 37 | D15 18WT/DG | SCI Tr (TCM) |
| 38 | D25 20WT/VT | PCI Bus |

## C2
C2 pinout
| Pin | Circuit | Fn |
| --- | ------- | -- |
| 1 | K10 18DB/OR | Coil #6 |
| 2 | K16 18DB/YL | Coil #5 |
| 3 | K15 18DB/GY | Coil #4 |
| 4 | K58 18BR/VT | Injector #6 |
| 5 | K38 18BR/OR | Injector #5 |
| 6 | K447 18TN/YL | Elec Throttle Control Motor + |
| 7 | K18 18DB/OR | Coil #3 |
| 8 | K35 18DB/VT | EGR Sol |
| 9 | K17 18DB/TN | Coil #2 |
| 10 | K19 18DB/DG | Coil #1 |
| 11 | K14 18BR/TN | Injector #4 |
| 12 | K13 18BR/LB | Injector #3 |
| 13 | K12 18BR/DB | Injector #2 |
| 14 | K11 18BR/YL | Injector #1 |
| 15 | K922 18BR/DB | Throttle Pos |
| 16 | - |
| 17 | K199 18BR/VT | O2 2/1 Heater |
| 18 | K99 18BR/LG | O2 1/1 Heater |
| 19 | K20 18BR/GY | Alternator Ctrl |
| 20 | K2 18VT/OR | Elec Throttle Control Sig |
| 21 | K22 18BR/OR | TP #1 Sig |
| 22 | K34 18DB/LG | EGR Sig |
| 23 | K1 18VT/BR | MAP Sig |
| 24 | K942 18BR/LG | Knock Sen #1 Ret |
| 25 | K42 18DB/YL | Knock Sen #1 Sig |
| 26 | - |
| 27 | K900 18DB/DG | Sensor Ground |
| 28 | K122 18BR/DG | TP #2 Sig |
| 29 | F855 18PK/YL | 5V+ |
| 30 | K21 18DB/LG | IAT Sig |
| 31 | K41 18DB/LB | O2 1/1 Sig |
| 32 | K904 18DB/DG | O2 Ret Downstream |
| 33 | K43 18DB/LG | O2 2/1 Sig |
| 34 | K44 20DB/GY | Cam Pos Sig |
| 35 | K24 20BR/LB | Crank Pos Sig |
| 36 | K242 18BR/WT | Knock Sen #2 Sig |
| 37 | K924 18WT/BR | Knock Sen #2 Ret |
| 38 | K448 18TN/OR | Elec Throttle Control - |

## C3
C3 pinout
| Pin | Circuit | Fn |
| --- | ------- | -- |
| 1 | - |
| 2 | - |
| 3 | K51 20BR/WT | ASD Relay Ctrl (-) |
| 4 | - |
| 5 | - |
| 6 | K173 18BR/VT | Condenser Fan Relay Ctrl |
| 7 | - |
| 8 | K106 18VT/LB | Vac Leak Det Sol Ctrl |
| 9 | K299 18BR/WT | O2 1/2 Heater |
| 10 | K399 18BR/GY | O2 2/2 Heater |
| 11 | C13 20LB/OR | A/C Clutch Relay Ctrl |
| 12 | - |
| 13 | - |
| 14 | V32 20VT/YL | Brake Switch #2 Sig |
| 15 | V937 20VT/BR | S/C Switch Ret |
| 16 | K167 20BR/YL | APPS #1 Ret (Pedal) |
| 17 | K400 20BR/VT | APPS #2 Ret (Pedal) |
| 18 | V38 20VT/OR | S/C Switch #2 Sig |
| 19 | K342 16BR/WT | ASD Relay Output |
| 20 | K52 18DB/WT | Evap Purge Sol Ctrl |
| 21 | T41 20YL/DB | TRS (Park/Neutral) - in N |
| 22 | G113 18VT | PTO Switch Sen |
| 23 | B29 20DG/WT | Brake Switch Sig |
| 24 | - |
| 25 | K23 20BR/W | APPS #1 Sig (Pedal) |
| 26 | - |
| 27 | - |
| 28 | K342 16BR/WT | ASD Relay Output |
| 29 | K70 18DB/BR | Evap Purge Sol Sig |
| 30 | K66 18DB/WT | P/S Switch Sig |
| 31 | - |
| 32 | K25 18DB/VT | Batt Temp Sig |
| 33 | N4 20DB/WT | Fuel Level Sen Sig |
| 34 | V37 20VT | S/C Switch #1 Sig |
| 35 | K107 18VT/WT | Vac Leak Switch Sig |
| 36 | K29 20WT/BR | APPS #2 Sig (Pedal) |
| 37 | K31 20BR | Fuel Pump Relay Ctrl |
| 38 | T752 20DG/OR | Starter Relay Ctrl |

## C4
C4 pinout
| Pin | Circuit | Fn |
| --- | ------- | -- |
| 1 | T60 18YL/GY | OD Sol Ctrl |
| 2 | T259 18YL/DG | 4C Sol Ctrl |
| 3 | - | |
| 4 | T140 18DG | MS Sol Ctrl |
| 5 | - | |
| 6 | T219 18YL/LG | 2C Sol Ctrl |
| 7 | - | |
| 8 | T59 18YL/LB | UD Sol Ctrl |
| 9 | - | |
| 10 | T20 18DG/WT | L/R Sol Ctrl |
| 11 | T118 18YL/GY | Pressure Ctrl Sol Ctrl |
| 12 | Z908 18BK | Ground |
| 13 | Z977 18BK | Ground |
| 14 | Z904 18BK | Ground |
| 15 | T1 18DG/LB | TRS T1 Sense |
| 16 | T3 18DG/DB | TRS T3 Sense |
| 17 | T6 18DG | Tow/Haul OD-off Switch Sense |
| 18 | T515 20YL/DB | Trans Ctrl Relay Ctrl |
| 19 | T16 18YL/OR | Trans Ctrl Relay Output |
| 20 | T48 18BR/YL | 4C Press Sw Sense |
| 21 | T29 18YL/WT | UD Press Sw Sense |
| 22 | T9 18DG/TN | OD Press Sw Sense |
| 23 | - | |
| 24 | - | |
| 25 | - | |
| 26 | T4 18DG/LB | TRS T2 Sense |
| 27 | - | |
| 28 | T16 18YL/OR | Trans Ctrl Relay Output |
| 29 | T50 18YL/TN | L/R Press Sw Sense |
| 30 | T147 18DG/YL | 2C Press Sw Sense |
| 31 | T38 18YL/BR | Line Press Sensor Sig |
| 32 | T14 18DG/BR | Output Speed Sensor Sig |
| 33 | T52 18DG/OR | Input Speed Sensor Sig |
| 34 | T13 18DG/VT | Speed Sensor Ground |
| 35 | T54 18DG/OR | Trans Temp Sensor Sig |
| 36 | - | |
| 37 | T42 18DG/YL | TRS T42 Sense |
| 38 | T16 18YL/OR | Trans Ctrl Relay Output |