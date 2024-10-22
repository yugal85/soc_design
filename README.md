
<details>
<summary> <h3> Module 0 : Tools Installation </h3> </summary>


**Yosys**
![yosys](https://github.com/user-attachments/assets/c6e81474-db27-4798-9d64-65802c028e3c)




**IVerilog**
![iverilog](https://github.com/user-attachments/assets/f59a239d-7145-4c5b-b0b3-6a7a90934065)




**GTKWave**
![gtkwave](https://github.com/user-attachments/assets/3de31f24-7b1a-45ac-9052-0b97d215041b)

</details>

<details>
<summary> <h2> Module 1 : Introduction to Verilog RTL Design and Synthesis </h2> </summary>




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
  <summary> <h3> Module 2 : Timing Libs, Hierarchical vs Flat Synthesis and Efficient Coding Styles </h3> </summary>

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
  <summary> <h3> Module 3 : Combinational and Sequential Optimizations </h3> </summary>

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
  <summary> <h3> Module 4 : GLS, Blocking vs Non-Blocking, and Synthesis-Simulation Mismatch </h3> </summary>

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
<summary> <h3> Module 5: Introduction to Logic Synthesis </h3> </summary>

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
<summary> <h3> Module 6 : Basics of STA </h3> </summary>

**Understanding the .lib File Part 1**



![Screenshot 2024-10-08 at 7 35 19 PM](https://github.com/user-attachments/assets/6d0e7660-e516-4c59-8bd0-b440afaedac6)





**Understanding the .lib File Part 2**


![Screenshot 2024-10-08 at 7 42 03 PM](https://github.com/user-attachments/assets/6ab03999-91aa-4ee0-bf1b-a5919cb1dbb3)



**TCL Script for Listing Cell Names**


![Screenshot 2024-10-12 at 7 32 55 PM](https://github.com/user-attachments/assets/9699894e-e85d-4b16-888d-9386d3644f64)


**Getting Direction of Pins Using TCL for AND2**


![Screenshot 2024-10-12 at 7 48 41 PM](https://github.com/user-attachments/assets/572caa09-75e8-46a7-a5a1-800574064fe5)


**Getting Direction of Pins Using TCL for NAND4**


![Screenshot 2024-10-12 at 7 54 25 PM](https://github.com/user-attachments/assets/fe4ca87b-9c49-4670-bced-9b47f2a4d9b7)


**TCL Script for Getting Name, Attribute, and Function**


![Screenshot 2024-10-12 at 8 09 09 PM](https://github.com/user-attachments/assets/c2cbaaa4-3538-47ae-9fa9-82c46aae036b)


**Output After Running TCL Script**


![Screenshot 2024-10-12 at 8 08 58 PM](https://github.com/user-attachments/assets/4006a830-2dc7-4018-961a-d6767d507513)













</details>

<details> 
<summary> <h3> Module 7 : Introduction to BabySoC Modeling </h3> </summary>

<br> 

A System on a Chip (SoC) refers to an integrated circuit that consolidates all essential components of a computing or electronic system onto a single chip. These integrated components typically include:

  1) **Central Processing Unit (CPU):** The primary processor responsible for executing instructions and managing system tasks.
  
  2) **Memory:** Incorporates RAM for temporary data storage and ROM for permanent storage.
  
  3) **Input/Output (I/O) Ports:** Interfaces that enable communication with external devices and peripherals.
  
  4) **Graphics Processing Unit (GPU):** Manages the rendering of images and videos.
  
  5) **Digital Signal Processor (DSP):** Specializes in processing audio, video, and other signal-related tasks.
  
  6) Specialized Modules: Additional components, such as wireless communication units (e.g., Wi-Fi, Bluetooth), power management systems, and various sensors, may be integrated depending on the application.



<img width="821" alt="Screenshot 2024-10-19 at 6 48 34 PM" src="https://github.com/user-attachments/assets/45f881e5-0c65-440f-8027-af56355d4615">







<u> Key Benefits of SoCs: </u> 

  1) **Size Reduction:** The integration of multiple components into a single chip drastically reduces the physical footprint of the system, making it ideal for compact designs.
  
  2) **Power Efficiency:** SoCs typically consume less power than systems composed of discrete components due to optimized interconnections and minimized external interfaces.
  
  3) **Performance Optimization:** The proximity of integrated components allows for faster data transfer and enhanced overall system performance.
  
  4) **Cost-Effectiveness:** The production of a single chip with multiple functionalities is often more economical than manufacturing several discrete components, leading to reduced costs for device manufacturers.
  
  5) **Enhanced Reliability:** With fewer external connections between components, SoCs minimize potential points of failure, increasing system reliability.



<u> Common Applications of SoCs: </u>

  1) **Smartphones and Tablets:** SoCs are integral to mobile devices, offering compact form factors and energy-efficient performance.
  
  2) **Wearable Devices:** Smartwatches, fitness trackers, and other wearables rely on SoCs for their small size and low power consumption.
  
  3) **IoT Devices:** SoCs manage sensor integration and connectivity tasks in Internet of Things (IoT) devices.
  
  4) **Embedded Systems:** Widely used in automotive, industrial, and consumer electronics, SoCs handle dedicated processing tasks efficiently.



<u> Notable Examples of SoCs: </u>

  1) **Apple A-Series:** Powers iPhones and iPads.
  
  2) **Qualcomm Snapdragon:** Found in a wide range of Android smartphones.
  
  3) **Samsung Exynos:** Used in Samsung's mobile devices.
  
  4) **NVIDIA Tegra:** Utilized in gaming consoles like the Nintendo Switch.



<u> Challenges and Considerations: </u>

  1) **Design Complexity:** Integrating multiple components onto a single chip is technically challenging and requires advanced design and fabrication techniques.
  
  2) **Thermal Management:** Concentrating various components in a compact space can lead to overheating, necessitating effective thermal management strategies.
  
  3) **Limited Flexibility:** SoCs, due to their high level of integration and application-specific design, offer less flexibility compared to discrete-component systems.



In summary, SoCs are central to the development of modern electronic devices, enabling the creation of more compact, efficient, and high-performance systems. However, their design and implementation demand sophisticated engineering solutions to address challenges such as heat dissipation, complexity, and flexibility.




Types of SoC:

  1) Microcontroller-based SoCs: These SoCs are built around a microcontroller, ideal for embedded systems that require less processing power but need integrated peripherals and memory.
  
  2) Microprocessor-based SoCs: These SoCs, often found in mobile phones, are built around a microprocessor and are designed for systems requiring more complex processing capabilities like smartphones, tablets, or personal computing devices.
  
  3) Application-Specific SoCs (ASIC): These are customized SoCs designed for particular applications that do not fit into the microcontroller or microprocessor categories. They often target specialized tasks such as video encoding, signal       
     processing, or networking.

<br> 

**SoC Structure:**
An SoC is composed of various hardware functional units that work together, including processors, memory modules, and communication subsystems. These components are interconnected by various communication frameworks like buses or Networks on Chip (NoCs).

**Functional Components:**

  1) Processor Cores: Execute software tasks and control system operations.
  2) Memory: Includes on-chip RAM, ROM, and cache for data storage and retrieval.
  3) Interfaces: Connect external devices and components.
  4) Digital Signal Processor (DSP): Handles real-time processing of audio, video, and other signals.


**SoC Design Flow:**
The SoC design process is structured in multiple stages, from specification and design, to verification and fabrication. This involves architecture design, IP integration, verification, and physical design, followed by validation and testing.


<img width="823" alt="Screenshot 2024-10-19 at 6 49 45 PM" src="https://github.com/user-attachments/assets/a4d63188-72e4-49ce-936e-945d3e82d505">




**Introduction to VSDBabySoC:**

VSDBabySoC is a compact yet powerful RISC-V-based SoC, designed to test and calibrate three open-source IP cores, while integrating an analog component. The key components of the VSDBabySoC are:


![image](https://github.com/user-attachments/assets/19432541-272e-430a-a668-379de7333056)



**RVMYTH Microprocessor:** A simple RISC-V-based CPU.
**8x-PLL:** Generates a stable clock signal for synchronization and timing.
**10-bit DAC:** Converts digital signals to analog, enabling communication with other analog devices.

**BabySoC Components:**
  1) RVMYTH Core: A basic RISC-V CPU used to perform general-purpose computing tasks.
  2) PLL (Phase-Locked Loop): A feedback control system that locks the output frequency to match a reference signal, widely used for clock generation.
  3) DAC (Digital-to-Analog Converter): Converts digital data into analog signals, essential for interfacing with analog devices in communication systems.

What is a PLL (Phase-Locked Loop)?
A Phase-Locked Loop (PLL) is a control system that generates an output signal with a phase that aligns with the phase of a given input signal. It maintains a constant phase difference between input and output, ensuring that both signals operate at the same frequency.

**Key Components of a PLL:**

  1) Phase Detector: Compares the phase of the input signal with that of the oscillator output, generating an error signal.
  2) Loop Filter: Filters the error signal, producing a smooth voltage to control the oscillator.
  3) Voltage-Controlled Oscillator (VCO): Adjusts the frequency based on the error voltage to lock onto the input frequency.
  4) In some configurations, a frequency divider is added in the feedback loop to generate output frequencies that are multiples of the reference signal.

**Why Off-Chip Clocks Can’t Be Used All the Time:**
External clocks can introduce delays due to long wiring and clock jitter. Additionally, different system blocks may require varying clock frequencies, making it impractical to rely on a single external source. Factors such as ppm (parts per million) error, frequency stability, and temperature sensitivity also impact the precision of off-chip clocks, making on-chip PLLs a more reliable option.

**Digital-to-Analog Converter (DAC):**
A Digital-to-Analog Converter (DAC) translates digital signals into analog output. DACs play a critical role in communication systems, where digitally encoded information needs to be converted into analog signals for transmission.

**Types of DACs:**

  1) Weighted Resistor DAC: Uses weighted resistances for each bit in the digital signal.
  2) R-2R Ladder DAC: Employs a repeating structure of resistors to convert the digital signal.

In the VSDBabySoC, a 10-bit DAC is used, which means it has 10 binary input bits that it converts into an analog output. This enables precise control and communication with analog devices.




</details>


<details> 
<summary> <h3> Module 8 : BabySoC Modeling </h3> </summary>

<br>

**What is Modelling?**
Modelling refers to the creation of a mathematical or logical representation of a system or a component to study its behavior, predict outcomes, and support decision-making. In the context of Modelling and Simulation (M&S), it involves constructing a physical or logical model to simulate how a system functions in the real world, allowing engineers to analyze the system under various conditions.

**Purpose of Modelling:**
The primary purpose of system modelling is to aid in:

  1) Analysis: Understanding system behavior and performance.
  2) Specification: Defining system requirements.
  3) Design: Aiding the development of complex systems.
  4) Verification and Validation: Ensuring that the system functions as intended and adheres to specifications.
  5) Communication: Conveying critical information about the system to stakeholders and collaborators.
  In the VLSI domain, modelling is essential for analyzing the functionality and performance of integrated circuits before they are physically built, saving time and resources in development.

**What Are We Modelling?** (VSDBabySoC)
For VSDBabySoC, the model consists of three main Intellectual Property (IP) cores:

  1) PLL (Phase-Locked Loop): Generates the clock signal for the entire system.
  2) RVMYTH (RISC-V CPU): Executes instructions based on the clock input.
  3) DAC (Digital-to-Analog Converter): Converts the output from RVMYTH into an analog signal.


**The flow of signals in the SoC:**

  1) Initial input signals are fed into the VSDBabySoC module.
  2) The PLL generates the proper clock signal (CLK) for the system.
  3) The clock signal triggers the RVMYTH core to execute instructions, producing intermediate values.
  4) These values are used by the DAC core to provide the final analog output signal, OUT.
  5) Additionally, the system includes a wrapper that integrates all the components and a testbench for simulation.

**Challenges in Modelling Mixed-Signal Blocks:**
A key challenge in modelling the VSDBabySoC is that it contains both digital and analog blocks, requiring different simulation approaches:

**RVMYTH (Digital Block):** Since this is a purely digital component, it can be modelled using a Hardware Description Language (HDL) like Verilog, which allows for designing and verifying its functionality using a testbench.

**DAC and PLL (Analog Blocks):** These blocks present a challenge because traditional HDLs like Verilog cannot synthesize analog designs. To simulate the functionality of these blocks, designers will often use specialized data types like real in Verilog for simulation purposes. This allows for verifying the logical correctness of the system without fully synthesizing the analog components.

**Goal of Modelling:**
The ultimate goal of this modelling effort is to simulate the functionality of the VSDBabySoC, ensuring that the system operates correctly from a logical standpoint. While physical synthesis of analog blocks (DAC, PLL) is not possible in Verilog, the model aims to verify the integration and interaction of all IP cores and check whether the system delivers the expected outputs based on input signals and clocking mechanisms.

<h2> RVMYTH MODELING </h2>

![Screenshot 2024-10-19 at 5 39 07 PM](https://github.com/user-attachments/assets/90b78d18-4962-4eaf-bfb4-f5591806a7a7)


<h2> DAC MODELING </h2>

![Screenshot 2024-10-19 at 5 47 12 PM](https://github.com/user-attachments/assets/fa13164a-1345-4de9-8116-329227f0febf)


<h2> PLL MODELING </h2>

![Screenshot 2024-10-19 at 5 51 04 PM](https://github.com/user-attachments/assets/7678b15e-3881-4ad1-b8a7-32fed46f68a3)

<h2> DAC OUTPUT VERIFICATION </h2>

![Screenshot 2024-10-19 at 6 06 53 PM](https://github.com/user-attachments/assets/b0edc2f5-eeda-4d6c-8b0c-16930ea5ad72)







</details>

<details>
  
<summary> <h3> Module 9 : Post-Synthesis Simulation of BabySoC (GLS) </h3> </summary>

<br>

**Why Perform Pre-Synthesis Simulation Instead of Jumping Straight to Post-Synthesis Simulation?**
Pre-synthesis simulation is done to verify the functionality of the design as per the written RTL code. This simulation helps ensure that the logic behaves as intended before synthesis. It focuses solely on functionality, without considering the physical properties of gates or timing delays.

On the other hand, post-synthesis simulation, also called gate-level simulation (GLS), is conducted after synthesis. It takes gate delays into account, checking not only functionality but also timing violations. Post-synthesis simulation highlights potential mismatches caused by improper use of operators or unintended latch inference. For example, incorrect usage of ‘X’ (which stands for 'Unknown' or "Don't care" in simulation or synthesis) can lead to functional discrepancies.

**Gate-Level Simulation (GLS): A Brief Overview**
"Gate level" refers to the netlist view of a circuit, typically generated by the synthesis process. While RTL simulation occurs before synthesis, GLS is a post-synthesis step.

The netlist produced during synthesis contains a detailed list of gates and IP models, representing both the functionality and timing behavior of the design. Unlike RTL simulation, which assumes zero delays and performs in a zero-delay environment, GLS can include unit delays or full timing information, providing a more realistic simulation of how the circuit behaves in terms of timing.

Gate-level simulation plays a critical role in verifying the actual implementation of the design, checking for dynamic circuit behavior that cannot be captured through static analysis. It is a key part of the verification process and helps to ensure that the synthesized design functions correctly under real-world conditions.

**Synthesizing the VSDBabySoC Design:**
To synthesize the VSDBabySoC design, you need .db format files for libraries such as avsddac.lib, avsdpll.lib, and sky130_fd_sc_hd__tt_025C_1v80.lib. These can be generated using the Synopsys Library Compiler (lc_shell).

<h2> Converting .lib to .db format </h2>

![Screenshot 2024-10-21 at 6 05 21 PM](https://github.com/user-attachments/assets/946f8ecf-10cc-4dd7-ba68-d1f7456f6d6f)


<h2> Synthesizing the Design </h2>


![Screenshot 2024-10-21 at 6 12 39 PM](https://github.com/user-attachments/assets/9b1eee7e-e523-4485-bc2a-1780dd7b95f2)





**Linking the Design**



![Screenshot 2024-10-21 at 6 13 12 PM](https://github.com/user-attachments/assets/b4e89e6c-3976-4a28-bbdc-bd951b3a9a8e)



**Report**




![Screenshot 2024-10-21 at 6 14 12 PM](https://github.com/user-attachments/assets/3bbe34c8-718f-4023-b5ce-bd555c93040d)

<h2> Post-Synthesis Waveform (Same as Pre-Synthesis Waveform) </h2>

![Screenshot 2024-10-21 at 6 29 56 PM](https://github.com/user-attachments/assets/3c0ea240-860a-48c8-bab6-5ea1a0e03e82)


  
</details>
