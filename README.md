# github 명령어 정리
## 1. 설정과 초기화
#### 전역 사용자명/이메일 구성하기 
* >`git config - -global user.name"Your name"`
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
* > `#`으로 시작하는 텍스트이다. <br> #은 하나부터 여섯개까지 쓸 수 있고, 늘어날때마다 제목의 수준이 내려간다(보통 글씨 크기가 작아진다.)
* > #h1<br> ##h2 <br> ###h3 <br> ####h4
* ># h1
* >## h2
* >### h3
* >#### h4

## 인용 Blockquotes
* > `(>)`으로 시작하는 텍스트
* > (>)인용문 <br> `(>>)`인용문 안의 인용문
## 코드 블럭 Code Blocks
* > ```혹은 ~~~코드 첫 줄과 마지막 줄에 Back quote (`)또는 물결 (~)3개 삽입
* > ~~~이것은 코드 블럭 입니다~~~ <br> ```이것은 코드 블럭입니다.```

## 강조 Emphasis
* > 기울여 쓰기 `(*)`또는 `(_)`로 감싼 텍스트 <br> (*) 굵게 쓰기 `(**)` 또는 `(__)`로 감싼 텍스트

## 수평선 Horizontal Rules
* > `-` 또는 `*` 또는 `_` 을 3개 이상 작성 <br> 단, `-`을 사용할 경우 header로 인식할 수 있으니 이 전 라인은 비워두어야 한다.

## 링크 Links
* > [링크] (http://example.com "링크 제목")
* > [Naver] (http://naver.com "네이버")

## 리스트 Lists
* > `No.1 숫자 다음 .을 찍는다. <br> (적힌 숫자랑 상관없이 순서대로 번호가 매겨진다.)
* > `*`,`+`,`-`으로 시작
  
- 순서가 필요하지 않은 목록에 사용 가능한 기호
  - 대쉬
  * 별표
  + 더하기
  
## 이미지 Images
* > 링크과 비슷하지만 `!`가 붙는다.
* > ![alt text](/test.png)



