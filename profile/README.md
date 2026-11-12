# 🔗 DevLink

**팀원들의 AI 코딩 도구를 연결하는 개발 협업 플랫폼**

DevLink는 서로 다른 AI 코딩 도구를 사용하는 팀원들의 Agent를 연결합니다. 팀원의 Agent에게 작업을 요청하고 진행 상태와 결과를 공유해, 개발자가 답변을 복사해 전달하거나 작업 맥락을 반복해서 설명하는 부담을 줄입니다.

[Related Repositories](#related-repositories) · [Connect With Us](#connect-with-us) · [Contribute](#contribute)

> 현재 개발 중인 프로젝트입니다. 설치·실행 방법과 지원 범위는 각 저장소의 README에서 확인해 주세요.

## How It Works

1. **작업 요청** — 자신의 AI 코딩 도구에서 팀원의 Agent에게 요청과 필요한 맥락을 전달합니다.
2. **담당자 확인** — 요청을 받은 담당자가 내용을 확인하고 수락합니다.
3. **작업과 결과 공유** — 담당자의 Agent가 로컬 프로젝트에서 작업하고, 요청자는 진행 상태와 결과를 확인합니다.

## Related Repositories

DevLink는 클라이언트, 중앙 서버, 웹 관리 화면으로 구성됩니다. 시작하려면 [DevLink_client](https://github.com/SSAFY-URAYAHA/DevLink_client)의 README를 확인해 주세요.

| Repository | 역할 | 주요 기술 |
| --- | --- | --- |
| [DevLink_client](https://github.com/SSAFY-URAYAHA/DevLink_client) | 개발자 PC에서 AI 코딩 도구와 중앙 서버를 연결하는 CLI·로컬 브로커·MCP 서버 | Rust, TypeScript |
| [DevLink_server](https://github.com/SSAFY-URAYAHA/DevLink_server) | 사용자·팀·Agent의 인증과 권한, 작업 상태·결과 저장, 실시간 요청 전달을 담당하는 중앙 서버 | Java, Spring Boot, PostgreSQL |
| [DevLink_frontend](https://github.com/SSAFY-URAYAHA/DevLink_frontend) | 계정·팀·Agent를 등록하고 관리하는 웹 화면 | React, TypeScript, Vite |

각 저장소의 README에서 해당 구성요소의 설치·실행 방법과 개발 문서를 확인할 수 있습니다.

## Connect With Us

질문, 사용 경험, 기능 아이디어를 들려주세요. 관련 저장소의 GitHub Issues에서 이야기할 수 있습니다.

| 채널 | 이야기할 내용 |
| --- | --- |
| [Client Issues](https://github.com/SSAFY-URAYAHA/DevLink_client/issues) | 설치, CLI, AI 코딩 도구 연결 |
| [Server Issues](https://github.com/SSAFY-URAYAHA/DevLink_server/issues) | API, 인증, 작업 상태와 요청 전달 |
| [Frontend Issues](https://github.com/SSAFY-URAYAHA/DevLink_frontend/issues) | 웹 화면, 계정·팀·Agent 관리 |

## Contribute

버그 제보, 문서 수정, 기능 제안, 코드 기여를 환영합니다. 작은 오탈자 수정부터 함께해 주세요.

1. **기여할 저장소 선택** — 위 목록에서 관심 있는 영역을 선택하고, README와 기여 안내가 있다면 먼저 확인해 주세요.
2. **기존 Issue 확인** — 같은 내용의 논의가 있는지 살펴봐 주세요. 버그를 제보할 때는 사용 환경, 재현 방법, 기대한 동작과 실제 동작을 적어 주세요. 큰 변경은 Issue에서 방향을 먼저 논의해 주세요.
3. **변경 및 검증** — 저장소를 Fork하고 작업 브랜치에서 수정한 뒤, 해당 저장소의 안내에 따라 동작을 확인해 주세요.
4. **Pull Request 제출** — 변경 목적, 주요 내용, 관련 Issue와 검증 결과를 적어 주세요. 화면 변경이 있다면 스크린샷도 함께 첨부해 주세요.
