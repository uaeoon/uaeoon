## 🍀🥨🎐🤍

### 🛠 Tech Stack

#### Backend
![Java](https://img.shields.io/badge/Java%2021-007396?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Spring Data JPA](https://img.shields.io/badge/Spring%20Data%20JPA-6DB33F?style=flat-square&logo=spring&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring%20Security-6DB33F?style=flat-square&logo=springsecurity&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)

#### DevOps & Tools
![Gradle](https://img.shields.io/badge/Gradle-02303A?style=flat-square&logo=gradle&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![AWS EC2](https://img.shields.io/badge/AWS%20EC2-FF9900?style=flat-square&logo=amazonec2&logoColor=white)

---

### 🖥️ Projects

### 🌍 [CoTempo — 글로벌 팀을 위한 AI 일정 조율 서비스](https://github.com/likelion-hackathon-cotempo/backend)

> 서로 다른 국가와 시간대에서 활동하는 팀원들의 일정을 통합하고, 모두가 참여하기 좋은 회의 시간과 프로젝트 마일스톤을 AI로 추천하는 협업 서비스입니다.

- 회원가입·로그인·로그아웃 및 회원 정보 조회·수정 API 구현
- Spring Security와 JWT 기반 인증·인가 구현
- 개인 일정 등록·수정·삭제 API 구현
- 개인 일정과 참여 중인 팀 일정을 제공하는 메인 화면 조회 API 구현
- 팀원의 개인 일정·팀 일정·마일스톤을 통합한 월별 캘린더 조회 API 구현
- 시간대와 일정 충돌도를 고려한 회의 후보 계산 및 AI 회의 시간 추천 기능 구현
- AI 마일스톤 추천 및 추천 결과 일괄 등록 기능 구현

### 💰 [Peerfolio — Peer Group 기반 AI 금융 분석 서비스](https://github.com/please-2000won/Backend)

> 경제적 여건이 유사한 사용자 그룹과의 비교를 통해 자신의 자산 구성과 투자 위험 요인을 객관적으로 점검할 수 있도록 돕는 금융 분석 서비스입니다.

- 사용자의 금융 정보를 기반으로 유사한 사용자를 탐색하는 Peer Matching 로직 구현
- Peer Group의 금융 자산 분포와 평균을 산출하는 Benchmark 계산 로직 구현
- 자산 집중도·부채·고정지출 등을 반영한 투자 위험 점수 및 위험 단계 계산
- Peer Matching부터 위험 점수 계산과 OpenAI 분석까지 연결되는 통합 분석 API 구현
- 불필요한 재분석을 방지하기 위한 최신 분석 결과 저장 및 조회 기능 구현
- 매칭된 Peer 중 임의의 사용자 3명을 제공하는 Peer 카드 조회 API 구현
- 선택한 Peer와 사용자의 금융 정보를 비교하는 1:1 상세 비교 API 구현
- Docker 및 Docker Compose 기반 애플리케이션 실행 환경 구성
- GitHub Actions를 활용한 Docker 빌드 검증 및 CI/CD 파이프라인 구축
- AWS EC2 서버 배포 및 `develop` 브랜치 기반 자동 배포 환경 구성
