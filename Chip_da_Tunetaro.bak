EESchema Schematic File Version 4
LIBS:Chip_da_Tunetaro-cache
EELAYER 29 0
EELAYER END
$Descr A3 16535 11693
encoding utf-8
Sheet 1 1
Title ""
Date ""
Rev ""
Comp ""
Comment1 ""
Comment2 ""
Comment3 ""
Comment4 ""
$EndDescr
$Comp
L ESP32-DEVKITC:ESP32-DEVKITC U1
U 1 1 5D2E8AF5
P 2400 2500
F 0 "U1" H 2400 3967 50  0000 C CNN
F 1 "ESP32-DEVKITC" H 2400 3876 50  0000 C CNN
F 2 "bongorian:ESP32-DEVKITC" H 2400 2500 50  0001 L BNN
F 3 "" H 2400 2500 50  0001 L BNN
F 4 "Module: development kit; Ciphering: AES, WPA, WPA2-PSK, WPS" H 2400 2500 50  0001 L BNN "フィールド4"
F 5 "Unavailable" H 2400 2500 50  0001 L BNN "フィールド5"
F 6 "None" H 2400 2500 50  0001 L BNN "フィールド6"
F 7 "ESP32-DEVKITC" H 2400 2500 50  0001 L BNN "フィールド7"
F 8 "None" H 2400 2500 50  0001 L BNN "フィールド8"
	1    2400 2500
	1    0    0    -1  
$EndComp
$Comp
L lib_microbit_connector:microbit_edge_connector J1
U 1 1 5D2EB31F
P 4800 2950
F 0 "J1" H 4800 4975 50  0000 C CNN
F 1 "microbit_edge_connector" H 4800 4884 50  0000 C CNN
F 2 "Connector_PCBEdge:4UCON_10156_2x40_P1.27mm_Socket_Horizontal" H 4700 2850 50  0001 C CNN
F 3 "https://www.microbit.co.uk/device/pins" H 4700 2850 50  0001 C CNN
	1    4800 2950
	1    0    0    -1  
$EndComp
$Comp
L power:GND #PWR03
U 1 1 5D647A28
P 3150 3850
F 0 "#PWR03" H 3150 3600 50  0001 C CNN
F 1 "GND" H 3155 3677 50  0000 C CNN
F 2 "" H 3150 3850 50  0001 C CNN
F 3 "" H 3150 3850 50  0001 C CNN
	1    3150 3850
	1    0    0    -1  
$EndComp
Wire Wire Line
	3000 3700 3150 3700
Wire Wire Line
	3150 3700 3150 3850
$Comp
L power:+5V #PWR07
U 1 1 5CB5176C
P 1850 6200
F 0 "#PWR07" H 1850 6050 50  0001 C CNN
F 1 "+5V" H 1865 6373 50  0000 C CNN
F 2 "" H 1850 6200 50  0001 C CNN
F 3 "" H 1850 6200 50  0001 C CNN
	1    1850 6200
	1    0    0    -1  
$EndComp
$Comp
L power:GND #PWR08
U 1 1 5CB517A3
P 1850 7000
F 0 "#PWR08" H 1850 6750 50  0001 C CNN
F 1 "GND" H 1855 6827 50  0000 C CNN
F 2 "" H 1850 7000 50  0001 C CNN
F 3 "" H 1850 7000 50  0001 C CNN
	1    1850 7000
	1    0    0    -1  
$EndComp
NoConn ~ 1550 6600
Wire Wire Line
	1850 6200 1850 6300
Wire Wire Line
	1850 6900 1850 7000
Text GLabel 3150 6150 0    50   Input ~ 0
16MHz
Wire Wire Line
	2150 6600 2600 6600
$Comp
L 4xxx:4040 U2
U 1 1 5CB7F88A
P 3850 6650
F 0 "U2" H 3850 7628 50  0000 C CNN
F 1 "4040" H 3850 7537 50  0000 C CNN
F 2 "Package_DIP:DIP-16_W7.62mm_Socket" H 3850 6650 50  0001 C CNN
F 3 "http://www.intersil.com/content/dam/Intersil/documents/cd40/cd4020bms-24bms-40bms.pdf" H 3850 6650 50  0001 C CNN
	1    3850 6650
	1    0    0    -1  
$EndComp
$Comp
L power:GND #PWR09
U 1 1 5CB7F998
P 4650 7550
F 0 "#PWR09" H 4650 7300 50  0001 C CNN
F 1 "GND" H 4655 7377 50  0000 C CNN
F 2 "" H 4650 7550 50  0001 C CNN
F 3 "" H 4650 7550 50  0001 C CNN
	1    4650 7550
	1    0    0    -1  
$EndComp
$Comp
L power:+5V #PWR06
U 1 1 5CB7FA16
P 4550 5850
F 0 "#PWR06" H 4550 5700 50  0001 C CNN
F 1 "+5V" H 4565 6023 50  0000 C CNN
F 2 "" H 4550 5850 50  0001 C CNN
F 3 "" H 4550 5850 50  0001 C CNN
	1    4550 5850
	1    0    0    -1  
$EndComp
Wire Wire Line
	3850 5850 4550 5850
Wire Wire Line
	3850 7550 4650 7550
Wire Wire Line
	3350 6450 3350 7550
Wire Wire Line
	3350 7550 3850 7550
Connection ~ 3850 7550
$Comp
L Device:C C2
U 1 1 5CBC7B12
P 4900 6950
F 0 "C2" H 4786 6904 50  0000 R CNN
F 1 "0.1u" H 4786 6995 50  0000 R CNN
F 2 "Capacitor_THT:C_Disc_D3.0mm_W1.6mm_P2.50mm" H 4938 6800 50  0001 C CNN
F 3 "~" H 4900 6950 50  0001 C CNN
	1    4900 6950
	1    0    0    1   
$EndComp
Wire Wire Line
	4550 5850 4900 5850
Wire Wire Line
	4900 5850 4900 6800
Connection ~ 4550 5850
Wire Wire Line
	4900 7100 4900 7550
Wire Wire Line
	4900 7550 4650 7550
Connection ~ 4650 7550
Text GLabel 4350 6150 2    50   Input ~ 0
CLK_SAA
Text GLabel 4350 6350 2    50   Input ~ 0
CLK_AY
Text GLabel 4350 6250 2    50   Input ~ 0
CLK_SN
NoConn ~ 4350 6450
NoConn ~ 4350 6550
NoConn ~ 4350 6650
NoConn ~ 4350 6750
NoConn ~ 4350 6850
NoConn ~ 4350 6950
NoConn ~ 4350 7050
NoConn ~ 4350 7150
NoConn ~ 4350 7250
$Comp
L Oscillator:CXO_DIP8 X1
U 1 1 5EB55EDF
P 1850 6600
F 0 "X1" H 2191 6646 50  0000 L CNN
F 1 "CXO_DIP8" H 2191 6555 50  0000 L CNN
F 2 "Oscillator:Oscillator_DIP-8" H 2300 6250 50  0001 C CNN
F 3 "http://cdn-reichelt.de/documents/datenblatt/B400/OSZI.pdf" H 1750 6600 50  0001 C CNN
	1    1850 6600
	1    0    0    -1  
$EndComp
NoConn ~ 1800 2000
NoConn ~ 1800 2100
NoConn ~ 3000 1900
NoConn ~ 3000 2000
NoConn ~ 3000 2100
NoConn ~ 3000 2200
Text GLabel 3150 1400 2    50   Input ~ 0
3V3
Wire Wire Line
	3000 1400 3150 1400
$Comp
L Connector:Conn_01x02_Male J2
U 1 1 5D683BD9
P 6850 1150
F 0 "J2" H 6958 1331 50  0000 C CNN
F 1 "Conn_01x02_Male" H 6958 1240 50  0000 C CNN
F 2 "Connector_JST:JST_PH_B2B-PH-K_1x02_P2.00mm_Vertical" H 6850 1150 50  0001 C CNN
F 3 "~" H 6850 1150 50  0001 C CNN
	1    6850 1150
	1    0    0    -1  
$EndComp
Wire Wire Line
	3150 6150 3350 6150
Wire Wire Line
	5300 1150 5400 1150
Wire Wire Line
	5400 1150 5400 1250
Wire Wire Line
	5400 1550 5300 1550
Wire Wire Line
	5300 1450 5400 1450
Connection ~ 5400 1450
Wire Wire Line
	5400 1450 5400 1550
Wire Wire Line
	5300 1350 5400 1350
Connection ~ 5400 1350
Wire Wire Line
	5400 1350 5400 1450
Wire Wire Line
	5300 1250 5400 1250
Connection ~ 5400 1250
Wire Wire Line
	5400 1250 5400 1350
$Comp
L power:GND #PWR02
U 1 1 5D68575F
P 5600 1150
F 0 "#PWR02" H 5600 900 50  0001 C CNN
F 1 "GND" H 5605 977 50  0000 C CNN
F 2 "" H 5600 1150 50  0001 C CNN
F 3 "" H 5600 1150 50  0001 C CNN
	1    5600 1150
	1    0    0    -1  
$EndComp
Wire Wire Line
	5400 1150 5600 1150
Connection ~ 5400 1150
Text GLabel 6200 1550 2    50   Input ~ 0
CLK_SAA
Text GLabel 5450 1750 2    50   Input ~ 0
CLK_SN
Text GLabel 5450 1850 2    50   Input ~ 0
CLK_AY
Wire Wire Line
	5300 1750 5450 1750
Wire Wire Line
	5300 1850 5450 1850
Wire Wire Line
	5300 2950 5400 2950
Wire Wire Line
	5400 2950 5400 3050
Wire Wire Line
	5400 3250 5300 3250
Wire Wire Line
	5300 3150 5400 3150
Connection ~ 5400 3150
Wire Wire Line
	5400 3150 5400 3250
Wire Wire Line
	5300 3050 5400 3050
Connection ~ 5400 3050
Wire Wire Line
	5400 3050 5400 3100
Text GLabel 5500 3100 2    50   Input ~ 0
3V3
Wire Wire Line
	5400 3100 5500 3100
Connection ~ 5400 3100
Wire Wire Line
	5400 3100 5400 3150
Wire Wire Line
	5300 3850 5400 3850
Wire Wire Line
	5400 3850 5400 3950
Wire Wire Line
	5400 4150 5300 4150
Wire Wire Line
	5300 4050 5400 4050
Connection ~ 5400 4050
Wire Wire Line
	5400 4050 5400 4150
Wire Wire Line
	5300 3950 5400 3950
Connection ~ 5400 3950
Wire Wire Line
	5400 3950 5400 4000
Wire Wire Line
	5300 4650 5400 4650
Wire Wire Line
	5400 4650 5400 4750
Wire Wire Line
	5400 4950 5300 4950
Wire Wire Line
	5300 4850 5400 4850
Connection ~ 5400 4850
Wire Wire Line
	5400 4850 5400 4950
Wire Wire Line
	5300 4750 5400 4750
Connection ~ 5400 4750
Wire Wire Line
	5400 4750 5400 4800
Text GLabel 5500 4000 2    50   Input ~ 0
RIGHT_IN
Text GLabel 5500 4800 2    50   Input ~ 0
LEFT_IN
Wire Wire Line
	5400 4000 5500 4000
Connection ~ 5400 4000
Wire Wire Line
	5400 4000 5400 4050
Wire Wire Line
	5400 4800 5500 4800
Connection ~ 5400 4800
Wire Wire Line
	5400 4800 5400 4850
Wire Wire Line
	5300 2050 5400 2050
Wire Wire Line
	5400 2050 5400 2150
Wire Wire Line
	5400 2350 5300 2350
Wire Wire Line
	5300 2250 5400 2250
Connection ~ 5400 2250
Wire Wire Line
	5400 2250 5400 2350
Wire Wire Line
	5300 2150 5400 2150
Connection ~ 5400 2150
Wire Wire Line
	5400 2150 5400 2200
Text GLabel 5500 2200 2    50   Input ~ 0
5V
Wire Wire Line
	5400 2200 5500 2200
Connection ~ 5400 2200
Wire Wire Line
	5400 2200 5400 2250
Wire Wire Line
	5300 1950 5400 1950
Wire Wire Line
	5400 1950 5400 2050
Connection ~ 5400 2050
Wire Wire Line
	5400 2350 5400 2450
Wire Wire Line
	5400 2450 5300 2450
Connection ~ 5400 2350
Text GLabel 5500 2650 2    50   Input ~ 0
DATA
Text GLabel 5500 2750 2    50   Input ~ 0
LATCH
Text GLabel 5500 2850 2    50   Input ~ 0
SCK
Wire Wire Line
	5300 2650 5500 2650
Wire Wire Line
	5300 2750 5500 2750
Wire Wire Line
	5300 2850 5500 2850
Text GLabel 5500 3450 2    50   Input ~ 0
CONTROL1
Text GLabel 5500 3550 2    50   Input ~ 0
CONTROL2
Text GLabel 5500 3650 2    50   Input ~ 0
CONTROL3
Text GLabel 5500 3750 2    50   Input ~ 0
CONTROL4
Wire Wire Line
	5300 3450 5500 3450
Wire Wire Line
	5300 3550 5500 3550
Wire Wire Line
	5300 3650 5500 3650
Wire Wire Line
	5300 3750 5500 3750
Text GLabel 5500 4250 2    50   Input ~ 0
CHECK3
Text GLabel 5500 4350 2    50   Input ~ 0
CHECK4
Text GLabel 5500 4450 2    50   Input ~ 0
CHECK1
Text GLabel 5500 4550 2    50   Input ~ 0
CHECK2
Wire Wire Line
	5300 4250 5500 4250
Wire Wire Line
	5300 4350 5500 4350
Wire Wire Line
	5300 4450 5500 4450
Wire Wire Line
	5300 4550 5500 4550
Text GLabel 5500 2550 2    50   Input ~ 0
MUDA1
Text GLabel 5500 3350 2    50   Input ~ 0
MUDA2
Text GLabel 5500 5050 2    50   Input ~ 0
MUDA3
Wire Wire Line
	5300 2550 5500 2550
Wire Wire Line
	5300 5050 5500 5050
Wire Wire Line
	5300 3350 5500 3350
Text GLabel 3000 3400 2    50   Input ~ 0
CHECK1
Text GLabel 3000 3500 2    50   Input ~ 0
CHECK2
Text GLabel 1800 1700 0    50   Input ~ 0
CHECK3
Text GLabel 1800 1800 0    50   Input ~ 0
CHECK4
Text GLabel 3000 2600 2    50   Input ~ 0
DATA
Text GLabel 1800 3500 0    50   Input ~ 0
LATCH
Text GLabel 1800 3400 0    50   Input ~ 0
SCK
Text GLabel 1800 2600 0    50   Input ~ 0
MUDA1
Text GLabel 1800 3200 0    50   Input ~ 0
CONTROL1
Text GLabel 1800 3300 0    50   Input ~ 0
CONTROL2
Text GLabel 3000 3200 2    50   Input ~ 0
CONTROL3
Text GLabel 3000 3300 2    50   Input ~ 0
CONTROL4
Text GLabel 1800 2500 0    50   Input ~ 0
MUDA2
Text GLabel 1800 2900 0    50   Input ~ 0
MUDA3
NoConn ~ 1800 2300
NoConn ~ 1800 2400
NoConn ~ 3000 1600
NoConn ~ 3000 1700
Text GLabel 3000 2800 2    50   Input ~ 0
DA1
Text GLabel 3000 2900 2    50   Input ~ 0
DA2
$Comp
L Device:C C1
U 1 1 5D6C5D94
P 1700 1300
F 0 "C1" H 1815 1346 50  0000 L CNN
F 1 "1n" H 1815 1255 50  0000 L CNN
F 2 "Capacitor_THT:C_Disc_D3.0mm_W1.6mm_P2.50mm" H 1738 1150 50  0001 C CNN
F 3 "~" H 1700 1300 50  0001 C CNN
	1    1700 1300
	1    0    0    -1  
$EndComp
Wire Wire Line
	1700 1450 1700 1600
Wire Wire Line
	1700 1600 1800 1600
$Comp
L power:GND #PWR01
U 1 1 5D6C859F
P 1700 950
F 0 "#PWR01" H 1700 700 50  0001 C CNN
F 1 "GND" H 1705 777 50  0000 C CNN
F 2 "" H 1700 950 50  0001 C CNN
F 3 "" H 1700 950 50  0001 C CNN
	1    1700 950 
	-1   0    0    1   
$EndComp
Wire Wire Line
	1700 950  1700 1150
$Comp
L Switch:SW_Push SW1
U 1 1 5D742B52
P 3600 2800
F 0 "SW1" V 3554 2948 50  0000 L CNN
F 1 "SW_Push" V 3645 2948 50  0000 L CNN
F 2 "keyswitches:PG1350" H 3600 3000 50  0001 C CNN
F 3 "~" H 3600 3000 50  0001 C CNN
	1    3600 2800
	0    1    1    0   
$EndComp
Wire Wire Line
	3000 3000 3600 3000
Wire Wire Line
	3600 3000 3600 3100
Connection ~ 3600 3000
Text GLabel 3700 2500 2    50   Input ~ 0
3V3
Wire Wire Line
	3700 2500 3600 2500
Wire Wire Line
	3600 2500 3600 2600
Text GLabel 3000 2400 2    50   Input ~ 0
SDA
Text GLabel 3000 2500 2    50   Input ~ 0
SCL
Text GLabel 1800 2800 0    50   Input ~ 0
LED1
Text GLabel 1800 3000 0    50   Input ~ 0
LED2
Text GLabel 1800 3100 0    50   Input ~ 0
LED3
$Comp
L Device:Jumper_NO_Small JP1
U 1 1 5D75767B
P 5950 1550
F 0 "JP1" H 5950 1735 50  0000 C CNN
F 1 "SAA_INT_CLOCK" H 5950 1644 50  0000 C CNN
F 2 "Jumper:SolderJumper-2_P1.3mm_Open_RoundedPad1.0x1.5mm" H 5950 1550 50  0001 C CNN
F 3 "~" H 5950 1550 50  0001 C CNN
	1    5950 1550
	1    0    0    -1  
$EndComp
Wire Wire Line
	5750 1650 5750 1550
Wire Wire Line
	5750 1550 5850 1550
Wire Wire Line
	5300 1650 5750 1650
Wire Wire Line
	6050 1550 6200 1550
Text GLabel 2600 6600 2    50   Input ~ 0
16MHz
$Comp
L power:GND #PWR05
U 1 1 5D75DF61
P 2100 5900
F 0 "#PWR05" H 2100 5650 50  0001 C CNN
F 1 "GND" H 2105 5727 50  0000 C CNN
F 2 "" H 2100 5900 50  0001 C CNN
F 3 "" H 2100 5900 50  0001 C CNN
	1    2100 5900
	1    0    0    -1  
$EndComp
Wire Wire Line
	2100 5750 2100 5900
Connection ~ 2100 5750
Text GLabel 3600 3100 2    50   Input ~ 0
SW
Text GLabel 2250 4850 1    50   Input ~ 0
SW
$Comp
L Device:LED D1
U 1 1 5D76F057
P 1300 4500
F 0 "D1" V 1339 4383 50  0000 R CNN
F 1 "LED" V 1248 4383 50  0000 R CNN
F 2 "LED_THT:LED_D3.0mm" H 1300 4500 50  0001 C CNN
F 3 "~" H 1300 4500 50  0001 C CNN
	1    1300 4500
	0    -1   -1   0   
$EndComp
$Comp
L Device:LED D2
U 1 1 5D76FF5A
P 1650 4500
F 0 "D2" V 1689 4383 50  0000 R CNN
F 1 "LED" V 1598 4383 50  0000 R CNN
F 2 "LED_THT:LED_D3.0mm" H 1650 4500 50  0001 C CNN
F 3 "~" H 1650 4500 50  0001 C CNN
	1    1650 4500
	0    -1   -1   0   
$EndComp
$Comp
L Device:LED D3
U 1 1 5D7703FF
P 2000 4500
F 0 "D3" V 2039 4383 50  0000 R CNN
F 1 "LED" V 1948 4383 50  0000 R CNN
F 2 "LED_THT:LED_D3.0mm" H 2000 4500 50  0001 C CNN
F 3 "~" H 2000 4500 50  0001 C CNN
	1    2000 4500
	0    -1   -1   0   
$EndComp
Wire Wire Line
	2000 4650 2000 4700
Wire Wire Line
	2000 4700 2150 4700
Wire Wire Line
	2150 4700 2150 4850
Wire Wire Line
	1650 4650 1650 4750
Wire Wire Line
	1650 4750 2050 4750
Wire Wire Line
	2050 4750 2050 4850
Wire Wire Line
	1300 4650 1300 4800
Wire Wire Line
	1300 4800 1950 4800
Wire Wire Line
	1950 4800 1950 4850
Text GLabel 1300 4350 1    50   Input ~ 0
LED1
Text GLabel 1650 4350 1    50   Input ~ 0
LED2
Text GLabel 2000 4350 1    50   Input ~ 0
LED3
$Comp
L Connector:Conn_01x04_Female J3
U 1 1 5D77AA3D
P 3700 4600
F 0 "J3" H 3728 4576 50  0000 L CNN
F 1 "I2C" H 3728 4485 50  0000 L CNN
F 2 "Connector_PinHeader_2.54mm:PinHeader_1x04_P2.54mm_Vertical" H 3700 4600 50  0001 C CNN
F 3 "~" H 3700 4600 50  0001 C CNN
	1    3700 4600
	1    0    0    -1  
$EndComp
Text GLabel 3450 4700 0    50   Input ~ 0
SCL
Wire Wire Line
	3450 4700 3500 4700
Text GLabel 3450 4800 0    50   Input ~ 0
SDA
Wire Wire Line
	3450 4800 3500 4800
Text GLabel 3450 4600 0    50   Input ~ 0
3V3
Wire Wire Line
	3450 4600 3500 4600
$Comp
L power:GND #PWR04
U 1 1 5D785F50
P 3150 4500
F 0 "#PWR04" H 3150 4250 50  0001 C CNN
F 1 "GND" H 3155 4327 50  0000 C CNN
F 2 "" H 3150 4500 50  0001 C CNN
F 3 "" H 3150 4500 50  0001 C CNN
	1    3150 4500
	1    0    0    -1  
$EndComp
Wire Wire Line
	3150 4500 3500 4500
$Comp
L SamacSys_Parts:MNR04MRAPJ103 RN1
U 1 1 5D312CFB
P 1950 5650
F 0 "RN1" V 2396 5222 50  0000 R CNN
F 1 "MNR04MRAPJ103" V 2305 5222 50  0000 R CNN
F 2 "bongorian:RESCAX50P100X200X36-8N" H 2600 5750 50  0001 L CNN
F 3 "http://rohmfs.rohm.com/en/products/databook/datasheet/passive/resistor/chip_resistor_network/mnr_g.pdf" H 2600 5650 50  0001 L CNN
F 4 "10k Ohm +/-5% 62.5mW Power Per Element Isolated 4 Resistor Network/Array +/-200ppm/C 0804, Convex, Long Side Terminals" H 2600 5550 50  0001 L CNN "Description"
F 5 "" H 2600 5450 50  0001 L CNN "Height"
F 6 "ROHM Semiconductor" H 2600 5350 50  0001 L CNN "Manufacturer_Name"
F 7 "MNR04MRAPJ103" H 2600 5250 50  0001 L CNN "Manufacturer_Part_Number"
F 8 "" H 2600 5150 50  0001 L CNN "Mouser Part Number"
F 9 "" H 2600 5050 50  0001 L CNN "Mouser Price/Stock"
F 10 "" H 2600 4950 50  0001 L CNN "RS Part Number"
F 11 "" H 2600 4850 50  0001 L CNN "RS Price/Stock"
	1    1950 5650
	0    -1   -1   0   
$EndComp
Wire Wire Line
	1950 5750 2050 5750
Wire Wire Line
	2100 5750 2150 5750
Wire Wire Line
	1950 5650 1950 5750
Wire Wire Line
	2050 5650 2050 5750
Connection ~ 2050 5750
Wire Wire Line
	2050 5750 2100 5750
Wire Wire Line
	2150 5650 2150 5750
Connection ~ 2150 5750
Wire Wire Line
	2150 5750 2250 5750
Wire Wire Line
	2250 5650 2250 5750
Text GLabel 3150 1300 2    50   Input ~ 0
5V
Wire Wire Line
	3000 1300 3150 1300
Text GLabel 4000 1250 2    50   Input ~ 0
5V
$Comp
L power:+5V #PWR0101
U 1 1 5D35047E
P 3950 1150
F 0 "#PWR0101" H 3950 1000 50  0001 C CNN
F 1 "+5V" H 3965 1323 50  0000 C CNN
F 2 "" H 3950 1150 50  0001 C CNN
F 3 "" H 3950 1150 50  0001 C CNN
	1    3950 1150
	1    0    0    -1  
$EndComp
Wire Wire Line
	3950 1150 3950 1250
Wire Wire Line
	3950 1250 4000 1250
Text GLabel 7200 1150 2    50   Input ~ 0
5V
Wire Wire Line
	7050 1150 7200 1150
$Comp
L power:GND #PWR010
U 1 1 5D361EC1
P 7150 1250
F 0 "#PWR010" H 7150 1000 50  0001 C CNN
F 1 "GND" H 7155 1077 50  0000 C CNN
F 2 "" H 7150 1250 50  0001 C CNN
F 3 "" H 7150 1250 50  0001 C CNN
	1    7150 1250
	1    0    0    -1  
$EndComp
Wire Wire Line
	7050 1250 7150 1250
Text GLabel 6850 1800 1    50   Input ~ 0
5V
$Comp
L Device:R R5
U 1 1 5D378686
P 6850 2050
F 0 "R5" H 6920 2096 50  0000 L CNN
F 1 "R" H 6920 2005 50  0000 L CNN
F 2 "Resistor_THT:R_Axial_DIN0204_L3.6mm_D1.6mm_P5.08mm_Horizontal" V 6780 2050 50  0001 C CNN
F 3 "~" H 6850 2050 50  0001 C CNN
	1    6850 2050
	1    0    0    -1  
$EndComp
$Comp
L Device:R R6
U 1 1 5D378DEC
P 6850 2450
F 0 "R6" H 6920 2496 50  0000 L CNN
F 1 "R" H 6920 2405 50  0000 L CNN
F 2 "Resistor_THT:R_Axial_DIN0204_L3.6mm_D1.6mm_P5.08mm_Horizontal" V 6780 2450 50  0001 C CNN
F 3 "~" H 6850 2450 50  0001 C CNN
	1    6850 2450
	1    0    0    -1  
$EndComp
$Comp
L power:GND #PWR012
U 1 1 5D3790A1
P 6850 2700
F 0 "#PWR012" H 6850 2450 50  0001 C CNN
F 1 "GND" H 6855 2527 50  0000 C CNN
F 2 "" H 6850 2700 50  0001 C CNN
F 3 "" H 6850 2700 50  0001 C CNN
	1    6850 2700
	1    0    0    -1  
$EndComp
Wire Wire Line
	6850 1800 6850 1850
Wire Wire Line
	6850 2200 6850 2250
Wire Wire Line
	6850 2600 6850 2650
Connection ~ 6850 2250
Wire Wire Line
	6850 2250 6850 2300
$Comp
L Amplifier_Operational:LMV324 U3
U 1 1 5D38B43E
P 10650 1200
F 0 "U3" H 10650 1567 50  0000 C CNN
F 1 "LMV324" H 10650 1476 50  0000 C CNN
F 2 "Package_SO:SOIC-14_3.9x8.7mm_P1.27mm" H 10600 1300 50  0001 C CNN
F 3 "http://www.ti.com/lit/ds/symlink/lmv324.pdf" H 10700 1400 50  0001 C CNN
	1    10650 1200
	1    0    0    -1  
$EndComp
$Comp
L Amplifier_Operational:LMV324 U3
U 2 1 5D38CD81
P 10650 2500
F 0 "U3" H 10650 2867 50  0000 C CNN
F 1 "LMV324" H 10650 2776 50  0000 C CNN
F 2 "Package_SO:SOIC-14_3.9x8.7mm_P1.27mm" H 10600 2600 50  0001 C CNN
F 3 "http://www.ti.com/lit/ds/symlink/lmv324.pdf" H 10700 2700 50  0001 C CNN
	2    10650 2500
	1    0    0    -1  
$EndComp
$Comp
L Amplifier_Operational:LMV324 U3
U 5 1 5D38F085
P 13900 2000
F 0 "U3" H 13858 2046 50  0000 L CNN
F 1 "LMV324" H 13858 1955 50  0000 L CNN
F 2 "Package_SO:SOIC-14_3.9x8.7mm_P1.27mm" H 13850 2100 50  0001 C CNN
F 3 "http://www.ti.com/lit/ds/symlink/lmv324.pdf" H 13950 2200 50  0001 C CNN
	5    13900 2000
	1    0    0    -1  
$EndComp
Text GLabel 13800 1550 1    50   Input ~ 0
5V
$Comp
L power:GND #PWR011
U 1 1 5D3931B7
P 13800 2450
F 0 "#PWR011" H 13800 2200 50  0001 C CNN
F 1 "GND" H 13805 2277 50  0000 C CNN
F 2 "" H 13800 2450 50  0001 C CNN
F 3 "" H 13800 2450 50  0001 C CNN
	1    13800 2450
	1    0    0    -1  
$EndComp
Wire Wire Line
	13800 1550 13800 1700
Wire Wire Line
	13800 2300 13800 2450
$Comp
L Device:R R1
U 1 1 5D3BD46B
P 10700 1650
F 0 "R1" V 10493 1650 50  0000 C CNN
F 1 "R" V 10584 1650 50  0000 C CNN
F 2 "Resistor_THT:R_Axial_DIN0204_L3.6mm_D1.6mm_P5.08mm_Horizontal" V 10630 1650 50  0001 C CNN
F 3 "~" H 10700 1650 50  0001 C CNN
	1    10700 1650
	0    1    1    0   
$EndComp
$Comp
L Device:R R3
U 1 1 5D3BDA0F
P 10350 1800
F 0 "R3" H 10280 1754 50  0000 R CNN
F 1 "R" H 10280 1845 50  0000 R CNN
F 2 "Resistor_THT:R_Axial_DIN0204_L3.6mm_D1.6mm_P5.08mm_Horizontal" V 10280 1800 50  0001 C CNN
F 3 "~" H 10350 1800 50  0001 C CNN
	1    10350 1800
	-1   0    0    1   
$EndComp
Wire Wire Line
	10350 1650 10550 1650
Wire Wire Line
	10850 1650 11050 1650
Wire Wire Line
	11050 1650 11050 1450
Wire Wire Line
	11050 1200 10950 1200
Wire Wire Line
	10350 1300 10350 1650
Connection ~ 10350 1650
Text GLabel 10200 2050 0    50   Input ~ 0
bias
Wire Wire Line
	10200 2050 10350 2050
Wire Wire Line
	10350 2050 10350 1950
Text GLabel 10200 2400 0    50   Input ~ 0
bias
Wire Wire Line
	10200 2400 10350 2400
Wire Wire Line
	10350 2600 10350 2900
Wire Wire Line
	10350 2900 11050 2900
Wire Wire Line
	11050 2900 11050 2700
Wire Wire Line
	11050 2500 10950 2500
$Comp
L Device:R R2
U 1 1 5D3FD348
P 12500 1650
F 0 "R2" V 12293 1650 50  0000 C CNN
F 1 "R" V 12384 1650 50  0000 C CNN
F 2 "Resistor_THT:R_Axial_DIN0204_L3.6mm_D1.6mm_P5.08mm_Horizontal" V 12430 1650 50  0001 C CNN
F 3 "~" H 12500 1650 50  0001 C CNN
	1    12500 1650
	0    1    1    0   
$EndComp
$Comp
L Device:R R4
U 1 1 5D3FD34E
P 12150 1800
F 0 "R4" H 12080 1754 50  0000 R CNN
F 1 "R" H 12080 1845 50  0000 R CNN
F 2 "Resistor_THT:R_Axial_DIN0204_L3.6mm_D1.6mm_P5.08mm_Horizontal" V 12080 1800 50  0001 C CNN
F 3 "~" H 12150 1800 50  0001 C CNN
	1    12150 1800
	-1   0    0    1   
$EndComp
Wire Wire Line
	12150 1650 12350 1650
Wire Wire Line
	12650 1650 12850 1650
Wire Wire Line
	12850 1650 12850 1450
Wire Wire Line
	12850 1200 12750 1200
Wire Wire Line
	12150 1300 12150 1650
Connection ~ 12150 1650
Text GLabel 12000 2050 0    50   Input ~ 0
bias
Wire Wire Line
	12000 2050 12150 2050
Wire Wire Line
	12150 2050 12150 1950
Text GLabel 12000 2400 0    50   Input ~ 0
bias
Wire Wire Line
	12000 2400 12150 2400
Wire Wire Line
	12150 2600 12150 2900
Wire Wire Line
	12150 2900 12850 2900
Wire Wire Line
	12850 2900 12850 2500
Wire Wire Line
	12850 2500 12750 2500
$Comp
L SamacSys_Parts:RK0972A503L15F VR1
U 1 1 5D40F5BE
P 9100 1200
F 0 "VR1" V 9754 1328 50  0000 L CNN
F 1 "RK0972A503L15F" V 9845 1328 50  0000 L CNN
F 2 "bongorian:RK0972A503L15F" H 10350 1300 50  0001 L CNN
F 3 "http://akizukidenshi.com/download/ds/supertech/RK0972A503L15F.pdf" H 10350 1200 50  0001 L CNN
F 4 "variable resistor" H 10350 1100 50  0001 L CNN "Description"
F 5 "11.3" H 10350 1000 50  0001 L CNN "Height"
F 6 "Supertech" H 10350 900 50  0001 L CNN "Manufacturer_Name"
F 7 "RK0972A503L15F" H 10350 800 50  0001 L CNN "Manufacturer_Part_Number"
F 8 "" H 10350 700 50  0001 L CNN "Mouser Part Number"
F 9 "" H 10350 600 50  0001 L CNN "Mouser Price/Stock"
F 10 "" H 10350 500 50  0001 L CNN "RS Part Number"
F 11 "" H 10350 400 50  0001 L CNN "RS Price/Stock"
	1    9100 1200
	0    1    1    0   
$EndComp
Text GLabel 10100 1100 0    50   Input ~ 0
FLOW_IN_L
Wire Wire Line
	10100 1100 10350 1100
Text GLabel 9000 1050 1    50   Input ~ 0
FLOW_IN_L
Wire Wire Line
	9000 1050 9000 1200
Text GLabel 12000 1100 0    50   Input ~ 0
FLOW_IN_R
Wire Wire Line
	12000 1100 12150 1100
Text GLabel 9200 1100 2    50   Input ~ 0
bias
Wire Wire Line
	9100 1200 9100 1100
Wire Wire Line
	9100 1100 9200 1100
Text GLabel 9200 2700 2    50   Input ~ 0
bias
Wire Wire Line
	9100 2600 9100 2700
Wire Wire Line
	9100 2700 9200 2700
$Comp
L Device:C C3
U 1 1 5D430956
P 7150 2050
F 0 "C3" H 7265 2096 50  0000 L CNN
F 1 "C" H 7265 2005 50  0000 L CNN
F 2 "Capacitor_THT:C_Disc_D3.8mm_W2.6mm_P2.50mm" H 7188 1900 50  0001 C CNN
F 3 "~" H 7150 2050 50  0001 C CNN
	1    7150 2050
	1    0    0    -1  
$EndComp
$Comp
L Device:C C4
U 1 1 5D430D56
P 7150 2450
F 0 "C4" H 7265 2496 50  0000 L CNN
F 1 "C" H 7265 2405 50  0000 L CNN
F 2 "Capacitor_THT:C_Disc_D3.8mm_W2.6mm_P2.50mm" H 7188 2300 50  0001 C CNN
F 3 "~" H 7150 2450 50  0001 C CNN
	1    7150 2450
	1    0    0    -1  
$EndComp
Wire Wire Line
	6850 2650 7150 2650
Wire Wire Line
	7150 2650 7150 2600
Connection ~ 6850 2650
Wire Wire Line
	6850 2650 6850 2700
Wire Wire Line
	6850 2250 7150 2250
Wire Wire Line
	7150 2200 7150 2250
Connection ~ 7150 2250
Wire Wire Line
	7150 2250 7150 2300
Wire Wire Line
	6850 1850 7150 1850
Wire Wire Line
	7150 1850 7150 1900
Connection ~ 6850 1850
Wire Wire Line
	6850 1850 6850 1900
Text GLabel 9000 2750 3    50   Input ~ 0
FLOW_IN_R
Wire Wire Line
	9000 2600 9000 2750
Text GLabel 8600 800  0    50   Input ~ 0
LEFT_IN
Wire Wire Line
	8800 1100 8900 1100
Wire Wire Line
	8900 1100 8900 1200
Text GLabel 8550 2450 0    50   Input ~ 0
RIGHT_IN
Wire Wire Line
	8800 2700 8900 2700
Wire Wire Line
	8900 2700 8900 2600
$Comp
L Device:Jumper_NO_Small JP4
U 1 1 5D483C9E
P 11650 2900
F 0 "JP4" H 11650 3085 50  0000 C CNN
F 1 "Jumper_NO_Small" H 11650 2994 50  0000 C CNN
F 2 "Jumper:SolderJumper-2_P1.3mm_Open_RoundedPad1.0x1.5mm" H 11650 2900 50  0001 C CNN
F 3 "~" H 11650 2900 50  0001 C CNN
	1    11650 2900
	1    0    0    -1  
$EndComp
Wire Wire Line
	11050 2900 11550 2900
Connection ~ 11050 2900
Wire Wire Line
	11750 2900 12150 2900
Connection ~ 12150 2900
Text GLabel 11150 1450 2    50   Input ~ 0
FLOW_OUT_L
Text GLabel 12950 1450 2    50   Input ~ 0
FLOW_OUT_R
Wire Wire Line
	11050 1450 11150 1450
Connection ~ 11050 1450
Wire Wire Line
	11050 1450 11050 1200
Wire Wire Line
	12850 1450 12950 1450
Connection ~ 12850 1450
Wire Wire Line
	12850 1450 12850 1200
Text GLabel 11150 2250 2    50   Input ~ 0
FLOW_OUT_SHIELD
Wire Wire Line
	11150 2250 11150 2700
Wire Wire Line
	11150 2700 11050 2700
Connection ~ 11050 2700
Wire Wire Line
	11050 2700 11050 2500
$Comp
L bongorian:PJ-325 U5
U 1 1 5D4AB5B1
P 15150 2050
F 0 "U5" H 15519 2501 50  0000 L CNN
F 1 "PJ-325" H 15519 2410 50  0000 L CNN
F 2 "bongorian:PJ-325" H 15150 2050 50  0001 C CNN
F 3 "" H 15150 2050 50  0001 C CNN
	1    15150 2050
	1    0    0    -1  
$EndComp
Text GLabel 14800 1650 0    50   Input ~ 0
FLOW_OUT_R
Text GLabel 14800 1850 0    50   Input ~ 0
FLOW_OUT_L
Wire Wire Line
	14800 1850 14850 1850
Wire Wire Line
	14850 1850 14850 1750
Connection ~ 14850 1850
Wire Wire Line
	14800 1650 14850 1650
Wire Wire Line
	14850 1550 14850 1650
Connection ~ 14850 1650
Text GLabel 14800 1450 0    50   Input ~ 0
FLOW_OUT_SHIELD
Wire Wire Line
	14800 1450 14850 1450
$Comp
L bongorian:PJ-325 U6
U 1 1 5D4DDCCC
P 7150 4100
F 0 "U6" H 7519 4551 50  0000 L CNN
F 1 "PJ-325" H 7519 4460 50  0000 L CNN
F 2 "bongorian:PJ-325" H 7150 4100 50  0001 C CNN
F 3 "" H 7150 4100 50  0001 C CNN
	1    7150 4100
	1    0    0    -1  
$EndComp
$Comp
L power:GND #PWR013
U 1 1 5D4DE6FF
P 6650 3350
F 0 "#PWR013" H 6650 3100 50  0001 C CNN
F 1 "GND" H 6655 3177 50  0000 C CNN
F 2 "" H 6650 3350 50  0001 C CNN
F 3 "" H 6650 3350 50  0001 C CNN
	1    6650 3350
	-1   0    0    1   
$EndComp
Wire Wire Line
	6650 3350 6650 3500
Wire Wire Line
	6650 3500 6850 3500
Text GLabel 6450 3300 0    50   Input ~ 0
RIGHT_IN
Text GLabel 6400 4250 0    50   Input ~ 0
LEFT_IN
Wire Wire Line
	6700 3900 6850 3900
Wire Wire Line
	6850 3900 6850 3800
Connection ~ 6850 3900
Wire Wire Line
	6700 3700 6850 3700
Wire Wire Line
	6850 3600 6850 3700
Connection ~ 6850 3700
$Comp
L Jumper:Jumper_3_Open JP2
U 1 1 5D515A52
P 8650 1100
F 0 "JP2" V 8696 1187 50  0000 L CNN
F 1 "FROW_L_SEL" V 8605 1187 50  0000 L CNN
F 2 "Jumper:SolderJumper-3_P1.3mm_Open_RoundedPad1.0x1.5mm" H 8650 1100 50  0001 C CNN
F 3 "~" H 8650 1100 50  0001 C CNN
	1    8650 1100
	0    -1   -1   0   
$EndComp
$Comp
L Jumper:Jumper_3_Open JP3
U 1 1 5D51686F
P 8650 2700
F 0 "JP3" V 8696 2787 50  0000 L CNN
F 1 "FLOW_R_SEL" V 8550 2850 50  0000 L CNN
F 2 "Jumper:SolderJumper-3_P1.3mm_Open_RoundedPad1.0x1.5mm" H 8650 2700 50  0001 C CNN
F 3 "~" H 8650 2700 50  0001 C CNN
	1    8650 2700
	0    -1   -1   0   
$EndComp
Wire Wire Line
	8600 800  8650 800 
Wire Wire Line
	8650 800  8650 850 
Wire Wire Line
	8550 2450 8650 2450
$Comp
L Connector:TestPoint TP1
U 1 1 5D52A940
P 8500 1500
F 0 "TP1" V 8695 1572 50  0000 C CNN
F 1 "FLOW_L_ALT" V 8604 1572 50  0000 C CNN
F 2 "TestPoint:TestPoint_Loop_D1.80mm_Drill1.0mm_Beaded" H 8700 1500 50  0001 C CNN
F 3 "~" H 8700 1500 50  0001 C CNN
	1    8500 1500
	0    -1   -1   0   
$EndComp
$Comp
L Connector:TestPoint TP2
U 1 1 5D52AE84
P 8500 3200
F 0 "TP2" V 8695 3272 50  0000 C CNN
F 1 "FLOW_R_ALT" V 8604 3272 50  0000 C CNN
F 2 "TestPoint:TestPoint_Loop_D1.80mm_Drill1.0mm_Beaded" H 8700 3200 50  0001 C CNN
F 3 "~" H 8700 3200 50  0001 C CNN
	1    8500 3200
	0    -1   -1   0   
$EndComp
Wire Wire Line
	8650 2950 8650 3200
Wire Wire Line
	8650 3200 8500 3200
Wire Wire Line
	8500 1500 8650 1500
Wire Wire Line
	8650 1500 8650 1350
$Comp
L Jumper:Jumper_3_Open JP5
U 1 1 5D540E3A
P 6500 3600
F 0 "JP5" V 6546 3687 50  0000 L CNN
F 1 "OUT_R_SEL" V 6455 3687 50  0000 L CNN
F 2 "Jumper:SolderJumper-3_P1.3mm_Open_RoundedPad1.0x1.5mm" H 6500 3600 50  0001 C CNN
F 3 "~" H 6500 3600 50  0001 C CNN
	1    6500 3600
	0    -1   -1   0   
$EndComp
Wire Wire Line
	6450 3300 6500 3300
Wire Wire Line
	6500 3300 6500 3350
Wire Wire Line
	6650 3600 6700 3600
Wire Wire Line
	6700 3600 6700 3700
$Comp
L Jumper:Jumper_3_Open JP6
U 1 1 5D55630E
P 6800 4250
F 0 "JP6" H 6800 4381 50  0000 C CNN
F 1 "OUT_L_SEL" H 6800 4472 50  0000 C CNN
F 2 "Jumper:SolderJumper-3_P1.3mm_Open_RoundedPad1.0x1.5mm" H 6800 4250 50  0001 C CNN
F 3 "~" H 6800 4250 50  0001 C CNN
	1    6800 4250
	-1   0    0    1   
$EndComp
Wire Wire Line
	6700 3900 6700 4000
Wire Wire Line
	6700 4000 6800 4000
Wire Wire Line
	6800 4000 6800 4100
Wire Wire Line
	6400 4250 6550 4250
$Comp
L Connector:TestPoint TP6
U 1 1 5D56BFC1
P 7050 4250
F 0 "TP6" V 7004 4438 50  0000 L CNN
F 1 "OUT_L_ALT" V 7095 4438 50  0000 L CNN
F 2 "TestPoint:TestPoint_Loop_D1.80mm_Drill1.0mm_Beaded" H 7250 4250 50  0001 C CNN
F 3 "~" H 7250 4250 50  0001 C CNN
	1    7050 4250
	0    1    1    0   
$EndComp
$Comp
L Connector:TestPoint TP4
U 1 1 5D56CB8D
P 6300 4000
F 0 "TP4" V 6495 4072 50  0000 C CNN
F 1 "OUT_R_ALT" V 6404 4072 50  0000 C CNN
F 2 "TestPoint:TestPoint_Loop_D1.80mm_Drill1.0mm_Beaded" H 6500 4000 50  0001 C CNN
F 3 "~" H 6500 4000 50  0001 C CNN
	1    6300 4000
	0    -1   -1   0   
$EndComp
Wire Wire Line
	6300 4000 6500 4000
Wire Wire Line
	6500 4000 6500 3850
Text GLabel 7550 2250 2    50   Input ~ 0
bias
Wire Wire Line
	7150 2250 7350 2250
$Comp
L Connector:TestPoint TP3
U 1 1 5D582BFF
P 7500 2100
F 0 "TP3" H 7558 2218 50  0000 L CNN
F 1 "BIAS" H 7558 2127 50  0000 L CNN
F 2 "TestPoint:TestPoint_Loop_D1.80mm_Drill1.0mm_Beaded" H 7700 2100 50  0001 C CNN
F 3 "~" H 7700 2100 50  0001 C CNN
	1    7500 2100
	1    0    0    -1  
$EndComp
Wire Wire Line
	7500 2100 7350 2100
Wire Wire Line
	7350 2100 7350 2250
Connection ~ 7350 2250
Wire Wire Line
	7350 2250 7550 2250
$Comp
L Mechanical:MountingHole H1
U 1 1 5D58EB1D
P 7700 9750
F 0 "H1" H 7800 9796 50  0000 L CNN
F 1 "MountingHole" H 7800 9705 50  0000 L CNN
F 2 "MountingHole:MountingHole_2.2mm_M2" H 7700 9750 50  0001 C CNN
F 3 "~" H 7700 9750 50  0001 C CNN
	1    7700 9750
	1    0    0    -1  
$EndComp
$Comp
L Mechanical:MountingHole H2
U 1 1 5D58EC4C
P 7700 10000
F 0 "H2" H 7800 10046 50  0000 L CNN
F 1 "MountingHole" H 7800 9955 50  0000 L CNN
F 2 "MountingHole:MountingHole_2.2mm_M2" H 7700 10000 50  0001 C CNN
F 3 "~" H 7700 10000 50  0001 C CNN
	1    7700 10000
	1    0    0    -1  
$EndComp
$Comp
L Mechanical:MountingHole H3
U 1 1 5D58EDDB
P 7700 10250
F 0 "H3" H 7800 10296 50  0000 L CNN
F 1 "MountingHole" H 7800 10205 50  0000 L CNN
F 2 "MountingHole:MountingHole_2.2mm_M2" H 7700 10250 50  0001 C CNN
F 3 "~" H 7700 10250 50  0001 C CNN
	1    7700 10250
	1    0    0    -1  
$EndComp
$Comp
L Mechanical:MountingHole H4
U 1 1 5D58F015
P 7700 10500
F 0 "H4" H 7800 10546 50  0000 L CNN
F 1 "MountingHole" H 7800 10455 50  0000 L CNN
F 2 "MountingHole:MountingHole_2.2mm_M2" H 7700 10500 50  0001 C CNN
F 3 "~" H 7700 10500 50  0001 C CNN
	1    7700 10500
	1    0    0    -1  
$EndComp
$Comp
L Connector:Conn_01x02_Male J4
U 1 1 5D58F740
P 14700 3250
F 0 "J4" H 14808 3431 50  0000 C CNN
F 1 "POWERPOINT" H 14808 3340 50  0000 C CNN
F 2 "Connector_PinHeader_2.54mm:PinHeader_1x02_P2.54mm_Vertical" H 14700 3250 50  0001 C CNN
F 3 "~" H 14700 3250 50  0001 C CNN
	1    14700 3250
	1    0    0    -1  
$EndComp
Text GLabel 15050 3250 2    50   Input ~ 0
5V
Wire Wire Line
	14900 3250 15050 3250
$Comp
L power:GND #PWR014
U 1 1 5D58F749
P 15000 3350
F 0 "#PWR014" H 15000 3100 50  0001 C CNN
F 1 "GND" H 15005 3177 50  0000 C CNN
F 2 "" H 15000 3350 50  0001 C CNN
F 3 "" H 15000 3350 50  0001 C CNN
	1    15000 3350
	1    0    0    -1  
$EndComp
Wire Wire Line
	14900 3350 15000 3350
$Comp
L SamacSys_Parts:RK0972A503L15F VR2
U 1 1 5D5A7761
P 9100 4500
F 0 "VR2" V 9754 4628 50  0000 L CNN
F 1 "RK0972A503L15F" V 9845 4628 50  0000 L CNN
F 2 "bongorian:RK0972A503L15F" H 10350 4600 50  0001 L CNN
F 3 "http://akizukidenshi.com/download/ds/supertech/RK0972A503L15F.pdf" H 10350 4500 50  0001 L CNN
F 4 "variable resistor" H 10350 4400 50  0001 L CNN "Description"
F 5 "11.3" H 10350 4300 50  0001 L CNN "Height"
F 6 "Supertech" H 10350 4200 50  0001 L CNN "Manufacturer_Name"
F 7 "RK0972A503L15F" H 10350 4100 50  0001 L CNN "Manufacturer_Part_Number"
F 8 "" H 10350 4000 50  0001 L CNN "Mouser Part Number"
F 9 "" H 10350 3900 50  0001 L CNN "Mouser Price/Stock"
F 10 "" H 10350 3800 50  0001 L CNN "RS Part Number"
F 11 "" H 10350 3700 50  0001 L CNN "RS Price/Stock"
	1    9100 4500
	0    1    1    0   
$EndComp
Text GLabel 9000 4350 1    50   Input ~ 0
AMP_IN_L
Wire Wire Line
	9000 4350 9000 4500
Wire Wire Line
	9100 4500 9100 4400
Wire Wire Line
	9100 5900 9100 6000
Text GLabel 9000 6050 3    50   Input ~ 0
AMP_IN_R
Wire Wire Line
	9000 5900 9000 6050
Text GLabel 8600 4100 0    50   Input ~ 0
LEFT_IN
Wire Wire Line
	8800 4400 8900 4400
Wire Wire Line
	8900 4400 8900 4500
Text GLabel 8550 5750 0    50   Input ~ 0
RIGHT_IN
Wire Wire Line
	8800 6000 8900 6000
Wire Wire Line
	8900 6000 8900 5900
$Comp
L Jumper:Jumper_3_Open JP7
U 1 1 5D5A7777
P 8650 4400
F 0 "JP7" V 8696 4487 50  0000 L CNN
F 1 "AMP_L_SEL" V 8605 4487 50  0000 L CNN
F 2 "Jumper:SolderJumper-3_P1.3mm_Open_RoundedPad1.0x1.5mm" H 8650 4400 50  0001 C CNN
F 3 "~" H 8650 4400 50  0001 C CNN
	1    8650 4400
	0    -1   -1   0   
$EndComp
$Comp
L Jumper:Jumper_3_Open JP8
U 1 1 5D5A777D
P 8650 6000
F 0 "JP8" V 8696 6087 50  0000 L CNN
F 1 "AMP_R_SEL" V 8550 6150 50  0000 L CNN
F 2 "Jumper:SolderJumper-3_P1.3mm_Open_RoundedPad1.0x1.5mm" H 8650 6000 50  0001 C CNN
F 3 "~" H 8650 6000 50  0001 C CNN
	1    8650 6000
	0    -1   -1   0   
$EndComp
Wire Wire Line
	8600 4100 8650 4100
Wire Wire Line
	8650 4100 8650 4150
Wire Wire Line
	8550 5750 8650 5750
$Comp
L Connector:TestPoint TP7
U 1 1 5D5A7786
P 8500 4800
F 0 "TP7" V 8695 4872 50  0000 C CNN
F 1 "AMP_L_ALT" V 8604 4872 50  0000 C CNN
F 2 "TestPoint:TestPoint_Loop_D1.80mm_Drill1.0mm_Beaded" H 8700 4800 50  0001 C CNN
F 3 "~" H 8700 4800 50  0001 C CNN
	1    8500 4800
	0    -1   -1   0   
$EndComp
$Comp
L Connector:TestPoint TP9
U 1 1 5D5A778C
P 8500 6500
F 0 "TP9" V 8695 6572 50  0000 C CNN
F 1 "AMP_R_ALT" V 8604 6572 50  0000 C CNN
F 2 "TestPoint:TestPoint_Loop_D1.80mm_Drill1.0mm_Beaded" H 8700 6500 50  0001 C CNN
F 3 "~" H 8700 6500 50  0001 C CNN
	1    8500 6500
	0    -1   -1   0   
$EndComp
Wire Wire Line
	8650 6250 8650 6500
Wire Wire Line
	8650 6500 8500 6500
Wire Wire Line
	8500 4800 8650 4800
Wire Wire Line
	8650 4800 8650 4650
$Comp
L power:GND #PWR019
U 1 1 5D5B51B9
P 9400 6200
F 0 "#PWR019" H 9400 5950 50  0001 C CNN
F 1 "GND" H 9405 6027 50  0000 C CNN
F 2 "" H 9400 6200 50  0001 C CNN
F 3 "" H 9400 6200 50  0001 C CNN
	1    9400 6200
	1    0    0    -1  
$EndComp
Wire Wire Line
	9400 6000 9400 6200
Wire Wire Line
	9100 6000 9400 6000
$Comp
L power:GND #PWR015
U 1 1 5D5C2A89
P 9400 4500
F 0 "#PWR015" H 9400 4250 50  0001 C CNN
F 1 "GND" H 9405 4327 50  0000 C CNN
F 2 "" H 9400 4500 50  0001 C CNN
F 3 "" H 9400 4500 50  0001 C CNN
	1    9400 4500
	1    0    0    -1  
$EndComp
Wire Wire Line
	9400 4400 9400 4500
Wire Wire Line
	9100 4400 9400 4400
$Comp
L Amplifier_Operational:LMV324 U4
U 1 1 5D5D586F
P 11400 4500
F 0 "U4" H 11400 4867 50  0000 C CNN
F 1 "LMV324" H 11400 4776 50  0000 C CNN
F 2 "Package_SO:SOIC-14_3.9x8.7mm_P1.27mm" H 11350 4600 50  0001 C CNN
F 3 "http://www.ti.com/lit/ds/symlink/lmv324.pdf" H 11450 4700 50  0001 C CNN
	1    11400 4500
	1    0    0    -1  
$EndComp
$Comp
L Amplifier_Operational:LMV324 U4
U 5 1 5D5D587B
P 15100 4800
F 0 "U4" H 15058 4846 50  0000 L CNN
F 1 "LMV324" H 15058 4755 50  0000 L CNN
F 2 "Package_SO:SOIC-14_3.9x8.7mm_P1.27mm" H 15050 4900 50  0001 C CNN
F 3 "http://www.ti.com/lit/ds/symlink/lmv324.pdf" H 15150 5000 50  0001 C CNN
	5    15100 4800
	1    0    0    -1  
$EndComp
Text GLabel 15000 4350 1    50   Input ~ 0
5V
$Comp
L power:GND #PWR017
U 1 1 5D5D5882
P 15000 5250
F 0 "#PWR017" H 15000 5000 50  0001 C CNN
F 1 "GND" H 15005 5077 50  0000 C CNN
F 2 "" H 15000 5250 50  0001 C CNN
F 3 "" H 15000 5250 50  0001 C CNN
	1    15000 5250
	1    0    0    -1  
$EndComp
Wire Wire Line
	15000 4350 15000 4500
Wire Wire Line
	15000 5100 15000 5250
$Comp
L Amplifier_Operational:LMV324 U3
U 3 1 5D6171A0
P 12450 1200
F 0 "U3" H 12450 1567 50  0000 C CNN
F 1 "LMV324" H 12450 1476 50  0000 C CNN
F 2 "Package_SO:SOIC-14_3.9x8.7mm_P1.27mm" H 12400 1300 50  0001 C CNN
F 3 "http://www.ti.com/lit/ds/symlink/lmv324.pdf" H 12500 1400 50  0001 C CNN
	3    12450 1200
	1    0    0    -1  
$EndComp
$Comp
L Amplifier_Operational:LMV324 U3
U 4 1 5D61936D
P 12450 2500
F 0 "U3" H 12450 2867 50  0000 C CNN
F 1 "LMV324" H 12450 2776 50  0000 C CNN
F 2 "Package_SO:SOIC-14_3.9x8.7mm_P1.27mm" H 12400 2600 50  0001 C CNN
F 3 "http://www.ti.com/lit/ds/symlink/lmv324.pdf" H 12500 2700 50  0001 C CNN
	4    12450 2500
	1    0    0    -1  
$EndComp
$Comp
L Amplifier_Operational:LMV324 U4
U 3 1 5D61A6F8
P 11400 5600
F 0 "U4" H 11400 5967 50  0000 C CNN
F 1 "LMV324" H 11400 5876 50  0000 C CNN
F 2 "Package_SO:SOIC-14_3.9x8.7mm_P1.27mm" H 11350 5700 50  0001 C CNN
F 3 "http://www.ti.com/lit/ds/symlink/lmv324.pdf" H 11450 5800 50  0001 C CNN
	3    11400 5600
	1    0    0    -1  
$EndComp
$Comp
L Amplifier_Operational:LMV324 U4
U 4 1 5D61B744
P 12750 5500
F 0 "U4" H 12750 5867 50  0000 C CNN
F 1 "LMV324" H 12750 5776 50  0000 C CNN
F 2 "Package_SO:SOIC-14_3.9x8.7mm_P1.27mm" H 12700 5600 50  0001 C CNN
F 3 "http://www.ti.com/lit/ds/symlink/lmv324.pdf" H 12800 5700 50  0001 C CNN
	4    12750 5500
	1    0    0    -1  
$EndComp
$Comp
L Amplifier_Operational:LMV324 U4
U 2 1 5D5D5875
P 12750 4400
F 0 "U4" H 12750 4767 50  0000 C CNN
F 1 "LMV324" H 12750 4676 50  0000 C CNN
F 2 "Package_SO:SOIC-14_3.9x8.7mm_P1.27mm" H 12700 4500 50  0001 C CNN
F 3 "http://www.ti.com/lit/ds/symlink/lmv324.pdf" H 12800 4600 50  0001 C CNN
	2    12750 4400
	1    0    0    -1  
$EndComp
Text GLabel 10350 4600 0    50   Input ~ 0
AMP_IN_L
$Comp
L Device:C C6
U 1 1 5D67C2AD
P 10500 4600
F 0 "C6" V 10248 4600 50  0000 C CNN
F 1 "C" V 10339 4600 50  0000 C CNN
F 2 "Capacitor_THT:C_Disc_D3.8mm_W2.6mm_P2.50mm" H 10538 4450 50  0001 C CNN
F 3 "~" H 10500 4600 50  0001 C CNN
	1    10500 4600
	0    1    1    0   
$EndComp
$Comp
L Device:R R9
U 1 1 5D67CA5D
P 10850 4600
F 0 "R9" V 10643 4600 50  0000 C CNN
F 1 "R" V 10734 4600 50  0000 C CNN
F 2 "Resistor_THT:R_Axial_DIN0204_L3.6mm_D1.6mm_P5.08mm_Horizontal" V 10780 4600 50  0001 C CNN
F 3 "~" H 10850 4600 50  0001 C CNN
	1    10850 4600
	0    1    1    0   
$EndComp
Wire Wire Line
	10650 4600 10700 4600
Wire Wire Line
	11000 4600 11050 4600
$Comp
L Device:R R12
U 1 1 5D698B85
P 11500 4950
F 0 "R12" V 11293 4950 50  0000 C CNN
F 1 "R" V 11384 4950 50  0000 C CNN
F 2 "Resistor_THT:R_Axial_DIN0204_L3.6mm_D1.6mm_P5.08mm_Horizontal" V 11430 4950 50  0001 C CNN
F 3 "~" H 11500 4950 50  0001 C CNN
	1    11500 4950
	0    1    1    0   
$EndComp
Wire Wire Line
	11050 4600 11050 4950
Wire Wire Line
	11050 4950 11350 4950
Connection ~ 11050 4600
Wire Wire Line
	11050 4600 11100 4600
Wire Wire Line
	11650 4950 11900 4950
Wire Wire Line
	11900 4950 11900 4500
Wire Wire Line
	11900 4500 11700 4500
$Comp
L Device:R R8
U 1 1 5D6B7714
P 12050 4500
F 0 "R8" V 11843 4500 50  0000 C CNN
F 1 "R" V 11934 4500 50  0000 C CNN
F 2 "Resistor_THT:R_Axial_DIN0204_L3.6mm_D1.6mm_P5.08mm_Horizontal" V 11980 4500 50  0001 C CNN
F 3 "~" H 12050 4500 50  0001 C CNN
	1    12050 4500
	0    1    1    0   
$EndComp
Connection ~ 11900 4500
Wire Wire Line
	12200 4500 12350 4500
$Comp
L Device:R R11
U 1 1 5D6C6FA2
P 12700 4850
F 0 "R11" V 12493 4850 50  0000 C CNN
F 1 "R" V 12584 4850 50  0000 C CNN
F 2 "Resistor_THT:R_Axial_DIN0204_L3.6mm_D1.6mm_P5.08mm_Horizontal" V 12630 4850 50  0001 C CNN
F 3 "~" H 12700 4850 50  0001 C CNN
	1    12700 4850
	0    1    1    0   
$EndComp
Wire Wire Line
	12350 4500 12350 4850
Wire Wire Line
	12350 4850 12550 4850
Connection ~ 12350 4500
Wire Wire Line
	12350 4500 12450 4500
Wire Wire Line
	13050 4400 13150 4400
Wire Wire Line
	13150 4400 13150 4850
Wire Wire Line
	13150 4850 12850 4850
Text GLabel 10950 4100 0    50   Input ~ 0
bias
Wire Wire Line
	10950 4100 11050 4100
Wire Wire Line
	11050 4100 11050 4400
Wire Wire Line
	11050 4400 11100 4400
Text GLabel 12300 4100 0    50   Input ~ 0
bias
Wire Wire Line
	12300 4100 12400 4100
Wire Wire Line
	12400 4100 12400 4300
Wire Wire Line
	12400 4300 12450 4300
$Comp
L Device:R R7
U 1 1 5D703E7E
P 13400 4400
F 0 "R7" V 13193 4400 50  0000 C CNN
F 1 "R" V 13284 4400 50  0000 C CNN
F 2 "Resistor_THT:R_Axial_DIN0204_L3.6mm_D1.6mm_P5.08mm_Horizontal" V 13330 4400 50  0001 C CNN
F 3 "~" H 13400 4400 50  0001 C CNN
	1    13400 4400
	0    1    1    0   
$EndComp
Wire Wire Line
	13150 4400 13250 4400
Connection ~ 13150 4400
$Comp
L Device:C C5
U 1 1 5D713E7E
P 13700 4400
F 0 "C5" V 13448 4400 50  0000 C CNN
F 1 "C" V 13539 4400 50  0000 C CNN
F 2 "Capacitor_THT:C_Disc_D3.8mm_W2.6mm_P2.50mm" H 13738 4250 50  0001 C CNN
F 3 "~" H 13700 4400 50  0001 C CNN
	1    13700 4400
	0    1    1    0   
$EndComp
$Comp
L Device:R R10
U 1 1 5D714611
P 13950 4650
F 0 "R10" H 13880 4604 50  0000 R CNN
F 1 "R" H 13880 4695 50  0000 R CNN
F 2 "Resistor_THT:R_Axial_DIN0204_L3.6mm_D1.6mm_P5.08mm_Horizontal" V 13880 4650 50  0001 C CNN
F 3 "~" H 13950 4650 50  0001 C CNN
	1    13950 4650
	-1   0    0    1   
$EndComp
Wire Wire Line
	13850 4400 13950 4400
Wire Wire Line
	13950 4400 13950 4500
$Comp
L power:GND #PWR016
U 1 1 5D724863
P 13950 4950
F 0 "#PWR016" H 13950 4700 50  0001 C CNN
F 1 "GND" H 13955 4777 50  0000 C CNN
F 2 "" H 13950 4950 50  0001 C CNN
F 3 "" H 13950 4950 50  0001 C CNN
	1    13950 4950
	1    0    0    -1  
$EndComp
Wire Wire Line
	13950 4800 13950 4950
Text GLabel 14150 4400 2    50   Input ~ 0
LEFT_OUT
Wire Wire Line
	13950 4400 14100 4400
Connection ~ 13950 4400
Text GLabel 10350 5700 0    50   Input ~ 0
AMP_IN_R
$Comp
L Device:C C8
U 1 1 5D76A8EE
P 10500 5700
F 0 "C8" V 10248 5700 50  0000 C CNN
F 1 "C" V 10339 5700 50  0000 C CNN
F 2 "Capacitor_THT:C_Disc_D3.8mm_W2.6mm_P2.50mm" H 10538 5550 50  0001 C CNN
F 3 "~" H 10500 5700 50  0001 C CNN
	1    10500 5700
	0    1    1    0   
$EndComp
$Comp
L Device:R R15
U 1 1 5D76A8F4
P 10850 5700
F 0 "R15" V 10643 5700 50  0000 C CNN
F 1 "R" V 10734 5700 50  0000 C CNN
F 2 "Resistor_THT:R_Axial_DIN0204_L3.6mm_D1.6mm_P5.08mm_Horizontal" V 10780 5700 50  0001 C CNN
F 3 "~" H 10850 5700 50  0001 C CNN
	1    10850 5700
	0    1    1    0   
$EndComp
Wire Wire Line
	10650 5700 10700 5700
Wire Wire Line
	11000 5700 11050 5700
$Comp
L Device:R R18
U 1 1 5D76A8FC
P 11500 6050
F 0 "R18" V 11293 6050 50  0000 C CNN
F 1 "R" V 11384 6050 50  0000 C CNN
F 2 "Resistor_THT:R_Axial_DIN0204_L3.6mm_D1.6mm_P5.08mm_Horizontal" V 11430 6050 50  0001 C CNN
F 3 "~" H 11500 6050 50  0001 C CNN
	1    11500 6050
	0    1    1    0   
$EndComp
Wire Wire Line
	11050 5700 11050 6050
Wire Wire Line
	11050 6050 11350 6050
Connection ~ 11050 5700
Wire Wire Line
	11050 5700 11100 5700
Wire Wire Line
	11650 6050 11900 6050
Wire Wire Line
	11900 6050 11900 5600
Wire Wire Line
	11900 5600 11700 5600
$Comp
L Device:R R14
U 1 1 5D76A909
P 12050 5600
F 0 "R14" V 11843 5600 50  0000 C CNN
F 1 "R" V 11934 5600 50  0000 C CNN
F 2 "Resistor_THT:R_Axial_DIN0204_L3.6mm_D1.6mm_P5.08mm_Horizontal" V 11980 5600 50  0001 C CNN
F 3 "~" H 12050 5600 50  0001 C CNN
	1    12050 5600
	0    1    1    0   
$EndComp
Connection ~ 11900 5600
Wire Wire Line
	12200 5600 12350 5600
$Comp
L Device:R R17
U 1 1 5D76A911
P 12700 5950
F 0 "R17" V 12493 5950 50  0000 C CNN
F 1 "R" V 12584 5950 50  0000 C CNN
F 2 "Resistor_THT:R_Axial_DIN0204_L3.6mm_D1.6mm_P5.08mm_Horizontal" V 12630 5950 50  0001 C CNN
F 3 "~" H 12700 5950 50  0001 C CNN
	1    12700 5950
	0    1    1    0   
$EndComp
Wire Wire Line
	12350 5600 12350 5950
Wire Wire Line
	12350 5950 12550 5950
Connection ~ 12350 5600
Wire Wire Line
	12350 5600 12450 5600
Wire Wire Line
	13050 5500 13150 5500
Wire Wire Line
	13150 5500 13150 5950
Wire Wire Line
	13150 5950 12850 5950
Text GLabel 10950 5200 0    50   Input ~ 0
bias
Wire Wire Line
	10950 5200 11050 5200
Wire Wire Line
	11050 5200 11050 5500
Wire Wire Line
	11050 5500 11100 5500
Text GLabel 12300 5200 0    50   Input ~ 0
bias
Wire Wire Line
	12300 5200 12400 5200
Wire Wire Line
	12400 5200 12400 5400
Wire Wire Line
	12400 5400 12450 5400
$Comp
L Device:R R13
U 1 1 5D76A926
P 13400 5500
F 0 "R13" V 13193 5500 50  0000 C CNN
F 1 "R" V 13284 5500 50  0000 C CNN
F 2 "Resistor_THT:R_Axial_DIN0204_L3.6mm_D1.6mm_P5.08mm_Horizontal" V 13330 5500 50  0001 C CNN
F 3 "~" H 13400 5500 50  0001 C CNN
	1    13400 5500
	0    1    1    0   
$EndComp
Wire Wire Line
	13150 5500 13250 5500
Connection ~ 13150 5500
$Comp
L Device:C C7
U 1 1 5D76A92E
P 13700 5500
F 0 "C7" V 13448 5500 50  0000 C CNN
F 1 "C" V 13539 5500 50  0000 C CNN
F 2 "Capacitor_THT:C_Disc_D3.8mm_W2.6mm_P2.50mm" H 13738 5350 50  0001 C CNN
F 3 "~" H 13700 5500 50  0001 C CNN
	1    13700 5500
	0    1    1    0   
$EndComp
$Comp
L Device:R R16
U 1 1 5D76A934
P 13950 5750
F 0 "R16" H 13880 5704 50  0000 R CNN
F 1 "R" H 13880 5795 50  0000 R CNN
F 2 "Resistor_THT:R_Axial_DIN0204_L3.6mm_D1.6mm_P5.08mm_Horizontal" V 13880 5750 50  0001 C CNN
F 3 "~" H 13950 5750 50  0001 C CNN
	1    13950 5750
	-1   0    0    1   
$EndComp
Wire Wire Line
	13850 5500 13950 5500
Wire Wire Line
	13950 5500 13950 5600
$Comp
L power:GND #PWR018
U 1 1 5D76A93C
P 13950 6050
F 0 "#PWR018" H 13950 5800 50  0001 C CNN
F 1 "GND" H 13955 5877 50  0000 C CNN
F 2 "" H 13950 6050 50  0001 C CNN
F 3 "" H 13950 6050 50  0001 C CNN
	1    13950 6050
	1    0    0    -1  
$EndComp
Wire Wire Line
	13950 5900 13950 6050
Text GLabel 14150 5500 2    50   Input ~ 0
RIGHT_OUT
Wire Wire Line
	13950 5500 14100 5500
Connection ~ 13950 5500
$Comp
L Connector:TestPoint TP5
U 1 1 5D79652F
P 14100 4150
F 0 "TP5" H 14158 4268 50  0000 L CNN
F 1 "LEFT_OUT" H 14158 4177 50  0000 L CNN
F 2 "TestPoint:TestPoint_Loop_D1.80mm_Drill1.0mm_Beaded" H 14300 4150 50  0001 C CNN
F 3 "~" H 14300 4150 50  0001 C CNN
	1    14100 4150
	1    0    0    -1  
$EndComp
Wire Wire Line
	14100 4150 14100 4400
Connection ~ 14100 4400
Wire Wire Line
	14100 4400 14150 4400
$Comp
L Connector:TestPoint TP8
U 1 1 5D7AA40A
P 14100 5300
F 0 "TP8" H 14158 5418 50  0000 L CNN
F 1 "RIGHT_OUT" H 14158 5327 50  0000 L CNN
F 2 "TestPoint:TestPoint_Loop_D1.80mm_Drill1.0mm_Beaded" H 14300 5300 50  0001 C CNN
F 3 "~" H 14300 5300 50  0001 C CNN
	1    14100 5300
	1    0    0    -1  
$EndComp
Wire Wire Line
	14100 5300 14100 5500
Connection ~ 14100 5500
Wire Wire Line
	14100 5500 14150 5500
$EndSCHEMATC
