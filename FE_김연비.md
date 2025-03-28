# 13th_git_session

git init: 해당 폴더를 저장소로 변환
git remote add origin [개인 레포지토리 주소]: 원격 저장소 연결
git remote add upstrean [중앙 레포지토리 주소]: 중앙 저장소 연결결
git remote -v: 원격 저장소 연결 확인
git branch -M main: master->main 

git pull origin main: 연결한 레포지토리의 main 브랜치 최신사항 불러오기
git pull upstream main: 중앙 레포지토리 main 브랜치 최신사항 불러오기

git add. : 현재 디렉토리 아래의 모든 변경 파일을 Git이 추적
ㅣ [커밋 전 중간 저장]
git commit -m "커밋 메시지" : 추적한 파일들을 실제 Git 이력에 기록
ㅣ [커밋 후 저장되는 로컬 저장소]
git push origin main: 컴퓨터의 커밋 내용을 원격 저장소(origin main 브랜치)에 업로드
   [푸쉬 후 업로드 되는 원격 저장소]

   * push 이전에는 꼭 pull하기 !

브랜치: 작업을 나누어하기 위해 기존 코드(main)에서 갈라져 나온 독립적인 작업 공간