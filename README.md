# Faiz Ali

**AI engineer.** Production LLM agents, computer vision, and the GPU infrastructure underneath them. IIT Madras.

I build AI systems that run on real work. At Centaq India I built the AI function from one workstation to a multi-GPU platform, and I now lead a small team shipping LLM agents to real clients.

## What I've built

- **Edward**: a tool-using LLM agent that interviews clients and files a structured creative brief into a partner's order workflow. Live on real orders. 25 typed tools, guardrails enforced in code, a fallback chain across four model providers, and an evaluation setup with simulated clients and regression checks.
- **AI infrastructure and vision models**: in-house models for portrait and face retouching, colour correction, hair removal and background removal. Multi-GPU training, TorchServe serving, and a production pipeline that processes 20,000+ images a day. Cut editing from 8-10 minutes per image to seconds.
- **SnapStand**: an on-device AI photobooth for iPad using CoreML.
- **Vissoo Portal**: a multi-tenant platform for creative collaboration and asset review.

## Open source

- **SeriousDB**: fixed write-ahead-log replay to reject corrupted entries, with regression tests. [Merged upstream (PR #344)](https://github.com/danieldeer/seriousdb/pull/344).
- **[InterviewGraph](https://github.com/PhaeezAli/interviewgraph)**: an open-source interview question bank, with a planned tool that predicts likely questions from a job description. In progress.

## Projects

- **[Multi-ball football tracking](https://github.com/PhaeezAli/football-multiball-tracking)**: tracks four balls through occlusion and labels possession from player pose. A YOLO11m detector distilled from Grounding DINO labels reaches 0.966 mAP50, and the write-up covers where the student beat the teacher.
- **[MethaneGuard](https://github.com/PhaeezAli/methane_guard)**: methane monitoring and leak localisation with a hybrid RAG copilot.
- **[Cricket biomechanics](https://github.com/PhaeezAli/cricket_biomech)**: real-time pose analysis extracting 20+ kinematic metrics from athlete motion.

## Tools

Python, PyTorch, FastAPI, TypeScript, PostgreSQL, Docker, Kubernetes, Azure, GCP. Gemini and open-weight models.

## Contact

[LinkedIn](https://www.linkedin.com/in/faiz-ali-510747151/)
