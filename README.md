# LED Flip Circuit

A circuit where pressing a switch alternates which LED is powered 
when one turns on, the other turns off.

to accses the demo you can by going to this link

https://falstad.com/circuit/circuitjs.html?ctz=DwYwlgTgBAZgvAIgIwKgFwM6IAwDpsEECsqYIiSeATAVQOx0DM2AHFQGwCcndqIARoiLZUAB0EJhqAG4QhqALaYhAUwC0SFAD4AUFCjAASlAAeiACyd2UKixZRGLczbup4ydqgDu7kVAUAhibS8gD0uvrA0GaS7Ng2dFRQRHE2rG44qHLIhAjhegbRQqnMzinxjuYZCH7ZlAR5EQYAMgCiACKmxfE09uzmPemwmf4A9ogAJiowAQCuADZoavMqE3x1fADmIwIjCvzkNfgo+ZFtnTHlDk5Q7CnXVcM1iuMIUzMLSytrUCAbv9tnr8JH59oc8NgTk1QF1JEgkkhUldetU-OD8IQUFAwCEjgQsRhsn5pBNEBpcOwGHQWMxHFROFQkNxeKcDCBYVdKslbFBzIjUXwcBj8aRcRDIahCSMSRQMXFsAymSwUv02I0CsBNrD+oM+ok0iwBazNRz4VBEfFLNYkOZHr51ZEtZceXzrEQzeZGFQjdCnYg7tYuew7A8fRqAMqwq0uezI1xPPzzMAjNAAC0Q3vywFC4AguiAA

## Demo

<img width="800" height="629" alt="CleanShot 2026-05-29 at 18 03 34" src="https://github.com/user-attachments/assets/54fe754a-d47c-402d-8b55-d7082e42741f" />



## How it works

The circuit uses two parallel branches each with a 1k resistor and a 10µF 
capacitor connected to an LED When the switch sends power to one branch, 
that capacitor discharges and allows current to flow lighting up that LED
The other branch's capacitor charges up and blocks current keeping that LED 
off Flipping the switch reverses this toggling which LED is on.
