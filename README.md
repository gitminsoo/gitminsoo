<div align="center">
  <img
    src="https://capsule-render.vercel.app/api?type=transparent&color=0:4ae881,100:3d67e6&height=160&text=Nice%20to,%20gitminsoo&fontColor=3d67e6&fontSize=58&animation=fadeIn"
    alt="Nice to, gitminsoo"
  />
</div>

<div align="center">

### Edge-to-Cloud Infrastructure Engineer

임베디드 시스템 연구에서 쌓은 구조 설계 경험을 바탕으로,  
**엣지 환경부터 AWS 클라우드까지 연결되는 인프라를 설계하고 자동화합니다.**

</div>

---

## Core Focus

- Raspberry Pi·K3s 기반 엣지 고가용성(HA) 환경 설계
- AWS IoT Core → Lambda → DynamoDB·S3 데이터 파이프라인 구축
- Terraform·Ansible 기반 Infrastructure as Code
- Kubernetes·Argo CD 기반 GitOps 및 운영 자동화
- 장애 대응, 관측성, 비용 효율을 함께 고려하는 인프라 설계
- AI·센서 데이터를 활용한 스마트팩토리 위험 관제

---

## Tech Stack

### Cloud & Infrastructure

<p>
  <img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white" alt="AWS">
  <img src="https://img.shields.io/badge/Terraform-151515?style=for-the-badge&logo=terraform&logoColor=7B42BC" alt="Terraform">
  <img src="https://img.shields.io/badge/Kubernetes-151515?style=for-the-badge&logo=kubernetes&logoColor=326CE5" alt="Kubernetes">
  <img src="https://img.shields.io/badge/Docker-151515?style=for-the-badge&logo=docker&logoColor=2496ED" alt="Docker">
  <img src="https://img.shields.io/badge/Argo_CD-151515?style=for-the-badge&logo=argo&logoColor=EF7B4D" alt="Argo CD">
  <img src="https://img.shields.io/badge/Ansible-151515?style=for-the-badge&logo=ansible&logoColor=EE0000" alt="Ansible">
</p>

### Edge, Data & AI

<p>
  <img src="https://img.shields.io/badge/Python-151515?style=for-the-badge&logo=python&logoColor=3776AB" alt="Python">
  <img src="https://img.shields.io/badge/Linux-151515?style=for-the-badge&logo=linux&logoColor=FCC624" alt="Linux">
  <img src="https://img.shields.io/badge/Raspberry_Pi-151515?style=for-the-badge&logo=raspberrypi&logoColor=A22846" alt="Raspberry Pi">
  <img src="https://img.shields.io/badge/Prometheus-151515?style=for-the-badge&logo=prometheus&logoColor=E6522C" alt="Prometheus">
  <img src="https://img.shields.io/badge/Grafana-151515?style=for-the-badge&logo=grafana&logoColor=F46800" alt="Grafana">
  <img src="https://img.shields.io/badge/Vertex_AI-151515?style=for-the-badge&logo=googlecloud&logoColor=4285F4" alt="Vertex AI">
</p>

---

## Featured Projects

### 1. Aegis-Pi Risk Twin — Multi-Factory Risk Observability Platform

단일 폐쇄망 엣지 시스템을 **AWS 기반 멀티 공장 실시간 위험 관제 플랫폼**으로 확장한 팀 프로젝트입니다.  
**메가존클라우드 MSP 솔루션 아키텍트 양성과정 최우수팀 수상**

- Raspberry Pi 기반 `factory-a/b/c` 엣지 환경 및 Tailscale Hub-Spoke 제어망 구성
- Terraform으로 AWS Foundation·Hub·Data Pipeline 인프라 구축
- AWS IoT Core → Lambda → DynamoDB·S3 E2E 파이프라인 구현
- 공장별 Risk Score를 `안전 / 주의 / 위험` 상태로 산출
- Slack 위험 알림 및 Bedrock 기반 Daily Factory Report MVP 구현
- Hub 상시 운영 비용을 **$0.26~0.30/hr**로 최적화

**My Role:** Edge · Management VPC · Data Pipeline 전반  
**Stack:** AWS, Terraform, Ansible, K3s, Argo CD, IoT Core, Lambda, DynamoDB, S3, Bedrock

---

### 2. Safe-Edge Blackbox — HA Edge Data Preservation System

산업 현장 사고로 장비가 파손되더라도 사고 직전 데이터를 안전 구역에 보존하기 위한  
**Raspberry Pi 기반 3-Node K3s HA 엣지 블랙박스** 개인 프로젝트입니다.  
**메가존클라우드 MSP 솔루션 아키텍트 양성과정 최우수상 수상**

- Safe / Buffer / Danger Zone으로 물리적 위험 구역 분리
- K3s HA 클러스터와 Active-Standby Failover 구조 설계
- Longhorn 분산 스토리지 기반 InfluxDB 데이터 동기 복제
- YOLOv8·YAMNet·BME280 기반 멀티모달 위험 감지 통합
- `tolerationSeconds: 30` 기반 장애 감지 및 Failover 설계
- 산업용 서버 대비 하드웨어 비용 **90% 이상 절감**

**Result:** RPO 0초 · RTO 2분 이내 목표 HA 설계  
**My Role:** 아키텍처 설계부터 구현·검증까지 전 범위 단독 수행  
**Stack:** K3s, Kubernetes, Longhorn, Docker, InfluxDB, Prometheus, Grafana, Python

---

### 3. LawMainRoad — AI Contract Risk Analysis

외국인 근로자가 근로계약서의 위험 조항을 확인할 수 있도록 돕는 AI 법률 지원 MVP 팀 프로젝트입니다.  
**제5회 고용노동 공공데이터 AI 활용 공모전 출품**

- Vertex AI Gemini를 활용한 계약서 이미지 OCR 구현
- 비정형 계약서 내용을 표준 JSON 스키마로 구조화
- 조항별 위험 신호 탐색 및 확인 필요 항목 정리
- 약 15건의 테스트셋에서 독소조항 탐지 정확도 **60% → 90%** 개선

**My Role:** 계약서 OCR · 위험조항 탐색 · JSON 구조화  
**Stack:** Python, Vertex AI Gemini

---

## Research & Certification

- SCIE 국제 저널 제1저자 논문 6편
- 석사 졸업논문: 엣지 학습 기반 교통량 예측 및 적응형 인프라 제어
- AWS Certified Solutions Architect – Associate
- 정보처리기사 · 네트워크관리사 2급

---

## GitHub Stats

<div align="center">
  <img
    src="https://github-readme-stats.vercel.app/api?username=gitminsoo&show_icons=true&theme=transparent&hide_border=true&title_color=3d67e6&icon_color=4ae881&text_color=6b7280"
    height="165"
    alt="GitHub Stats"
  />
  <img
    src="https://github-readme-stats.vercel.app/api/top-langs/?username=gitminsoo&layout=compact&theme=transparent&hide_border=true&title_color=3d67e6&text_color=6b7280"
    height="165"
    alt="Top Languages"
  />
</div>

---

## Contact

<p>
  <a href="mailto:minsukim0919@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white" alt="Email">
  </a>
  <a href="https://minsooport.notion.site/3958af48a8dd8063b950e2b995cfd248">
    <img src="https://img.shields.io/badge/Portfolio-000000?style=flat&logo=notion&logoColor=white" alt="Portfolio">
  </a>
</p>
