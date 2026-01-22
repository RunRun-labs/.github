

# 🏃‍♂️ 실시간 매칭 러닝 플랫폼 RUNRUN
  
<img width="100%" alt="readme" src="https://github.com/user-attachments/assets/77bca501-4fed-4409-8051-d6cbc78ea38f" />

**"러닝의 순간이 연결의 시작이 되도록"** 단순한 기록 측정을 넘어, 실시간 경쟁과 크루 활동으로 함께 달리는 즐거움을 선사합니다.

---

## 📌 프로젝트 개요
**RunRun**은 GPS 추적 기술과 실시간 통신을 결합한 **러닝 기반 소셜 플랫폼**입니다. 혼자 달리는 지루함을 해소하기 위해 실시간 매칭 배틀, 과거 기록과 경쟁하는 고스트 러닝, 크루 시스템 등을 제공하여 지속적인 동기부여를 제공합니다.

* **📅 개발 기간:** 2025.12 ~ 2026.01
* **👥 개발 인원:** 5명 (Team RunRun)
* **🎓 프로젝트:** 멀티캠퍼스 파이널 프로젝트
* **🏗 아키텍처:** RESTful API + WebSocket 실시간 통신
* **🚀 배포 환경:** Docker, Kubernetes (EKS), Jenkins CI/CD

---

## ✨ 핵심 가치 (Value Proposition)
* **소셜 러닝:** 크루, 친구, 피드 시스템을 통한 러너 간의 강력한 유대감 형성
* **실시간 경쟁:** 온라인 배틀 및 고스트 러닝으로 러닝의 게임화(Gamification) 실현
* **동기부여:** 챌린지, 포인트, 등급 시스템을 통한 지속적인 참여 유도
* **사용자 편의:** TMap API 연동 코스 추천 및 TTS 음성 안내로 전문적인 러닝 환경 제공
* **비즈니스 확장성:** 프리미엄 멤버십, 광고 슬롯, 쿠폰 시스템을 포함한 수익 모델 설계

---

## 🧩 주요 기능

### 1. 러닝 모드 (Running Modes)
* **솔로 러닝:** 개인 기록 측정 및 상세 통계 제공
* **온라인 배틀:** 실시간 매칭을 통한 사용자 간 경쟁 (WebSocket 기반)
* **고스트 러닝:** 본인의 과거 기록 데이터를 불러와 가상의 '고스트'와 실시간 경쟁
* **오프라인 러닝:** 주변 크루원/친구와 함께 달리기 세션 생성 및 참여

### 2. 크루 & 소셜 (Social & Crew)
* **크루 시스템:** 리더/부리더 등 역할 분담 및 프리미엄 멤버십 기반 크루 개설
* **실시간 채팅:** MongoDB를 활용한 저지연 크루 채팅 서비스
* **피드:** 러닝 인증샷 공유, 좋아요 및 댓글 소통

### 3. 코스 및 공간 데이터 (Geospatial)
* **코스 관리:** TMap API 연동을 통한 자동/수동 코스 생성 및 Mapbox 썸네일 제공
* **완주 판정:** PostGIS를 활용한 경로 진행도 및 거리 기반의 정밀한 완주 검증

### 4. 커머스 & 관리 (Commerce & Admin)
* **결제:** Toss Payments 연동 정기 결제 및 멤버십 관리
* **포인트/쿠폰:** 활동 기반 포인트 적립 및 상점 이용, 만료일 자동 관리 (Scheduler)
* **어드민:** 대시보드 통계, 광고 슬롯 관리, 쿠폰 및 포인트 상품 총괄

---

## 🏗 시스템 아키텍처

<img width="1664" height="824" alt="시스템아키텍처" src="https://github.com/user-attachments/assets/47fcd9a3-a892-4014-a91d-acf8fbbf6dce" />


## 🛠 Tech Stack

### Language & Framework
![Java](https://img.shields.io/badge/Java%2017-007396?style=for-the-badge&logo=java&logoColor=white)
![SpringBoot](https://img.shields.io/badge/Spring%20Boot%204.0.0-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![SpringSecurity](https://img.shields.io/badge/Spring%20Security-6DB33F?style=for-the-badge&logo=springsecurity&logoColor=white)

### Database
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![PostGIS](https://img.shields.io/badge/PostGIS-336699?style=for-the-badge&logo=postgis&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)

### Infrastructure & DevOps
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![AWS EKS](https://img.shields.io/badge/AWS%20EKS-FF9900?style=for-the-badge&logo=amazon-eks&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white)
![AWS S3](https://img.shields.io/badge/AWS%20S3-569A31?style=for-the-badge&logo=amazons3&logoColor=white)

### Monitoring & Real-time
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)
![WebSocket](https://img.shields.io/badge/WebSocket-010101?style=for-the-badge&logo=socket.io&logoColor=white)

---

## 📚 Directory Structure

```text
📦 RunRun-Backend
 ┣ 📂 src/main/java/com/multi/runrunbackend
 ┃ ┣ 📜 RunRunBackendApplication.java
 ┃ ┣ 📂 common                    # 공통 설정 및 모듈
 ┃ ┃ ┣ 📂 config                  # Security, WebSocket, S3 설정 등
 ┃ ┃ ┣ 📂 entitiy                 # 공통 BaseEntity
 ┃ ┃ ┣ 📂 exception               # 전역 예외 핸들러 (GlobalExceptionHandler)
 ┃ ┃ ┣ 📂 jwt                     # JWT 필터 및 Provider
 ┃ ┃ ┗ 📂 event                   # 도메인 간 결합도를 낮추기 위한 이벤트 객체
 ┃ ┣ 📂 domain                    # 비즈니스 도메인 레이어 (DDD)
 ┃ ┃ ┣ 📂 running                 # 러닝 핵심 (솔로, 배틀, 고스트)
 ┃ ┃ ┣ 📂 course                  # 코스 생성 및 PostGIS 기반 경로 관리
 ┃ ┃ ┣ 📂 crew                    # 크루 관리 및 CrewScheduler
 ┃ ┃ ┣ 📂 chat                    # 실시간 채팅 (MongoDB 연동)
 ┃ ┃ ┣ 📂 notification            # SSE + Redis Pub/Sub 알림 시스템
 ┃ ┃ ┣ 📂 payment                 # 결제 처리 및 PaymentScheduler
 ┃ ┃ ┣ 📂 membership              # 멤버십 구독 관리 및 스케줄러
 ┃ ┃ ┣ 📂 point                   # 포인트 적립/차감 및 상점
 ┃ ┃ ┗ 📂 ... (challenge, feed, friend, admin, tts)
 ┃ ┗ 📂 util                      # 공통 유틸리티
 ┣ 📂 src/main/resources
 ┃ ┣ 📂 static/templates          # Thymeleaf 기반 뷰 레이어
 ┃ ┗ 📜 application-prod.yml      # 운영 환경 설정
 ┣ 📂 k8s                         # Kubernetes (EKS) 배포 설정
 ┣ 📜 Dockerfile                  # 컨테이너화 설정
 ┗ 📜 Jenkinsfile                 # CI/CD 파이프라인

```
 ## 🔐 인증 & 보안 설계

효율적이고 안전한 사용자 경험을 위해 다음과 같은 보안 원칙을 준수하여 설계되었습니다.

* **JWT Access/Refresh Token**: Stateless 세션 관리를 통해 서버 확장성을 확보하였으며, **Redis**에 Refresh Token을 저장하여 토큰 탈취 시 즉각적인 무효화가 가능하도록 보안을 강화했습니다.
* **권한 체계 (RBAC)**: Spring Security를 활용하여 역할 기반의 접근 제어를 구현했습니다.
    * `ROLE_USER`: 일반 러닝 및 커뮤니티 기능 이용
    * `ROLE_PREMIUM`: 크루 개설 및 유료 멤버십 전용 혜택 제공
    * `ROLE_ADMIN`: 시스템 설정, 광고 및 사용자 통계 관리
* **API 보안**: 모든 비즈니스 로직이 포함된 `/api/**` 경로에 대해 인증을 필수로 적용하고, 사용자 비밀번호는 `BCrypt` 해시 알고리즘을 통해 암호화하여 저장합니다.
* **파일 보안**: AWS S3 업로드 시 백엔드 단에서 파일 크기 제한 및 확장자 화이트리스트 검증 로직을 적용하여 악성 파일 업로드를 방지합니다.





## 🧠 트러블슈팅 하이라이트

프로젝트 진행 중 발생한 기술적 한계를 극복하기 위해 도입한 핵심 해결책들입니다.

### 1. 실시간 매칭 서버 부하 개선
* **문제**: 단일 서버 기반의 SSE(Server-Sent Events) 사용 시 서버 확장 시 알림이 누락되는 한계 발생.
* **해결**: **Redis Pub/Sub** 구조를 도입하여 다중 서버 환경에서도 모든 인스턴스가 실시간 알림을 안정적으로 전송할 수 있도록 분산 아키텍처를 구현했습니다.

### 2. GPS 정밀도 및 완주 판정 로직 고도화
* **문제**: GPS 오차로 인해 단순 직선거리 측정 시 실제 코스 주행 여부를 정확히 판정하기 어려움.
* **해결**: **PostGIS**의 공간 쿼리를 활용하여 코스(LineString)와 사용자 위치(Point) 사이의 이탈 거리를 체크하고, 코스 진행도(Fraction)를 결합한 정밀 판정 알고리즘을 설계했습니다.



### 3. 결제 정합성 및 사용자 경험 최적화
* **문제**: Toss Payments 결제 승인 후 멤버십 처리 과정에서 지연이 발생할 경우 사용자가 대기해야 하는 문제.
* **해결**: 결제 승인 완료 후 멤버십 승격 로직을 **Spring Event**를 활용한 비동기 방식으로 분리하여, 사용자는 즉시 결제 성공 응답을 받고 백그라운드에서 안전하게 권한 처리가 진행되도록 개선했습니다.

### 4. 고스트 러닝 데이터 최적화
* **문제**: 수만 개의 좌표 데이터로 구성된 과거 경로를 매초 DB에서 조회 시 성능 저하 유발.
* **해결**: 실시간 경쟁에 필요한 경로 데이터를 **Redis에 캐싱** 처리하여 DB I/O 부하를 80% 이상 감소시키고 매끄러운 실시간 경쟁 환경을 구축했습니다.


## 🔗 외부 API 연동 (External API Integration)

**RunRun**은 신뢰성 있는 외부 서비스를 결합하여 보다 전문적이고 안정적인 기능을 제공합니다.

### 🗺️ Location & Mapping
* **TMap API**: 고도화된 경로 탐색 알고리즘을 활용하여 사용자에게 최적화된 러닝 경로를 제안하고, 주행 데이터를 바탕으로 **자동 코스 생성** 로직을 처리합니다.
* **Mapbox API**: 사용자 친화적인 지도 인터페이스를 제공하며, 생성된 러닝 코스의 데이터를 시각화하여 고해상도 **코스 썸네일**을 동적으로 생성합니다.

### 💳 Payment & Security
* **Toss Payments API**: 전자결제 표준 가이드를 준수하여 안전하고 간편한 **결제 처리** 시스템을 구축했습니다. 정기 결제 기능을 통해 프리미엄 멤버십 서비스를 안정적으로 운영합니다.

### ☁️ Infrastructure & Storage
* **AWS S3 (Amazon Simple Storage Service)**: 사용자 프로필, 러닝 인증 사진, 시스템 리소스 등 모든 대용량 **파일 데이터**를 안전하고 확장성 있게 저장 및 관리합니다.

---


## 👥 팀 구성 (Team RunRun)

프로젝트를 함께 완성한 **Team RunRun**의 멤버들을 소개합니다.

| 이름 | 역할 | 담당 업무 및 개발 기능 |
| :--- | :--- | :--- |
| **연경수** | **인프라/GitHub 담당** | 인프라 구축 및 관리, 광고·쿠폰 시스템, 코스 관리(TMap), TTS, 관리자 통계 구현 |
| **김창우** | **회의록 담당** | WebSocket 기반 채팅방 구축, 오프라인/온라인 대결 로직, 고스트런 기능 개발 |
| **김용원** | **산출물 담당** | 회원 프로필 및 마이페이지, 소셜 기능(친구 요청/수락/차단), 피드 개발, 챌린지 관리, 환경 설정 |
| **김광호** | **산출물 담당** | 오프라인/온라인 매칭 시스템, 실시간 알림 서비스, 사용자 레이팅 시스템 구축 |
| **홍보경** | **Notion 담당** | 크루 시스템 기획 및 개발, 멤버십 구독 시스템, 포인트 적립 및 상점 시스템 구현 |






