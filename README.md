# A-Model-Based-Approach-to-Torque-Modulation-in-EVs-Using-CAN-and-Simulink
A model-based design for torque modulation in EVs using Simulink and CAN. It features a dynamic model to control motor torque for smooth and efficient performance. Includes Simulink models, CAN setup, and control logic—ideal for MBD, EV applications, and embedded automotive systems.
A Model-Based Approach to Torque Modulation in EVs Using CAN and Simulink

* Objective
To develop a simulation model that controls and modulates the motor torque in an EV based on input conditions such as driver demand, system feedback, and performance constraints. The system aims to:

1] Enhance energy efficiency

2] Ensure smooth driving dynamics

3] Support scalable and modular EV drivetrain design

 * Key Features
Simulink-based Control Architecture:
A closed-loop torque control system is modeled in Simulink, incorporating blocks for input acquisition, control logic, motor dynamics, and feedback.

CAN Communication Integration:
The system simulates a real-time CAN protocol interface, enabling communication between Electronic Control Units (ECUs) such as the pedal sensor module and the motor controller.

Driver Input Simulation:
Accelerator pedal input is modeled and translated into torque demand, processed through control algorithms to generate appropriate motor commands.

Torque Modulation Logic:
Includes dynamic control strategies (e.g., PID or custom logic) to adjust torque based on speed, load, and system state.

Simulation & Analysis:
Time-domain simulations are used to observe torque response, communication flow over CAN, and overall system performance under various driving conditions.

* Simunlink model
  ![Simulink Block diagram](https://github.com/user-attachments/assets/642e6f34-e0c2-4dc7-b2ed-eb326f09968e)


* Results
* 
  ![Graph1](https://github.com/user-attachments/assets/ae6643c7-16ce-41bf-8387-ae9a770b9e35)

  
  ![Graph2](https://github.com/user-attachments/assets/b10cd7d9-088e-49c5-b1a5-af425481da43)

 * Benefits
Promotes a modular and scalable design approach.

Prepares the system for future real-time implementation (e.g., on dSPACE or Speedgoat).

Aligns with automotive industry standards using CAN for robust inter-module communication.

Reduces development time and improves reliability through model-in-the-loop (MIL) testing.

 * Applications
Electric powertrain simulation and control

Automotive control system prototyping

Teaching tool for MBD and embedded automotive applications

Foundation for HIL and Rapid Control Prototyping (RCP)

