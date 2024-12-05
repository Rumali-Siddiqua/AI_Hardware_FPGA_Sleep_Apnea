# AI_Hardware_Project

## Team Name: 
Team Sleep_Apnea

## Team Members:
- Alexander Osei-Bonsu
- Rumali Siddiqua
- Mehedi Hasan

## Project Title:
An Energy-Efficient FPGA-Based Sleep Apnea Detection System

## Project Description:
This project addresses the prevalent issue of sleep apnea, a disorder causing interruptions in breathing during sleep, which impacts health significantly. The project focuses on developing an energy-efficient hardware system for real-time detection of sleep apnea using EEG signals. By leveraging specific EEG signal features and a Linear Support Vector Machine (LSVM) classifier, the system aims to provide high accuracy, sensitivity, and specificity while maintaining low power consumption.

## Key Objectives:
- Implement a low-power hardware design optimized for minimal dynamic power consumption
- Achieve latency reduction to enable real-time processing of EEG signals for immediate detection and feedback
- Minimize the utilization of FPGA resources (e.g., LUTs, slice registers, DSPs) while maintaining performance to allow cost-effective implementations

## Technology Stack:
Hardware: NEXYS 4 Equipped with Xilinx Artix-7 FPGA

Software Tools: MATLAB, Xilinx Vivado Design Suite

Classifier: Linear Support Vector Machine (LSVM)

## Expected Outcomes:
- A functional prototype of an FPGA-based apnea detection system demonstrating real-time operation
- Detailed Performance metrics including accuracy, sensitivity, and resource utilization

## Timeline:
Phase 1: Literature Review & Data Preparation

Phase 2: Software Simulation
- Implement preprocessing, feature extraction, and LSVM classification in MATLAB.
- Optimize feature selection for high accuracy.

Phase 3: Hardware Implementation
- Map optimized LSVM parameters onto the FPGA board.
- Validate feature extraction and classifier hardware blocks.

Phase 4: Testing and Validation
- Evaluate system performance on test datasets.
- Measure hardware metrics like power consumption and resource utilization.
