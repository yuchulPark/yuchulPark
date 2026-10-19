<div align="center">
  <h1>박유철 | Java / Spring Backend Developer</h1>
  <p><strong>요구사항 분석부터 REST API 구현, 데이터 처리, 배포 및 운영 검증까지 수행하는 백엔드 개발자</strong></p>
  <p>공공기관·기업의 업무 시스템을 개발하고 운영해 왔으며,<br>
  최근에는 개인 프로젝트를 통해 <strong>Docker·Jenkins CI/CD와 LLM/RAG 기반 AI 서비스</strong>로 기술 범위를 넓히고 있습니다.</p>
  <p>
    <a href="https://github.com/yuchulPark"><img alt="GitHub" src="https://img.shields.io/badge/GitHub-yuchulPark-181717?style=flat-square&amp;logo=github&amp;logoColor=white"></a>
    <a href="https://github.com/yuchulPark/perfume"><img alt="Featured Project" src="https://img.shields.io/badge/Featured%20Project-Scent%20Archive-617A6C?style=flat-square"></a>
    <a href="https://github.com/yuchulPark?tab=repositories"><img alt="Focus" src="https://img.shields.io/badge/Focus-Backend%20%26%20DevOps-346FA0?style=flat-square"></a>
  </p>
</div>

👋 Professional Summary
안녕하세요. Java/Spring 기반 백엔드 개발자 박유철입니다.

2020년부터 공공기관 및 기업의 웹서비스에서 API 개발, 데이터베이스 처리, 배치 작업, 외부 시스템 연계와 운영 업무를 수행했습니다. 새로운 기능을 구현하기 전에 기존 서비스의 구조와 데이터 흐름을 파악하고, 구현 → API 검증 → 배포 → 정상 동작 확인까지 책임지는 개발을 지향합니다.
- Backend: Java/Spring, 전자정부프레임워크, Spring Boot 기반 웹 애플리케이션·REST API 개발
- Database: Oracle, CUBRID, MariaDB, PostgreSQL 활용 및 SQL 작성·개선
- Operation: Linux, Tomcat, JBoss, Nginx, Jenkins, Docker 기반 빌드·배포·운영 경험
- Collaboration: Git/SVN 형상관리, Postman 테스트, 팀원·고객 요구사항 협의
- Continuous Learning: 개인 프로젝트에서 React, pgvector, Ollama, LLM/RAG 및 배포 자동화 실습
AI 활용 원칙: ChatGPT/Codex를 구현·리팩터링에 활용하되, 생성한 코드를 직접 검토하고 테스트한 뒤 적용합니다.

🎯 Core Competencies
1. 비즈니스 요구사항을 API와 데이터 흐름으로 구현
- 바코드 스캔 기반 도서 입고·출고·배송·반품 REST API 개발 및 개선
- 신청·예약·관리자 기능, 이메일 인증, 알림톡·앱푸시 연계 기능 개발
- 회원 재동의·장기 미접속 정책을 반영한 휴면회원 전환·개인정보 파기 배치 구현
- 기존 API·테이블·서비스 구조를 분석해 신규 요구사항을 안정적으로 반영
2. 개발부터 배포·운영 검증까지 연결
- Kakao Cloud 인스턴스 생성 및 Linux 개발서버 환경 구축
- Tomcat·Nginx 기반 서비스 배포, WAS 이중화 환경의 순차 배포 및 확인
- Jenkins 기반 빌드·배포, Docker 이미지 빌드 및 Docker Compose 컨테이너 재기동 경험
- Git Branch/Merge/Cherry-pick/Stash와 Postman을 활용한 변경·API 검증
3. 새로운 기술을 실제 서비스 구조에 적용
- 개인 프로젝트에서 Spring Boot·React·PostgreSQL 기반 서비스 구성
- pgvector + 임베딩 모델을 활용한 향수 의미 검색 구현
- Ollama LLM을 연동한 검색 근거 기반 RAG 추천 기능 개발
- 개인 Ubuntu 개발서버에 Docker Compose와 Jenkins 파이프라인 구성
🛠️ Technical Expertise
분야	기술 및 도구
Backend	Java 8/11/17, Spring MVC, Spring Boot, eGovFrame, REST API, JSP
Persistence / DB	MyBatis, JPA, Oracle, CUBRID, MariaDB, PostgreSQL, SQL
Frontend / Web	JavaScript, HTML, CSS, React, Vite
Server / Infra	Linux(CentOS·Ubuntu), Kakao Cloud, Tomcat 9, JBoss, Nginx, Docker, Docker Compose
CI/CD / Collaboration	Jenkins, Git, GitHub, GitLab, Gitea, SVN, Postman
AI — 개인 프로젝트	ScentRev MCP, Ollama, Qwen3, Embedding, pgvector, Vector Search, RAG


업무 프로젝트와 개인 프로젝트에서 사용한 기술을 함께 정리했습니다. AI·pgvector·최신 React 관련 경험은 아래 개인 프로젝트를 통해 확장하고 있습니다.
🌿 Featured Personal Project
향의 기록 (Scent Archive) — AI 기반 향수 정보·추천 플랫폼
2026.10 ~ 진행 중 · 개인 프로젝트
GitHub Repository →

Java 17 Spring Boot 3.5 Spring Data JPA PostgreSQL 17 pgvector React Vite Ollama Docker Compose Jenkins

향수 정보를 수집·검색·조회하고, 사용자가 원하는 향의 특성을 자연어로 입력하면 벡터 검색과 저장된 근거를 바탕으로 향수를 추천하는 웹서비스입니다.

주요 구현 내용
- 향수 데이터 수집: ScentRev MCP 연동, 브랜드 단위 Import, 페이지네이션, 데이터 검증 및 타 브랜드 데이터 제외 처리
- 카탈로그 API: 브랜드 목록, 향수 검색·페이징, 향수 상세정보 REST API 개발
- React UI: 향수 목록·브랜드 필터·상세 페이지, 노트 피라미드·평가·유사 향수 표시
- 임베딩 / 검색: Qwen3 임베딩 모델과 PostgreSQL pgvector를 활용한 의미 검색
- RAG 추천: 검색된 향수의 저장된 근거를 확인하고, Ollama 기반 LLM 결과를 검증해 추천 답변 구성
- 추천 작업 관리: 비동기 추천 Job의 상태 조회·취소 및 요청 중복·동시성 처리 기능 개발
- 데이터 갱신: 신규·변경 데이터를 대상으로 한 증분 임베딩 배치 구현 및 수동 검증
- 배포 자동화: Ubuntu 개발서버, Docker Compose, Jenkins 파이프라인을 활용한 서비스 빌드·배포 구성
시스템 흐름
ScentRev MCP ──> Spring Boot Import / REST API ──> PostgreSQL
                                                     └─ pgvector
React / Vite ──> Spring Boot API ──> 의미 검색 ──> Ollama / LLM
                                      └────────> 근거 검증·추천 응답

GitHub ──> Jenkins ──> Docker Compose ──> Ubuntu 개발서버
이 프로젝트에서 집중한 부분
- 외부 데이터나 LLM 출력값을 그대로 신뢰하지 않고, 입력값·검색 근거·응답을 단계적으로 검증하는 구조
- 검색/추천 API의 타임아웃, 중복 요청, 비동기 작업 상태·취소 등 예외 상황 처리
- 애플리케이션·프론트엔드·DB 서비스를 분리한 배포 구성과 운영 절차 문서화
현재도 기능을 개선하고 검증 중이며, AI 추천은 저장된 데이터 중 임베딩된 범위를 기반으로 동작합니다. 모든 향수에 대한 완전한 추천이나 운영서비스 수준의 성능을 주장하지 않습니다.

📚 RAG 추천 설계 · 추천 Job/취소 처리 · Docker Compose 배포
💼 Professional Projects
1. 서점ON 공동수배송 PDA 연계시스템 · 스마트앱
2025.06 ~ 2025.07 / 2025.12 ~ 2026.05 (약 8개월)
㈜스마트코어 / 한국서점조합연합회 · 백엔드 API·관리자 웹 개발, 서버 구축·배포

Java 8 eGovFrame 4.2 JSP Oracle CentOS Tomcat 9 Nginx Jenkins Kakao Cloud Git
- 바코드 스캔 기반 입고·출고·배송·반품 처리 API 기능 개발 및 유지보수
- 바코드가 없는 매입처를 위한 수량 직접 입력 처리 기능·API 개발
- 배송·반품, 도서, 서점, 배송기사 등의 관리자 페이지 개발
- 스마트앱의 메인·도서·주문·회원 마이페이지 REST API 개발 및 유지보수
- 알림톡·이메일·앱푸시 발송 이력 관리, Batch Scheduler 연계 이메일 발송 기능 개발
- Kakao Cloud 개발서버 구축, Nginx 정적 이미지 제공, WAS1/WAS2 순차 배포·검증
2. HDC 단지서버 3.0 유지관리
2025.08 ~ 2025.11 (약 4개월)
㈜스마트코어 / HDC랩스 · 백엔드 API 유지보수 및 빌드·배포

Java 11 Spring Boot 2.7 MariaDB RedisTemplate Jenkins Docker Docker Compose GitLab
- 월패드·로비폰·경비실기 등 단지 장치의 상태·수량 조회 API 유지보수
- 카드 발급·관리 및 카드와 동·호수 매핑 관련 API 개선
- Jenkins 이미지 빌드 및 Docker Compose를 통한 컨테이너 업데이트·재기동 검증
3. 인천광역시 통합 웹사이트 개발 및 유지보수
2021.04 ~ 2022.12 / 2023.04 ~ 2024.12 (약 3년 6개월)
㈜이즈파크 · ㈜윤커뮤니케이션즈 / 인천광역시 · 웹 개발·배치·시스템 연계

Java Spring eGovFrame JSP JavaScript CUBRID JBoss Jenkins
- 각종 신청서·평가지·관리자 페이지 및 특별지원금 신청 기능 개발
- 외부 Open API 연계, 이메일 인증·알림, 이수증 출력 기능 구현
- 휴면회원 데이터 분리, 대상 판별·사전 알림·자동 전환·개인정보 파기 Batch 개발
- 장기 운영 서비스의 기능 개선과 Jenkins/JBoss 기반 빌드·배포 대응
4. 국토교통부 공간정보 데이터 통합·품질관리 시스템
2020.07 ~ 2021.03 (약 9개월)
㈜신한항업 / 국토교통부 · 공간정보 데이터 품질관리 웹 개발

Java Spring eGovFrame React JavaScript PostgreSQL
- 공간정보 품질지표·품질진단 정보·중요정보 항목·업무규칙 관리 기능 개발
- 관리자 화면에서 각 데이터의 등록·조회·수정·삭제 기능 구현
- 국가·공공기관의 공간정보 통합 및 품질관리 시스템 구축 참여
🧑‍💻 Professional Experience
기간	회사	업무
2025.05 ~ 2026.05	㈜스마트코어	백엔드/서버 개발, 개발서버 구축·배포
2023.04 ~ 2025.01	㈜윤커뮤니케이션즈	인천광역시 통합 웹서비스 개발·유지보수
2021.04 ~ 2023.03	㈜이즈파크	공공 웹서비스 및 예약 시스템 개발
2020.07 ~ 2021.03	㈜신한항업	공공 공간정보 데이터 품질관리 시스템 개발


위 표는 개발 직무 경력을 중심으로 정리했습니다.
🎓 Education & Certifications
- 수원대학교 통계정보학과 졸업 (2018.02)
- SQL개발자(SQLD) (2025.04)
- 정보처리기사 (2021.06)
- 비트캠프 풀스택 Java 웹개발자 과정 수료 (2019.12 ~ 2020.06)
💡 How I Work
- 먼저 이해합니다. 기존 코드·DB 구조와 기능 간 영향을 살펴본 뒤 수정합니다.
- 직접 검증합니다. API 응답, 예외 케이스, 배포 후 서비스 상태까지 확인합니다.
- 운영을 고려합니다. 데이터 일관성·보안·유지보수성을 함께 생각합니다.
- 도구보다 결과를 중시합니다. AI 도구를 사용해도 검토·테스트·최종 책임은 개발자가 가져야 한다고 생각합니다.
<div align="center">
  <p><strong>지속적으로 학습하며 안정적이고 유지보수하기 좋은 백엔드를 만드는 개발자가 되겠습니다.</strong></p>
  <p><a href="https://github.com/yuchulPark?tab=repositories">GitHub Repositories</a> · <a href="https://github.com/yuchulPark/perfume">Scent Archive</a></p>
</div>
