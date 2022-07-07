# 오늘 공부한 내용들!
-오늘 공부한 내용을 남깁니다.

00. 초기설정

git config --global user.name "유저명"

git config --global user.email "깃허브 메일"


설정 확인
git config --global --list

01. 폴더를 저장소로 만들기 (최초 1회)
git init

파일 만들기
touch README.md
파일 수정 
ctrl + s

02. 무대위로 올린다. (staging area)
git add README.md

03. 파일의 상태를 파악한다.
git status

04. 변경사항을 기록해! (commits)
git commit -m "커밋 메시지"

05. 변경사항의 내역을 보고 싶어!
git log --oneline

------------------------
GITHUB
<로컬에서!>

홈 폴더 하단 TIL 폴더 만들기

마우스 우클릭 > CODE로 열기

ctrl + ` (터미널 열기)


경로확인!!!
~/TIL

touch day01.md

touch README.md

01. 일반 폴더를 repository로 바꾸기
git init

02. 무대위로 올리기 
git add .

03. 사진 찍기
git commit -m "메시지"

04. 파일 상태 확인
git status

05. 변경사항 내역 확인
git log --oneline

------------------------------
<github에서!>
01. new repository 만들기
02. url 복사

------------------------------
<연결하기>
git remote add origin https://github.com/educhelsea/TIL.git

연결 확인
git remote -v

오타난 경우,
git remote rm origin

-------------------------------
<github에 변경사항 백업하기>
git push origin master




