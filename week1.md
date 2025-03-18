# Git 이란?
**파일의 변경 사항을 추적**하고 **여러 사용자 간에 해당 파일들의 작업들을 조율**하기 위한 *분산 버전 관리 시스템*

## Git에서 파일은 어떻게 관리될까?
### Working Directory
현재 내가 작업하고 있는 공간(폴더)를 칭함
### Staging Area
내 파일의 변경사항을 반영하는 공간
- 변경없음 (unmodified)<br>
변경되지 않은 파일을 의미함
- 변경됨(modified)<br>
변경된 파일을 의미함

- 스테이지됨(staged)<br>
`commit`을 위한 준비 단계로, `modified` 된 파일 중 선택적으로 해당 파일을 stage해서 해당 파일만 커밋할 수 있도록 한다. 즉 커밋이 준비된 상태를 의미한다.

### Local Repository
현재 내 작업이 기록되는 곳

# Git의 Repository
`Repository name` : 레포지토리의 이름<br>
`Description` : 레포지토리의 부가적인 설명을 작성<br>
`Public`/`Private` : 레포지토리의 공개 여부 결정

# .gitignore
`.gitignore` 파일은 워킹 디렉토리 내에서 추적되지 않아야 하는 파일 목록을 지정하는 파일이다.

파일의 이름을 적거나 특정 폴더나 확장자를 적어 추적을 해제할 수도 있다.

# Git의 기본 명령어 모음
`git add {파일이름}` : 파일을 `staged`상태로 변경<br>
만일 모든 파일을 staged 상태로 변경하고 싶다면 `git add .`을 사용

`git commit -m "(커밋 메세지)"` : `staged`된 파일들의 변경 사항을 로컬 레포에 반영하기 위해 `commit` 명령어를 사용한다. <br>
이때 메세지를 통해 어떤 작업을 했는지 알릴 수 있다.

`git push origin (브랜치 이름)` : 로컬 에포에 반영된 내용을 원격 레포에 보내는 명령어.
- `origin` : 원격 레포지토리의 URL을 담고 있는 키워드

`git status` : 파일의 상태를 확인할 수 있음

# Git의 Branch
한 레포지토리에서 독립적인 작업 영역

`git branch (브랜치 이름)` : 브랜치를 생성

`git switch (브랜치 이름)` : 브랜치 간 이동 명령어

`git merge (병합할 브랜치)` : 현재 브랜치에서 다른 브랜치의 변경사항을 현재 브랜치에 적용시키고 싶을 때 사용하는 명령어.

# 커밋 기록 확인하기
`git log` : 정확히 언제 파일을 수정했는지, 그 때 파일 내에서 어떠한 변화가 있었는지 기록을 살펴볼 수 있다.

`HEAD` : 브랜치의 최신 커밋을 참조하는 값으로, 현재 내 위치의 브랜치의 최신 커밋을 포인터로 가리키고 있다고 생각하면 됨.

# Issue와 PR
`Issue` : 팀원과 프로젝트의 작업 진행 현황과 기능 구현, 버그 수정, 리팩토링 등을 공유하기 위해 생성하는 것.
- 이슈 제목
- 이슈 내용
- Assignees
- Labels
- Projects,Milestone
- Development <br>

등이 들어감

`Pull Request` :  메인 브랜치에게 Pull을 받아줄 것을 요청하는 것.

Issue와 동일하게 내용들이 들어가며, Github 레포지토리 주소에 접속한 후 `Pull requests`를 클릭하여, 오른쪽 상단 `New pull request`를 클릭하여 작성할 수 있음

