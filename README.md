## 정현수 | 백엔드 엔지니어 희망
- Java & Spring을 사용한 백엔드 개발에 큰 관심이 있습니다.
- Docker & Kubernetes와 같은 컨테이너 오케스트레이션 도구에도 관심이 있습니다.
- 항상 서비스 사용자 입장에서 생각해보고, 어떻게 하면 성능을 더 최적화 시킬 수 있는지에 대해 생각하는 엔지니어가 되고 싶습니다.

### **[희망 이유]**
- 다른 사람들의 삶을 조금이나마 편리하게 하는데 도움이 될 수 있다고 생각합니다.
- 서비스의 핵심을 다룰 수 있다는 것에 가장 큰 매력을 느꼈습니다.
- 최신 기술을 적극적으로 도입하기 위해, 끊임없이 노력해야 한다는 점이 개인적인 성장에도 매우 좋은 영향이 될 수 있다고 생각합니다.
&nbsp;  


## 📧 Contact
**Naver.** jhs99126@naver.com        
**Gmail.** jhs990313@gmail.com   

&nbsp;

## 🛠️ Skills  

<img src="https://img.shields.io/badge/Languate-848484"/>&nbsp;&nbsp;&nbsp;&nbsp; 
<img src="https://img.shields.io/badge/Java-007396?style=flat-square&logo=java&logoColor=white"/>  

<img src="https://img.shields.io/badge/Web-Backend-848484"/>&nbsp;&nbsp;&nbsp;&nbsp; 
<img src="https://img.shields.io/badge/Spring-6DB33F?style=flat-square&logo=spring&logoColor=white"/> &nbsp; <img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white">  

<img src="https://img.shields.io/badge/DataBase-848484"/>&nbsp;&nbsp;&nbsp;&nbsp; 
<img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white"/>

<img src="https://img.shields.io/badge/Cloud-848484"/>&nbsp;&nbsp;&nbsp;&nbsp;
<img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white"/>

<img src="https://img.shields.io/badge/Container Orchestration-848484"/>&nbsp;&nbsp;&nbsp;&nbsp;  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white">&nbsp;&nbsp; 
<img src="https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white">

<br>
  
## 💻 Project

### CJ CloudWave 2기 Team Project [최우수팀 선정]
24.02.06 - 24.02.29 (4주) , 팀원 6명 (AWS Infra 구축 - 3명, Service 개발 및 배포 - 3명) 
<br>
<br>
**[프로젝트 개요 및 주요 사항]**
- 최근 글로벌 시장에서 순항 중인 뚜레주르 이커머스를 멀티 리전에 구축해보는 프로젝트입니다.
- AWS 서비스를 적극적으로 사용하고, Terraform을 이용해 서울 리전과 버지니아 북부 리전에(멀티 리전) 인프라를 구축해보는 것이 주 목표입니다.
- 배포할 예시 서비스로는 NodeJS 기반의 회원 서비스(로그인, 회원 가입), Spring 기반의 주문 서비스입니다.
- MSA 구성을 위해 AWS EKS를 사용했고, ClusterIP의 DNS를 이용해 Service Discovery를 구현했습니다.
- 그 외에도 이커머스에 콜센터, AI 챗봇, 사용자 추천 기능을 구현하기 위해 AWS Connect, Lex, Personalize 등의 서비스를 사용했습니다.
- Hybrid Cold DR 전략을 사용하여, On-Premise 환경은 Synology NAS로 설정하고, AWS RDS 스냅샷을 AWS S3 버킷과 On-Premise에 각각 저장하는 방식으로 구현했습니다.

**[역할]**
- 팀장 역할 수행, Service 개발 및 배포 팀 소속
- AWS EKS 내 아키텍처 설계 및 구현
- GitHub Actions & ArgoCD & Kustomize를 활용한 CI/CD 파이프라인 구축

#### **[Architecture]**
![Architecture](https://github.com/user-attachments/assets/19bbe38c-6a64-4460-a7aa-30ea1619be74)

#### **[EKS Architecture]**
![EKS Architecture](https://github.com/user-attachments/assets/01f15585-5c2b-46d7-baa1-8b9e97f2164f)

#### **[CI/CD Pipeline]**
![CICD](https://github.com/user-attachments/assets/2313b2df-ff10-408f-a545-dfc248fc1feb)

#### **[시연 영상]**
https://github.com/user-attachments/assets/a18f9b9d-745c-41b4-8bbb-14b9cd15c827

#### **[부하 테스트 영상]**
https://github.com/user-attachments/assets/4d065bf1-e29b-4e9b-af49-12fe510ad696





**[GitHub Link]** : https://github.com/cloudwave-cloudladder-DevOps


&nbsp;  

### Online Shop 개발 미니 프로젝트 
24.09.02 - 24.09.06 (1주) , 팀원 4명 (Frontend - 2명, Backend - 2명) 

<br>
<br>

**[프로젝트 개요]**
- 간식거리를 판매하는 가상의 Online Shop을 개발해보는 미니 프로젝트입니다.
- Frontend는 HTML, CSS, JS, BootStrap을 이용해 개발했습니다.
- Backend는 Spring Boot + Spring Security + Spring JPA + QueryDSL을 이용해 API 서버를 개발했습니다.
- 주 기능으로는 회원 가입, 조회, 수정, 로그인, 로그아웃, 주문(즉시 구매, 장바구니에서 구매), 주문 조회, 상품 등록(이미지와 함께 등록), 장바구니 조회, 수량 수정, 삭제 기능 등이 있습니다.
- 회원 가입, 수정 시 이메일 인증 기능 등 실제 쇼핑몰과 최대한 유사하게 개발해보는 것이 프로젝트 목표입니다.
- 실제 운영 환경으로 배포는 진행하지 않았습니다.

**[역할]**
- Backend 개발

**[예시 이미지]**
![main1](https://github.com/user-attachments/assets/123eefcf-4a04-4c3d-ad5d-fc4f8a7688d6)
![main2](https://github.com/user-attachments/assets/5fd14253-f4a2-45f6-b400-3f63cfb80dfc)
![화면 예시1](https://github.com/user-attachments/assets/70223615-8cc8-4a8d-a7f5-3658faca71a8)

**[GitHub Link]** : https://github.com/TeamGansik
<br>
**[BLOG Link]**: https://velog.io/@jhs99126/series/Mini-Project  (현재 수정 중에 있습니다.)
&nbsp;  


### 📙 Education
- 인천대학교 정보기술대학 컴퓨터공학부 학사졸업  / 18.03.05 – 24.02.16
- CJ 올리브네트웍스 주관 KDT 교육 CloudWave 2기 수료(우수 교육생 선발) / 23.12.18 - 24.02.29


### 💼 Internship
- CJ 올리브네트웍스 송도 IDC 센터 (Infra Tech Lab) / 24.07.01 - 24.07.19
- CloudWave 2기 우수 수료생 특전으로 인턴십 프로젝트 진행

### 💳 Certification
- SQL개발자(SQLD) (23.07.17)
- 정보처리기사 (23.06.09)



