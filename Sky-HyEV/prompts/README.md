# Prompt Engineering for Sky-HyEV Specification Generation

This directory contains the **prompt templates** used to rapidly generate detailed design specifications for the Sky-HyEV project using ChatGPT.

## Background

- Created to provide clear, structured instructions to ChatGPT per module
- Each template covers module name, target model (Standard/Professional/Military), expected scope, deliverables, and key focus points
- Highly reusable and adaptable for similar modules

## Usage

1. Copy the desired prompt template and input it into ChatGPT
2. Review and edit the generated response to finalize the specification
3. Adjust parameters and regenerate as needed

## Sample Excerpt

```text
Please create a design specification for the AI control chip (28nm FD-SOI) of the Sky-HyEV Professional Model v0.1. Consider PoC deployment.
■ Scope: Architecture structure, performance, power consumption, MRAM integration
■ Deliverables (priority order): ① Block diagram ② Performance indicators ③ AI task mapping
■ Key focus points: Real-time inference capability, MRAM rewrite endurance, low-latency control

See Prompt_Collection.md for the full list.
```
