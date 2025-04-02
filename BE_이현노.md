프로젝트 초기 세팅
1.Gihub 개인 레포지토리 생성
2.로컬 폴더 생성 후, 사용자 등록
3.생성한 개인 레포지토리 연결

변경사항 업데이트시
파일 수정 후에는 꼭 저장
git add . : 현재 디렉토리( . ) 아래의 모든 변경 파일을 Git이 추적
git commit -m “커밋 메시지" : 추적한 파일들을 실제 Git 이력에 기록
git push origin main : 컴퓨터의 커밋 내용을 원격 저장소 (origin의 main 브랜치) 에 올림

브랜치 관련 명령어 모음
git branch : branch 목록 확인
git branch 새 브랜치 이름 : 새 브랜치 생성
git switch 브랜치 이름 : 브랜치 이동
git branch -d 브랜치 이름 : 해당 브랜치 삭제
main 최신화 후에는 사용한 브랜치를 삭제하기