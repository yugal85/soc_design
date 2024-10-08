# soc_design


<details>
<summary>DAY 0 : Tools Installation</summary>


**Yosys**
![yosys](https://github.com/user-attachments/assets/c6e81474-db27-4798-9d64-65802c028e3c)




**IVerilog**
![iverilog](https://github.com/user-attachments/assets/f59a239d-7145-4c5b-b0b3-6a7a90934065)




**GTKWave**
![gtkwave](https://github.com/user-attachments/assets/3de31f24-7b1a-45ac-9052-0b97d215041b)

</details>

<details>
<summary>Day 1 : Introduction to Verilog RTL Design and Synthesis</summary>




**GTKWave Output After Running IVerilog**
![good_mux_gtkwave](https://github.com/user-attachments/assets/840a4f95-27bd-4d36-ba19-c790bb52b40f)



**Good MUX and Testbench**
![good_mux_gvim](https://github.com/user-attachments/assets/9c820a1b-1329-4cd5-b725-f8c439f1280c)



**Yosys Output**
![Screenshot 2024-09-26 084110](https://github.com/user-attachments/assets/398ded47-7516-4b38-b87b-abec3354a0c3)



**Synthesized Netlist**
![Screenshot 2024-09-26 084833](https://github.com/user-attachments/assets/8273b602-6642-4c3f-9bb8-2a0b974559b7)


</details>

<details>
  <summary>Day 2 : Timing Libs, Hierarchical vs Flat Synthesis and Efficient Coding Styles</summary>

<h2> Introduction to timing .libs </h2>

**Introduction to Timing Libs**

![Screenshot 2024-09-28 142704](https://github.com/user-attachments/assets/398e1ea6-796e-4cde-ade5-8ca908ff36e2)

<h2> Hierarchical Synthesis </h2>

**Hierarchical Synthesis Code**

![Screenshot 2024-09-28 144633](https://github.com/user-attachments/assets/79fcd54f-3496-4e61-82e3-a6c24d6486f5)

**Hierarchical Synthesis Details 1**
![Screenshot 2024-09-28 145227](https://github.com/user-attachments/assets/9a42c2f2-69ef-48bf-9cf6-d189cfce4b58)


**Hierarchical Synthesis Details 2**

![Screenshot 2024-09-28 145307](https://github.com/user-attachments/assets/e2ed9c6c-0334-4d51-98c0-31dc1d6f147d)

**Hierarchical Synthesis Schematic**

![Screenshot 2024-09-28 145531](https://github.com/user-attachments/assets/3fb7dc8b-bbda-4e1f-bfd2-c04cccd7ab64)

<h2> Flat Synthesis </h2>

**Flat Synthesis Code**

![Screenshot 2024-09-28 150350](https://github.com/user-attachments/assets/e1606871-5434-4eee-be42-3a549f4a26c9)

**Flat Synthesis Schematic**

![Screenshot 2024-09-28 150642](https://github.com/user-attachments/assets/d4ae97bf-79ed-4a22-8e2e-6e1d7d0a7fc8)

<h2> Sub-module Level Synthesis </h2>

**Sub Module Synthesis Details**

![Screenshot 2024-09-28 150909](https://github.com/user-attachments/assets/282d050a-4288-455c-b709-cd4eee109303)


**Sub Module Synthesis Schematic**

![Screenshot 2024-09-28 150941](https://github.com/user-attachments/assets/482d2c13-781b-46ab-abe1-f8c09b178dda)

<h2> Various Flops and Synthesis </h2>


**D-FF with Asynchronous Reset GTKWave**

![Screenshot 2024-09-28 154515](https://github.com/user-attachments/assets/4f6ee167-66e4-48b0-b6ca-e3005e985776)

**D-FF with Asynchronous Reset YOSYS**

![Screenshot 2024-09-28 160045](https://github.com/user-attachments/assets/3e478a51-dcae-4128-8bfb-2ca370b8a2a2)

**D-FF with Asynchronous Set GTKWave**

![Screenshot 2024-09-28 154831](https://github.com/user-attachments/assets/b3e035a2-877b-438b-97db-91afc940ae7c)


**D-FF with Asynchronous Set YOSYS**

![Screenshot 2024-09-28 160236](https://github.com/user-attachments/assets/b88412d0-7053-498b-97c0-6b67ad7c885e)


**D-FF with Synchronous ResetGTKWave**

![Screenshot 2024-09-28 155259](https://github.com/user-attachments/assets/269a2706-3fd0-428b-bc2b-ee181dd21b3b)

**D-FF with Synchronous Reset YOSYS**

![Screenshot 2024-09-28 160359](https://github.com/user-attachments/assets/11a41703-ccb2-47ab-9fb0-3d473eee47b7)

<h2> Synthesizing Mul2 </h2>

**Mul2 Details**

![Screenshot 2024-09-28 161735](https://github.com/user-attachments/assets/2e8ef7ff-ea81-4bbe-82a7-dfa86f76639d)


**Mul2 Code**

![Screenshot 2024-09-28 162221](https://github.com/user-attachments/assets/d85f193c-20f5-413a-ad34-6138255b6012)


**Mul2 Schematic**

![Screenshot 2024-09-28 161805](https://github.com/user-attachments/assets/62e6a194-7047-40c2-82bd-2f2b057eee82)

<h2> Synthesizing Mult8 </h2>

**Mult8 Details**

![Screenshot 2024-09-28 162436](https://github.com/user-attachments/assets/f982a4b5-0ced-43aa-9a66-a19ae67fc623)


**Mult8 Code**

![Screenshot 2024-09-28 162606](https://github.com/user-attachments/assets/32d69219-bbe6-4c8f-83fc-29066022b5bb)


**Mult8 Schematic**

![Screenshot 2024-09-28 162508](https://github.com/user-attachments/assets/748fa535-440e-4f75-b5ba-624bb9b54ed9)
  
</details>

<details>
  <summary>Day 3 : Combinational and Sequential Optimizations</summary>

<h2> Optimizations </h2>

**Optimization Check 1 YOSYS**
![Screenshot 2024-10-01 003042](https://github.com/user-attachments/assets/84ed23e5-16a0-4fa2-998c-31799e1ea1db)



**Optimization Check 2 YOSYS**
![Screenshot 2024-10-01 003239](https://github.com/user-attachments/assets/639deb0a-caa8-4737-9fd2-0cfad9c24eb1)



**Optimization Check 3 YOSYS**
![Screenshot 2024-10-01 003534](https://github.com/user-attachments/assets/93a5d1db-3e1c-470c-b079-8a6a5f609dee)



**Optimization Check 4 YOSYS**
![Screenshot 2024-10-01 003932](https://github.com/user-attachments/assets/cb815290-c9f9-43bb-8f48-907511ff8a08)



**Optimization Check Multiple Module YOSYS**
![Screenshot 2024-10-01 004059](https://github.com/user-attachments/assets/ecdd172f-897f-4b25-9c37-350bf8a7a896)




<h2> D-FF Optimizations </h2>

**D-FF 1 YOSYS**

![Screenshot 2024-10-01 010407](https://github.com/user-attachments/assets/ca02da2b-c439-4a80-896b-bab757c69a5a)



**D-FF 1 GTKWave**

![Screenshot 2024-10-01 010013](https://github.com/user-attachments/assets/9df72448-d6d9-4ad6-86f9-30b2820dbd1e)



**D-FF 2 YOSYS**

![Screenshot 2024-10-01 010718](https://github.com/user-attachments/assets/e256bc6a-e676-4712-a41f-70ebb93a4148)



**D-FF 2 GTKWave**

![Screenshot 2024-10-01 010155](https://github.com/user-attachments/assets/0b037e04-59f1-43a0-b2b8-e3237fc549af)



**D-FF 3 YOSYS**

![Screenshot 2024-10-01 010843](https://github.com/user-attachments/assets/b99aa1e5-2104-4c8d-9ec3-7732ee1617bb)



**D-FF 3 GTKWave**

![Screenshot 2024-10-01 011423](https://github.com/user-attachments/assets/c47c5fc2-f16a-4d07-9756-0b5743c79f91)




**D-FF 4 YOSYS**

![Screenshot 2024-10-01 010929](https://github.com/user-attachments/assets/d206347a-5d5d-449f-9ba2-3bb312e0452a)



**D-FF 4 GTKWave**

![Screenshot 2024-10-01 011501](https://github.com/user-attachments/assets/99d285b6-b3c9-44c2-a4b2-70ca64dd94d7)



**D-FF 5 YOSYS**

![Screenshot 2024-10-01 011003](https://github.com/user-attachments/assets/97851665-94a3-4d75-9072-2a593227e6d5)



**D-FF 5 GTKWave**

![Screenshot 2024-10-01 011540](https://github.com/user-attachments/assets/ce6a5153-ad92-448d-bc4c-5b893cde0719)


<h2> Counter Optimizations </h2>

**Counter Optimization with 1 FF YOSYS**

![Screenshot 2024-10-01 012257](https://github.com/user-attachments/assets/c0c73875-60e1-40e6-b39d-5554bd50d4ac)



**Counter Optimization with 3 FF's YOSYS**

![Screenshot 2024-10-01 013252](https://github.com/user-attachments/assets/32d616c7-cf2f-4001-af7c-b018b4ddbff5)


</details>

<details>
  <summary>Day 4 : GLS, Blocking vs Non-Blocking, and Synthesis-Simulation Mismatch</summary>

<h2> Synthesis-Simulation Mismatch </h2>

**Ternary Operator MUX YOSYS**
![Screenshot 2024-10-01 023111](https://github.com/user-attachments/assets/54fa4436-124f-4741-b9b5-fad61960cf4a)



**Ternary Operator MUX GTKWave**
![Screenshot 2024-10-01 022949](https://github.com/user-attachments/assets/208da10b-4a14-4845-b1a9-edc4e117331a)



**Ternary Operator MUX GLS GTKWave**
![Screenshot 2024-10-01 023618](https://github.com/user-attachments/assets/caf8d2c9-db15-4af2-941f-a1b402d030ac)



**Bad MUX GTKWave**
![Screenshot 2024-10-01 023856](https://github.com/user-attachments/assets/58f03fa2-b2ce-4c0f-8237-457945aae014)



**Bad MUX GLS GTKWave**
![Screenshot 2024-10-01 024237](https://github.com/user-attachments/assets/3976ad7d-819e-424b-91d1-37bd8e1be72f)


<h2> Blocking Vs Non-Blocking </h2>

**Blocking Caveat YOSYS**
![Screenshot 2024-10-01 025246](https://github.com/user-attachments/assets/9d52363b-ff32-4b76-b3ee-8b5a97d7fd18)



**Blocking Caveat GTKWave**
![Screenshot 2024-10-01 024844](https://github.com/user-attachments/assets/2d7979c4-c093-475f-a9f1-b1d64d3056a7)



**Blocking Caveat GLS GTKWave**
![Screenshot 2024-10-01 025550](https://github.com/user-attachments/assets/c0b4c9cf-1c69-4b89-83b7-6d56905bdc64)



  
</details>

<details> 
<summary> Day 5: Introduction to Logic Synthesis</summary>

**Setting Up Synopsys Design Compiler (Flip-Flop)**


![Screenshot 2024-10-08 at 1 09 09 AM](https://github.com/user-attachments/assets/c9c8aa9f-fbf6-47c7-a63d-509369a7cced)



**Un-optimized Netlist**


![Screenshot 2024-10-08 at 1 11 17 AM](https://github.com/user-attachments/assets/d21b3be9-36d6-4f97-8b78-5646717aa3e0)



**Optimization**


![Screenshot 2024-10-08 at 1 17 59 AM](https://github.com/user-attachments/assets/d0d0e57c-1b69-420b-9d0f-e24b79970667)



**Optimized Netlist**


![Screenshot 2024-10-08 at 1 19 06 AM](https://github.com/user-attachments/assets/b645c2de-37c0-4c70-a2a2-e40a82d23e43)



**Design Vision Graphical User Interface**


![Screenshot 2024-10-08 at 1 26 07 AM](https://github.com/user-attachments/assets/1ac3dbb9-a4ee-4c56-9f7f-2d77e1182a74)




</details>

<details> 
<summary> Day 6 : Basics of STA </summary>

**Understanding the .lib File Part 1**



![Screenshot 2024-10-08 at 7 35 19 PM](https://github.com/user-attachments/assets/6d0e7660-e516-4c59-8bd0-b440afaedac6)





**Understanding the .lib File Part 2**


![Screenshot 2024-10-08 at 7 42 03 PM](https://github.com/user-attachments/assets/6ab03999-91aa-4ee0-bf1b-a5919cb1dbb3)





</details>
