# 전기차 제조데이터 플랫폼 구축 과제 (KIAT)

본 문서는 **전기차 파워트레인 제조 밸류체인의 탄력성 확보를 위한 정형·비정형 데이터 기반 협업 및 AI 서비스 플랫폼 개발 과제**의 기록 및 소개를 목적으로 작성되었습니다. 이 과제는 제조 현장에서 발생하는 데이터를 효과적으로 공유하고, 협업을 촉진하여 전기차 밸류체인의 경쟁력을 강화하는 데 초점을 두고 있습니다.

---

## 📌 플랫폼 컨셉 및 구성

### 1. 협업 특화 메신저 기반 플랫폼 (MaaP: Messenger as a Platform)
- 밸류체인 내 필수 공유 데이터(PQCD)의 영향을 반영하며, 다양한 정보화 수준을 가진 밸류체인 기업들 간 효과적인 협업 지원.
- **통합 커뮤니케이션 인프라**로서의 역할 수행.

![Messenger as a Platform](https://github.com/user-attachments/assets/9f67bcd9-708f-4c49-9abf-43b1bd8eecf9)

---

### 2. 밸류체인 PQCD 데이터 공유 서비스
- 제조 밸류체인 PQCD 정형∙비정형 데이터를 기반으로 한 서비스 기능 구조.

![PQCD Service Structure](https://github.com/user-attachments/assets/26a67ab6-214c-4fdd-9d8c-b3ec29ea00b8)

---

### 3. AUTODA(데이터 공유 플랫폼) 구성
- **데이터 수집 및 저장**을 위한 메신저 플랫폼과 **관리·분석**을 위한 소프트웨어 서비스.
- 업스트림 및 다운스트림 모두 사용할 수 있는 공급망 협업 시스템.
- 기존 레거시 시스템과의 빠른 연동 지원.

![AUTODA 구성도](https://github.com/user-attachments/assets/29d1abe3-bcd2-4e27-bdf3-e5ae76204524)

#### 주요 서비스:
- **대시보드**, **채팅**, **생산 모니터링**, **What-if Simulator**, **Work Manager**, **클레이독스**, **관계망 서비스** 등.

![AUTODA 랜딩 페이지](https://github.com/user-attachments/assets/785f06cd-83f1-422c-a608-a014516ceba5)

---

## 🛠 주요 서비스 내용

### 1. Dash Board
- 제조 현장의 PQCD 핵심 데이터를 기반으로 한 종합 관제 Monitoring Board.
- 정형 및 비정형 데이터의 시각적 표현과 데이터 분석 제공.

![Dash Board](https://github.com/user-attachments/assets/8e1dffde-5a7a-4f46-b2cb-b6be1e4e5025)

---

### 2. PQCD 생산일보 조회
- 생산 활동 데이터를 디지털로 관리하며, 업체 간 공유를 통해 PQCD 관리.

![생산일보 조회](https://github.com/user-attachments/assets/737a2c84-6fa0-4e35-8846-69afcb32d526)

---

### 3. 밸류체인 스마트 제조 운영 종합 모니터링
- 실시간 물류/생산 흐름을 표현하여 데이터 기반 의사결정 지원.

![밸류체인 모니터링](https://github.com/user-attachments/assets/848f8c69-40d8-486e-b943-80cf22ff04bc)

---

### 4. 이상감지 3종 알람 서비스
- **OTD Early Warning**: 계획 실적 대비 일일 목표치 미달 시 알림.
- **물류 품질 이상**: 협력사 4M 변경품 입고 시 알림.
- **설비 이상**: 설비 이상 징후 및 고장 발생 시 알림.

![이상감지 알람](https://github.com/user-attachments/assets/26e2038c-54bd-4ef8-9a63-989d180628e7)

---

### 5. AI 분석 서비스
- 자연어, 이미지, 문서 데이터를 분석하여 주요 콘텐츠를 식별 및 알림.

![AI 분석 서비스](https://github.com/user-attachments/assets/300a999b-d644-43ad-8100-20edf6471a36)

---

### 6. What-if Simulator
- 디지털 트윈 기반으로 기업 모델을 구축하여 생산 시뮬레이션 수행.

![What-if Simulator](https://github.com/user-attachments/assets/2b8d0c13-70a0-4b8d-99a7-d445489f57a0)

---

### 7. Work Manager (업무 협업 서비스)
- 프로젝트 및 산출물 관리 기능 제공.

![Work Manager](https://github.com/user-attachments/assets/8ee87b08-8550-4747-99d4-e626a45bd6bb)

---

### 8. Claydox (성적서 통합관리 서비스)
- 시험 성적서 작성 및 데이터 통합 관리 기능 제공.

![Claydox 작성 기능](https://github.com/user-attachments/assets/aa36c327-6455-41d5-a1e3-0a61666a4c99)

![Claydox 성적서](https://github.com/user-attachments/assets/f68edb37-b8e7-462d-a0e6-2fa9d0a96dd2)

---

### 9. 관계망 서비스
- 기업 간 거래 구조를 네트워크 형식으로 시각화.

![관계망 서비스](https://github.com/user-attachments/assets/9d9677e3-5c1c-44bb-90f5-9a91ab4bb806)

---

### 10. 협업 메신저
- 사용자 초대 및 그룹 방 생성, 채팅, 조직 관리 기능 제공.

![협업 메신저](https://github.com/user-attachments/assets/01c60563-fc39-4475-837d-75ea85b6f032)

---

### 11. API 모듈 및 스마트 데이터 허브 시스템
- 타 시스템과의 연동이 가능한 다양한 API 제공.

![API 모듈](https://github.com/user-attachments/assets/bfe04679-b104-4020-9c92-c2a5ee8bfd89)

---

