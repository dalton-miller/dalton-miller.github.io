# C105
C105 engine side pinout
![[Pasted image 20220630132219.png]]
| Pin | Circuit | Fn |
| --- | ------- | -- |
| 1 | - | |
| 2 | T16 16RD | Trans Ctrl Relay Output |
| 3 | Y193 20WT/LG | Trans Range Sensor Mux |
| 4 | Y128 20DG/GY | Trans Range Sensor 5V+ |
| 5 | K6 18VT/WT | 5V+ |
| 6 | K125 18WT/DB | Alternator Source |
| 7 | C18 18DB | A/C Pressure Sig |
| 8 | A142 14DG/OR | ASD Relay Output |
| 9 | C20 18BR | A/C Switch Sense |
| 10 | F84 16YL/WT | Battery + |

# C106
C106 engine side pinout
![[Pasted image 20220630132226.png]]
| Pin | Circuit | Fn | Notes |
| --- | ------- | -- | ------ |
| 1 | F142 16OR/DG | ASD Relay Output |
| 2 | Y112 18YL/BR | T-case Mode Sensor D |
| 3 | Y124 16DG/VT | T-case Shift Motor Ctrl A |
| 4 | Y125 16DG/WT | T-case Shift Motor Ctrl B |
| 5 | Y115 18YL/WT | T-case Mode Sensor C |
| 6 | Y117 18YL/DB | T-case Mode Sensor 5V+ |
| 7 | Y119 18YL/TN | T-case Mode Sensor Gnd |
| 8 | Y114 18YL/VT | T-case Mode Sensor B |
| 9 | L1 18VT/BK | Reverse Light Feed |
| 10 | A142 14DG/OR | ASD Relay Output |
| 11 | A169 18RD/YL | Ignition Switch Start |
| 12 | A14 16RD/WT | Battery + |
| 13 | L10 18BR/LG | Ignition Switch Run |
| 14 | - | |
| 15 | Y113 18YL/OR | T-case Mode Sensor A |
| 16 | K200 18VT/OR | O2 Relay Driver |
| 17 | K100 18VT/WT | O2 1/1 Heater |
| 18 | F18 18LG/BK | Ignition Sw Run/Start |
| 19 | K125 18WT/DB | Alternator Source |
| 20 | D25 18VT/YL | PCI Bus |
| 21 | K4 18BK/LB | Sensor Ground |
| 22 | T41 18BK/WT | TRS (Park/Neutral) - in N | This goes to t-case |
| 23 | C3 18DB/BK | A/C Clutch Relay Output |
| 24 | - | |

# C107
C107 engine side 
![[Pasted image 20220630132248.png]]
| Pin | Circuit | Fn |
| --- | ------- | -- |
| 1 | - | |
| 2 | D22 20PK/BK | SCI Receive (TCM) |
| 3 | D21 18PK | SCI Transmit (TCM) |
| 4 | F11 18RD/WT | Ignition Sw Run/Start |
| 5 | T15 18LG | Transmission Relay Ctrl |
| 6 | F242 18DG/OR | |
| 7 | T6 18OR/WT | Tow/Haul OD-Off Sense |
| 8 | T10 18YL/DG | Torque Mgmt Req Sense |
| 9 | - | |
| 10 | C24 18DB/PK | Rad Fan Relay Ctrl |

# ECU
ECU connectors
C1 = black
C2 = white
C3 = gray

![[Pasted image 20220630132323.png]]

## C1
C1 pinout
| Pin | Circuit | Fn |
| --- | ------- | -- |
| 1 | K93 16TN/OR | Coil #3 |
| 2 | F18 18LG/BK | Ignition Sw Run/Start |
| 3 | K94 16TN/LG | Coil #4 |
| 4 | K4 18BK/LB | Sensor Ground |
| 5 | K96 16TN/LB | Coil #6 |
| 6 | T41 18BK/WT | PRS (Park/Neutral) |
| 7 | K19 16BK/GY | Coil #1 |
| 8 | K24 18GY/BK | Crank Pos Sensor |
| 9 | K98 16LB/RD | Coil #8 |
| 10 | K60 16YL/BK | IAC #2 |
| 11 | K40 16BR/WT | IAC #3 |
| 12 | K10 18DB/OR | P/S Press Switch Sense |
| 13 | - | |
| 14 | - | |
| 15 | K21 18BK/RD | IAT Sig |
| 16 | K2 18TN/BK | Coolant Temp |
| 17 | K7 18OR | 5V+ |
| 18 | K44 16TN/YL | Cam Pos Sensor |
| 19 | K39 16GY/RD | IAC #1 |
| 20 | K59 16TN/DG | IAC #4 |
| 21 | K95 16TN/DG | Coil #5 |
| 22 | A14 16RD/WT | Battery + |
| 23 | K22 18OR/DB | TPS Sig |
| 24 | K41 18BK/DG | O2 1/1 Sig |
| 25 | K141 18TN/WT | O2 1/2 Sig |
| 26 | K241 18LG/RD | O2 2/1 Sig |
| 27 | K1 18DG/RD | MAP Sig |
| 28 | - | |
| 29 | K341 18TN/WT | O2 2/2 Sig |
| 30 | - | |
| 31 | Z12 14BK/TN | Ground |
| 32 | Z12 14BK/TN | Ground |

## C2
C2 pinout
| Pin | Circuit | Fn |
| --- | ------- | -- |
| 1 | - | |
| 2 | K26 18VT | Injector #7 |
| 3 | - | |
| 4 | K11 18WT/DB | Injector #1 |
| 5 | K13 18YL/WT | Injector #3 |
| 6 | K38 18GY | Injector #5 |
| 7 | K17 16DB/TN | Coil #7 |
| 8 | - | |
| 9 | K92 16TN/PK | Coil #2 |
| 10 | K20 18DG | Alternator Ctrl |
| 11 | - | |
| 12 | K58 18BR/DB | Injector #6 |
| 13 | K28 18GY/LB | Injector #8 |
| 14 | - | |
| 15 | K12 18TN | Injector #2 |
| 16 | K14 18LB/BR | Injector #4 |
| 17 | C24 18DB/PK | Rad Fan Relay Ctrl |
| 18 | - | |
| 19 | C18 18DB | A/C Press Sig |
| 20 | - | |
| 21 | - | |
| 22 | - | |
| 23 | G60 18GY/YL | Oil Press Sig |
| 24 | - | |
| 25 | - | |
| 26 | - | |
| 27 | G7 18WT/OR | VSS Sig |
| 28 | - | |
| 29 | - | |
| 30 | - | |
| 31 | K6 18VT/WT | 5V+ |
| 32 | - | |

## C3
C3 pinout
| Pin | Circuit | Fn |
| --- | ------- | -- |
| 1 | C13 18DB/OR | A/C Clutch Relay Ctrl |
| 2 | - | |
| 3 | K51 18DB/YL | ASD Relay Ctrl |
| 4 | V36 18TN/RD | Speed Ctrl Vac Sol Ctrl |
| 5 | V35 18LG/RD | Speed Ctrl Vent Sol Ctrl |
| 6 | - | |
| 7 | - | |
| 8 | K100 18VT/WT | O2 1/1 Heater |
| 9 | K512 18DG/BK | O2 Downstream Heater Relay Ctrl |
| 10 | K106 18WT/DG | Leak Pump Sol Ctrl |
| 11 | V32 18YL/RD | Speed Ctrl Supply |
| 12 | A142 14DG/OR | ASD Relay Output |
| 13 | T10 18YL/DG | Torque Mgmt Req Sense |
| 14 | K107 18OR | Leak Pump Sw Sense |
| 15 | K118 18PK/YL | Batt Temp Sensor Sig |
| 16 | K200 18VT/OR | O2 Relay Driver |
| 17 | - | |
| 18 | - | |
| 19 | K31 18BR | Fuel Pump Relay Ctrl |
| 20 | K52 18PK/BK | Duty Cycle Evap/Purge Sol Ctrl |
| 21 | - | |
| 22 | C20 18BR | A/C Switch Sense |
| 23 | - | |
| 24 | V40 18WT/PK | Brake Switch Sense |
| 25 | K125 18WT/DB | Alternator Source |
| 26 | K226 18DB/WT | Fuel Level Sig |
| 27 | D21 18PK | SCI Transmit |
| 28 | - | |
| 29 | D20 18LG | SCI Receive |
| 30 | D25 18VT/YL | PCI Bus |
| 31 | - | |
| 32 | V37 18RD/LG | Speed Ctrl Sw Sig |

# TCM
TCM pinout
| Pin | Circuit | Fn |
| --- | ------- | -- |
| 1 | T1 18LG/BK | TRS T1 Sense |
| 2| T4 18PK/OR | TRS T2 Sense |
| 3 | T3 18VT | TRS T3 Sense |
| 4 | - | |
| 5 | - | |
| 6 | K24 18GY/BK | Crank Pos Sig |
| 7 | D21 18PK | SCI Transmit |
| 8 | A169 18RD/YL | Ignition Sw Start |
| 9 | T9 18OR/BK | Overdrive Pressure Sw Sense |
| 10 | T10 18YL/DG | Torque Management Sw Sense |
| 11 | F11 18RD/WT | Ignition Sw Run/Start |
| 12 | K22 18OR/DB | TPS Sig |
| 13 | T13 18DB/BK | Speed Sensor Ground |
| 14 | T14 18LG/WT | Output Speed Sensor Sig |
| 15 | T15 18LG | Trans Relay Ctrl |
| 16 | T16 18RD | Trans Relay Ctrl Output |
| 17 | T16 18RD | Trans Relay Ctrl Output |
| 18 | T118 18YL/DB | Pressure Ctrl Sol Ctrl |
| 19 | T119 18WT/DB | 2C Sol Ctrl |
| 20 | T120 18LG | LR/CC Sol Ctrl |
| 21 | - | |
| 22 | - | |
| 23 | - | |
| 24 | - | |
| 25 | - | |
| 26 | - | |
| 27 | - | |
| 28 | G7 18WT/OR | VSS Sig |
| 29 | T29 18GY | Underdrive Pressure Sw Sig |
| 30 | T39 18GY/LB | Line Pressure Sig |
| 31 | - | |
| 32 | - | |
| 33 | - | |
| 34 | - | |
| 35 | - | |
| 36 | T16 18RD | Trans Ctrl Relay Output |
| 37 | Z13 16BK/RD | Ground |
| 38 | T38 18VT/TN | 5V+ |
| 39 | Z134 16BK/RD | Ground |
| 40 | T140 18VT/LG | MS Sol Ctrl |
| 41 | T41 16YL | TRS T41 Sense |
| 42 | T42 18VT/WT | TRS T42 Sense |
| 43 | D25 18VT/YL | PCI Bus |
| 44 | - | |
| 45 | - | |
| 46 | D22 20PK/BK | SCI Receive |
| 47 | T47 18YL/BK | 2C Pressure Sw Sense |
| 48 | T48 18DB | 4C Pressure Sw Sense |
| 49 | T6 18OR/WT | OD-off Sw Sense |
| 50 | T50 18DG | Low/Rev Pressure Sw Sense |
| 51 | K4 18BK/LB | Sensor Ground |
| 52 | T52 18RD/BK | Input Speed Sensor Sig |
| 53 | Z113 16BK | Ground |
| 54 | T54 20VT | Trans Temp Sensor Sig |
| 55 | T59 18PK | Underdrive Sol Ctrl |
| 56 | F84 16YL/WT | Battery + |
| 57 | Z13 16BK/RD | Ground |
| 58 | - | |
| 59 | T159 18DG/WT | 4C Sol Ctrl |
| 60 | T60 18BR | 3-4 Shift Sol Ctrl |

#wiringdiagram #dakota 