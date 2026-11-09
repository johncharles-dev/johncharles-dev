## John Charles

AI/ML engineer in Singapore. Computer vision, multimodal and generative
models — including vision-language models and LLM-based systems — and the
evaluation behind them.

Most recently at **HTX**, Singapore's science and technology agency for public
safety, where I built an image-to-3D pipeline that produced 753 digital-twin
assets and cut asset creation from days of manual modelling to 10–75 seconds.

**Open to AI/ML engineering roles in Singapore.** Available immediately.

---

### What I've built

**[SceneSense](https://github.com/johncharles-dev/scenesense)** — urban scene
understanding on Singapore and Boston driving video, from detection to an LLM
agent you can question. RT-DETR detection with ByteTrack tracking, and YOLO11 on
TensorRT at 0.62 ms/frame; Qwen2-VL-2B fine-tuned for grounded visual questions
(59.0% to 75.1%), served on vLLM; a tool-calling Qwen2.5-14B agent with RAG over
the tracking logs that refused 9/9 unanswerable questions vs 5/9 for a 7B
baseline. Served through FastAPI and docker-compose.

**[HTX-3D](https://github.com/johncharles-dev/HTX-3D)** — one interface over
several generative 3D models (TRELLIS, Hunyuan3D, SAM 3D), with interactive
segmentation and automatic metric scaling. Dimensional error cut from 77.5% to
24.6% MAPE; 305 generated models evaluated, the second batch scored blind, with
paired bootstrap confidence intervals.

**[Visual Grounding API](https://github.com/johncharles-dev/visual-grounding-api)**
— LLaVA-1.5-7B, an LLM-based vision-language model, LoRA-tuned with a
bounding-box regression head. Team project; I built the serving and deployment
layer (FastAPI, sequential loading of a 7B model under constrained VRAM, CUDA 12.8
port for Blackwell, docker-compose, CI) and owned the evaluation reporting.

**[Data Centre Digital Twin](https://github.com/johncharles-dev/Data_Center_Digital_Twin)**
— six interacting twins over MQTT, with a classifier on eleven CRAC signals that
gave 1.5x more warning of cooling failure than the room's threshold rules
(median 292 vs 195 minutes). Advisory-only, with a hash-chained audit trail.

**[HDB Resale Prediction](https://github.com/johncharles-dev/HDB-Resale-Price-Prediction-and-Recommendation)**
— hybrid XGBoost–Prophet model over 254K Singapore transactions, R² 0.94 and
$36K MAE. Team project; I sourced the data and built the hybrid model.

---

### Working with

`PyTorch` `CUDA` `RT-DETR` `YOLO` `TensorRT` `Qwen2-VL` `LoRA / PEFT` `vLLM`
`RAG / Chroma` `LLM agents` `TRELLIS` `Hunyuan3D` `SAM` `CLIP` `UniDepth`
`OpenCV` `FastAPI` `Docker` `React` `Three.js` `Linux`

Everything runs on a GPU server I built and administer myself — RTX 5090,
Ubuntu 24.04, CUDA 12.8, Docker with GPU passthrough, remote access.

---

[Portfolio](https://johncharles-dev.github.io) ·
[LinkedIn](https://www.linkedin.com/in/-john-charles) ·
johncharles.steve@gmail.com
