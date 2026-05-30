# week-1-hardware-resolution

# flip flip


# LED Flip Circuit

[Preface] I am  building an LED flip circuit because I wanted to make 
something where pressing a switch alternates which LED is powered  
when one turns on the other turns off

## May 26 - 

Today I worked on researching RC circuits and building the schematic in Falstad and searched for insperation to my circut to be based on.
the insperation i was talking about:
<img width="282" height="470" alt="image" src="https://github.com/user-attachments/assets/9c2c1889-45f2-4c63-ba8a-03bebc459166" />

The idea is to have two LED branches that alternate  when one LED is on 
the other is off I looked into how RC circuits work and found that capacitors  can control current flow with a delay which is what makes the alternating 
effect possible  Each branch has a 1k resistor to limit current to the LED and a 10µF capacitor that charges and lets off the power it charged 
which gives the LED the fading effect  When the switch sends power to one branch, that capacitor discharges and lets current flow lighting that LED

I ran into a few issues while building this in Falstad:
 **Wrong capacitor placement**
 I wired the capacitors incorrectly at first 
  which caused the circuit to not work as expected After consistent trail and error i managed to get it working
**LED polarity**
I placed one of the LEDs in the wrong direction becuased led are polarized meaning one side is negative and one side is positive which only let on way to worrk
 **Getting Falstad to work**
 had a lot of problems with getting falstad working and the interface was confusing at first but got it working after a couple of trail and error

 the final product:
 <img width="699" height="547" alt="Screenshot 2026-05-29 at 6 26 48 PM" src="https://github.com/user-attachments/assets/7e8e20d3-cdcb-4ffe-90ab-35af6ccb88cd" />


the insperation i had :
[Reddit thread](https://www.reddit.com/r/arduino/comments/1qwpiql/project_help_making_a_switch_of_some_sort_that/)

### Time Spent: 15 min
