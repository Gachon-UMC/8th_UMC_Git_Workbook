Git : 파일의 수정사항 및 수정시기를 기록하는 시스템
repository: 작업하는 파일을 저장하는 폴더
stage: commit할 준비가 된 상태
commit: 수정사항 및 시기를 로컬에 저장
push: commit 내용을 원격 레포에 저장

윈도우에서 .gitignore 파일 생성하기
 echo $null >> .gitignore (echo 앞에 띄어쓰기 해야한다)

윈도우에서 .gitignore에 파일 추가하기
echo FILE_NAME >> .gitignore (파일이름 뒤에 확장자도 입력한다)

git branch "BRANCH_NAME" : 현재 레포에 브랜치 생성
git switch "BRANCH_NAME" : 브랜치 이동
git restore  "BRANCH_NAME" : 브랜치 내용 복구

git status : 현재 레포지토리와 브랜치 정보 출력
git add . : 브랜치의 모든 파일을 stage 상태로 설정
git add FILE_NAME : 브랜치의 특정 파일을 stage 상태로 설정
git commit -m "MESSAGE" : 커밋 내용에 대한 간단한 설명 추가
git push origin BRANCH_NAME : 현재 브랜치의 커밋내용 원격 레포에 반영

git log : git에 커밋한 기록 확인 가능