# Git과 GitHub 차이

## 한 문장으로 정리

Git은 내 컴퓨터에서 변경 기록을 저장하는 도구이고,
GitHub는 그 기록을 온라인에서 공유하고 협업하는 플랫폼이다.

## 비교표

| 구분 | Git | GitHub |
|---|---|---|
| 종류 | 버전 관리 도구 | 온라인 협업 플랫폼 |
| 위치 | 내 컴퓨터에서 사용 가능 | 인터넷 서비스 |
| 핵심 역할 | 변경 기록 저장 | 저장소 공유, 협업, 리뷰, 자동화 |
| 인터넷 필요 여부 | 기본 사용은 불필요 | 필요 |
| 대표 명령/기능 | add, commit, log, branch | repository, issue, pull request, actions |
| 실무 의미 | 작업 기록 관리 | 팀 협업과 운영 관리 |

## 쉬운 비유

- Git은 게임 저장 슬롯이다.
- Commit은 저장 지점이다.
- GitHub는 팀원이 함께 보는 온라인 작업실이다.

## 주의할 점

비밀번호, 토큰, SSH private key, PAT, API key는 절대 저장소에 커밋하지 않는다.

## Local Repository와 Remote Repository

| 구분 | 의미 | 위치 |
|---|---|---|
| Local Repository | 내 컴퓨터에 있는 Git 저장소 | 내 PC |
| Remote Repository | GitHub에 있는 온라인 저장소 | GitHub |

## push와 pull

| 명령어 | 방향 | 의미 |
|---|---|---|
| git push | Local → Remote | 내 커밋을 GitHub에 올린다. |
| git pull | Remote → Local | GitHub의 변경 내용을 내 컴퓨터로 가져온다. |
| git clone | Remote → Local | GitHub 저장소를 처음 복사한다. |
