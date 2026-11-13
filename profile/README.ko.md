<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="./assets/devlink-logo-dark.png">
    <source media="(prefers-color-scheme: light)" srcset="./assets/devlink-logo.png">
    <img src="./assets/devlink-logo.png" alt="DevLink" width="480">
  </picture>
</p>

# DevLink

[English](./README.md) | [한국어](./README.ko.md)

**팀원들의 AI 코딩 도구를 연결하는 개발 협업 플랫폼**

DevLink는 서로 다른 AI 코딩 도구를 사용하는 팀원들의 Agent를 연결합니다. 자신의 AI 코딩 도구에서 팀원의 Agent에게 작업을 요청하고, 진행 상태와 결과를 공유할 수 있습니다.

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

## 시작하기

설치부터 AI 도구 연결, 첫 작업 요청과 결과 확인까지 안내합니다.

👉 [사용설명서](https://github.com/SSAFY-URAYAHA/.github/blob/main/docs/DevLink_User_Guide.ko.md)

## Connect With Us

DevLink 팀에 궁금한 점이나 협업 제안이 있다면 이메일로 연락해 주세요.

📧 [mhroh075@gmail.com](mailto:mhroh075@gmail.com)

## Contribute

버그 제보, 문서 수정, 기능 제안, 코드 기여를 환영합니다.

기여 방법과 진행 절차는 [CONTRIBUTING.md](https://github.com/SSAFY-URAYAHA/DevLink_server/blob/develop/CONTRIBUTING.md)를 참고해 주세요.
