# 깃허브 사용법 정리

## 기본 용어

### 1. Switch : 브랜치 전환

### 2. Commit : 로컬에서 작업한 파일 변경사항을 github에 업로드

#### 사용법 
git push origin main

### 3. Pull : 깃허브의 최신 변경 사항을 내 로컬로 가져온다

#### 사용법 
git pull origin main

### 4. Branch : 코드를 독립적으로 개발할 수 있도록 해준다

#### 사용법 

git branch new-feature
git checkout new-feature (브랜치 이동시)

### 5. Merge : 다른 브랜치에서 작업한 내용을 main 브랜치로 합친다

#### 사용법 

git checkout  main
git merge new-feature (new-feature 브랜치를 main에 병합)

### 6. Clone : 깃허브에 있는 레포지토리를 내 컴퓨터로 다운로드한다

#### 사용법

git clone https://github.com/your-username/my-repo.git
