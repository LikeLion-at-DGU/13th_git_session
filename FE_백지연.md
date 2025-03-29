### git
: 오픈 소스 분산 버전 제어 시스템

### git vs github
git은 내 컴퓨터에서 버전 관리를 하는 프로그램
github는 git을 온라인으로 공유할 수 있는 플랫폼

### 과정 요약
working directory(코드 작업) -> staging area(커밋 전 중간 저장소) -> local repository(git) -> remote repository(github)

### github 협업(fork)
git remote add origin 포크한 개인 레포지토리 주소
git remote add upstream 중앙 레포지토리 주소
git remote -v : 원격 저장소 연결 확인
git branch -M main : 기본 브랜치 이름 master -> main
git pull upstream main : 중앙 레포지토리의 main 브랜치의 최신 사항을 불러오기
git branch -b 브랜치명 : 새로운 브랜치 생성 후 switch
-> 변경사항 커밋 후 push -> 다시 main으로 돌아와 pull해 코드 최신화 -> 작업하던 브랜치 삭제(git branch -d 브랜치명)

### 브랜치관련 명령어 모음
git branch : branch 목록 확인
git branch 새 브랜치 이름 : 새 브랜치 생성
git switch 브랜치 이름 : 브랜치 이동
git branch -d 브랜치 이름 : 해당 브랜치 삭제