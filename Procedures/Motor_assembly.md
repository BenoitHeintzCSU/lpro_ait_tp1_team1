Authors: Hager François
         Herpsont Horrillo Tristan
Date: 07/03/2019 09:42;

Motor assembly procedure:

- First step:
    - How to mount the motor on the blue support:
        1. Prepare:
            - 3 screws( diamater 3mm)
            - the motor (EMG30 https://www.gotronic.fr/art-motoreducteur-encodeur-emg30-866.htm)
            - The pre-prepared support for the motor 
            - Image:
            
             <img src="https://user-images.githubusercontent.com/47211503/53944221-34c88b00-40bf-11e9-91ea-e04711a8d387.jpg" width="500px"/>
                       

        2. introduce the motor shaft into the big hole on the support as in the following
            Image:

             <img src="https://user-images.githubusercontent.com/47211503/53945231-735f4500-40c1-11e9-8225-456a34cd5692.jpg" width="500px"/>
        
        3. Then screw the motor to the support with a flat screwdriver:

             <img src="https://user-images.githubusercontent.com/47211503/53946732-a3f4ae00-40c4-11e9-84e8-dc79f56a1d49.jpg" width="500px"/>

            In the following holes:

             <img src="https://user-images.githubusercontent.com/47211503/53946782-bff84f80-40c4-11e9-9495-775080fd97b5.jpg" width="500px"/> 

          (the 3 prepared screw must be used)
- Second step:
    - How to connect the arduino and the motor
        1. Plug the red wire to the motor driver pin M1A and the black one in the motor driver pin M1B 

         <img src="https://user-images.githubusercontent.com/47211503/53949930-634c6300-40cb-11e9-903f-d686acf780a3.jpg" width="500px"/>

        2. Insert the motor driver into Arduino digital pins 6, 7, 8, 9, and 10 on one side and Arduino VIN, GND, GND, and 5V/VCC on the other. The upper-left corner of the shield partially blocks the Arduino’s 3.3V pin

         <img src="https://user-images.githubusercontent.com/47211503/53949928-62b3cc80-40cb-11e9-9b95-2d2cd852b8c8.jpg" width="500px"/>

        3. Plug the jumper on the motor driver between vout and the pin near Vout 

         <img src="https://user-images.githubusercontent.com/47211503/53949929-62b3cc80-40cb-11e9-969f-8e4f8f431c54.jpg" width="500px"/>

- Third step:
    - Mount the sensor support
        1. Use a philips screwdriver to swrew the screw in the holes of the sensor support

         <img src="https://user-images.githubusercontent.com/47211503/53949680-dacdc280-40ca-11e9-8e79-916f0524d36f.jpg" width="500px"/>

        2. insert the motor shaft in the big hole of the sensor support and then tighten by screwing the screw 

         <img src="https://user-images.githubusercontent.com/47211503/53949681-dacdc280-40ca-11e9-8458-975934fd2a9d.jpg" width="500px"/>



How to use the motor procedure: 

 - First step:
    1. Get form https://github.com/pololu/drv8835-motor-shield/releases/tag/2.0.0 the library 

    2. Open arduino IDE, create a new folder and add a library ".zip" select the .zip library downloaded previously 

    3. Then file -> exemple -> DRV8835MOTORSHIELD and compile.

    4. Connect the adruino to your computer and upload the programm to the arduino.
        (Be sure to select the right COM Port in the menu tools->port)

    5. Check if the motor is working. 

