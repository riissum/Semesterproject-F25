# Semesterproject-F25
Semesterproject 1 - Software and robots 

##Using wiringPi
Installering: Git clone git@github.com:WiringPi/WiringPi.git

Check GPIO layout på https://pinout.xyz/pinout/wiringpi

NOTE: To compile programs with wiringPi, you need to add:
    -lwiringPi
  to your compile line(s) To use the Gertboard, MaxDetect, etc.
  code (the devLib), you need to also add:
    -lwiringPiDev
  to your compile line(s).
  
Compile: g++ -o <navn på program output> <navnPåCppFil.cpp> -lwiringPi


