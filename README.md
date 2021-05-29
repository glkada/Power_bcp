# Power_bcp
Power back up for routers 12V@2A.

Alot of people are facing sudden power cuts these days which ruins the flow of work from home.
Thus I have developed a power back up board that is able to switch from Vext to Vbat with almost 0ms delay and thus preventing from sudden power loss to the router.
The battries are being charged at 8.2V 600mA. This can be changed by simply tweaking Rprog resistor however it is a linear charger i.e in worst case it will dissipate 9 - 6 * Ichg, so you need to be very careful with this and either increase the thickness of the copper being use or increase the area of the copper under the IC for better heat dissipation.

The battries used are Li-ion 3200 mAh thus to avoid all sorts of risks I have kept the voltage low.
The estimated running time is 3-4 hours majorly depending on the routers model. 

*Please note author is not responsible for any damages incurred due to the above design. Please use it with caution.*
Thanks! Happy Hacking!
