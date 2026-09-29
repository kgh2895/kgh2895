<div align="center">

# 김근호 (Geunho Kim) 🧑‍💻

**AI/ML Engineer in Progress**

> *"컴퓨터공학 전공으로 CV·LLM 프로젝트와 온디바이스 추론 경험을 쌓았으며, Efficient Multimodal AI와 로봇에 적용되는 AI 모델을 공부하고 있습니다."*

</div>

---

## 🧑‍💻 About Me

- 🏫 **B.S. Computer Engineering** — 한국외국어대학교 (HUFS), 23학번 · 2025년 편입 · 2027년 2월 졸업 예정 · GPA **4.02 / 4.50**
- 🎯 **Research Interests** — Efficient Multimodal AI · Vision-Language Models · Model Compression & Edge AI · Embodied AI
- 🔬 **Current Focus** — Medintech AI 인턴 (실시간 시각 인식·TensorRT/Jetson 배포), 대학원 진학 준비

| 등급 | 과목 |
|---|---|
| **A+** | 머신러닝 · 딥러닝 · 딥러닝응용 · 캡스톤설계및실습 · 컴퓨터구조 · 자료구조 · 자료구조와 알고리즘 · 이산수학|
| **A** | 알고리즘 · 논리회로 |

---

## 🏆 Awards & Activities

| Date | Event | Result |
|------|-------|--------|
| 2026.07 ~ 2026.12 | **Medintech 하계+2학기 인턴** — AI 개발 (후두경 가이드) | 🔬 진행 중 |
| 2026.06 | **한국외국어대학교 컴퓨터공학과 캡스톤디자인** | 🥇 최우수상 (1위) |
| 2026.06 | **한국외국어대학교 G-RISE 캡스톤디자인 경진대회** | 🥈 최우수상 (2위) · G-RISE 단장상 |
| 2026.05 | **Dacon 모기 비행 궤적 예측 AI 경진대회** | 참가 |
| 2026.04 ~ 2026.06 | **현대자동차 H-모빌리티 클래스** (자율주행 판단 트랙) | ✅ 수료 |
| 2026.04 | **Dacon 월간 스마트 창고 출고 지연 예측 AI 경진대회** | 상위 2.9% |
| 2026.03 | **Dacon 월간 구조물 안정성 물리 추론 AI 경진대회** | 상위 1% |
| 2025.10 | **경기도 AI 테크데이** | 🥉 우수상 (3위) |
| 2025.08 | **NVIDIA AI Bootcamp** | 🥇 1위 |

---

## 🚀 Projects

### 🩺 Laryngoscope Guidance AI *(Medintech Internship · 2026.07 ~ 진행 중)*
> 후두경 영상에서 주요 구조를 인식하고 삽입 방향을 실시간으로 안내하는 AI 시스템 개발

- **RTMDet 기반 회전 객체 검출(OBB)** 모델의 데이터 준비·전이학습·추론 파이프라인 개발
- Hard-negative 활용, 라벨링 기준 정비 및 입력 해상도 실험으로 검출 안정성 개선
- **TensorRT FP16**을 이용해 **NVIDIA Jetson Orin Nano**에 모델 배포 및 실시간 추론 구현
- **FP16·INT8 PTQ** 정확도–지연시간 트레이드오프 평가 및 혼합 정밀도 QAT 검토
- **8방향 정렬 가이드**와 C++ 추론 파이프라인 구현, 프레임 단위 판정 로직 및 테스트 작성
- `PyTorch` `RTMDet` `OBB Detection` `Transfer Learning` `TensorRT` `Jetson Orin Nano` `Real-time Inference` `Medical Imaging`

---

### 🗣️ CodeViva *(Capstone Design · 2026.03 ~ 2026.06)*
> 학생이 제출한 코드를 음성 설명으로 이해도를 검증하는 AI 시스템

- 🏆 한국외국어대학교 컴퓨터공학과 캡스톤디자인 **최우수상 (1위)** · G-RISE 캡스톤디자인 경진대회 **최우수상 (2위)**
- 음성 답변을 Whisper STT로 텍스트화 → LLM-as-a-Judge로 코드 이해도 평가
- 단순 정답 여부가 아닌 **실제 이해 여부**를 검증하는 교육 보조 시스템
- 오픈소스 LLM(**EXAONE 3.5 7.8B · Mi:dm 2.0 11.5B · Qwen3 14B**)을 **Curriculum SFT**로 파인튜닝
- `Whisper` `LLM` `Curriculum SFT` `Fine-tuning` `LLM-as-a-Judge` `Chain-of-Thought` `Prompt Engineering`
- 멘토: 브랜치앤바운드 이승용 대표님

---

### 👴 Elder Ease *(2025.08 ~ 2025.10 · NVIDIA AI Bootcamp 🥇 1위 / 경기도 AI 테크데이 🥉 우수상)*
> 디지털 소외계층을 위한 AI 키오스크 접근성 보조 시스템

- 얼굴 감지 + 연령 추정 CV 파이프라인 → 고령 사용자 자동 인식
- LangChain 기반 STT/TTS 음성 대화 + 개인 조건(알레르기·식단) 반영 메뉴 안내
- Overall design, CV pipeline, LLM/Prompt Engineering 전담
- 2025 경기도 AI 테크데이 우수상 수상
- `PyTorch` `OpenCV` `LangChain` `Age Estimation` `STT/TTS` `Accessibility`

---

### 🔐 AEGIS — Invisible Watermark & Tamper Detection *(DL Project · 2025.09 ~ 2025.12 · 🥇 1위)*
> 생성형 AI 이미지 위변조(Deepfake) 대응을 위한 비가시성 워터마크 삽입 + 변조 탐지 시스템

- EditGuard 기반 파인튜닝으로 성능 개선 (PSNR 38.9 → 41.54 dB, 검증 정확도 95% → 98%)
- FP16·Quantization으로 추론 비용 절감 (VRAM 사용량 감소)
- JPG 압축·크롭·리사이즈 공격 시나리오 테스트 및 Threshold 최적화
- `Watermarking` `Tamper Detection` `Quantization` `FP16` `FastAPI` `Image Security`

---

### 📝 [Paraphraser](https://github.com/kgh2895/Paraphraser) *(Personal Project)*
> AI 기반 글쓰기 교정 & 패러프레이징 도구

- Streamlit과 OpenAI API로 만든 글쓰기 교정 & 패러프레이징 보조 도구
- AI가 문법·번역투 교정안과 문장 구조 변경 예시·유의어 풀을 제시 → 사용자가 참고해 **한 문장씩 직접 재작성**
- Responses API와 Pydantic 스키마로 모델 응답 검증
- `session_state` 기반 상태 관리 + `Future` 기반 다음 문장 prefetch로 체감 대기 감소
- `Streamlit` `OpenAI API` `Pydantic` `Prompt Engineering` `NLP` `Python`

---

## 📄 Research Reading

관심 분야의 논문을 읽고 주요 개념·연구 방법을 정리하고 있습니다.

| Domain | Key Topics |
|--------|-----------|
| Efficient AI | Quantization, Pruning, Knowledge Distillation, LoRA / QLoRA, MoE |
| LLM / NLP | Transformer, RLHF, Alignment, Instruction Tuning, CLIP |
| Computer Vision | Detection, Segmentation, Depth Estimation, U-Net, Grad-CAM, YOLO |
| AI Robustness / XAI | Adversarial Attacks, Robustness, XAI, Verification |
| Robotics / Systems | Autonomous Driving, VLA, Sensor Fusion, Alpamayo-R1, ADR |

---

## 🛠️ Tech Stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white)

**DL / ML Frameworks**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white)
![LM Studio](https://img.shields.io/badge/LM_Studio-4A26C9?style=flat-square&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)

**LLM / NLP**

`LangChain` `LangGraph` `Prompt Engineering` `LoRA / QLoRA` `PEFT` `RAG Pipeline` `LLM-as-a-Judge` `STT/TTS`

**Infrastructure**

![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![VSCode](https://img.shields.io/badge/VSCode-007ACC?style=flat-square&logo=visualstudiocode&logoColor=white)
`Tailscale` `tmux` `VS Code Remote SSH`

**Edge / Deployment**

![TensorRT](https://img.shields.io/badge/TensorRT-76B900?style=flat-square&logo=nvidia&logoColor=white)
![Jetson Orin Nano](https://img.shields.io/badge/Jetson_Orin_Nano-76B900?style=flat-square&logo=nvidia&logoColor=white)

**AI Tools**

![Claude Code](https://img.shields.io/badge/Claude_Code-D97757?style=flat-square&logo=anthropic&logoColor=white)
![Cursor](https://img.shields.io/badge/Cursor-000000?style=flat-square&logo=cursor&logoColor=white)
![Antigravity](https://img.shields.io/badge/Antigravity-4285F4?style=flat-square&logo=google&logoColor=white)
![OpenClaw](https://img.shields.io/badge/🦞_OpenClaw-FF4500?style=flat-square&logoColor=white)
`Codex CLI` `Gemini CLI`

---
## 📜 Certifications & Training

- 🏅 **NVIDIA Certified Associate** — Generative AI & LLMs (2025.11 – 2027.11)
- 🏅 **NVIDIA DLI Certificate × 7** — 심화 과정 수료 (2025.07 – 2025.08)
  - Building Agentic AI Applications with Large Language Models
  - Building RAG Agents with LLMs
  - Building Transformer-Based Natural Language Processing Applications
  - Building LLM Applications With Prompt Engineering
  - Generative AI with Diffusion Models
  - Efficient Large Language Model (LLM) Customization
  - Rapid Application Development with Large Language Models (LLMs)
- 🏅 **NVIDIA AI 전문인력 양성과정** — 304h 수료
- 🏅 **TOPA Level 2** — Python Coding (2025.07)
- ✅ **Hyundai NGV H-Mobility Class** — 자율주행 판단 트랙 (2026.04 ~ 2026.06)
- ✅ **Hyundai NGV H-Mobility Class** — Car Inside Out (2026.04 ~ 2026.06)

---

## 🔭 Interests

`Efficient Multimodal AI` `Vision-Language Models` `Embodied AI` `Model Compression` `Quantization` `Edge AI`

---

## 📬 Contact

[![HUFS Email](https://img.shields.io/badge/HUFS_Email-0A66C2?style=flat-square&logo=gmail&logoColor=white)](mailto:kgh2895@hufs.ac.kr)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/%EA%B7%BC%ED%98%B8-%EA%B9%80-43b03a378/)

---

<div align="center">
