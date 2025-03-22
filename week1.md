# Git이란?

-   분산 버전 관리 시스템

## 파일 관리 과정

1. working directory에서 작업
2. add 명령어를 통해 modified 된 파일을 staging area에 올려둠
3. commit을 통해 local repository에 기록!
4. 로컬 레포의 변경 사항을 원격 레에 반영하기 위해 push 명령어 사용

## .gitignore

-   추적되지 않아야 할 파일 목록 지정
-   특정 폴더나 확장자 추적 해제 시
    -   \*.(확장자 이름)
    -   (폴더 이름)/

> git clone (레포지토리 주소)
>
> > 로컬 레포와 원격 레포 연결

> git add .
>
> > 모든 파일을 staged 상태로 변경

> git add (파일 이름)
>
> > 특정 파일만 staged 상태로 변경

> git commit -m "(커밋 메시지)"
>
> > 로컬 레포에 변경 사항 반영

> git push origin (브랜치 이름)
>
> > 원격 레포에 변경 사항 보냄
> >
> > > origin: 원격 레포의 url을 담고 있는 키워드

> git status
>
> > 파일 상태 확인

## 브랜치

-   서로에게 영향을 주지 않는 작업을 진행하기 위해 브랜치 생성
-   기능 별로 브랜치 나누고 관리리
-   기본 브랜치는 main

> git branch (브랜치 이름)
>
> > 브랜치 생성

> git switch (브랜치 이름)
>
> > 브랜치 전환

## 커밋 기록

-   HEAD: 현재 브랜치의 최신 커밋을 참조

> git log (브랜치 이름)
>
> > 커밋 기록 조회

## Issue

-   브랜치를 나누기 전 팀원들과 작업 현황, 기능 구현, 버그 수정 등을 공유하기 위해 생성
-   제목, 내용, Assignees, Labels, Projects, Milestone, Development로 구성

## Pull Request

-   브랜치에서 작업한 내용을 메인에 반영해 줄 것을 요청
-   제목, 내용, Reviewers, Assignees, Labels, Projects, Milestone, Development로 구성
-   merge 대신 pull request 주로 사용
