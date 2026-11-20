# 🖍️ 매쓰AI는 어떻게 그림과 노래를 만들까? — 수학과 감성컴퓨팅으로 보는 AI 창작

> **[🌐 웹으로 발표 바로가기](https://s24437427-netizen.github.io/ai-empathy-paper/)**  
> *의미 지도, 확산 모델, 소리 파형, 다음 말 확률 체험과 학생 작품 갤러리가 있는 웹 발표 화면으로 이동합니다.*

---

## 🎬 설명 영상

| 영상 | 길이 | 바로 보기 |
| :--- | :--- | :--- |
| 내레이션 + 자막 | 3분 12초 | [videos/explainer-voice.mp4](videos/explainer-voice.mp4) |
| 자막만 (직접 녹음용) | 2분 48초 | [videos/explainer-captions.mp4](videos/explainer-captions.mp4) |

---


## 📌 세 가지 질문

초등 교실에서 학생들과 매쓰AI로 만든 그림과 노래를 출발점으로 삼습니다.

1. **수학** — 매쓰AI는 말 한 줄로 어떻게 그림과 노래를 만들까?
2. **감성컴퓨팅** — 감정이 없는 AI의 작품에 우리는 왜 감동하고, 그 감동을 어떻게 받아들여야 할까?
3. **태도** — AI가 만든 창작물에 우리는 어떻게 다가가야 할까?

> 우리 반이 쓴 플랫폼은 매쓰AI(주식회사 매쓰에이아이)의 생성형 AI 스튜디오 **SMART**입니다. Chat·Image·Music 생성에 안전 필터와 기관 운영 정책을 결합한 서비스로, 이미지·음악 생성 모델은 공개되어 있지 않아 대표적인 생성형 AI 원리로 설명합니다.

---

## ① 수학으로 보기

| 만드는 것 | 핵심 수학 개념 | 근거 |
| :--- | :--- | :--- |
| 말 이해하기 | 벡터(인코딩), 내적, 코사인 유사도 | Radford 외 (2021) CLIP |
| 그림 | 정규분포 노이즈, 단계별 노이즈 제거, 잠재 공간 | Ho 외 (2020) DDPM, Rombach 외 (2022) |
| 노래 | 파동과 주파수, 화음의 비율(옥타브 2:1, 완전5도 3:2), 오디오 토큰의 확률분포 | Défossez 외 (2022), Copet 외 (2023) MusicGen |
| 영상 | 프레임의 연속, 프레임 사이 일관성 | — |
| 배우기 | 손실함수, 경사하강법 | 강의 8주차 |

> 📌 같은 말을 넣어도 매번 다른 작품이 나오는 것은 **확률분포에서 새로 뽑기** 때문입니다.

---

## ② 감성컴퓨팅으로 보기

- 감성컴퓨팅은 감정의 **추정·표현·경험**을 구분합니다. 매쓰AI는 추정과 표현을 수학으로 해내지만, 경험하지는 않습니다.
- 사람은 템포·조성 같은 신호로 음악의 감정을 읽고(Juslin & Laukka, 2003), AI는 이 **감정과 패턴 사이의 통계적 연결**을 학습해 재현합니다.
- 사람은 컴퓨터에도 사회적으로 반응하고(Nass 외, 1994), 뇌는 자기 경험으로 감정을 구성합니다(Barrett, 2017).

- SMART가 소개된 행사 이름은 "우리가족 마음잇기 AI 챌린지"였습니다. 마음을 가진 것은 가족이고, AI는 그 마음을 **잇는 도구**입니다.

> 💡 **감정은 AI 작품 안이 아니라, 감상하는 사람 안에서 완성됩니다.** AI의 노래는 계산의 결과지만, 그 노래에 움직인 학생의 마음은 진짜입니다.

---

## ③ AI 창작물에 다가가기

- 사람들은 AI 시를 46.6% 정확도로밖에 구별하지 못했습니다(Porter·Machery, 2024).
- 같은 AI 그림도 "사람이 그렸다"고 하면 더 높게 평가했고, 작품 뒤의 **이야기와 노력**이 평가를 움직였습니다(Bellaiche 외, 2023).

**교실에서 지킬 다섯 가지 태도**

1. **출처를 밝힌다** — "AI와 함께 만들었어요"
2. **과정을 이야기로 남긴다** — 내가 쓴 문장, 고친 과정, 고른 이유
3. **감동은 인정하고, 원리는 안다** — AI 리터러시
4. **경쟁보다 협업으로 본다** — 무엇을 만들지 정하는 사람은 나
5. **다른 사람의 권리를 지킨다** — 얼굴·목소리·작품은 허락받고

> 매쓰AI의 SMART 원칙(Safe·Mindful·Accountable·Respectful·Trustworthy)과도 이어집니다.

---

## 💡 [선택 과제] LLM, Multimodal, Zero-shot — 초등 눈높이 설명 (⑮번)

| 개념 | 초등 맞춤 비유 | 매쓰AI 연계 |
| :--- | :--- | :--- |
| **LLM** | **끝말잇기 천재** — 다음에 올 말을 확률로 이어붙이는 달인 | 대화 실습 |
| **Multimodal** | **오감(五感) AI** — 글과 그림을 같은 의미 지도에 놓는 AI | 이미지·노래 동시 생성 |
| **Zero-shot** | **처음 보는 문제도 척척** — 예시 없이 설명만 듣고 해내는 능력 | 즉석 지시만으로 창작 |

---

## 📚 참고문헌

- Ho, J., Jain, A., & Abbeel, P. (2020). Denoising diffusion probabilistic models. *NeurIPS*, 33.
- Rombach, R., Blattmann, A., Lorenz, D., Esser, P., & Ommer, B. (2022). High-resolution image synthesis with latent diffusion models. *CVPR*.
- Radford, A., et al. (2021). Learning transferable visual models from natural language supervision. *ICML*.
- Défossez, A., Copet, J., Synnaeve, G., & Adi, Y. (2022). High fidelity neural audio compression. arXiv:2210.13438.
- Copet, J., et al. (2023). Simple and controllable music generation. *NeurIPS*, 36.
- Brown, T. B., et al. (2020). Language models are few-shot learners. *NeurIPS*, 33.
- Juslin, P. N., & Laukka, P. (2003). Communication of emotions in vocal expression and music performance. *Psychological Bulletin*, 129(5), 770–814.
- Nass, C., Steuer, J., & Tauber, E. R. (1994). Computers are social actors. *CHI '94*, 72–78.
- Barrett, L. F. (2017). The theory of constructed emotion. *Social Cognitive and Affective Neuroscience*, 12(1), 1–23.
- Porter, B., & Machery, E. (2024). AI-generated poetry is indistinguishable from human-written poetry and is rated more favorably. *Scientific Reports*, 14, 26133.
- 주식회사 매쓰에이아이 (2026). MathAI SMART | 우리가족 마음잇기 AI 챌린지. https://www.mathaitalk.com/ai-challenge.html
- Bellaiche, L., et al. (2023). Humans versus AI: whether and why we prefer human-created compared to AI-created artwork. *Cognitive Research: Principles and Implications*, 8, 42.

---

> *"감정은 작품 안이 아니라, 감상하는 사람 안에서 완성된다."*
