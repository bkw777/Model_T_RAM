# Model_T_RAM
8K RAM module for "Model T Computers"  
* TRS-80 Model 100  
* Kyotronic KC-85  
* NEC PC-8201  
* Olivetti M10  

![](Model_T_RAM.jpg)  
![](Model_T_RAM.svg)

Gerbers available in [releases](../../releases/latest).

[PCB from OSHPark](https://oshpark.com/shared_projects/HOKfWeCp)  
[PCB from PCBWAY](https://www.pcbway.com/project/shareproject/Model_T_RAM.html)

[BOM from DigiKey](https://www.digikey.com/short/93zm37zr)

[How to do the legs](doc/DIP_PCB_legs.md)

C1 & C2 are optional: 2 x [0.1uF 0805](https://www.digikey.com/short/hd15vqp7)

----
Thanks to Steve Adolph for advice about putting RAM_RST on /CE rather than just /OE, to protect against write during power transitions.
