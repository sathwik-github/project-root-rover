# Bill of Materials (BOM) & Cost Tracking

One of ROOT's core design goals is achieving reliable indoor autonomous manipulation without high-cost sensors (e.g., 360° LiDAR or industrial depth cameras).

| Subsystem | Component | Qty | Purpose | Status | Est. Cost (INR) |
| :--- | :--- | :---: | :--- | :---: | :---: |
| **Compute** | Raspberry Pi 4 Model B | 1 | High-level vision, state machine & logging | Owned / Running | ₹0 (Existing) |
| **Control** | Microcontroller (Arduino Uno/Nano) | 1 | Real-time PWM motor & 3-DOF servo control | Pending Integration | ₹450 |
| **Vision** | Standard Raspberry Pi Camera Module | 1 | Monocular ArUco marker detection & alignment | Pending Integration | ₹800 |
| **Locomotion** | DC Gear Motors + Wheels + Motor Driver | 1 set | Differential drive indoor navigation | Pending Integration | ₹900 |
| **Manipulation** | 3-DOF Robotic Arm Servos (e.g., MG996R/SG90) | 3 | Joint actuation for soil-probe insertion | Pending Fabrication | ₹950 |
| **Sensing** | Capacitive Soil Moisture Sensor | 1 | Corrosion-resistant analog moisture measurement | Pending Integration | ₹150 |
| **Chassis** | Low-Cost 3D-Printed / Custom Frame | 1 | Structural base & arm mounts (CAD in progress) | CAD In Progress | ₹600 |
| **Power** | LiPo / Li-Ion Battery Pack + Buck Converter | 1 | 5V regulated Pi/servo power & motor supply | Pending Integration | ₹1,150 |
| **Total Estimated Build Cost** | | | | | **~₹5,000** |

*Note: Update exact prices, weights (grams), and current draw (mA) as physical components are finalized.*
