# UPS for Router
Power back up for routers 12V@2A.

Alot of people are facing sudden power cuts these days which ruins the flow of work from home.
Thus I have developed a power back up board that is able to switch from Vext to Vbat with almost 0ms delay and thus preventing from sudden power loss to the router.
The battries are being charged at 8.2V 600mA. This can be changed by simply tweaking Rprog resistor however it is a linear charger i.e in worst case it will dissipate 9 - 6 * Ichg, so you need to be very careful with this and either increase the thickness of the copper being use or increase the area of the copper under the IC for better heat dissipation.

![Top Layer](https://user-images.githubusercontent.com/36476534/120070263-3ff4a080-c0a7-11eb-8ecc-7f9a77545249.png) ![Final PCB](https://user-images.githubusercontent.com/36476534/120070273-471bae80-c0a7-11eb-8008-2d5029286c3d.jpeg)



The battries used are Li-ion 3200 mAh thus to avoid all sorts of risks I have kept the voltage low.
The estimated running time is 3-4 hours majorly depending on the routers model. 

The Rev2.0 was a successful prototype and few of my friends and family memebers asked me to make a few more copies of the same but due to the global shortfall of semiconductors I couldn't get hands on the step up IC thus replicating wasn't possible. This is where I decided to resdesign the board with a new step up IC and covering all the various designing errors present. 
Thus the PCB Rev 3.0 has alot of edits. Also I haven't yet sent the board to the FAB house so beware.

![Top Layer](https://user-images.githubusercontent.com/36476534/120070301-6581aa00-c0a7-11eb-9ad6-cddf9be4b972.png) ![3D Top Layer](https://user-images.githubusercontent.com/36476534/120070307-6e727b80-c0a7-11eb-84e7-572ea183204a.png)



*Please note author is not responsible for any damages incurred due to the above design. Please use it with caution.*
Thanks! Happy Hacking!
