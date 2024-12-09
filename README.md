# ESP32_FrequencyOscilator_Botons

-----------------------
Feqüencimetre  i oscilador (1Hz - 40MHz) basat en ESP32 (CAT)

Es tracta d'una adaptació del projecte original creat per Gustavo Murta:

https://blog.eletrogate.com/esp32-frequencimetro-de-precisao
https://www.esp32.com/viewtopic.php?f=19&t=17018

a partir de la darrera acutualitazció de juliol del 2024:

https://github.com/Gustavomurta/ESP32_frequencyMeter/tree/master/ESP32_Frequency_Meter_2024

En aquesta versió s'ha eliminat la part o es defineix, per consola, la freqüencia del oscilador i s'ha substituit aquest per un control mitjançant pulsadors. 

En el cirtuuit original caldrà efegir-hi 4 pulsadors que tenen les funcions següents:

•	GPIO 19 - Incrementa la freqüencia n pasos

•	GPIO 18 - Decrementa la freqüencia n pasos
	
•	GPIO 17 - Defineix n (apasos). Pulsant seqüencialment obtindrem pasos: 
	1 Hz → 10 Hz → 100 Hz → 1 kHz → 10 kHz → 100 kHz → 1 MHz → 10 MHz → 1 Hz
	
•	GPIO 16 - commuta la visualització entre la freqüencia de la senyal d'entrada (GPIO 34) o la freqüencia de la senyal generada (GPIO 33).

-----------------------
Frequency meter and oscillator (1 Hz - 40 MHz) based on ESP32 (ENG)

This is an adaptation of the original project created by Gustavo Murta:
	•	https://blog.eletrogate.com/esp32-frequencimetro-de-precisao
	•	https://www.esp32.com/viewtopic.php?f=19&t=17018

based on the latest update from July 2024:

https://github.com/Gustavomurta/ESP32_frequencyMeter/tree/master/ESP32_Frequency_Meter_2024

In this version, the functionality to define the oscillator frequency via the console has been removed and replaced with control via push buttons.

In the original circuit, 4 push buttons will need to be added with the following functions:
•	GPIO 19 - Increases the frequency by n steps

•	GPIO 18 - Decreases the frequency by n steps

•	GPIO 17 - Defines n (steps). Pressing sequentially will give the following steps:
	1 Hz → 10 Hz → 100 Hz → 1 kHz → 10 kHz → 100 kHz → 1 MHz → 10 MHz → 1 Hz

•	GPIO 16 - Toggles the display between the input signal frequency (GPIO 34) and the generated signal frequency (GPIO 33).
