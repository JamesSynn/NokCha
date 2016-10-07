# GIt Tutorial

## Git init
directory: workbench 

~~~bash

$ git init # 저장소 초기화  .git 디렉토리 생성(깃파일 생성과 변경이력 보관)


# 사용자 이름 이메일 등록

$ git config --global user.name "Leejeeyong"
$ git config --global user.email "fghj0720@gmail.com"
$ git config --local user.name "Leejeeyong"
$ git config --local user.email "fghj0720@gmail.com"
$ git config -l

# 디렉토리에  파일 추가

$ git status
$ git add content.docx
$ git add . # 변경 사항만
$ git add *.docx # docx의 확장자를 가진 파일들만

.gitignore # 제외하고싶은 파일 설정
ex) contents: ~*.* # 임시파일 제 외

# 추가 되돌리기(option)

$ git reset filename.extension

# 파일 커밋(새로운 단계 규정)

$ git commit -m "your comments for the commit"

# 체크 아웃(이력간의 이동)

$ git log # 저장소 이력
$ git check ___commit_id___

$ git checkout master #최근변경사항으로 되돌림
~~~
