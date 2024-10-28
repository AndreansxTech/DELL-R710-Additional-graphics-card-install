# DELL R710 Additional graphics card install</br>
<img alt="Static Badge" src="https://img.shields.io/badge/Dell%20PowerEdge-R710-%23ff29c2">  <img alt="Static Badge" src="https://img.shields.io/badge/Additional_GPU_install-blue">  <img alt="Static Badge" src="https://img.shields.io/badge/Modyfying-8A2Be0">  </br>
__Before doing anything mentioned below please read the whole article__</br>
In the following article I am going to show and explain the proccess of installing an additional GPU to a Dell PowerEdge R710 server.</br>
Please keep in mind that I am __NOT__ responsible for any damage done to your hardware during an attempt to do what I show here.</br>
__Remember that the following article is partially universal, so for example the modding of the riser in Dell R710 will also apply to the R610 riser.__
__Also remember that the following modifications include cutting and doing irreversible changes to your hardware__
## Prerequisites
Before you begin with installing a GPU into that R710, you need to have:
- a basic toolkit (screwdrivers, wire cutters etc.)
- a precise drill
- a saw for metal (optional, because if you will be installing a smaller graphics card for example a GTX 1060, you will not need to cut the <i>Riser 2</i> bracket.
- a soldering iron. I highly advise you to __NOT__ use a typical transformer soldering iron. Instead you should use a precise soldering iron, most likely with a flat-edge soldering tip.
- Of course you need to have some flux and solder
- Also, you most definetly need to have a basic knowledge about things like soldering and electronics.</br>

**I strongly advise you to only do this if you do know what you are doing.** Remember that there are multiple tutorials on Youtube and if something in my article will be unclear to you, just check the videos that other people made.</br>
Below are photos of the front and upper side without cover of the server</br>
<img src="https://github.com/user-attachments/assets/64c85fcd-e2b9-4e1d-92a6-c72aeaed66a8" width=350>
<img src="https://github.com/user-attachments/assets/71c0effe-bd11-450c-a73c-a1e9a4e16cd3" width=500></br>

## What will you need to buy
- Your wanted GPU
- a PCIe power cable (one that fits your card power pins, preferably a 8 pin)
- preferably another motherboard power cable for the R710 (not necessary, just a precaution)
- some electrical tape</br>

## Requirements
Remember that the Dell R710 has limited space for a GPU. You can enlarge that space by cutting a part of the <i>Riser 2</i>. However, you can not make the width of the space bigger, as it would involve interfering with <i>Riser 1</i> which has a dedicated slot for the RAID controller. 

# First step - preparing the Dell R710 <i>Riser 2</i></br>
Preparing the Riser 2 for modifications includes using a drill or a soldering iron. In this step we will "open" the PCIe x8 slot on the riser. "Opening" the slot is just a fancy word for cutting off a piece of plastic that blocks you from physically inserting a GPU with a PCIe x16 connector into a x8 slot. You will need to mount the riser on a stable surface. Now, there are two ways to do this mod. First one includes a precise drill, and the other inludes a soldering iron. 
