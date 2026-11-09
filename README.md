<div align="center">

# Azizbek Xajibayev

### AI Engineer & Systems Developer
**[https://zizx4um.github.io](https://zizx4um.github.io/)**

[![Portfolio Website](https://img.shields.io/badge/Portfolio%20Website-zizx4um.github.io-0ea5e9?style=flat-square)](https://zizx4um.github.io/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/azizbek-xajibayev-a8787226a/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/Zizx4uM)
[![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)](https://huggingface.co/ZaaX19)
[![Email](https://img.shields.io/badge/Email-khadjibayev65%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:khadjibayev65@gmail.com)

</div>

---

### Profile

AI Engineer and Systems Developer specializing in clinical Generative AI, edge TinyML systems, and GPU-accelerated computing. Experienced in fine-tuning medical foundation models (MedGemma, MedSAM, BiomedCLIP), deploying quantized vision networks to microcontrollers, and building low-latency production pipelines using Python, C++, and CUDA.

---

### Research & Publications

#### An Energy-Efficient TinyML Framework for Real-Time On-Device Crop Disease Classification in Resource-Constrained Edge Environments

![IEEE Paper](https://img.shields.io/badge/Publication-IEEE%20Manuscript-blue?style=flat-square)
![Model](https://img.shields.io/badge/Architecture-MicroCropNet-green?style=flat-square)
![Accuracy](https://img.shields.io/badge/Top--1%20Accuracy-100.0%25-brightgreen?style=flat-square)
![Macro F1](https://img.shields.io/badge/Macro%20F1-1.0000-brightgreen?style=flat-square)
![Quantization](https://img.shields.io/badge/Quantization-INT8%20PTQ-orange?style=flat-square)
![Latency](https://img.shields.io/badge/Latency-2.9ms-purple?style=flat-square)
![Flash](https://img.shields.io/badge/Flash%20Footprint-34.95%20KB-teal?style=flat-square)

- **Author**: Azizbek Khadjibayev (*Department of Infocommunication Engineering*)
- **Key Contributions**:
  - Engineered an ultra-compact depthwise separable Convolutional Neural Network (CNN) with 8,140 weights.
  - Applied symmetric uniform 8-bit integer (INT8) Post-Training Quantization, fitting the complete model into a 34.95 KB Flash footprint (1.71% of available 2 MB Flash on ESP32-CAM) and 36.86 KB peak SRAM.
  - Demonstrated 100.0% Top-1 accuracy and 1.0000 macro F1-score across foliar pathologies (Early Blight, Late Blight, Bacterial Spot, Healthy).
  - Measured hardware execution latency of 2.9 ms and 0.76 mJ energy consumption per inference, enabling multi-year autonomous battery and solar operation.
- **Code Repository**: [github.com/Zizx4uM/tinyml-crop-disease](https://github.com/Zizx4uM/tinyml-crop-disease)

---

### Featured Projects

#### [ShifoAI — Medical LLM Platform for Uzbek Healthcare](https://shifoai.site)
![Status](https://img.shields.io/badge/Status-Active-brightgreen?style=flat-square)
[![Live Platform](https://img.shields.io/badge/Live%20Platform-shifoai.site-0ea5e9?style=flat-square)](https://shifoai.site)
![Foundation](https://img.shields.io/badge/Foundation-MedGemma-blue?style=flat-square)
![Framework](https://img.shields.io/badge/Framework-PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Backend](https://img.shields.io/badge/Backend-FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Frontend](https://img.shields.io/badge/Frontend-React-61DAFB?style=flat-square&logo=react&logoColor=black)

- Clinical triage and medical question-answering assistant fine-tuned with Google's **MedGemma**.
- End-to-end symptom assessment, differential triage suggestions, and bilingual consultation flows with FastAPI backend and React frontend.
- **Live Platform**: [https://shifoai.site](https://shifoai.site)
- **Repository**: [github.com/Zizx4uM/shifoai-uzbek-mvp](https://github.com/Zizx4uM/shifoai-uzbek-mvp)

#### [NazoratAI — Banking Corporate Credit Monitoring & Early Warning System (EWS)](https://www.nazoratai.uz/)
![Status](https://img.shields.io/badge/Status-Production-brightgreen?style=flat-square)
[![Live Platform](https://img.shields.io/badge/Live%20Platform-nazoratai.uz-10b981?style=flat-square)](https://www.nazoratai.uz/)
![Python](https://img.shields.io/badge/Python-3.10%20%7C%203.11%20%7C%203.12-blue?style=flat-square&logo=python&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)
![API](https://img.shields.io/badge/API-FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Dashboard](https://img.shields.io/badge/Dashboard-Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![Tests](https://img.shields.io/badge/Tests-45%20Passing-brightgreen?style=flat-square)

- Enterprise credit surveillance platform monitoring 600+ corporate loan borrowers across industrial sectors.
- Combines continuous portfolio ingestion, statutory Central Bank regulatory trigger engines, and SHAP-explainable machine learning credit scoring models.
- **Live Platform**: [https://www.nazoratai.uz](https://www.nazoratai.uz/)
- **Repository**: [github.com/Zizx4uM/NazoratAI](https://github.com/Zizx4uM/NazoratAI)

#### MicroCropNet — TinyML Crop Pathology On-Device
![Target](https://img.shields.io/badge/Target-ESP32--CAM-red?style=flat-square)
![Framework](https://img.shields.io/badge/Framework-TFLite%20Micro-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![Quant](https://img.shields.io/badge/Precision-INT8-orange?style=flat-square)
![Inference](https://img.shields.io/badge/Inference-2.9ms-purple?style=flat-square)

- On-device real-time agricultural diagnostics running quantized neural networks directly on microcontroller-class hardware.
- Complete hardware profiling, offline inference pipeline, and embedded sensor camera integration.
- **Repository**: [github.com/Zizx4uM/tinyml-crop-disease](https://github.com/Zizx4uM/tinyml-crop-disease)

#### High-Performance CUDA GPU Computing
![Compute](https://img.shields.io/badge/Architecture-Ada%20Lovelace-76B900?style=flat-square&logo=nvidia&logoColor=white)
![Language](https://img.shields.io/badge/Language-CUDA%20C%2B%2B-00599C?style=flat-square)
![Tools](https://img.shields.io/badge/Profiling-Nsight%20Systems-76B900?style=flat-square)

- Custom CUDA C++ kernels targeting NVIDIA Ada Lovelace architecture (RTX 4060).
- Parallel reductions, warp shuffle primitives, shared memory tiling for matrix multiplication, and memory coalescing optimization.

---

### Technical Tooling & Technologies

| Category | Badges |
| :--- | :--- |
| **Languages** | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white) ![CUDA](https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnu-bash&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white) |
| **AI / Machine Learning** | ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white) ![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black) ![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white) ![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white) |
| **Medical AI Models** | ![MedGemma](https://img.shields.io/badge/Model-MedGemma-blue?style=flat-square) ![MedSAM](https://img.shields.io/badge/Model-MedSAM-blue?style=flat-square) ![BiomedCLIP](https://img.shields.io/badge/Model-BiomedCLIP-blue?style=flat-square) ![CheXagent](https://img.shields.io/badge/Model-CheXagent-blue?style=flat-square) ![PubMedBERT](https://img.shields.io/badge/Model-PubMedBERT-blue?style=flat-square) |
| **DevOps & Infrastructure** | ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black) ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white) |

---

<div align="center">

[![LinkedIn](https://img.shields.io/badge/Connect-LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/azizbek-xajibayev-a8787226a/)
[![GitHub](https://img.shields.io/badge/Follow-GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/Zizx4uM)
[![Hugging Face](https://img.shields.io/badge/Models-HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black)](https://huggingface.co/ZaaX19)
[![Email](https://img.shields.io/badge/Contact-Email-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:khadjibayev65@gmail.com)

</div>
