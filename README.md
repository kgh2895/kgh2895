<div align="center">

# 김근호 (Geunho Kim) 🧑‍💻

**AI/ML Engineer in Progress**

> *"컴퓨터공학을 전공하며 AI/ML, Computer Vision, LLM 응용을 중심으로 공부하고 있는 학부생입니다."*

</div>

---

## 🧑‍💻 About Me

- 🏫 **B.S. Computer Science** — 한국외국어대학교 (HUFS), 23학번 · 2025년 편입 · 2027년 졸업 예정 · GPA **4.0 / 4.5**
- 🎯 **Research Interest** — Computer Vision, LLM Integration, Autonomous Driving
- 🔬 **Current Focus** — CodeViva (Capstone), AI Competition, 대학원 준비
- 📍 **Location** — Seoul, South Korea

| 등급 | 과목 |
|---|---|
| **A+** | 머신러닝 · 딥러닝 · 자료구조 · 자료구조와 알고리즘 · 이산수학 |
| **A** | 알고리즘 |

---

## 🏆 Awards & Competitions

| Date | Event | Result |
|------|-------|--------|
| 2026.06 | **한국외국어대학교 G-RISE 캡스톤디자인 경진대회** | 🏅 G-RISE 단장상 수상 |
| 2026.04 ~ | **현대자동차 H-모빌리티 클래스** (자율주행 판단 트랙) | ✅ 합격 · 참가 중 |
| 2026.05 ~ | **Dacon 모기 비행 궤적 예측 AI 경진대회** | 참가 |
| 2026.04 | **Dacon 스마트 창고 출고 지연 예측 AI 경진대회** | 상위 2.9% |
| 2026.03 | **Dacon 월간 구조물 안정성 물리 추론 AI 경진대회** | 상위 1% |
| 2025 | **경기도 AI 테크데이** | 🥉 우수상 |
| 2025 | **NVIDIA AI Bootcamp** | 🥇 1위 |

---

## 🚀 Projects

### 🗣️ CodeViva *(Capstone Design, 2026.03 ~ )*
> 학생이 제출한 코드를 음성 설명으로 이해도를 검증하는 AI 시스템

- 음성 답변을 Whisper STT로 텍스트화 → LLM-as-a-Judge로 코드 이해도 평가
- 단순 정답 여부가 아닌 **실제 이해 여부**를 검증하는 교육 보조 시스템
- 오픈소스 LLM(**EXAONE 3.5 7.8B · Mi:dm 2.0 11.5B · Qwen3 14B**)을 **Curriculum SFT**로 파인튜닝
- `Whisper` `LLM` `Curriculum SFT` `Fine-tuning` `LLM-as-a-Judge` `Chain-of-Thought` `Prompt Engineering`
- 멘토: 브랜치앤바운드 이승용 대표님

---

### 👴 Elder Ease *(NVIDIA AI Bootcamp 2025, 🥇 1위 /	경기도 AI 테크데이 2025, 🥉 우수상)*
> 디지털 소외계층을 위한 AI 키오스크 접근성 보조 시스템

- 얼굴 감지 + 연령 추정 CV 파이프라인 → 고령 사용자 자동 인식
- LangChain 기반 STT/TTS 음성 대화 + 개인 조건(알레르기·식단) 반영 메뉴 안내
- Overall design, CV pipeline, LLM/Prompt Engineering 전담
- 2025 경기도 AI 테크데이 우수상 수상
- `PyTorch` `OpenCV` `LangChain` `Age Estimation` `STT/TTS` `Accessibility`

---

### 🔐 AEGIS — Invisible Watermark & Tamper Detection *(DL Project, 🥇 1위)*
> 생성형 AI 이미지 위변조(Deepfake) 대응을 위한 비가시성 워터마크 삽입 + 변조 탐지 시스템

- EditGuard 기반 파인튜닝으로 성능 개선 (PSNR 38.9 → 41.54 dB, 검증 정확도 95% → 98%)
- FP16·Quantization으로 추론 비용 절감 (VRAM 사용량 감소)
- JPG 압축·크롭·리사이즈 공격 시나리오 테스트 및 Threshold 최적화
- `Watermarking` `Tamper Detection` `Quantization` `FP16` `FastAPI` `Image Security`

---

### 📝 Paraphraser *(Personal Project)*
> AI 기반 글쓰기 교정 & 패러프레이징 도구

- Streamlit과 OpenAI API를 활용한 AI 기반 글쓰기 교정 및 패러프레이징 도구
- 사용자가 **한 문장씩 직접 확인하며** 자신의 문장으로 재구성하는 수동 패러프레이징 가이드 기능
- 논문·보고서 작성 시 표절률 감소 및 개인 문체 유지에 특화
- `Streamlit` `OpenAI API` `Prompt Engineering` `NLP` `Python`

---

## 📄 Paper Reviews

5개 도메인, 약 24편 자기주도 리뷰 (Notion 구조화 마크다운 템플릿 사용)

| Domain | Key Topics |
|--------|-----------|
| Efficient AI | Quantization, Pruning, Knowledge Distillation, LoRA / QLoRA, MoE |
| LLM / NLP | Transformer, RLHF, Alignment, Instruction Tuning, CLIP |
| Computer Vision | Detection, Segmentation, Depth Estimation, U-Net, Grad-CAM, YOLO |
| AI Robustness / XAI | Adversarial Attacks, Robustness, XAI, Verification |
| Robotics / Systems | Autonomous Driving, VLA, Sensor Fusion, Alpamayo-R1, ADR |

📝 [논문 리뷰 Notion 바로가기](https://www.notion.so/2e108a455ffa8013b882c253c8b38f55?source=copy_link)

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

**AI Tools**

![Claude Code](https://img.shields.io/badge/Claude_Code-D97757?style=flat-square&logo=anthropic&logoColor=white)
![Cursor](https://img.shields.io/badge/Cursor-000000?style=flat-square&logo=cursor&logoColor=white)
![Antigravity](https://img.shields.io/badge/Antigravity-4285F4?style=flat-square&logo=google&logoColor=white)
![OpenClaw](https://img.shields.io/badge/🦞_OpenClaw-FF4500?style=flat-square&logoColor=white)
`Codex CLI` `Gemini CLI`

---
## 📜 Certifications

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

---

## 🔭 Interests

`Autonomous Driving` `Computer Vision` `LLM Application` `Multimodal AI`  
`Bio-AI` `Aerospace` `Big Data Analytics` `Robotics` `Data Engineering`

---

## 📬 Contact

[![Gmail](https://img.shields.io/badge/kgh2895@naver.com-EA4335?style=flat-square&logo=naver&logoColor=white)](mailto:kgh2895@naver.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/%EA%B7%BC%ED%98%B8-%EA%B9%80-43b03a378/)
[![Notion](https://img.shields.io/badge/Paper_Reviews-000000?style=flat-square&logo=notion&logoColor=white)](https://www.notion.so/2e108a455ffa8013b882c253c8b38f55?source=copy_link)

---

<div align="center">
