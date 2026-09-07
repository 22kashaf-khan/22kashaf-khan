<div align="center">

# Kashaf Khan

### Robot Learning & Simulation · Isaac Lab · MuJoCo · PPO · Sim-to-Real · Berlin, Germany

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/kashaf-khan2000)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:22kashaf.khan@gmail.com)

</div>

---

I build and validate learned controllers for humanoid robots in simulation.

Currently writing my M.Sc. thesis with **Fraunhofer IEM** on Digital Twin-supported reinforcement learning for a humanoid robot: URDF/USD asset pipeline, PPO training in Isaac Lab, and sim-to-real transfer. Alongside that I work as an AI Solutions Consultant at **Siemens Mobility**, benchmarking and prototyping LLM systems for enterprise use.

Most of my public work is about a question I find more interesting than "can it walk": **how does a learned controller behave when the model, the contact parameters, or the training objective change, and how do you measure that reproducibly?**

---

## Selected Work

| Project | What it is | Stack |
|---|---|---|
| **[Humanoid Simulation Robustness Benchmark](https://github.com/22kashaf-khan/humanoid-simulation-robustness-benchmark)** | Trained and froze a Unitree H1 PPO locomotion policy, then built an independent benchmark around it: friction, mass, and actuator-effort perturbations across 5 seeds. 95 runs, 9,500 episodes, 44 tests, CI. Includes a custom mechanical-power reward and a matched A/B study: 43.9% power reduction at unchanged survival, but *worse* robustness under friction and mass mismatch. | Isaac Lab · RSL-RL · PPO · PyTorch · pytest · GH Actions |
| **[MuJoCo Contact & Actuator Playground](https://github.com/22kashaf-khan/mujoco-contact-actuator-playground)** | A 2-link leg written from raw MJCF, used to work through contact solver tuning (`solref`), position vs. velocity vs. torque actuators, and sensor logging. Written up as findings, including the ones that turned out to be modelling mistakes. | MuJoCo · MJCF · Python |
| **[Scholar Multimodal RAG](https://github.com/22kashaf-khan/Scholar-Multimodal-RAG)** | Retrieval pipeline over scientific papers: hybrid dense/sparse retrieval, table-aware PDF ingestion, cross-encoder reranking, RAGAS evaluation. | Weaviate · LangChain · FastAPI · Docker |

---

## Stack

**Simulation & RL**

![Isaac Sim](https://img.shields.io/badge/NVIDIA_Isaac_Sim-76B900?style=flat-square&logo=nvidia&logoColor=white)
![Isaac Lab](https://img.shields.io/badge/Isaac_Lab-76B900?style=flat-square&logo=nvidia&logoColor=white)
![MuJoCo](https://img.shields.io/badge/MuJoCo-1a1a1a?style=flat-square&logoColor=white)
![RSL-RL](https://img.shields.io/badge/RSL--RL-4B5563?style=flat-square&logoColor=white)
![PPO](https://img.shields.io/badge/PPO-4B5563?style=flat-square&logoColor=white)
![Gymnasium](https://img.shields.io/badge/Gymnasium-0081A5?style=flat-square&logoColor=white)
![USD](https://img.shields.io/badge/USD_/_URDF-005F9E?style=flat-square&logoColor=white)

**ML / DL**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-189fdd?style=flat-square&logoColor=white)

**Engineering**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white)

**LLM Systems**

![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![Weaviate](https://img.shields.io/badge/Weaviate-00C9A7?style=flat-square&logoColor=white)
![RAGAS](https://img.shields.io/badge/RAGAS-6E56CF?style=flat-square&logoColor=white)
![QLoRA](https://img.shields.io/badge/PEFT_/_QLoRA-FF6B6B?style=flat-square&logoColor=white)

---

## Background

**M.Sc. Artificial Intelligence**, BTU Cottbus-Senftenberg, 2023-2026  
**B.Sc. Software Engineering**, SSUET Karachi

Before robotics: three years of production ML. Computer vision and NLP models at Hackerspace Karachi, LLM-powered customer support at Daraz (Alibaba Group), and an AI/IoT waste-segregation startup that won the National Idea Bank 2022.

---

Side project: I built an [AI twin](https://22kashaf-khan.github.io) you can ask about my work. Gemini, Vercel, GitHub Pages.

---

<div align="center">

Open to robotics and RL engineering roles in Germany and Europe.
Happy to talk about locomotion, evaluation methodology, or anything sim-to-real.

**[22kashaf.khan@gmail.com](mailto:22kashaf.khan@gmail.com)**

</div>
