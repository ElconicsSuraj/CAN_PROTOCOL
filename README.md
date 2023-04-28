# CAN_PROTOCOL

I have used CAN module and arduino Nano for this project
DHT22 is Connected with arduino nano 
DHT22 is measuring the tempreture and humidity passing the value to arduino nano and further to can bus
one arduino nano is working as master which is receiving the data 
this received data is passing through UART to ESP32
ESP32 is publishing the data to Cloud (ubidots)
