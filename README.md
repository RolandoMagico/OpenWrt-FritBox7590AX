# OpenWrt-FritzBox7590AX
Information about OpenWrt on FritzBox 7590AX

## Disassembly

There are 5 T10 screws at the bottom which must be removed to open remove the top cover.

## UART
There are 4 pinholes at the big black metal shield/cover. Pinout from back to front:
```
O  GND
O  TX
O  RX
[] VCC
```
Do NOT connect VCC. UART settings: 115200, 8N1.

## Wifi

### 2.4 GHz

- WAV614A1MC-S-LN24 with SKY33021 frontend

### 5 GHz

- WAV624A1MC-S-LN25 with QPF4530 frontend
