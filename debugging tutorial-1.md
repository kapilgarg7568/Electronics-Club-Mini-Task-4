# Debuggging Tutorial for Project "Advanced Irrigation System"
Check out this link for complete project description:
[ Advanced Irrigation System ](https://github.com/kapilgarg7568/Electronics-Club-Mini-Task-2/blob/master/Advanced%20Irrigation%20System.md)
 
**Pipeline for Project:**

`Temp.,Humidity and Soil Moisture sensor`=>Input for `Microcontroller`(Analyse the input signal)=>give command to `Relay`=>`Water Pump` 
=>`Irrigation to plants.`

dispaly the data recieved from differnt sensors <=`Microcontroller`=>Send Updates and Recieve messages

so if your project is not working problem must be in the any one element of the above pipeline

but before going into the pipeline check some basic things which will help you debigging your circuit
- check if all modules light up and getting right power supply just by checking voltage at different points and the modules which doesnt glow have bben shorted and we need to purchase a new one.
- check whether any devices is getting heated up and if ans is yes then its a bad news, you might have burnt it check out resource section to buy a new one.

lets dive into the debugging of each element seperately.

**DHT11 Troubleshooting**
if you are geeting an error message while reading the temp and humidity from the sensor folllow these steps. It might help you to get you back on track.

- First you need to check the wiring or pin assigment to see that your cicrcuit is properly connected and for that you can check the datasheet. and if everything is allright and still you are unable to find whats the problem, go on to next tips.
- The DHT11 sensor has a working voltage of 3V to 5.5V so if you are powering the sensor from a 3.3V pin. in some cases powering the DHT wit 5V solves the problem.
- and still you are not able to isolate the problem then its possible that problem is with your sensor so go get a new sensor.



