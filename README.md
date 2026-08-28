# 양정현 | AI / Backend Developer

기능이 실행되는 것과 **제대로 동작하는 것은 다르다**는 기준으로 개발합니다.
AI 기능을 구현할 때도 모델 호출 자체보다 **검색 품질, 데이터 흐름, API 계약, 테스트와 검증**까지 확인하는 과정을 중요하게 생각합니다.

## Focus

`Python` · `FastAPI` · `Django` · `RAG / Retrieval` · `LLM` · `PostgreSQL / pgvector` · `Java` · `React`

---

## Featured Projects

### 1. LoL Commentary AI — Personal Project

League of Legends 데이터를 기반으로 **RAG · Machine Learning · LLM**을 결합하여 경기 상황에 맞는 AI 해설 시스템을 개발하는 개인 프로젝트입니다.

- FastAPI Backend 및 Health API 구축
- `uv` 기반 dependency 관리
- Ruff lint / format, ty type check
- pytest 기반 테스트 및 coverage 검증
- GitHub Actions CI 구성
- 데이터 수집 → Retrieval → LLM Commentary로 이어지는 서비스 구조 설계

**Tech**
Python · FastAPI · RAG · LLM · Retrieval · PostgreSQL · React

**Repository**
https://github.com/didwjdgus90/lol-commentary-ai

---

### 2. RAG Coding Test Learning Platform — RAG Retrieval

코딩테스트 문제 분석, 코드 실행 검증, RAG 기반 알고리즘 개념 검색을 결합한 AI 학습 지원 시스템입니다.

**담당: RAG Retrieval 구현 및 검색 구조 개선**

- 알고리즘 학습 문서 Retrieval 파이프라인 구현
- Alias Mapping, Metadata Filtering, MMR Search, Document Voting 적용
- Hard Query 50 기준 **Hit@1 0.420 → 0.900**
- Hard Query 50 기준 **Recall@5 0.640 → 1.000**
- 실패 질의 분석을 기반으로 Retrieval 구조 개선

**Tech**
Python · FastAPI · LangGraph · LangChain · ChromaDB · RAG

**Team Repository**
https://github.com/SKNETWORKS-FAMILY-AICAMP/SKN29-3RD-1Team

---

### 3. WaterBridge — AI Customer Care Platform

정수기 구독 고객의 문의부터 AI 안내, 상담, 방문 A/S, 해결 확인까지 하나의 문의 이력으로 연결하는 AI 고객케어 팀 프로젝트입니다.

**주요 기여**

- Android Customer App / Remote E2E 검증
- MCP Server / Client Bootstrap 구현
- `search_official_evidence` MCP Tool 구현
- 기존 `VectorSearchService` Retriever와 MCP Tool 연동
- MCP Tool Input / Output Schema 구현
- 정책 허용·차단 경로 및 단위 테스트 검증

**Tech**
Python · FastAPI · MCP · RAG · PostgreSQL / pgvector · Kotlin · React

**Team Repository**
https://github.com/SKNETWORKS-FAMILY-AICAMP/SKN29-FINAL-4TEAM

**Contribution PR**
https://github.com/SKNETWORKS-FAMILY-AICAMP/SKN29-FINAL-4TEAM/pull/24

---

### 4. SKN29 Learning Archive

SK Networks Family AI Camp 29기에서 학습하고 실습한 내용을 주제별로 정리한 학습 아카이브입니다.

`Python → Web → ML/DL → NLP → LLM/RAG → Docker/AWS`

**Repository**
https://github.com/didwjdgus90/skn29

---

### 5. Java Socket Chat — Refactoring Project

기존 Java Socket 프로그래밍 프로젝트를 Java 17 기반 구조로 다시 설계하고 있는 개인 리팩터링 프로젝트입니다.

**Focus**
Java 17 · TCP Socket · Multi-client Communication · Concurrency · Maven

**Repository**
https://github.com/didwjdgus90/javaproject

---

## Other Team Projects

### YouTube Trend Analysis

YouTube API 데이터를 수집하고 영상 지표를 기반으로 Feature를 구성하여 머신러닝 분석 결과를 웹 서비스와 연결한 프로젝트입니다.

https://github.com/SKNETWORKS-FAMILY-AICAMP/SKN29-2nd-1Team

### Automobile Information Service

외부 자동차 정보 API를 연동하고 데이터를 조회·가공하여 Streamlit 기반 사용자 화면으로 제공한 프로젝트입니다.

https://github.com/SKNETWORKS-FAMILY-AICAMP/SKN29-1st-4team

---

## Engineering Approach

- 실행 여부만 확인하지 않고 **실패 케이스와 검증 기준**을 함께 확인합니다.
- RAG에서는 모델 교체보다 먼저 **검색 실패 원인과 Retrieval 구조**를 분석합니다.
- AI 기능도 일반 Backend 기능처럼 **입출력 계약, 테스트, 예외 경로**를 명확하게 관리합니다.
- 학습 자료와 실제 프로젝트 Repository의 역할을 분리해 관리합니다.