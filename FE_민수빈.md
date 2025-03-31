# Git 세션 요약

- Git이란 오픈소스 분산 버전 관리 시스템이다.
- 프로젝트 초기 세팅 : 깃허브 개인 레포 생성 -> 로컬 폴더 생성 후 사용자 등록 -> 개인 레포 연결
- `git init`으로 해당 폴더를 로컬 저장소로 변환
- 변경 사항 업데이트 시, `git add`, `git commit`, `git push` 순으로 작업
- `git remote add origin 레포 주소` : 원격 저장소 연결 / `git remote -v` : 원격 저장소 연결 확인
- `git branch -M main` : 기본 브랜치 이름을 master -> main으로 변경
- `git pull origin main` : 연결한 레포의 main 브랜치의 최신 사항 불러오기
