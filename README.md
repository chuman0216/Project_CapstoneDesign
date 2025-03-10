# ☕ 스타벅스 스토어 클론코딩을 통한 리테일 웹서비스 제작하기

## 😎 프로젝트 개요
- 프로젝트명: 스타벅스 스토어 클론코딩
- 수행 형태: 백엔드 및 데브옵스
- 팀원: 추지우

## 🛠 기술 스택
- **Backend**: Java, Spring Boot, Spring MVC, Spring Security, OAuth 2.0, JPA, MyBatis
- **Frontend**: HTML, CSS, JavaScript, Thymeleaf, React (선택사항)
- **Database**: MySQL, Redis (세션 관리)
- **API & Deployment**: AWS (EC2, S3, RDS), Docker, GitHub Actions (CI/CD)
- **Authentication**: OAuth 2.0 (Google, Kakao, Naver 로그인)
- **DevOps**: Docker, Jenkins (또는 GitHub Actions)

---

## 📅 프로젝트 일정 (10주)

### 🗂️ **칸반보드 (Kanban Board)**  
| 주차 | 주요 내용 | 진행 상태 |
|------|-------------------------------|------------|
| 1주차 | 프로젝트 기획 및 요구사항 분석 | 🔄 진행중 |
| 2주차 | 시스템 설계 및 ERD 작성 | ⏳ 예정 |
| 3주차 | Spring Boot 기반 백엔드 개발 (1) | ⏳ 예정 |
| 4주차 | Spring Security 및 OAuth 2.0 적용 | ⏳ 예정 |
| 5주차 | 프론트엔드 개발 (1) - 기본 UI 구현 | ⏳ 예정 |
| 6주차 | 상품 관리 및 장바구니 기능 구현 | ⏳ 예정 |
| 7주차 | 주문 및 결제 시스템 개발 | ⏳ 예정 |
| 8주차 | 관리자 페이지 개발 및 대시보드 구축 | ⏳ 예정 |
| 9주차 | 배포 및 최적화 | ⏳ 예정 |
| 10주차 | 테스트 및 프로젝트 마무리 | ⏳ 예정 |

---

## 📌 주차별 상세 내용

<details>
  <summary>1주차 - 프로젝트 기획 및 요구사항 분석</summary>

  - 프로젝트 목표 및 기능 정의  
  - 스타벅스 공식 웹사이트 분석  
  - 사용자 요구사항 정리 (유스케이스 다이어그램)  
  - 기술 스택 확정 및 개발 환경 설정 (IntelliJ, VSCode, MySQL Workbench 등)  

</details>

<details>
  <summary>2주차 - 시스템 설계 및 ERD 작성</summary>

  - 데이터베이스 ERD 설계 (MySQL)  
  - API 설계 (RESTful API 엔드포인트 정의)  
  - 화면 와이어프레임 제작 (Figma, Adobe XD)  
  - GitHub Repository 생성 및 브랜치 전략 수립 (Git Flow)  

</details>

<details>
  <summary>3주차 - Spring Boot 기반 백엔드 개발 (1)</summary>

  - Spring Boot 프로젝트 세팅 (Gradle 또는 Maven)  
  - JPA 및 MyBatis 설정, DB 연결 테스트  
  - 회원 가입 및 로그인 기능 구현 (JWT 또는 OAuth 2.0)  
  - 예외 처리 및 글로벌 예외 핸들링 적용  

</details>

<details>
  <summary>4주차 - Spring Security 및 OAuth 2.0 적용</summary>

  - Spring Security 설정 및 JWT 인증 적용  
  - OAuth 2.0을 활용한 소셜 로그인 (Google, Kakao, Naver)  
  - 사용자 권한(Role) 및 보안 정책 설정  
  - Redis를 활용한 세션 관리  

</details>

<details>
  <summary>5주차 - 프론트엔드 개발 (1) - 기본 UI 구현</summary>

  - HTML/CSS, JavaScript를 활용한 기본 레이아웃 구현  
  - Thymeleaf 적용 및 템플릿 엔진 설정  
  - 반응형 웹 디자인 적용 (Bootstrap 또는 Tailwind CSS)  
  - 로그인/회원가입 UI 개발  

</details>

<details>
  <summary>6주차 - 상품 관리 및 장바구니 기능 구현</summary>

  - 상품 목록 조회 및 상세 페이지 개발  
  - 장바구니 담기, 삭제 기능 구현  
  - JPA 활용한 상품 데이터 관리  
  - RESTful API 설계 및 데이터 연동  

</details>

<details>
  <summary>7주차 - 주문 및 결제 시스템 개발</summary>

  - 주문 생성 및 결제 API 연동 (카카오페이, 토스페이먼츠 등)  
  - 결제 상태 관리 및 주문 내역 조회 기능 구현  
  - Spring Batch 활용한 주문 데이터 처리 자동화  
  - 이메일 및 SMS 알림 시스템 적용  

</details>

<details>
  <summary>8주차 - 관리자 페이지 개발 및 대시보드 구축</summary>

  - 관리자 페이지 개발 (상품 관리, 주문 관리 기능 포함)  
  - 매출 데이터 시각화 대시보드 구축 (Chart.js, Recharts 활용)  
  - ElasticSearch 적용하여 검색 기능 최적화  
  - 관리자 로그인 및 권한 관리 추가  

</details>

<details>
  <summary>9주차 - 배포 및 최적화</summary>

  - AWS EC2, S3, RDS 환경에서 배포  
  - Docker를 활용한 컨테이너화 및 배포 자동화 (GitHub Actions)  
  - 성능 최적화 (Redis 캐싱, Lazy Loading 적용)  
  - SSL 적용 및 HTTPS 설정  

</details>

<details>
  <summary>10주차 - 테스트 및 프로젝트 마무리</summary>

  - JUnit 및 Mockito를 활용한 단위 테스트 수행  
  - 통합 테스트 및 성능 테스트 진행 (JMeter)  
  - 버그 수정 및 코드 리팩토링  
  - 프로젝트 발표 및 문서화 정리 (API 명세서, ERD 공유)  

</details>

---

## 🚀 기대 효과
- 실무 수준의 리테일 웹서비스 개발 경험  
- OAuth 2.0을 활용한 인증/인가 구현 경험  
- RESTful API 설계 및 배포 자동화 (CI/CD) 경험  
- AWS 기반 인프라 구축 및 성능 최적화 경험  
