#Veil

Veil is a tool designed to generate metasploit payloads that bypass common anti-virus solutions.

Veil was developed and is actively supported by @ChrisTruncer

Greetz & Thanks to @TheMightyShiv for your help and all others who have helped bear with my questions, gave advice, and more.  You all know what and how you've helped and how appreciative I am.


##Software Requirements:

1.  Python (developed for 2.7)
2.  Py2Exe
3.  PyCrypto (for Windows)


##Setup (tldr;)

Install Python 2.7, Py2Exe, and PyCrypto on a Windows computer.  

Directions: Take the three files generated by Veil and place them on your windows computer (if not there already).  Run the runme.bat file to create an executable form of your payload.


##Description
Veil was designed to run on Kali Linux, but should function on any system capable of executing python scripts.  Simply call Veil from the command line, and follow the menu to generate a payload.  Veil will create three files:

* payload.py - The payload file
* setup.py - Required file for Py2Exe
* runme.bat - Batch script for compiling the payload into a Windows executable

Move the three files generated by Veil onto your windows machine (place them in your python directory if python is not in the system path).  Run the runme.bat to generate an executable format of the payload file.

Now, move your payload.exe file onto your target system and don't get caught!
