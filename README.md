# Greetings and salutations! I’m Ayaan.
### Electrical/Computer Engineering @ University of Toronto
#### Motion Planning · Localization · Embedded Systems · Autonomous Vehicles

I'm soon to enter my final year of study, set to graduate with with an Undergraduate in **Electrical/Computer Engineering** (I satisfy requirements for both) from the **University of Toronto**. I build software for autonomous systems, ranging from AGV's in cold storage facilities to formula student racecars with no driver. 

[![LinkedIn](https://img.shields.io/badge/LinkedIn-ayaan--path-0A66C2?style=flat&logo=linkedin)](https://www.linkedin.com/in/ayaan-path)
[![Email](https://img.shields.io/badge/Email-ayaan.path@gmail.com-EA4335?style=flat&logo=gmail)](mailto:ayaan.path@gmail.com)

# Experience

### Robotics Software Developer — SEW Eurodrive
`May 2025 – May 2026 (tentative)`

Bringing AGVs closer to full autonomy in industrial warehouse environments.

- Improved **GMapping-based** localization by enhancing the scan-matching scoring function
- Tuned a **nonlinear optimizer** for the proprietary **Free-Space Segmentation** obstacle avoidance algorithm and implemented **Trajectory Rollout** with **Hybrid A\*** path generation
- Validated the full stack in **Gazebo/RViz**, then successfully deployed on a live AGV in a cold storage facility
- Modified **PLC logic (Structured Text)** to integrate obstacle avoidance output into AGV motion control


<img width="459" height="294" alt="image" src="https://github.com/user-attachments/assets/9107ee8a-d025-459a-be3a-d2f9f362cb95" />
<img width="450" height="200" alt="image" src="https://github.com/user-attachments/assets/b641025a-468c-445b-b367-66e4365bbaef" />

Examples of some path planning output, bound within "corridors" - part of the VDA5050 specification for sending AGVs commands.

<video src="https://github.com/user-attachments/assets/85b69c1a-2e2d-4580-ac71-1ecf7b14c726" controls></video>

The first time we fully integrated obstacle avoidance functionality into an order! I was evidently quite excited.


---

### FSAE Driverless Controls Lead — UofT Formula Racing
`January 2023 – May 2025`

Led controls and firmware for a fully autonomous formula car competing at FSAE.

- Replaced **Pure Pursuit** with **Model Predictive Control (MPC)** in **ROS2** using **GraphSLAM** localization, IMU, and steering angle sensors
- Implemented a centerline path planning algorithm from ETH Zurich (AMZ Driverless) using **Delaunay Triangulation**
- Developed firmware on **ARM Cortex M7** for autonomous state machine, interfacing over **CANbus, I2C, UART, SPI**
- Tuned **PID controllers** for steering, hydraulic brakes, and the main electric drive motor

![IMG_5676](https://github.com/user-attachments/assets/7e2b3325-f12f-4947-a85e-ccd779a1fcd7)

The testing day on which our car ran driverless for the first time! We are the first Canadian team to run Driverless events at competition!

<img width="3442" height="1930" alt="Screenshot 2026-03-07 142259" src="https://github.com/user-attachments/assets/3b5812c4-2b83-4804-82a9-f9033c0e82d2" />

![IMG_4734](https://github.com/user-attachments/assets/2cefe8e3-7799-42cc-840e-ecbb377514e7)

Our full HIL (Hardware-in-the-Loop) test bench. This incorporated our SCS (safety critical signals), RES (Remote Emergency Stop), and our braking + steering-by-wire systems. It was run and fully actuated in parallel to simulation.

<img width="2798" height="1082" alt="Screenshot 2026-03-07 163937" src="https://github.com/user-attachments/assets/0ab0da5f-fa66-411e-a591-b1da6ad029c8" />
<video src="https://github.com/user-attachments/assets/46111e70-5f95-4a31-a63a-701ec362da08" width="600" controls></video>



---


### CottonCandy — LoRa Sensor Network
`May 2024 - August 2024`

Contributed to a self-forming multi-hop **LoRa** network for large-scale agricultural sensing.

- Built the downlink module on **Atmega328** for soil/air quality data collection across square kilometres
- Enabled async cloud transmission to **AWS** via **MQTT** using **FreeRTOS** multithreading
- Designed **LDO and load-switch circuits** for power management; ESP32 gateway ran off 2 AA batteries for months
<img width="651" height="531" alt="Screenshot 2026-03-07 151634" src="https://github.com/user-attachments/assets/cce432e1-d50a-45b6-97d4-1e3ece5ef0b2" />
<img width="303" height="348" alt="Screenshot 2026-03-07 151715" src="https://github.com/user-attachments/assets/1c7f85f1-5305-475b-a877-a13636d46ab8" />

Adapted from [this paper](https://www.techrxiv.org/doi/full/10.36227/techrxiv.20365050.v1), to explain the protocol.

<img width="2004" height="1418" alt="Screenshot 2026-03-07 152026" src="https://github.com/user-attachments/assets/c23db1b9-f189-4c08-a635-d2985dda3d0a" />

The uplink gateway (above schematic) was built in collaboration with a [capstone team](https://github.com/wintrmut3/ECE496Hardware).

---




## Projects

### Battery Management System with Passive Cell Balancing
`Altium · Embedded C++`

Designed a BMS for a 12V Li-ion pack with real-time SoC tracking and passive balancing.

- Designed board on **Altium** with voltage/current monitoring and **MOSFET-switched** shunt resistors
- Generated **OCV vs SoC** curve using **Coulomb-Counting**
- Wrote firmware for **Kalman Filters**, balancing logic, and **Digital Twin** battery profiles via a **Hall current sensor**

<img width="500" height="350" alt="image" src="https://github.com/user-attachments/assets/a86457cb-35d0-49fc-9eac-2ccbb727ab59" />
<img width="500" height="350" alt="image" src="https://github.com/user-attachments/assets/fac1865e-2639-49fd-bd6a-bb56210fd31d" />
<img width="1347" height="500" alt="image" src="https://github.com/user-attachments/assets/3ddc46f7-0ec0-42ad-8d16-2658f0b30936" />
<img width="1390" height="922" alt="image" src="https://github.com/user-attachments/assets/08c64106-c597-424f-aa0f-c0bc1d0a02c5" />

We used the **Chroma 17020 Cell Cycler** to characterize our batteries as an RC circuit.





---

## Skills

**Languages** &nbsp;
![C++](https://img.shields.io/badge/C%2FC%2B%2B-00599C?style=flat&logo=c%2B%2B)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![MATLAB](https://img.shields.io/badge/MATLAB-0076A8?style=flat)
![Verilog](https://img.shields.io/badge/Verilog-orange?style=flat)

**Frameworks & Tools** &nbsp;
![ROS2](https://img.shields.io/badge/ROS2-22314E?style=flat&logo=ros)
![FreeRTOS](https://img.shields.io/badge/FreeRTOS-8CC84B?style=flat)
![Altium](https://img.shields.io/badge/Altium-A5915F?style=flat)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)

---


<!---
N00dleMaster/N00dleMaster is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
