# aiStudy

> **Do It AI 기반 실습 중심 AI 학습 저장소**
> 이론보다 **직접 실행 가능한 코드와 실험 결과**를 중심으로 AI/LLM을 학습합니다.

---

## 📌 Repository Overview

이 저장소는 **Do It AI 교재 및 관련 자료**를 바탕으로
AI 개념을 Python 코드로 직접 구현하고,
OpenAI API 및 프롬프트 실험을 통해 **실무 감각을 기르기 위한 개인 학습 레포지토리**입니다.

* 단순 요약 ❌
* 실행 가능한 코드 ⭕
* 재현 가능한 실습 ⭕

을 원칙으로 정리합니다.

---

## 🎯 학습 목표

* AI / LLM 기본 개념 이해
* Prompt Engineering 실습
* OpenAI API 구조 및 사용 방식 이해
* 응답 처리, 토큰·비용 관리 경험
* Python 기반 실험 결과 정리

---

## 📂 프로젝트 구조

```text
aiStudy/
├─ basics/              # AI 기본 개념 및 예제
├─ prompts/             # 프롬프트 설계 및 실험
├─ openai-api/          # OpenAI API 실습 코드
├─ notebooks/           # Jupyter Notebook 실험
├─ utils/               # 공통 유틸리티
├─ .gitignore
├─ requirements.txt
└─ README.md
```

> 폴더 구조는 학습 진행에 따라 유연하게 변경될 수 있습니다.

---

## 🛠 기술 스택

* **Language**: Python 3.x
* **AI / LLM**

  * OpenAI API
  * Prompt Engineering
* **Tools**

  * Git / GitHub
  * Jupyter Notebook
* **Environment**

  * Python Virtual Environment
  * `.env` 기반 환경 변수 관리

---

## 🚀 실행 방법

### 1️⃣ 레포지토리 클론

```bash
git clone https://github.com/ithansiyeon/aiStudy.git
cd aiStudy
```

---

### 2️⃣ 가상환경 생성 및 활성화

```bash
python -m venv .venv
source .venv/bin/activate    # macOS / Linux
```

```powershell
.venv\Scripts\activate       # Windows
```

---

### 3️⃣ 의존성 설치

```bash
pip install -r requirements.txt
```

---

### 4️⃣ 환경 변수 설정

`.env` 파일 생성:

```env
OPENAI_API_KEY=your_api_key_here
```

> `.env` 파일은 Git에 커밋하지 않습니다.

---

## 🧪 학습 진행 항목

* [ ] AI 기본 개념 정리
* [ ] 프롬프트 패턴 실험
* [ ] OpenAI API 기본 호출
* [ ] 응답 파싱 및 후처리
* [ ] 토큰·비용 관리 실습

---

## 📝 학습 원칙

* 실행되지 않는 코드는 기록하지 않음
* 실험 결과가 있는 코드만 정리
* 불필요한 추상화보다 **명확한 동작 우선**
* 나중에 다시 봐도 이해 가능한 수준으로 정리

---

## ⚠️ 주의 사항

* API Key 및 민감 정보는 절대 커밋하지 않음
* 실습·학습 목적의 저장소
* 상용 서비스 목적 아님

---

## 👤 Author

* 한시연
* 개인 AI 학습 및 실습 기록용 레포지토리
* 지속적으로 업데이트 예정
