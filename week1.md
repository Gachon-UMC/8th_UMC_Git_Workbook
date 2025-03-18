# 1주차 과제 정리 

## Git 기초 명령어

- `git clone [URL]` : 원격 저장소 복제
- `git status` : 내 파일 상태를 확
- `git add .` : 모든 파일 staged
- `git add (파일 이름)` : 특정 파일 staged
- `git commit -m "커밋 메시지"` : 변경 사항 저장
- `git push origin 브랜치명` : 원격 저장소로 업로드
- `git branch (브랜치 이름)` : 브랜치 생성
- `git switch (브랜치 이름)` : 해당 브랜치로 이동

## push와 origin
- 로컬 레포에 반영된 내용을 원격 레포에 보내기 위해서는 `push` 라는 명령어 사용
- `origin` 은 원격 레포지토리(github)의 URL을 담고 있는 키워드


## .gitignore 사용법
 `.gitignore` 파일을 만들어 특정 파일을 Git에서 제외할 수 있음.
 `touch .gitignore` 로 폴더에 `.gitignore` 파일 생성
