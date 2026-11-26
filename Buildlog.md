# ROOT Engineering Build Log

A chronological record of design decisions, software/hardware iterations, debugging bottlenecks, and benchmark tests.

---

## Entry 01 — 26 November 2026
**Phase:** Software Foundation & Navigation Simulation Setup  
**Author:** Autonomy & Controls Lead  

### Objective
Establish the core compute environment on the Raspberry Pi 4 and initialize the navigation workspace to validate virtual waypoint navigation before integrating physical motors and cameras.

### Progress Completed
* Configured Raspberry Pi 4 operating system and remote development workflow.
* Created structured navigation workspace and repository architecture.
* Initiated Python virtual environment setup for simulation and computer vision dependencies (`numpy`, `opencv-python`).
* **Mechanical Parallel Track:** Co-builder initiated 3D CAD modeling of the base chassis and 3-DOF arm geometry with a focus on minimizing material and actuator cost.

### Current Bottlenecks & Open Issues
* Python environment configuration is still underway; virtual rover waypoint navigation has not yet been confirmed working.
* Camera localization (`OpenCV/ArUco`), Arduino motor firmware, and physical fabrication remain pending until simulation logic is verified.

### Next Milestone
1. Finalize Python dependencies and confirm virtual rover navigation to a target coordinate `(x, y)` and return to `(0, 0)` in simulation.
2. Capture screen recording and trajectory plot of the successful virtual run before starting OpenCV ArUco camera integration.
