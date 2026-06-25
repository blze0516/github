# Version Matrix

이 문서는 GitHub Admin 180 학습 과정에서 사용할 도구와 운영 기준 버전을 정리합니다.

## 1. 기본 프로그램

| 구분 | 고정 버전 | 사용 목적 |
|---|---:|---|
| Git | 2.54.0 | Git 기본 명령어, 브랜치, 병합, 충돌 해결 |
| Git LFS | 3.7.1 | 대용량 파일 관리 |
| GitHub CLI | 2.93.0 | 터미널에서 Issue, PR, repo, release 관리 |
| GitHub Desktop | 3.5.8 | CLI 보조 GUI 도구 |
| Visual Studio Code | 1.122.0 | 실습용 에디터 |
| Node.js | 24.16.0 LTS | GitHub Actions JavaScript 실습 |

## 2. GitHub Actions 기준

| 구분 | 고정 버전 |
|---|---:|
| GitHub-hosted runner | ubuntu-24.04 |
| actions/checkout | v5 |
| actions/setup-node | v6.4.0 |
| actions/cache | v5 |

## 3. 운영 규칙

| 항목 | 기준 |
|---|---|
| 기본 브랜치명 | main |
| 기능 브랜치 접두사 | feature/ |
| 버그 수정 브랜치 접두사 | fix/ |
| 문서 브랜치 접두사 | docs/ |
| 릴니다.
3. GitHub Desktop은 3.5.8 기준으로 보조 도구로만 사용합니다.
4. Git LFS는 3.7.1 기준으로 대용량 파일 관리 Day에서 사용합니다.
5. VS Code는 1.122.0 기준으로 설명합니다.
6. GitHub Actions는 `runs-on: ubuntu-24.04`로 고정합니다.
7. Node.js가 필요한 GitHub Actions 예제는 Node.js 24.16.0 LTS를 사용합니다.
8. GitHub Actions 예제는 `actions/checkout@v5`, `actions/setup-node@v6.4.0`, `actions/cache@v5`를 사용합니다.
9. 비밀번호, 토큰, SSH private key, PAT, API key는 절대 저장소에 커밋하지 않습니다.
10. GitHub Enterprise 기능은 실제 Enterprise 계정이 없어도 개념, 운영 설계, 문서 실습 중심으로 진행합니다.
