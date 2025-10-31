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
This repository contains the KiCad and gerber files associated with the Diagnostic board and loopback harnesses.

# Changes from Mike Brown's Original Design
The following changes have been made from Mike Brown's Original Design:

* The clock circuit has been replaced by an [ECS-100AX-010](https://www.digikey.co.uk/en/products/detail/ecs-inc/ECS-100AX-010/827230) oscillator.

* The LED resistors have been replaced with 220ohm values.
>[!TIP]
>I still found the LEDs quite bright and you may consider increasing this value.

* LS components replaced with HCT.

* 3M holes have been added to allow for standoffs to be fitted.

For all other information about Mike Brown's original design please refer to [Mike Brown's website](https://oric.signal11.org.uk/html/diagrom.htm)

# Ribbon Cable
The Oric Diagnostic board has been designed to be used with a 34-way ribbon cable and can be used partly when the Oric motherboard is still in the case, altough it is a bit diffult to use the NMI button underneath.

<img src="https://github.com/user-attachments/assets/fcc7f0ca-b3a3-4e3b-8d8a-00407bc48600" width="500">

However for the most part it will probably be used when the Oric motherboard has been removed from the case, but remember the motherboard is normally upside down and hence the twist in the ribbon cable when used in this configuration.

<img src="https://github.com/user-attachments/assets/633542f1-dc84-4e4b-abd3-7c63b52d13c1" width="500">

>[!TIP]
>Note the orientation of the ribbon connectors and red cable aligned to pin 1 and check connectivity back to the Oric motherboard before use.

<img src="https://github.com/user-attachments/assets/7d9fac18-6bba-4eee-b2e0-cdba2e7ed44a" width="500">

# Port A Loopback
The Port A loopback is designed to fit straight into the Oric printer port.

<img src="https://github.com/user-attachments/assets/c4c70989-c5b5-4ce6-961c-18877d0efc25" width="300">

>[!TIP]
>I found it difficult to remove the Port A Loopback when required. In the end I placed a pin header on the wrong side of the PCB and connected using a ribbon cable.
>
><img src="https://github.com/user-attachments/assets/794acb3d-051e-4832-afe7-153e1509dc5f" width="300"> <img src="https://github.com/user-attachments/assets/294dc2cd-1320-4933-b067-a9a300e952f0" width="300">


# Keyboard Loopback
The Keyboard loopback is designed to fit over the end 10 pins.

<img src="https://github.com/user-attachments/assets/4d38d124-1e45-4ed7-8824-667dff0b2661" width="300">

>[!NOTE]
>I struggled to find pin headers that fitted. In the end I used these [pin headers](https://www.digikey.co.uk/en/products/detail/samtec-inc/SSA-110-S-T/1105806) but they are not a perfect fit.

# Casette Loopback
The Casette loopback is not part of this repository please refer to [Mike Brown's Diagnostic ROM and PCB page](https://oric.signal11.org.uk/html/diagrom.htm)

# 1MHz Clock
>[!NOTE]
>I have not had a need to use the clock source yet.

<img src="https://github.com/user-attachments/assets/792475f8-8011-4395-bc69-1fb56fbed303" width="500">

# ROM
Please refer to [Mike Brown's Diagnostic ROM and PCB page](https://oric.signal11.org.uk/html/diagrom.htm)

>[!NOTE]
>I used a 27C512 EPROM and and copied the 16K ROM image four times to fill the 64K EPROM.

# Jumpers
Please refer to [Mike Brown's Diagnostic ROM and PCB page](https://oric.signal11.org.uk/html/diagrom.htm)

>[!CAUTION]
>I have not tested the jumpers A14=0, A15=0, INHIBIT VIA and VIA SEL

# Testing
The Oric Diagnostic board has been tested on two Oric-1 computers. One Oric-1 passed all tests and the other failed on the Casette Input test (which was resolved by replacing the LM358 OpAmp). So unfortunately I have not yet had to use the Oric Diagnostic board extensively on a fully failed computer.

<img src="https://github.com/user-attachments/assets/2127b17d-bf6f-4c9e-8466-6344f3e995aa" width="500">
