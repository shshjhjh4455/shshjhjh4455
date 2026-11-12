<p align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0F172A,50:4338CA,100:22D3EE&height=220&section=header&text=Jeonghyeon%20Park&fontSize=50&fontColor=FFFFFF&animation=fadeIn&fontAlignY=36&desc=LLM%20Agents%20%C2%B7%20Persona%20Dialogue%20%C2%B7%20Agent%20Memory%20%C2%B7%20Verification&descAlignY=57&descSize=17" width="100%" alt="Jeonghyeon Park"/>
</p>

<p align="center">
<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=19&duration=3000&pause=900&color=6366F1&center=true&vCenter=true&width=720&lines=LLM+agents+that+stay+grounded;Persona+Dialogue+%C2%B7+Agent+Memory+%C2%B7+Verification;Training+%C2%B7+Serving+%C2%B7+Evaluation+pipelines" alt="Typing SVG"/>
</p>

<p align="center">
페르소나가 흔들리지 않는 대화, 사실을 지키는 기억, 믿고 쓰기 전에 검증하는 에이전트를 연구합니다.<br/>
연구에 필요한 학습·서빙·평가 파이프라인과 팀 도구도 직접 만듭니다.
</p>

<p align="center">
<a href="mailto:shshjhjh4455@hanyang.ac.kr"><img src="https://img.shields.io/badge/Email-shshjhjh4455%40hanyang.ac.kr-0F172A?style=flat-square&logo=gmail&logoColor=white" alt="Email"/></a>
<a href="https://huggingface.co/Kkonjeong"><img src="https://img.shields.io/badge/Hugging%20Face-Kkonjeong-FFD21E?style=flat-square&logo=huggingface&logoColor=black" alt="Hugging Face"/></a>
<a href="https://ai.hanyang.ac.kr/"><img src="https://img.shields.io/badge/Hanyang%20Univ.-AI%20Lab-4338CA?style=flat-square" alt="Hanyang University AI Lab"/></a>
</p>

<br/>

<div align="center">

| **316** | **8편** | **27,000+** | **2건** |
|:---:|:---:|:---:|:---:|
| 학생용 GPT 서비스 가입 계정 | 게재·채택 논문 (1저자 3 · 공저 5) | 음성인식 모델 누적 다운로드 | 특허 출원 (공동 발명) |

</div>

---

## 🔬 Research Interests

> **Persona-grounded Dialogue · Agent Memory · Agent Verification · Tool-agent Fine-tuning**

* **Persona-grounded Dialogue** — 캐릭터가 아직 겪지 않은 사건을 모르는 채로 답하는 시점 인식 롤플레이, 가설–검증 RAG
* **Agent Memory** — 근거와 출처, 현재성을 지키는 에이전트 장기기억
* **Agent Verification** — 에이전트가 만든 결과물과 검사기를 믿고 쓰기 전에 검증하는 절차
* **Tool-agent Fine-tuning** — 모르는 값을 지어내지 않고 되묻게 하는 LoRA 미세조정

<br/>

## 📚 Research & Publications

### 모르면 되묻는 개인화 도구 에이전트: 결정 손실을 결합한 턴 단위 미세조정

**First Author · ACK 2026 (한국정보처리학회 추계학술발표대회)**

![ACK 2026](https://img.shields.io/badge/ACK%202026-Accepted-1f6feb?style=flat-square)
![First Author](https://img.shields.io/badge/First%20Author-DA--TFT-4338CA?style=flat-square)

도구 에이전트가 문맥에 없는 값을 지어내 도구를 호출하는 문제를 다뤘습니다. 호출할지 되물을지는 응답의 첫 토큰에서 정해진다고 보고, 그 지점에 결정 손실을 직접 걸어 학습했습니다.

* Qwen3-32B를 **LoRA**로 학습하고 첫 토큰에 **결정 손실(BCE)** 적용
* 되묻기 재현율 **9.0% → 76.1%** (되물어야 하는 67턴 중 6턴 → 51턴)
* 결정 손실만 뺀 절제 실험은 **40.3%** 로, 효과를 분리해 확인 (McNemar p = 8.1 × 10⁻⁷)
* 나빠진 지표도 함께 보고: 오정지율 **0.4% → 6.7%** (호출이 정답인 240턴 중 1턴 → 16턴)

---

### RAG 공동 연구

**Co-author (4th) · 한양대학교 인공지능 연구실 공동 연구**

문제 탐색과 해결을 팀이 함께 했고, 리버틀 대응에 참여했습니다.

| Venue&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | Paper | Link |
|:---|:---|:---:|
| ![ACL 2026](https://img.shields.io/badge/ACL%202026-Main-1f6feb?style=flat-square) | **TH-RAG**: Topic-Based Hierarchical Knowledge Graphs for Robust Multi-hop Reasoning in Graph-based RAG Systems | [Paper](https://aclanthology.org/2026.acl-long.1740/) |
| ![EMNLP 2026](https://img.shields.io/badge/EMNLP%202026-Main-8A2BE2?style=flat-square) | Retrieval-Augmented Generation with Retrieval-optimized TRA Structure | |
| ![EMNLP 2026](https://img.shields.io/badge/EMNLP%202026-Findings-0F766E?style=flat-square) | **Atom-RAG**: Atomic Fact-Centric Retrieval for Multi-Hop Reasoning | [Paper](https://aclanthology.org/2026.findings-emnlp.2323/) |
| ![EMNLP 2025](https://img.shields.io/badge/EMNLP%202025-Findings-0F766E?style=flat-square) | **ReGraphRAG**: Reorganizing Fragmented Knowledge Graphs for Multi-Perspective Retrieval-Augmented Generation | [Paper](https://aclanthology.org/2025.findings-emnlp.290/) |

---

### 학부 연구

**한성대학교 학부 과정에서 쓴 논문**

| Venue&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | Paper | Role |
|:---|:---|:---:|
| ![KICS 2024](https://img.shields.io/badge/KICS%202024-%ED%95%9C%EA%B5%AD%ED%86%B5%EC%8B%A0%ED%95%99%ED%9A%8C-475569?style=flat-square) | 야구 중계 영상 내 행동 인식을 위한 모델 및 데이터셋 비교 분석 연구 (LG U+ 산학) | 1저자 |
| ![KICS 2024](https://img.shields.io/badge/KICS%202024-%ED%95%9C%EA%B5%AD%ED%86%B5%EC%8B%A0%ED%95%99%ED%9A%8C-475569?style=flat-square) | 리뷰 데이터 기반의 사용자 친화적인 호텔 추천 챗봇 시스템 | 1저자 |
| ![KCI 2025](https://img.shields.io/badge/KCI-2025-B45309?style=flat-square) | 코사인 유사도 기반 객체 추적을 통한 다중 객체 환경에서의 행동 인식 개선 (LG U+ 산학) · 차세대융합기술학회논문지 9(1) · [Paper](https://www.earticle.net/Article/A461379) | 공저 (3저자) |

---

### Under Review

1저자·공동 1저자 원고 4편이 double-blind 심사 중입니다. 제목과 코드는 결과가 나온 뒤 이곳에 공개합니다.

---

### Patents

| 발명의 명칭 | 출원번호 | 출원일 |
|:---|:---:|:---:|
| 가설-검증 기반의 검색증강생성 프레임워크를 이용한 장편서사 특화 대화형 챗봇 시스템 | 10-2026-0096704 | 2026.05.28 |
| 대규모 언어 모델과 검색증강생성 기술을 결합한 조선왕조실록 특화 대화형 챗봇 시스템 | 10-2026-0118026 | 2026.06.29 |

공동 발명 · 출원인 한양대학교 산학협력단

<br/>

---

## 🚀 주요 프로젝트

### 🎭 [TimeAware-LLM-Demo — 시점을 지키는 캐릭터 롤플레이 에이전트](https://github.com/shshjhjh4455/TimeAware-LLM-Demo)

**설계 · 분류기 학습 · 데모 패키징과 배포**

`Python` `PyTorch` `RoBERTa` `RAG` `Gemini API` `Docker Compose`

캐릭터가 아직 겪지 않은 사건을 아는 것처럼 답하지 않도록, 장면 가설을 세우고 검증한 뒤 그 시점까지의 기억만 꺼내 답하는 웹 데모입니다.

* **RoBERTa-Large** 분류기가 185개 장(chapter) 가운데 후보 장면을 고르고, LLM 검증기가 하나로 확정
* 검증과 기억 검색을 **병렬**로 실행하고, 답변은 생성되는 대로 스트리밍
* 캐릭터 3명 × 시점 25개, 캐릭터 기억 **7,034건**, 장면 임베딩 **988건**
* `docker compose up` 으로 실행, 가중치는 설치 스크립트가 Hugging Face Hub에서 내려받음

---

### 💬 학생용 GPT 채팅 서비스

**개발 · 운영 · 저장소 커밋 252개 중 251개 작성**

`Streamlit` `Firebase Auth` `Firestore` `OpenAI API` `Groq API`

월 구독 대신 API를 직접 불러, 쓴 만큼만 비용이 들게 만든 대학생용 채팅 서비스입니다.

* OpenAI·Groq **모델 6종** 선택, 문서(PDF·CSV·Word) 입력, 이미지 생성, 계정별 대화 기록 저장
* Google 로그인과 이메일 가입(Firebase Authentication)
* 2024년 7월부터 2025년 2월까지 **계정 316개** 가입
* 코드는 비공개 저장소에 있습니다

---

### 🧾 Signal Receipts — 숫자와 출처를 근거까지 되짚는 공시 브리핑 파이프라인

**문제 정의 · 설계 · 검수 (구현에는 코딩 에이전트 사용) · 코드 비공개**

`Python` `MCP Server` `BM25 + Embedding RRF` `pytest` `Claude Code Hooks`

DART 공시로 검증 가능한 에이전트 환경을 만들고, 에이전트가 쓴 글의 숫자와 출처가 실제 근거에서 나왔는지 코드로 확인합니다.

* 잠정실적 공시 **7,373건** 중 6,976건 파싱(94.6%), MCP 서버 **도구 12개**(연결마다 기준 시각 지정)
* 기준 시각 RAG(공개 시각 필터 → BM25 + 임베딩 RRF → LLM 리랭크): 기준 시각에 맞지 않는 값의 문서가 상위 5에 섞이는 질문 **104개 중 94개 → 3개**
* 채점기 2개는 LLM이 아닌 코드: 브리핑의 숫자를 근거에서 다시 계산하고, 출처가 그 에피소드의 도구 결과에 있었는지 확인
* 평가셋은 훅과 해시 봉인으로 보호, 테스트 **647건** 통과

---

### 🧰 lab-infra — 연구실 GPU 서버 절차를 설치형 도구로

**설계 · 구현 · 배포 · 연구실 비공개 저장소**

`TypeScript` `Node CLI` `Claude Code Plugin` `GitHub Actions`

개인 스킬에만 있던 공유 GPU 서버의 접속·서빙·복구 절차를 플러그인과 CLI로 묶어 팀에 배포했습니다.

* Claude Code 플러그인(**스킬 10개**)과 의존성 없는 CLI, `npx` 한 줄로 설치
* 새 팀원 서버 세팅 **5단계 → 명령 1회**, 연구실 동료 **5명** 사용
* CLI를 TypeScript로 옮길 때 이전 출력 11종을 정답으로 고정해 동작이 같은지 확인, PR마다 Node 18/20/22에서 검사

---

### ⚙️ 연구용 서빙 · 평가 · 운영 파이프라인

**문제 정의 · 설계 · 검증 (구현에는 코딩 에이전트 사용)**

`vLLM` `Docker` `systemd` `cron` `SSH`

실험이 사람 손 없이 돌도록, 느리거나 깨지는 원인을 찾아 고친 기록입니다.

* vLLM 텐서 병렬 서빙과 병렬 평가 러너로 **2,200 질의를 400 워커로 약 3분**에 처리
* 분산 채점이 느려진 원인(프로세스마다 BLAS 스레드 12개)을 찾아 고정, 처리량 **25배** 회복
* 임대 GPU 유휴 과금 차단: 감시를 세션 밖으로 옮겨 시간당 **$4.06 → $0.06**
* 공유 서버 재부팅 복구를 3중(재시작 정책·systemd·cron)으로 구성, 끊긴 세션 **9건 중 9건** 접속 복구

---

### 🎙 [wav2vec2-base-korean — 한국어 음성인식 모델](https://huggingface.co/Kkonjeong/wav2vec2-base-korean)

**공동 개발**

`wav2vec2` `CTC` `Transformers` `Zeroth-Korean`

wav2vec2-base를 자모 단위 CTC로 미세조정한 한국어 음성인식 모델입니다.

* Zeroth-Korean 테스트 **CER 0.073**
* Hugging Face 누적 다운로드 **27,000회 이상**, 이 모델에서 파생된 공개 미세조정 모델 **90개 이상** (2026년 11월 조회)
* 학습·추론 노트북: [KkonJJ/wav2vec2-base-korean](https://github.com/KkonJJ/wav2vec2-base-korean)

---

### 🎬 [시네마캐릭터 — 영화 캐릭터 페르소나 챗봇](https://github.com/shshjhjh4455/character_chatbot_web)

**AI/모델 팀 (2인) · 2024 한성대학교 캡스톤 디자인**

`RAG` `GPT Fine-tuning`

영화 캐릭터의 말투와 성격을 RAG와 GPT 미세조정으로 구현한 페르소나 챗봇 프로젝트입니다. 긴 문맥과 기억을 잃는 한계가 석사 연구의 출발점이 됐습니다.

---

### 🎓 학부 프로젝트

| 프로젝트 | 내용 | 기간 |
|:---|:---|:---:|
| [야구 행동 인식 모델](https://github.com/shshjhjh4455/mmaction2_aihub_sports_video_data_baseball) | 한성대학교 × LG U+ 산학 프로젝트. 중계 영상에서 사람을 검출하고(Faster R-CNN) 포즈를 추정한 뒤(HRNet) PoseC3D로 13개 동작을 분류 | 2023.10 ~ 2024.01 |
| AI 기반 얼굴 이미지 합성 엔진 | 한성대학교 × LG U+ 산학 프로젝트. 얼굴 랜드마크로 마스크를 만들고 inpainting으로 보정 | 2024.10 ~ 2024.11 |
| 음성·표정 동기화 AI 캐릭터 인터랙션 | 음성과 표정을 동기화한 캐릭터 인터랙션 시스템. 위의 wav2vec2 한국어 음성인식 모델을 이 프로젝트에서 만들었습니다 | 2024.03 ~ 2024.07 |
| 호텔 추천 챗봇 | 호텔 리뷰로 KoBERT 감성 분류기를 학습하고 문장 임베딩 유사도와 결합해 추천 | 2023.10 ~ 2023.12 |
| 농산물 가격 예측 | 멀티캠퍼스 부트캠프 최종 프로젝트 **최우수상** | 2022.12 ~ 2023.01 |

<br/>

---

## 💼 경력 · 활동

| 활동 | 역할 | 기간 |
|:---|:---|:---:|
| 한양대학교 인공지능 연구실 | 석사과정 연구원 (지도교수 최용석) | 2025.03 ~ 현재 |
| BK21 딥러닝 수업 | 조교 | 2026년 1학기 |
| 학생용 GPT 채팅 서비스 | 개발 · 운영 | 2024 |
| 시네마캐릭터 (캡스톤 디자인) | AI/모델 팀 | 2024.03 ~ 2024.07 |
| 한성대학교 × LG U+ 산학 프로젝트 | 야구 행동 인식 · 얼굴 이미지 합성 | 2023.10 ~ 2024.01, 2024.10 ~ 2024.11 |
| 멀티캠퍼스 「AI 플랫폼을 활용한 데이터 분석」 부트캠프 | 교육생 | 2022.07 ~ 2023.01 |
| 성북구청 서울형혁신교육지구 마을 교육 활동 | 연구원 (아두이노 교육 교재 제작 · 대면 교육) | 2021.06 ~ 2021.08 |

<br/>

---

## 🏆 수상 · 대회

| 대회 | 내용 | 시기 |
|:---|:---|:---:|
| 2024 SW중심대학 디지털 경진대회 (SW 부문) · 데이콘 | 예선 | 2024.07 |
| 멀티캠퍼스 「AI 플랫폼을 활용한 데이터 분석」 부트캠프 | 프로젝트 **최우수상** | 2023.01 |

<br/>

---

## 🎓 Education

| 학교 | 과정 | 기간 |
|:---|:---|:---:|
| 한양대학교 일반대학원 컴퓨터소프트웨어학과 | 석사과정 (인공지능 연구실) | 2025 ~ 2027.02 (예정) |
| 한성대학교 컴퓨터공학부 | 학사 | 2020 ~ 2024 |

<br/>

---

## 🛠 기술 스택

### LLM · Training

<p>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white"/>
<img src="https://img.shields.io/badge/Transformers-FFD21E?style=flat-square&logo=huggingface&logoColor=black"/>
<img src="https://img.shields.io/badge/PEFT%20%C2%B7%20LoRA%20%C2%B7%20QLoRA-7C3AED?style=flat-square"/>
<img src="https://img.shields.io/badge/vLLM-0F766E?style=flat-square"/>
</p>

### RAG · Agents

<p>
<img src="https://img.shields.io/badge/RAG-2563EB?style=flat-square"/>
<img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white"/>
<img src="https://img.shields.io/badge/Tool%20Calling-475569?style=flat-square"/>
<img src="https://img.shields.io/badge/Subagent%20Orchestration-334155?style=flat-square"/>
<img src="https://img.shields.io/badge/Claude%20Code-D97757?style=flat-square&logo=anthropic&logoColor=white"/>
</p>

### Serving · Ops

<p>
<img src="https://img.shields.io/badge/Docker%20Compose-2496ED?style=flat-square&logo=docker&logoColor=white"/>
<img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black"/>
<img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white"/>
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white"/>
<img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white"/>
<img src="https://img.shields.io/badge/Firebase-DD2C00?style=flat-square&logo=firebase&logoColor=white"/>
</p>

<br/>

---

<p align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0F172A,50:4338CA,100:22D3EE&height=110&section=footer" width="100%" alt=""/>
</p>
