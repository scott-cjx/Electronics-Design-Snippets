# Universal Serial Device

The USB port is one of the most common IO port found on electronic devices (but not all). 


## Purpose

The USB port is provides 2 devices to exchange:

- Power
- Data (Serial, Differential Pair)

\* note: USB cables can be the limiting factor where they might not have the same internal wires to support the maximum capability the port can provide. (ie. USB power only wires)


### Types of USB

There are quite a number of different USB ports.

- USB A
- USB B
- USB Mini
- USB Micro
- USB C

> Personal opinion: for the love of god, please use the latest: USB C. It is not that hard to work with + its not THAT much more expensive.


### USB Standards

I will only focus on the slower (and older) standards as it is the only ones that matter in this juncture. Some embedded devices (microcontroller/microprocessors) have an on-board USB "driver" that allows direct hookup from the chip to the port (without an external IC) to communicate with another device via USB.

|Standard|AKA|
|:--|:--|
|USB 1.1|USB Full-Speed (FS)|
|USB 2.0|USB High-Speed (HS)|

For more information on USB connectivity types and standards, you can refer to [Tripp Lite's USB Connectivity Types & Standards](https://tripplite.eaton.com/products/usb-connectivity-types-standards).


#### Disclaimer

Do note that there is a difference between the USB port and the USB standard. 

|USB Port|USB Standard|
|---|---|
|physical connector and its form factor|protocol and capabilities of data transfer and power delivery|

