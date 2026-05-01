# Parallel Inference Engine for Autonomous Disaster Drones

A research-based computer architecture proposal for real-time, low-power, and fault-tolerant CNN inference on autonomous disaster-response drones.

## About the Paper

Disaster-response drones must process aerial imagery quickly while operating with limited power, unreliable connectivity, and possible hardware failures.

This paper proposes a lightweight onboard architecture combining:

- ARM-based control and preprocessing
- A RISC-V SPMD inference array
- Shared-memory CNN weight reuse
- Tile-based parallel processing
- ECC, spare cores, and graceful degradation
- Rescue and energy-saving survey modes

The design targets real-time inference below 150 ms per frame while maintaining a power budget below 2 W.

## Read the Paper

[View the full research paper](paper/Parallel_Inference_Engine_for_Autonomous_Disaster_Drones.pdf)

## Key Topics

`Computer Architecture` · `SPMD` · `RISC-V` · `CNN Acceleration` · `Memory Hierarchy` · `Fault Tolerance` · `Autonomous Drones`

## Paper Information

- **Course:** CSE340 — Computer Architecture
- **Assessment:** Research-Based Assessment
- **Semester:** Spring 2026
- **Author:** Roza Akter
- **Submitted:** May 1, 2026
- **Institution:** BRAC University

## Citation

Akter, R. (2026). *Parallel Inference Engine for Autonomous Disaster Drones*. Research-Based Assessment, BRAC University.

## Note

This paper presents a literature-informed architectural proposal. The stated performance values are design estimates rather than measurements from a fabricated hardware prototype.
