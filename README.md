# RC522 Test
A simple program that allows you to receive characters of different lengths using UART. 
The code is based on the LL libraries from ST. In C.

The receiving buffer, after detecting the end of the transmission from the transmitter, is sent back to it. 
Interrupt termination detection is based on an idle interrupt generated by the UART module in the microcontroller