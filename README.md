
# Openlane-SKY130-WORKSHOP

<img width="748" height="245" alt="image" src="https://github.com/user-attachments/assets/f18cfa23-34aa-4036-a1a0-8d33ed9ca54a" />


### Sky130 Day 1 - Inception of open-source EDA, OpenLANE and Sky130 PDK




<img width="407" height="332" alt="image" src="https://github.com/user-attachments/assets/bf21acff-92c9-4a71-9308-8b795e47d5aa" />


The layout of this  Ardunio Board is :


<img width="774" height="424" alt="image" src="https://github.com/user-attachments/assets/f8e4c451-004e-4d63-96dc-0ce2629e4599" />



<img width="554" height="422" alt="image" src="https://github.com/user-attachments/assets/2ae22033-06c8-45af-bb59-595426223984" />




<img width="659" height="419" alt="image" src="https://github.com/user-attachments/assets/7c13cc7e-7ccb-4149-98fa-4e66aa9a8472" />



Pads are something which acts like a gate where the signal goes inside and outside 

Core is a place where all the digital logic sits 


<img width="776" height="419" alt="image" src="https://github.com/user-attachments/assets/59cb132e-13f2-414c-96f3-787451d21645" />






<img width="953" height="565" alt="image" src="https://github.com/user-attachments/assets/af3b4e16-8fc2-4ff4-9607-cf0e245eafe0" />





converting the inputs into the desired hardware language is the job of the **COMPILER**

converting the instructions  into binary language is the job of the **ASSEMBLER**


<img width="945" height="578" alt="image" src="https://github.com/user-attachments/assets/1f3f8d66-d78f-485f-b695-e0e331003a36" />


<img width="952" height="580" alt="image" src="https://github.com/user-attachments/assets/046569b8-2369-43e8-b658-1b02af6efa37" />


Basic Flowchart 


<img width="953" height="568" alt="image" src="https://github.com/user-attachments/assets/47dd9059-d675-4d03-a8eb-57835256f273" />



<img width="863" height="467" alt="image" src="https://github.com/user-attachments/assets/dc960992-1736-4e85-8d8f-613df448eada" />



<img width="575" height="428" alt="image" src="https://github.com/user-attachments/assets/1c11d21e-be69-4c11-bba3-3b2a15e204d2" />


Google worked out an agreement  with skywater to opensource the pdk for the 130nm processed by skywater

as a result google released the **first opensource pdk**

<img width="527" height="494" alt="image" src="https://github.com/user-attachments/assets/391a85fa-d012-4501-82bd-51277ce9680f" />



<img width="890" height="485" alt="image" src="https://github.com/user-attachments/assets/0912d469-a7d5-438a-b6bf-de9141ebd852" />




**SYNTHESIS**


<img width="895" height="503" alt="image" src="https://github.com/user-attachments/assets/0e70c150-3ce4-4b8f-88e3-9a9460c8f33a" />






**FLOOR AND POWER PLANNING**

Floor planning has 2 types the CHIP FLOOR PLANNING & MACRO FLOOR PLANNING


<img width="878" height="501" alt="image" src="https://github.com/user-attachments/assets/eeb5027c-a2c4-415d-9546-88897183e541" />






**PLACEMENT**


<img width="897" height="514" alt="image" src="https://github.com/user-attachments/assets/9c9a8eed-492e-4dc4-aa46-2a453fcdfd5b" />






**CLOCK TREE SYNTHESIS**



<img width="928" height="502" alt="image" src="https://github.com/user-attachments/assets/555621ed-770c-46ca-b645-a70df70fece3" />




**ROUTING**



<img width="878" height="498" alt="image" src="https://github.com/user-attachments/assets/13be7c53-8683-4ff8-ad2b-da1a1511fdba" />



<img width="575" height="209" alt="image" src="https://github.com/user-attachments/assets/bd3f66f5-bd81-4460-8a3d-0a7be52a1ce8" />






**SIGN OFF**


<img width="902" height="506" alt="image" src="https://github.com/user-attachments/assets/000dc02b-a4ef-4d24-8105-7059cd9871de" />



### SKY_L3 - Introduction to OpenLANE and Strive chipsets



<img width="862" height="470" alt="image" src="https://github.com/user-attachments/assets/b5e3b541-2d69-4a37-8c12-2c2912c0ac9f" />


**OpenLANE ASIC Flow**

* **Main Goal:**
  **Produce a clean GDSII with no human intervention (no-human-in-the-loop)**

* Tuned for **SkyWater 130nm Open PDK**

* **Containerized**

  * Functional out of the box
  * Instructions to build and run natively will follow




1) Can be used to harden Macros and Chips
2) Two modes of operation:
3) Design Space Exploration
4) Large number of design examples
5) 43 designs with their best configurations
6) More will be added soon







<img width="869" height="412" alt="image" src="https://github.com/user-attachments/assets/5d7e2aea-ec0f-4526-9f22-91f9c610d5e4" />


<img width="869" height="412" alt="image" src="https://github.com/user-attachments/assets/a7fb7e1e-ea48-4133-b967-7719e6506b04" />





<img width="552" height="290" alt="image" src="https://github.com/user-attachments/assets/176a7044-3ef6-40b4-b462-e4e566d39f00" />






It can be used to **generate reports showing how the design and area are affected by different synthesis strategies, helping us choose the most suitable strategy for the design.**






Design Exploration is used to find the best configuration 



<img width="436" height="252" alt="image" src="https://github.com/user-attachments/assets/d8d5542b-b7dc-46d9-b00f-dc95ac5f19a2" />





***Regression Testing***


<img width="875" height="480" alt="image" src="https://github.com/user-attachments/assets/d30b99da-43d1-4891-82cd-e4a32b683e4b" />


Next step is design testing



<img width="865" height="438" alt="image" src="https://github.com/user-attachments/assets/624aa87b-2ce8-495e-816d-014a1522b64f" />


**Physical Implementation**


Also called **Automated PnR (Place and Route)**

* Floor/Power Planning
* End Decoupling Capacitors and Tap Cells insertion
* Placement: Global and Detailed
* Post-placement optimization
* Clock Tree Synthesis (CTS)
* Routing: Global and Detailed

**Logic Equivalence Check (LEC)**

* Every time the netlist is modified, verification must be performed.

  * CTS modifies the netlist.
  * Post-placement optimizations modify the netlist.

* LEC is used to formally confirm that the function did not change after modifying the netlist.


**Static time analysis**

<img width="751" height="440" alt="image" src="https://github.com/user-attachments/assets/0d55431b-6883-45e0-a2ad-6f24c5a794c8" />


**Physical Verification – DRC & LVS**

* Magic is used for **Design Rules Checking (DRC)** and **SPICE extraction from layout**.
* Magic and Netgen are used for **LVS (Layout Versus Schematic)**.

  * Extracted SPICE by Magic vs. Verilog netlist.





Openlane is not a tool its a flow which comprises of open source EDA tools 

cd--changing the directory


To locate the work/tools directory in the VSDSquadron Ubuntu environment:

1. Open the terminal.

2. Go to the home directory:
cd

3. List the contents:
ls

4. Enter the Desktop directory:
cd Desktop

5. Check its contents:
ls

6. Enter the work directory:
cd work

7. Check its contents:
ls

8. Enter the tools directory:
cd tools

9. Verify the current location:
pwd

Expected path:
/home/vsduser/Desktop/work/tools

Note: Make sure you are in the VSDSquadron environment, where the terminal prompt is:
vsduser@vsdsquadron:~$


pdk which we will be using is - skywater-130nm


open pdk is the set of files which convert these foundry level pdks to be compatible with the open source EDA tools 

sky130_fd_sc_hd ---> sky130-process name
fd-skywater  foundry
sc- standard cell
hd- (high density)

<img width="913" height="278" alt="image" src="https://github.com/user-attachments/assets/d513b35b-f153-4bb2-a2a6-a24d984776f0" />





OpenLane Docker Setup and Interactive Mode

1. Navigate to the OpenLane directory:
cd ~/Desktop/work/tools/openlane_working_dir/openlane

2. Verify the current directory:
pwd

Expected output:
/home/vsduser/Desktop/work/tools/openlane_working_dir/openlane

3. Check the contents of the OpenLane directory:
ls

The directory should contain files/directories such as:
flow.tcl
designs
scripts
configuration
docker_build
README.md

4. Check the Docker configuration:
type docker

In this setup, Docker is configured as an alias that automatically runs:
docker run -it -v $(pwd):/openLANE_flow -v $PDK_ROOT:$PDK_ROOT -e PDK_ROOT=$PDK_ROOT -u $(id -u $USER):$(id -g $USER) efabless/openlane:v0.21

5. Check the available Docker images:
\docker image ls

The OpenLane image available in this setup is:
efabless/openlane:v0.21

Note:
The instructor's system uses openlane:rc2, while this setup uses efabless/openlane:v0.21.

6. Start the OpenLane Docker container:
docker

The terminal prompt should change to a container prompt such as:
bash-4.1$

7. Enter the mounted OpenLane directory:
cd /openLANE_flow

8. Verify the directory:
pwd

Expected output:
/openLANE_flow

9. List the OpenLane files:
ls -ltr

The output should contain files/directories such as:
flow.tcl
designs
scripts
configuration
docker_build
README.md

10. Start OpenLane in interactive mode:
./flow.tcl -interactive

OpenLane should start and display information such as:
[INFO]: OpenLane
[INFO]: Version: ...

The prompt will then change to:
%

This indicates that the OpenLane interactive mode has been successfully started.

Overall flow:

Host Ubuntu
    ↓
~/Desktop/work/tools/openlane_working_dir/openlane
    ↓
docker
    ↓
OpenLane Docker container
    ↓
/openLANE_flow
    ↓
./flow.tcl -interactive
    ↓
OpenLane interactive prompt (%)



<img width="959" height="486" alt="image" src="https://github.com/user-attachments/assets/07a8b0d1-1994-421d-94dc-7372cb3e277c" />



<img width="959" height="283" alt="image" src="https://github.com/user-attachments/assets/0acc88ca-50fc-4e5b-9b27-78ad68a6f635" />




 <img width="959" height="445" alt="image" src="https://github.com/user-attachments/assets/4f5f5ed2-553c-4a3a-ae88-dc90d579a987" />



 <img width="959" height="424" alt="image" src="https://github.com/user-attachments/assets/a7aa7fe8-02ef-430d-aa46-9293493da231" />



<img width="959" height="449" alt="image" src="https://github.com/user-attachments/assets/f5f39a3d-78b0-45e7-975c-1ad65b08d997" />



### SKY_L3 - Review files after design prep and run synthesis



<img width="934" height="51" alt="image" src="https://github.com/user-attachments/assets/1f31fcd8-f689-46eb-b1c2-f99d126a8e6a" />



<img width="934" height="106" alt="image" src="https://github.com/user-attachments/assets/5fef556a-aefb-48a4-b94d-fbef8f2c488a" />



<img width="959" height="530" alt="image" src="https://github.com/user-attachments/assets/47c89477-500f-457d-8a57-74d68dc8b503" />


Now the initial prep is done so we use the command 
run_synthesis




https://github.com/The-OpenROAD-Project/OpenLane.git

contains all the steps and working and design for the openlane



1) To find the flop ratio--> number of d ff



<img width="387" height="400" alt="image" src="https://github.com/user-attachments/assets/16261242-3229-43de-ae37-55a48978eda4" />



Total no of celss: 14876

(1613/14876)=0.1084 approx 10 %



<img width="911" height="289" alt="image" src="https://github.com/user-attachments/assets/ca2c1017-f80e-49bd-aa46-6bbb2836b346" />



earlier we saw that the folder was empty but now we have synthesis.v file



all the mappings have been done



<img width="953" height="542" alt="image" src="https://github.com/user-attachments/assets/1c36c55f-9b56-4529-9fca-bc6f8914409d" />


<img width="959" height="541" alt="image" src="https://github.com/user-attachments/assets/0c9bf617-a41c-409e-8628-f21b0bdb55ab" />


This is what we had got 


### Sky130 Day 2 - Good floorplan vs bad floorplan and introduction to library cells




First step of floor planning is defining the length and width of core and die


<img width="562" height="387" alt="image" src="https://github.com/user-attachments/assets/f016d81f-25e7-4472-baa5-c1c2e1925808" />



<img width="746" height="348" alt="image" src="https://github.com/user-attachments/assets/5966892c-6fa7-4c58-bf81-ff8e3a4e0b0e" />



we are only interested in the width of the logic gates and ff 



<img width="959" height="521" alt="image" src="https://github.com/user-attachments/assets/29c13665-bdb9-4498-ba78-b8819871ea88" />


<img width="530" height="308" alt="image" src="https://github.com/user-attachments/assets/ae2ecc21-f0c2-4387-819c-5f99908df637" />



### Core and Die

**Die:**
A die is the actual piece of semiconductor material, usually silicon, on which the integrated circuit (IC) is fabricated. A single silicon wafer contains many dies, which are separated and then packaged to form individual chips.

**Core:**
The core is the main area within the die where the actual circuit design is implemented. It contains the logic cells, memory elements, and other circuit components required for the functionality of the design.

**In simple terms:**

* **Wafer** → contains multiple dies
* **Die** → the complete piece of silicon containing the chip
* **Core** → the main circuit area inside the die
* **Package** → protects the die and provides connections to the outside world.


the netlist which was of 4 sq units occupies the complete area of the core 


<img width="863" height="410" alt="image" src="https://github.com/user-attachments/assets/232d4166-ddbc-473d-908e-f232e0c9e691" />


we have utilized the core 100 % 



<img width="592" height="241" alt="image" src="https://github.com/user-attachments/assets/e2b44282-00e0-4256-a3fd-15a8c3f38227" />


**Practically we go for 50-60% utilization**



**Aspect Ratio = Height / Width = 2 unit / 2 unit = 1**


Whenever the **ASPECT RATIO** is **1** it signifies that the chip is a **SQUARE** shape 


<img width="941" height="574" alt="image" src="https://github.com/user-attachments/assets/a0243cf1-5df8-45be-9df9-a2c7ba0525fb" />






<img width="914" height="578" alt="image" src="https://github.com/user-attachments/assets/39f2202d-3db5-4cde-bc07-708367705613" />



Utilization factor is 0.25 suggest that the first netlist has only used 25% of the core


**Define the location of Pre paced cells**




<img width="665" height="386" alt="image" src="https://github.com/user-attachments/assets/f0f16c66-b87d-4d84-b03e-d0789c8775d6" />



### Reusability of IPs/Modules

A large design can be divided into smaller blocks or modules and treated as separate IPs. Once a module is designed and verified, it can be reused multiple times in the same design or in different designs.

For example, **Block 1** can be instantiated multiple times without redesigning its internal logic. Each instance can have different input and output signals.

**Main advantage:**
Design once → Verify once → Reuse multiple times.

This saves **design time, verification effort, and development cost**, while also making the overall design more modular and easier to manage.



<img width="868" height="528" alt="image" src="https://github.com/user-attachments/assets/deb77b57-5026-4bea-bee5-31557e2271ab" />




**Define the location of the pre paced cells**


<img width="863" height="548" alt="image" src="https://github.com/user-attachments/assets/48171e35-c1dc-4e1b-9338-43102361de4f" />


We need to surround them with decoupling capacitors


<img width="959" height="558" alt="image" src="https://github.com/user-attachments/assets/7513c966-3a58-42b3-bdf1-37a150489094" />



<img width="731" height="394" alt="image" src="https://github.com/user-attachments/assets/56fe5316-4e47-4a09-9424-415e4fcde132" />


decoupling capacitor is a huge capacitor which is filled with charge lets say whenever the circuit switches on it
gets current through the capacitor , this capacitor **decouples** the main circuit


Switching activity--> capacitor loose the charge to the circuit
No switching activity-->capacitor replenishes the charge 


<img width="739" height="569" alt="image" src="https://github.com/user-attachments/assets/80c2da82-9b21-4c0f-8420-b01a51916bc8" />


now there is no problem of **cross talk**


 

Since we dont have any decoupling capacitor in this region the power supply is the one who has to supply power to that complete line


<img width="745" height="492" alt="image" src="https://github.com/user-attachments/assets/fde6916a-feb2-451e-aa54-b0fc679f382d" />


1--> charged  to VDD
0--> discharged to ground



<img width="629" height="389" alt="image" src="https://github.com/user-attachments/assets/a79b2e5e-91c6-4d1b-81ee-8dfb5ead8deb" />


now we will connect it to an invertor 


<img width="713" height="264" alt="image" src="https://github.com/user-attachments/assets/1e3652d8-a704-4bdf-9554-ceac2d7e6eb1" />


**Ground bounce** is the unwanted rise in the ground voltage caused by a sudden large current flowing through the parasitic resistance and inductance of the ground path.

In simple words:

 **When many circuits switch at the same time, a sudden current flows through the ground path, causing the ground voltage to temporarily rise. This is called ground bounce.**



 <img width="734" height="268" alt="image" src="https://github.com/user-attachments/assets/3632d569-b1b7-4d79-a005-8ea3cc714b7f" />



**Voltage droop** is the temporary **drop in the supply voltage** when a circuit suddenly demands a large amount of current.

In simple words:

**When many circuits switch at once, the sudden current through the power-delivery path causes the supply voltage to temporarily decrease. This is called voltage droop.**


If there were power supplies all over the places these problems would not have hapend



<img width="740" height="518" alt="image" src="https://github.com/user-attachments/assets/aec97f7e-364a-4b5a-994e-3703b93abc42" />

**instead of a single power supply**



<img width="730" height="521" alt="image" src="https://github.com/user-attachments/assets/4aaa9fff-e19f-4c3a-8775-68ed7de299e5" />



**we connect multiple power supplies**


<img width="781" height="394" alt="image" src="https://github.com/user-attachments/assets/d2acae8f-58a4-4232-ba16-134f31fe43e3" />


**This is how we do power planning***



<img width="812" height="542" alt="image" src="https://github.com/user-attachments/assets/3a157935-07fe-413f-8541-3be92638714b" />



**COMPLETE DESIGN**


<img width="635" height="424" alt="image" src="https://github.com/user-attachments/assets/3f485ea8-8081-4824-a7f2-15481bc070a3" />


<img width="663" height="394" alt="image" src="https://github.com/user-attachments/assets/e48bcace-b1f5-498f-bd81-14726c62aa74" />


We need to be smart in placing the pins 

We need to block the area this make sure that the placement tool doesn't place anything on that area which is reserved for pins 





<img width="959" height="539" alt="image" src="https://github.com/user-attachments/assets/ac9cfd0e-8ffd-4926-b662-f3d1b0ac3051" />


<img width="959" height="544" alt="image" src="https://github.com/user-attachments/assets/dcc25e75-bd51-43f7-863c-32d167cd53da" />

 

to do 



to do






In real world we dont have shapes like this we only have squares and rectangles 

each component of the netlist has been given proper height and width 



<img width="653" height="413" alt="image" src="https://github.com/user-attachments/assets/c848fb8b-b640-4fa5-b236-258635350b80" />



Library consists of width,height,delay information of the cells

mostly all the information of the particular gates 




<img width="819" height="389" alt="image" src="https://github.com/user-attachments/assets/f4aa59a3-cfd5-4cdd-a742-a13a4a718eae" />



<img width="858" height="380" alt="image" src="https://github.com/user-attachments/assets/20093705-817b-4112-8a1c-8bef20ae6928" />


<img width="845" height="401" alt="image" src="https://github.com/user-attachments/assets/f1b50b38-e081-4235-8240-dbc6d1882cb6" />





We need to use optimized placement

we need buffers and repeaters 

<img width="529" height="87" alt="image" src="https://github.com/user-attachments/assets/21999c67-8ed9-41a4-8eab-bca05f116d0e" />

for this we dont need any buffers as the capacitance is enough and the signals are very easily receivable 


<img width="401" height="61" alt="image" src="https://github.com/user-attachments/assets/175905fd-7bdb-4ce7-a57e-c6cd78d6666f" />


**Here the long distance has been cut to short distance using buffer**



<img width="762" height="397" alt="image" src="https://github.com/user-attachments/assets/b8c42b61-1c2d-47eb-9d99-bae1b13963f7" />


<img width="772" height="373" alt="image" src="https://github.com/user-attachments/assets/625f54cd-d661-4b3a-84c2-5c09ce887588" />





<img width="932" height="443" alt="image" src="https://github.com/user-attachments/assets/5224af13-902b-4f0e-b4aa-a5e47ce2f143" />


<img width="551" height="330" alt="image" src="https://github.com/user-attachments/assets/91de38fd-3814-43c7-991f-05f1b688d9b1" />


### SKY_L5 - Congestion aware placement using RePlAce

**congestion related placement***

legalization --> standard cells should be exactly in the rows specified and should not overlap


















### Sky130 Day 3 - Design library cell using Magic Layout and ngspice characterization



<img width="783" height="348" alt="image" src="https://github.com/user-attachments/assets/d41b9bc6-c13e-4427-8015-cd45cc8f6af7" />



pins are equidistant

<img width="959" height="515" alt="image" src="https://github.com/user-attachments/assets/dbd6a185-5a42-44b4-8913-71d5f63b6397" />


<img width="793" height="441" alt="image" src="https://github.com/user-attachments/assets/e12139ac-8adb-4dad-a7f3-02096be56baa" />

**this is a hungarian io pin**


**pins have been stacked upon eachother**

we reset the variables to make change in openlane


The rest of theory on CMOS was learnt in the previous course :: CMOS CIRCUIT DESIGN

Ref for the previous course 
https://github.com/samhitausharma-droid/CMOS-Circuit-Design-SKY130


<img width="494" height="368" alt="image" src="https://github.com/user-attachments/assets/c1c30863-acf1-49b7-be17-c484981b77d0" />






<img width="761" height="91" alt="Screenshot 2026-08-26 191153" src="https://github.com/user-attachments/assets/0ac3f0f9-060c-4782-8c16-fed557413a9a" />


<img width="959" height="456" alt="Screenshot 2026-08-26 191834" src="https://github.com/user-attachments/assets/1c279295-a59e-4d27-af1f-542b8946b1ce" />



<img width="596" height="396" alt="Screenshot 2026-08-26 193230" src="https://github.com/user-attachments/assets/f14f748a-05a3-4df4-8a19-aeeeabe5586a" />



<img width="870" height="275" alt="Screenshot 2026-08-26 193857" src="https://github.com/user-attachments/assets/dd953dcc-08de-4d70-9a78-bbc619ac7333" />



<img width="755" height="257" alt="Screenshot 2026-08-26 194115" src="https://github.com/user-attachments/assets/84e0c3a0-cb1e-4943-ab49-4074aa88446b" />


<img width="562" height="350" alt="image" src="https://github.com/user-attachments/assets/d3cb3454-60dc-40a9-8a9c-2494d4ada311" />



<img width="278" height="182" alt="image" src="https://github.com/user-attachments/assets/8d353de4-a6a8-472c-90c3-dde2f0bd5b2f" />


# Characterization of the Cell

Cell characterization is the process of determining the important timing parameters of the designed CMOS inverter. The three main parameters are Rise Time, Fall Time, and Propagation Delay.

## 1. Rise Time

Rise time is the time taken by the output signal to transition from 20% to 80% of its maximum voltage.

For a maximum voltage of 3.3 V:

* 20% of VDD = 0.66 V
* 80% of VDD = 2.64 V

From the waveform:

* At 0.66 V → t = 6.1615 ns
* At 2.64 V → t = 6.20388 ns

Therefore,

tr = 6.20388 - 6.1615

tr ≈ 0.04238 ns

Therefore, the rise time is approximately 42.38 ps.

## 2. Fall Time

Fall time is the time taken by the output signal to transition from 80% to 20% of VDD.

For VDD = 3.3 V:

* 80% of VDD = 2.64 V
* 20% of VDD = 0.66 V

From the waveform:

* At 2.64 V → t = 4.0402 ns
* At 0.66 V → t = 4.068 ns

Therefore,

tf = 4.068 - 4.0402

tf ≈ 0.0278 ns

Therefore, the fall time is approximately 27.8 ps.

## 3. Propagation Delay

Propagation delay is the time difference between the 50% VDD crossing of the input and the corresponding 50% VDD crossing of the output.

Since VDD = 3.3 V,

50% of VDD = 1.65 V

Using the plot cursor, the threshold-crossing points were measured as:

Input:
Time = 2.14998 ns
Voltage = 1.65008 V

Output:
Time = 2.18598 ns
Voltage = 1.65001 V

Therefore,

tpd = t(output @ 50%) - t(input @ 50%)

tpd = 2.18598 ns - 2.14998 ns

tpd = 0.036 ns

Therefore, the propagation delay is approximately 36 ps for the shown transition.

Note: A different transition of the waveform gave a propagation delay of 0.03357 ns (33.57 ps). This difference occurs because the measurements were taken from different input/output transitions. For the threshold-crossing example shown here, the propagation delay is 0.036 ns.

## Key Takeaways

* Rise time = 0.04238 ns (42.38 ps)
* Fall time = 0.0278 ns (27.8 ps)
* Propagation delay = 0.036 ns (36 ps) for the shown transition.
* The output correctly follows the inverse of the input, confirming the expected CMOS inverter behavior.
* Propagation delay indicates how quickly the inverter responds to an input transition and is important for determining the switching speed and timing performance of the standard cell.
* Layout-extracted parasitics make the SPICE simulation more representative of the actual layout implementation rather than an ideal schematic.
* The PMOS is made slightly wider than the NMOS to compensate for the lower hole mobility and help balance the pull-up and pull-down strengths.


### Sky130 Day 4 - Pre-layout timing analysis and importance of good clock tree


Our objective is to extract the lef file 


<img width="278" height="182" alt="image" src="https://github.com/user-attachments/assets/b7f70b1c-3cd0-405d-b345-193e28477e86" />

Track = a routing lane for wires.

**the width must be odd multiples of the x pitch**



<img width="959" height="552" alt="image" src="https://github.com/user-attachments/assets/fdc6a63d-24f3-4c37-874c-628b1ae2c2c8" />


**next step would be to plug the file into picorv32a**


<img width="950" height="525" alt="image" src="https://github.com/user-attachments/assets/117e20be-22cc-4e9a-abc3-279469875597" />


<img width="959" height="484" alt="image" src="https://github.com/user-attachments/assets/8ad6dbf4-1476-4679-8636-49cfba79c898" />


CLOCK TREE SYNTHESIS (CTS)

CTS is the process of building a clock distribution network using buffers so that the clock signal reaches all flip-flops with minimum skew.

Example:

                    Clock
                      |
                   Buffer 1
                      |
                      A
                   /     \
              Buffer 2   Buffer 2
                 |           |
                 B           C
               /   \       /   \
             C1    C2    C3    C4

There are 2 levels of buffering:

Level 1:
- The first buffer drives two buffers.
- The two buffers are identical.

Level 2:
- Each Level-2 buffer drives two output loads.
- The buffers at the same level are identical.

Assume:
C1 = C2 = C3 = C4 = 25 fF
Cbuf1 = Cbuf2 = 30 fF

Capacitance at node A:
Node A drives two buffers, each having 30 fF input capacitance.

Therefore,
C(A) = Cbuf1 + Cbuf2
     = 30 + 30
     = 60 fF

Capacitance at node B:
Node B drives C1 and C2.

Therefore,
C(B) = C1 + C2
     = 25 + 25
     = 50 fF

Capacitance at node C:
Node C drives C3 and C4.

Therefore,
C(C) = C3 + C4
     = 25 + 25
     = 50 fF


DELAY TABLE

The delay table of a standard-cell buffer gives the delay of the buffer for different:

1. Input slew
2. Output load capacitance

The delay is determined using:

Input Slew + Output Load → Buffer Delay

For example, if the input slew is 40 ps and the output load is 50 fF, the library delay table is used to find the corresponding buffer delay.


POWER-AWARE CTS

CTS does not only try to minimize clock skew. It also considers power consumption.

Larger buffers:
- Can drive larger loads
- Improve slew and timing
- Consume more power
- Occupy more area

Smaller buffers:
- Consume less power
- Occupy less area
- May have worse slew and timing

Therefore, power-aware CTS tries to balance:

Timing + Clock Skew + Power + Area


KEY POINT:

CTS builds a balanced clock tree so that the clock reaches all sequential elements with minimum skew.

Capacitance at a node = Sum of the capacitances directly driven by that node.

Buffer delay depends mainly on:
Input Slew + Output Load Capacitance


<img width="959" height="583" alt="image" src="https://github.com/user-attachments/assets/1f8c9f0a-4976-46ee-9b52-6bab5eeb8585" />



<img width="958" height="599" alt="image" src="https://github.com/user-attachments/assets/0cdd9d4b-6802-4525-b763-960cbbcfec07" />


<img width="542" height="394" alt="image" src="https://github.com/user-attachments/assets/3f769b3a-176d-4fdb-9e9f-1d7414032d4e" />




<img width="553" height="310" alt="image" src="https://github.com/user-attachments/assets/c53bb595-4f51-42a2-bc61-1eaec796a64e" />



1. **Setup time** is the minimum time data must be stable before the capture clock edge.
2. Data is launched from the **launch flop** at the clock edge.
3. It passes through the **combinational logic** and reaches the capture flop.
4. Data must arrive **before the next clock edge** by at least the setup time.
5. Setup condition: **Tclk ≥ Tcq + Tcomb + Tsetup**.



<img width="731" height="263" alt="image" src="https://github.com/user-attachments/assets/430a637b-b275-49b2-b175-20b80838e09a" />


<img width="959" height="599" alt="image" src="https://github.com/user-attachments/assets/98bfd65b-0169-405f-9a82-466cdd6cad39" />


<img width="791" height="369" alt="image" src="https://github.com/user-attachments/assets/c9197b71-39e4-494c-8018-039261d3c5c9" />



1. **Clock Tree Synthesis (CTS)** distributes the clock signal from the source to all flip-flops.
2. It inserts **clock buffers/inverters** to drive the clock properly.
3. CTS tries to make the clock arrival time at different flip-flops as equal as possible.
4. This reduces **clock skew**, which can cause setup and hold violations.
5. The final goal is a **balanced clock tree** with proper timing and minimal delay.


<img width="807" height="387" alt="image" src="https://github.com/user-attachments/assets/e60591ac-d9d4-4cdd-b504-413e35e83138" />


<img width="660" height="470" alt="image" src="https://github.com/user-attachments/assets/e393c450-88e0-4c2d-b4f8-f72e62f17098" />


1. **Crosstalk** between nearby wires can change the delay of a signal.
2. Before crosstalk, the delay is **D**; after crosstalk, it becomes **D + Δ**.
3. This extra delay **Δ** shifts the clock arrival time.
4. Different clock paths experience different delays, creating **clock skew**.
5. Therefore, crosstalk can cause **setup/hold timing violations**.



<img width="959" height="530" alt="image" src="https://github.com/user-attachments/assets/02277c1f-4d26-4980-b0b5-4639eace03d0" />


<img width="321" height="312" alt="image" src="https://github.com/user-attachments/assets/3a81a3da-d626-4ff6-ac75-0d21405f2a24" />


A summary of everything 

including ### 

* **Clock Tree Synthesis (CTS)** is basically the stage where we make sure the clock reaches all the flip-flops in a controlled and balanced way. Before CTS, the clock is treated as an ideal signal, but in the actual chip the clock has to travel through physical wires and buffers, so different flip-flops can receive it at different times.

* CTS solves this by building a **clock distribution tree** from the main clock source to all the sequential elements. It adds clock buffers at different points in the design so that one clock signal can drive thousands of flip-flops without excessive delay or signal degradation.

* The important thing here is **clock skew**. Skew is the difference between the clock arrival times at two different flip-flops. Ideally, we want the clock to reach all the flip-flops at nearly the same time because large skew can create **setup and hold timing problems**.

* In this flow, the important CTS variables were checked first, such as `CTS_CLK_BUFFER_LIST`, `CTS_ROOT_BUFFER`, `SYNTH_MAX_TRAN` and `CTS_MAX_CAP`. These variables basically tell OpenLane/OpenROAD which clock buffers can be used and what electrical limits should be maintained. 

* The `CTS_CLK_BUFFER_LIST` contained `clkbuf_1`, `clkbuf_2`, `clkbuf_4` and `clkbuf_8`. The smallest buffer, `clkbuf_1`, was temporarily removed before CTS. This leaves the stronger buffers available for building the clock tree. 

* The root of the clock tree used `clkbuf_16`. This makes sense because the root buffer has to drive a very large amount of downstream clock load, so a stronger buffer is useful there. 

* CTS was then executed using `run_cts`. After completion, the generated CTS DEF was loaded back into OpenROAD along with the LEF, Liberty file, netlist and SDC constraints. This was done to verify that the CTS result could be read correctly and timing could be checked on it. 

* One very noticeable change after CTS was the **increase in component count**. The design went from about **21,699 components before CTS to 29,412 after CTS**. This huge increase is mainly because CTS inserted a large number of clock buffers and clock nets. 

* For the hold check, the reported slack was **+0.25**, which means the path passed the hold requirement. A positive slack means the timing requirement is satisfied. 

* The setup check was also clean, with a **slack of 10.15** and `WNS = 0.00`, `TNS = 0.00`. So after CTS, there were no setup timing violations in the reported analysis. 

* The clock skew report showed a skew of about **3.87** for the checked clock paths. The main idea is that CTS has now replaced the ideal clock assumption with an actual clock network containing buffers and delays. 

* After CTS was finished, `clkbuf_1` was added back to the buffer list. So the configuration was restored to the original four-buffer list. This doesn't mean CTS suddenly uses the buffer again for the already completed tree; it restores the environment for later stages. 

* The next major step is **PDN generation**. PDN stands for **Power Distribution Network**. Basically, before we start routing all the signal connections, we need to create the VDD and GND network that supplies power to the standard cells.

* PDN has to be present before routing because the power grid occupies physical metal resources. The signal router has to work around these fixed power structures instead of routing signals through them. Also, without a proper power network, the cells cannot actually receive their required power in the final chip. 

* Before generating the PDN, `CURRENT_DEF` was pointed to the **floorplan DEF**. This is important because PDN is generated on top of the floorplanned design, before the later placement and routing details are added. 

* After that, routing was performed using `run_routing`. The router connects the signal nets between all the cells while respecting the existing placement and power structures.

* The final routed design had a total wire length of approximately **1,325,012 µm**. Most of the wiring was on `met1` and `met2`, with additional routing on `met3`, `met4` and the other layers. There were also around **179,133 vias** used to make connections between different metal layers. 

* The really important result here is **zero DRC violations after detailed routing**. DRC means **Design Rule Check**. It verifies things such as spacing, width and other manufacturing-related physical rules. Zero violations means the routed layout passed the router's detailed design-rule checks. 

* After routing, we cannot just assume that timing is still perfect because real wires introduce **resistance and capacitance**. So the next step is **parasitic extraction**.

* During SPEF extraction, the routed LEF and DEF information is processed to calculate the parasitic effects of the physical interconnect. The extracted information is stored in a **SPEF file**, which can then be used during static timing analysis. 

* OpenSTA then performs **post-route Static Timing Analysis (STA)** using the routed design and extracted parasitics. This gives a much more realistic timing picture than the earlier ideal-clock analysis because now the physical wire delays are included.

* The final reported result was **WNS = 0.00 and TNS = 0.00**. So the routed design remained timing-clean after parasitic extraction. 

* Finally, the design moves toward **GDSII generation**. GDSII is basically the final physical layout database that represents the shapes, layers, cells, wires and other information needed for fabrication.

* The generated GDS was opened in **Magic** using the Sky130A technology file. This allows us to visually inspect the final layout and see the standard cells, metal layers, vias and filler cells. 

* After this, the main sign-off checks are **final DRC, LVS, parasitic extraction/STA and GDSII sign-off**. LVS is especially important because it checks whether the physical layout actually corresponds to the intended circuit/netlist.

* So the overall flow is basically: **CTS → balanced clock network → PDN → signal routing → parasitic extraction → post-route STA → GDSII → final sign-off**. The nice part is that each stage is building on the previous one: first we make the clock physically realistic, then provide power, then connect everything, then account for real wire effects, and finally prepare the layout for fabrication. 


<img width="536" height="354" alt="image" src="https://github.com/user-attachments/assets/2634491b-1559-4cf6-a28b-17fe87aae17c" />



<img width="757" height="378" alt="image" src="https://github.com/user-attachments/assets/21807947-dd12-477c-ab7b-6be94c4bf3c7" />





* **Routing** is the stage where all the placed cells/pins in the chip are physically connected using metal layers. The router has to find paths between source and destination while making sure there are no unwanted connections or design-rule violations.

* Routing is generally divided into **Global/Fast Routing** and **Detailed Routing**. Global routing first decides the approximate path and which regions/layers should be used. It does not worry about the exact metal shapes yet.

* **Detailed routing** comes after that. Here, the actual tracks, metal segments and vias are decided. It works with the detailed routing grid and has to obey the actual spacing, width, layer and connectivity rules.

* TritonRoute takes things such as **LEF, DEF and preprocessed route guides** as inputs. Its job is to produce a detailed routing solution while trying to keep the **wire length and number of vias** reasonable. It also has to follow the route guides, maintain connectivity and obey design rules.

* Before detailed routing, the original route guides need some **preprocessing**. The initial guides may be too large or may not be properly aligned with the routing tracks, so they are modified into a form that the detailed router can actually use.

* The preprocessing mainly involves **splitting, merging and bridging**. Splitting breaks larger guide regions into smaller usable pieces, merging combines compatible regions, and bridging connects separated guide portions when required.

* A good preprocessed route guide should have **unit width** and should follow the **preferred routing direction** of its metal layer. In the example, M1 is preferred for vertical routing while M2 is preferred for horizontal routing.

* **Access Points (APs)** are important because the router needs specific locations from which a net can enter or leave a routing segment or connect to a pin. Basically, they provide legal points where the router can make a connection.

* An access point can connect to a **lower metal layer**, connect directly to a **pin shape**, or connect to an **upper metal layer**. When changing between layers, a **via** is required.

* The access-point concept is especially important when a pin exists on one layer but the routing path needs to continue on another layer. The router therefore has to find a legal point and a legal via connection rather than simply drawing a wire wherever it wants.

* After the access points are identified, the router needs to decide **how all the terminals should be connected**. This is where the **routing topology** comes in.

* The routing topology can be optimized using a **Minimum Spanning Tree (MST)**. First, the distances/costs between the different access points are calculated. These costs represent how expensive it is to connect one point to another.

* The algorithm considers every pair of access points and calculates something like `cost(i,j) = distance(APCi, APCj)`. Then the MST is generated using these costs.

* The main idea of MST is to connect **all required points with minimum total connection cost**, without creating unnecessary loops. This gives the global router a good starting topology before the actual detailed routing happens.

* Once the topology is decided, the router still has to find actual physical paths through the routing grid. This is where **maze routing** becomes useful.

* In maze routing, the routing area is treated like a **2-D grid**. Each grid location can either be available for routing or blocked because of cells, existing metal, obstacles or design rules.

* The router starts from one terminal and explores neighbouring grid locations until it reaches the destination. Different grid locations can have different costs, so the router tries to choose a path with the lowest overall cost.

* **Straight movement** is generally given a lower cost, while turns can have higher costs. This encourages the router to avoid unnecessary bends and helps produce shorter and cleaner routes.

* The numbers shown in the maze-routing example represent the **cost/distance from the target point**. The router expands through neighbouring grid cells and eventually finds a path connecting the required terminals.

* The overall idea is therefore not just "draw a wire between two points." The router has to consider **routing tracks, preferred directions, obstacles, access points, vias, wire length, connectivity and design rules** at the same time.

* In the bigger picture, the routing flow can be remembered as:

**Preprocess route guides → Find access points → Build routing topology using MST → Global/Fast routing → Detailed/Maze routing → Check DRC**

* In your OpenLane flow, after PDN generation, the actual routing was performed using `run_routing`. The resulting design contained routing across multiple metal layers and a very large number of vias. 

* The important final check after detailed routing is **DRC**. In your run, the detailed routing completed with **no DRC violations**, which means the generated layout satisfied the checked physical design rules. 

**One-line memory trick:**
**Guide → Access Point → Topology → Global Route → Maze/Detailed Route → DRC**.


<img width="196" height="347" alt="image" src="https://github.com/user-attachments/assets/ed9efd71-be44-4608-bfad-26fc010a50c1" />


**short notes**




