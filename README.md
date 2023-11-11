# TM4C123GH6PM-TIVA-C
Hello 

Modbus slave implementation code for TM4C123GH6PM TIVA-C TI board.

Modbus master is PC with Q-MODBUS software.

Functions Tested:

Read:
01: Coils (FC=01)
02: Discrete Inputs (FC=02)
03: Multiple Holding Registers (FC=03)
04: Input Registers (FC=04)

Write:
05: Single Coil (FC=05)
06: Single Holding Register (FC=06)
0F: Multiple Coils (FC=15)
10: Multiple Holding Registers (FC=16)

Microcontroller Board:TM4C123GH6PM
Peripherals Used:    UART0
										 EEPROM
										 SYSTICK
							
	
