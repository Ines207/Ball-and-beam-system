# Ball-and-beam-system

This project implements a **Ball and Beam control system** using **LabVIEW**, a classic example in control theory where the goal is to balance a ball at a desired position on a beam by adjusting the beam angle. The system is a benchmark for testing feedback control strategies, especially **PID control**.


##  Tools 

- LabVIEW for simulation, UI, and control logic
- PID Controller implemented in LabVIEW
- Solidworks for the mechanical design
- Proteus for the electrical design

## System Description

The Ball and Beam system consists of:
- A horizontal beam that can rotate slightly up or down
- A ball that rolls on the beam due to gravity
- A control algorithm that adjusts the beam angle to keep the ball at a desired position

The main challenge is that the system is open-loop unstable , and requires continuous feedback to stabilize the ball.

## Control Algorithm

- Controller Type:PID (Proportional-Integral-Derivative)
- Feedback Variable: Ball position on the beam calculated by the sensor
- Control Variable: Beam angle (actuated using a motor)
- Goal: Minimize the error between desired and actual position




