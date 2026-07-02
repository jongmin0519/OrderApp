# 📦 Order App

> **OutSystems 11을 활용한 주문 현황 관리 시스템**

## 📖 프로젝트 소개

Order App은 **OutSystems 11**을 활용하여 개발한 주문 현황 관리 시스템입니다.

주문 정보를 한 화면에서 효율적으로 관리할 수 있도록 주문 목록 조회, 최근 주문 확인, 검색 기능을 구현하였으며, 주문 상태를 색상으로 구분하여 직관적인 사용자 경험(UI/UX)을 제공하도록 개발하였습니다.

또한 OutSystems의 **Entity**, **Aggregate**, **Client Action**, **Navigation**, **Style Classes**를 활용하여 데이터 조회 및 화면 구성을 구현하였습니다.

---

## 🛠 Tech Stack

| Category | Technology |
|----------|------------|
| Platform | OutSystems 11 |
| Database | OutSystems Entity |
| Data Query | Aggregate |
| Logic | Client Action |
| UI | Reactive Web |
| Styling | CSS Style Classes |

---

## 📅 Project Information

| 항목 | 내용 |
|------|------|
| 프로젝트명 | Order App |
| 개발 형태 | 개인 프로젝트 |
| 개발 인원 | 1명 |
| 개발 환경 | OutSystems 11 |

---

## 🎯 주요 기능

- 📋 주문 목록 조회
- 🔍 주문 검색
- 📦 최근 주문 확인
- 📊 전체 주문 건수 표시
- 🎨 주문 상태별 색상 표시
- 💰 주문 금액 천 단위(,) 표시

---

## 📌 주문 상태

| 상태 | UI |
|------|----|
| 완료 | 🟢 Green Badge |
| 배송중 | 🟡 Yellow Badge |
| 준비중 | 🔵 Blue Badge |

---

## 🗄 Data Model

### Order Entity

| Attribute | Description |
|-----------|-------------|
| Id | 주문 번호 |
| Product | 상품명 |
| Customer | 고객명 |
| Amount | 주문 금액 |
| Status | 주문 상태 |

---

## 🔨 구현 내용

- Entity를 활용한 데이터 모델 설계
- Aggregate를 활용한 주문 데이터 조회
- Aggregate 정렬(Sorting) 기능 구현
- Client Action을 활용한 검색 기능 구현
- Screen Navigation 구성
- Expression을 활용한 금액 포맷 적용
- Dynamic Style Classes를 활용한 상태별 UI 구현
- Dashboard 형태의 화면 구성

---

## 🖥 화면 구성

### 메인 화면

- 주문 현황 Dashboard
- 전체 주문 건수 표시
- 주문 목록(Table)
- 최근 주문(Card)
- 상품 검색 기능

> 프로젝트 실행 화면
<img width="1687" height="884" alt="오늘한거1" src="https://github.com/user-attachments/assets/02d3f911-b82e-43a6-90dd-bb2ed618900d" />

<img width="1680" height="711" alt="오늘한거2" src="https://github.com/user-attachments/assets/3081df38-dbcd-4650-b471-38866433e918" />
