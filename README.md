﻿# HomeAutomationSystem
 Sensors Used:
- PIR (Passive Infrared Sensor)

![image](https://user-images.githubusercontent.com/80665616/235198045-37e079ed-8e06-480b-9dcb-6274febfa29c.png)

- LDR (Light Dependent Resistor)

![image](https://user-images.githubusercontent.com/80665616/235197912-08448fa7-1353-4219-aeb3-7fd0b7b5703c.png)

- TMP36 (Temperature Sensor)

![image](https://user-images.githubusercontent.com/80665616/235198105-8e4f0dc8-a067-48dc-995f-9bed86675cd6.png)


Processor Used:
- Arduino Uno R3

![image](https://user-images.githubusercontent.com/80665616/235198366-96050b7d-4cd8-430c-b38c-8b501d4984e4.png)


LCD Controller:
- Breadboard

![image](https://user-images.githubusercontent.com/80665616/235198656-564f2839-a962-4e5f-87ae-329ddaf2b345.png)

Functioning:
if(MOTION DETECTED) {

- Temperature HIGH && Light Intensity LOW: Bulb and Fan both are switched ON.
- Temperature LOW && Light Intensity HIGH: Only Fan is switched ON. 
- Temperature LOW && Light Intensity HIGH: Only Bulb is switched ON. 
- Temperature LOW && Light Intensity LOW: All appliances switched OFF.

} else {

- print (No MOTION DETECTED)

}

Output Screen - LCD 16x2

![image](https://user-images.githubusercontent.com/80665616/235198174-1512e568-4e9a-48ee-8201-ded0ac7aeb1b.png)

Output:
1) No Movement

![Output](https://user-images.githubusercontent.com/80665616/235196929-18313c0c-fab3-48ce-85ba-c67c5418424f.png)

2) When movement is detected the Bulb and Fan is turned ON.

![image](https://user-images.githubusercontent.com/80665616/235199772-37b1d490-5093-4d67-b023-847d73df68d3.png)


