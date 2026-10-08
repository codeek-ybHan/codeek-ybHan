![Yebin Han — Finance × Data × AI](./assets/profile-header.svg)

<div align="center">

**재무의 논리를 이해하고, 데이터와 AI로 업무 흐름을 구현합니다.**

Economics · Business Administration · Information Statistics

[ValuFlow](https://github.com/codeek-ybHan/ValuFlow) &nbsp; / &nbsp; [Research Automation](https://github.com/codeek-ybHan/valuation-career-automation) &nbsp; / &nbsp; [일로ON](https://github.com/codeek-ybHan/illo-on)

</div>

<br>

## About

경제학·경영학·정보통계학을 바탕으로 업무의 구조를 이해하고, 데이터와 AI를 활용해 반복 업무를 실제 서비스로 구현합니다.  
기업가치평가 업무를 대상으로 **재무데이터 수집 → 계산 → AI 분석 → 근거 검증 → 보고서**를 연결한 ValuFlow를 개발·배포했습니다.

- **Focus** — Financial Analysis · Valuation · AI Workflow Automation
- **Interests** — RAG · AI Agent · Tool Calling · Financial AI
- **Training** — SKALA · Web, Data, Cloud & AI

<br>

## Selected Projects

### 01 &nbsp; [ValuFlow](https://github.com/codeek-ybHan/ValuFlow)
**From Financial Statements to AI-powered Valuation.**

OpenDART 재무데이터부터 DCF/WACC, AI 기반 분석·근거 검색, 검증 및 보고서 생성까지 연결한 기업가치평가 업무 자동화 플랫폼입니다.

- OpenDART 실제 재무데이터 수집·정규화 및 DCF/WACC Valuation Engine 구현
- Tool Calling 기반 AI Analyst와 사업보고서·PDF Hybrid RAG 구성
- Claim–Evidence 기반 Grounding, Sensitivity·Scenario·Report Automation 구현
- React / FastAPI / PostgreSQL·pgvector 기반 Production 배포

`TypeScript` `React` `Python` `FastAPI` `PostgreSQL` `pgvector` `RAG` `AI Agent`

🔗 [Live Demo](https://valu-flow.vercel.app) · `v1.0.0`

<br>

### 02 &nbsp; [Valuation Career Automation](https://github.com/codeek-ybHan/valuation-career-automation)
**뉴스와 공시를 가치평가 학습으로 연결하는 리서치 파이프라인.**

뉴스·공시 수집부터 가치평가 관점 분석, 학습 포인트·퀴즈 생성, Notion 저장과 이메일 발송까지 연결합니다.

- Pydantic 기반 Structured Output으로 AI 출력 형식 정의
- 원문 출처 보존과 처리 이력 기반 중복 방지
- 수집·분석·저장·발송 단계 분리, 단계별 오류 처리

`Python` `OpenAI API` `OpenDART` `Notion / Gmail API` `GitHub Actions`

<br>

### 03 &nbsp; [일로ON](https://github.com/codeek-ybHan/illo-on)
**회의에서 결정된 일을 실제 업무 실행으로 연결합니다.**

회의 내용을 AI로 분석하고, 사용자가 검토한 Action Point를 Task·Sprint로 연결하는 업무관리 서비스입니다.

- 회의·메신저 내용 분석 → Action Point → 사용자 검토 → 업무 등록
- Task에서 관련 회의로 이동해 업무 생성 맥락 추적
- JWT 인증, REST API, Docker Compose 기반 서비스 구성

`Vue` `Java` `Spring Boot` `Spring AI` `MySQL` `Docker`

<br>

## Toolbox

| Area | Technologies |
| :--- | :--- |
| **Languages** | Python · Java · TypeScript · JavaScript · SQL |
| **Web & Backend** | React · Vue · FastAPI · Spring Boot · REST API |
| **Data** | PostgreSQL · pgvector · MySQL · Pandas |
| **AI** | LLM · RAG · AI Agent · Tool Calling · Structured Output |
| **Infrastructure** | Docker · Kubernetes · Vercel · GitHub Actions |

<br>

## Building Principles

**도메인부터 이해합니다.**  
자동화할 업무의 흐름과 계산 근거를 먼저 정리합니다.

**계산과 해석을 분리합니다.**  
재무 계산은 검증 가능한 로직으로, AI는 정보 정리와 해석 지원에 활용합니다.

**검토 가능한 결과를 만듭니다.**  
데이터 출처와 가정을 남기고, 사용자의 판단이 필요한 지점을 분명히 합니다.

---

<div align="center">
<sub>Understand the domain. Build the workflow. Make it useful.</sub>
</div>
