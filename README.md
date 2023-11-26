# gitCommand

## 1. 기존에 작업하던 프로젝트 github에 올리는법 

#### 깃허브에 들어가서 repository 새로 생성한다. (단. Read.ME 만들지말것!!! 나중에 commit할때 충돌남!!) 

#### 생성후 repository 주소 복사한다.
    https://github.com/hachanghyun/chatGptLottoWebView.git

#### 기존작업중인 프로젝트 디렉토리안에 들어간다 (일반폴더에서 git 저장소로 변환)
    git init 

#### 추적하지 않는 파일에 붉은글씨로 자신이 commit 해야할 파일 표시해준다
    git status

#### 자신이 commit 할 파일을 추가해준다 ("git add ." 은 모든파일 선택, git add <파일/디렉토리경로>)
    git add .
    git add *
    git add <파일/디렉토리 경로명>

#### 추가했던 파일 commit 
    git commit -m "커밋메시지"

#### github repository에 자신의 프로젝트 추가
    git remote add origin <조금 전 repository에서 복사한 주소>

#### 커밋한 파일을 push (git push [저장소이름] [브랜치이름])
    git push origin main(master)
    
## 2. 기타 git 명령어 

#### remote의 commit을 가져오고 병합 (git fetch + git merge)
        git pull

#### 사용자 성정 정보 확인
        git config --list

#### 사용자 이름 , Email 설정
        git config --global user.email "자신의이메일"
        git config --global user.name "자신의 이름/닉네임"
        
#### 사용자 설정 정보 확인
        git config --global user.email 
        git config --global user.name 
        
#### 기존에 사용 중인 저장소를 clone 해서 가져옴
        git clone [url]

#### 브랜치 목록 조회 (*가 현재 브랜치)
        git branch

#### 브랜치 신규 생성
        git branch [브랜치네임]

#### 브랜치 변경후 해당파일을 Working directory에 복사
        git checkout [변경하고자하는 브랜치명]

#### githun token값 
        https://'토큰값'@github.com 으로 프로젝트 소스트리에 설정해주면됨.
        

        
    
