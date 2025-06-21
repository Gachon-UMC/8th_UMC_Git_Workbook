# 📘 Git 정리 - Week1

---

## 🧠 Git이란?

- Git은 **버전 관리 시스템(VCS)** 으로, 파일의 변경 이력을 저장하고 협업을 원활하게 해줍니다.
- 내 작업이 기록되는 공간은 **Local Repository (로컬 저장소)**입니다.

---

## 🛠️ Git은 어떻게 사용할까요?

1. **원격 저장소(clone) 후 로컬 저장소 연결**
   - `git clone <URL>`
   - GitHub와 내 컴퓨터를 연결해 협업 준비

2. **`.gitignore`로 추적 제외할 파일 설정**
   - 예: 로그, 빌드 결과물, 환경변수 파일 등

3. **add → commit → push 단계로 변경 이력 기록**
   - `git add .` : 변경 파일 스테이징
   - `git commit -m "메시지"` : 스냅샷 생성
   - `git push` : 원격 저장소에 업로드

4. **파일 상태 확인하기**
   - `git status` : 수정된 파일 목록 및 상태 확인

---

## 🌱 브랜치(Branch)란?

1. 브랜치는 **내가 작업하는 독립된 공간**입니다.
   - `main`에 영향을 주지 않고 실험이나 개발 가능

2. **브랜치 만들고 전환하기**
   - 생성: `git checkout -b week1-yeye`
   - 전환: `git switch week1-yeye`

3. **브랜치 병합(Merge)**
   - `git merge <브랜치명>` : 브랜치 작업 결과를 합치기

---

## 🕵️ 커밋 기록은 어떻게 확인할까요?

1. `git log` : 커밋 히스토리 확인 (작성자, 메시지, 시간 등)

2. `HEAD` : 현재 내가 가리키는 최신 커밋
   - `git show HEAD` 또는 `git log -1`

---

## ❓ Issue와 PR(Pull Request)이란?

1. **Issue**: 작업 단위나 목표를 정리해두는 기능
   - ex) 버그, 할 일, 기능 제안 등

2. **PR(Pull Request)**: 작업 내용을 메인 브랜치에 반영해달라고 요청하는 것
   - 브랜치에서 작업 후 PR 작성
   - 예: `week1-yeye` → `main`

---