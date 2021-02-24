EESchema Schematic File Version 4
EELAYER 30 0
EELAYER END
$Descr A4 11693 8268
encoding utf-8
Sheet 1 1
Title "Project Irene"
Date "2020-10-12"
Rev "v0.1"
Comp "Erictronics"
Comment1 ""
Comment2 ""
Comment3 "Custom Arduino Board with ATmega328p"
Comment4 "Author: mr_mensah"
$EndDescr
Text Notes 4250 850  0    98   ~ 20
PROJECT IRENE ~ CUSTOM ARDUINO UNO  
$Comp
L power:+5V #PWR03
U 1 1 5F7DFCE1
P 850 1650
F 0 "#PWR03" H 850 1500 50  0001 C CNN
F 1 "+5V" H 865 1823 50  0000 C CNN
F 2 "" H 850 1650 50  0001 C CNN
F 3 "" H 850 1650 50  0001 C CNN
	1    850  1650
	1    0    0    -1  
$EndComp
$Comp
L power:GND #PWR06
U 1 1 5F7E078C
P 1100 1650
F 0 "#PWR06" H 1100 1400 50  0001 C CNN
F 1 "GND" H 1105 1477 50  0000 C CNN
F 2 "" H 1100 1650 50  0001 C CNN
F 3 "" H 1100 1650 50  0001 C CNN
	1    1100 1650
	-1   0    0    1   
$EndComp
$Comp
L power:PWR_FLAG #FLG01
U 1 1 5F7E096F
P 600 2100
F 0 "#FLG01" H 600 2175 50  0001 C CNN
F 1 "PWR_FLAG" V 650 1950 50  0000 C CNN
F 2 "" H 600 2100 50  0001 C CNN
F 3 "~" H 600 2100 50  0001 C CNN
	1    600  2100
	-1   0    0    1   
$EndComp
$Comp
L power:PWR_FLAG #FLG02
U 1 1 5F7E0E0C
P 850 2100
F 0 "#FLG02" H 850 2175 50  0001 C CNN
F 1 "PWR_FLAG" V 900 1950 50  0000 C CNN
F 2 "" H 850 2100 50  0001 C CNN
F 3 "~" H 850 2100 50  0001 C CNN
	1    850  2100
	-1   0    0    1   
$EndComp
$Comp
L power:PWR_FLAG #FLG03
U 1 1 5F7E121A
P 1100 2100
F 0 "#FLG03" H 1100 2175 50  0001 C CNN
F 1 "PWR_FLAG" V 1150 1950 50  0000 C CNN
F 2 "" H 1100 2100 50  0001 C CNN
F 3 "~" H 1100 2100 50  0001 C CNN
	1    1100 2100
	-1   0    0    1   
$EndComp
Wire Wire Line
	1100 1650 1100 2100
Wire Wire Line
	850  1650 850  2100
Wire Wire Line
	600  1650 600  2100
Text Notes 600  1300 0    98   ~ 20
POWER
$Comp
L Connector:Barrel_Jack_Switch J3
U 1 1 5F7E3BBD
P 1950 1700
F 0 "J3" H 2007 2017 50  0000 C CNN
F 1 "Barrel_Jack_Switch" H 2007 1926 50  0000 C CNN
F 2 "Connector_BarrelJack:BarrelJack_Horizontal" H 2000 1660 50  0001 C CNN
F 3 "~" H 2000 1660 50  0001 C CNN
	1    1950 1700
	1    0    0    -1  
$EndComp
$Comp
L Regulator_Linear:LM7805_TO220 U3
U 1 1 5F7E40A2
P 3950 1600
F 0 "U3" H 3950 1842 50  0000 C CNN
F 1 "LM7805" H 3950 1751 50  0000 C CNN
F 2 "Package_TO_SOT_SMD:TO-252-2" H 3950 1825 50  0001 C CIN
F 3 "http://www.fairchildsemi.com/ds/LM/LM7805.pdf" H 3950 1550 50  0001 C CNN
	1    3950 1600
	1    0    0    -1  
$EndComp
$Comp
L Device:CP C7
U 1 1 5F7E5202
P 4550 1750
F 0 "C7" H 4668 1796 50  0000 L CNN
F 1 "100uF" H 4668 1705 50  0000 L CNN
F 2 "Capacitor_SMD:CP_Elec_6.3x5.4" H 4588 1600 50  0001 C CNN
F 3 "~" H 4550 1750 50  0001 C CNN
	1    4550 1750
	1    0    0    -1  
$EndComp
$Comp
L Device:R R4
U 1 1 5F7E64D0
P 5000 1600
F 0 "R4" V 4793 1600 50  0000 C CNN
F 1 "10K" V 4884 1600 50  0000 C CNN
F 2 "Resistor_SMD:R_1206_3216Metric_Pad1.42x1.75mm_HandSolder" V 4930 1600 50  0001 C CNN
F 3 "~" H 5000 1600 50  0001 C CNN
	1    5000 1600
	0    1    1    0   
$EndComp
$Comp
L Device:LED D4
U 1 1 5F7E6AB2
P 5450 1750
F 0 "D4" V 5489 1632 50  0000 R CNN
F 1 "RED" V 5398 1632 50  0000 R CNN
F 2 "LED_SMD:LED_1206_3216Metric_Pad1.42x1.75mm_HandSolder" H 5450 1750 50  0001 C CNN
F 3 "~" H 5450 1750 50  0001 C CNN
	1    5450 1750
	0    -1   -1   0   
$EndComp
$Comp
L power:GND #PWR020
U 1 1 5F7E88A8
P 3950 2050
F 0 "#PWR020" H 3950 1800 50  0001 C CNN
F 1 "GND" H 3955 1877 50  0000 C CNN
F 2 "" H 3950 2050 50  0001 C CNN
F 3 "" H 3950 2050 50  0001 C CNN
	1    3950 2050
	1    0    0    -1  
$EndComp
Wire Wire Line
	4850 1600 4550 1600
Wire Wire Line
	4250 1600 4550 1600
Connection ~ 4550 1600
Wire Wire Line
	5150 1600 5450 1600
Wire Wire Line
	2750 1600 3050 1600
Connection ~ 3050 1600
Wire Wire Line
	2450 1600 2250 1600
$Comp
L power:GND #PWR013
U 1 1 5F7E9FAF
P 2350 2050
F 0 "#PWR013" H 2350 1800 50  0001 C CNN
F 1 "GND" H 2355 1877 50  0000 C CNN
F 2 "" H 2350 2050 50  0001 C CNN
F 3 "" H 2350 2050 50  0001 C CNN
	1    2350 2050
	1    0    0    -1  
$EndComp
Wire Wire Line
	2250 1700 2350 1700
Wire Wire Line
	2350 1700 2350 1800
Wire Wire Line
	2250 1800 2350 1800
Connection ~ 2350 1800
Wire Wire Line
	2350 1800 2350 2050
Wire Wire Line
	3950 1900 3950 2000
Connection ~ 3950 2000
Wire Wire Line
	3950 2000 3950 2050
Wire Wire Line
	3050 1900 3050 2000
Wire Wire Line
	4550 1900 4550 2000
Wire Wire Line
	4550 2000 3950 2000
Wire Wire Line
	5450 1900 5450 2000
Wire Wire Line
	5450 2000 4550 2000
Connection ~ 4550 2000
$Comp
L power:+5V #PWR022
U 1 1 5F7EC246
P 4550 1500
F 0 "#PWR022" H 4550 1350 50  0001 C CNN
F 1 "+5V" H 4565 1673 50  0000 C CNN
F 2 "" H 4550 1500 50  0001 C CNN
F 3 "" H 4550 1500 50  0001 C CNN
	1    4550 1500
	1    0    0    -1  
$EndComp
Wire Wire Line
	4550 1500 4550 1600
Wire Wire Line
	3050 1500 3050 1600
Text Notes 1950 5850 0    98   ~ 20
RESET BUTTON
$Comp
L power:+5V #PWR012
U 1 1 5F7F99B6
P 2100 6100
F 0 "#PWR012" H 2100 5950 50  0001 C CNN
F 1 "+5V" H 2115 6273 50  0000 C CNN
F 2 "" H 2100 6100 50  0001 C CNN
F 3 "" H 2100 6100 50  0001 C CNN
	1    2100 6100
	1    0    0    -1  
$EndComp
$Comp
L Switch:SW_Push_Dual SW1
U 1 1 5F7FA20B
P 2800 6800
F 0 "SW1" H 2800 7085 50  0000 C CNN
F 1 "SW_Push_Dual" H 2800 6994 50  0000 C CNN
F 2 "Button_Switch_THT:SW_PUSH_6mm_H5mm" H 2800 7000 50  0001 C CNN
F 3 "~" H 2800 7000 50  0001 C CNN
	1    2800 6800
	1    0    0    -1  
$EndComp
$Comp
L power:GND #PWR016
U 1 1 5F7FB00E
P 3150 7150
F 0 "#PWR016" H 3150 6900 50  0001 C CNN
F 1 "GND" H 3155 6977 50  0000 C CNN
F 2 "" H 3150 7150 50  0001 C CNN
F 3 "" H 3150 7150 50  0001 C CNN
	1    3150 7150
	1    0    0    -1  
$EndComp
Wire Wire Line
	2100 6550 2100 6900
Wire Wire Line
	2100 6900 2600 6900
Wire Wire Line
	2600 6900 2600 6800
Wire Wire Line
	2600 6900 2600 7000
Connection ~ 2600 6900
Wire Wire Line
	3000 6800 3000 6900
Wire Wire Line
	3000 6900 3150 6900
Wire Wire Line
	3150 6900 3150 7150
Connection ~ 3000 6900
Wire Wire Line
	3000 6900 3000 7000
Wire Wire Line
	1850 6900 2100 6900
Connection ~ 2100 6900
$Comp
L power:VCC #PWR01
U 1 1 5F847A38
P 600 1650
F 0 "#PWR01" H 600 1500 50  0001 C CNN
F 1 "VCC" H 615 1823 50  0000 C CNN
F 2 "" H 600 1650 50  0001 C CNN
F 3 "" H 600 1650 50  0001 C CNN
	1    600  1650
	1    0    0    -1  
$EndComp
$Comp
L Device:CP C4
U 1 1 5F7E5474
P 3050 1750
F 0 "C4" H 3168 1796 50  0000 L CNN
F 1 "480uF" H 2800 1650 50  0000 L CNN
F 2 "Capacitor_SMD:CP_Elec_6.3x5.4" H 3088 1600 50  0001 C CNN
F 3 "~" H 3050 1750 50  0001 C CNN
	1    3050 1750
	1    0    0    -1  
$EndComp
Text Notes 2350 1250 0    98   ~ 20
LM7805 VOLTAGE REGULATOR
Wire Notes Line width 51 style dash_dot
	500  1000 11200 1000
$Comp
L Device:Polyfuse F1
U 1 1 5F85CE36
P 2600 1600
F 0 "F1" V 2375 1600 50  0000 C CNN
F 1 "1A" V 2466 1600 50  0000 C CNN
F 2 "Fuse:Fuse_1206_3216Metric_Pad1.42x1.75mm_HandSolder" H 2650 1400 50  0001 L CNN
F 3 "~" H 2600 1600 50  0001 C CNN
	1    2600 1600
	0    1    1    0   
$EndComp
$Comp
L power:VCC #PWR015
U 1 1 5F85D374
P 3050 1500
F 0 "#PWR015" H 3050 1350 50  0001 C CNN
F 1 "VCC" H 3065 1673 50  0000 C CNN
F 2 "" H 3050 1500 50  0001 C CNN
F 3 "" H 3050 1500 50  0001 C CNN
	1    3050 1500
	1    0    0    -1  
$EndComp
$Comp
L Interface_USB:FT232RL U1
U 1 1 5F86B26A
P 3200 3900
F 0 "U1" V 3150 3900 50  0000 C CNN
F 1 "FT232RL" V 3250 3900 50  0000 C CNN
F 2 "Package_SO:SSOP-28_5.3x10.2mm_P0.65mm" H 4300 3000 50  0001 C CNN
F 3 "https://www.ftdichip.com/Support/Documents/DataSheets/ICs/DS_FT232R.pdf" H 3200 3900 50  0001 C CNN
	1    3200 3900
	1    0    0    -1  
$EndComp
$Comp
L power:+5V #PWR017
U 1 1 5F86C039
P 3300 2800
F 0 "#PWR017" H 3300 2650 50  0001 C CNN
F 1 "+5V" H 3315 2973 50  0000 C CNN
F 2 "" H 3300 2800 50  0001 C CNN
F 3 "" H 3300 2800 50  0001 C CNN
	1    3300 2800
	1    0    0    -1  
$EndComp
Wire Wire Line
	3300 2800 3300 2850
Wire Wire Line
	3100 2900 3100 2850
Wire Wire Line
	3100 2850 3300 2850
Connection ~ 3300 2850
Wire Wire Line
	3300 2850 3300 2900
$Comp
L power:GND #PWR014
U 1 1 5F86DA9A
P 3000 5300
F 0 "#PWR014" H 3000 5050 50  0001 C CNN
F 1 "GND" H 3005 5127 50  0000 C CNN
F 2 "" H 3000 5300 50  0001 C CNN
F 3 "" H 3000 5300 50  0001 C CNN
	1    3000 5300
	1    0    0    -1  
$EndComp
Wire Wire Line
	3000 4900 3000 5150
Wire Wire Line
	3000 5150 3200 5150
Wire Wire Line
	3400 5150 3400 4900
Wire Wire Line
	2400 4600 2400 5150
Wire Wire Line
	2400 5150 3000 5150
Connection ~ 3000 5150
Wire Wire Line
	3000 5150 3000 5300
Wire Wire Line
	3200 4900 3200 5150
Connection ~ 3200 5150
Wire Wire Line
	3200 5150 3300 5150
Wire Wire Line
	3300 4900 3300 5150
Connection ~ 3300 5150
Wire Wire Line
	3300 5150 3400 5150
$Comp
L Connector:USB_B_Mini J1
U 1 1 5F872AC0
P 800 4000
F 0 "J1" H 857 4467 50  0000 C CNN
F 1 "USB_B_Mini" H 857 4376 50  0000 C CNN
F 2 "Connector_USB:USB_Mini-B_Lumberg_2486_01_Horizontal" H 950 3950 50  0001 C CNN
F 3 "~" H 950 3950 50  0001 C CNN
	1    800  4000
	1    0    0    -1  
$EndComp
$Comp
L power:+5V #PWR07
U 1 1 5F87344C
P 1150 3250
F 0 "#PWR07" H 1150 3100 50  0001 C CNN
F 1 "+5V" H 1165 3423 50  0000 C CNN
F 2 "" H 1150 3250 50  0001 C CNN
F 3 "" H 1150 3250 50  0001 C CNN
	1    1150 3250
	1    0    0    -1  
$EndComp
$Comp
L Device:D_Schottky D1
U 1 1 5F873926
P 1150 3500
F 0 "D1" V 1050 3400 50  0000 L CNN
F 1 "D_Schottky" V 950 3050 50  0000 L CNN
F 2 "Diode_SMD:D_1206_3216Metric_Pad1.42x1.75mm_HandSolder" H 1150 3500 50  0001 C CNN
F 3 "~" H 1150 3500 50  0001 C CNN
	1    1150 3500
	0    1    1    0   
$EndComp
Wire Wire Line
	1150 3650 1150 3800
Wire Wire Line
	1150 3800 1100 3800
$Comp
L power:GND #PWR02
U 1 1 5F877E42
P 750 4550
F 0 "#PWR02" H 750 4300 50  0001 C CNN
F 1 "GND" H 755 4377 50  0000 C CNN
F 2 "" H 750 4550 50  0001 C CNN
F 3 "" H 750 4550 50  0001 C CNN
	1    750  4550
	1    0    0    -1  
$EndComp
Wire Wire Line
	700  4400 700  4500
Wire Wire Line
	700  4500 750  4500
Wire Wire Line
	800  4500 800  4400
Wire Wire Line
	750  4550 750  4500
Connection ~ 750  4500
Wire Wire Line
	750  4500 800  4500
$Comp
L power:GND #PWR011
U 1 1 5F87F3EB
P 2000 3200
F 0 "#PWR011" H 2000 2950 50  0001 C CNN
F 1 "GND" H 2005 3027 50  0000 C CNN
F 2 "" H 2000 3200 50  0001 C CNN
F 3 "" H 2000 3200 50  0001 C CNN
	1    2000 3200
	1    0    0    -1  
$EndComp
NoConn ~ 2400 3900
NoConn ~ 2400 4100
NoConn ~ 2400 4300
NoConn ~ 4000 3500
NoConn ~ 4000 3400
NoConn ~ 4000 3700
NoConn ~ 4000 3800
NoConn ~ 4000 3900
$Comp
L power:GND #PWR09
U 1 1 5F892B34
P 1400 3700
F 0 "#PWR09" H 1400 3450 50  0001 C CNN
F 1 "GND" H 1405 3527 50  0000 C CNN
F 2 "" H 1400 3700 50  0001 C CNN
F 3 "" H 1400 3700 50  0001 C CNN
	1    1400 3700
	1    0    0    -1  
$EndComp
$Comp
L power:GND #PWR010
U 1 1 5F8AC40D
P 1700 3700
F 0 "#PWR010" H 1700 3450 50  0001 C CNN
F 1 "GND" H 1705 3527 50  0000 C CNN
F 2 "" H 1700 3700 50  0001 C CNN
F 3 "" H 1700 3700 50  0001 C CNN
	1    1700 3700
	1    0    0    -1  
$EndComp
$Comp
L Device:LED D2
U 1 1 5F8B05C2
P 4700 4050
F 0 "D2" V 4800 4100 50  0000 R CNN
F 1 "TX LED" H 4850 4150 50  0000 R CNN
F 2 "LED_SMD:LED_1206_3216Metric_Pad1.42x1.75mm_HandSolder" H 4700 4050 50  0001 C CNN
F 3 "~" H 4700 4050 50  0001 C CNN
	1    4700 4050
	0    -1   -1   0   
$EndComp
$Comp
L Device:LED D3
U 1 1 5F8B3296
P 4950 4050
F 0 "D3" V 5050 4100 50  0000 R CNN
F 1 "RX LED" H 5100 4150 50  0000 R CNN
F 2 "LED_SMD:LED_1206_3216Metric_Pad1.42x1.75mm_HandSolder" H 4950 4050 50  0001 C CNN
F 3 "~" H 4950 4050 50  0001 C CNN
	1    4950 4050
	0    -1   -1   0   
$EndComp
Wire Wire Line
	4950 4300 4950 4200
Wire Wire Line
	4700 3850 4700 3900
Wire Wire Line
	4000 3600 4150 3600
Wire Wire Line
	4000 4300 4950 4300
Wire Wire Line
	4250 3400 4150 3400
Wire Wire Line
	4150 3400 4150 3600
Wire Wire Line
	4450 3400 4650 3400
Wire Wire Line
	4000 3300 4650 3300
Wire Wire Line
	4000 3200 4650 3200
Text Label 4650 3200 2    31   ~ 0
TX
Text Label 4650 3300 2    31   ~ 0
RX
Text Label 4650 3400 2    31   ~ 0
RST
NoConn ~ 4000 4400
NoConn ~ 4000 4500
NoConn ~ 4000 4600
Wire Wire Line
	1150 3250 1150 3300
Connection ~ 1150 3300
Wire Wire Line
	1150 3300 1150 3350
Wire Wire Line
	2400 3500 2000 3500
Wire Wire Line
	2000 3500 2000 4000
Wire Wire Line
	2000 4000 1100 4000
Wire Wire Line
	2400 3600 2100 3600
Wire Wire Line
	2100 3600 2100 4100
Wire Wire Line
	2100 4100 1100 4100
NoConn ~ 1100 4200
Text Notes 1550 2600 0    98   ~ 20
FTDI FT232RL PROGRAMMING INTERFACE
$Comp
L Device:C_Small C5
U 1 1 5F944FA6
P 4350 3400
F 0 "C5" V 4300 3450 50  0000 L CNN
F 1 "100nF" V 4450 3300 50  0000 L CNN
F 2 "Capacitor_SMD:C_1206_3216Metric_Pad1.42x1.75mm_HandSolder" H 4350 3400 50  0001 C CNN
F 3 "~" H 4350 3400 50  0001 C CNN
	1    4350 3400
	0    1    1    0   
$EndComp
Wire Wire Line
	1150 3300 1400 3300
$Comp
L Device:C_Small C1
U 1 1 5F94582C
P 1400 3450
F 0 "C1" H 1400 3550 50  0000 L CNN
F 1 "100nF" V 1300 3300 50  0000 L CNN
F 2 "Capacitor_SMD:C_1206_3216Metric_Pad1.42x1.75mm_HandSolder" H 1400 3450 50  0001 C CNN
F 3 "~" H 1400 3450 50  0001 C CNN
	1    1400 3450
	1    0    0    -1  
$EndComp
Wire Wire Line
	1400 3350 1400 3300
Wire Notes Line width 20 style dash_dot
	5750 1050 5750 5550
Connection ~ 1400 3300
Wire Wire Line
	1400 3300 1700 3300
Wire Wire Line
	1400 3550 1400 3700
$Comp
L Device:C_Small C2
U 1 1 5F94AC85
P 1700 3450
F 0 "C2" H 1700 3550 50  0000 L CNN
F 1 "4.7uF" V 1600 3350 50  0000 L CNN
F 2 "Capacitor_Tantalum_SMD:CP_EIA-3216-10_Kemet-I_Pad1.58x1.35mm_HandSolder" H 1700 3450 50  0001 C CNN
F 3 "~" H 1700 3450 50  0001 C CNN
	1    1700 3450
	1    0    0    -1  
$EndComp
Wire Wire Line
	1700 3350 1700 3300
Wire Wire Line
	1700 3550 1700 3700
$Comp
L Device:C_Small C3
U 1 1 5F94FE9D
P 2200 3200
F 0 "C3" V 2300 3150 50  0000 L CNN
F 1 "100nF" V 2100 3050 50  0000 L CNN
F 2 "Capacitor_SMD:C_1206_3216Metric_Pad1.42x1.75mm_HandSolder" H 2200 3200 50  0001 C CNN
F 3 "~" H 2200 3200 50  0001 C CNN
	1    2200 3200
	0    -1   -1   0   
$EndComp
Wire Wire Line
	2000 3200 2100 3200
Wire Wire Line
	2300 3200 2400 3200
$Comp
L Device:R_Small R2
U 1 1 5F95CE46
P 4700 3750
F 0 "R2" H 4600 3850 50  0000 L CNN
F 1 "1K" H 4550 3750 50  0000 L CNN
F 2 "Resistor_SMD:R_1206_3216Metric_Pad1.42x1.75mm_HandSolder" H 4700 3750 50  0001 C CNN
F 3 "~" H 4700 3750 50  0001 C CNN
	1    4700 3750
	1    0    0    -1  
$EndComp
$Comp
L Device:R_Small R3
U 1 1 5F95DD1B
P 4950 3750
F 0 "R3" H 4850 3850 50  0000 L CNN
F 1 "1K" H 4800 3750 50  0000 L CNN
F 2 "Resistor_SMD:R_1206_3216Metric_Pad1.42x1.75mm_HandSolder" H 4950 3750 50  0001 C CNN
F 3 "~" H 4950 3750 50  0001 C CNN
	1    4950 3750
	1    0    0    -1  
$EndComp
Wire Wire Line
	4950 3850 4950 3900
Wire Wire Line
	4000 4200 4700 4200
Wire Wire Line
	4700 3600 4700 3650
Wire Wire Line
	4950 3550 4950 3600
$Comp
L power:+5V #PWR023
U 1 1 5F8B59F6
P 4950 3550
F 0 "#PWR023" H 4950 3400 50  0001 C CNN
F 1 "+5V" H 4965 3723 50  0000 C CNN
F 2 "" H 4950 3550 50  0001 C CNN
F 3 "" H 4950 3550 50  0001 C CNN
	1    4950 3550
	1    0    0    -1  
$EndComp
Wire Wire Line
	4950 3600 4700 3600
Connection ~ 4950 3600
Wire Wire Line
	4950 3600 4950 3650
$Comp
L mylibrary:ATmega328_DIP U4
U 1 1 5F85E18F
P 8300 2500
F 0 "U4" H 7600 3150 50  0000 C CNN
F 1 "ATmega328_DIP" H 7600 3050 50  0000 C CNN
F 2 "Package_DIP:DIP-28_W7.62mm_LongPads" H 8250 2300 50  0001 C CNN
F 3 "https://www.google.com.gh/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&cad=rja&uact=8&ved=2ahUKEwjv3_P5kqbsAhVSJhoKHcKJBVcQFjAAegQIAxAC&url=https%3A%2F%2Fww1.microchip.com%2Fdownloads%2Fen%2FDeviceDoc%2FAtmel-7810-Automotive-Microcontrollers-ATmega328P_Datasheet.pdf&usg=AOvVaw1saIayRRDKrz7YCcviikuY" H 7550 3200 50  0001 C CNN
	1    8300 2500
	1    0    0    -1  
$EndComp
$Comp
L power:+5V #PWR025
U 1 1 5F86B4F0
P 8300 1750
F 0 "#PWR025" H 8300 1600 50  0001 C CNN
F 1 "+5V" H 8315 1923 50  0000 C CNN
F 2 "" H 8300 1750 50  0001 C CNN
F 3 "" H 8300 1750 50  0001 C CNN
	1    8300 1750
	1    0    0    -1  
$EndComp
$Comp
L power:GND #PWR026
U 1 1 5F86C5AD
P 8300 4600
F 0 "#PWR026" H 8300 4350 50  0001 C CNN
F 1 "GND" H 8305 4427 50  0000 C CNN
F 2 "" H 8300 4600 50  0001 C CNN
F 3 "" H 8300 4600 50  0001 C CNN
	1    8300 4600
	1    0    0    -1  
$EndComp
Wire Wire Line
	8150 4400 8150 4500
Wire Wire Line
	8150 4500 8300 4500
Wire Wire Line
	8450 4500 8450 4400
Wire Wire Line
	8300 4600 8300 4500
Connection ~ 8300 4500
Wire Wire Line
	8300 4500 8450 4500
Wire Wire Line
	8150 1950 8150 1850
Wire Wire Line
	8150 1850 8300 1850
Wire Wire Line
	8450 1850 8450 1950
Wire Wire Line
	8300 1750 8300 1850
Connection ~ 8300 1850
Wire Wire Line
	8300 1850 8450 1850
Text Label 6950 2300 0    31   ~ 0
RST
Wire Wire Line
	7200 2300 6950 2300
Text Label 9650 4050 2    31   ~ 0
TX
Text Label 9650 3950 2    31   ~ 0
RX
$Comp
L Device:C_Small C10
U 1 1 5F88B081
P 9600 2300
F 0 "C10" V 9700 2250 50  0000 L CNN
F 1 "100nF" V 9500 2150 50  0000 L CNN
F 2 "Capacitor_SMD:C_1206_3216Metric_Pad1.42x1.75mm_HandSolder" H 9600 2300 50  0001 C CNN
F 3 "~" H 9600 2300 50  0001 C CNN
	1    9600 2300
	0    -1   -1   0   
$EndComp
$Comp
L power:GND #PWR028
U 1 1 5F88B74C
P 9800 2350
F 0 "#PWR028" H 9800 2100 50  0001 C CNN
F 1 "GND" H 9900 2250 50  0000 C CNN
F 2 "" H 9800 2350 50  0001 C CNN
F 3 "" H 9800 2350 50  0001 C CNN
	1    9800 2350
	1    0    0    -1  
$EndComp
Wire Wire Line
	9800 2300 9700 2300
Wire Wire Line
	9500 2300 9450 2300
$Comp
L Device:Crystal_Small Y1
U 1 1 5F89353D
P 7000 4000
F 0 "Y1" V 7200 4000 50  0000 L CNN
F 1 "16MHz" V 7300 3900 50  0000 L CNN
F 2 "Crystal:Crystal_HC49-4H_Vertical" H 7000 4000 50  0001 C CNN
F 3 "~" H 7000 4000 50  0001 C CNN
	1    7000 4000
	0    1    1    0   
$EndComp
$Comp
L Device:C_Small C9
U 1 1 5F8941A2
P 6750 4100
F 0 "C9" V 6850 4100 50  0000 C CNN
F 1 "22pF" V 6950 4100 50  0000 C CNN
F 2 "Capacitor_SMD:C_1206_3216Metric_Pad1.42x1.75mm_HandSolder" H 6750 4100 50  0001 C CNN
F 3 "~" H 6750 4100 50  0001 C CNN
	1    6750 4100
	0    1    1    0   
$EndComp
$Comp
L Device:C_Small C8
U 1 1 5F895839
P 6750 3900
F 0 "C8" V 6521 3900 50  0000 C CNN
F 1 "22pF" V 6612 3900 50  0000 C CNN
F 2 "Capacitor_SMD:C_1206_3216Metric_Pad1.42x1.75mm_HandSolder" H 6750 3900 50  0001 C CNN
F 3 "~" H 6750 3900 50  0001 C CNN
	1    6750 3900
	0    1    1    0   
$EndComp
$Comp
L power:GND #PWR024
U 1 1 5F89652F
P 6350 4100
F 0 "#PWR024" H 6350 3850 50  0001 C CNN
F 1 "GND" H 6355 3927 50  0000 C CNN
F 2 "" H 6350 4100 50  0001 C CNN
F 3 "" H 6350 4100 50  0001 C CNN
	1    6350 4100
	1    0    0    -1  
$EndComp
Wire Wire Line
	6850 3900 7000 3900
Wire Wire Line
	7000 3900 7200 3900
Wire Wire Line
	7200 3900 7200 3950
Connection ~ 7000 3900
Wire Wire Line
	7200 4050 7200 4100
Wire Wire Line
	7200 4100 7000 4100
Wire Wire Line
	7000 4100 6850 4100
Connection ~ 7000 4100
Wire Wire Line
	6650 3900 6650 4000
Wire Wire Line
	6350 4100 6350 4000
Wire Wire Line
	6350 4000 6650 4000
Connection ~ 6650 4000
Wire Wire Line
	6650 4000 6650 4100
$Comp
L Connector:Conn_01x06_Female J4
U 1 1 5F8B39A3
P 6550 3100
F 0 "J4" V 6700 3100 50  0000 C CNN
F 1 "ANALOG PORTS" V 6600 3050 50  0000 C CNN
F 2 "Connector_PinSocket_2.54mm:PinSocket_1x06_P2.54mm_Vertical" H 6550 3100 50  0001 C CNN
F 3 "~" H 6550 3100 50  0001 C CNN
	1    6550 3100
	-1   0    0    -1  
$EndComp
$Comp
L Connector:Conn_01x08_Female J5
U 1 1 5F8B46D9
P 10200 3650
F 0 "J5" H 10200 3400 50  0000 L CNN
F 1 "D0 - D7" V 10250 3500 50  0000 L CNN
F 2 "Connector_PinSocket_2.54mm:PinSocket_1x08_P2.54mm_Vertical" H 10200 3650 50  0001 C CNN
F 3 "~" H 10200 3650 50  0001 C CNN
	1    10200 3650
	1    0    0    1   
$EndComp
Wire Wire Line
	2100 6100 2100 6250
Text Label 1850 6900 0    50   ~ 0
RST
Text Notes 700  5850 0    98   ~ 20
ICSP HEADER
Wire Notes Line width 20 style dash_dot
	1750 5550 1750 7800
Wire Notes Line
	1750 7800 1700 7800
Wire Notes Line width 20 style dash_dot
	3300 5550 3300 7800
Wire Wire Line
	6750 2900 7200 2900
Wire Wire Line
	7200 3000 6750 3000
Wire Wire Line
	6750 3100 7200 3100
Wire Wire Line
	6750 3200 7200 3200
Wire Wire Line
	6750 3300 7200 3300
Wire Wire Line
	6750 3400 7200 3400
Text Label 6900 3000 0    50   ~ 0
A1
Text Label 6900 2900 0    50   ~ 0
A0
Text Label 6900 3100 0    50   ~ 0
A2
Text Label 6900 3200 0    50   ~ 0
A3
Text Label 6900 3300 0    50   ~ 0
A4
Text Label 6900 3400 0    50   ~ 0
A5
Wire Wire Line
	9400 3250 10000 3250
Wire Wire Line
	9400 3350 10000 3350
Wire Wire Line
	9400 3450 10000 3450
Wire Wire Line
	9400 3550 10000 3550
Wire Wire Line
	9400 3650 10000 3650
Wire Wire Line
	9400 3750 10000 3750
Wire Wire Line
	10000 3850 9800 3850
Wire Wire Line
	9800 3850 9800 3950
Wire Wire Line
	9400 3950 9800 3950
Wire Wire Line
	10000 3950 9900 3950
Wire Wire Line
	9900 3950 9900 4050
Wire Wire Line
	9400 4050 9900 4050
Text Label 9600 3750 0    50   ~ 0
D2
Text Label 9600 3650 0    50   ~ 0
D3
Text Label 9600 3550 0    50   ~ 0
D4
Text Label 9600 3450 0    50   ~ 0
D5
Text Label 9600 3350 0    50   ~ 0
D6
Text Label 9600 3250 0    50   ~ 0
D7
Wire Wire Line
	9800 2350 9800 2300
Wire Wire Line
	9450 2300 9450 2150
Connection ~ 9450 2300
Wire Wire Line
	9450 2300 9400 2300
Text Label 9450 2150 0    50   ~ 0
AREF
Wire Wire Line
	9400 3050 10400 3050
Wire Wire Line
	9400 2950 10400 2950
Wire Wire Line
	9400 2850 10400 2850
Wire Wire Line
	9400 2750 10400 2750
Wire Wire Line
	9400 2650 10400 2650
Wire Wire Line
	9400 2550 10400 2550
$Comp
L power:GND #PWR029
U 1 1 5F97650F
P 10300 2450
F 0 "#PWR029" H 10300 2200 50  0001 C CNN
F 1 "GND" H 10300 2300 50  0000 C CNN
F 2 "" H 10300 2450 50  0001 C CNN
F 3 "" H 10300 2450 50  0001 C CNN
	1    10300 2450
	0    1    1    0   
$EndComp
Wire Wire Line
	10300 2450 10400 2450
Text Label 10200 2350 0    50   ~ 0
AREF
Wire Wire Line
	10400 2350 10200 2350
Text Label 6900 3400 0    50   ~ 0
A5
Wire Wire Line
	10400 2250 10200 2250
Text Label 10200 2250 0    50   ~ 0
A4
Wire Wire Line
	10400 2150 10200 2150
Text Label 10200 2150 0    50   ~ 0
A5
$Comp
L power:VCC #PWR034
U 1 1 5F99BBC1
P 10400 5050
F 0 "#PWR034" H 10400 4900 50  0001 C CNN
F 1 "VCC" V 10415 5223 50  0000 C CNN
F 2 "" H 10400 5050 50  0001 C CNN
F 3 "" H 10400 5050 50  0001 C CNN
	1    10400 5050
	0    -1   -1   0   
$EndComp
$Comp
L power:GND #PWR033
U 1 1 5F99C989
P 10400 4900
F 0 "#PWR033" H 10400 4650 50  0001 C CNN
F 1 "GND" V 10405 4772 50  0000 R CNN
F 2 "" H 10400 4900 50  0001 C CNN
F 3 "" H 10400 4900 50  0001 C CNN
	1    10400 4900
	0    1    1    0   
$EndComp
Wire Wire Line
	10550 4850 10500 4850
Wire Wire Line
	10500 4850 10500 4900
Wire Wire Line
	10500 4950 10550 4950
Wire Wire Line
	10500 4900 10400 4900
Connection ~ 10500 4900
Wire Wire Line
	10500 4900 10500 4950
Wire Wire Line
	10550 5050 10400 5050
$Comp
L power:+5V #PWR032
U 1 1 5F9AF1DA
P 10400 4750
F 0 "#PWR032" H 10400 4600 50  0001 C CNN
F 1 "+5V" V 10415 4878 50  0000 L CNN
F 2 "" H 10400 4750 50  0001 C CNN
F 3 "" H 10400 4750 50  0001 C CNN
	1    10400 4750
	0    -1   -1   0   
$EndComp
Wire Wire Line
	10400 4750 10550 4750
$Comp
L Regulator_Linear:AMS1117-3.3 U2
U 1 1 5F9B6153
P 3900 6350
F 0 "U2" H 3900 6592 50  0000 C CNN
F 1 "AMS1117-3.3" H 3900 6501 50  0000 C CNN
F 2 "Package_TO_SOT_SMD:SOT-223-3_TabPin2" H 3900 6550 50  0001 C CNN
F 3 "http://www.advanced-monolithic.com/pdf/ds1117.pdf" H 4000 6100 50  0001 C CNN
	1    3900 6350
	1    0    0    -1  
$EndComp
Wire Notes Line width 20 style dash_dot
	5750 2300 450  2300
Wire Notes Line width 20 style dash_dot
	1550 1050 1550 2300
$Comp
L power:+3.3V #PWR08
U 1 1 5F9D7F30
P 1350 1650
F 0 "#PWR08" H 1350 1500 50  0001 C CNN
F 1 "+3.3V" H 1365 1823 50  0000 C CNN
F 2 "" H 1350 1650 50  0001 C CNN
F 3 "" H 1350 1650 50  0001 C CNN
	1    1350 1650
	1    0    0    -1  
$EndComp
$Comp
L power:PWR_FLAG #FLG04
U 1 1 5F9D862B
P 1350 2100
F 0 "#FLG04" H 1350 2175 50  0001 C CNN
F 1 "PWR_FLAG" V 1400 1950 50  0000 C CNN
F 2 "" H 1350 2100 50  0001 C CNN
F 3 "~" H 1350 2100 50  0001 C CNN
	1    1350 2100
	-1   0    0    1   
$EndComp
Wire Wire Line
	1350 1650 1350 2100
$Comp
L power:+3.3V #PWR021
U 1 1 5F9DEA09
P 4350 6300
F 0 "#PWR021" H 4350 6150 50  0001 C CNN
F 1 "+3.3V" H 4365 6473 50  0000 C CNN
F 2 "" H 4350 6300 50  0001 C CNN
F 3 "" H 4350 6300 50  0001 C CNN
	1    4350 6300
	1    0    0    -1  
$EndComp
$Comp
L power:+5V #PWR018
U 1 1 5F9DF951
P 3450 6300
F 0 "#PWR018" H 3450 6150 50  0001 C CNN
F 1 "+5V" H 3465 6473 50  0000 C CNN
F 2 "" H 3450 6300 50  0001 C CNN
F 3 "" H 3450 6300 50  0001 C CNN
	1    3450 6300
	1    0    0    -1  
$EndComp
Wire Wire Line
	3450 6300 3450 6350
Wire Wire Line
	3450 6350 3600 6350
Wire Wire Line
	4200 6350 4350 6350
Wire Wire Line
	4350 6350 4350 6300
$Comp
L Device:CP_Small C6
U 1 1 5F9EE50D
P 4350 6500
F 0 "C6" H 4438 6546 50  0000 L CNN
F 1 "100uF" H 4438 6455 50  0000 L CNN
F 2 "Capacitor_SMD:CP_Elec_6.3x5.4" H 4350 6500 50  0001 C CNN
F 3 "~" H 4350 6500 50  0001 C CNN
	1    4350 6500
	1    0    0    -1  
$EndComp
Wire Wire Line
	4350 6400 4350 6350
Connection ~ 4350 6350
$Comp
L power:GND #PWR019
U 1 1 5F9F588F
P 3900 6750
F 0 "#PWR019" H 3900 6500 50  0001 C CNN
F 1 "GND" H 3905 6577 50  0000 C CNN
F 2 "" H 3900 6750 50  0001 C CNN
F 3 "" H 3900 6750 50  0001 C CNN
	1    3900 6750
	1    0    0    -1  
$EndComp
Wire Wire Line
	3900 6650 3900 6700
Wire Wire Line
	3900 6700 4350 6700
Wire Wire Line
	4350 6700 4350 6600
Connection ~ 3900 6700
Wire Wire Line
	3900 6700 3900 6750
Wire Notes Line
	5750 5550 5750 5500
Text Notes 3400 5950 0    98   ~ 20
  ASM1117 - 3.3V \nVOLTAGE REGULATOR 
Wire Notes Line width 20 style dash_dot
	5000 5550 5000 7800
Text Notes 7400 1300 0    98   ~ 20
ATMEGA328P MCU INTERFACE
$Comp
L power:+3.3V #PWR031
U 1 1 5FA2F5C3
P 10400 4650
F 0 "#PWR031" H 10400 4500 50  0001 C CNN
F 1 "+3.3V" V 10415 4778 50  0000 L CNN
F 2 "" H 10400 4650 50  0001 C CNN
F 3 "" H 10400 4650 50  0001 C CNN
	1    10400 4650
	0    -1   -1   0   
$EndComp
Wire Wire Line
	10400 4650 10550 4650
Wire Wire Line
	10550 4550 10400 4550
Text Label 10400 4550 0    51   ~ 0
RST
$Comp
L power:+5V #PWR030
U 1 1 5FA45E81
P 10400 4450
F 0 "#PWR030" H 10400 4300 50  0001 C CNN
F 1 "+5V" V 10415 4578 50  0000 L CNN
F 2 "" H 10400 4450 50  0001 C CNN
F 3 "" H 10400 4450 50  0001 C CNN
	1    10400 4450
	0    -1   -1   0   
$EndComp
Wire Wire Line
	10400 4450 10550 4450
$Comp
L Connector:Conn_01x08_Female J7
U 1 1 5F98E95F
P 10750 4750
F 0 "J7" H 10750 4500 50  0000 L CNN
F 1 "POWER PORT" V 10800 4600 50  0000 L CNN
F 2 "Connector_PinSocket_2.54mm:PinSocket_1x08_P2.54mm_Vertical" H 10750 4750 50  0001 C CNN
F 3 "~" H 10750 4750 50  0001 C CNN
	1    10750 4750
	1    0    0    1   
$EndComp
NoConn ~ 10550 4350
Text Label 9600 3050 0    50   ~ 0
D8
Text Label 9600 2950 0    50   ~ 0
D9
Text Label 9600 2850 0    50   ~ 0
D10
Text Label 9600 2750 0    50   ~ 0
D11
Text Label 9600 2650 0    50   ~ 0
D12
Text Label 9600 2550 0    50   ~ 0
D13
Wire Notes Line width 20 style dash_dot
	450  5550 11200 5550
$Comp
L Connector:AVR-ISP-6 J2
U 1 1 5F86A49E
P 950 6750
F 0 "J2" V 500 6850 50  0000 R CNN
F 1 "AVR-ISP-6" V 600 7000 50  0000 R CNN
F 2 "Connector_PinHeader_2.54mm:PinHeader_2x03_P2.54mm_Vertical" V 700 6800 50  0001 C CNN
F 3 " ~" H -325 6200 50  0001 C CNN
	1    950  6750
	1    0    0    -1  
$EndComp
$Comp
L power:+5V #PWR04
U 1 1 5F86B4EE
P 850 6150
F 0 "#PWR04" H 850 6000 50  0001 C CNN
F 1 "+5V" H 865 6323 50  0000 C CNN
F 2 "" H 850 6150 50  0001 C CNN
F 3 "" H 850 6150 50  0001 C CNN
	1    850  6150
	1    0    0    -1  
$EndComp
$Comp
L power:GND #PWR05
U 1 1 5F86BB98
P 850 7250
F 0 "#PWR05" H 850 7000 50  0001 C CNN
F 1 "GND" H 855 7077 50  0000 C CNN
F 2 "" H 850 7250 50  0001 C CNN
F 3 "" H 850 7250 50  0001 C CNN
	1    850  7250
	1    0    0    -1  
$EndComp
Wire Wire Line
	850  6250 850  6150
Wire Wire Line
	850  7150 850  7250
Wire Wire Line
	1350 6550 1550 6550
Wire Wire Line
	1350 6650 1550 6650
Wire Wire Line
	1350 6750 1550 6750
Wire Wire Line
	1350 6850 1550 6850
Text Label 1550 6850 2    50   ~ 0
RST
Text Label 1550 6750 2    50   ~ 0
D13
Text Label 1550 6550 2    50   ~ 0
D12
Text Label 1550 6650 2    50   ~ 0
D11
$Comp
L Mechanical:MountingHole H1
U 1 1 5F918001
P 5450 6350
F 0 "H1" H 5550 6396 50  0000 L CNN
F 1 "H1" H 5550 6305 50  0000 L CNN
F 2 "MountingHole:MountingHole_3.2mm_M3" H 5450 6350 50  0001 C CNN
F 3 "~" H 5450 6350 50  0001 C CNN
	1    5450 6350
	1    0    0    -1  
$EndComp
$Comp
L Mechanical:MountingHole H2
U 1 1 5F9205D6
P 5450 6600
F 0 "H2" H 5550 6646 50  0000 L CNN
F 1 "H2" H 5550 6555 50  0000 L CNN
F 2 "MountingHole:MountingHole_3.2mm_M3" H 5450 6600 50  0001 C CNN
F 3 "~" H 5450 6600 50  0001 C CNN
	1    5450 6600
	1    0    0    -1  
$EndComp
$Comp
L Mechanical:MountingHole H3
U 1 1 5F920888
P 5450 6850
F 0 "H3" H 5550 6896 50  0000 L CNN
F 1 "H3" H 5550 6805 50  0000 L CNN
F 2 "MountingHole:MountingHole_3.2mm_M3" H 5450 6850 50  0001 C CNN
F 3 "~" H 5450 6850 50  0001 C CNN
	1    5450 6850
	1    0    0    -1  
$EndComp
$Comp
L Mechanical:MountingHole H4
U 1 1 5F920C93
P 5450 7100
F 0 "H4" H 5550 7146 50  0000 L CNN
F 1 "H4" H 5550 7055 50  0000 L CNN
F 2 "MountingHole:MountingHole_3.2mm_M3" H 5450 7100 50  0001 C CNN
F 3 "~" H 5450 7100 50  0001 C CNN
	1    5450 7100
	1    0    0    -1  
$EndComp
Wire Notes Line width 20 style dash_dot
	6100 5550 6100 7800
Text Notes 5150 6000 0    98   ~ 20
MOUNTING\n  HOLES
Wire Wire Line
	3050 1600 3650 1600
Wire Wire Line
	3050 2000 3950 2000
Text Label 9500 4350 0    50   ~ 0
D13
Wire Wire Line
	9500 4450 9500 4350
Wire Wire Line
	9500 4650 9500 4750
Wire Wire Line
	9500 5050 9500 5150
$Comp
L power:GND #PWR027
U 1 1 5FA0BCC1
P 9500 5150
F 0 "#PWR027" H 9500 4900 50  0001 C CNN
F 1 "GND" H 9505 4977 50  0000 C CNN
F 2 "" H 9500 5150 50  0001 C CNN
F 3 "" H 9500 5150 50  0001 C CNN
	1    9500 5150
	1    0    0    -1  
$EndComp
$Comp
L Device:LED D5
U 1 1 5FA0ADE3
P 9500 4900
F 0 "D5" V 9539 4782 50  0000 R CNN
F 1 "LED" V 9448 4782 50  0000 R CNN
F 2 "LED_SMD:LED_1206_3216Metric_Pad1.42x1.75mm_HandSolder" H 9500 4900 50  0001 C CNN
F 3 "~" H 9500 4900 50  0001 C CNN
	1    9500 4900
	0    -1   -1   0   
$EndComp
$Comp
L Device:R_Small R5
U 1 1 5FA0A862
P 9500 4550
F 0 "R5" H 9559 4596 50  0000 L CNN
F 1 "R_Small" H 9559 4505 50  0000 L CNN
F 2 "Resistor_SMD:R_1206_3216Metric_Pad1.42x1.75mm_HandSolder" H 9500 4550 50  0001 C CNN
F 3 "~" H 9500 4550 50  0001 C CNN
	1    9500 4550
	1    0    0    -1  
$EndComp
$Comp
L Connector:Conn_01x10_Female J6
U 1 1 5F8B1FAB
P 10600 2550
F 0 "J6" H 10628 2526 50  0000 L CNN
F 1 "D8-D13" V 10650 2100 50  0000 L CNN
F 2 "Connector_PinSocket_2.54mm:PinSocket_1x10_P2.54mm_Vertical" H 10600 2550 50  0001 C CNN
F 3 "~" H 10600 2550 50  0001 C CNN
	1    10600 2550
	1    0    0    -1  
$EndComp
$Comp
L Device:R R1
U 1 1 5F7F9C5B
P 2100 6400
F 0 "R1" H 2170 6446 50  0000 L CNN
F 1 "R" H 2170 6355 50  0000 L CNN
F 2 "Resistor_SMD:R_1206_3216Metric_Pad1.42x1.75mm_HandSolder" V 2030 6400 50  0001 C CNN
F 3 "~" H 2100 6400 50  0001 C CNN
	1    2100 6400
	1    0    0    -1  
$EndComp
$EndSCHEMATC
