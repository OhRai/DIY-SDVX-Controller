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
<img src="https://user-images.githubusercontent.com/67884995/209010287-5e8af069-4eb6-468d-ba16-f87a26ca8a9a.JPG" width=50% height=50%>

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
![image](https://lh3.googleusercontent.com/4mWgoHU3GAIZE5_lP4-tqn-n9VBtu7POByutxR-ZrM5z3CkwY8wKOft_iIw6PdnJSlwc80x_jjqEWEKiu3mDoHywBm8UPytiEsZP5NsKSYn3U6nC0PoxgkFxhybnJMhHD9r5wBe7Kad7_kohX7Zn_XNDIbx-OfhqapwZ6sa4MPn7S3QwXbq_sT3f5VPS8TSEWdZ2OBSsI6LZtfMs0-Grb67bgpWnSppOaqhsZO2_KdZmQd5613MQ5nkR641Y4Cqo1Fkulh5rgMVzCcVj4VVy7raBlVW2mK8S4XjmOEKE46dSUD0kHR1-w7BjbmmuuXpFlbW5MZD96k5VwwS206hxz7IMH_xiAQB6P3mNTq14SnQrfvQ6GBS5PNHOtjpFdOdl0wjDYww1uwMktWk7VSUueBWvt4plwZISjkFrHtFbEhy6M7JaRiWWFRhu8xiNdeLOr0capY5bVrISXoHsU-pLEVJ9puoAGPo2YmeFtl3VKYlc0M8G95-QCZBWlAyVFRhwdsISbD4djaWkg4ezeC4Dg7vgWlx_Yhk7ANkBygvXRQco1IeAFf4yNY2kxT4klf7UpdF7JKec9eChDAdy0ZTpKnJqfVgawRP3IMlOw17oJwM7f1OIBduY5ufANfy7tODCioNdjwveyzQPefvdZueknFJ9p4mpNd2cWCRyHWCwaq0hV_kl7naxplBSrVXKRMz5f9eN13GiAmYWqqIiLnPmyykwr3Wn1VhYyXPHdaP0c2IdWK067IIIdRdBb9Ouy9480FF_PieX97HsHjcH22HdQL1af7K6tgNheLY49JD3_bLGjRTZ1_00mxfU-4qHt3VQyyM9cqQdhJqIKx-PrTli-jARItuxiitduI9sUKyBh1qUc1ltavzNr02JJGCfQJNW5QGFFp97fEhVTNzpUHM4-rRAXJ_3foxjY44OvYH6I2i-Yg=w1355-h869-no?authuser=0)

### **Firmware**
The firmware for the controller has already been released by [speedypotato](https://github.com/speedypotato) and available to [download here](https://github.com/speedypotato/Pocket-SDVX).
