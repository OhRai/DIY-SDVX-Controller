# **DIY Pocket SDVX Controller**

### **Introduction**
Sound Voltex is a popular Japanese arcade rhythm game, where you have 6 keys to press with two volume knobs as your inputs. As hard as it may be to play the game, it is very fun and enjoyed amongst many in the world. However, finding Sound Voltex arcade machines are nearly impossible to find in countries such as Canada and America. This can be fixed by purchasing a controller that is almost identical to the arcade machine, or making your own. These can be very pricy however, which is why I decided to create my own controller for around $30 CAD. 

### **Planning**
Before making this controller, I had to first gather all the parts I needed to assemble this controller.

Parts that were used: 
* Arduino Pro Micro
* 3D-Printed Case and Cover
* 3D-Printed Keycaps (1x1u keycap // 4x1.25u keycaps // 2x1.5u keycaps)
* Rotary Encoders x2
* Aluminum Hi-fi Knobs x2
* Gateron Switches x6
* Wires 
* Male Micro-USB to Female USB-C Adapter
* USB-C Cable
* M3x5 Screw
* Vinyl Skin 

### **Assembly**
To assemble the controller, I had to use a glue gun to keep the key switches in place, so when I solder and put on the keycaps, they won't fall out. Other than that, the rest is very simple and it is a matter of just soldering all the pins to the Arduino in the correct order. 

<img src="https://user-images.githubusercontent.com/67884995/209010251-299becfc-a177-4252-89fb-69118dcc3332.JPG" width=50% height=50%>
<img src="https://user-images.githubusercontent.com/67884995/209010268-9bb19102-c0b7-449e-a7d3-1e7b8c0740ab.JPG" width=50% height=50%>

Pinout: 
![image](https://user-images.githubusercontent.com/67884995/174512733-320b3090-c7c9-4b96-a728-2ff57a1596a4.png)

* RXI - VOL_R A
* TXO - VOL_R B
* 2 - VOL-L A
* 3 - VOL-L B 
* 4 - BT_ST
* 5 - BT_A
* 6 - BT_B
* 7 - BT_C
* 8 - BT_D
* 9 - FX_L
* 10 - FX_R

After everything is glued in and soldered, I put on the vinyl skin that was printed so the controller would look nice. With this being added, I can now put on the rest of the parts, which include the keycaps and the volume knobs. To finish, I put in the Micro-USB to USB-C adapter in and the controller is now complete. 
<img src="https://user-images.githubusercontent.com/67884995/209010287-5e8af069-4eb6-468d-ba16-f87a26ca8a9a.JPG" width=50% height=50%>

### **Firmware**
The firmware for the controller has already been released by [speedypotato](https://github.com/speedypotato) and available to [download here](https://github.com/speedypotato/Pocket-SDVX).
