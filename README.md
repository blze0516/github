# GitHub Admin 180

Git과 GitHub를 초급부터 관리자급까지 180일 동안 학습하는 실습 저장소입니다.

## 학습 목표

이 저장소의 목표는 Git 기초부터 GitHub 협업, GitHub Actions, 보안, 조직 관리자, Enterprise 관리자 개념까지 단계적으로 학습하는 것입니다.

## 전체 흐름

| 기간 | 단계 | 목표 |
|---|---|---|
| Day 1~30 | GitHub 초급 기초 | Git/GitHub 기본, README, Issue, PR |
| Day 31~60 | 팀 협업과 저장소 운영 | PR Template, CODEOWNERS, Branch Protection, Rulesets |
| Day 61~90 | GitHub Actions와 자동화 | CI/CD, Secrets, Environments, Release 자동화 |
| Day 91~120 | GitHub 보안과 품질 관리 | Dependabot, Secret Scanning, CodeQL, Security Policy |
| Day 121~150 | 조직 관리자와 저장소 관리자 | Organization, Teams, Roles, Audit Log, API 자동화 |
| Day 151~180 | Enterprise 관리자와 최종 프로젝트 | SSO/SCIM, Billing, Compliance, Enterprise 정책, 최종 프로젝트 |

## 기본 운영 규칙

- 기본 브랜치명은 `main`을 사용합니다.
- 기능 브랜치는 `feature/` 접두사를 사용합니다.
- 버그 수정 브랜치는 `fix/` 접두사를 사용합니다.
- 문서 작업 브랜치는 `docs/` 접두사를 사용합니다.
- 기본 PR 병합 방식은 Squash merge를 기준으로 학습합니다.

## 보안 주의사항

다음 정보는 절대 저장소에 커밋하지 않습니다.

- 비밀번호
- 토큰
- SSH private key
- Personal Access Token
- API key
- 실제 서비스 접속 정보

## Day별 학습 위치

- 강의 노트: `days/dayNNN/lecture.md`
- 실습 기록: `days/dayNNN/practice.md`
- 회고: `days/dayNNN/review.md`
