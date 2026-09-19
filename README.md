# Information-Security
숭실대학교 전자정보공학부 IT융합 정보보호론 2026-2 연구과제 자료

# SASV

숭실대학교 전자정보공학부 IT융합 **정보보호론 2026-2 수업 연구 과제 자료** (정수환 교수님)

## 🧠 Colab 실행 가이드

이 노트북은 Google Colab 환경에서 바로 실행할 수 있습니다.<br>
본인의 음성을 이용한 **Voice Cloning**, **화자인증(ASV)**, **딥페이크 음성 탐지(CM)**,  
**Spoofing-Aware Speaker Verification(SASV)** 실습을 수행할 수 있습니다.

---

## 💡 실습 자료

Score Fusion 실습을 위해 ASVspoof2019 데이터셋의 다음 파일을 함께 제공합니다.

- `dev_scores.csv` : Score Fusion 방식 설계 및 성능 비교
- `eval_scores.csv` : DEV에서 선택한 방식의 최종 성능 평가

Score 파일 형식:

` speaker, utt, key, label, asv_score, cm_score `

> DEV 데이터를 이용하여 Score Fusion 방식을 설계하고,  
> 가장 좋은 방식을 선택한 뒤 EVAL 데이터에서 최종 성능을 확인합니다.

---

## ⚙️ 1. Colab 접속 및 새 노트북 생성

1️⃣ [https://colab.google/](https://colab.google/) 접속 <br>
2️⃣ **New notebook**을 클릭하여 새 Colab 노트북을 생성하거나 **Open Colab**을 클릭하여 `.ipynb` 파일을 업로드합니다.

---

## 💻 2. 런타임 설정 변경

1️⃣ 상단 메뉴에서 **“런타임 → 런타임 유형 변경(Change runtime type)”** 선택<br>
2️⃣ **하드웨어 가속기(Accelerator)** → `T4 GPU` 선택<br>
3️⃣ **[저장]** 클릭

> 💡 Voice Cloning 및 음성 AI 모델 추론에는 GPU 사용을 권장합니다.

<img width="580" height="532" alt="image" src="https://github.com/user-attachments/assets/71217cd2-f898-4f46-aa13-4167e09834f2" />

---

## ▶️ 3. 코드 실행

셀에 코드 입력 후 **Shift + Enter**를 누르면 셀이 실행됩니다.

실습 중 안내에 따라 본인의 음성 파일과 제공된  
`dev_scores.csv`, `eval_scores.csv` 파일을 업로드하여 사용합니다.

---

## 💾 4. 노트북 파일 다운로드

코드 실행이 끝난 후,<br>
상단 메뉴의 **“파일 → 다운로드 → .ipynb 다운로드”**를 클릭하면 로컬 PC로 노트북을 저장할 수 있습니다.

---

## 📮 과제 제출

- 보고서
- 제출 기한 및 방법은 과제 안내문 참고
