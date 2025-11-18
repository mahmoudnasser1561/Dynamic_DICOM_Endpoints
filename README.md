# Dynamic_DICOM_Endpoints
this is a dynamic DICOM endpoint system that intelligently routes medical
imaging data based on real-time performance metrics (latency, queue depth,bandwidth utilization, and server load) to dynamically select
optimal transmission paths for DICOM data.

This system will:
1. Reduce transmission delays for faster diagnosis.
2. Improve resource utilization through intelligent workload balancing.​
3. Enhance system resilience against network fluctuations.​
4. Support multi-site healthcare operations, optimizing teleradiology workflows.

At the end of this workflow, the anonymized metadata stored in the database will will be used for training medical machine-learning models, enabling continuous improvement in diagnostic accuracy and system intelligence.

<img width="2631" height="1391" alt="updated_system" src="https://github.com/user-attachments/assets/f6f56462-344a-456a-85b4-03c08a6d95bb" />

---
The system will be implemented using a containerized development approach with
Docker Compose, allowing for consistent, reproducible environments and simplified component isolation.

As shown in the diagram, each system component runs in its own Docker container
within a shared virtual network.

<br>

<img width="2784" height="1217" alt="vpn drawio" src="https://github.com/user-attachments/assets/c9495a20-c910-4a05-af0a-e4cddc5a2b4c" />
