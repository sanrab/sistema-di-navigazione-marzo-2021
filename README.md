# sistema-di-navigazione-marzo-2021
sistema di navigazione marzo 2021

HARDWARE

IMU9255, Raymarine ST60+ Wind,Raymarine ST60+ Tridata, Raymarine GPS 125, autopilota Raymarine ST6001+
Interfaccia SeaTalk-NMEA USB bridge, dAISy

Raspberry 3B con openplotter, Access Point con SSID openplotter
legge dati Seatalk (GPS, Wind, Depth tramite convertitore Seatalk-USB), AIS (dAISy su USB), IMU9255
da SignalK pypilot e li passa su SignalK

RaspberryPi ZeroW con IMU9255 e pypilot
legge dati pitch, roll, heading
si collega all'Access Point con SSID openplotter e manda dati SignalK

PC con opencpn. Si collega all'Access Point openplotter.
Legge dati SignalK (GPS, Wind, Depth, pitch, roll, heading, AIS)

Raspberry ZeroW, SignalK --> Raspberry 3, SignalK --> PC opencpn

