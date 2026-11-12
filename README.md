# Jeonghyeon Park (박정현)

M.S. student at the [Hanyang University AI Lab](https://ai.hanyang.ac.kr/), advised by Prof. Yong Suk Choi. Degree expected February 2027.

I work on LLM agents that stay grounded: persona-consistent dialogue, long-term agent memory, and checking what agents produce before it is trusted.

LLM 에이전트의 페르소나 일관성, 장기기억, 결과물 검증을 연구합니다.

## Selected work

**[TimeAware-LLM-Demo](https://github.com/shshjhjh4455/TimeAware-LLM-Demo)** — a role-play agent that answers as a story character without "knowing" events the character has not lived through yet. A RoBERTa-large navigator proposes where in the story a question belongs, an LLM verifier checks the premise, and the answer is streamed to the browser over SSE. Packaged with Docker Compose; weights are on [Hugging Face](https://huggingface.co/Kkonjeong/TimeAware-LLM-Demo).

**[wav2vec2-base-korean](https://huggingface.co/Kkonjeong/wav2vec2-base-korean)** — Korean speech recognition. wav2vec2-base fine-tuned with jamo-level CTC on Zeroth-Korean, CER 0.073. More than 27,000 downloads, and 90+ public models have been fine-tuned from it. Co-developed; the training code is in [this repository](https://github.com/shshjhjh4455/wav2vec2-base-korean).

**Student GPT chat service** (2024, private) — a pay-per-use chat service for university students, built as an alternative to a monthly subscription. Six selectable models from two providers, document and image input, image generation, saved conversations. Streamlit, Firebase Auth and Firestore. 316 accounts signed up.

**lab-infra** (private, lab organization) — our lab's GPU-server procedures packaged as a Claude Code plugin (10 skills) and a dependency-free TypeScript CLI. One `npx` command installs it, GitHub Actions tests it on Node 18, 20 and 22, and five labmates use it.

## Research

- **Persona grounding** — hypothesize where a question sits on a story's timeline, verify its premise, then decide whether to refuse, correct, recall or abstain.
- **Agent memory** — keeping an agent from storing its own guesses as user statements, or serving values that are no longer current.
- **Verifying agent output** — deciding when a check that an agent generated can itself be trusted.
- **Asking instead of guessing** — fine-tuning a tool agent (Qwen3-32B, LoRA) so that it asks for a missing argument rather than inventing one.

Part of this work is under double-blind review. Titles and code for those manuscripts will be linked here after the decisions.

## Publications

- Jeonghyeon Park, Yong Suk Choi. *모르면 되묻는 개인화 도구 에이전트: 결정 손실을 결합한 턴 단위 미세조정.* 한국정보처리학회 추계학술발표대회 (ACK 2026).
- JungHyoun Kim, Soohyeong Kim, Seok Jun Hwang, Jeonghyeon Park, Yong Suk Choi. *TH-RAG: Topic-Based Hierarchical Knowledge Graphs for Robust Multi-hop Reasoning in Graph-based RAG Systems.* ACL 2026 (Main).
- JungHyoun Kim, Soohyeong Kim, Seok Jun Hwang, Jeonghyeon Park, Yong Suk Choi. *Retrieval-Augmented Generation with Retrieval-optimized TRA Structure.* EMNLP 2026 (Main).
- Seok Jun Hwang, Soohyeong Kim, JungHyoun Kim, Jeonghyeon Park, Yong Suk Choi. *Atom-RAG: Atomic Fact-Centric Retrieval for Multi-Hop Reasoning.* Findings of EMNLP 2026.
- Soohyeong Kim, Seok Jun Hwang, JungHyoun Kim, Jeonghyeon Park, Yong Suk Choi. *ReGraphRAG: Reorganizing Fragmented Knowledge Graphs for Multi-Perspective Retrieval-Augmented Generation.* Findings of EMNLP 2025.

## How I work

Claude Code is my main working environment. I write down the problem, the design and the acceptance checks, hand implementation to coding agents, and review what comes back. A procedure I repeat twice becomes a skill, a hook or a CLI that someone else can install.

## Contact

shshjhjh4455@hanyang.ac.kr
