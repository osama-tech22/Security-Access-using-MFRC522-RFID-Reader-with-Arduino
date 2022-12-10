# Security-Access-using-MFRC522-RFID-Reader-with-Arduino
An RFID tag is an identification system that uses small radio frequency identification devices for identification and tracking. An RFID tag system includes the tag itself, a reading/writing device, and a host system application to collect, process, and transmit data.
### Materials you will need to do the project.
* ##### Arduino Board       
* ##### RFID RC522 Module
* ##### LED Kit
* ##### Buzzer
* ##### F to F Jumper
* ##### M to M Jumper
### Steps : 1
* ##### MFRC522 Wiring Diagram : 
PinWiring to Arduino Uno

SDA------------------------Digital 10

SCK------------------------Digital 13

MOSI----------------------Digital 11

MISO----------------------Digital 12

IRQ------------------------unconnected

GND-----------------------GND

RST------------------------Digital 9

3.3V------------------------3.3V (DO NOT CONNECT TO 5V) 

![Mifare_bb](https://user-images.githubusercontent.com/113222717/206814093-11b310ea-296f-4a73-9f68-bd86cb4f59fa.png)
### Steps : 2
1. Download the RFID libaray the file is attached as RIFD.zip
2. Unzip the RFID library
3. Install the RFID library in your Arduino IDE
4. Restart your Arduino IDE
### Steps : 3
After having the circuit ready, go to File > Examples > MFRC522 > DumpInfo and upload the code. This code will be available in Arduino IDE (after installing the RFID library).

Then, open the serial monitor. write down your UID cards we will need it for later. 
### Steps : 4
Upload the code used. 
* ###### Note :You need to change the if (content.substring(1) == “REPLACE WITH YOUR UID”) and type the UID card you’ve written previously.
* ###### Also, you can change the message or the sound of the buzzer or the delay time for light. 



### links to Documention and Videos

* ##### [Security Access Using RFID Reader](https://create.arduino.cc/projecthub/Aritro/security-access-using-rfid-reader-f7c746)

* ##### [  How to Make Arduino Security Access Lock | RFID MFRC522 ](https://youtu.be/3uWz7Xmr55c)


