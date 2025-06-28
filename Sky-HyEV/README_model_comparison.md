# Sky-HyEV Model Comparison & Design Philosophy

## Overview  
This document summarizes and compares the three main Sky-HyEV models — Standard, Professional, and Military — focusing on their design goals, targeted applications, and architectural differences. It also outlines the AI-accelerated workflow used to generate their detailed specifications rapidly.

## 1. Model Summary

| Model         | Target Use Case                   | Process Node       | Key Features                                   | Focus Points                                   |
|---------------|---------------------------------|--------------------|-----------------------------------------------|-----------------------------------------------|
| Standard      | Entry-level, cost-sensitive EVs | 65nm or similar     | Basic AI control, standard sensors, communication interfaces | Cost efficiency, power/performance balance    |
| Professional  | Mid-to-high-end EVs              | 28nm FD-SOI        | Advanced AI chip, MRAM integration, PoC support | Real-time inference, MRAM endurance, PoC deployment |
| Military      | High-reliability defense systems| 28nm FD-SOI, hardened | Secure boot, EMP tolerance, redundant control | High reliability, fail-safe, environmental robustness |

## 2. Architectural Differences

- **AI Control Chip**  
  - Standard: Focus on 65nm CMOS, basic AI workloads  
  - Professional: RISC-V-based TPU cores with MRAM for model persistence  
  - Military: Hardened design with security and redundancy features

- **Sensors & Cameras**  
  - Standard: General-purpose sensors (9-axis, temp, pressure)  
  - Professional: High precision MEMS, fusion algorithms  
  - Military: Visible + IR dual sensors, robust to extreme conditions

- **Communication Interfaces**  
  - Standard: UART/I2C/SPI/USB, focus on ease of use  
  - Professional: High-speed, multi-protocol with debug and PoC modes  
  - Military: Secure, redundant, anti-jamming capable

## 3. AI-Accelerated Design Workflow

- Modular prompt templates created per module and model  
- Iterative ChatGPT-driven drafting and refinement  
- Rapid generation of consistent specification documents  
- Integration of domain knowledge and PoC considerations

## 4. Benefits & Impact

- Significant reduction in specification authoring time  
- Enhanced consistency and repeatability in design docs  
- Enables quick adaptation to evolving design requirements  
- Supports educational and prototype development activities
