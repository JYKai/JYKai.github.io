# JYK Lab – Vision & Agent-based Robotics Automation

This repository hosts my personal engineering log and portfolio site:

➡ https://JYKai.github.io

I document real-world failures and recovery processes in **vision-guided robotic automation systems** and explore **agent-based workflows** for reliable operation.

---

## Who I am

I am Jiyun Kim (JYK), an engineer focusing on:

- vision-guided robotic manipulation
- ROS2-based system integration
- failure-aware automation design
- agentic workflows using LLMs (LangChain / LangGraph)

My background includes:
- M.S. in Computer Vision / AI
- hands-on robotics system integration in real environments
- multi-agent workflow design for industrial automation

---

## What this site is about

This site is not a tutorial blog.

It is a **field engineering log** that focuses on:

- what actually fails in real robotic systems
- how those failures were diagnosed
- what was changed
- and what finally worked

Every post aims to be:
- reproducible
- environment-specific
- and grounded in real execution

---

## Main topics

- Vision-guided picking and manipulation (YOLO → 3D pose → grasp)
- Camera–robot calibration and coordinate transforms (TF, hand–eye)
- ROS2 navigation and mobile robots (TurtleBot3, Nav2)
- MoveIt2 motion planning and execution
- Failure analysis and recovery strategies
- Agent-based experiment orchestration and reporting (LangChain / LangGraph)

---

## Current projects

### 1. Vision-guided robotic picking PoC
- object detection with YOLO
- depth-based 3D target localization
- hand–eye calibration
- grasp execution and failure logging

### 2. ROS2 navigation practice with TurtleBot3
- localization and mapping
- TF debugging
- parameter tuning under real sensor noise

### 3. Video / lecture Q&A agent
- video URL or file ingestion
- transcript / STT processing
- question answering with timestamp references
- built using LangChain and LangGraph

---

## Why I publish failures

In automation systems, performance metrics alone are not enough.

What matters in real deployments is:

- how systems fail
- how often they fail
- and how quickly they recover

This repository and blog focus on building
**failure-aware and recovery-oriented automation systems.**

---

## Contact

If you are interested in collaboration, automation PoCs, or technical discussions:

- GitHub: https://github.com/JYKai
- Email: noahyun1222@gmail.com

---

## Tech stack

- ROS2 (Jazzy)
- OpenCV / PyTorch
- AI Vision
- LangChain / LangGraph
- Python
- Linux (Ubuntu 24.04)

---

## License

The content of this repository is published under the MIT License unless otherwise stated.