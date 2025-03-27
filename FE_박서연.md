# 13th_git_session_review
## 1. Git vs. Github
- Git: 내 컴퓨터에서 버전 관리를 하는 프로그램
- Github: Git을 온라인으로 공유할 수 있는 플랫폼
---
## 2. Github 개인 레포지토리
1. Git hub에서 개인 레포지토리 생성 & 레포지토리 주소 복사
2. 폴더 생성 후 VSCode에서 해당 폴더 열기
3. Terminal 열어서 Git bash 클릭
4. git init : Git이 파일 변경 사항 추적하기 시작
5. git remote add origin "레포지토리 주소"": 원격 저장소 연결
6. git remote -v: 원격 저장소 연결 확인
7. git branch -M main: 브랜치 이름 master->main
8. git pull origin main: 레포지토리의 main 브랜치의 최신 사항 불러오기
9. 파일 수정
10. git add . : 현재 디렉토리 아래의 모든 변경 파일을 Git이 추적
11. git commit -m "커밋 메시지": 추적한 파일들을 실제 Git 이력에 기록
12. git push origin main: 커밋 내용을 원격 저장소에 올림
13. 깃허브의 레포지토리에서 확인

---
## 3. Github 협업
1. Github에서 Create a new fork: 중앙 레포지토리를 fork하여 개인 레포지토리 생성
2. 폴더 생성 후 VSCode에서 해당 폴더 열기
3. Terminal 열어서 Git bash 클릭
4. git init : Git이 파일 변경 사항 추적하기 시작
5. git remote add origin "개인 레포지토리 주소"
6. git remote add upstream "중앙 레포지토리 주소"
7. git remote -v: 원격 저장소 연결 확인
8. git branch -M main: 기본 브랜치를 master->main으로 변경
9. git pull upstream main: 중앙 레포지토리의 main 브랜치의 최신 사항을 불러옴
10. git branch 브랜치이름: 새 브랜치 생성
11. git switch 브랜치이름: 해당 브랜치로 이동
12. 파일 내용 수정
13. git add . : 현재 디렉토리 아래의 모든 변경 파일을 Git이 추적
14. git commit -m "커밋 메시지": 추적한 파일들을 실제 Git 이력에 기록
15. git pull upstream main: 충돌 방지하기 위해 push 전에 pull 함(다른 사람이 변경했을 수도 있으므로 최신 변경사항을 가져오는거임)
16. git push origin 현재 브랜치 이름 : 내 변경사항 올리기
16. Github에 들어가서 Compare& pull request 클릭
17. 제목, 설명 추가한 후 Create pull request 클릭
18. git switch main : 사용한 브랜치 삭제 위해 main 브랜치로 이동
19. git pull upstream main: merge해준 내 작업이 진짜로 반영되었는지 확인
20. git branch -d 사용한브랜치명: 작업이 끝난 브랜치는 더이상 쓸일 없음-> 삭제
