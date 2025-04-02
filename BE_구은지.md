# 깃 간단 정리

git: 오픈 소스 분산 버전 제어 시스템, 내 컴퓨터에서 관리
github: git을 온라인으로 공유

git init 처음에 설정
git remote add origin 레포지토리주소 : 원격저장소를 연결해주어야 한다
git remote -v: 원격 저장소 연결 확인을 한다
git pull origin main: 연결한 레포지토리의 main 브랜치의 최신 사항을 불러온다
git add .: 현재 디레고리 아래의 모든 변경 파일을 git이 추적한다
git commit -m "message": 추척한 파일들을 실제 git 이력에 기록한다
git push origin main: 컴퓨터의 커밋 내용을 원격 저장소에 올린다. (우리는 개인 브랜치에 올렸다)