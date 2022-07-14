I used STM32F103c8t6 a.k.a Blue Pill for getting the analog value.
And also i connected a 10k resistor serial to the NTC. Then i did voltage division and get the adc value from that point.
After that we process that analog value and turning it to the Celcius value with the help of a Temprature function.
( NOTE: With another microcontroller you may not have the same and correct value as the circuit needs a 3.3V supply voltage which Blue Pill provides. )

---------------Process Finished---------------
Simply send the data with UART module. I used Poll method.
You can use the other methods aswell which is better. But i just made it simple.

---------------Sending Over---------------
