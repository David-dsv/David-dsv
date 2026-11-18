<table>
<tr><td>

<p align="right"><a href="https://www.linkedin.com/in/david-soeiro-vuong-a28b582ba/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn" height="24"></a> <a href="https://huggingface.co/Davidsv"><img src="https://img.shields.io/badge/Hugging%20Face-21262d?style=flat&logo=huggingface&logoColor=FFD21E" alt="Hugging Face" height="24"></a> <a href="https://arxiv.org/abs/2610.38042"><img src="https://img.shields.io/badge/arXiv-21262d?style=flat&logo=arxiv&logoColor=B31B1B" alt="arXiv" height="24"></a></p>

### 👋 Hey, I'm David

AI engineer in training (Data & AI at ECE Paris) and AI developer at Racine.ai. I build computer vision and LLM systems that run on real data: tennis video analytics, UI detection for computer-use agents, people detection from drone thermal cameras, retrieval for large document bases. Some of them became papers.

<p>
<a href="https://arxiv.org/abs/2610.38042"><img src="assets/oka.jpg" alt="Oka: court homography, player pose and ball detection on a club match" width="49%"></a>
<a href="https://huggingface.co/blog/paulml/ui-detr-1"><img src="assets/cu1.jpg" alt="CU-1: every clickable UI element detected and numbered" width="49%"></a>
<a href="https://arxiv.org/abs/2610.38042"><img src="assets/rallyarb.jpg" alt="RallyArb: ball trajectory with ground-truth and predicted bounces and hits" width="49%"></a>
<a href="https://arxiv.org/abs/2610.38042"><img src="assets/oka_report.jpg" alt="Oka: automatic match report with bounce map" width="49%"></a>
<a href="https://raw.githubusercontent.com/David-dsv/David-dsv/main/assets/thermal.jpg"><img src="assets/thermal.jpg" alt="AlpSAR: people detected in drone thermal video" width="98.6%"></a>
</p>

</td></tr>
<tr><td><b>research</b><br>

- **Can Event Detectors Leave the Broadcast Camera? Evidence from Tennis** · D. Soeiro-Vuong, A.-L. Rochet · arXiv 2026 · [paper](https://arxiv.org/abs/2610.38042) · [benchmark](https://github.com/David-dsv/tennis-bounce-hit-benchmark) (345 frame-exact bounce and hit events)
- **CU-1**, a class-agnostic RF-DETR detector of UI elements for computer-use agents, 70.8% on WebClick (+20% over the previous state of the art) · IEEE BigData 2025, co-author · [model](https://huggingface.co/racineai/UI-DETR-1)
- **AlpSAR** (in progress) · finding people in drone thermal video for mountain rescue. Baselines trained on real drone footage, synthetic RGB + thermal data in Unreal Engine 5 on the way, every model evaluated on real flights it never saw in training

<sub>Thermal frames in the showcase: <a href="https://sites.google.com/uw.edu/wisard">WiSARD</a> dataset (Broyles, Hayner and Leung, 2022).</sub>

</td></tr>
<tr><td><b>building</b><br>

- **Oka** · tennis analytics from a single club camera: fine-tuned YOLO26 ball detector (mAP50 0.94), Kalman tracking, pose, automatic court homography (line detection + RANSAC), 97x faster than real time on CPU, full stack on FastAPI, Supabase, Next.js and Modal
- **Retrieval for a major energy group** · OCR, fine-tuned Qwen3-Embedding-4B, Qwen3-VL reranking served on vLLM
- **Tender grading pipeline** · 1,000+ requirements scored by an LLM with hybrid retrieval (pgvector + full text, RRF) and NLI verification

</td></tr>
<tr><td><b>languages</b><br>
<img src="https://img.shields.io/badge/Python-21262d?style=flat&logo=python&logoColor=3776AB" alt="Python" height="24"> <img src="https://img.shields.io/badge/TypeScript-21262d?style=flat&logo=typescript&logoColor=3178C6" alt="TypeScript" height="24"> <img src="https://img.shields.io/badge/JavaScript-21262d?style=flat&logo=javascript&logoColor=F7DF1E" alt="JavaScript" height="24"> <img src="https://img.shields.io/badge/SQL-21262d?style=flat&logo=postgresql&logoColor=4169E1" alt="SQL" height="24">
</td></tr>
<tr><td><b>vision / ml</b><br>
<img src="https://img.shields.io/badge/PyTorch-21262d?style=flat&logo=pytorch&logoColor=EE4C2C" alt="PyTorch" height="24"> <img src="https://img.shields.io/badge/Ultralytics%20YOLO-21262d?style=flat&logo=ultralytics&logoColor=white" alt="Ultralytics YOLO" height="24"> <img src="https://img.shields.io/badge/RF--DETR-21262d?style=flat" alt="RF-DETR" height="24"> <img src="https://img.shields.io/badge/SAM%202-21262d?style=flat&logo=meta&logoColor=0467DF" alt="SAM 2" height="24"> <img src="https://img.shields.io/badge/Hugging%20Face-21262d?style=flat&logo=huggingface&logoColor=FFD21E" alt="Hugging Face" height="24">
</td></tr>
<tr><td><b>llm / agents</b><br>
<img src="https://img.shields.io/badge/vLLM-21262d?style=flat" alt="vLLM" height="24"> <img src="https://img.shields.io/badge/Qwen3-21262d?style=flat" alt="Qwen3" height="24"> <img src="https://img.shields.io/badge/RAG%20%2B%20reranking-21262d?style=flat" alt="RAG + reranking" height="24"> <img src="https://img.shields.io/badge/LangChain-21262d?style=flat&logo=langchain&logoColor=white" alt="LangChain" height="24"> <img src="https://img.shields.io/badge/Gemini-21262d?style=flat&logo=googlegemini&logoColor=8E75B2" alt="Gemini" height="24">
</td></tr>
<tr><td><b>frontend</b><br>
<img src="https://img.shields.io/badge/Next.js-21262d?style=flat&logo=nextdotjs&logoColor=white" alt="Next.js" height="24"> <img src="https://img.shields.io/badge/React-21262d?style=flat&logo=react&logoColor=61DAFB" alt="React" height="24">
</td></tr>
<tr><td><b>infra</b><br>
<img src="https://img.shields.io/badge/FastAPI-21262d?style=flat&logo=fastapi&logoColor=009688" alt="FastAPI" height="24"> <img src="https://img.shields.io/badge/Postgres%20%2B%20pgvector-21262d?style=flat&logo=postgresql&logoColor=4169E1" alt="Postgres + pgvector" height="24"> <img src="https://img.shields.io/badge/Supabase-21262d?style=flat&logo=supabase&logoColor=3FCF8E" alt="Supabase" height="24"> <img src="https://img.shields.io/badge/Celery-21262d?style=flat&logo=celery&logoColor=37814A" alt="Celery" height="24"> <img src="https://img.shields.io/badge/Docker-21262d?style=flat&logo=docker&logoColor=2496ED" alt="Docker" height="24"> <img src="https://img.shields.io/badge/Modal-21262d?style=flat" alt="Modal" height="24"> <img src="https://img.shields.io/badge/AWS%20S3-21262d?style=flat&logo=amazons3&logoColor=569A31" alt="AWS S3" height="24"> <img src="https://img.shields.io/badge/Azure-21262d?style=flat" alt="Azure" height="24">
</td></tr>
</table>
