1. touch 명령어를 통해 gitignore 파일 생성
touch .gitignore
2. branch 생성 및 스위치
git branch (브랜치이름) -> 생성
git switch (브랜치이름) -> 브랜치 변경 (기본은 main)
git merge (병합할 브랜치 이름) -> 다른 브랜치의 변경 사항을 현재 브랜치에 적용하고 싶을 때
git log -> 커밋 기록들
3. add, commit, push
git add . -> 모든 파일 staged 상태 변경
git commit -m "커밋 메세지" -> staged 파일의 변경사항을 로컬 레포에 반영
git push origin (브랜치이름) -> 로컬 레포에 반영된 내용을 원격 레포에 보냄
git status -> 현재 상태
 
