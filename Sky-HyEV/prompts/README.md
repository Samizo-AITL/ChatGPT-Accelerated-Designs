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

## 📄 `Sky-HyEV/prompts/Prompt_Collection.md`（English）


## Sky-HyEV Prompt Template Collection

Below is a list of prompt templates created for each model and module of the Sky-HyEV project.

| ID  | Model        | Module              | Prompt ID              | Main Deliverables                           |
|------|--------------|---------------------|------------------------|--------------------------------------------|
| 01   | Standard     | AI Control Chip     | AI_control_std_v0.1    | Block diagram, performance table, function list |
| 02   | Standard     | Sensor Control      | sensor_ctrl_std_v0.1   | Sensor connection diagram, control flow, calibration method |
| 03   | Standard     | Communication IF    | comm_if_std_v0.1       | Interface list, timing chart                |
| 04   | Professional | AI Control Chip     | AI_control_pro_v0.1    | Block diagram, performance metrics, AI task mapping |
| 05   | Professional | Camera Module       | camera_pro_v0.1        | Configuration diagram, LVDS spec, image quality evaluation |
| 06   | Professional | MRAM                | mram_pro_v0.1          | Memory configuration diagram, access profile, reliability evaluation |
| 07   | Military     | AI Control Chip     | AI_control_mil_v0.1    | Redundancy diagram, security spec, performance table |
| 08   | Military     | Sensor & Camera     | sensor_cam_mil_v0.1    | Optical configuration, infrared range, fusion algorithm overview |
| 09   | Military     | PoC / Education Mode| poc_mode_mil_v0.1      | Education mode configuration, debug IF, scenarios |

*This is a representative subset.*  
Please refer to the files under `/Sky-HyEV/prompts/` for the full set.
