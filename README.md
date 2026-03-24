# 뭐쓸까? (mwossulkka)

> AI 코딩 & 생산성 도구 비교 가이드 — 2026년 3월 기준

AI 도구가 너무 많아서 뭘 써야 할지 모르겠다면, 여기서 한눈에 비교하세요.

---

## 카테고리 한눈에 보기

| 카테고리 | 설명 | 도구 수 |
|---|---|---|
| [범용 AI 채팅](#-범용-ai-채팅) | 웹/앱 기반 대화형 AI | 6개 |
| [코딩 에이전트 (CLI)](#-코딩-에이전트-cli) | 터미널에서 자율적으로 코드 수정 | 4개 |
| [AI IDE](#-ai-ide) | 에디터에 AI가 내장된 통합 환경 | 6개 |
| [AI 코드 어시스턴트](#-ai-코드-어시스턴트) | 기존 IDE에 플러그인으로 추가 | 3개 |
| [AI 앱 빌더](#-ai-앱-빌더) | 자연어로 앱 생성 + 배포 | 4개 |
| [자율 에이전트](#-자율-에이전트) | 목표만 주면 알아서 완수 | 2개 |
| [오픈소스](#-오픈소스) | 무료, 자체 호스팅, 모델 자유 선택 | 7개 |

---

## 범용 AI 채팅

웹이나 앱에서 대화형으로 코딩 질문, 코드 생성, 디버깅을 수행하는 AI 서비스입니다.

| | ChatGPT | Claude.ai | Gemini | Copilot (MS) | Grok | Perplexity |
|---|---|---|---|---|---|---|
| **제공사** | OpenAI | Anthropic | Google | Microsoft | xAI | Perplexity AI |
| **공식 사이트** | [chatgpt.com](https://chatgpt.com) | [claude.com](https://claude.com) | [gemini.google.com](https://gemini.google.com) | [microsoft.com/copilot](https://www.microsoft.com/en-us/microsoft-365-copilot) | [x.ai](https://x.ai) | [perplexity.ai](https://www.perplexity.ai) |
| **최신 모델** | GPT-5.4 | Claude Opus 4.6 | Gemini 3.1 Pro | GPT-5.4 + Claude | Grok 4.20 | Sonar Pro |
| **무료** | O | O | O | O (M365 포함) | O | O |
| **유료 시작가** | $20/월 (Plus) | $20/월 (Pro) | $19.99/월 (AI Pro) | $18/월 (Business) | $30/월 (SuperGrok) | $20/월 (Pro) |
| **최고 요금** | $200/월 (Pro) | $200/월 (Max) | ~$42/월 (Ultra) | $30/월 (Enterprise) | $30/월 | $325/seat/월 (Ent Max) |
| **컨텍스트** | 128K (Pro) | 1M | 1M | - | **2M** | 모델별 상이 |
| **코딩 강점** | Canvas + Codex 통합 | 가장 깨끗한 코드 품질 | 빠른 응답 + 창작 미디어 | M365 깊은 통합 | X 실시간 데이터 | 검색+인용 통합 |
| **고유 특징** | SuperApp 발표 (Chat+Codex+브라우저) | Extended Thinking, Agent Teams | Veo 영상/Imagen 이미지 생성 | Agent 365 자율 에이전트 | 코딩 전용 모델 (grok-code-fast-1) | Perplexity Computer (자율 에이전트) |

---

## 코딩 에이전트 (CLI)

터미널에서 실행되며, 코드베이스를 이해하고 자율적으로 코드를 수정하는 에이전트입니다.

| | Claude Code | Codex CLI | Gemini CLI | Aider |
|---|---|---|---|---|
| **제공사** | Anthropic | OpenAI | Google | 오픈소스 커뮤니티 |
| **공식 사이트** | [code.claude.com](https://code.claude.com) | [developers.openai.com/codex/cli](https://developers.openai.com/codex/cli) | [github.com/google-gemini/gemini-cli](https://github.com/google-gemini/gemini-cli) | [aider.chat](https://aider.chat) |
| **오픈소스** | X | O (Rust) | O (Apache 2.0) | O (Apache 2.0) |
| **무료** | X | X | **O (1,000 req/일)** | O (API 비용만) |
| **유료 시작가** | $20/월 (Pro) | $20/월 (Plus) | $0 (무료) | $0 (API 비용만) |
| **모델 선택** | Anthropic만 | OpenAI만 | Gemini만 | **모든 LLM** |
| **컨텍스트** | 200K+ | GPT-5 컨텍스트 | **1M** (2.5 Pro) | 모델별 상이 |
| **샌드박스** | X | **O (기본 활성)** | X | X |
| **Git 통합** | O | 부분적 | 부분적 | **네이티브 (자동 커밋)** |
| **멀티 에이전트** | **O (Agent Teams)** | O (서브에이전트) | X (ReAct 루프) | X |
| **MCP 통합** | **O (300+ 서비스)** | O | O | X |
| **고유 특징** | CLAUDE.md 지속 학습, Skills, Hooks | 가장 안전한 샌드박스 실행 | Google Search 그라운딩 | 가장 성숙한 Git 워크플로우 |
| **GitHub Stars** | - | - | - | 42.3K |

---

## AI IDE

AI가 내장된 통합 개발 환경(IDE)입니다. 에디터 자체를 교체하여 사용합니다.

| | Cursor | Windsurf | Antigravity | Kiro | Trae | GitHub Copilot |
|---|---|---|---|---|---|---|
| **제공사** | Cursor Inc. | Cognition AI | **Google DeepMind** | Amazon (AWS) | ByteDance | Microsoft/GitHub |
| **공식 사이트** | [cursor.com](https://cursor.com) | [windsurf.com](https://windsurf.com) | [antigravity.google](https://antigravity.google) | [kiro.dev](https://kiro.dev) | [trae.ai](https://www.trae.ai) | [github.com/features/copilot](https://github.com/features/copilot) |
| **기반** | VS Code 포크 | VS Code 포크 | VS Code 포크 (Windsurf 계열) | VS Code 포크 | VS Code 포크 | 플러그인 (9+ IDE) |
| **무료** | O (제한적) | O (제한적) | **O (관대한 무료)** | O (50 크레딧/월) | **O (강력한 무료)** | O (2,000 완성/월) |
| **유료 시작가** | $20/월 | $20/월 | 구독 필요 | $20/월 | $10/월 | **$10/월** |
| **최고 요금** | $200/월 (Ultra) | $200/월 (Max) | - | $200/월 (Power) | $10/월 | $39/user/월 (Ent) |
| **모델** | Multi (OpenAI, Claude, Gemini, xAI) | Multi + SWE-1.5 | Gemini 3 Pro, Claude, GPT | Claude Sonnet | Claude 4, GPT-4o, DeepSeek | Multi (Claude, GPT, Gemini) |
| **자동완성** | **최고 수준** | 우수 | 우수 | 우수 | 우수 | 양호 |
| **백그라운드 에이전트** | O (병렬) | X | **O (다중 에이전트)** | O (Agent Hooks) | X | O |
| **고유 특징** | Autonomy Slider, 병렬 Cloud Agent | Cascade 메모리 시스템 | **Manager View + 브라우저 자동화** | **Spec 기반 개발 (EARS)** | 무료 Claude 4 제공 | **GitHub 네이티브 통합** |
| **주의사항** | VS Code 포크만 | Cognition 인수 (Devin 팀) | Windsurf 인수 ($24억) | AWS 계정 불필요 | **ByteDance 데이터 수집 주의** | Premium 요청 미터링 |

---

## AI 코드 어시스턴트

기존 IDE에 플러그인으로 추가하여 사용하는 AI 코딩 도구입니다.

| | Cody | Tabnine | Amazon Q Developer |
|---|---|---|---|
| **제공사** | Sourcegraph | Tabnine | Amazon (AWS) |
| **공식 사이트** | [sourcegraph.com](https://sourcegraph.com) | [tabnine.com](https://www.tabnine.com) | [aws.amazon.com/q/developer](https://aws.amazon.com/q/developer) |
| **무료** | O | **X (2025년 종료)** | O (50 req/월) |
| **유료 시작가** | **$9/user/월** | $39/user/월 | $19/user/월 |
| **IDE 지원** | VS Code, JetBrains | VS Code, JetBrains, Eclipse, VS | VS Code, JetBrains, Eclipse, VS |
| **자체 호스팅** | O (Enterprise) | **O (에어갭 포함)** | X |
| **코딩 강점** | 대규모 코드베이스 이해 최강 | 데이터 프라이버시 최강 | AWS 생태계 네이티브 |
| **고유 특징** | Sourcegraph 코드 그래프 인덱싱 | SOC 2, GDPR, ISO 27001 인증 | 레거시 현대화 (Java/.NET), IP 보상 |
| **대상** | 대규모 모노레포 팀 | 금융/의료/국방 | AWS 기반 팀 |

---

## AI 앱 빌더

자연어로 앱을 생성하고 배포까지 완결하는 서비스입니다. 코딩 경험이 적어도 사용 가능합니다.

| | Bolt.new | v0.app | Lovable | Replit Agent |
|---|---|---|---|---|
| **제공사** | StackBlitz | Vercel | Lovable (스웨덴) | Replit |
| **공식 사이트** | [bolt.new](https://bolt.new) | [v0.app](https://v0.app) | [lovable.dev](https://lovable.dev) | [replit.com](https://replit.com) |
| **무료** | O (100만 토큰) | O ($5 크레딧) | O (일 5 크레딧) | O (체험) |
| **유료 시작가** | $25/월 | $30/user/월 | $25/월 | $17/월 |
| **배포** | Netlify | **Vercel (원클릭)** | 내장 | **내장 (호스팅 포함)** |
| **DB 통합** | Bolt Cloud 내장 | X | Supabase | **PostgreSQL 내장** |
| **디자인 입력** | Figma 임포트 | Design Mode | Chat Mode | Design Canvas |
| **팀 협업** | O (Teams 플랜) | O | **O (실시간 20명)** | O (최대 15명) |
| **고유 특징** | 브라우저 내 완전 개발환경 | Next.js/Vercel 완벽 통합 | $6.6B 밸류에이션, 유럽 최대 | 50+ 언어, 병렬 태스크 |
| **대상** | 빠른 프로토타이핑 | Next.js/React 개발자 | 비개발자 창업자 | 1인 개발~소규모 팀 |

---

## 자율 에이전트

목표만 제시하면 연구, 계획, 실행, 검증까지 자율적으로 완수하는 AI 에이전트입니다.

| | Claude Cowork | Devin |
|---|---|---|
| **제공사** | Anthropic | Cognition AI |
| **공식 사이트** | [claude.com](https://claude.com) | [devin.ai](https://devin.ai) |
| **출시** | 2026년 1월 | 2025년 (2.0: 2026년) |
| **대상** | **지식 노동자** (비개발자) | **소프트웨어 엔지니어** |
| **환경** | 데스크톱 앱 | 클라우드 IDE (브라우저) |
| **유료 시작가** | $20/월 (Pro에 포함) | $20/월 (Core) |
| **병렬 실행** | - | O (최대 10 세션) |
| **연동** | Google Drive, Gmail, Slack, DocuSign, FactSet | GitHub, 자체 IDE |
| **주요 워크플로우** | 파일 정리, 문서 작성, 리서치 종합, 데이터 추출 | 코드 작성, 버그 수정, 모델 학습, 앱 배포 |
| **고유 특징** | **Claude Code 엔진의 비개발자 버전** | Devin Wiki (자동 코드베이스 문서화), Interactive Planning |
| **과금 방식** | 구독 (Pro/Max) | ACU 기반 ($2.25/ACU, ~15분) |

---

## 오픈소스

무료로 사용 가능하고, 모델을 자유롭게 선택할 수 있는 오픈소스 도구들입니다.

| | OpenClaw | OpenCode | Cline | Aider | Tabby | Continue.dev | Goose |
|---|---|---|---|---|---|---|---|
| **GitHub Stars** | **333K** | 95K+ | 59.3K | 42.3K | 33K | 32K | 29.4K |
| **라이선스** | MIT | 오픈소스 | Apache 2.0 | Apache 2.0 | - | Apache 2.0 | Apache 2.0 |
| **유형** | 범용 AI 어시스턴트 | 터미널 코딩 에이전트 | VS Code 에이전트 | CLI 코딩 에이전트 | 자체호스팅 코드완성 | IDE 어시스턴트 + CI | 자율 코딩 에이전트 |
| **GitHub** | [openclaw/openclaw](https://github.com/openclaw/openclaw) | [opencode-ai/opencode](https://github.com/opencode-ai/opencode) | [cline/cline](https://github.com/cline/cline) | [Aider-AI/aider](https://github.com/Aider-AI/aider) | [TabbyML/tabby](https://github.com/TabbyML/tabby) | [continuedev/continue](https://github.com/continuedev/continue) | [block/goose](https://github.com/block/goose) |
| **모델** | 다중 공급자 | 75+ 모델 | 다중 공급자 + Ollama | **모든 LLM** | 로컬 모델 전용 | 모든 모델 | 모든 LLM |
| **로컬 모델** | O | O | O (Ollama, LM Studio) | O | **O (전용)** | O (Ollama) | O |
| **자체 호스팅** | O (Docker) | O | - | - | **O (완전 온프레미스)** | O | O |
| **IDE 통합** | - | ACP (JetBrains, Zed 등) | **VS Code, JetBrains, Cursor, Windsurf** | - | VS Code, JetBrains 등 | VS Code, JetBrains, CLI | CLI + 데스크톱 |
| **고유 특징** | 50+ 메신저 통합, 5400+ Skills | TUI, LSP 자동구성, 세션 공유 | 5M+ 설치, 브라우저 제어 | Git-first 자동커밋 | 코드 외부 전송 0% | CI/CD 파이프라인 통합 | Block(Square) 제작, MCP |
| **주의** | 코딩 외 범용 도구 | 원래 repo 아카이브, Crush로 분기 | - | - | GPU 필요 | - | - |

---

## 어떤 도구를 써야 할까?

### 용도별 추천

| 용도 | 추천 도구 | 이유 |
|---|---|---|
| **일상 코딩 + 자동완성** | Cursor, Windsurf | 최고 수준의 탭 자동완성과 AI IDE 경험 |
| **대규모 리팩토링 + 아키텍처** | **Claude Code** | 200K+ 컨텍스트, 멀티에이전트, MCP 300+ 통합 |
| **빠른 대량 편집** | Codex CLI | 샌드박스 실행, 240+ tok/s 속도 |
| **무료로 시작** | Gemini CLI, Trae, Antigravity | 무료 티어가 실용적 수준 |
| **GitHub 워크플로우** | GitHub Copilot | PR 자동화, 코드 리뷰, 이슈 관리 |
| **AWS 기반 개발** | Amazon Q Developer, Kiro | AWS 네이티브 통합 |
| **보안/규정 준수** | Tabnine | 에어갭 배포, SOC 2/GDPR/ISO 인증 |
| **비개발자 업무 자동화** | Claude Cowork | 파일 정리, 문서 작성, 리서치 |
| **노코드 앱 제작** | Lovable, Bolt.new | 코딩 없이 풀스택 앱 배포 |
| **오픈소스 + 모델 자유** | Aider, OpenCode | API 비용만, 모든 LLM 지원 |
| **검색 기반 코딩 리서치** | Perplexity | 실시간 웹 검색 + 인용 통합 |

### 커뮤니티 한 줄 평

> **"Cursor는 최고의 AI 에디터. Claude Code는 최고의 AI 엔지니어. Windsurf는 최고의 가성비."**

### 실전 조합 패턴

많은 개발자들이 단일 도구가 아닌 **조합**으로 사용합니다:

- **일상 코딩**: Cursor 또는 Windsurf (자동완성 + 인라인 편집)
- **복잡한 작업**: Claude Code (아키텍처, 보안 리뷰, 대규모 리팩토링)
- **빠른 검증**: Codex CLI (안전한 샌드박스 실행)
- **리서치**: Perplexity (최신 문서/API 검색)

---

## 가격 비교 요약

### 무료로 쓸 수 있는 도구

| 도구 | 무료 범위 |
|---|---|
| Gemini CLI | 1,000 req/일 (실용적 수준) |
| Antigravity | 관대한 무료 (Gemini 3 Pro) |
| Trae | 월 5,000 자동완성 + Claude 4 |
| GitHub Copilot | 2,000 완성 + 50 프리미엄/월 |
| Aider | 완전 무료 (API 비용만) |

### 월 $20 이하

| 도구 | 가격 | 포함 내용 |
|---|---|---|
| GitHub Copilot Pro | $10/월 | 무제한 자동완성 + 에이전트 |
| Trae Pro | $10/월 | 확장 사용량 |
| Cody Pro | $9/user/월 | 대규모 코드베이스 AI |
| Amazon Q Pro | $19/user/월 | AWS 통합 + 취약점 스캔 |

### 월 $20

| 도구 | 가격 | 포함 내용 |
|---|---|---|
| ChatGPT Plus | $20/월 | GPT-5.2 + Codex |
| Claude Pro | $20/월 | Claude Code + Cowork |
| Cursor Pro | $20/월 | 자동완성 + Cloud Agent |
| Windsurf Pro | $20/월 | Cascade + SWE-1.5 |
| Kiro Pro | $20/월 | 1,000 크레딧 |
| Perplexity Pro | $20/월 | 무제한 Pro 쿼리 |
| Devin Core | $20/월 | ACU 기반 에이전트 |

---

## 기여하기

이 프로젝트는 AI 도구 시장의 빠른 변화를 추적합니다. 정보가 오래되었거나 새로운 도구가 등장했다면 PR을 보내주세요!

- 새로운 도구 추가
- 가격/기능 정보 업데이트
- 오류 수정

---

## 라이선스

MIT License

---

> 마지막 업데이트: 2026-03-24
>
> 이 문서의 정보는 각 서비스의 공식 웹사이트와 신뢰할 수 있는 리뷰 사이트에서 수집되었습니다. 가격과 기능은 수시로 변경될 수 있으므로, 최신 정보는 각 공식 사이트를 확인해주세요.
