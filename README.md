# 멍멍Paw 

<div align="center">

<img width="202" height="80" alt="로고" src="https://github.com/user-attachments/assets/4e2ec72e-dc59-416b-ab2f-994d5885d224" />

**한 마리의 유기견도 잊히지 않도록**  
DID를 통해 유기견의 존재를 기록하고 입양과 후원을 연결하는 웹 플랫폼

</div>
<br>

---

## 목차

- [팀 소개](#-팀-소개)
- [프로젝트 소개](#프로젝트-소개)
- [주요 기능](#주요-기능)
- [홈 화면](#홈-화면)
- [기술 스택](#기술-스택)
- [시스템 아키텍처](#시스템-아키텍처)
- [데이터베이스 설계](#데이터베이스-설계)
<br>

---

## 👥 팀 소개

### 팀명: 더워멍냥

| 이름 | 역할 | 소속 | 이메일 | GitHub |
|------|------|------|--------|--------|
| 모진영 | 팀장, 풀스택 개발 | 상명대학교 | ahwlsqja1324@gmail.com | [@ahwlsqja](https://github.com/ahwlsqja) |
| 신윤진 | 백엔드 개발 | 상명대학교 | yj001shin@naver.com | [@nomad1jin](https://github.com/nomad1jin) |
| 박수현 | 프론트엔드 개발 | 상명대학교 | tngus092112@gmail.com | [@onion-0](https://github.com/onion-0) |

<br>

---

## 프로젝트 소개

### 배경

반려동물 산업이 성장하는 이면에는 여전히 **매년 10만 마리 이상의 유기견**이 발생하고, 그중 약 **2만여 마리(18.5%)가 안락사** 되는 현실이 있습니다.

### 문제점

- **신원 미등록**: 유기동물은 고유한 식별번호 없이 '기록되지 않은 존재'로 남음
- **높은 입양 진입장벽**: 제한적인 정보와 불편한 입양 절차
- **보호소 재정 부족**: 수용 한계와 관리 비용 문제로 인한 안락사

### 솔루션

멍멍Paw는 **DID(Decentralized Identifier) 기술**과 **블록체인**을 활용하여:

1. **유기견 비문을 통한 고유 신원 부여**
2. **실시간 채팅과 입양 후기로 입양 접근성 향상**
3. **자체 화폐(뼈다귀)를 통한 충전식 후원 시스템**

<br>

---

## 주요 기능

**1. DID 기반 신원 관리**
비문 인식을 통해 유기견의 고유 DID를 생성하고, 블록체인 기반 VC/VP로 신원 정보를 관리

**2. 입양 플랫폼**
실시간 채팅과 스토리 기능을 통해 입양 상담을 지원하고, 블록체인 기반으로 소유권 이전 내역을 관리

**3. 후원 시스템**
토스 페이먼츠와 자체 화폐 '뼈다귀'를 활용한 간편 후원 및 익명 후원 내역 공개 기능을 제공

**4. 입양 후기 & 스토리**
입양 후기와 일상 스토리를 공유하며 입양자 간 소통과 유대감 형성을 지원

<br>

---

## 홈 화면

<img width="4056" height="3240" alt="메인" src="https://github.com/user-attachments/assets/e554aec7-5b26-4fbe-a5c8-7ca578b7d01f" />

<br>

---

## 기술 스택

### Frontend
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)

### Backend
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=for-the-badge&logo=nestjs&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)

### Blockchain & DID
![Hyperledger Besu](https://img.shields.io/badge/Hyperledger_Besu-2F3134?style=for-the-badge&logo=hyperledger&logoColor=white)
![MetaMask](https://img.shields.io/badge/MetaMask-F6851B?style=for-the-badge&logo=metamask&logoColor=white)
![Solidity](https://img.shields.io/badge/Solidity-363636?style=for-the-badge&logo=solidity&logoColor=white)

### Database
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)

### AI/ML
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

### Infrastructure
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![NCP](https://img.shields.io/badge/Naver_Cloud_Platform-03C75A?style=for-the-badge&logo=naver&logoColor=white)

<br>

---

## 시스템 아키텍처

<!-- 아키텍처 이미지를 여기에 추가하세요 -->
<img width="7484" height="4796" alt="최종 아키텍처" src="https://github.com/user-attachments/assets/3b4ad453-ebcc-4b10-acb3-cafa43e4de0e" />

### 아키텍처 특징

- **마이크로서비스 아키텍처**: 각 도메인별 독립적인 서비스 구성
- **gRPC 통신**: 서비스 간 고성능 통신으로 응답 속도 향상
- **프라이빗 블록체인**: 3-node QBFT 합의 알고리즘 기반 Hyperledger Besu
- **CI/CD 자동화**: NCP SourcePipeline 기반 자동 빌드 및 배포

<br>

---

## 데이터베이스 설계

### ERD (Entity Relationship Diagram)
<img width="3960" height="2576" alt="멍멍paw_erd" src="https://github.com/user-attachments/assets/84483569-224d-484d-afba-210428aab474" />

<br>

---

## 시연 영상

### 1️회원가입 및 로그인
[![회원가입 및 로그인](https://img.youtube.com/vi/1mu14A6NgTQ/maxresdefault.jpg)](https://youtu.be/1mu14A6NgTQ)

### 2️둘러보기 및 후원
[![둘러보기 및 후원](https://img.youtube.com/vi/VXeHKIPrqlA/maxresdefault.jpg)](https://youtu.be/VXeHKIPrqlA)

### 3️반려동물 등록 및 채팅, 입양
[![반려동물 등록 및 입양](https://img.youtube.com/vi/_ttPlAIccy0/maxresdefault.jpg)](https://youtu.be/_ttPlAIccy0)

<br>

---

## 추가 문서

- [API 문서](./docs/API.md)
- [스마트 컨트랙트](./docs/CONTRACTS.md)
- [배포 가이드](./docs/DEPLOYMENT.md)
- [개발 환경 설정](./docs/SETUP.md)

---

## 공모전 

- **제9회 K-PaaS 활용 공모전** - 서비스 개발 부문 출품 (2025.10.31)

---

<!--## 라이선스

이 프로젝트는 MIT 라이선스 하에 배포됩니다. 자세한 내용은 [LICENSE](LICENSE) 파일을 참조하세요.

-->


<div align="center">

**Made with by Team 더워멍냥**
</div>
