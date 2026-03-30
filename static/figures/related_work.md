| Method | Date | State Representation | Model Architecture | Physical Prior | Real Data Dependency | Deformable Dynamics | Spatially Varying Properties |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| **VPD [1]** | 2023.12 | 3D latent particles | Graph Neural Networks | None (Data-driven) | High (Multi-view RGB-D videos) | Yes | No (Implicit) |
| **HD-VPD [2]** | 2024.06 | Dense 3D latent particles | Point Cloud Transformer | None (Data-driven) | High (Large-scale bi-manual interaction data) | No | No (Implicit) |
| **3DGSim [3]** | 2025.08 | 3DGS | Transformer | None (Data-driven) | High (Multi-view RGB videos) | Yes | No (Implicit) |
| **GWM [4]** | 2025.09 | 3DGS | Diffusion Transformer | None (Data-driven) | High (Massive offline trajectories) | No | No (Implicit) |
| **PointWorld [5]** | 2026.01 | 3D Point Flows | Point Transformer v3 | None (Data-driven) | High (~2M real & sim trajectories) | Yes | No (Implicit) |
| **GaussTwin [6]** | 2026.03 | Particles bonded to 3DGS | PBD Simulator | Explicit (PBD + Cosserat rod)| Low (Online visual correction) | Yes | No (Assumes known/uniform) |
| **PhysWorld (Ours)**| **2026.03** | **3D Points** | **Graph Neural Networks** | **Explicit (MPM)**| **Low (Multi-view RGB-D videos under 10s)** | **Yes** | **Yes (Explicitly modeled)**|