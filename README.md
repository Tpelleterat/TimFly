# TimFly
## Flight Controller DIY.

This system is composed by 3 applications:

* The Controller (Arduino): Manage motors control and drone stabilization.
    * https://github.com/Tpelleterat/TimFlyController
* The Brain (Raspberry Pi): Expose network connection and communicate with controller for send movements orders.
    * https://github.com/Tpelleterat/TimFlyBrain
* The Mobile App (Cross-platform): Connect to the Brain network and send movements orders.
    * https://github.com/Tpelleterat/TimFlyMobile