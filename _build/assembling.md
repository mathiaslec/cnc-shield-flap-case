# Assembling

<div markdown="1" class="pagebom">

### Parts

* 36 cm of [16awg/1.5mm² black wire]{: Class="bom"} 
* 36 cm of [16awg/1.5mm² red wire]{: Class="bom"} 
* 1 [Arduino Uno board]{: Class="bom"} 
* 4 [blade receptacle connector]{: Class="bom"} 
* 4 [cable ties]{: Class="bom"} 
* 1 [CNC shield]{: Class="bom"} 
* 1 [DC connector socket]{: Class="bom"} 
* 1 [fan]{: Class="bom"} 
* 1 [ferrule]{: Class="bom"} 
* 30 mm of [heat-shrink tube]{: Class="bom"} 
* 5 [jumper wires]{: Class="bom"} 
* 1 [kill switch]{: Class="bom"} 
* 4 [M3x12mm screws]{: Class="bom"} 
* 8 [M3x6mm screws]{: Class="bom"} 
* 1 [noise filtering PCB]{: Class="bom"} 
* 1 [pre-fab braid]{: Class="bom"} 
* 1 [toggle switch]{: Class="bom"} 
* 2 [wagos]{: Class="bom"} 


### Tools

* 1 [Allen wrench]{: Class="bom"} 
* 1 [crimping pliers]{: Class="bom"} 
* 1 [small flat screwdriver]{: Class="bom"} 
* 1 [soldering iron]{: Class="bom"} 
* 1 [wire stripper]{: Class="bom"} 


</div>

## Step 1: Wiring {:id="wiring" class="page-step"}
Before assembly, you need to prepare a few wires. You will need wire strippers and crimpers to complete this step.
![](images/wire-stripper.JPG "")  
![](images/wire-stripper2.JPG "")  
![](images/crimper1.JPG "")  
![](images/crimper2.JPG "")  
 
<div markdown="1" class="info-block">
**Note about stripped wires**

The length of the stripped wire will depend on the component it is connected to. Make sure to refer to the instructions for each component if you are using different brands. The following reference lengths are provided:  
- 11 mm for Wagos  
- 8 mm for ferrules  
- 5 mm for blade receptacle connectors  
These lengths are only guidelines and may vary based on the specific components and wiring requirements, so be sure to consult the instructions for each component before stripping the wires.
</div>


### Jumper wires
If you are using the [noise filtering PCB], you may need up to 5 [jumper wires] to connect the CNC shield to the PCB.  
![](images/jumpers.JPG "")  

### Pre-fab braid
You need 1 [pre-fab braid] (to connect to the emergency button to the CNC shield). Just cut the excess of wires to get 20 cm, then strip about 1 cm on each wire with (for example with a [wire stripper]). Attach the stripped wires to the [kill switch]. 
![](images/braid.JPG "")  
### Connections to power supply
A few wires and components are needed : 

* 8 cm of a [16awg/1.5mm² red wire]. Strip about 5 mm on one side with the [wire stripper](tools/WireStripper.md ""), and solder this wire (with a [soldering iron] and [soldering wire](parts/SolderingWire.md "")) to the **central pin** of the [DC connector socket]. Make sure to add about 15 mm long [heat-shrink tube] of suitable diameter. Strip the other end of the wire of about 11 mm.
* 8 cm of a [16awg/1.5mm² black wire]. Strip about 5 mm on one side with the [wire stripper](tools/WireStripper.md ""), and solder this wire (with a [soldering iron] and [soldering wire](parts/SolderingWire.md "")) to the **external pin** of the [DC connector socket](parts/DCconnector.md ""). Make sure to add about 15 mm long [heat-shrink tube] of suitable diameter. Strip the other end of the wire of about 11 mm.  
![](images/8cm_1.png "")   
* Another 8 cm long [16awg/1.5mm² red wire]. Strip one side of this wire on about 11 mm, and strip the other end on about 5 mm and add a [blade receptacle connector]. Crimp the blade connector with a [crimping pliers].
* Another 8 cm long [16awg/1.5mm² black wire]. Strip one side of this wire on about 11 mm, and strip the other end on about 5 mm and add a [blade receptacle connector]. Crimp the blade connector with a [crimping pliers].
![](images/8cm_2.png "")   
* 20 cm of a [16awg/1.5mm² black wire]. Strip one side of this wire on about 11 mm, then strip the other end on about 5 mm and add a [blade receptacle connector].
* 20 cm of a [16awg/1.5mm² red wire]. Strip one side of this wire on about 8 mm, and add a [ferrule], then strip the other end on about 5 mm and add a [blade receptacle connector].
![](images/20cm.png "")   

Here are all the 16awg/1.5mm² wires:  
![](images/all_wires.JPG "")   

### Fan wires
Make sure the [fan] wires are about 30 cm long, then strip about 11 mm on each end.
![](images/fan.JPG "")   

 
## Step 2: First components to attach {:id="first-components-to-attach" class="page-step"}
![](images/kill-switch1.JPG "")   
![](images/kill-switch2.JPG "")   
![](images/kill-switch3.JPG "")   
![](images/kill-switch4.JPG "")   
![](images/dc1.JPG "")   
![](images/wagos.JPG "") 
![](images/switch1.JPG "") 
![](images/switch2.JPG "") 
The following components are easy to install into the case:

* Detach the 2 parts of the [kill switch](parts/KillSwitch.md ""), place the button on the lid, attach it with its plastic nut, then clip the last part to fully assemble it.  
* Attach the DC connector into the case.
* Clip both [wagos] into the case.
* Snap-in the [toggle switch] to the small lid. 

## Step 3: Components attached with screws {:id="components-attached-with-screws" class="page-step"}
![](images/arduino.JPG "") 
![](images/pcb.JPG "") 
![](images/fan2.JPG "") 
A few components need screws to attach them to the box:

* The [Arduino Uno board] needs 4 [M3x6mm screws]. 
* The [noise filtering PCB](parts/NoiseFilteringPCB.md "") needs 4 [M3x6mm screws];
* The [fan](parts/Fan.md "") needs 4 [M3x12mm screws].

Note: Use an [Allen wrench] to attach the components securely.

## Step 4: Final assembling {:id="final-assembling" class="page-step"}
### Wiring
![](images/allred.JPG "") 
![](images/allblack.JPG "") 
![](images/all-blade-connectors.JPG "") 
![](images/black-red-cnc.JPG "") 
![](images/wires-estop.JPG "") 
![](images/wires-estop2.JPG "") 
![](images/jumpers-shield.JPG "") 
The last steps for the wiring are the following:

* Insert all red stripped wires into 1 [wago](parts/Wagos.md "").
* Insert all black stripped wires into the other [wago](parts/Wagos.md "").
* Attach the blade receptacle connector from the 8 cm black wire to the colored pin of the toggle switch (the one below the orange light). *If you bought another toggle switch, make sure to read the datasheet to check were the GND should be plugged*.
* Attach the blade receptacle connector from the 8 cm red wire to the opposite pin of the toggle switch.
* Attach the blade receptacle connector from the 20 cm long red wire to the centered pin of the toggle switch.
* Finally, insert the 20 cm long black and red wires with the ferrules into the "-" and "+" terminal block of the CNC shield, then tighten the screws with a [small flat screwdriver]. You can then plug the [CNC shield].

There are now a few wires to plug:  

* Attach the [pre-fab braid](parts/PrefabBraid.md "") to the kill switch, and to the "E-STOP" pins on the CNC shield.
* If you have a noise filtering PCB, plug it with the 5 jumper wires to the CNC shield.


### Assemble the case
![](images/lid.JPG "") 
![](images/smalllid.JPG "") 
![](images/cableties.JPG "") 
![](images/cableties2.JPG "") 
![](images/cableties3.JPG "") 
Attach the small lid then the lid onto the base.

Now to organize these wires, you can use 2 [cable ties] to attach the 20 cm long wires to the case, and 2 other [cable ties] to attach the kill switch and fan wires together.
[noise filtering PCB]:parts/NoiseFilteringPCB.md ""
[jumper wires]:parts/JumperWires.md ""
[pre-fab braid]:parts/PrefabBraid.md ""
[wire stripper]:tools/WireStripper.md ""
[kill switch]:parts/KillSwitch.md ""
[16awg/1.5mm² red wire]:parts/16awgRedWire.md ""
[soldering iron]:tools/SolderingIron.md ""
[DC connector socket]:parts/DCconnector.md ""
[heat-shrink tube]:parts/Heatshrink.md ""
[16awg/1.5mm² black wire]:parts/16awgBlackWire.md ""
[blade receptacle connector]:parts/BladeReceptacleConnector.md ""
[crimping pliers]:tools/CrimpingPliers.md ""
[ferrule]:parts/Ferrule.md ""
[fan]:parts/Fan.md ""
[wagos]:parts/Wagos.md ""
[toggle switch]:parts/ToggleSwitch.md ""
[Arduino Uno board]:parts/Arduino.md ""
[M3x6mm screws]:parts/M3x6mm.md ""
[M3x12mm screws]:parts/M3x12mm.md ""
[Allen wrench]:tools/AllenWrench.md ""
[small flat screwdriver]:tools/FlatScrewdriver.md ""
[CNC shield]:parts/CNCShield.md ""
[cable ties]:parts/CableTies.md ""

---

[Previous page](3dprinting.md) | [Next page](testing.md)