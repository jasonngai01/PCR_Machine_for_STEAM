# PCR_Machine_for_STEAM OUHK

The thermal cycler (also known as a thermocycler, PCR machine or DNA amplifier) is a laboratory apparatus most commonly used to amplify segments of DNA via the polymerase chain reaction (PCR).

Thermal cyclers may also be used in laboratories to facilitate other temperature-sensitive reactions, including restriction enzyme digestion or rapid diagnostics.

OUHK STEAM designs and develops a simple thermal cycler for secondary school teachers and students to demostate the polymerase chain reaction (PCR). You are welcome to download and modify both hardware design and software here!!

The device has a thermal chamber with the ceramic heating bulb and fan where PCR tubes holding the reaction mixtures can be inserted. The cycler then raises and lowers the temperature of the block in discrete, pre-programmed steps.

# Mechanical Design 

![image](https://github.com/jasonngai01/PCR_Machine_for_STEAM_OUHK/blob/main/Photo/PCR%20Machine%20ver.1.png)

# Electronic Circuit

The cycler is controlled by the Arduino Uno. It needs to connect with the computer to monitor the temperature. The Ceramic heating bulb and the Fan need external 220 AC power source. 

![image](https://github.com/jasonngai01/PCR_Machine_for_STEAM_OUHK/blob/main/Photo/Circuit.png)

# Arduino Software programme 

In this program, it allows users to define the Temperture, Duratuation of different stage and number of cycles. 

![image](https://github.com/jasonngai01/PCR_Machine_for_STEAM_OUHK/blob/main/Photo/Program%20flow.png)