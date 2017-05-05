### 1. Describe goals of project briefly
I want to explore a new way of humidification and make it more interesting. People can manipulate the whale and humidify where they want.
- Original proposal: ![](images/plan.jpg)
 
### 2. Describe how, from a technical point of view, your choice of hardware and software achieves that goal
#### For hardware
The whale humidifier has two working systems.
The first is for walking. I use the Bluetooth accessories, it can be wirelessly connected to the user interface on the phone. People can be more free to control the vehicle and humidification system. I used two DC motors to drive the vehicle and change the direction of the vehicle by controlling the motor rotation. The two caster around the vehicle helps to support the vehicle and keep the balance.

The second system is used for humidification. I would like to use the way to replace the traditional fan for humidification, because in such a way, the spray of water mist is assembled rather than linear, which gives the user a different experience. In order to achieve this function, I tried a lot of ways. Eventually I chose to use the Servo motor to drive the entire shell up and down to achieve the final results. In this way, the fog stored in the bag is quickly extruded by squeezing the plastic bag connecting the housing and the water tank to achieve the fog effect. I also made a plasitc shell by vacuum forming. Due to light weight of plastic shell and bag, the Servo works pretty effective and the result looks great.
 
#### For software
the most troublesome part of the Bluetooth installation and connection. I learned the tutorial on the computer and installed the Bluetooth device on the vehicle. I have defined the Bluetooth control panel buttons to control the movement of the entire vehicle. For example, pressing 1 control the Servo motor up and down a specific angle to humidify; pressing the left button will let the left of the DC motor to stop turning and the vehicle turn left. In order to control the DC motor I learned and used H-Brige. It allows the DC motor to rotate forward, reverse or stop, which gives me a good control over the direction of the vehicle.
 
### 3. Accurate schematic
 ![](images/whale-humidifer_schematic.jpg)
 
### 4. Parts list (major or unique parts, not LEDs, wire, etc.)
#### General:
Arduino Uno X1

Adafruit Bluefruit LE UART Friend X1

9v battery X4

#### Driving System:
H-brige X1

DC Motor X2

Caster X2

#### Humidification:
Servo Motor X1

AGPtek Aluminum Mini Mist Maker 24V X1

Watercontainer X1

Plastic shell of whale shape X1

Plastic Connector(Connect Watercontainer and shell) X1

#### 4. A few pictures of overall project plus some close ups of the electronics and any mechanism (cellphone is fine)
- Circuit under the vehicle: ![](images/IMG_2513.JPG)

- shell was lifted and put down: ![](images/IMG_2519.JPG)
 ![](images/IMG_2520.JPG)

- clear view of lifted shell: ![](images/IMG_2521.JPG)

- Back view and bottom view: ![](images/IMG_2523.JPG)
 ![](images/IMG_2522.JPG)

- ring to fix the water container: ![](images/IMG_2524.JPG)

- lifting system experiment: ![](images/IMG_2072.JPG)

- Useing screws to fix wheels make the structure more reliable: ![](images/IMG_2304.JPG)

- Experiments: How structures influence shapes of Mist: ![](images/test1.jpg)
 ![](images/test2.jpg)
 ![](images/test33.jpg)
 ![](images/test4.jpg)

5. A short video (cellphone is fine) of the operational project

6. [Code](https://github.com/danqian/homework1/blob/master/finalProject/code_finalproject)

