## Java I Lab 04

Speed Of Sound

**Date assigned:** 

**Program due:**

**Points:** 

**This is an individual assignment.**

**Goals:**

1.  Use the various if statements that exist

2.  Make sure that code is readable by using well named constants, variables, and proper nesting

**Lab 4**

The speed of sound traveling through a gas medium depends on the density of the medium. 
The less dense the medium, the faster the speed of the sound travels. 
The following table shows the speed of sound at 0 degrees Celsius.

Speed of sound through a gas medium at 0 degrees Celsius


<pre>
Medium                          Speed (Meters/Second)
Carbon Dioxide                  258.0
Air                             331.5
Helium                          972.0
Hydrogen                        1,270.0
</pre>

Write a program that displays a menu allowing the user the ability to select one of the four gases. 
The program is to ask the user to enter the time it took (in seconds) for the sound to travel 
from the source to the detection location. The program is to report how far away (in meters) 
the source of the sound is from the detection location.

1. Check to make sure the user has selected a valid menu choice. 
If an invalid choice is entered, output the message "Illegal Menu Choice" and terminate the program.

2. Optional Challenge: Do not accept any input times less than 0 or more than 60 seconds.

Here is how your program is to work:

<pre>
Speed of Sound in Gas

    Medium - Speed (m/s)
------------------------
[1] Carbon Dioxide - 258.00
[2] Air - 331.50
[3] Helium - 972.00
[4] Hydrogen - 1270.00

Enter number corresponding to medium: 2

Enter seconds sound travelled: 20

Distance of Sound from Detection Device: 6630.00 meters
</pre>

<pre>
Speed of Sound in Gas

    Medium - Speed (m/s)
------------------------
[1] Carbon Dioxide - 258.00
[2] Air - 331.50
[3] Helium - 972.00
[4] Hydrogen - 1270.00

Enter number corresponding to medium: 6

Illegal Menu Choice
</pre>

1.	Research how to output the values to 2 decimal places.

**To complete this assignment you must submit the following:**

1.  **An electronic Solution of your program on GitHub**

    a.  You are to click on the Lab04 link to accept this
        assignment as we've done before. Once accepted, code up a
        complete solution to each project specified above. Your
        complete solution is to be pushed to GitHub no later than the
        date and time specified above for your specific section. I will
        only grade your solution from the proper location on GitHub.

    b.  Pay attention to the example output above. Your program's output
        must look **exactly** like the example output! The spacing and
        newlines in your output must match exactly.

    c.  Make sure that your program compiles and runs correctly with no
        errors and no warnings. If you get any errors, double check that
        you typed everything correctly. Be aware that C++ is
        case-sensitive.

2.  **An electronic pdf (punetidLab04SpeedOfSound.pdf) 
of your program is to be emailed to ryandj@pacificu.edu**
