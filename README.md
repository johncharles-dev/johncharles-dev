## John Charles
 
AI/ML engineer in Singapore. Computer vision, multimodal and generative
models — including vision-language models and LLM-based systems — and the
evaluation behind them.
 
Most recently at **HTX**, Singapore's science and technology agency for public
safety, where I built an image-to-3D pipeline that produced 753 digital-twin
assets and cut asset creation from days of manual modelling to under a minute.
 
**Open to AI/ML engineering roles in Singapore.** Available immediately.
 
---
 
### What I've built
 
**[HTX-3D](https://github.com/johncharles-dev/HTX-3D)** — one interface over
several generative 3D models (TRELLIS, Hunyuan3D, SAM 3D), with interactive
segmentation and automatic metric scaling. Dimensional error cut from 77.5% to
24.6% MAPE; 305 generated models evaluated, the second batch scored blind, with
paired bootstrap confidence intervals.
 
**[Visual Grounding API](https://github.com/vincent-chengsheng-zheng/visual-grounding-api)**
— LLaVA-1.5-7B, an LLM-based vision-language model, LoRA-tuned with a
bounding-box regression head. Team project; I built the serving and deployment
layer (FastAPI, sequential loading of a 7B model under constrained VRAM, CUDA 12.8
port for Blackwell, docker-compose, CI) and owned the evaluation reporting.
 
**[Data Centre Digital Twin](https://github.com/johncharles-dev/Data_Center_Digital_Twin)**
— six interacting twins over MQTT, predicting CRAC cooling failure up to four
hours before conventional sensor thresholds trigger. Advisory-only, with a
hash-chained audit trail.
 
**[Trellis_Blackwell](https://github.com/johncharles-dev/Trellis_Blackwell)** —
TRELLIS ported to NVIDIA Blackwell (`sm_120`) before upstream supported it:
a custom SDPA attention backend, CUDA arch flags, float16 fixes and VRAM tiering.
 
**[HDB Resale Prediction](https://github.com/johncharles-dev/HDB-Resale-Price-Prediction-and-Recommendation)**
— hybrid XGBoost–Prophet model over 254K Singapore transactions, R² 0.94 and
$36K MAE. Team project; I sourced the data and built the model and backend.
 
---
 
### Working with
 
`PyTorch` `CUDA` `LLaVA (VLM fine-tuning)` `LoRA / PEFT` `LLM-based code analysis`
`TRELLIS` `Hunyuan3D` `SAM` `CLIP` `UniDepth` `OpenCV` `FastAPI` `Docker` `React`
`Three.js` `Linux`
 
Everything runs on a GPU server I built and administer myself — RTX 5090,
Ubuntu 24.04, CUDA 12.8, Docker with GPU passthrough, remote access.
 
---
 
[Portfolio](https://johncharles-dev.github.io) ·
[LinkedIn](https://www.linkedin.com/in/-john-charles) ·
johncharles.steve@gmail.com
