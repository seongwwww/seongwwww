<h1 align="center">김성원 · Seongwon Kim</h1>

<p align="center">
  <b>문제 정의부터 배포까지, AI로 A–Z를 완주합니다</b><br/>
  <sub>울산대학교 IT융합학과 · 2027년 2월 졸업예정 · 울산</sub>
</p>

<p align="center">
  <a href="mailto:s260822@naver.com"><img src="https://img.shields.io/badge/Email-s260822@naver.com-333?style=flat-square&logo=gmail&logoColor=white"/></a>
  <img src="https://img.shields.io/badge/npm_downloads-2,215-CB3837?style=flat-square&logo=npm&logoColor=white"/>
</p>

---

## 어떤 사람인가

변화하는 **AI 시장 흐름**을 쫓는 데 관심이 많습니다. 기술을 깊이 파고들어 실제로 적용하고, 그래서 **성능이 올라가는 것을 보는 데 갈증**이 있습니다.

울산에 살면서 자연스럽게 **제조업에 AI를 붙였을 때 만들어질 변화의 크기**를 계속 생각하게 됐습니다. 지금 시대에 맞는 방향이라고 판단하고, 그쪽으로 커리어를 잡고 있습니다.

**AI를 어디에 쓰고 어디에 쓰지 않을지 판단하는 것**을 중요하게 생각합니다. 판정처럼 검증 가능해야 하는 일은 규칙과 통계로, 서술처럼 사람 말이 필요한 일은 LLM으로 나눠 설계합니다.

---

## 대표 프로젝트

### 🛠 [Nextify](https://github.com/Capstone-0123/Nextify) — React → Next.js 마이그레이션 자동화 CLI
> 🏅 **교내 캡스톤 대상** · 🏅 **2026 울산 WAVE 대학생 아이디어 피칭 대회 최우수**

`npx nextify-cli` 로 설치되는 실제 배포 도구. **npm 누적 다운로드 2,215회**, VS Code 확장까지 마켓플레이스에 배포했습니다.
마이그레이션을 5단계로 쪼개 **되돌릴 수 있는 단위**로 만들고, AI가 바꾼 코드를 파일에 바로 덮어쓰지 않고 **diff 패널에서 사람이 승인**하게 설계했습니다.

`Node.js` `VS Code Extension API` `Gemini CLI` `npm 배포`

### 🏙 [정책핏 인천](https://github.com/rokmc1893/INU-X-UOU) — 청년정책 중복·공백 판정 도구
> 🏅 **인천대·울산대 초광역 AI 해커톤 장려**

36시간 동안 리서치 → 데이터 설계 → 개발 → 발표까지 혼자 돌린 프로젝트 (팀 전체 94커밋 중 91). 공무원이 쓰는 「유사·중복 사업 자체 검토서」 초안을 자동 생성합니다.
**판정은 전부 규칙이 하고 LLM은 원문 정규화에만** 씁니다 — 결재에 올라가는 문서라 판정 근거를 설명할 수 있어야 했기 때문입니다. 정답셋으로 채점하고, 시연 실패에 대비해 폴백을 3중으로 깔았습니다.

`Python` `Streamlit` `Neo4j / Cypher` `규칙 엔진`

### 🌙 [실은 (silen)](https://github.com/seongwwww/silen) — 하루의 놓친 차이를 찾아주는 앱
1인 개발 · **커밋 287개**. DB 스키마부터 인증, 워커 파이프라인, LLM, 프론트까지 전부 직접 만들었습니다.
차이 검출은 LLM이 아니라 **정보이론의 surprisal(Jeffreys 평활)** 로 계산합니다. 결정론적이라 골든셋 회귀 테스트를 CI 게이트로 걸 수 있고, 비용이 들지 않으며, 환각이 끼어들 자리가 없습니다.
**완료의 정의에 `eval` 통과를 넣었습니다.**

`Next.js` `TypeScript` `Python` `PostgreSQL` `pgmq` `Vertex AI Gemini`

### 🤖 [AI Org Simulation](https://github.com/Google-AI-Agent-Challenge-eeeee/ai-org-simulation) — 멀티에이전트 조직 시뮬레이터
Google AI Agent Challenge 출품작. PRD를 넣으면 가상 조직이 일해보고 최적 팀 조합을 리포트로 돌려줍니다. **shadow roleplay 에이전트 파이프라인 전체(Phase 0–10)** 와 SSE 스트리밍 API를 담당했습니다.
에이전트의 자유도를 프롬프트가 아니라 **모듈 경계와 검증 게이트**로 제한했습니다 — human-in-the-loop 체크포인트, 토큰 한도 검증, 커버리지 체크.

`Python` `FastAPI` `Next.js` `Docker` `SSE`

---

## 기술 스택

**Frontend**
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react)
![Next.js](https://img.shields.io/badge/Next.js-000?style=flat-square&logo=nextdotjs)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![TanStack Query](https://img.shields.io/badge/TanStack_Query-FF4154?style=flat-square&logo=reactquery&logoColor=white)
![Zustand](https://img.shields.io/badge/Zustand-443E38?style=flat-square)

**Backend**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)

**Data · AI**
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Neo4j](https://img.shields.io/badge/Neo4j-4581C3?style=flat-square&logo=neo4j&logoColor=white)
![Vertex AI](https://img.shields.io/badge/Vertex_AI-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)

**Infra**
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![npm](https://img.shields.io/badge/npm-CB3837?style=flat-square&logo=npm&logoColor=white)
![Netlify](https://img.shields.io/badge/Netlify-00C7B7?style=flat-square&logo=netlify&logoColor=white)

---

## 지금 공부하는 것

- **제조 AX** — AI를 제조 현장 프로세스에 붙이는 방법
- **백엔드 인프라 · AWS** — 만든 것을 안정적으로 운영하는 쪽
- **Java** — 백엔드 역량을 한 단계 더

---

## 기록

| | |
|---|---|
| 주요 프로젝트 | **14개** · 커밋 704 · PR 117 |
| 협업 경험 | 2~7인 팀 **12개 프로젝트** |
| 활동 기간 | 2023.09 ~ 현재 |
| 소속 | UMC 7th·9th · 구름톤 유니브 4기 · 울산대 가온누리 |

<br/>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=seongwwww&show_icons=true&hide_border=true&count_private=true&include_all_commits=true&theme=default" height="150"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=seongwwww&layout=compact&hide_border=true&langs_count=8&theme=default" height="150"/>
</p>
