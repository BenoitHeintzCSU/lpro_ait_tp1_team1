

Authors: Hager François
         Herpsont Horrillo Tristan
Date: 20/03/2019 14:52;


## Preview :
This procedure is used to mount the Octopus 9DOF module on a test bench using an EMG30 motor.

### -Preparation :
To mount the Octopus 9DOF module you must prepare the following equipements:

- Arduino with usb cable 

 - Motor mounted as specified in the Motor_assembly procedure
        
 - Green support: 

    <img src=https://user-images.githubusercontent.com/47211503/54690212-306d8a80-4b21-11e9-9574-fd97442ffcf2.jpg width ="100px"/>

 - Octopus 9DOF module 

 - 4 tie wrap
 - connector for the Octopus 9DOF module :

 <img src=https://user-images.githubusercontent.com/47211503/54690742-56dff580-4b22-11e9-8ec1-b5f98493679d.jpg width ="100px"/>



## I. 
#### Please refer to the motor_assembly procedure for the first part of the mounting (mounting of the motor on the blue support and the green support on the motor shaft)


## II
#### Mounting of the Octopus 9DOF module on the green support:
- place the Octopus 9DOF module on the green support: 
<img src=https://user-images.githubusercontent.com/47211503/54693661-4b42fd80-4b27-11e9-906f-609b21ee4b41.jpg width ="500px"/>
- Fasten the Octopus 9DOF module with the 4 tie wrap on the green module ( 1 tie wrpa per hole)

<img src=https://user-images.githubusercontent.com/47211503/54693823-8c3b1200-4b27-11e9-8d53-f79516d58d0e.jpg width ="500px"/>

- plug the connector in the Octopus 9DOF module (black->G ; White->V ; Grey->SD ; Purlple->SC )

<img src=https://user-images.githubusercontent.com/47211503/54694176-184d3980-4b28-11e9-9a24-f84f26626dff.jpg width ="500px"/>

- plug the extremity of the purple wire on the SCL connector of the arduino and the grey one in the SDA connector

<img src=https://user-images.githubusercontent.com/47211503/54696639-7845df00-4b2c-11e9-8b36-a628adc60e78.jpg width ="500px"/>

- plug the extremity of the black wire in the GND connector of the motor driver and the with one in the VIN

<img src=https://user-images.githubusercontent.com/47211503/54696633-74b25800-4b2c-11e9-80ec-9efbb0983c98.jpg width ="500px"/>


## III
#### How to use the Octopus 9DOF module

- Download the CODE from the source file hmc5883L ( at the bottom of the page Ressources->9DOF Module CODE)

- Open arduino IDE, create a new folder and paste the code

- Upload the code to the arduinno 
