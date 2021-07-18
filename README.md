# Air-Pollution-Monitoring-System
I have worked on Arduino IDE associating the hardware circuitry and calibrated the results with MQ135 Gas sensor which gives us an output in serial monitor showing the risk of pollution levels, the amount of CO2 PPM present in the atmosphere. This system continuously monitors the CO2 levels present in the atmosphere and prints the risk level present (Fresh Air, Poor Air, Very Poor Air according to the PPM levels ) 

# Circuit Diagram
![image](https://user-images.githubusercontent.com/73469122/126072102-6d5941cc-4698-4996-9ce0-4e47e3f55770.png)


# Connections
Arduino ==> LCD

GND ==> GND
5 V ==> Vcc
D13 ==> RS
GND ==> R/W
D12 ==> Enable
D6 ==> DB4
D5 ==> DB5
D4 ==> DB6
D3 ==> DB7
5V ==> LED+
GND ==> LED-
Arduino ==> Gas sensor

GND ==> GND
5V ==> Vcc
Analog0 ==> A0
Arduino ==> ESP8266

D10 ==> Tx
D11 ==> Rx



