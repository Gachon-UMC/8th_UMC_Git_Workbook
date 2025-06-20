## Git이란?
Git: 파일의 변경 사항을 추적하고, 여러 사용자가 협업할 수 있도록 도와주는 분산 버전 관리 시스템 (DVCS)

- 파일의 변경 사항 추적
- 여러 사용자 협업 조율
- 분산 시스템: 각각의 컴퓨터가 전체 히스토리를 가짐


## Git이 관리하는 3가지 영역
- Working Directory: 현재 작업 중인 공간
- Staging Area: 커밋할 파일을 준비하는 공간 (git add)
- Local Repository: 커밋된 기록이 저장되는 공간 (git commit)
변경 흐름: Working Directory → Staging Area → Local Repository

## 추적 제외: .gitignore
- Git이 추적하지 않을 파일/폴더 지정


## 브랜치 (Branch)
- 브랜치 = 독립적인 작업 공간
- 기능 단위로 나누어 작업 가능
- main은 기본 브랜치

## 커밋 기록 확인
- git log

## Issue란?
- 작업 단위로 세부 목표를 설정
- 담당자, 라벨, 설명 등을 포함
- 협업 시 소통/기록용으로 사용

## Pull Request (PR)
- 작업 브랜치를 메인 브랜치에 반영 요청
- 리뷰어 지정 가능 (Code Review)
- 작업 내용을 요약해 설명