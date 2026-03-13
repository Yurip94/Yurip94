# Jungwook Park — AI Agent Engineer

저는 커뮤니케이션 중심으로 실용적인 AI 에이전트 시스템을 설계하고 구축합니다.

- 연락처: qkrqud94@gmail.com
- LinkedIn: https://www.linkedin.com/in/jungwook-park-0a0b733a4
- Notion: https://www.notion.so/yuripking/AI-Agent-Architect-321c9a24feff80d385c9e2a58ad48ac1?source=copy_link

### 프로젝트

#### [Pommit](https://github.com/Pommit/pommit)

- 2026.01 ~ 현재
- GitHub commit 기반 개발자 포트폴리오 생성 AI 에이전트

**Tech Stack**
- AI/Agent: Python, LangGraph, LangChain
- Backend: FastAPI, Supabase
- Monitoring: LangSmith
- Dev: GitPython

**Description**

커밋 히스토리를 분석해 개발자의 숨겨진 역량을 발굴하는 multi-agent 시스템

- Company Analysis Pipeline: repo_agent, tech_blog_agent, job_description_agent로 채용공고·기술 블로그 분석
- User Analysis Pipeline: raw_agent, outline_agent, commit_agent, episode_agent로 커밋 기반 역량 추출
- LangGraph 기반 병렬/순차 오케스트레이션, agent I/O 계약 설계

**담당 제작 기능**
- 채용공고 웹 스크래핑 (job_description_agent): URL·텍스트 2가지 입력 방식, 최대 8,000자 처리, 채용요건 5개 카테고리 구조화 추출, 3종 아티팩트(requirements.yaml, summary.md, requirements.txt) 생성
- 회사 기술 블로그 파싱 및 요구 역량 분석 (tech_blog_agent): URL·HTML·텍스트 3가지 입력 방식, 입력 타입별 신뢰도 차등 적용 (URL 0.85 / HTML 0.75 / text 0.65), 역량 name·category·confidence 3개 필드로 구조화 추출

---

#### [upstage_workflow_pjt](https://github.com/upstage-mini-PJT/upstage_workflow_pjt)

- 2026.02
- 보험금 지급거절 통지서를 받은 사용자가 재심의를 준비할 수 있도록 돕는 AI 워크플로우

**Tech Stack**
- AI/Agent: Python, LangGraph, LangChain
- Document AI: Upstage UIE
- VectorDB: ChromaDB
- Data: Pydantic

**Description**

3단계 파이프라인(온보딩 → 증거 수집 → 데이터 분석) 기반 보험 분쟁 분석 시스템

- Onboarding Agent: 지급거절 통지서 파싱, 이슈 플래닝, 약관 조항 RAG 검색
- Data Analysis Agent: 판례/분쟁사례 비교 스코어링, 성공 확률 계산 (LOW/MEDIUM/HIGH), 증거 팩 생성
- LangGraph MemorySaver 기반 인터럽트/재개 패턴 구현

**담당 제작 기능**
- 판례/분쟁사례 기반 유사 근거 탐색: top-10 검색 후 base score 70% + lexical overlap 30% 가중 재랭킹
- HyDE 쿼리 확장: plain·hyde·reverse_hyde·hybrid_hyde 4가지 쿼리 변형 모드 구현
- 보험 약관 조항·금융 분쟁 판례·유사 조정 사례 3종 VectorDB 구축 (청크 300 tokens / overlap 60 tokens), 8개 스코어링 룰 기반 성공 확률 0–100점 산출 (LOW/MEDIUM/HIGH 3단계)


### 기술스택

#### AI / Agent
![LangChain](https://img.shields.io/badge/LangChain-000000?style=flat&logo=chainlink&logoColor=white) ![LangGraph](https://img.shields.io/badge/LangGraph-1A73E8?style=flat)

#### VectorDB
![Chroma](https://img.shields.io/badge/Chroma-00C897?style=flat)

#### Backend / Infra
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white) ![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat&logo=supabase&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)

#### Monitoring / Tools
![LangSmith](https://img.shields.io/badge/LangSmith-2A2B2D?style=flat) ![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white) ![VSCode](https://img.shields.io/badge/VSCode-007ACC?style=flat&logo=visualstudiocode&logoColor=white)


### 학력/교육
- 한양 사이버 대학교 — 컴퓨터공학과 / 1학년 재학중
- UPSTAGE AI Agent Service deploy - SESAC (Seoul Software ACademy) / 2026년 5월 수료 예정
- KGA 게임 기획 아카데미 / 2021년 12월 ~ 2022 6월
  
### 이력/경험
- Softon Entertainment — 게임 기획 / 캐릭터, 전투 밸런스 
- 세텍 - 사운드 엔지니어
- 모델 및 배우 활동 - [![Naver](https://img.shields.io/badge/Naver-03C75A?style=flat&logo=naver&logoColor=white)](https://search.naver.com/search.naver?where=nexearch&sm=tab_etc&mra=bjky&pkid=1&os=1972608&qvt=0&query=%EB%B0%B0%EC%9A%B0%20%EB%B0%95%EC%A0%95%EC%9A%B1)
