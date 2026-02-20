# 🎮 YJJH Team's C# & Unity Study Space

> **"기초부터 실전까지, 함께 성장하는 게임 개발자의 기록"**  
> 본 프로젝트는 C#, 자료구조, 알고리즘, 그리고 유니티 엔진에 대한 학습 내용을 체계적으로 정리하고 공유하기 위한 팀 프로젝트 공간입니다.

---

## 🛠️ Tech Stack & Tools

| Category | Technology |
| :--- | :--- |
| **Documentation** | [MkDocs](https://www.mkdocs.org/) (Static Site Generator) |
| **Theme** | [MkDocs Material](https://squidfunk.github.io/mkdocs-material/) |
| **Deployment** | [Firebase Hosting](https://firebase.google.com/docs/hosting) |
| **Language** | C#, Markdown |
| **Version Control** | Git & GitHub |

---

## 🏗️ 프로젝트 아키텍처 (Frontend & Docs)

본 프로젝트는 단순한 문서 나열이 아닌, **지속 가능한 지식 공유 플랫폼**을 지향합니다.

### 1. MkDocs를 활용한 정적 사이트 구축
- **Material Theme**: 가독성 높은 UI와 다크/라이트 모드 지원
- **Navigation Tabs**: 학습 파트별(Part 1, 2, 3) 체계적인 로드맵 UI 제공
- **Markdown Extensions**: 코드 하이라이트, 접이식 섹션(`details`), 수식 지원 등을 통해 기술 문서의 퀄리티를 높였습니다.

### 2. Firebase Hosting 연동
- **정적 호스팅**: MkDocs로 빌드된 HTML 파일들을 Firebase를 통해 안정적으로 서비스합니다.
- **배포 프로세스**: `mkdocs build`를 통해 생성된 결과물을 전용 배포 폴더(`public/`)로 연동하여 관리합니다.

---

## 👥 협업 및 문서 관리 (Workflow)

저희 팀은 Git을 기반으로 한 협업 전략을 따릅니다.

### 🚩 Commit Convention
- `Docs`: 학습 문서 내용 추가 및 수정
- `Feat`: 새로운 기능(테마 설정, 내비게이션 등) 추가

### 🔄 작업 흐름
1. 로컬에서 마크다운(`docs/*.md`) 문서 작성
2. `mkdocs serve` 명령어로 실시간 미리보기 확인
3. `mkdocs build`를 통해 정적 파일 생성
4. `firebase deploy`로 웹페이지 최종 반영

---

## 🚀 시작하기 (Local Setup)

프로젝트를 로컬 환경에서 실행하고 문서를 수정하려면 아래 단계가 필요합니다.

### 사전 설치 요구사항
- Python 3.x
- Node.js (Firebase CLI 사용 시)

### 설치 및 실행
```bash
# 1. 필요 라이브러리 설치
pip install mkdocs-material

# 2. 로컬 서버 실행 (실시간 확인)
mkdocs serve

# 3. 빌드 및 배포
mkdocs build
firebase deploy
```

---

## 🗺️ 학습 로드맵
- **Part 1. C# 기초**: 데이터 타입, 제어문, OOP, Generic 등
- **Part 2. 유니티 실무**: 컴포넌트 시스템, 애니메이션, UI, RPG 제작 등

---
**Team YJJH** | *Keep Learning, Keep Coding.*
