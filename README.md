# Dynamic_DICOM_Endpoints
this is a dynamic DICOM endpoint system that intelligently routes medical
imaging data based on real-time performance metrics (latency, queue depth,bandwidth utilization, and server load) to dynamically select
optimal transmission paths for DICOM data.

This system will:
1. Reduce transmission delays for faster diagnosis.
2. Improve resource utilization through intelligent workload balancing.​
3. Enhance system resilience against network fluctuations.​
4. Support multi-site healthcare operations, optimizing teleradiology workflows.

<img width="2631" height="1441" alt="Arch" src="https://github.com/user-attachments/assets/693265a3-1d3f-411d-9253-3a0fc6ff2a82" />

---
The system will be implemented using a containerized development approach with
Docker Compose, allowing for consistent, reproducible environments and simplified component isolation.

As shown in the diagram, each system component runs in its own Docker container
within a shared virtual network.

<br>

<img width="2506" height="1096" alt="dockerCompose" src="https://github.com/user-attachments/assets/60091352-c872-4700-8da0-f4663b8a367a" />
