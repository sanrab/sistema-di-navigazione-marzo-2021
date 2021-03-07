# sistema-di-navigazione-marzo-2021
sistema di navigazione marzo 2021

Raspberry 3 con openplotter, Access Point con SSID openplotter
legge dati Seatalk (GPS, Wind, Depth tramite convertitore Seatalk-USB), AIS (dAISy su USB), IMU9255
da SignalK pypilot e li passa su SignalK

RaspberryPi ZeroW con IMU9255 e pypilot
legge dati pitch, roll, heading
si collega all'Access Point con SSID openplotter e manda dati SignalK

PC con opencpn. Si collega all'Access Point openplotter.
Legge dati SignalK (GPS, Wind, Depth, pitch, roll, heading, AIS)
