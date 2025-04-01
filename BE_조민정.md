# Git & GitHub 세션 요약

## ✅ Git이란?
- 오픈소스 **분산 버전 관리 시스템 (VCS)**
- 개발자가 **전체 히스토리를 로컬에 저장**하고, 인터넷 없이도 작업 가능
- 버전 관리를 통해 **변경 이력 추적, 되돌리기, 협업**이 쉬워짐

## ✅ GitHub이란?
- Git 저장소를 **온라인에서 공유/관리**할 수 있는 플랫폼
- Git은 로컬, GitHub는 온라인 → **협업을 위해 둘 다 필요함**

## ✅ Git vs GitHub
- **Git**: 로컬에서 버전 관리  
- **GitHub**: Git 저장소를 클라우드에서 관리  
→ 함께 사용해야 협업 가능!

---

## ✅ Git 기본 명령어
- `git init` : Git 저장소 생성
- `git add .` : 변경된 파일을 Staging Area로 추가
- `git commit -m "메시지"` : 변경 사항을 커밋
- `git push origin 브랜치명` : 변경 사항을 GitHub에 업로드
- `git pull origin 브랜치명` : 최신 내용 받아오기
- `git branch` : 브랜치 목록 확인
- `git checkout -b 브랜치명` : 새 브랜치 생성 및 이동
- `git remote add origin 주소` : 원격 저장소 연결

---

## ✅ 협업 흐름
1. 중앙 레포지토리를 **Fork** → 개인 레포지토리 생성
2. 로컬에서 **브랜치 생성**
3. `.md` 파일 작성 및 커밋
4. **Push** 후 **PR(Pull Request)** 생성
5. 중앙 레포에서 **Merge**

---

## ✅ 기타 개념
- **README.md**: 프로젝트 설명 파일
- **.gitignore**: Git 추적 제외 파일 목록
- **브랜치**: 작업 단위를 나누는 독립적인 공간
- **pull 전 push 필수**: 충돌 방지를 위해 항상 최신화 먼저!

---


