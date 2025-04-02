- GIT은 내 컴퓨터에서 버전 관리를 하는 프로그램
- GITHUB는 GIT을 온라인으로 공유할 수 있는 플랫폼

<개인 리포지토리>

**원격 저장소 연결**

- git init : git이 해당 폴더를 저장소로 변환
- git remote add origin 레포지토리 주소 : 원격 저장소 연결
- git remote -v : 원격 저장소 연결 확인
- git branch -M main : 기본 브랜치 이름 master-> main

**연결한 레포지토리 불러오기**

- git pull origin main : 연결한 레포지토리의 main 브랜치의 최신 사항을 불러오기
- 

**README.md에자기소개를 해보세요**

**수정 사항 github에 올리기**

- git add . : 현재 디렉토리( . ) 아래의 모든 변경 파일을 Git이 추적
- git commit -m “커밋 메시지" : 추적한 파일들을 실제 Git 이력에 기록
- git push origin main : 컴퓨터의 커밋 내용을 원격 저장소 (origin의 main 브랜치) 에 올리기