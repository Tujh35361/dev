MaslowCNC Notes
===

2017-11-03
---

* Kit is unavailable, so trying to source materials ourselves.

### Electronics

* Ordered a few different options for motors.
In general, this is a 12V DC high torque worm geared motor with encoder.
The gearing ratio, RPM and stall amperage are all factors that I don't have
a good handle on.  They need to be driven by the L298 H-bridge chip.
  - [L298](https://raw.githubusercontent.com/abetusk/dev/projects/maslowcnc/doc/L298_H_Bridge.pdf) has a limit of 4A
  - [MaslowCNC Mechanics BOM](https://github.com/MaslowCNC/Mechanics/blob/master/BOM.txt) states a 291:1 reduction, 30kg/cm torque, 20 RPM and 12V
  - Ordered four GW4058-31ZY [from AliExpress](https://www.aliexpress.com/item/GW4058-31ZY-DC-worm-gear-motor-With-Magnetic-Bipolar-hall-encoder-CW-CCW/32829395257.html) of the 12V 280:1 variety. I can't make out what the specs are but it looks like it's 0.6-2.3A, 32-70 Kg/cm torque and 11-28 RPM.  They were about $35 each with shipping.
  - Ordered three 10RPM and two 20RPM motors from [Ebay](https://www.ebay.com/itm/DC-12V-Reversible-High-Torque-Turbo-Worm-Geared-Motor-Encoder-10-20-30-40-100RPM/182326886308).  The claim is 22.5-25 Kg/cm and 12-25 Kg/cm torque respectively so we'll see if this is a viable option.  Cost was about $12 per motor.
* Ordered [MaslowCNC's Arduino 2560 motor shield](http://www.maslowcnc.com/store/arduino-shield) which has the L298 chips on them to drive the motors.  Cost was about $30.
* Ordered two Arduino 2560 clones, the Elegoo MEGA 2560 R3 board ATMega2560 ATMEGA16U2 + USB, from [Amazon](https://www.amazon.com/Elegoo-Board-ATmega2560-ATMEGA16U2-Arduino/dp/B01H4ZLZLQ/ref=sr_1_1) (I ordered the black one).  Cost was about $16 each.

#### GW4058-31ZY

![GW4058-31ZY Photo](https://raw.githubusercontent.com/abetusk/dev/projects/maslowcnc/img/GW4058-31ZY_photo.png)

![GW4058-31ZY CAD](https://raw.githubusercontent.com/abetusk/dev/projects/maslowcnc/img/GW4058-31ZY_cad.png)

![GW4058-31ZY Spec](https://raw.githubusercontent.com/abetusk/dev/projects/maslowcnc/img/GW4058-31ZY_spec.png)

![GW4058-31ZY Pinout](https://raw.githubusercontent.com/abetusk/dev/projects/maslowcnc/img/GW4058-31ZY_pinout.png)

[AliExpress link](https://www.aliexpress.com/item/GW4058-31ZY-DC-worm-gear-motor-With-Magnetic-Bipolar-hall-encoder-CW-CCW/32829395257.html)

#### Ebay 12V Reversible High Torque Turbo Worm Geared Motor Encoder 10/20/30/40/100RPM

![ebay-12v-hitorque-worm-encoder photo](https://raw.githubusercontent.com/abetusk/dev/projects/maslowcnc/img/ebay-12v-hitorque-worm-encoder_photo.png)

![ebay-12v-hitorque-worm-encoder spec](https://raw.githubusercontent.com/abetusk/dev/projects/maslowcnc/img/ebay-12v-hitorque-worm-encoder_spec.png)

[Ebay link](https://www.ebay.com/itm/DC-12V-Reversible-High-Torque-Turbo-Worm-Geared-Motor-Encoder-10-20-30-40-100RPM/182326886308)


### Hardware

* Ordered two Diablo 1/4 in. Up Spiral Router Bits from [Home Depot](https://www.homedepot.com/p/Diablo-1-4-in-Up-Spiral-Router-Bit-DR75101/204073552).  Cost was about $20 each.


