<div align="center">

# Trung M. Bui, PhD

**Computer Vision · Robotics · Multimodal AI Engineer — Production & Embodied AI Systems**

Morgan Hill, CA &nbsp;·&nbsp; 🟢 U.S. Green Card &nbsp;·&nbsp; Open to ML Engineer / Robotics AI / Embodied AI roles

[![Email](https://img.shields.io/badge/bmtrungvp%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:bmtrungvp@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/trung-m-bui-244562160)
[![Website](https://img.shields.io/badge/aistations.org-111111?style=flat-square&logo=safari&logoColor=white)](https://aistations.org)
[![Scholar](https://img.shields.io/badge/Google%20Scholar-40%2B%20citations-4285F4?style=flat-square&logo=googlescholar&logoColor=white)](https://scholar.google.com/citations?user=1UB5mFQAAAAJ&hl=en)

</div>

---

**7+ years** shipping production robotic AI at **KETI** (Korea Electronics Technology Institute). Builds the full perception stack — detection, segmentation, 6D pose estimation, multi-object tracking — and integrates **VLMs, LLMs, and VLA policies** into grounded, multi-step robot execution. From research paper to Jetson deployment.

---

## ⚡ Production Highlights

|   | Achievement | Numbers |
|---|-------------|---------|
| 🏭 | **Industrial bin-picking** — end-to-end perception pipeline | 70% → **92% success** in cluttered scenes · **30+ FPS on Jetson AGX** (TensorRT INT8) · **3+ years in production** across multiple sites |
| 🦾 | **MARS** — 7-DOF mobile manipulation system (Ubiquitous Robots 2025) | 4-layer ROS2 architecture · hybrid gripper · RGB-D perception · LLM task planning + Skill Controller with hierarchical retry |
| 🤖 | **VLA manipulation** — Franka Panda on Isaac Lab + MuJoCo | **98.75% on LIBERO** (exceeds OpenVLA-OFT paper baseline of 97.1%) · 100% Spatial / Object / Goal · 95% Long |
| 👁️ | **Fine-aware ViT** — precision grasp pose detection (IEICE 2025) | **20% precision improvement** over CNN · trained on 200K+ annotations · deployed on Jetson at 30+ FPS |
| 🔁 | **Multi-object tracking** — 4 trackers from scratch | **11× fewer ID switches** vs DeepSORT on MOT17-val · SORT · DeepSORT · ByteTrack · custom |
| ⚙️ | **C++ ML kernels** — from scratch, no Eigen | **14× GEMM speedup** · naive → cache-blocked → tiled → AVX2+FMA SIMD |

---

## 🔬 Featured Repos

| Repo | What it is | Stack | Key result |
|------|-----------|-------|------------|
| [**robot_sim_vla**](https://github.com/mtbui2010/robot_sim_vla) | VLA policy benchmarking on Franka Panda (Isaac Lab + MuJoCo) + classical 3D CV from scratch: hand-eye calibration, PnP, ICP | Python · Isaac Sim 4.5 · MuJoCo · OpenVLA-OFT · LeRobot | **98.75% LIBERO** |
| [**vision_tracking**](https://github.com/mtbui2010/vision_tracking) | SORT · DeepSORT · ByteTrack · custom tracker from scratch — Kalman, Hungarian, ReID — + FastAPI + Next.js UI with side-by-side comparison | Python · TypeScript · YOLOv11 · OSNet · Docker · Vercel | **11× fewer ID switches** |
| [**cpp-ml-system**](https://github.com/mtbui2010/cpp-ml-system) | ML/CV/Robotics in C++17 — GEMM variants, im2col CNN, NMS, Kalman/EKF, PID, point cloud; no external ML libs | C++17 · AVX2/FMA · CMake · GoogleTest | **14× GEMM speedup** |
| [**carerobotagent**](https://github.com/mtbui2010/carerobotagent) | LangGraph multi-agent care robot — Whisper STT, intent routing, task planning, ROS2 execution, auto-replan, dual memory | LangGraph · LangChain · AI2-THOR · SQLite · ChromaDB · Streamlit | Full MARS stack |
| [**pyplanner**](https://github.com/mtbui2010/pyplanner) | Pluggable LLM planning library — 7 methods (CoT, ReAct, Self-Refine, Hierarchical, LLM Router…) — AI2-THOR benchmark · [live demo ↗](https://demo-planner.aistations.org) | Python · OpenAI · Anthropic · Ollama | 7 planning methods |
| [**groundingdino_tool**](https://github.com/mtbui2010/groundingdino_tool) | Semi-auto labeling: GroundingDINO → FastSAM → human verify → YOLOv8 fine-tune loop; targets long-tail | Python · Streamlit · GroundingDINO · FastSAM | Active learning |
| [**Single-Image-Dehazing**](https://github.com/mtbui2010/Single-Image-Dehazing-using-Color-Ellipsoid-Prior) | PhD research — Color Ellipsoid Prior for single-image dehazing | Python | IEEE TIP 2018 · **32 citations** |

---

## 🛠️ Tech Stack

**Perception & Computer Vision**
```
PyTorch · OpenCV · RGB-D · 6D Pose Estimation · Multi-Object Tracking · Vision Transformers
TensorRT · ONNX · CUDA · INT8 Quantization · 30+ FPS edge inference
```

**Robotics & Manipulation**
```
ROS2 / ROS · MoveIt2 · Nav2 · Mobile Manipulation · Bin-Picking · Grasp Planning
Skill Controllers (hierarchical retry) · Hand-Eye Calibration · Point Clouds
```

**Multimodal AI & LLM Agents**
```
LangGraph · LangChain · VLA: OpenVLA-OFT · LeRobot Diffusion Policy
VLMs: CLIP · BLIP · LLaVA · GroundingDINO · Gemini Vision
RAG Pipelines · Tool-Use Agents · Episodic + Semantic Memory (SQLite + ChromaDB)
```

**Simulation & Training**
```
Isaac Lab / Isaac Sim 4.5 · MuJoCo · AI2-THOR · LIBERO
Dataset curation · Active learning · Distributed training · Evaluation harnesses
```

**Languages & Infrastructure**
```
Python (expert) · C++17 · TypeScript · C
Docker · FastAPI · Next.js · Streamlit · Vercel · RunPod serverless GPU
```

---

## 📄 Publications

| Year | Title | Venue | Citations |
|------|-------|-------|-----------|
| 2025 | [**A Fine-Aware Vision Transformer for Precision Grasp Pose Detection**](https://www.jstage.jst.go.jp/article/transinf/E108.D/11/E108.D_2024EDP7261/_article) | *IEICE Transactions on Information and Systems* | — |
| 2025 | **Development of a Mobile Assistive Robot for Daily Living Support** | *Ubiquitous Robots* | — |
| 2018 | **Single Image Dehazing Using Color Ellipsoid Prior** | *IEEE Transactions on Image Processing* **(Q1)** | **32** |
| 2014 | **Segmenting Dark Channel Prior in Single Image Dehazing** | *IET Electronics Letters* | 5 |

---

## 💼 Experience

**Senior Computer Vision, Robotics & AI Engineer**  
Korea Electronics Technology Institute (KETI) · Seongnam, South Korea · Mar 2019 – Present

- Led production **bin-picking system**: 70% → 92% success, 30+ FPS on Jetson AGX (TensorRT INT8), **3+ years deployed** across multiple sites, hundreds of items/hour
- Architected **MARS**: 7-DOF arm + hybrid gripper on 4-layer ROS2 — WebRTC frontend → LLM Task Manager → Skill Controller (hierarchical retry) → Hardware
- Designed **Fine-aware ViT**: 20% precision improvement over CNN, 200K+ annotations, custom augmentation
- Integrated **VLMs** (CLIP, BLIP, LLaVA, GroundingDINO, Gemini Vision) for zero-shot recognition; RAG pipelines over internal knowledge bases
- Built **LangGraph multi-agent orchestration** with structured outputs grounded in robot skill affordances; episodic + semantic memory (SQLite + ChromaDB)
- Optimized inference for edge with TensorRT, ONNX, INT8 — **sub-200ms perception-to-action latency**
- **Mentored 3 junior engineers**; led national R&D projects with **multi-million USD funding**

---

## 🎓 Education

| Degree | Institution | Years |
|--------|------------|-------|
| **Ph.D., Computer Vision** | Kyung Hee University, South Korea | 2014 – 2019 |
| **M.Eng., Computer Vision** | Kyung Hee University, South Korea | 2011 – 2014 |
| **B.Eng., Electrical & Electronics** | HCMC University of Technology, Vietnam | 2005 – 2010 |

*Ph.D. thesis: basis of IEEE TIP 2018 publication — 32 citations*

---

<div align="center">

📬 **bmtrungvp@gmail.com** &nbsp;·&nbsp; 📞 **+1 (669) 326-2460** &nbsp;·&nbsp; 📍 **Morgan Hill, CA · U.S. Green Card**

</div>
