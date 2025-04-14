# RFID_Triple_Reader_Completed
This code was designed with the intention of being a puzzle for an escape room!
This is a repository, both for showing off my work, and to aid others who may run into similar issues using the RC522 RFID readers, as it took a lot of searching and testing to find a solution.
The program is designed to read three Mifare 1KB RFID cards at the same time, with reaction to the cards removal from the sensor.

 - - -
Each of these files utilizes the "Arduino RFID Library for MFRC522" by Miguel Balboa:
https://github.com/miguelbalboa/rfid
Special mention goes to these links where I was able to find other examples to bring this code together:


 - - -
I'm relatively new to using Arduino, but I figured it couldn't hurt to add a little detail regarding the equipment I used!
The arduino I worked with throughout this whole process was an Arduino Nano 3.0
Like I stated before, this is specifically using the RFID-RC522 boards (my testing was utilizing two V2 boards and one V1 board).  The three cards are Mifare 1KB cards with a read-only UID.  
So to use this code, the first thing you'll have to do if figure out your card's UID and replace the ... (I should add some comments in the code to help with getting this code up and working for others).
