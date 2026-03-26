# tech-org

**AI가 운영하는 테크 에이전시**

> AI와 사람이 협업하는 새로운 개발 문화를 만들고, 누구나 양질의 소프트웨어를 가질 수 있게 합니다.

---

## About

전 구성원이 AI로 구성된 가상 테크 에이전시입니다. CEO, CTO, COO부터 9개 팀까지 모든 구성원이 AI. 24시간 가동, 일관된 품질을 제공합니다.

## Core Values

| 원칙 | 설명 |
|------|------|
| **WHY 우선** | 모든 결정에 '왜'를 기록합니다. 이유 없는 결정은 하지 않습니다. |
| **문서 우선** | 코드 전에 설계, 설계 전에 문서. 문서 없는 작업은 진행하지 않습니다. |
| **빠른 실행** | MVP 우선, 점진적 개선. 완벽한 계획보다 빠른 실행과 피드백을 추구합니다. |
| **품질** | QA 없는 배포는 없습니다. 모든 기능은 체크리스트 기반으로 검증합니다. |

## Portfolio

| 프로젝트 | 설명 | 기술 스택 | 링크 |
|----------|------|-----------|------|
| **Live Chat Widget** | 실시간 채팅 위젯 SaaS (WebSocket + 텔레그램 연동 + 멀티테넌트) | Go, WebSocket, PG, MongoDB, Redis | [chat.shaul.kr](https://chat.shaul.kr) |
| **Web RPG Game** | 서버-권위 턴제 수집형 RPG (5 Act, 강화/합성/도감) | Go, PG, MongoDB, Redis, Keycloak | [rpg.shaul.kr](https://rpg.shaul.kr) |
| **Tech Blog** | 기술 블로그 플랫폼 (CMS + 시리즈 + MinIO 이미지) | Go, PG, MinIO, HTMX | [blog.shaul.kr](https://blog.shaul.kr) |
| **URL Shortener** | URL 단축 + 클릭 분석 (GeoIP, 디바이스, 시간대) | Go, PG, Redis, GeoIP | [s.shaul.kr](https://s.shaul.kr) |
| **YouTube Script** | YouTube 영상 스크립트 추출기 (SSO + 권한 관리) | Go, PG, yt-dlp, Keycloak | [youtube.shaul.kr](https://youtube.shaul.kr) |
| **AI Shorts** | AI 자동화 YouTube Shorts 파이프라인 | Python, Gemini, ElevenLabs, Go | [ai-shorts.shaul.kr](https://ai-shorts.shaul.kr) |
| **Company Website** | tech-org 소개 + 포트폴리오 + 프로젝트 문의 | HTML, Tailwind, Alpine.js, Go | [www.shaul.kr](https://www.shaul.kr) |
| **Developer Resume** | 개발자 이력서 사이트 | HTML, Tailwind, Go | [resume.shaul.kr](https://resume.shaul.kr) |

## Tech Stack

```
Backend     Go (Echo v4), Python
Database    PostgreSQL, MongoDB, Redis
Auth        Keycloak SSO (OAuth 2.0)
Storage     MinIO S3
Frontend    HTMX, Alpine.js, Tailwind CSS, Vanilla JS
Infra       Docker, systemd, Caddy, Cloudflare Tunnel
Monitoring  Prometheus, Grafana, Loki
AI/ML       Gemini, ElevenLabs, HuggingFace
```

## Process

```
문서 (PRD → API 명세서 → 아키텍처 → QA) → Gate 0 승인
  → MVP 구현 → MVP 배포 → Gate 1
    → v1.0 구현 → v1.0 릴리스 → Gate 2
      → v1.1 운영 안정화 → 회고
```

모든 의사결정에 WHY/WHY NOT을 기록하고, Plane으로 이슈를 추적합니다.

## Links

- **Website**: [www.shaul.kr](https://www.shaul.kr)
- **Wiki**: [wiki.shaul.kr](https://wiki.shaul.kr)
