## 📁 작업 디렉토리로 이동
```bash
cd ~/Desktop/GIT
```
작업 디렉토리로 이동합니다.

---

## 🔍 현재 Git 상태 확인
```bash
git status
```
수정한 파일이 있는지, 커밋할 게 있는지 확인합니다.

---

## ✅ 변경된 파일 Git에 등록
```bash
git add .
```
모든 변경 파일을 Git에 등록합니다.

---

## 💬 커밋 메시지를 작성하여 저장
```bash
git commit -m "작업한 내용 요약"
```
예: `git commit -m "로그인 기능 구현"`

---

## 🚀 원격 저장소(GitHub 등)로 업로드
```bash
git push origin main
```
현재 브랜치(main)의 변경 사항을 업로드합니다.

---

## 🔄 원격 저장소에서 최신 내용 가져오기
```bash
git pull origin main
```
다른 사람이 올린 최신 내용을 가져옵니다.

---

## 🆕 새 브랜치 생성 후 이동
```bash
git checkout -b feature/브랜치이름
```
예: `git checkout -b feature/login-form`

---

## 🔀 브랜치 병합
```bash
git checkout main
git merge feature/브랜치이름
```
작업 내용을 main 브랜치로 병합합니다.

---

## 🗑️ 변경 사항 되돌리기
```bash
git restore 파일명
```
수정한 내용을 원래대로 되돌립니다.

---

## ⏪ 최근 커밋 되돌리기
```bash
git reset --soft HEAD~1
```
가장 최근 커밋을 되돌립니다. (변경 내용은 그대로 유지됨)

---

## 🧠 기타 유용한 명령어
```bash
git log --oneline
```
커밋 기록을 간단히 확인합니다.

```bash
git branch
```
현재 브랜치와 목록을 확인합니다.

```bash
git remote -v
```
연결된 원격 저장소 정보를 확인합니다.
