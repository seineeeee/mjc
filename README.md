# github 명령어 정리
## 1. 설정과 초기화
#### 전역 사용자명/이메일 구성하기 
* >git config - -global user.name"Your name"
* >`git config - -global user.email"Your email address"`
## 2. 저장소 만들기
#### 기존 프로젝트를 git저장소로 만드는 방법
* >`git init`
#### 다른 서버에 있는 저장소를 clone으로 저장하기
* >`git clone git://github.com/mjc.grit.git`
## 3. 수정하고 저장소에 저장하기
#### 파일의 상태 확인하기
* >`git status`
#### 파일을 새로 추적하기
* >`git add README`
#### 변경사항 커밋하기
* >`git commit -m "변경된 메시지 내용을 입력"` 
#### 파일 삭제하기
* >`git rm text.txt`
#### 변경된 내용 푸쉬(발행)하기
* >`git push - u origin master`
## 4. 브랜치
#### 지역 브랜치 목록 보기
* >`git branch`
#### 새로운 브랜치 생성하기
* >`git branch <새로운 브랜치>`
#### 브랜치를 옮기거나 브랜치명 변경하기
* >`git checkout -m <기존 브랜치> <새로운 브랜치>`
#### 다른 브랜치에 합치기
* >`git merge - -squash`
#### 브랜치 삭제하기
* >`git branch -d<삭제할 브랜치>`
## git 이력
#### 모든 이력 보기
* >`git log`
#### 1개의 항목반 보이도록 로그 개수 제한
* >`git log -1`
#### 두 지점 사이의 커밋 로그 보기
* >`git log<시작 지점>...<끝 지점>`

# MarkDown 문법
## 제목 Headers
* >
