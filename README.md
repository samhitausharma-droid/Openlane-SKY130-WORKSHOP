
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


![Uploading image.png…]()



### SKY_L1 - Create Active regions

