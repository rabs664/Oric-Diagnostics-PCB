# Oric Diagnostics
This is a reproduction of Mike Brown's Oric Diagnostic board and loopback harnesses, see [Mike Brown's Diagnostic ROM and PCB](https://oric.signal11.org.uk/html/diagrom.htm)

>[!NOTE]
>Acknowledgements go to Mike Brown for posting the original design to his website [Oric And Atmos Support](https://oric.signal11.org.uk/index.htm). Many Thanks.

![Diag board and Loopback PCBs](https://github.com/user-attachments/assets/d1dbd898-2688-4ffc-b7ec-fb37d1c7c7c3)

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
