# Git에서 자주 사용하는 명령어들

### 기본 설정 관련 명령어

- git config --global [user.name](http://user.name/) "이름"
- git config --global user.email "이메일주소"
- git config --list

### 저장소 초기화 및 상태 확인

- git init
- git status
- git log
    - git log --oneline : 로그 한 줄만 보기

### 파일 추적 및 커밋

- git add [파일명]
- git add .
- git commit -m "커밋 메시지"
- git commit -am "메시지"
- git reset [파일명]
- git reset --hard

### 브랜치 관리

- git branch
- git branch -a
- git branch [브랜치명]
- git checkout [브랜치명]
- git checkout -b [브랜치명]
- git switch [브랜치명]
- git switch -c [브랜치명]
- git merge [브랜치명]
- git branch -d [브랜치명]

### 원격 저장소 관리

- git remote
    - git remote add origin [URL]
    - git remote -v
- git push
    - git push -u origin [브랜치명]
    - git push --force
- git pull

### 히스토리 확인 및 되돌리기

- git diff
    - git diff --staged
- git reset HEAD
- git revert [커밋 해시]

### 기타 명령어

- git stash
- git rebase --abort