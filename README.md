# A Ludologist(게임학자)
- **클린 코딩을 지향하는 유니티 클라이언트 프로그래머 입니다.**
---
## 포트폴리오 요약

### 1. Project.Arcana [[GithubLink]](https://github.com/moonshine1004/Project.Arcana)
#### 본 프로젝트는 2D 던전게임과 실시간 카드 게임을 합친다는 컨셉을 바탕으로, 플레이어가 덱을 구성하여 실시간 전투를 통해 몰입할 수 있도록 제작되었습니다.
#### 프로젝트 요약
- 플랫폼: Windows
- 엔진: Unity 6 (6000.2.12.f1)(URP)
- 개발 기간: 2025.05 ~ 진행 중
- 개발 인원: 개인 프로젝트
- 버전 관리: Git, GitHub
- 데이터 관리: Excel -> CSV -> Unity ScriptableObject, Unity Gaming Service Cloud Save(Unity Gaming Service)
- 아키텍쳐 패턴: MVP
#### 주요 구현 내용
- 데이터 테이블 파싱: 기획자가 제작한 데이터 테이블을 CSV 데이터로 변환하여 유니티의 스크립터블 오브젝트로 파싱할 수 있도록 구현
- 데이터 베이스 저장: UGS(Unity Gaming Service)의 Cloud Save를 이용하여 플레이어가 게임 내에서 저장한 카드 덱을 게임 로드 시에 서버로부터 불러오도록 구현
- 오브젝트 풀링: 몬스터 오브젝트와 UI의 카드 오브젝트를 오브젝트 풀링으로 구현하여 메모리 공간 및 성능 저하를 방지
- FSM: 몬스터의 인공지능을 FSM으로 구현

---

### 2. StairCase [[GithubLink]](https://github.com/moonshine1004/26.01_SBS_TeamProject)
#### 본 프로젝트는 SBS 게임 아카데미 학원의 2026년 겨울 방학 팀 프로젝트로 제작된 '무한의 게임' 모작 게임으로, 불타는 빌딩에서 제한 시간 안에 아래층으로 탈출하는 하이퍼 캐주얼 타임어택 아케이드 게임입니다. 
프로젝트 요약
- 플랫폼: Android
- 엔진: Unity 6 (6000.2.12.f1)(URP)
- 개발 기간: 2026.01 ~ 진행 중
- 개발 인원: 4인
- 아키텍쳐 패턴: MVP
- 주요 구현 내용: 이벤트 버스 기반 플레이어 입력 처리, 오브젝트 풀링

---

