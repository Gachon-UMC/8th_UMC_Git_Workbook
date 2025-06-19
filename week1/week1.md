# Week 1 과제 - Git 요약

## Git이란?
- 파일의 변경 사항을 추적하고, 여러 사람이 협업할 수 있게 해주는 분산 버전 관리 시스템

## 파일 관리 흐름
1. Working Directory에서 파일 작업
2. `add` 명령어로 Staging Area에 올리기
3. `commit`으로 Local Repository에 기록
4. `push`로 원격 저장소에 반영

## .gitignore
- Git이 추적하지 않을 파일/폴더를 지정
- 예시:
  - `*.log` (확장자 기준)
  - `node_modules/` (폴더 전체)
  - `ignore.md` (특정 파일)

## 브랜치
- 기능 단위로 작업을 분리하기 위한 독립 공간
- `main` 브랜치를 기준으로 여러 브랜치 생성 가능
- 서로에게 영향을 주지 않고 작업한 뒤, `merge`로 통합

## Merge와 HEAD
- `merge`: 브랜치의 변경 내용을 다른 브랜치로 통합
- `HEAD`: 현재 브랜치에서 마지막 커밋을 가리키는 포인터

## Issue & Pull Request
- Issue: 작업 내용(버그, 기능 추가 등)을 공유하는 공간
- Pull Request: 브랜치에서 작업한 내용을 메인 브랜치에 반영 요청

---

