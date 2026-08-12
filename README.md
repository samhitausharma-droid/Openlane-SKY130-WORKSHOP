# Openlane-SKY130-WORKSHOP

### Sky130 Day 1 - Inception of open-source EDA, OpenLANE and Sky130 PDK

### SKY_L1 - Introduction to QFN-48 Package, chip, pads, core, die and IPs


<img width="407" height="332" alt="image" src="https://github.com/user-attachments/assets/bf21acff-92c9-4a71-9308-8b795e47d5aa" />


The layout of this  Ardunio Board is :


<img width="774" height="424" alt="image" src="https://github.com/user-attachments/assets/f8e4c451-004e-4d63-96dc-0ce2629e4599" />



<img width="554" height="422" alt="image" src="https://github.com/user-attachments/assets/2ae22033-06c8-45af-bb59-595426223984" />




<img width="659" height="419" alt="image" src="https://github.com/user-attachments/assets/7c13cc7e-7ccb-4149-98fa-4e66aa9a8472" />



Pads are something which acts like a gate where the signal goes inside and outside 

Core is a place where all the digital logic sits 


<img width="776" height="419" alt="image" src="https://github.com/user-attachments/assets/59cb132e-13f2-414c-96f3-787451d21645" />




### SKY_L2 - Introduction to RISC-V


<img width="953" height="565" alt="image" src="https://github.com/user-attachments/assets/af3b4e16-8fc2-4ff4-9607-cf0e245eafe0" />



### SKY_L3 - From Software Applications to Hardware


converting the inputs into the desired hardware language is the job of the **COMPILER**

converting the instructions  into binary language is the job of the **ASSEMBLER**


<img width="945" height="578" alt="image" src="https://github.com/user-attachments/assets/1f3f8d66-d78f-485f-b695-e0e331003a36" />


<img width="952" height="580" alt="image" src="https://github.com/user-attachments/assets/046569b8-2369-43e8-b658-1b02af6efa37" />


Basic Flowchart 


<img width="953" height="568" alt="image" src="https://github.com/user-attachments/assets/47dd9059-d675-4d03-a8eb-57835256f273" />


### SKY_L1 - Introduction to all components of open-source digital asic design

<img width="863" height="467" alt="image" src="https://github.com/user-attachments/assets/dc960992-1736-4e85-8d8f-613df448eada" />



<img width="575" height="428" alt="image" src="https://github.com/user-attachments/assets/1c11d21e-be69-4c11-bba3-3b2a15e204d2" />


Google worked out an agreement  with skywater to opensource the pdk for the 130nm processed by skywater

as a result google released the **first opensource pdk**

<img width="527" height="494" alt="image" src="https://github.com/user-attachments/assets/391a85fa-d012-4501-82bd-51277ce9680f" />


### SKY_L2 - Simplified RTL2GDS flow

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


### SKY_L4 - Introduction to OpenLANE detailed ASIC design flow




<img width="869" height="412" alt="image" src="https://github.com/user-attachments/assets/5d7e2aea-ec0f-4526-9f22-91f9c610d5e4" />


<img width="869" height="412" alt="image" src="https://github.com/user-attachments/assets/a7fb7e1e-ea48-4133-b967-7719e6506b04" />





<img width="552" height="290" alt="image" src="https://github.com/user-attachments/assets/176a7044-3ef6-40b4-b462-e4e566d39f00" />






It can be used to **generate reports showing how the design and area are affected by different synthesis strategies, helping us choose the most suitable strategy for the design.**



Design Exploration is used to find the best configuration 



<img width="436" height="252" alt="image" src="https://github.com/user-attachments/assets/d8d5542b-b7dc-46d9-b00f-dc95ac5f19a2" />
