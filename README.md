<div align="center">

# 🐋 Yang Jeong Hyeon

## AI / 백엔드 개발자

**AI 기능을 서비스로 연결하고, 실제로 제대로 동작하는지 검증하는 개발자입니다.**

`Python` · `FastAPI` · `RAG` · `Retrieval` · `LLM` · `PostgreSQL` · `Django` · `React`

🌊 **문제를 재현하고 → 측정하고 → 원인을 찾고 → 구조를 개선하고 → 다시 검증합니다.**

</div>

---

## 👋 소개

컴퓨터공학을 전공하고, **AI 기능을 실제 서비스 구조 안에서 안정적으로 동작하게 만드는 과정**에 관심을 두고 개발하고 있습니다.

단순히 기능이 실행되는 것에서 끝내지 않고, 다음 내용을 함께 확인하는 개발 방식을 지향합니다.

- **검색 품질**: RAG가 실제로 필요한 문서를 찾는지
- **데이터 흐름**: 입력부터 최종 응답까지 데이터가 올바르게 전달되는지
- **API 규격**: 기능 간 입력과 출력이 명확하게 연결되는지
- **실패 상황**: 정상 상황뿐 아니라 오류와 예외도 처리되는지
- **테스트와 검증**: 수정한 기능이 실제로 개선되었는지

### 현재 집중하고 있는 분야

`AI 백엔드` · `RAG / 검색` · `LLM 응용` · `API 설계` · `테스트 / 검증`

현재는 개인 프로젝트로 **LoL Commentary AI**를 개발하고 있습니다.

---

## 🧰 기술 스택

### 🤖 AI · RAG · LLM

`RAG` `LLM` `LangChain` `LangGraph` `ChromaDB` `pgvector` `MCP` `NLP`

**할 수 있는 것**

- 문서 수집 및 전처리
- Chunking / Embedding
- Vector DB 검색
- Metadata Filtering
- MMR Search
- Retrieval 평가
- LLM과 검색 결과 연결
- MCP Tool 연동

### ⚙️ 백엔드 · 언어

`Python` `FastAPI` `Django` `Java` `Kotlin` `JavaScript`

**주요 경험**

- REST API 구현
- FastAPI 기반 AI 서비스 연결
- Django 기반 웹 서비스 구현
- 입력 / 출력 Schema 설계
- 예외 처리 및 정책 분기
- Java Socket 프로그래밍

### 🖥️ 프론트엔드 · 데이터

`React` `Vite` `Streamlit` `PostgreSQL` `MySQL` `scikit-learn`

**주요 경험**

- React 기반 서비스 화면 구성
- Streamlit 데이터 서비스 통합
- PostgreSQL / MySQL 데이터 저장 및 조회
- 머신러닝 분석 결과를 웹 서비스와 연결

### 🧪 개발 품질 · 도구

`Git` `GitHub Actions` `pytest` `Ruff` `ty` `uv` `Docker` `AWS` `Maven`

**개발할 때 중요하게 보는 것**

- Lint / Format
- Type Check
- Unit Test
- Coverage
- CI
- Git Branch / PR 기반 협업
- 실행 환경 재현

---

# 🚀 대표 프로젝트

## 1. 🎮 LoL Commentary AI
### 개인 프로젝트 · 개발 진행 중

League of Legends 데이터를 기반으로 **데이터 수집 → 검색 → 상황 분석 → AI 해설**로 이어지는 시스템을 만들고 있습니다.

### 현재 구현한 기반

- FastAPI 백엔드 및 Health API
- Riot 패치노트 Raw Collector
- `uv` 기반 Python 의존성 관리
- Ruff Lint / Format
- ty Type Check
- pytest / Coverage 검증
- GitHub Actions CI

### 앞으로 연결할 핵심 흐름

`경기 데이터` → `검색 / RAG` → `상황 분석` → `LLM 해설`

**저장소**  
https://github.com/didwjdgus90/lol-commentary-ai

---

## 2. 🧠 RAG 코딩테스트 학습 지원 시스템
### 팀 프로젝트 · RAG Retrieval 구현 및 설계

코딩테스트 문제 분석, 코드 실행 검증, 알고리즘 개념 검색을 결합한 **RAG 기반 AI 학습 지원 시스템**입니다.

### 담당한 부분

- 알고리즘 학습 문서 Retrieval 파이프라인 구현
- Alias Mapping 적용
- Metadata Filtering 적용
- MMR Search 적용
- Document Voting 적용
- 실패 질의 분석을 통한 검색 구조 개선

### 검색 성능 개선

팀 프로젝트 README의 Hard Query 50 평가 기준입니다.

| 지표 | 개선 전 | 개선 후 |
|---|---:|---:|
| Hit@1 | 0.420 | **0.900** |
| Recall@5 | 0.640 | **1.000** |

**개인 Fork**  
https://github.com/didwjdgus90/SKN29-3RD-1Team

---

## 3. 💧 WaterBridge
### 팀 프로젝트 · MCP / Retrieval 연동

정수기 구독 고객의 문의부터 AI 안내, 상담, 방문 A/S, 해결 확인까지 하나의 흐름으로 연결하는 **AI 고객케어 플랫폼**입니다.

### 담당한 부분

- Android Customer App 검증
- 실제 Backend Remote E2E 검증
- MCP Server / Client 기본 구조 구현
- `search_official_evidence` MCP Tool 구현
- 기존 `VectorSearchService`와 MCP Tool 연동
- MCP Tool 입력 / 출력 Schema 구현
- 정책 허용 / 차단 경로 검증
- 단위 테스트 작성 및 검증

**팀 저장소**  
https://github.com/SKNETWORKS-FAMILY-AICAMP/SKN29-FINAL-4TEAM

**기여 PR #24**  
https://github.com/SKNETWORKS-FAMILY-AICAMP/SKN29-FINAL-4TEAM/pull/24

---

# 📂 주요 팀 프로젝트

<details>
<summary><strong>🧑‍💻 WOOK'S CODING — Django 웹 UI / 화면 흐름</strong></summary>

<br/>

AI가 학습 상태를 기억하고 힌트, 오답노트 RAG, 미니튜터 기능을 제공하는 코딩 학습 플랫폼입니다.

### 담당한 부분

- Django 기반 서비스 UI 구성 및 통합
- main merge 이후 깨진 UI 흐름 복구
- 계정 / 인증 / 오답노트 / 문제풀이 화면 레이아웃 보정
- 반응형 환경의 overflow / clipping 문제 개선
- 프로필 아바타 및 레벨 UI 정리

**개인 Fork**  
https://github.com/didwjdgus90/SKN29-4TH-1Team

</details>

<br/>

<details>
<summary><strong>📈 TrendIt — 프론트엔드 / 백엔드</strong></summary>

<br/>

YouTube KR 트렌딩 데이터를 기반으로 콘텐츠 성과와 지속 가능성을 분석·예측하는 플랫폼입니다.

### 담당한 부분

- React / Vite 기반 프론트엔드 구성 참여
- FastAPI 백엔드 구성 및 연동 참여
- 분석·예측 결과를 웹 UI와 연결
- README, 발표자료, 서비스 화면 자료 정리

**개인 Fork**  
https://github.com/didwjdgus90/SKN29-2nd-1Team

</details>

<br/>

<details>
<summary><strong>🚗 자동차 등록·보험 정보 서비스 — DB / Streamlit 통합</strong></summary>

<br/>

자동차 등록 현황과 보험 정보를 조회·시각화하는 Streamlit 기반 데이터 서비스입니다.

### 담당한 부분

- 차량 등록 현황 데이터베이스 구축
- 자동차 등록 데이터 조회 구조 구성
- 팀원별 Streamlit 기능 취합 및 통합
- 자동차 등록 현황 조회 화면 구성

**개인 Fork**  
https://github.com/didwjdgus90/SKN29-1st-4team

</details>

---

# 📚 학습 및 리팩터링

## SKN29 학습 아카이브

SK Networks Family AI Camp에서 학습하고 실습한 내용을 정리한 저장소입니다.

`Python` → `Web` → `ML / DL` → `NLP` → `LLM / RAG` → `Docker / AWS`

https://github.com/didwjdgus90/skn29

## Java Socket Chat

Java 17 기반으로 기존 Socket 프로젝트를 다시 정리하고 있는 리팩터링 프로젝트입니다.

`Java 17` · `TCP Socket` · `Multi-client` · `Concurrency` · `Maven`

https://github.com/didwjdgus90/javaproject

---

# 🔍 개발 방식

```text
문제 발견
   ↓
재현
   ↓
측정
   ↓
실패 원인 분석
   ↓
구조 / 검색 / API 규격 개선
   ↓
테스트
   ↓
결과 기록
```

- 기능이 실행됐다는 사실보다 **왜 제대로 동작하는지 설명할 수 있는 상태**를 중요하게 생각합니다.
- RAG에서는 모델을 바로 교체하기보다 **검색 실패 원인과 Retrieval 구조**를 먼저 확인합니다.
- AI 기능도 일반 백엔드 기능처럼 **입력 / 출력 / 예외 / 테스트 기준**을 관리합니다.
- 팀 프로젝트에서는 **팀 전체 결과와 제가 직접 담당한 영역을 구분해서 기록**합니다.

---

<div align="center">

## 🐋 Yang Jeong Hyeon

**AI / 백엔드 개발자**

🌊 하나씩 깊게 이해하고, 검증하면서 개선하는 개발자가 되겠습니다.

</div>
