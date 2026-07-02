📦 Order App
OutSystems 11을 활용한 주문 현황 관리 시스템
📖 프로젝트 소개

Order App은 OutSystems 11을 활용하여 개발한 주문 현황 관리 시스템입니다.

사용자가 주문 정보를 한 화면에서 확인하고 관리할 수 있도록 주문 목록, 최근 주문, 검색 기능을 제공하며, 주문 상태를 색상으로 구분하여 직관적인 사용자 경험(UI/UX)을 구현하였습니다.

OutSystems의 Entity, Aggregate, Client Action, Navigation, Style Classes를 활용하여 데이터 조회와 화면 구성을 구현하였습니다.

🛠 Tech Stack
Category	Technology
Platform	OutSystems 11
Database	OutSystems Entity (Relational Database)
Data Query	Aggregate
Logic	Client Action
UI	OutSystems Reactive Web
Styling	CSS Style Classes
📅 Project Information
항목	내용
프로젝트	Order App
개발 형태	개인 프로젝트
개발 인원	1명
개발 환경	OutSystems 11
🎯 프로젝트 목표
OutSystems 11을 활용한 주문 관리 시스템 구현
Entity를 활용한 데이터 모델 설계
Aggregate를 이용한 주문 데이터 조회
직관적인 주문 현황 Dashboard 구현
사용자 친화적인 UI 구성
✨ 주요 기능
📋 주문 목록 조회
전체 주문 목록 표시
상품명
고객명
주문 금액
주문 상태
🔍 주문 검색
상품명을 입력하여 주문 검색
검색 결과 즉시 조회
📦 최근 주문 표시
최근 등록된 주문 정보를 별도 카드 형태로 제공
📊 주문 건수 표시
전체 주문 수 Dashboard 제공
🎨 주문 상태 표시

주문 상태에 따라 Style Class를 적용하여 시각적으로 구분

상태	표시
완료	🟢 초록
배송중	🟡 노랑
준비중	🔵 파랑
💰 금액 표시
천 단위 콤마 적용
원(₩) 단위 표시

예시

89,000원

320,000원

158,000원
🗄 Data Model
Order
Attribute	Description
Id	주문번호
Product	상품명
Customer	고객명
Amount	주문금액
Status	주문상태
🔨 구현 내용
Entity를 활용한 데이터 모델 설계
Aggregate를 이용한 주문 조회
Aggregate 정렬 기능 적용
Search 기능 구현
Client Action을 활용한 검색 로직 구현
Screen Navigation 구성
Expression을 활용한 금액 포맷 적용
Dynamic Style Classes를 활용한 상태별 UI 구현
Container를 활용한 Dashboard 레이아웃 구성
🖥 화면 구성
메인 Dashboard
주문 현황 요약
주문 건수 표시
주문 목록
최근 주문
검색 기능
