# Oric Diagnostics
This is a reproduction of Mike Brown's Oric Diagnostic board and loopback harnesses, see [Mike Brown's Diagnostic ROM and PCB](https://oric.signal11.org.uk/html/diagrom.htm)

>[!NOTE]
>Acknowledgements go to Mike Brown for posting the original design to his excellent website [Oric And Atmos Support](https://oric.signal11.org.uk/index.htm). Many Thanks.

<img src="https://github.com/user-attachments/assets/d1dbd898-2688-4ffc-b7ec-fb37d1c7c7c3" width="700">

>[!CAUTION]
>USE AT YOUR OWN RISK.
>There is always the risk that the Oric Diagnostic board could cause harm to your Oric. Although I have tested the Oric Diagnostic board, there is no guarantee that it
>will work properly under all circumstances.

# Repository Content
This repository contains the Kicad and gerber files associated with the Diagnostic board and loopback harnesses.

# Changes from Mike Brown's Original Design
The following changes have been made when compared with Mike Brown's Original Design:

* The clock circuit has been replaced by [ECS-100AX-010](https://www.digikey.co.uk/en/products/detail/ecs-inc/ECS-100AX-010/827230)

* The LED resistors have been replaced with 220ohm values.

* 3M holes have been added to allow for standoffs to be fitted.

For all other information about Mike Brown's original design please refer to [Mike Brown's website](https://oric.signal11.org.uk/html/diagrom.htm)

# Ribbon Cable
The Oric Diagnostic board has been designed to be used with a 34 way ribbon cable and can be used partly when the Oric motherboard is still in the case, altough it is a bit diffult to get to the NMI button underneath.

<img src="https://github.com/user-attachments/assets/fcc7f0ca-b3a3-4e3b-8d8a-00407bc48600" width="500">

However for the most part it will probably be used when the Oric motherboard has been removed from the case, but remember the motherboard is normally upside down and hence the twist in the ribbon cable when used in this configuration.

<img src="https://github.com/user-attachments/assets/633542f1-dc84-4e4b-abd3-7c63b52d13c1" width="500">

Note the orientation of the ribbon connectors and red cable align to pin 1.

<img src="https://github.com/user-attachments/assets/7d9fac18-6bba-4eee-b2e0-cdba2e7ed44a" width="500">

# Port A Loopback
The Port A loopback is designed to fit straight into the Oric printer port.

<img src="https://github.com/user-attachments/assets/c4c70989-c5b5-4ce6-961c-18877d0efc25" width="300">

>[!TIP]
>I found it difficult to remove the Port A Loopback when required. In the end I placed a pin header on the wrong side and connected using a ribbon cable.

# Keyboard Loopback
The Keyboard loopback is design to fit over the end 10 pins.

<img src="https://github.com/user-attachments/assets/4d38d124-1e45-4ed7-8824-667dff0b2661" width="300">








